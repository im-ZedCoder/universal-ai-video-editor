[🇮🇷 فارسی](README.fa.md) · 🇬🇧 **English**

# 🎬 Universal AI Video Editor

**Turn a simple idea into a professionally planned and edited video.**

Universal AI Video Editor is a topic-agnostic AI video editing skill designed to make an AI behave like a professional:

- 🎬 Video Editor
- 🎨 Motion Designer
- 🎧 Sound Designer
- ✍️ Scriptwriter
- 🎙️ Voiceover Director
- 📝 Subtitle Designer
- 🎥 Cinematic Director
- 📱 Short-form Content Editor
- 📚 Documentary Editor
- 📢 Content Strategist

The user can provide a single topic. The skill handles the production decisions automatically.

---

## ✨ What makes it different?

Most AI video prompts force users to repeatedly specify:

> "Use subtitles."

> "Add transitions."

> "Make it cinematic."

> "Add motion graphics."

> "Use B-roll."

> "Add sound effects."

> "Make it suitable for Instagram."

This project turns those repeated instructions into a reusable editing system.

### The user can simply say:

```text
Create a video about the history of the internet.
```

The skill determines the appropriate:

- content type
- audience depth
- storytelling structure
- hook
- pacing
- visuals
- B-roll
- motion graphics
- subtitles
- voiceover
- music
- sound design
- transitions
- color treatment
- platform format

---

## 🌍 Topic agnostic

This project is not designed only for AI or technology.

It can adapt to:

| Topic | Likely editing approach |
|---|---|
| History | Documentary / storytelling |
| Science | Educational / visual explainer |
| Gaming | Dynamic gameplay edit |
| Travel | Cinematic travel |
| Food | Macro / sensory edit |
| Business | Explainer / professional |
| Sports | High-energy action |
| Tutorial | Screen recording / callouts |
| Product | Showcase / advertisement |
| Horror | Cinematic storytelling |
| News | Information-first |
| Podcast | Talking-head / multicam |
| Comedy | Timing-driven edit |
| Biography | Documentary storytelling |

These are examples, not fixed templates.

---

## 🧠 Core idea

```text
                    USER
                     │
                     ▼
                  SIMPLE IDEA
                     │
                     ▼
              TOPIC UNDERSTANDING
                     │
                     ▼
             CONTENT CLASSIFICATION
                     │
                     ▼
            AUDIENCE + DEPTH ANALYSIS
                     │
                     ▼
              STORY / SCRIPT
                     │
          ┌──────────┼──────────┐
          ▼          ▼          ▼
       VISUALS    AUDIO       MOTION
          │          │          │
          ▼          ▼          ▼
       B-ROLL     VOICE       GRAPHICS
          │          │          │
          └──────────┼──────────┘
                     ▼
                  SUBTITLES
                     │
                     ▼
                   EDIT
                     │
                     ▼
               QUALITY CONTROL
                     │
                     ▼
                FINAL VIDEO
```

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/universal-ai-video-editor.git
```

Then use `SKILL.md` as the system/skill instruction for the AI video workflow you are using.

> The exact installation method depends on the AI agent or video-generation platform.

---

## 🚀 Basic usage

The simplest possible input:

```text
Create a video about:

The history of the internet
```

Another example:

```text
Create a 45-second video about:

Why do cats purr?
```

Another:

```text
Create a cinematic video about:

My trip to Tokyo
```

Another:

```text
Create an educational video about:

How inflation works
```

The skill automatically adapts its production strategy.

---

## 🎛️ Optional controls

Users can override the defaults whenever needed:

```text
TOPIC:
How electric cars work

DURATION:
60 seconds

LANGUAGE:
Persian

STYLE:
Cinematic educational

PLATFORM:
Instagram Reels
```

You can also specify:

```text
VOICE:
Male, energetic

MUSIC:
Electronic

SUBTITLES:
Minimal

BRANDING:
MyBrand

ASPECT_RATIO:
9:16
```

If an option is not provided, the skill makes a professional choice automatically.

---

## 🎥 Supported workflows

### 1. Topic → Full video

```text
Create a video about:
The history of Minecraft
```

### 2. Script → Video

```text
Turn this script into a professional video:

[script]
```

### 3. Raw footage → Edit

```text
Edit these clips into a 60-second travel Reel.
```

### 4. Talking head → Social clip

```text
Turn this talking-head recording into a high-retention short.
```

### 5. Podcast → Clips

```text
Find the strongest moments and turn them into short-form clips.
```

### 6. Product → Advertisement

```text
Create a premium product advertisement from these assets.
```

---

## 🎨 Automatic style selection

The system does not force a single visual identity.

For example:

**A history video** may become cinematic and documentary.

**A gaming video** may become fast and energetic.

**A cooking video** may use macro shots and natural kitchen sounds.

**A horror story** may use darkness, negative space, slow reveals, and tension.

**A programming tutorial** may use screen recording, zooms, cursor tracking, and UI callouts.

The subject determines the visual language.

---

## 📝 Subtitles

The system automatically handles:

- transcription
- timing
- segmentation
- typography
- animation
- positioning
- RTL/LTR behavior

For Persian content, **Doran Fanum** can be used when available.

The system should fall back to an appropriate readable font when it is not installed.

---

## 🧩 Consistent UI, typography, and motion

The skill uses a reusable visual system across a creator's video series instead of inventing a new layout in every scene. Designed UI components follow restrained **iOS-inspired** principles: rounded cards, clear hierarchy, generous spacing, subtle materials, and consistent iconography.

- Default creator handle: `XodeOMiD` in the top-right corner, kept subtle and consistently positioned unless the user specifies otherwise.
- Typography uses a defined scale; text and graphics must remain inside their assigned cards and safe areas.
- Large/bold text must remain readable: avoid excessive neon glow, bloom, or saturated gradients.
- Every scene receives a layout QA pass for overflow, clipping, overlap, contrast, and subtitle collisions.
- Animations use smooth, consistent easing and restrained movement rather than abrupt linear motion or excessive bounce.

---

## 🎙️ ElevenLabs voiceover workflow

The skill **does not generate the final voice audio**. It prepares an ElevenLabs-ready narration script with natural punctuation, pause cues, voice direction, and phrase-level timing. If ElevenLabs does not support pause markers directly, the skill also provides a clean TTS script and a separate timing map. Once the user supplies the generated audio, the edit and subtitles are synchronized to its actual waveform and pauses. Without an audio file, the project keeps a clearly marked voiceover placeholder.

---

## 🎧 Audio

The skill automatically considers:

- voiceover script and timing handoff (ElevenLabs)
- dialogue
- music
- SFX
- ambience
- ducking
- loudness
- transitions

Dialogue always receives priority over background music.

---

## 🎞️ Motion graphics

Motion graphics are generated according to the information being communicated.

Examples:

- diagrams
- timelines
- charts
- callouts
- kinetic typography
- UI cards
- maps
- counters
- animated icons
- tracked labels

The system should never add effects only because they look impressive.

---

## 🔎 Accuracy

For factual subjects, the system must avoid fabricating:

- statistics
- dates
- quotes
- prices
- rankings
- scientific claims
- product features
- sources

If current information is required and web research is available, the information should be verified before being presented as fact.

---

## 🌐 Languages

The skill is designed to work with multiple languages.

It supports:

- LTR languages
- RTL languages
- mixed-language content
- multilingual subtitles
- technical terminology

Persian and Arabic require correct RTL handling.

---

## 📱 Platform formats

Common defaults:

### Vertical

```text
1080 × 1920
9:16
```

### Landscape

```text
1920 × 1080
16:9
```

### Square

```text
1080 × 1080
1:1
```

The platform should determine the final composition when known.

---

## 🛡️ Safety and accuracy

This project is an editing framework, not a license to fabricate information.

The system should:

- avoid misinformation
- distinguish fact from opinion
- avoid fake statistics
- avoid fake testimonials
- avoid invented sources
- avoid misleading visual implications
- respect copyright
- avoid pretending an unavailable capability was completed

---

## 📁 Repository structure

```text
universal-ai-video-editor/
│
├── SKILL.md
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CHANGELOG.md
├── .gitignore
│
├── examples/
│   ├── ai.md
│   ├── documentary.md
│   ├── gaming.md
│   ├── tutorial.md
│   ├── travel.md
│   ├── product.md
│   └── storytelling.md
│
└── references/
    ├── editing-principles.md
    ├── motion-design.md
    ├── subtitle-guidelines.md
    ├── sound-design.md
    └── platform-formats.md
```

---

## 🤝 Contributing

Contributions are welcome.

Good contributions include:

- new editing strategies
- new content modes
- improved subtitle rules
- better accessibility guidance
- platform-specific workflows
- multilingual improvements
- examples
- bug fixes
- documentation improvements

Before submitting a change, make sure it does not make the skill unnecessarily dependent on one topic, platform, language, or brand.

See [CONTRIBUTING.md](CONTRIBUTING.md).

---

## 📄 License

This project is released under the MIT License.

See [LICENSE](LICENSE).

---

## ⭐ Philosophy

The goal is simple:

> **The user gives the idea. The AI builds the production.**

A good video is not a collection of effects.

It is a story told through:

**image + motion + sound + timing + typography + emotion.**
