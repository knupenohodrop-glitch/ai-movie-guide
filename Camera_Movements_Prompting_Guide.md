# Camera Movements & Cinematic Prompting Guide

> **A complete reference for AI filmmakers**
> *How to describe every camera movement in your prompts for Runway, Sora, Kling, Veo, and other AI video generators.*
>
> 📂 **This guide includes video samples!** Look for the 🎬 links throughout — each points to a sample `.mp4` in the [`samples/`](samples/) folder generated with Veo3 and MiniMax.

---

## Table of Contents

- [1. Why Camera Language Matters](#1-why-camera-language-matters)
- [2. Shot Types (Distance)](#2-shot-types-distance)
- [3. Camera Angles](#3-camera-angles)
- [4. Camera Movements](#4-camera-movements)
  - [4.1 Pan](#41-pan)
  - [4.2 Tilt](#42-tilt)
  - [4.3 Dolly / Push / Pull](#43-dolly--push--pull)
  - [4.4 Tracking / Lateral Move](#44-tracking--lateral-move)
  - [4.5 Crane / Boom / Jib](#45-crane--boom--jib)
  - [4.6 Zoom](#46-zoom)
  - [4.7 Orbit / Arc](#47-orbit--arc)
  - [4.8 Steadicam / Gimbal](#48-steadicam--gimbal)
  - [4.9 Handheld](#49-handheld)
  - [4.10 Dolly Zoom (Vertigo Effect)](#410-dolly-zoom-vertigo-effect)
  - [4.11 Whip Pan / Swish Pan](#411-whip-pan--swish-pan)
  - [4.12 Roll / Dutch Roll](#412-roll--dutch-roll)
  - [4.13 Static / Locked-Off](#413-static--locked-off)
  - [4.14 Flyover / Aerial](#414-flyover--aerial)
  - [4.15 First Person / POV](#415-first-person--pov)
  - [4.16 Follow Shot](#416-follow-shot)
  - [4.17 Rack Focus Pull](#417-rack-focus-pull)
  - [4.18 One-Take / Long Take (Oner)](#418-one-take--long-take-oner)
- [5. Lens & Depth of Field](#5-lens--depth-of-field)
- [6. Combining Movements in Prompts](#6-combining-movements-in-prompts)
- [7. Model-Specific Tips](#7-model-specific-tips)
- [8. Quick Reference Table](#8-quick-reference-table)
- [9. Scene-Based Prompt Templates](#9-scene-based-prompt-templates)

---

## 1. Why Camera Language Matters

AI video models respond dramatically better to **precise cinematographic language** than to vague descriptions. The difference:

| Approach | Prompt | Result Quality |
|----------|--------|----------------|
| Vague | *"A cool shot of a woman in a city"* | Random, unpredictable framing |
| Specific | *"Medium close-up, slow dolly in on a woman standing on a rain-soaked street at night, shallow depth of field, warm streetlight glow"* | Controlled, cinematic output |

**The formula** (from Paul Trillo's method):

```
[Shot type] + [Camera movement] + [Subject action] + [Lighting/mood] + [Temporal pacing]
```

> Always describe what the **camera sees and does** — not what the character feels.

---

## 2. Shot Types (Distance)

The distance between the camera and the subject sets the emotional tone of every frame.

| Shot Type | Abbreviation | What It Shows | Emotional Effect | Prompt Language |
|-----------|-------------|---------------|------------------|-----------------|
| **Extreme Wide Shot** | EWS | Full landscape, subject tiny or invisible | Isolation, scale, establishing world | `"extreme wide shot of..."`, `"vast landscape showing..."` |
| **Wide Shot / Establishing Shot** | WS | Full environment with subject visible | Context, location, scene-setting | `"wide establishing shot of..."`, `"full wide shot of..."` |
| **Full Shot** | FS | Subject head to toe | Action, body language | `"full body shot of..."`, `"full shot showing..."` |
| **Medium Wide / Cowboy Shot** | MWS | Subject from mid-thigh up | Movement + context | `"cowboy shot of..."`, `"medium wide framing..."` |
| **Medium Shot** | MS | Subject from waist up | Neutral, conversational | `"medium shot of..."`, `"waist-up framing of..."` |
| **Medium Close-Up** | MCU | Subject from chest up | Intimacy begins | `"medium close-up of..."`, `"chest-up shot of..."` |
| **Close-Up** | CU | Face fills the frame | Emotion, detail, intensity | `"close-up of..."`, `"tight shot on face..."` |
| **Extreme Close-Up** | ECU | Single feature (eye, hand, object) | Maximum intensity, micro-detail | `"extreme close-up of..."`, `"macro shot of..."` |
| **Insert Shot** | INS | Detail of an object or action | Narrative information | `"insert shot of..."`, `"detail shot showing..."` |
| **Over-the-Shoulder** | OTS | Subject framed past another's shoulder | Dialogue, connection | `"over-the-shoulder shot of..."`, `"OTS framing..."` |
| **Two Shot** | 2S | Two subjects in frame | Relationship, dialogue | `"two shot of..."`, `"both characters in frame..."` |

---

## 3. Camera Angles

The vertical angle of the camera changes power dynamics and mood.

| Angle | Description | Emotional Effect | Prompt Language |
|-------|-------------|------------------|-----------------|
| **Eye Level** | Camera at subject's eye height | Neutral, natural, relatable | `"eye-level shot..."`, `"straight-on angle..."` |
| **Low Angle** | Camera looks up at subject | Power, dominance, heroism | `"low angle shot looking up at..."`, `"from below..."` |
| **High Angle** | Camera looks down at subject | Vulnerability, smallness, weakness | `"high angle shot looking down on..."`, `"from above..."` |
| **Bird's Eye / Top-Down** | Camera directly above | God-like perspective, pattern, geography | `"top-down shot of..."`, `"bird's eye view of..."`, `"directly overhead..."` |
| **Worm's Eye** | Camera on the ground looking straight up | Extreme power, awe, distortion | `"worm's eye view of..."`, `"ground-level looking straight up..."` |
| **Dutch Angle / Canted** | Camera tilted on its axis | Unease, tension, disorientation | `"dutch angle shot of..."`, `"tilted frame..."`, `"canted angle..."` |
| **Over-the-Top** | Camera placed above and behind subject | Surveillance, observation | `"looking over the subject from behind and above..."` |

---

## 4. Camera Movements

### 4.1 Pan

**What it is:** Camera rotates horizontally on a fixed point (left to right or right to left). The tripod stays still — only the head turns.

**Emotional effect:** Reveals environment, follows action, creates spatial awareness.

**Prompt examples:**

```
"Slow pan left across a dimly lit jazz club, revealing musicians one by one"
```
> 🎬 [**Video sample**](samples/freepik_slow-pan-left-across-a-dimly-lit-jazz-club-reveali_veo3_1_720p_16-9_24fps_16326.mp4)

```
"Camera pans right, following a car driving along a coastal road at sunset"
```
> 🎬 [**Video sample**](samples/freepik_camera-pans-right-following-a-car-driving-along-a-_veo3_1_720p_16-9_24fps_16325.mp4)

```
"Gentle pan from an empty chair to a window with rain streaming down"
```
> 🎬 [**Video sample**](samples/freepik_gentle-pan-from-an-empty-chair-to-a-window-with-ra_veo3_1_720p_16-9_24fps_16324.mp4)

**Speed variations:**
- `"slow pan"` — contemplative, observational
- `"smooth pan"` — neutral, controlled
- `"fast pan"` — urgent, searching (see also Whip Pan)

---

### 4.2 Tilt

**What it is:** Camera rotates vertically on a fixed point (up or down). Like nodding.

**Emotional effect:** Reveals height/scale, shifts focus between ground and sky, dramatic reveal.

**Prompt examples:**

```
"Camera tilts up from muddy boots on the ground to reveal a cowboy standing against the sunset sky"
```
> 🎬 [**Video sample**](samples/freepik_camera-tilts-up-from-muddy-boots-on-the-ground-to-_veo3_1_720p_16-9_24fps_16323.mp4)

```
"Slow tilt down from storm clouds to a lone figure walking through an open field"
```

```
"Tilt up along a skyscraper facade, floor by floor, until reaching the rooftop"
```
> 🎬 [**Video sample**](samples/freepik_tilt-up-along-a-skyscraper-facade-floor-by-floor-u_veo3_1_720p_16-9_24fps_16322.mp4)

**Speed variations:**
- `"slow tilt up"` — builds anticipation, reveals gradually
- `"smooth tilt down"` — descent, grounding

---

### 4.3 Dolly / Push / Pull

**What it is:** The entire camera physically moves toward (dolly in / push in) or away from (dolly out / pull back) the subject.

**Emotional effect:**
- **Dolly in:** Increasing intimacy, focus, tension, entering a character's world
- **Dolly out / Pull back:** Reveal, context, isolation, distancing

**Prompt examples:**

```
"Slow dolly in toward a woman sitting alone at a candlelit table, her expression slowly becoming visible"

"Camera pushes in on a detective's face as realization dawns"

"Slow pull back from a child's face to reveal the vast empty playground behind her"

"Dolly out from a close-up of hands typing to reveal a massive control room"
```
> 🎬 [**Video sample — Dolly in close-up**](samples/freepik_closeup-eye-level-gentle-dolly-in85mm-lens-shallow_veo3_1_720p_16-9_24fps_16265.mp4)

> 🎬 [**Video sample — Dolly in on woman in rain**](samples/freepik_medium-closeup-slow-dolly-in-on-a-woman-standing-o_veo3_1_720p_16-9_24fps_16327.mp4)

> **Dolly vs Zoom:** A dolly changes *perspective* (parallax shifts, background changes). A zoom only magnifies. AI models respond to both terms differently — `"dolly in"` tends to produce more cinematic parallax than `"zoom in"`.

---

### 4.4 Tracking / Lateral Move

**What it is:** Camera moves sideways alongside the subject, maintaining framing. Like walking next to someone.

**Emotional effect:** Journey, movement, companionship, observational.

**Prompt examples:**

```
"Tracking shot moving alongside a man jogging through a city street at dawn"
```
> 🎬 [**Video sample**](samples/freepik_tracking-shot-moving-alongside-a-man-jogging-throu_veo3_1_720p_16-9_24fps_16321.mp4)

```
"Lateral tracking shot following a woman as she walks through a crowded market"
```
> 🎬 [**Video sample**](samples/freepik_lateral-tracking-shot-following-a-woman-as-she-wal_veo3_1_720p_16-9_24fps_16320.mp4)

```
"Camera slides left to right past a row of old photographs on a mantel"
```
> 🎬 [**Video sample**](samples/freepik_camera-slides-left-to-right-past-a-row-of-old-phot_veo3_1_720p_16-9_24fps_16319.mp4)

```
"Side-scrolling tracking shot through a futuristic corridor with neon lights"
```
> 🎬 [**Video sample**](samples/freepik_sidescrolling-tracking-shot-through-a-futuristic-c_veo3_1_720p_16-9_24fps_16318.mp4)

---

### 4.5 Crane / Boom / Jib

**What it is:** Camera rises or descends vertically while maintaining a horizontal view, often combined with lateral movement. Grand, sweeping vertical motion.

**Emotional effect:** Grandeur, revelation, transition between ground and aerial perspective.

**Prompt examples:**

```
"Crane shot rising from street level up above the rooftops to reveal the entire city skyline"
```
> 🎬 [**Video sample**](samples/freepik_crane-shot-rising-from-street-level-up-above-the-r_veo3_1_720p_16-9_24fps_16317.mp4)

```
"Camera descends from above the treetops down through the canopy to find a cabin in the woods"
```
> 🎬 [**Video sample**](samples/freepik_camera-descends-from-above-the-treetops-down-throu_veo3_1_720p_16-9_24fps_16381.mp4)

```
"Boom up from a kneeling figure, rising to reveal an army assembled behind them"
```
> 🎬 [**Video sample**](samples/freepik_boom-up-from-a-kneeling-figure-rising-to-reveal-an_veo3_1_720p_16-9_24fps_16315.mp4)

```
"Crane shot lifting from a couple on a beach up into the sky, the coastline stretching into the distance"
```
> 🎬 [**Video sample**](samples/freepik_crane-shot-lifting-from-a-couple-on-a-beach-up-int_veo3_1_720p_16-9_24fps_16314.mp4)

---

### 4.6 Zoom

**What it is:** Lens focal length changes — magnifying (zoom in) or widening (zoom out) without moving the camera body.

**Emotional effect:**
- **Zoom in:** Sudden focus, emphasis, shock, discovery
- **Zoom out:** Reveal, disorientation, context shift
- **Crash zoom:** Comedic or dramatic punch

**Prompt examples:**

```
"Slow zoom in on a letter lying on a desk, the handwriting gradually becoming legible"
```
> 🎬 [**Video sample**](samples/freepik_slow-zoom-in-on-a-letter-lying-on-a-desk-the-handw_veo3_1_720p_16-9_24fps_16313.mp4)

```
"Dramatic zoom out from an eye to reveal the face, then the room, then the building from outside"
```
> 🎬 [**Video sample**](samples/freepik_dramatic-zoom-out-from-an-eye-to-reveal-the-face-t_veo3_1_720p_16-9_24fps_16312.mp4)

```
"Quick crash zoom into the subject's face as they hear the news"
```
> 🎬 [**Video sample**](samples/freepik_quick-crash-zoom-into-the-subjects-face-as-they-he_veo3_1_720p_16-9_24fps_16311.mp4)

```
"Subtle zoom in during a monologue, tightening from medium shot to close-up"
```
> 🎬 [**Video sample**](samples/freepik_subtle-zoom-in-during-a-monologue-tightening-from-_veo3_1_720p_16-9_24fps_16310.mp4)

---

### 4.7 Orbit / Arc

**What it is:** Camera moves in a circular path around the subject, keeping the subject centered.

**Emotional effect:** Reveals all sides, heightens drama, creates a sense of circling or entrapment, visual dynamism.

**Prompt examples:**

```
"Camera slowly orbits around a statue in a dark museum, dramatic side-lighting"
```
> 🎬 [**Video sample**](samples/freepik_camera-slowly-orbits-around-a-statue-in-a-dark-mus_veo3_1_720p_16-9_24fps_16309.mp4)

```
"360-degree orbit around two people facing each other in an argument"
```
> 🎬 [**Video sample**](samples/freepik_360degree-orbit-around-two-people-facing-each-othe_veo3_1_720p_16-9_24fps_16308.mp4)

```
"Arc shot circling a lone warrior standing on a hilltop, wind blowing, golden hour light"
```
> 🎬 [**Video sample**](samples/freepik_arc-shot-circling-a-lone-warrior-standing-on-a-hil_veo3_1_720p_16-9_24fps_16307.mp4)

```
"Camera orbits a table of evidence, each piece revealed as the camera passes"
```
> 🎬 [**Video sample**](samples/freepik_camera-orbits-a-table-of-evidence-each-piece-revea_veo3_1_720p_16-9_24fps_16306.mp4)

**Partial vs full:**
- `"half orbit"` or `"180-degree arc"` — reveals the other side
- `"full 360 orbit"` — complete revolution around subject

---

### 4.8 Steadicam / Gimbal

**What it is:** Camera moves freely through space with smooth stabilization — following subjects through doors, down hallways, across rooms. No shake.

**Emotional effect:** Immersive, fluid, dreamlike, following the character's journey intimately.

**Prompt examples:**

```
"Steadicam shot following a waiter through a busy restaurant kitchen, weaving between cooks"

"Smooth gimbal shot trailing behind a character as they walk down a long dimly lit corridor"

"Stabilized tracking shot following a dancer across a stage in one continuous motion"

"Steadicam glide through an empty mansion, room to room, dust floating in the light"
```

---

### 4.9 Handheld

**What it is:** Camera held by operator without stabilization — natural shake and movement.

**Emotional effect:** Raw, urgent, documentary, intimate, chaotic, authentic.

**Prompt examples:**

```
"Handheld camera following a person running through a dark forest, shaky and urgent"
```
> 🎬 [**Video sample**](samples/freepik_handheld-camera-following-a-person-running-through_veo3_1_720p_16-9_24fps_16305.mp4)

```
"Documentary-style handheld close-up of a street musician performing"
```
> 🎬 [**Video sample**](samples/freepik_documentarystyle-handheld-closeup-of-a-street-musi_veo3_1_720p_16-9_24fps_16304.mp4)

```
"Shaky handheld shot of a crowd pushing forward, chaotic and claustrophobic"
```
> 🎬 [**Video sample**](samples/freepik_shaky-handheld-shot-of-a-crowd-pushing-forward-cha_veo3_1_720p_16-9_24fps_16303.mp4)

```
"Raw handheld footage of a soldier moving through rubble, unsteady and tense"
```
> 🎬 [**Video sample**](samples/freepik_raw-handheld-footage-of-a-soldier-moving-through-r_veo3_1_720p_16-9_24fps_16302.mp4)

**Intensity control:**
- `"gentle handheld"` — subtle, natural breathing motion
- `"shaky handheld"` — intense, chaotic
- `"documentary handheld"` — observational, present

---

### 4.10 Dolly Zoom (Vertigo Effect)

**What it is:** Camera dollies in while zooming out (or vice versa). The subject stays the same size but the background warps dramatically.

**Also called:** Vertigo shot, Hitchcock zoom, trombone shot, zolly.

**Emotional effect:** Disorientation, realization, dread, psychological shift.

**Prompt examples:**

```
"Dolly zoom on a man standing in a hallway — the walls stretch and warp behind him as he remains fixed"
```
> 🎬 [**Video sample**](samples/freepik_dolly-zoom-on-a-man-standing-in-a-hallway-the-wall_veo3_1_720p_16-9_24fps_16301.mp4)

```
"Vertigo effect on a woman's face, background distorting as the camera pushes in and zooms out simultaneously"
```
> 🎬 [**Video sample**](samples/freepik_vertigo-effect-on-a-womans-face-background-distort_veo3_1_720p_16-9_24fps_16300.mp4)

```
"Hitchcock zoom on a figure at the edge of a cliff, the landscape warping with unease"
```
> 🎬 [**Video sample**](samples/freepik_hitchcock-zoom-on-a-figure-at-the-edge-of-a-cliff-_veo3_1_720p_16-9_24fps_16299.mp4)

> **Note:** This is one of the harder effects for AI models. Try multiple generations and be explicit about the background distortion.

---

### 4.11 Whip Pan / Swish Pan

**What it is:** Extremely fast horizontal pan that blurs the frame between two points — often used as a transition.

**Emotional effect:** Energy, surprise, transition, comedic timing, temporal jump.

**Prompt examples:**

```
"Whip pan from a character looking left to reveal a figure standing in the doorway"
```
> 🎬 [**Video sample**](samples/freepik_whip-pan-from-a-character-looking-left-to-reveal-a_veo3_1_720p_16-9_24fps_16298.mp4)

```
"Fast swish pan from the clock on the wall to the window, motion blur between"
```
> 🎬 [**Video sample**](samples/freepik_fast-swish-pan-from-the-clock-on-the-wall-to-the-w_veo3_1_720p_16-9_24fps_16297.mp4)

```
"Whip pan transition — starting on a sunrise, blurring, landing on a moonlit scene"
```
> 🎬 [**Video sample**](samples/freepik_whip-pan-transition-starting-on-a-sunrise-blurring_veo3_1_720p_16-9_24fps_16296.mp4)

---

### 4.12 Roll / Dutch Roll

**What it is:** Camera rotates along its own axis (like a barrel roll). The horizon line tilts.

**Emotional effect:** Disorientation, dream/nightmare, drug effects, surrealism, zero gravity.

**Prompt examples:**

```
"Camera slowly rolls clockwise as a character falls through a dreamlike void"
```
> 🎬 [**Video sample**](samples/freepik_camera-slowly-rolls-clockwise-as-a-character-falls_veo3_1_720p_16-9_24fps_16295.mp4)

```
"Gradual dutch roll tilting the horizon as the world becomes increasingly surreal"
```
> 🎬 [**Video sample**](samples/freepik_gradual-dutch-roll-tilting-the-horizon-as-the-worl_veo3_1_720p_16-9_24fps_16294.mp4)

```
"Camera barrel rolls as a spaceship enters zero gravity, objects floating"
```
> 🎬 [**Video sample**](samples/freepik_camera-barrel-rolls-as-a-spaceship-enters-zero-gra_veo3_1_720p_16-9_24fps_16293.mp4)

---

### 4.13 Static / Locked-Off

**What it is:** Camera does not move at all. Fixed frame. All movement comes from within the scene.

**Emotional effect:** Observation, tension through stillness, theatrical, letting the scene breathe.

**Prompt examples:**

```
"Static wide shot of an empty room — a door slowly opens and a figure enters"
```
> 🎬 [**Video sample**](samples/freepik_static-wide-shot-of-an-empty-room-a-door-slowly-op_veo3_1_720p_16-9_24fps_16292.mp4)

```
"Locked-off camera on a park bench, people passing by in different seasons"
```
> 🎬 [**Video sample**](samples/freepik_lockedoff-camera-on-a-park-bench-people-passing-by_veo3_1_720p_16-9_24fps_16290.mp4)

```
"Fixed frame medium shot of a face, the only movement is a single tear falling"
```
> 🎬 [**Video sample**](samples/freepik_fixed-frame-medium-shot-of-a-face-the-only-movemen_veo3_1_720p_16-9_24fps_16289.mp4)

```
"Completely still camera, wide shot of a landscape — clouds moving, light changing"
```
> 🎬 [**Video sample**](samples/freepik_completely-still-camera-wide-shot-of-a-landscape-c_veo3_1_720p_16-9_24fps_16288.mp4)

> **Pro tip:** Static shots are the most reliable for AI models — fewer motion artifacts, more consistent quality.

---

### 4.14 Flyover / Aerial

**What it is:** Camera moves high above the ground, flying over landscapes, cities, or environments. Drone-like perspective.

**Emotional effect:** Scale, majesty, establishing, freedom, journey.

**Prompt examples:**

```
"Aerial flyover of a mountain range at golden hour, moving forward through clouds"
```
> 🎬 [**Video sample**](samples/freepik_aerial-flyover-of-a-mountain-range-at-golden-hour-_veo3_1_720p_16-9_24fps_16287.mp4)

```
"Drone shot flying low over ocean waves at sunset, moving toward the horizon"
```
> 🎬 [**Video sample**](samples/freepik_drone-shot-flying-low-over-ocean-waves-at-sunset-m_veo3_1_720p_16-9_24fps_16286.mp4)

```
"Bird's eye aerial tracking a river through dense forest canopy"
```
> 🎬 [**Video sample**](samples/freepik_birds-eye-aerial-tracking-a-river-through-dense-fo_veo3_1_720p_16-9_24fps_16375.mp4)

```
"Sweeping aerial shot circling a medieval castle on a cliff, fog in the valley below"
```
> 🎬 [**Video sample**](samples/freepik_sweeping-aerial-shot-circling-a-medieval-castle-on_veo3_1_720p_16-9_24fps_16283.mp4)

**Height control:**
- `"high altitude aerial"` — far above, map-like
- `"low drone flyover"` — close to terrain, immersive
- `"ascending aerial"` — starting low, rising to reveal scale

---

### 4.15 First Person / POV

**What it is:** Camera represents the character's eyes — we see what they see.

**Emotional effect:** Immersion, vulnerability, horror, discovery, empathy.

**Prompt examples:**

```
"First person POV walking through a dark hallway, hands visible reaching for a door handle"
```
> 🎬 [**Video sample**](samples/freepik_first-person-pov-walking-through-a-dark-hallway-ha_veo3_1_720p_16-9_24fps_16282.mp4)

```
"POV shot looking down at hands opening an old letter, trembling slightly"
```
> 🎬 [**Video sample**](samples/freepik_pov-shot-looking-down-at-hands-opening-an-old-lett_veo3_1_720p_16-9_24fps_16281.mp4)

```
"First person perspective of running through a forest, branches whipping past"
```

```
"POV from inside a car, driving down an empty highway at night, dashboard visible"
```
> 🎬 [**Video sample**](samples/freepik_pov-from-inside-a-car-driving-down-an-empty-highwa_veo3_1_720p_16-9_24fps_16279.mp4)

---

### 4.16 Follow Shot

**What it is:** Camera follows behind a subject as they move through space — we see their back or partial profile.

**Emotional effect:** Journey, mystery (we can't see their face), destination-focused, narrative momentum.

**Prompt examples:**

```
"Camera follows behind a cloaked figure walking through a narrow medieval alley"
```
> 🎬 [**Video sample**](samples/freepik_camera-follows-behind-a-cloaked-figure-walking-thr_veo3_1_720p_16-9_24fps_16278.mp4)

```
"Follow shot trailing a child running through a field of tall grass"
```
> 🎬 [**Video sample**](samples/freepik_follow-shot-trailing-a-child-running-through-a-fie_veo3_1_720p_16-9_24fps_16374.mp4)

```
"Behind-the-back follow shot of an astronaut floating through a space station corridor"
```
> 🎬 [**Video sample**](samples/freepik_behindtheback-follow-shot-of-an-astronaut-floating_veo3_1_720p_16-9_24fps_16275.mp4)

```
"Close follow shot behind a woman's head as she pushes through a crowd"
```
> 🎬 [**Video sample**](samples/freepik_close-follow-shot-behind-a-womans-head-as-she-push_veo3_1_720p_16-9_24fps_16274.mp4)

---

### 4.17 Rack Focus Pull

**What it is:** Focus shifts between foreground and background elements within the same shot, without camera movement.

**Emotional effect:** Reveals, connects two elements, shifts attention, creates depth.

**Prompt examples:**

```
"Rack focus from a blurry flower in the foreground to a sharp figure standing in the distance"
```
> 🎬 [**Video sample**](samples/freepik_rack-focus-from-a-blurry-flower-in-the-foreground-_veo3_1_720p_16-9_24fps_16273.mp4)

```
"Focus pull from a close-up of a ring on the table to the person sitting behind it"
```
> 🎬 [**Video sample**](samples/freepik_focus-pull-from-a-closeup-of-a-ring-on-the-table-t_veo3_1_720p_16-9_24fps_16272.mp4)

```
"Shallow depth of field, focus shifts from the window raindrops to the face reflected in the glass"
```
> 🎬 [**Video sample**](samples/freepik_shallow-depth-of-field-focus-shifts-from-the-windo_veo3_1_720p_16-9_24fps_16271.mp4)

```
"Rack focus between two characters — one sharp, one blurry — swapping as the conversation shifts"
```
> 🎬 [**Video sample**](samples/freepik_rack-focus-between-two-characters-one-sharp-one-bl_veo3_1_720p_16-9_24fps_16270.mp4)

---

### 4.18 One-Take / Long Take (Oner)

**What it is:** An extended continuous shot with no cuts — the camera moves fluidly through an entire scene.

**Emotional effect:** Immersion, real-time tension, virtuosity, unbroken reality.

**Prompt examples:**

```
"One continuous shot following a character from the street through a door, up stairs, and into a room"
```
> 🎬 [**Video sample**](samples/freepik_one-continuous-shot-following-a-character-from-the_veo3_1_720p_16-9_24fps_16269.mp4)

```
"Unbroken long take gliding through a ballroom — past dancers, musicians, and servers"
```
> 🎬 [**Video sample**](samples/freepik_unbroken-long-take-gliding-through-a-ballroom-past_veo3_1_720p_16-9_24fps_16268.mp4)

```
"Single-take shot starting on a close-up, pulling back to wide, then pushing into another character"
```
> 🎬 [**Video sample**](samples/freepik_singletake-shot-starting-on-a-closeup-pulling-back_veo3_1_720p_16-9_24fps_16267.mp4)

> **Note:** True long takes are extremely challenging for AI. Keep them under 10 seconds and describe the path clearly.

---

## 5. Lens & Depth of Field

Lens choice affects how the audience perceives space, intimacy, and reality.

| Lens Type | Focal Length | Visual Effect | Prompt Language |
|-----------|-------------|---------------|-----------------|
| **Ultra Wide** | 14–24mm | Exaggerated perspective, distortion at edges, vast environments | `"ultra wide angle lens"`, `"fisheye perspective"` |
| **Wide** | 24–35mm | Natural wide view, slight distortion, good for environments | `"wide angle lens"`, `"35mm lens"` |
| **Normal** | 40–60mm | Closest to human eye, neutral, natural | `"50mm lens"`, `"natural perspective"` |
| **Telephoto** | 85–200mm | Compressed perspective, isolates subject, flattened background | `"telephoto lens"`, `"85mm portrait lens"`, `"compressed perspective"` |
| **Super Telephoto** | 200mm+ | Extreme compression, surveillance look, sports/wildlife | `"long telephoto lens"`, `"300mm lens"` |
| **Macro** | Macro | Extreme close-up detail, insects/textures/tiny objects | `"macro lens"`, `"extreme macro shot"` |
| **Anamorphic** | Various | Horizontal lens flares, oval bokeh, cinematic widescreen feel | `"anamorphic lens"`, `"anamorphic flares"`, `"2.39:1 aspect ratio"` |
| **Tilt-Shift** | Various | Miniature/toy effect or controlled plane of focus | `"tilt-shift lens"`, `"miniature effect"` |

### Depth of Field

| Setting | Visual Effect | Prompt Language |
|---------|---------------|-----------------|
| **Shallow DOF** | Subject sharp, background/foreground blurry (bokeh) | `"shallow depth of field"`, `"blurred background"`, `"bokeh"`, `"f/1.4"` |
| **Deep DOF** | Everything in focus, front to back | `"deep focus"`, `"everything in focus"`, `"f/11"` |
| **Split Diopter** | Two planes of focus simultaneously (foreground + background both sharp, middle blurry) | `"split diopter shot"`, `"dual focus planes"` |

---

## 6. Combining Movements in Prompts

The most cinematic shots combine multiple elements. Layer them in this order:

### The Layering Formula

```
1. Shot type (distance)
2. Camera angle
3. Camera movement
4. Lens/DOF
5. Subject description + action
6. Environment/Setting
7. Lighting/Mood
8. Speed/Pacing
```

### Examples of Layered Prompts

**Dramatic Reveal:**
```
"Wide shot, low angle, slow crane rising from ground level.
35mm lens, deep focus.
A lone figure stands at the base of a massive steel structure.
Industrial wasteland, overcast sky.
Cold blue-grey lighting with harsh overhead shadows.
Slow, deliberate pace."
```
> 🎬 [**Video sample**](samples/freepik_wide-shot-low-angle-slow-crane-rising-from-ground-_veo3_1_720p_16-9_24fps_16266.mp4)

**Intimate Character Moment:**
```
"Close-up, eye level, gentle dolly in.
85mm lens, shallow depth of field, warm bokeh.
A woman's face as she reads a letter, subtle emotion crossing her features.
Sitting at a wooden kitchen table by a window.
Soft golden afternoon light streaming in, dust particles floating.
Very slow, contemplative."
```
> 🎬 [**Video sample**](samples/freepik_closeup-eye-level-gentle-dolly-in85mm-lens-shallow_veo3_1_720p_16-9_24fps_16265.mp4)

**Action Sequence:**
```
"Medium shot, slightly low angle, fast tracking shot moving alongside.
Wide angle lens, deep focus.
A man sprinting through a neon-lit alley, splashing through puddles.
Cyberpunk city at night, rain falling.
Harsh neon pink and blue reflections on wet pavement.
Fast-paced, urgent energy."
```
> 🎬 [**Video sample**](samples/freepik_medium-shot-slightly-low-angle-fast-tracking-shot-_veo3_1_720p_16-9_24fps_16373.mp4)

**Establishing Grandeur:**
```
"Extreme wide shot, aerial flyover, slow forward movement.
Ultra-wide lens, everything in focus.
Vast mountain range with a winding river cutting through the valley.
Dawn, first light hitting the peaks.
Golden and purple sky, mist in the valleys.
Majestic, slow glide forward."
```
> 🎬 [**Video sample**](samples/freepik_extreme-wide-shot-aerial-flyover-slow-forward-move_veo3_1_720p_16-9_24fps_16260.mp4)

**Psychological Tension:**
```
"Medium close-up, dutch angle, static camera.
50mm lens, shallow DOF.
A man staring at a ringing phone on a desk, not picking it up.
Sparse office, single desk lamp.
Harsh single-source light from the lamp, deep shadows on face.
Still, no movement except a subtle eye twitch."
```
> 🎬 [**Video sample**](samples/freepik_medium-closeup-dutch-angle-static-camera50mm-lens-_veo3_1_720p_16-9_24fps_16259.mp4)

---

## 7. Model-Specific Tips

Different AI video models interpret camera language with varying accuracy.

### Runway (Gen-4 / Gen-4.5)

| Strength | Notes |
|----------|-------|
| Excellent style control | Very responsive to cinematic language |
| Good at image-to-video | Use a still frame + camera instruction for best results |
| Remix and iterate | Generate, then refine motion with re-generation |

**Best prompt approach:**
```
"Camera slowly dollies in on [subject], [lighting], [mood]. 
Shot on 35mm film, cinematic color grading."
```

### Sora (OpenAI)

| Strength | Notes |
|----------|-------|
| Best physics and realism | Understands complex multi-element scenes |
| Strong temporal coherence | Long shots hold together well |
| Expensive per generation | Make prompts count — be precise |

**Best prompt approach:**
```
"A [shot type] [camera movement] of [detailed subject + action] in [environment]. 
[Lighting]. [Mood]. Photorealistic, shot on cinema camera."
```

### Kling (2.6 / 3.0)

| Strength | Notes |
|----------|-------|
| Free daily credits | Great for volume and iteration |
| Multi-Shot storyboard mode | Chain sequences with consistent characters |
| Motion brush | Control motion in specific areas of the frame |
| Start/End frame support | Lock beginning and end for predictable camera paths |

**Best prompt approach:**
```
Use start and end frames for camera movement control.
Text prompts work best for describing subject action; 
use frame-to-frame for camera path.
```

### Veo (Google 3.1)

| Strength | Notes |
|----------|-------|
| Native 4K output | Best resolution output |
| Native audio generation | Sound comes with the video |
| Excellent camera motion | Very responsive to cinematographic terms |

**Best prompt approach:**
```
"Cinematic [camera movement], [shot type]. [Subject action] in [environment]. 
[Lighting description]. 4K, film grain, shallow depth of field."
```

---

## 8. Quick Reference Table

### All Camera Movements at a Glance

| Movement | Direction | Prompt Keywords | Best For |
|----------|-----------|-----------------|----------|
| **Pan** | Horizontal rotation (L/R) | `pan left`, `pan right`, `slow pan` | Revealing environments, following action |
| **Tilt** | Vertical rotation (up/down) | `tilt up`, `tilt down`, `slow tilt` | Revealing height, scale |
| **Dolly In** | Camera moves toward subject | `dolly in`, `push in`, `move closer` | Building intimacy, focus |
| **Dolly Out** | Camera moves away from subject | `dolly out`, `pull back`, `pull away` | Revealing context, isolation |
| **Tracking** | Camera moves sideways alongside | `tracking shot`, `lateral move`, `side track` | Following journeys, movement |
| **Crane Up** | Camera rises vertically | `crane up`, `rising shot`, `ascending` | Grandeur, reveal |
| **Crane Down** | Camera descends vertically | `crane down`, `descending shot` | Grounding, approaching |
| **Zoom In** | Lens magnifies (no camera move) | `zoom in`, `slow zoom`, `tighten frame` | Emphasis, discovery |
| **Zoom Out** | Lens widens | `zoom out`, `widen frame` | Reveal, context shift |
| **Orbit** | Camera circles subject | `orbit`, `arc shot`, `revolve around` | Drama, revealing all sides |
| **Steadicam** | Smooth free movement | `steadicam`, `smooth tracking`, `gliding` | Immersive following |
| **Handheld** | Unstabilized, natural shake | `handheld`, `shaky cam`, `documentary style` | Urgency, rawness |
| **Dolly Zoom** | Dolly + opposing zoom | `dolly zoom`, `vertigo effect`, `zolly` | Psychological shift |
| **Whip Pan** | Ultra-fast pan (blur) | `whip pan`, `swish pan`, `fast pan` | Transition, energy |
| **Roll** | Rotation on camera axis | `camera roll`, `barrel roll`, `dutch roll` | Disorientation, surrealism |
| **Static** | No movement | `static shot`, `locked-off`, `fixed camera` | Tension, observation |
| **Aerial** | High above, flying | `aerial shot`, `drone shot`, `flyover` | Scale, establishing |
| **POV** | Character's eyes | `first person`, `POV shot`, `subjective camera` | Immersion, horror |
| **Follow** | Behind the subject | `follow shot`, `behind the back`, `trailing` | Journey, mystery |
| **Rack Focus** | Focus shifts within frame | `rack focus`, `focus pull`, `shift focus` | Connecting elements |
| **Long Take** | Extended unbroken shot | `one continuous shot`, `long take`, `oner` | Real-time immersion |

---

## 9. Scene-Based Prompt Templates

### Opening / Establishing

```
"Slow aerial flyover of [location] at [time of day]. 
Camera glides forward, descending gradually toward [focal point]. 
Wide angle lens, deep focus. [Lighting/weather]. 
Cinematic, epic scale."
```

### Character Introduction

```
"Medium shot, eye level, slow dolly in. 
[Character description] standing/sitting in [environment]. 
85mm lens, shallow depth of field, warm bokeh. 
[Lighting]. Quiet, contemplative. 
Camera moves in slowly, revealing the details of their face."
```

### Dialogue Scene

```
"Over-the-shoulder shot, static camera. 
[Character A] in foreground (blurred shoulder), 
[Character B] in focus, speaking. 
50mm lens, shallow depth of field. 
[Interior/Exterior], [lighting]."
```

### Tension / Suspense

```
"Close-up, dutch angle, very slow dolly in. 
[Subject detail — hands, eyes, object]. 
Anamorphic lens, shallow DOF. 
Dark, single harsh light source from [direction]. 
Silence except for [ambient sound descriptor]. 
Very slow, almost imperceptible movement."
```

### Chase / Action

```
"Medium shot, handheld camera, fast tracking alongside. 
[Character] running through [environment]. 
Wide angle lens, deep focus, motion blur. 
[Lighting — neon, harsh sun, etc.]. 
Urgent pace, shaky camera. 
Heavy breathing pace."
```

### Emotional Climax

```
"Extreme close-up, eye level, static camera. 
[Character's] face fills the frame. 
85mm lens, very shallow depth of field. 
[Single tear / eyes closing / subtle expression change]. 
Soft, diffused light. 
Completely still. Let the performance carry."
```

### Reveal / Plot Twist

```
"Wide shot, slow crane rising from [starting subject]. 
Camera rises up and pulls back to reveal [the thing being revealed]. 
35mm lens, deep focus. 
[Dramatic lighting change]. 
Pacing starts slow, then accelerates as the reveal completes."
```

### Closing Shot

```
"Extreme wide shot, static or very slow dolly out. 
[Subject] small in the frame, [environment] dominating. 
50mm lens, deep focus. 
[Time of day], [mood-appropriate lighting]. 
Slow. Final. Lingering.
Cut to black."
```

---

> *"The camera is not just a recording device — it is a storytelling instrument.
> Every movement, every angle, every lens choice speaks to the audience,
> whether they're conscious of it or not."*

---

*Last updated: February 7, 2026*
*Companion document to [AI Film Hackathon Guide](AI_Film_Hackathon_Guide.md)*
