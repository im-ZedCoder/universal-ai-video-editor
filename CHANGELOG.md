# Changelog

All notable changes to this project will be documented here.

## [1.0.0] - Initial release

### Added

- Universal topic-agnostic video editing skill
- Automatic content classification
- Automatic audience/depth adaptation
- Automatic script and hook generation
- Visual storyboard logic
- B-roll strategy
- Motion graphics system
- Subtitle system
- Persian RTL support
- Voiceover guidance
- Music and sound-design system
- Raw footage workflow
- Talking-head workflow
- Interview workflow
- Podcast workflow
- Product workflow
- Tutorial workflow
- Documentary workflow
- Storytelling workflow
- Advertisement workflow
- News workflow
- Gaming workflow
- Travel workflow
- Food workflow
- Accessibility guidance
- Fact-checking and accuracy rules
- Copyright-aware media guidance
- Quality-control checklist


## [1.1.0] - Consistent design system and voiceover handoff

### Added

- Reusable cross-video visual template and component system
- Default top-right `XodeOMiD` creator watermark placement
- iOS-inspired UI component principles
- Typography scale, layout bounds, safe margins, and overflow checks
- Contrast/glow restraint for bold and large text
- Smooth, consistent motion easing guidelines
- Mandatory scene-by-scene layout QA
- ElevenLabs-ready narration script with pause cues and phrase-level timing map

### Changed

- Final voiceover audio must not be synthesized by the skill; ElevenLabs is the voice generation handoff
- When generated narration audio is supplied, the edit and subtitles must follow the actual waveform and pauses
