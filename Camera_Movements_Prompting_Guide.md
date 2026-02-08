# Camera Movements & Cinematic Prompting Guide

> **A complete reference for AI filmmakers**
> *How to describe every camera movement in your prompts for Runway, Sora, Kling, Veo, and other AI video generators.*

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

"Camera pans right, following a car driving along a coastal road at sunset"

"Gentle pan from an empty chair to a window with rain streaming down"
```

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

"Slow tilt down from storm clouds to a lone figure walking through an open field"

"Tilt up along a skyscraper facade, floor by floor, until reaching the rooftop"
```

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

> **Dolly vs Zoom:** A dolly changes *perspective* (parallax shifts, background changes). A zoom only magnifies. AI models respond to both terms differently — `"dolly in"` tends to produce more cinematic parallax than `"zoom in"`.

---

### 4.4 Tracking / Lateral Move

**What it is:** Camera moves sideways alongside the subject, maintaining framing. Like walking next to someone.

**Emotional effect:** Journey, movement, companionship, observational.

**Prompt examples:**

```
"Tracking shot moving alongside a man jogging through a city street at dawn"

"Lateral tracking shot following a woman as she walks through a crowded market"

"Camera slides left to right past a row of old photographs on a mantel"

"Side-scrolling tracking shot through a futuristic corridor with neon lights"
```

---

### 4.5 Crane / Boom / Jib

**What it is:** Camera rises or descends vertically while maintaining a horizontal view, often combined with lateral movement. Grand, sweeping vertical motion.

**Emotional effect:** Grandeur, revelation, transition between ground and aerial perspective.

**Prompt examples:**

```
"Crane shot rising from street level up above the rooftops to reveal the entire city skyline"

"Camera descends from above the treetops down through the canopy to find a cabin in the woods"

"Boom up from a kneeling figure, rising to reveal an army assembled behind them"

"Crane shot lifting from a couple on a beach up into the sky, the coastline stretching into the distance"
```

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

"Dramatic zoom out from an eye to reveal the face, then the room, then the building from outside"

"Quick crash zoom into the subject's face as they hear the news"

"Subtle zoom in during a monologue, tightening from medium shot to close-up"
```

---

### 4.7 Orbit / Arc

**What it is:** Camera moves in a circular path around the subject, keeping the subject centered.

**Emotional effect:** Reveals all sides, heightens drama, creates a sense of circling or entrapment, visual dynamism.

**Prompt examples:**

```
"Camera slowly orbits around a statue in a dark museum, dramatic side-lighting"

"360-degree orbit around two people facing each other in an argument"

"Arc shot circling a lone warrior standing on a hilltop, wind blowing, golden hour light"

"Camera orbits a table of evidence, each piece revealed as the camera passes"
```

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

"Documentary-style handheld close-up of a street musician performing"

"Shaky handheld shot of a crowd pushing forward, chaotic and claustrophobic"

"Raw handheld footage of a soldier moving through rubble, unsteady and tense"
```

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

"Vertigo effect on a woman's face, background distorting as the camera pushes in and zooms out simultaneously"

"Hitchcock zoom on a figure at the edge of a cliff, the landscape warping with unease"
```

> **Note:** This is one of the harder effects for AI models. Try multiple generations and be explicit about the background distortion.

---

### 4.11 Whip Pan / Swish Pan

**What it is:** Extremely fast horizontal pan that blurs the frame between two points — often used as a transition.

**Emotional effect:** Energy, surprise, transition, comedic timing, temporal jump.

**Prompt examples:**

```
"Whip pan from a character looking left to reveal a figure standing in the doorway"

"Fast swish pan from the clock on the wall to the window, motion blur between"

"Whip pan transition — starting on a sunrise, blurring, landing on a moonlit scene"
```

---

### 4.12 Roll / Dutch Roll

**What it is:** Camera rotates along its own axis (like a barrel roll). The horizon line tilts.

**Emotional effect:** Disorientation, dream/nightmare, drug effects, surrealism, zero gravity.

**Prompt examples:**

```
"Camera slowly rolls clockwise as a character falls through a dreamlike void"

"Gradual dutch roll tilting the horizon as the world becomes increasingly surreal"

"Camera barrel rolls as a spaceship enters zero gravity, objects floating"
```

---

### 4.13 Static / Locked-Off

**What it is:** Camera does not move at all. Fixed frame. All movement comes from within the scene.

**Emotional effect:** Observation, tension through stillness, theatrical, letting the scene breathe.

**Prompt examples:**

```
"Static wide shot of an empty room — a door slowly opens and a figure enters"

"Locked-off camera on a park bench, people passing by in different seasons"

"Fixed frame medium shot of a face, the only movement is a single tear falling"

"Completely still camera, wide shot of a landscape — clouds moving, light changing"
```

> **Pro tip:** Static shots are the most reliable for AI models — fewer motion artifacts, more consistent quality.

---

### 4.14 Flyover / Aerial

**What it is:** Camera moves high above the ground, flying over landscapes, cities, or environments. Drone-like perspective.

**Emotional effect:** Scale, majesty, establishing, freedom, journey.

**Prompt examples:**

```
"Aerial flyover of a mountain range at golden hour, moving forward through clouds"

"Drone shot flying low over ocean waves at sunset, moving toward the horizon"

"Bird's eye aerial tracking a river through dense forest canopy"

"Sweeping aerial shot circling a medieval castle on a cliff, fog in the valley below"
```

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

"POV shot looking down at hands opening an old letter, trembling slightly"

"First person perspective of running through a forest, branches whipping past"

"POV from inside a car, driving down an empty highway at night, dashboard visible"
```

---

### 4.16 Follow Shot

**What it is:** Camera follows behind a subject as they move through space — we see their back or partial profile.

**Emotional effect:** Journey, mystery (we can't see their face), destination-focused, narrative momentum.

**Prompt examples:**

```
"Camera follows behind a cloaked figure walking through a narrow medieval alley"

"Follow shot trailing a child running through a field of tall grass"

"Behind-the-back follow shot of an astronaut floating through a space station corridor"

"Close follow shot behind a woman's head as she pushes through a crowd"
```

---

### 4.17 Rack Focus Pull

**What it is:** Focus shifts between foreground and background elements within the same shot, without camera movement.

**Emotional effect:** Reveals, connects two elements, shifts attention, creates depth.

**Prompt examples:**

```
"Rack focus from a blurry flower in the foreground to a sharp figure standing in the distance"

"Focus pull from a close-up of a ring on the table to the person sitting behind it"

"Shallow depth of field, focus shifts from the window raindrops to the face reflected in the glass"

"Rack focus between two characters — one sharp, one blurry — swapping as the conversation shifts"
```

---

### 4.18 One-Take / Long Take (Oner)

**What it is:** An extended continuous shot with no cuts — the camera moves fluidly through an entire scene.

**Emotional effect:** Immersion, real-time tension, virtuosity, unbroken reality.

**Prompt examples:**

```
"One continuous shot following a character from the street through a door, up stairs, and into a room"

"Unbroken long take gliding through a ballroom — past dancers, musicians, and servers"

"Single-take shot starting on a close-up, pulling back to wide, then pushing into another character"
```

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

**Intimate Character Moment:**
```
"Close-up, eye level, gentle dolly in.
85mm lens, shallow depth of field, warm bokeh.
A woman's face as she reads a letter, subtle emotion crossing her features.
Sitting at a wooden kitchen table by a window.
Soft golden afternoon light streaming in, dust particles floating.
Very slow, contemplative."
```

**Action Sequence:**
```
"Medium shot, slightly low angle, fast tracking shot moving alongside.
Wide angle lens, deep focus.
A man sprinting through a neon-lit alley, splashing through puddles.
Cyberpunk city at night, rain falling.
Harsh neon pink and blue reflections on wet pavement.
Fast-paced, urgent energy."
```

**Establishing Grandeur:**
```
"Extreme wide shot, aerial flyover, slow forward movement.
Ultra-wide lens, everything in focus.
Vast mountain range with a winding river cutting through the valley.
Dawn, first light hitting the peaks.
Golden and purple sky, mist in the valleys.
Majestic, slow glide forward."
```

**Psychological Tension:**
```
"Medium close-up, dutch angle, static camera.
50mm lens, shallow DOF.
A man staring at a ringing phone on a desk, not picking it up.
Sparse office, single desk lamp.
Harsh single-source light from the lamp, deep shadows on face.
Still, no movement except a subtle eye twitch."
```

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
