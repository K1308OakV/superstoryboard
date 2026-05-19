# Batman Teaser Sequence 01 Render Sheet

## Sequence Identity

**Sequence:** S01 - Arkham Blackout / First Fear Reveal  
**Placement:** One selected sequence inside the teaser trailer, not the entire teaser.  
**Target Length:** 16-20 seconds for this sequence slice.  
**Production Goal:** Create a locked set of still keyframes first, then animate only the approved cuts.  
**Primary Feeling:** The criminals think they control Arkham; the dark proves Batman does.

This render sheet turns the approved storyboard bible into production shots. It is written for a board artist, image generator, video generator, or editor. It should be used before spending credits on moving clips.

## Non-Negotiables

- Batman's first reveal is a black armored death-knight silhouette with no active glowing optics.
- Batman's night-vision close-up happens later, already active, as tactical escalation.
- Female Two-Face's burned-half duality reveal is in this sequence.
- The burn origin is not explained, dramatized, or depicted.
- The goons are diverse, represented naturally, and unified by shared red / half-face paint markings.
- Firearms are allowed and important; muzzle flashes are the main readable action light.
- Lightning is used sparingly for major silhouette punctuation.
- Batman is brutal but non-lethal.
- The location is Arkham exterior transfer courtyard / service exit, unless later replaced by a better Arkham exterior-interior hybrid.

## Render Pass Strategy

### Pass 0 - Character Model Sheets

Before rendering story shots, create character model sheets for:

1. Batman armored suit, inactive optics.
2. Batman armored suit, night-vision optics active.
3. Female Two-Face, composed side / concealed burn.
4. Female Two-Face, burned-half reveal.
5. Painted goon lineup with visible diversity.
6. Elevated rifle threat / sniper silhouette.

These sheets lock proportions, costume, markings, face language, and render rules so later shots do not drift.

### Pass 1 - Still Keyframes Only

Render these seven keyframes first:

1. `S01_KF01_arkham_procession`
2. `S01_KF02_female_twoface_profile`
3. `S01_KF03_burned_half_reveal`
4. `S01_KF04_blackout_batman_silhouette`
5. `S01_KF05_first_gunfire_disarm`
6. `S01_KF06_nightvision_closeup`
7. `S01_KF07_batarang_upward_throw`

Only after these are approved should we generate video clips or a timed animatic.

### Pass 2 - Trailer Motion Clips

Animate only approved stills:

- One short atmosphere/procession clip.
- One duality reveal clip.
- One Batman silhouette / blackout clip.
- One compact fight burst.
- One batarang throw button.

## Sequence Cut Sheet

### S01_C001 - Arkham Rain Establishing

**Duration:** 1.5s  
**Frame Type:** Wide keyframe, optional slow push.  
**Camera:** Low wide angle across wet concrete, Arkham walls and barred service gate in frame.  
**Action:** Painted goons move as a controlled group through rain. Some hold firearms low.  
**Lighting:** Security lights and floodlights still functioning; red emergency accents in background.  
**Purpose:** Establish Arkham, crew size, weather, and criminal procession.

**Keyframe Prompt:**

```text
wide low-angle view of Arkham Asylum transfer courtyard at night in heavy rain, wet concrete reflections, barred service gate, brutal institutional walls, diverse criminal crew moving in formation, white Black Hispanic Indian and other backgrounds, shared red and half-face paint markings, tactical street clothing, firearms held low, cinematic noir atmosphere, premium gritty Japanese action anime keyframe, sharp cel shading, hard ink shadows, red emergency glow, no caricature
```

**Negative Prompt:**

```text
photorealism, comedy, clean daylight, cute proportions, fantasy castle, police procedural flat lighting, ethnic caricature, gore, overlit background
```

**Review Criteria:**

- Arkham reads immediately.
- Goons read as a group, not a random crowd.
- Diversity is visible without turning anyone into a stereotype.
- Rain and reflections are strong.

### S01_C002 - Female Two-Face Leads

**Duration:** 1.5s  
**Frame Type:** Medium profile keyframe.  
**Camera:** Side profile / three-quarter rear, slightly below eye level.  
**Action:** Female Two-Face leads the group, holding a frame. Her burned side is hidden by angle, hair, shadow, or the frame.  
**Lighting:** Still controlled, with security lights catching rain and formal fabric.  
**Purpose:** Introduce authority and conceal duality.

**Keyframe Prompt:**

```text
formal blonde crime leader woman late 30s to early 40s, medium shoulder-length hair, elegant severe posture, leading armed painted goons through rain-soaked Arkham courtyard, holding a frame object, seen in side profile and three-quarter rear so one side of face is hidden by hair shadow and framing, formal attire wet from rain, controlled menace, cinematic noir atmosphere, premium gritty Japanese action anime rendering, sharp cel shading, hard ink linework, wet reflections
```

**Negative Prompt:**

```text
full face reveal, smiling glamour portrait, comedic villain, revealing both sides too early, gore, exaggerated anime schoolgirl design, oversexualized pose
```

**Review Criteria:**

- She feels like the leader.
- Her hidden side is genuinely concealed.
- She feels elegant, severe, and dangerous.
- The frame object is visible but not over-explained.

### S01_C003 - Duality Hint

**Duration:** 1.0s  
**Frame Type:** Insert / reflection keyframe.  
**Camera:** Tight insert on the frame glass, puddle reflection, or angled shadow on her face.  
**Action:** A distorted hint of the hidden side appears, but not the full reveal.  
**Lighting:** Flicker from failing Arkham lights.  
**Purpose:** Tell the audience there is something wrong beneath the controlled image.

**Keyframe Prompt:**

```text
tight cinematic insert, rain drops on a frame glass or puddle reflection, distorted partial reflection of formal blonde crime leader, one side still hidden, red paint streaks and Arkham light flicker, psychological duality hinted but not fully revealed, heavy noir shadows, premium gritty Japanese anime keyframe, hard cel shading, sharp ink lines, wet reflective surface
```

**Negative Prompt:**

```text
clear full face, explicit injury origin, gore, horror splatter, bright clean reflection, readable text on frame
```

**Review Criteria:**

- The shot hints at duality without giving everything away.
- It feels intentional, not confusing.
- It can be cut quickly in a trailer.

### S01_C004 - Burned Half Reveal

**Duration:** 1.0s  
**Frame Type:** Medium close-up keyframe.  
**Camera:** Hard angle shift or lightning/flicker reveal.  
**Action:** Her burned half is revealed for the first time. She remains composed.  
**Lighting:** Flickering security light or lightning edge light; rain streaks across frame.  
**Purpose:** Make Female Two-Face's visual identity part of the teaser.

**Keyframe Prompt:**

```text
formal blonde Female Two-Face crime leader in rain, late 30s to early 40s, composed severe expression, camera angle finally reveals burned half of face, other half elegant and controlled, no origin shown, tragic duality and menace, Arkham courtyard at night, flickering security light and rain streaks, premium gritty Japanese action anime keyframe, respectful non-exploitative framing, sharp cel shading, hard ink shadows
```

**Negative Prompt:**

```text
self-harm depiction, injury origin, gore focus, medical close-up, parody, beauty glamour shot, exaggerated monster face, comedic expression
```

**Review Criteria:**

- Duality is clear.
- The burn is visible but not exploitative.
- She still feels powerful, not pathetic.

### S01_C005 - Blackout

**Duration:** 1.0s  
**Frame Type:** Wide-to-medium transition keyframe.  
**Camera:** Behind Female Two-Face, looking toward the darkened courtyard.  
**Action:** Lights cut out. Goons raise weapons. Female Two-Face freezes.  
**Lighting:** Security lights dead; only red emergency spill and wet reflections remain.  
**Purpose:** Hand control of the scene to darkness.

**Keyframe Prompt:**

```text
behind formal blonde Female Two-Face in rain-soaked Arkham courtyard as the lights suddenly cut out, painted armed goons raising firearms into darkness, red emergency glow barely reflecting on wet concrete, heavy black negative space, tense frozen moment, cinematic noir, premium gritty Japanese action anime keyframe, hard cel shadows, sharp ink linework
```

**Negative Prompt:**

```text
bright visibility, clean hero lighting, daylight, calm crowd, empty courtyard, comedy, no weapons
```

**Review Criteria:**

- The blackout is readable.
- The frame creates dread.
- Female Two-Face remains visually present without stealing Batman's reveal.

### S01_C006 - Batman Death-Knight Silhouette

**Duration:** 1.5s  
**Frame Type:** Hero silhouette keyframe.  
**Camera:** Low angle, partially obscured by rain and muzzle flash haze.  
**Action:** Batman appears as a black armored silhouette. No active optic glow.  
**Lighting:** One lightning strike or gunfire burst outlines armor and cape.  
**Purpose:** First Batman image. Fear before tech.

**Keyframe Prompt:**

```text
black armored Batman-like vigilante appears as a death-knight silhouette in rain and darkness, no glowing eye optics yet, short cowl ears, broad tactical armor, heavy cape mass, gauntlets, futuristic knight presence, outlined by one burst of lightning and distant muzzle flash haze, Arkham courtyard, terrifying stillness, premium gritty Japanese action anime keyframe, sharp cel shading, hard ink shadows, heavy negative space
```

**Negative Prompt:**

```text
glowing eyes, clean superhero pose, smiling, bright background, fantasy demon, horned monster, photorealistic cosplay, toy armor, cute proportions
```

**Review Criteria:**

- Batman reads as Batman without overexposing suit details.
- Optics are not active.
- The silhouette is frightening.

### S01_C007 - First Gunfire Disarm

**Duration:** 2.0s  
**Frame Type:** Action keyframe / video candidate.  
**Camera:** Medium close, violent diagonal composition.  
**Action:** A goon fires into the dark; muzzle flash reveals Batman's gauntlet knocking the rifle aside.  
**Lighting:** Muzzle flash is the main light source.  
**Purpose:** Start the fight with clarity and force.

**Keyframe Prompt:**

```text
close medium anime action keyframe, armed painted goon firing automatic weapon into darkness, bright muzzle flash lighting rain and wet concrete, black armored vigilante gauntlet enters frame and knocks rifle upward, cape smear in background, red paint streaks on goon, brutal non-lethal disarm, Arkham courtyard, premium gritty Japanese action anime, sharp cel shading, hard ink shadows, orange-white impact flash
```

**Negative Prompt:**

```text
blood spray, lethal gunshot impact, comedic slapstick, clear daylight, soft blurry action, rubbery 3D, superhero posing
```

**Review Criteria:**

- Action is readable in one frame.
- Muzzle flash lights the composition.
- Batman's brutality is non-lethal.

### S01_C008 - Night-Vision Close-Up

**Duration:** 1.5s  
**Frame Type:** Close-up keyframe.  
**Camera:** Tight face/cowl close-up, backlit.  
**Action:** Batman's night-vision optics are already active. He looks through darkness toward the elevated threat.  
**Lighting:** Dark background, minimal distractions, rim light and rain.  
**Purpose:** Tactical escalation.

**Keyframe Prompt:**

```text
tight close-up of black armored vigilante cowl in rain, short cowl ears partly out of frame, night-vision optics already active with controlled glow, backlit by faint red emergency rim light, background almost black with minimal lights, wet armor texture, tactical focus, premium gritty Japanese action anime keyframe, sharp cel shading, hard ink shadows, no activation mechanism shown
```

**Negative Prompt:**

```text
activation animation, too many background lights, bright city skyline, smiling face, exposed human eyes, toy helmet, photorealistic cosplay, cute anime face
```

**Review Criteria:**

- This is clearly later than the first silhouette reveal.
- Optics feel tactical, not decorative.
- Background is clean and dark.

### S01_C009 - Fight Burst Montage

**Duration:** 3.0s  
**Frame Type:** Multi-action clip candidate.  
**Camera:** Fast medium shots, close inserts, and diagonal cuts.  
**Action:** Batman moves through gunfire, strips weapons, throws one attacker into another, cape arcs through flashes.  
**Lighting:** Muzzle flashes dominate; one lightning punctuation at most.  
**Purpose:** Sell the trailer's raw action.

**Keyframe Prompt:**

```text
fragmented brutal non-lethal Batman fight in rain-soaked Arkham courtyard, black armored vigilante pivots through automatic gunfire, strips rifle from painted goon, throws one attacker into another, heavy cape arc through muzzle flashes, wet concrete exploding with rain, red paint smears, diverse armed goons, premium gritty Japanese action anime montage keyframe, speed smears, impact holds, hard cel shadows, sharp ink linework
```

**Negative Prompt:**

```text
gore, killing, blood pools, comedy fight, unreadable blur, clean daylight, western comic flat color, rubbery 3D animation, ethnic caricature
```

**Review Criteria:**

- The fight feels intense, professional, and controlled.
- Batman's silhouette stays consistent.
- It is dark but still readable because of gunfire.

### S01_C010 - Threat Above

**Duration:** 1.5s  
**Frame Type:** POV / over-shoulder keyframe.  
**Camera:** Batman POV or over-cowl angle toward an upper Arkham platform.  
**Action:** A thin red laser or elevated rifle threat becomes readable.  
**Lighting:** Night-vision logic; red laser haze in rain.  
**Purpose:** Justify the upward batarang throw.

**Keyframe Prompt:**

```text
over-shoulder view from black armored vigilante toward upper Arkham platform in rain, thin red rifle laser visible through darkness and rain haze, elevated shooter barely seen, night-vision tactical framing, wet metal railings, red laser reflection on rain drops, premium gritty Japanese action anime keyframe, hard shadows, sharp ink lines, noir atmosphere
```

**Negative Prompt:**

```text
clear bright sniper portrait, daylight, sci-fi HUD clutter, comedy, giant laser beam, overexposed platform
```

**Review Criteria:**

- Audience understands there is a threat above.
- The optics from C008 logically matter.
- The red laser is thin and dangerous, not cartoonish.

### S01_C011 - Batarang Upward Button

**Duration:** 2.0s  
**Frame Type:** Trailer button keyframe / video candidate.  
**Camera:** Slow-motion follow on batarang rising through rain.  
**Action:** Batman throws the batarang upward toward the elevated threat.  
**Lighting:** Muzzle-flash residue, red laser haze, rain, and one controlled lightning edge.  
**Purpose:** End Sequence 01 with a sharp trailer hook.

**Keyframe Prompt:**

```text
slow-motion anime trailer button, black armored vigilante throws batarang upward through rain toward elevated rifle threat, camera follows spinning batarang through red laser haze and muzzle-flash smoke, Arkham courtyard below in darkness, wet reflections, cape trailing behind Batman, premium gritty Japanese action anime keyframe, sharp cel shading, hard ink shadows, dramatic motion lines, cinematic noir
```

**Negative Prompt:**

```text
boomerang toy, comedy, bright daylight, gore, explosion overload, unreadable motion blur, superhero poster pose
```

**Review Criteria:**

- The throw feels like a trailer endpoint.
- The target direction is clear.
- The image makes the viewer want the next shot.

## First Render Batch

Do not render all eleven shots first.

Render this first batch only:

| Priority | Keyframe | Why |
| --- | --- | --- |
| 1 | S01_C006 Batman Death-Knight Silhouette | If Batman's first image fails, the sequence fails. |
| 2 | S01_C008 Night-Vision Close-Up | Confirms suit tech and face design. |
| 3 | S01_C004 Burned Half Reveal | Confirms Female Two-Face's teaser identity. |
| 4 | S01_C001 Arkham Rain Establishing | Confirms location and group representation. |
| 5 | S01_C007 First Gunfire Disarm | Confirms action readability in darkness. |
| 6 | S01_C011 Batarang Upward Button | Confirms trailer ending image. |

Only after those six land should C002, C003, C005, C009, and C010 be generated or animated.

## Approval Checklist

Before video generation, answer yes to all:

- Does Batman read as a Batman-inspired armored vigilante, not a generic monster?
- Does the first Batman silhouette avoid active glowing optics?
- Does the night-vision close-up feel like a later tactical escalation?
- Does Female Two-Face's burned-half reveal read clearly without exploiting the injury?
- Does the goon group show visible, respectful diversity?
- Is gunfire doing useful lighting work?
- Is the scene dark but readable?
- Does the batarang button feel like a teaser hook?

If any answer is no, revise still prompts before spending video credits.
