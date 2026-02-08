# 🎬 AI Film Hackathon — Complete Production Guide

> **NO TITLE AI Film Festival 2025**
> *Everything you need to create your AI-powered film. Tools, guides, specifications, and best practices — all in one place.*

---

## Table of Contents

- [1. Festival Rules](#1-festival-rules)
- [2. Film Specifications & Deliverables](#2-film-specifications--deliverables)
- [3. AI Tools Directory](#3-ai-tools-directory)
  - [3.1 Video Generation](#31-video-generation)
  - [3.2 Image Generation](#32-image-generation)
  - [3.3 Music & Audio](#33-music--audio)
  - [3.4 Voice & Narration](#34-voice--narration)
  - [3.5 Editing Tools](#35-editing-tools)
  - [3.6 Post-Production](#36-post-production)
  - [3.7 Upscaling & Enhancement](#37-upscaling--enhancement)
- [4. Expert Techniques & Masterclasses](#4-expert-techniques--masterclasses)
  - [4.1 Cinematic Prompting: The Paul Trillo Method](#41-cinematic-prompting-the-paul-trillo-method)
  - [4.2 Multi-Tool Orchestration: The Shy Kids Method](#42-multi-tool-orchestration-the-shy-kids-method)
  - [4.3 Character Consistency Workflow](#43-character-consistency-workflow)
  - [4.4 AI Storyboarding & Visual Pre-Production](#44-ai-storyboarding--visual-pre-production)
  - [4.5 Emotional Voice Direction with ElevenLabs](#45-emotional-voice-direction-with-elevenlabs)
  - [4.6 AI Music Production](#46-ai-music-production)
  - [4.7 Broadcast-Ready Upscaling with Topaz](#47-broadcast-ready-upscaling-with-topaz)
  - [4.8 Subtitle Workflow with Descript](#48-subtitle-workflow-with-descript)
- [5. Video Model Comparison](#5-video-model-comparison)
- [6. Competition Lessons & Speed Workflow](#6-competition-lessons--speed-workflow)
  - [6.1 48-Hour Speed Workflow Secrets](#61-48-hour-speed-workflow-secrets)
  - [6.2 Five Lessons from Gen:48 Veterans](#62-five-lessons-from-gen48-veterans)
  - [6.3 Solo Competitor Survival Guide](#63-solo-competitor-survival-guide)
- [7. Prompt Engineering Cheat Sheet](#7-prompt-engineering-cheat-sheet)
- [8. Production Pipeline — Quick Reference](#8-production-pipeline--quick-reference)

---

## 1. Festival Rules

| # | Rule | Details |
|---|------|---------|
| 1 | **48-Hour Window** | All film content must be created within the official 48-hour production window. Pre-production (scripts, storyboards, team formation) is allowed beforehand. |
| 2 | **Film Duration** | Films must be **1–10 minutes** in length (includes credits). |
| 3 | **AI Tool Disclosure** | All AI tools used in production must be disclosed in the submission — video generation, music, voices, and any AI-assisted creation. |
| 4 | **Team Size** | Teams of any size. Solo participation is allowed. |
| 5 | **Theme Integration** | Films must incorporate the revealed theme and required elements announced at the start of the 48h window. |
| 6 | **Original Content** | All content must be original or properly licensed. Stock footage, music, and assets must be cleared for use. |
| 7 | **Language & Subtitles** | Films can be in any language. Subtitles in **English**, **Latvian**, and **Russian** are required for all dialogue. |
| 8 | **Submission** | Films must be submitted through the platform with all required materials before the deadline. |

> 💡 **Pro Tip:** Use the feedback widget on the platform to ask questions or report issues.

---

## 2. Film Specifications & Deliverables

### 2.1 Technical Specifications

| Parameter | Requirement |
|-----------|-------------|
| **Duration** | 1–10 minutes (including credits) |
| **Resolution** | 1920×1080 (Full HD) minimum; **3840×2160 (4K) recommended** |
| **Video Format** | MP4, MOV |
| **Video Codec** | H.264 or H.265 |
| **Audio Codec** | AAC or WAV |
| **Audio Channels** | Stereo (2.0) or 5.1 Surround |
| **Sample Rate** | 48kHz |
| **Bit Depth** | 16-bit or 24-bit |

### 2.2 Required Submission Files

You must submit **3 video files** — both video versions must be identical except for subtitle overlay.

| # | File | Description | Naming Convention |
|---|------|-------------|-------------------|
| 1 | **Clean Version** | Video WITHOUT burned-in subtitles (for streaming platforms) | `[FilmTitle]_CLEAN.mp4` |
| 2 | **Subtitled Version** | Video WITH burned-in English subtitles (for festivals, social media) | `[FilmTitle]_SUBS.mp4` |
| 3 | **Vertical Trailer** | 30-second vertical teaser (9:16 aspect ratio) for Reels, Stories, TikTok | `[FilmTitle]_TRAILER.mp4` |

### 2.3 Subtitle Requirements

| Language | Code | Required |
|----------|------|----------|
| Latvian | LV | Yes |
| English | EN | Yes |
| Russian | RU | Yes |

**File format:** SRT or VTT
**Naming:** `[FilmTitle]_[LanguageCode].srt` — e.g., `MyFilm_EN.srt`, `MyFilm_LV.srt`, `MyFilm_RU.srt`

<details>
<summary><strong>SRT File Format Example</strong></summary>

```
1
00:00:01,000 --> 00:00:04,000
Hello, welcome to our film.

2
00:00:05,500 --> 00:00:08,200
This is an example subtitle.
```

**Key points:**
- Plain text file (open in Notepad)
- Contains timing codes (when to show/hide)
- Universal format — works everywhere
- Small file size (few KB)
</details>

### 2.4 Poster & Visual Assets

| Asset | Dimensions | Aspect Ratio | Notes |
|-------|-----------|--------------|-------|
| **Official Film Poster** | 2000×3000 | 2:3 | 300+ DPI, title visible, festival laurel area at bottom |
| **Instagram Feed** | 1080×1350 | 4:5 | Portrait, maximum visibility |
| **Instagram Reels/Stories** | 1080×1920 | 9:16 | Vertical content |
| **Facebook / X (Twitter)** | 1200×630 | 1.91:1 | Link previews, event covers |
| **YouTube Thumbnail** | 1280×720 | 16:9 | Video thumbnails |
| **LinkedIn** | 1200×627 | 1.91:1 | Article covers |

### 2.5 Go3 Streaming Platform Deliverables

| Asset | Dimensions | Ratio | Notes |
|-------|-----------|-------|-------|
| **Hero/Carousel (Centered)** | 1920×1080 | 16:9 | Main subject centered, safe zone: central 60% |
| **Hero/Carousel (Right Safe)** | 1920×1080 | 16:9 | Key elements right side, safe zone: right 40% clear for text overlay |
| **Mobile Thumbnail** | 1080×1080 | 1:1 | Centered composition, no title treatment |

> ⚠️ **Hero/Carousel images: NO title treatment.** Platform adds title overlay automatically.
> General: JPEG (preferred) or PNG, sRGB color space, max quality, key elements 10% from edges.

### 2.6 Metadata Requirements

| Field | Details |
|-------|---------|
| **Film Title** | Max 60 characters, in English + Latvian |
| **Short Synopsis** | Max 50 words (for program listings) |
| **Long Synopsis** | Max 200 words (for streaming platform) |
| **Logline** | One sentence that captures the essence |
| **Genre** | Primary (required, select 1) + Secondary (optional, up to 2) |
| **Credits** | Director, AI Tools Used, Festival Attribution |

**Available Genres:** Drama, Sci-Fi, Horror, Documentary, Animation, Comedy, Music Video, Experimental

**Required Credits:**
1. **Director** — must match registered team member
2. **AI Tools Used** — list all AI tools in production
3. **Festival Attribution** — "NO TITLE AI Film Festival 2025"

---

## 3. AI Tools Directory

### 3.1 Video Generation

| Tool | Best For | Pricing | Key Feature |
|------|----------|---------|-------------|
| **Runway Gen-4.5** | Cinematic scenes, character consistency, complex camera movements | Limited free credits | World's top-rated visual fidelity |
| **Runway Gen-4** | Character-driven storytelling | Limited free credits | Act Two for character consistency |
| **Kling 3.0** | Multi-shot sequences, storyboard workflows, longer clips | Free daily credits | Native audio-video generation, Multi-Shot storyboard |
| **Kling 2.6** | Character-driven scenes, motion control, lip-sync | Free daily credits | Motion brush, pose control |
| **Google Veo 3.1** | Dialogue scenes, audio-visual synchronization | Google AI Studio (limits) | Native audio generation + lip-sync |
| **OpenAI Sora 2** | Realistic motion, complex scenes, long-duration clips | ChatGPT Plus subscription | Exceptional physics understanding |
| **Pika 2.0** | Creative effects, transformations, quick iterations | Free tier | Fast creative experimentation |
| **Luma Ray2** | Fast iteration, cinematic shots, atmospheric scenes | Free generations | Ray2 Flash for rapid prototyping |
| **Hailuo AI Pro 2.3** | Controlled camera movements, cinematic compositions | Free tier | 12V Director for shot control |
| **Wan 2.6** | Local generation, fine-tuning, open-source workflows | Free (open source) | Animate mode, good text following |
| **LTX Video 2** | Speed-focused workflows, real-time preview | Free tier (limits) | Real-time generation + LTXV 2 Retake |
| **Higgsfield Soul 1.0** | Multi-model access, comparing outputs | Free account with credits | Access to Veo 3, Kling, and more |
| **SeedAnce Pro** | Dance sequences, character animation | Free tier | ByteDance's motion specialization |
| **Marey** | Pose-driven animation, motion transfer | Limited free tier | Director-style camera paths, licensed training data |
| **xAI Imagine Video** | Grok ecosystem, alternative style | Via X Premium | Grok integration |

### 3.2 Image Generation

| Tool | Best For | Pricing | Key Feature |
|------|----------|---------|-------------|
| **Midjourney V6.1** | Concept art, storyboards, character consistency | Paid only | `--cref` for character references, style references |
| **Flux Kontext** | Storyboards, character sheets, consistent visuals | Via platforms | Character-consistent generation |
| **Google Imagen 4** | Photorealistic images, complex scenes | Google AI Studio | Excellent prompt understanding |
| **Ideogram 3.0** | Movie posters, title cards, graphics with text | 25 free images/day | Best typography in images |
| **Recraft V3** | Logos, icons, design assets | Free tier | Design-focused with vector outputs |
| **Luma Photon** | Photorealistic images, product shots | Free tier | Photorealistic outputs |
| **Stable Diffusion 3.5** | Local generation, custom models, fine-tuning | Free (open source) | LoRA support, full customization |
| **Nano Banana (Gemini Image)** | Quick iterations, poster generation, image editing | Included with Lovable | Fast generation and editing |
| **Nano Banana Pro** | High-quality posters, detailed artwork | Included with Lovable | Better quality for complex prompts |
| **Qwen Image Edit** | Image editing, inpainting, style transfer | Via platforms | Alibaba's editing model |
| **Reve / Reve Blend** | Image blending, creative compositions | Free tier | Blending capabilities |
| **xAI Imagine** | Grok ecosystem, alternative style | Via X Premium | Grok integration |

### 3.3 Music & Audio

| Tool | Best For | Pricing | Key Feature |
|------|----------|---------|-------------|
| **Suno V4** | Full songs with vocals, custom jingles, theme songs | 10 songs/day free | Complete songs with lyrics and vocals up to 4 min |
| **Udio** | Professional instrumentals, genre-specific tracks | Limited free | High-fidelity, excellent genre control |
| **ElevenLabs Music** | Background music, mood-based generation | Free tier | Studio-quality output |
| **ElevenLabs Sound Effects** | Custom sound effects, foley, ambient sounds | Free tier | Text-to-SFX |
| **Stable Audio Open** | Free music generation, local workflows | Free (open source) | Full local control |
| **Soundverse** | Background music, audio branding | Free tier | AI-powered composition |
| **Soundraw** | Video-matched music, customizable tracks | Free tier | Stems + energy curve customization |
| **Moises AI Studio** | Building on existing audio, stem generation | Free trial | Stem matching to your style |

### 3.4 Voice & Narration

| Tool | Best For | Pricing | Key Feature |
|------|----------|---------|-------------|
| **ElevenLabs** | Voiceovers, narration, character voices, dubbing | 10,000 chars/month free | Emotional synthesis, voice cloning, 32 languages, Audio Tags |
| **Fish Audio** | Quick voice cloning, multilingual TTS | Free tier | Fast cloning with minimal samples |
| **Murf AI** | Professional voiceovers, e-learning | 10 minutes free | 200+ natural voices, studio quality |
| **Resemble AI** | Custom voice agents, real-time applications, gaming | Free trial | Real-time cloning with emotion control |
| **Lovo AI** | Multilingual voiceovers, narration with video | Limited free | 500+ voices with built-in video editor |

### 3.5 Editing Tools

| Tool | Best For | Pricing | Key Feature |
|------|----------|---------|-------------|
| **Adobe Premiere Pro** | Professional editing, complex timelines | 7-day free trial | AI auto-reframe, speech-to-text |
| **Final Cut Pro** | Mac users, fast rendering | 90-day free trial | Magnetic timeline, optimized for Mac |
| **DaVinci Resolve 19** | Color grading, professional finishing, complete post | **Full free version** | Industry-standard color + AI tools |
| **Descript** | Text-based editing, transcript editing, subtitles | Free tier | Edit video by editing text |
| **CapCut** | Quick edits, auto-captions, social media | Free with premium | Auto-captions, AI effects |
| **Arcade Studio** | AI-assisted creative workflows | Free tier | Multi-modal generation |
| **Opus Clip** | Creating short clips from long videos | Free tier | AI virality scoring |

### 3.6 Post-Production

| Tool | Best For | Pricing |
|------|----------|---------|
| **Flora AI** | Unified multi-model access (video, image, audio) | One subscription |
| **Weavy** | Complex AI workflows, combining multiple models | Free tier (now part of Figma) |

### 3.7 Upscaling & Enhancement

| Tool | Best For | Pricing | Key Feature |
|------|----------|---------|-------------|
| **Topaz Video AI** | Upscaling AI video to 4K, removing artifacts | Free trial | Industry-leading upscaling + stabilization |
| **Magnific AI V2** | Image upscaling with artistic enhancement | Limited free | Creative detail hallucination + Precision mode |
| **Bria Video Upscaler** | Quick video upscaling, batch processing | Via platforms | Fast processing |
| **Flora Upscaler** | Upscaling within Flora workflow | Pay-per-use | Integrated workflow |
| **UniFab** | SDR to HDR conversion, video enhancement | Free trial | HDR upconversion + noise reduction |

---

## 4. Expert Techniques & Masterclasses

### 4.1 Cinematic Prompting: The Paul Trillo Method

> **Source:** Paul Trillo — Sora early tester, director of *The Golden Record*, co-founder of Asteria

**The Prompt Formula:**

```
[Shot type] + [Camera movement] + [Subject action] + [Lighting/mood] + [Temporal pacing]
```

**Key Principles:**

| Principle | Explanation |
|-----------|-------------|
| **Treat AI like a cinematographer** | Describe what the CAMERA sees, not emotions |
| **Prompts are a new cinematic language** | Generate hundreds of shots, make impossible moves, carve a story from the best ones |
| **Reverse workflow** | Start with visual chaos, then build scripts and storyboards from the best outputs |
| **Push tools until they break** | "Every new technology is an opportunity for a new visual concept" |
| **Craft outlasts shortcuts** | Real artists treat the machine like any instrument — learn its quirks, push harder, repeat |

**Paul's Production Studio — Asteria:**
- Combines cel animation, CG, and AI in one pipeline
- **Marey** model: trained exclusively on licensed filmmaker footage — ethical AI video
- Director-style camera paths and multi-cam takes of the same shot

> 💡 *"Avoid abstract concepts — describe what the CAMERA sees, not emotions."*

**Works with:** Sora, Runway, Kling, Veo

---

### 4.2 Multi-Tool Orchestration: The Shy Kids Method

> **Source:** Shy Kids (Walter Woodman, Patrick Cederberg) — creators of *Air Head* (OpenAI Sora premiere film)

**Core Philosophy:** *"Sora isn't a magic trick — it's one tool in an orchestra."*

**Step-by-step Workflow:**

1. **Generate same scene** with 3–4 different AI models
2. **Cherry-pick** the best frames/clips from each
3. **Composite** frame-by-frame using After Effects or DaVinci Resolve
4. **Embrace "happy accidents"** — unexpected AI outputs often become key visuals
5. **Iterate prompts 50–100+ times** per scene

**Tools used:** Sora + Runway Gen-3/4 + Pika + After Effects

> 💡 *Don't rely on a single model. Generate with multiple tools, select the best outputs, and composite.*

---

### 4.3 Character Consistency Workflow

> **Source:** Industry standard techniques, Midjourney + Flux workflow

**The Problem:** Maintaining a consistent character across multiple scenes and shots.

**Solution — Midjourney `--cref` Workflow:**

1. **Create initial character** with a detailed prompt (face, clothing, style)
2. **Save character image** as your reference
3. **Use `--cref [image_url]`** in Midjourney for all subsequent images
4. **Adjust `--cw` value** (1–100) to control consistency:
   - **High (80–100):** Takes everything — clothes, face, hair
   - **Low (20–40):** Focuses on face only, allows outfit changes
5. **For video:** Use consistent character reference images as I2V (image-to-video) inputs
6. **Maintain same lighting/style keywords** across all prompts

**Multi-Character Scenes:**
- Use a second or third `--cref` for additional characters
- Results vary — two characters in one scene may need multiple generations

**Alternative Tools:**
- **Flux Kontext** — Character-consistent generation
- **Nano Banana** — Quick iterations with consistency
- **Runway Act-One** — Character consistency in video

> 💡 *Create a "character sheet" first — multiple angles and expressions — then reference it in every generation.*

---

### 4.4 AI Storyboarding & Visual Pre-Production

**The "Visual Bible" Approach:**

Before touching video generation, build a complete visual foundation:

| Step | Action | Tool |
|------|--------|------|
| 1 | **Concept art & mood boards** | Midjourney, Flux |
| 2 | **Character sheets** (multiple angles + expressions) | Midjourney `--cref`, Flux Kontext |
| 3 | **Environment establishing shots** | Midjourney, Imagen 4 |
| 4 | **Visual bible compilation** | Any image organizer |
| 5 | **Consistent style prompts** across all pre-production | Copy-paste your style keywords |

> 💡 *The visual bible IS your production guide. Every video generation should reference it.*

---

### 4.5 Emotional Voice Direction with ElevenLabs

> **Source:** ElevenLabs v3 Audio Tags documentation

**Audio Tags for Emotional Control:**

| Tag Type | Examples |
|----------|----------|
| **Emotional states** | `[excited]`, `[nervous]`, `[frustrated]`, `[sorrowful]`, `[calm]` |
| **Reactions** | `[sigh]`, `[laughs]`, `[gulps]`, `[gasps]`, `[whispers]` |
| **Physical** | `[tired]`, `[light chuckle]`, `[sigh of relief]` |
| **Intensity** | `[quietly]`, `[loudly]`, `[hesitant]` |

**Example Script with Tags:**
```
[tired] I've been working for 14 hours straight. [sigh] I can't even feel my 
hands anymore. [nervously] You sure this is going to work? [gulps] Okay... 
let's go.
```

**The "Actor-in-the-Loop" Method:**

1. **Record yourself** acting the line first (any quality)
2. **Use voice-to-voice transform** with your performance as the emotional guide
3. **Adjust sliders:**
   - Lower **Stability** = more emotional variation
   - Higher **Style Exaggeration** = more dramatic performances
4. **Clone your own voice** for faster iteration, then swap to final voice

**Important Note:** Professional Voice Clones (PVCs) are not yet fully optimized for v3. Use Instant Voice Clones (IVC) or designed voices for best results.

---

### 4.6 AI Music Production

**Platform Comparison:**

| Platform | Strength | Best For |
|----------|----------|----------|
| **Suno V4** | Full songs with vocals | Theme songs, jingles, songs with lyrics |
| **Udio** | Audio fidelity, musical complexity | Film scores, instrumentals, ambient |
| **Soundraw** | Customizable stems + timing | Video-matched background music |

**Production Workflow:**

1. **Start with style tags:** `[Cinematic] [Orchestral] [Tense] [Minor key]`
2. **Generate 30-second chunks** — don't try to generate a full track at once
3. **Extend what works** — iterate on the best sections
4. **Use Suno's "Covers" feature** to restyle existing generations
5. **Import to DAW** (GarageBand, Logic, Ableton)
6. **Separate stems** with Moises or Demucs
7. **Layer multiple AI tracks** for a fuller, richer sound

**Prompt Engineering for Music:**
- Combine **genre + mood + instrumentation + context**
- Example: *"Uplifting corporate background track with acoustic guitar, light piano, and subtle percussion, 120 BPM, major key"*
- Use **negative prompts** to exclude unwanted elements

> ⚠️ **Licensing:** Free tiers typically restrict commercial use. Paid subscriptions unlock full commercial rights. Keep records of your prompts as proof of originality.

---

### 4.7 Broadcast-Ready Upscaling with Topaz

**Standard Upscaling Workflow:**

1. **Generate** video at native resolution
2. **Import** into Topaz Video AI
3. **Select "Proteus" model** (best for AI-generated content)
4. **Enable:** Reduce Noise + Reduce Compression Artifacts
5. **For flickering:** Enable Stabilize with Rolling Shutter
6. **Upscale 2x max** (1080p → 4K) — never 4x
7. **Batch process overnight** — allow 10–30 min per minute of footage
8. **Export as ProRes or high-bitrate H.265** for editing

> ⚠️ This is GPU-intensive. Plan for overnight processing.

---

### 4.8 Subtitle Workflow with Descript

**Quick Subtitle Pipeline:**

| Step | Action |
|------|--------|
| 1 | Import video → Descript auto-transcribes |
| 2 | Click any word to jump to that point in video |
| 3 | Edit transcript to fix errors (edit text = edit video) |
| 4 | Export → Subtitles → SRT format |
| 5 | Translate with ChatGPT or DeepL for LV and RU versions |
| 6 | **Never burn in** — always export as separate SRT files |

**Alternative Subtitle Tools:**

| Tool | Pricing | Notes |
|------|---------|-------|
| **Descript** | Free: 1 hr transcription/month | Best for AI-powered accuracy |
| **CapCut** | Free | Text → Auto Captions → Generate |
| **DaVinci Resolve** | Free | Edit → Create Subtitle Track |
| **Premiere Pro** | Subscription | Professional workflow |
| **Subtitle Edit** | Free (open source) | Manual editing |

**Descript Editing Power Features:**
- **Delete text = delete video** (non-destructive)
- **Filler word removal** — auto-detected with blue underline
- **Speaker identification** — auto-labels different speakers
- **Overdub** — fix mispronounced words with AI voice
- **Studio Sound** — remove background noise and echo
- **Hotkeys:** `Z` + click = toggle capitalization, `X` + click = cycle space/comma/period, `C` = correct text mode

---

## 5. Video Model Comparison

### At-a-Glance Comparison

| Feature | Kling | Sora | Veo | Runway |
|---------|-------|------|-----|--------|
| **Best For** | High-volume social content | Cinematic realism | 4K cinematic movement | Rapid experimentation |
| **Realism** | Strong (social/action) | Excellent (film-like) | Excellent (4K-ready) | Good (design-led) |
| **Motion Fidelity** | Very strong (stable physics) | Excellent (natural camera motion) | Good (reliable for VFX) | Very strong (controlled) |
| **Temporal Consistency** | Good (short runs solid) | Excellent (characters + props locked) | Very strong (narrative continuity) | Strong (with defined frames) |
| **Style Control** | Strong (social styles) | Strong (mood/tone/lighting) | Excellent (fine-grained cinematic) | Excellent (remixing/restyling) |
| **Speed** | Fast | Slow (expensive) | Moderate | Fast |
| **Cost** | Free daily credits | ChatGPT Plus | Google AI Studio | Subscription tiers |

### When to Use Each Model

| Scenario | Best Model |
|----------|-----------|
| UGC ads, TikTok, YouTube automation | **Kling** |
| Footage that must look like live-action | **Sora** |
| Polished explainers, B-roll, cinematic camera | **Veo** |
| Early exploration, creative experimentation | **Runway** |
| Dialogue scenes with synchronized audio | **Veo 3.1** |
| Multi-shot storyboard sequences | **Kling 3.0** |
| Character-driven narrative with consistency | **Runway Gen-4** (Act-One) |

---

## 6. Competition Lessons & Speed Workflow

### 6.1 48-Hour Speed Workflow Secrets

> **Source:** Veterans of Runway Gen:48 and other AI film competitions

**Time Allocation:**

```
[Hours 0–4]   → Ideation & Story Construction
[Hours 4–24]  → Generation Sprint (images, video, audio, music)
[Hours 24–46] → Editing, Polish, Subtitles, Deliverables
[Hours 46–48] → Final Review & Submit (30 min early!)
```

**Golden Rules:**

| Rule | Why |
|------|-----|
| **Scope for 2–3 minutes, not 10** | Quality over quantity — always |
| **Pre-build templates before the 48h** | Have your editing project, folder structure, and export presets ready |
| **Batch-generate overnight** | Queue up generations before sleeping |
| **Submit 30 minutes early** | Technical issues WILL happen |
| **Have backup tools ready** | If one model goes down, switch instantly |
| **Story first, tech second** | The winners focused on emotion and story, not technical complexity |

### 6.2 Five Lessons from Gen:48 Veterans

> **Source:** Erik Knobl's experience at Runway Gen:48 + community insights

| # | Lesson | Detail |
|---|--------|--------|
| 1 | **Story first — AI is a tool, not the star** | Simple concepts with strong execution beat ambitious failures every time |
| 2 | **Less is more** | One strong scene beats five weak ones |
| 3 | **Embrace limitations** | Work WITH the AI's quirks — "happy accidents" become key visuals |
| 4 | **Sound design sells it** | Prioritize audio polish — it's what separates amateur from professional |
| 5 | **Test your pipeline BEFORE the competition** | Know your tools, know their limits, have workflows ready to go |

### 6.3 Solo Competitor Survival Guide

> **Source:** Sophia Banton's experience competing solo in Gen:48 (3,000 teams entered)

**Day 1 — Story Construction (Full Day):**
- Draft a full scene-by-scene outline based on the brief
- Pressure-test the story arc using ChatGPT, Claude, and Gemini
- Map out Day 2 production workflow with time blocks
- **No footage created on Day 1** — entirely focused on narrative + planning

**Day 2 — Production Sprint:**
- Generate ALL visuals, animations, soundtrack, voiceover
- Complete final editing in under 24 hours
- Every decision must be made rapidly and decisively

**Technical Arsenal (Proven Solo Setup):**

| Task | Tool Used |
|------|-----------|
| Environment images | Google ImageFX |
| Character scenes | Runway Gen-4 (with reference images) |
| Animation | Runway Gen-4 Turbo |
| Soundtrack | Suno AI (3 original songs) |
| Sound effects | Epidemic Sound |
| Voiceover | ElevenLabs (AI-cloned voice) |
| Video editing | CapCut Pro |

**Key Insights:**
- Generate **longer 10-second clips** for editing flexibility — salvage usable portions from flawed animations
- **Character consistency is the hardest challenge** — expect distortions, multiple generations needed
- **Animation > Image generation** in difficulty — requires director-level technical direction
- **Traditional filmmaking instincts remain crucial** — framing, motion, pacing, emotional resonance

> 💡 *"AI literacy proved invaluable — allowing me to devote an entire day to story development while confidently planning for the technical execution that would follow."*

---

## 7. Prompt Engineering Cheat Sheet

### Video Prompting Mistakes to Avoid

| Mistake | Problem | Solution |
|---------|---------|----------|
| **Too much dramatic wording** | Competing instructions degrade consistency | Describe **actions, order, and visual intent**. Let style emerge after structure. |
| **Skipping references** | Identity, style, and environments drift between clips | Always use **reference images** and locked inputs |
| **Judging by frames, not motion** | A single frame can look flawless while video falls apart | Always evaluate **movement over time**, not stills |
| **Mixing aesthetics** | Stacking too many styles forces the model to compromise | Commit to **one visual language** and let everything follow |

### The Perfect Video Prompt Structure

```
[Action/Scene Description]
+ [Shot Type: close-up, wide, medium]
+ [Camera Movement: pan left, dolly in, static]
+ [Subject Action: walking, turning, speaking]
+ [Lighting/Mood: warm golden hour, cold blue fluorescent]
+ [Duration/Pacing: slow, 10 seconds]
```

### Example — Bad vs Good

**Bad:**
> *"Create an epic, emotional, hyper-realistic UGC-style video of a man wearing a jacket with lifestyle shots, moody lighting, and fabric close-ups."*

**Good:**
> *"Create a 30-second UGC-style video. Open with man putting on jacket at home. Walk outside to show fit and movement. Quick fabric and stitching close-ups. End with jacket being folded. Natural daylight, handheld camera feel."*

---

## 8. Production Pipeline — Quick Reference

### Phase 1: Pre-Production (Before 48h)

```
□ Write script / scene-by-scene outline
□ Create character sheets (Midjourney --cref or Flux Kontext)
□ Build mood boards and environment concepts
□ Assemble "visual bible"
□ Set up editing project template (DaVinci / Premiere / CapCut)
□ Prepare folder structure and naming conventions
□ Test your full pipeline end-to-end
□ Prepare export presets for all deliverables
```

### Phase 2: Production (During 48h)

```
□ Receive brief → Integrate theme + required elements
□ Finalize story based on brief requirements
□ Generate character images with consistency references
□ Generate environment/establishing shots
□ Generate video clips (batch, use multiple models)
□ Generate soundtrack (Suno / Udio — 30-sec chunks, extend)
□ Generate voiceover (ElevenLabs with Audio Tags)
□ Generate sound effects (ElevenLabs SFX)
```

### Phase 3: Post-Production

```
□ Assemble rough cut in editor
□ Fine-tune timing, pacing, transitions
□ Color grade (DaVinci Resolve)
□ Sound mix — balance dialogue, music, SFX
□ Upscale to 4K with Topaz Video AI (overnight)
□ Create subtitles in Descript → Export EN SRT
□ Translate to LV and RU (ChatGPT / DeepL)
□ Export Clean version + Subtitled version
□ Create 30-sec vertical trailer
□ Create poster and social media assets
□ Prepare Go3 streaming assets
□ Fill in all metadata
□ Final review of all files
□ SUBMIT (30 minutes early!)
```

### File Submission Checklist

```
□ [FilmTitle]_CLEAN.mp4        — Clean video (no subs)
□ [FilmTitle]_SUBS.mp4         — Video with burned-in English subs
□ [FilmTitle]_TRAILER.mp4      — 30-sec vertical trailer (9:16)
□ [FilmTitle]_EN.srt           — English subtitles
□ [FilmTitle]_LV.srt           — Latvian subtitles
□ [FilmTitle]_RU.srt           — Russian subtitles
□ Film Poster                  — 2000×3000, 300+ DPI
□ Go3 Hero (Centered)          — 1920×1080
□ Go3 Hero (Right Safe)        — 1920×1080
□ Go3 Mobile Thumbnail         — 1080×1080
□ Metadata (title, synopsis, logline, genre, credits)
```

---

## Sources & References

| Source | Content |
|--------|---------|
| [NO TITLE AI Film Festival](https://notitleai.org/archive/resources) | Official rules, specs, tools, and learning resources |
| Paul Trillo / Motionographer | Cinematic prompting method, Asteria studio, Marey model |
| Shy Kids (Walter Woodman, Patrick Cederberg) | Multi-tool orchestration, *Air Head* film |
| Erik Knobl — Medium | 5 Lessons from Gen:48 AI Film Competition |
| Sophia Banton | Solo competitor Gen:48 survival guide |
| ElevenLabs Blog | Eleven v3 Audio Tags for emotional voice direction |
| InVideo Blog | Kling vs Sora vs Veo vs Runway comparison |
| PromptTag Blog | AI Music Generation guide (Suno, Udio, Soundraw) |
| JourneyAIArt / Creative Exploration | Flux model deep-dive and Midjourney techniques |
| Tom's Guide | Midjourney character consistency (`--cref`) feature testing |
| Descript Blog | Text-based video editing tutorial |

---

> *Last updated: February 7, 2026*
> *Compiled for the NO TITLE AI Film Festival Hackathon*
