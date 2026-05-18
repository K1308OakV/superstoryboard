# agents.md

## storyboard_builder

This agent generates AI-assisted storyboards using the SuperStoryboard project.

```yaml
agents:
  - name: storyboard_builder
    description: |
      Generates storyboards from natural language descriptions using the SuperStoryboard
      Figma plugin and Supabase backend. Assumes the repository has been cloned,
      Supabase/Figma credentials are configured, and all required environment
      variables are set.
    working_directory: /workspace
    tools:
      - run
      - pip_install
      - npm_install
    steps:
      - name: Install dependencies
        run: |
          cd figma-plugin && npm install
          cd ../supabase/scripts && npm install
      - name: Build Figma plugin
        run: cd figma-plugin && npm run plugin:build && npm run ui:build
      - name: Start image generation backend
        run: cd supabase/functions && supabase functions serve process-image-generation
      - name: Start video generation backend
        run: cd supabase/functions && supabase functions serve process-video-generation
      - name: Generate storyboard assets
        run: |
          cd supabase/scripts
          deno run --allow-net --allow-env queue-trigger.ts batch-images test-prompts.json
```
