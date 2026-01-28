---
name: video-generator
description: Generates videos with Type×Style system and Superpowers framework. Supports 8 video types, 14 visual styles, AI media generation (Stable Diffusion, DALL-E, Runway, Pika, Sora), complete superpower-driven 4-phase workflow, zero-API local solutions (ChatTTS, Edge-TTS, Ollama, local Stable Diffusion/SVD). Enhanced with Graphiti, multilingual TTS, Baoyu design systems mapping, and personalized recommendations. Use when asking to "generate video", "create video", or mentions "视频生成".
dependency:
  python:
    - moviepy>=1.0.3
    - pillow>=10.0.0
    - requests>=2.28.0
    - diffusers>=0.21.0
    - transformers>=4.30.0
    - accelerate>=0.20.0
  system:
    - ffmpeg
---

# Video Generator

Generate professional videos with flexible Type × Style combinations, inspired by article-illustrator's two-dimension system, comic's preset system, and infographic's rich style options.

**Enhanced with**:
- Superpowers-driven workflow from obra/superpowers (intent analysis → selection → mapping → generation, 10 actionable superpowers)
- Structured workflow from doc-coauthoring (Context Gathering → Refinement & Structure → Reader Testing)
- UI/UX design thinking from frontend-design (distinctive aesthetics, avoiding generic AI look)
- Algorithmic art aesthetics from algorithmic-art (generative, code-based visuals)
- FFmpeg advanced processing (professional video optimization, filters, effects)
- Remotion-inspired concepts (declarative animation, frame-precise control, data-driven visuals)
- Chinese text humanization (natural, authentic, culturally-appropriate Chinese expression)
- Canvas design principles (composition, grid systems, layout patterns)
- Persuasive copywriting (headlines, hooks, CTAs, emotional connection)
- Visual skills (mind maps, flowcharts, concept maps, timelines, org charts, knowledge graphs)
- Xiaohongshu design aesthetics (fresh, refined, youthful, social media optimized)
- VibeVoice-ASR audio transcription (60-minute long-form, speaker identification, timestamps)
- Baoyu design systems (Type×Style framework for articles, comics, covers, infographics)
- Multilingual support from illa-helper (intelligent language detection, AI translation, 20+ languages)
- TTS integration from illa-helper (multi-service TTS, pronunciation variants, audio caching)
- ChatTTS conversational voice synthesis (natural dialogue, speech markers, character simulation)
- Graphiti temporal knowledge graph (real-time updates, hybrid retrieval, personalized recommendations, context management)
- AI media generation (Stable Diffusion, DALL-E, Runway, Pika, Sora integration, Superpower-aware generation)
- Complete copywriting system (video scripts, marketing copies, scene descriptions, voiceover scripts, SEO keywords, social media content)

## Superpowers (from obra/superpowers)

Video generation should incorporate specific "superpowers" - actionable capabilities that make the output extraordinary. Apply these strategically to elevate content:

### The Superpower Framework

**When to Apply**:
- Content needs emotional impact beyond explanation
- User seeks inspiration or motivation
- Topic involves transformation, growth, or achievement
- Narrative requires memorable, action-oriented messaging

**Core Superpowers**:

1. **The Pattern Hunter**: Identify and make visible hidden patterns, systems, or connections that others miss
   - Visual: Overlay connecting lines, reveal underlying structure, animated pattern emergence
   - Use: Explaining complex systems, showing cause-effect chains, revealing insights

2. **The Bridge Builder**: Connect disparate concepts, disciplines, or domains in surprising ways
   - Visual: Split-screen juxtaposition, morphing between domains, Venn diagram evolution
   - Use: Cross-domain analogies, interdisciplinary learning, novel connections

3. **The Storyteller**: Transform dry facts into compelling narratives with emotional resonance
   - Visual: Character journey arcs, metaphorical scenes, story beats with visual punctuation
   - Use: Making data memorable, humanizing concepts, creating emotional engagement

4. **The Simplifier**: Break down complexity into intuitive, instantly graspable visual metaphors
   - Visual: Step-by-step breakdown, layered peel-away, animated deconstruction
   - Use: Technical concepts, new ideas, abstract principles

5. **The Amplifier**: Intensify key messages for maximum impact and memorability
   - Visual: Dramatic zoom, kinetic typography, color explosion, focus pull effects
   - Use: Call-to-action, key insights, emotional climax points

6. **The Perspective Shifter**: Present familiar concepts from radically different viewpoints
   - Visual: Camera rotation, scale shift (micro to macro), inverted perspectives
   - Use: Paradigm shifts, new frameworks, challenging assumptions

7. **The Empathy Engine**: Create visceral emotional connection through relatable human elements
   - Visual: Human faces, relatable scenarios, emotional reaction shots
   - Use: Social impact content, user stories, brand narratives

8. **The Pattern Breaker**: Deliberately disrupt expectations to create surprise and insight
   - Visual: Sudden style shifts, rule-breaking layouts, unexpected transitions
   - Use: Challenging assumptions, innovative approaches, paradigm shifts

9. **The Time Bender**: Manipulate temporal perception - accelerate, decelerate, or freeze moments
   - Visual: Slow-motion reveals, timelapse sequences, freeze-frame analysis
   - Use: Process explanations, showing change over time, dramatic moments

10. **The Sensemaker**: Transform chaos into order through structured visualization
    - Visual: Organizing chaos into grids, pattern emergence from randomness, structured categorization
    - Use: Making sense of complexity, finding structure in noise, strategic frameworks

### Applying Superpowers

**Select 1-3 superpowers per video** based on:
- **Goal**: What outcome do you want? (inspire, explain, persuade, motivate)
- **Audience**: Who watches this? What moves them?
- **Content**: What's the core message? Which superpower amplifies it best?

**Integration Steps**:
1. Identify the core message or transformation in the content
2. Match 1-3 superpowers that amplify this core message
3. Design visual scenes that embody these superpowers
4. Use motion, color, and composition to reinforce the chosen superpowers

**Example Applications**:

**Pattern Hunter**:
- Scene: Show scattered data points → animated lines connect revealing a trend
- Motion: Smooth emergence of patterns from chaos
- Style: minimal or technical-schematic works well

**Bridge Builder**:
- Scene: Split screen with concept A → morph into concept B
- Motion: Fluid transition between domains
- Style: bold-editorial or algorithmic emphasizes connection

**Storyteller**:
- Scene: Follow a character through their journey with emotional beats
- Motion: Emotional pacing, dramatic reveals
- Style: warm, watercolor, or craft-handmade for emotional resonance

**Amplifier**:
- Scene: Key insight appears → dramatic zoom, kinetic typography
- Motion: Punchy, high-impact moments
- Style: bold-editorial, cyberpunk-neon, or pixel-art

**Simplifier**:
- Scene: Complex concept → peel away layers revealing simple core
- Motion: Deconstructive, layer-by-layer
- Style: minimal or chalkboard for clarity

**Perspective Shifter**:
- Scene: Familiar view → rotate camera to reveal new angle
- Motion: Smooth camera movement, reveal
- Style: cinematic or algorithmic for visual drama

**Empathy Engine**:
- Scene: Real people showing genuine reactions
- Motion: Natural, authentic movement
- Style: warm or craft-handmade for humanity

**Pattern Breaker**:
- Scene: Expected sequence → sudden unexpected twist
- Motion: Jarring or surprising transitions
- Style: cyberpunk-neon, pixel-art, or algorithmic for disruption

**Time Bender**:
- Scene: Process at normal speed → slow-motion reveal of detail
- Motion: Variable speed, dramatic slow-motion
- Style: cinematic or technical-schematic

**Sensemaker**:
- Scene: Chaotic elements → organize into structured grid
- Motion: Order emerging from chaos
- Style: minimal or algorithmic

**Combination Example**:
Video about climate change:
- **Pattern Hunter**: Show temperature data over time, revealing accelerating trend
- **Amplifier**: Dramatic visualization of impact
- **Empathy Engine**: Show real people affected

**Key Principle**: Superpowers should feel intentional and integrated, not random. Choose what truly amplifies the core message.

### Superpowers × Baoyu Design Systems Integration

Each Superpower now integrates with Baoyu's proven design frameworks for fine-grained visual control:

**Integration Principle**: "Superpowers provide the soul; Baoyu provides the body."

- **Superpowers**: Determine emotional intent, dynamic behaviors, camera movements
- **Baoyu Design Systems**: Provide structural foundation, composition, aesthetic precision
- **Combined**: Rich visuals with both emotional depth and professional structure

**Example Mappings**:
- **Storyteller** × **Article Illustration** (scene × warm): Emotional narrative with friendly composition
- **Simplifier** × **Infographic** (linear-progression × minimal): Clear step-by-step with clean design
- **Pattern Hunter** × **Infographic** (hub-spoke × technical-schematic): Reveal connections with network visualization
- **Amplifier** × **Cover Image** (hero × vivid): Maximum impact with bold hero composition
- **Empathy Engine** × **Comic** (manga × warm): Human connection with expressive manga style

**Benefits**:
- 40+ unique visual approaches (10 Superpowers × 4 Baoyu Systems)
- Proven design frameworks for professional quality
- Fine-grained control over both emotion and structure
- Flexible combinations for any content type

See [references/superpower-baoyu-mapping.md](references/superpower-baoyu-mapping.md) for complete mapping guide.

## Superpowers-Driven Workflow

**Recommended Approach**: Use the complete 4-phase Superpowers-driven workflow for all video generation tasks. See [references/complete-workflow-guide.md](references/complete-workflow-guide.md) for detailed documentation.

### Quick Start

Execute complete end-to-end video generation with a single command:

```bash
python scripts/video-generation-workflow.py \
  --request "Create a product promotion video for our new smartphone" \
  --platform douyin \
  --goal persuade \
  --output ./output
```

This command will automatically execute all 4 phases:
- Phase 0: Preparation (initialize environment, validate input)
- Phase 1: Intent Analysis & Superpower Selection (analyze request, select superpowers, map to Baoyu systems)
- Phase 2: 内容生成（并行执行） (parallel generation of scripts, visuals, audio)
- Phase 3: Integration & Rendering (merge, add audio/subtitles, apply effects, FFmpeg render)
- Phase 4: Quality Control (quality check, intent alignment, optimization suggestions)

### Four-Phase Workflow Overview

**Phase 1: Intent Analysis**
- Analyze user request (goal, audience, platform)
- Extract core message
- Retrieve context from Graphiti knowledge graph
- Output: Intent object with goal, audience, core message

**Phase 2: Superpower Selection**
- Evaluate all 10 superpowers based on goal, audience, and content
- AI-driven selection with scoring (goal alignment 40%, audience fit 30%, content fit 30%)
- Select top 1-3 superpowers with rationale
- Output: Selected superpowers with priority and application strategy

**Phase 3: Superpower Mapping**
- Map superpowers to visual elements (style, camera movements, color palette, transitions)
- Map superpowers to copywriting tone (style, keywords, emotional arc)
- Map superpowers to audio parameters (voice tone, speed, pitch, TTS markers)
- Map superpowers to camera movements (type, speed, purpose)
- Output: Comprehensive mapping for all elements

**Phase 4: Content Generation (Parallel)**
- **Copywriter Generator**: Generate superpower-aware scripts, marketing copies, scene descriptions, voiceover scripts
- **AI Media Generator**: Generate superpower-aware visuals with style parameters
- **TTS Generator**: Generate superpower-aware audio with tone and markers
- **Integration**: Merge all content with superpower-specific transitions and effects
- Output: Complete video file with all superpowers applied

### Usage: Complete Superpower Workflow

**Recommended workflow for all video generation**:

1. **Call Superpower Orchestrator**:
   ```bash
   python scripts/superpower-orchestrator.py \
     --request "Create a 30-second product promo for保温杯" \
     --platform douyin \
     --target-audience "young professionals" \
     --goal persuade \
     --output workflow.json
   ```

2. **Review Superpower Selection**:
   - Check selected superpowers (e.g., storyteller + empathy_engine + amplifier)
   - Review rationale for each superpower
   - Confirm superpower mapping (visual, copywriting, audio, camera)

3. **Generate Content in Parallel**:

   *Generate Script*:
   ```bash
   python scripts/copywriter-generator.py \
     --type video_script \
     --product 保温杯 \
     --duration 30 \
     --tone professional \
     --output script.json
   ```

   *Generate Visuals*:
   ```bash
   python scripts/ai-media-generator.py \
     --scenes workflow.json \
     --superpower storyteller \
     --output ./visuals
   ```

   *Generate Audio*:
   ```bash
   python scripts/tts-generator.py \
     --script script.json \
     --voice natural_warm \
     --output audio.mp3
   ```

4. **Integrate and Render**:
   ```bash
   python scripts/ffmpeg-processor.py \
     --visuals ./visuals \
     --audio audio.mp3 \
     --output final_video.mp4 \
     --transitions emotional_fade,punchy_cut
   ```

### Superpower Selection Guide

| Goal | Recommended Superpowers |
|------|------------------------|
| **Persuade** | Storyteller + Empathy Engine + Amplifier |
| **Explain** | Simplifier + Pattern Hunter + Sensemaker |
| **Inspire** | Storyteller + Perspective Shifter + Amplifier |
| **Motivate** | Amplifier + Storyteller + Pattern Breaker |
| **Entertain** | Pattern Breaker + Time Bender + Storyteller |

### Integration with Existing Capabilities

The Superpowers workflow integrates seamlessly with all existing video generator capabilities:

- **Type×Style System**: Superpowers guide the selection of visual styles and video types
- **Baoyu Design Systems**: Superpowers automatically select and use Baoyu systems for visual foundation
- **Knowledge Graph**: Context retrieval during intent analysis phase
- **TTS Integration**: Superpower-aware audio generation with tone and markers
- **Copywriting System**: Superpower-aware script and copy generation
- **AI Media Generation**: Superpower-aware visual generation with style parameters
- **FFmpeg Processing**: Superpower-specific transitions and effects
- **FFmpeg Processing**: Superpower-specific transitions and effects

**Key Benefit**: The Superpowers framework provides a unified, intentional approach to video production, ensuring all elements work together cohesively to amplify the core message.

## FFmpeg Advanced Processing

Leverage FFmpeg's professional-grade video processing capabilities for optimization, enhancement, and professional quality output.

### Core Processing Capabilities

**Video Quality Optimization**:
- Codec selection (H.264, H.265/HEVC, VP9, AV1)
- Bitrate control (CBR, VBR, CRF)
- Resolution and frame rate adjustments
- Color space conversion and HDR support

**Video Filters & Effects**:
- Color correction and grading (brightness, contrast, saturation, hue)
- Blur and sharpen effects (Gaussian, unsharp mask)
- Speed manipulation (slow motion, fast forward, reverse)
- Crop, scale, and padding
- Rotate, flip, and transpose
- Overlay and watermarking
- Text and graphics overlay

**Audio Processing**:
- Audio normalization and volume adjustment
- Noise reduction
- Audio extraction and replacement
- Multi-channel mixing
- Audio codec optimization (AAC, MP3, Opus)

**Advanced Features**:
- Batch processing of multiple videos
- Multi-pass encoding for optimal quality
- Hardware acceleration (NVENC, VAAPI, QuickSync)
- Custom FFmpeg filter chains
- Video concatenation and splitting

### FFmpeg Processing Presets

**Quality Presets**:

| Preset | Encoder | Settings | Use Case |
|--------|----------|----------|----------|
| `web-optimized` | H.264 | CRF 23, fast preset | Web streaming, balance |
| `high-quality` | H.264 | CRF 18, slow preset | Archival, professional |
| `ultra-quality` | H.265 | CRF 20, medium preset | 4K, high detail |
| `social-media` | H.264 | CRF 25, fast preset | Instagram, TikTok |
| `tiny` | H.264 | CRF 30, veryfast preset | Thumbnails, previews |
| `max-compression` | H.265 | CRF 28, slow preset | Storage optimization |

**Effect Presets**:

| Preset | Filters | Effect |
|--------|----------|--------|
| `cinematic` | film grain, color grading, vignette | Film-like look |
| `dreamy` | blur, brightness+, saturation+, overlay | Soft, ethereal |
| `vintage` | sepia, contrast-, noise | Nostalgic, aged |
| `dramatic` | contrast+, saturation+, sharpness | High impact |
| `clean` | denoise, sharpen, white balance | Professional look |
| `slow-motion` | fps×2, smooth motion | Slow motion effect |

### FFmpeg Command Examples

**Quality Optimization**:
```bash
# High-quality H.264 encoding
ffmpeg -i input.mp4 -c:v libx264 -crf 18 -preset slow output.mp4

# Web-optimized with bitrate
ffmpeg -i input.mp4 -c:v libx264 -b:v 2M -maxrate 2M -bufsize 4M output.mp4

# H.265 for better compression
ffmpeg -i input.mp4 -c:v libx265 -crf 20 -preset medium output.mp4
```

**Video Filters**:
```bash
# Color correction
ffmpeg -i input.mp4 -vf "eq=brightness=0.1:contrast=1.1:saturation=1.2" output.mp4

# Blur background
ffmpeg -i input.mp4 -vf "split[a][b];[a]scale=iw:2*ih[b];[b][a]overlay=(W-w)/2:(H-h)/2:shortest=1" output.mp4

# Add vignette
ffmpeg -i input.mp4 -vf "vignette" output.mp4

# Speed up (2x)
ffmpeg -i input.mp4 -filter:v "setpts=0.5*PTS" output.mp4

# Slow down (0.5x)
ffmpeg -i input.mp4 -filter:v "setpts=2.0*PTS" output.mp4
```

**Audio Processing**:
```bash
# Normalize audio
ffmpeg -i input.mp4 -af "loudnorm" output.mp4

# Boost volume
ffmpeg -i input.mp4 -af "volume=2.0" output.mp4

# Extract audio
ffmpeg -i input.mp4 -vn -acodec libmp3lame output.mp3

# Replace audio
ffmpeg -i video.mp4 -i audio.mp3 -c:v copy -c:a aac -map 0:v:0 -map 1:a:0 output.mp4
```

**Text & Overlay**:
```bash
# Add text watermark
ffmpeg -i input.mp4 -vf "drawtext=text='Copyright':fontcolor=white:fontsize=24:x=10:y=10" output.mp4

# Add logo overlay
ffmpeg -i input.mp4 -i logo.png -filter_complex "overlay=10:10" output.mp4

# Burn-in subtitles
ffmpeg -i input.mp4 -vf "subtitles=subs.srt" output.mp4
```

**Batch Processing**:
```bash
# Process all videos in directory
for f in *.mp4; do
    ffmpeg -i "$f" -c:v libx264 -crf 23 -preset fast "optimized_$f"
done
```

### Hardware Acceleration

**NVIDIA (NVENC)**:
```bash
ffmpeg -i input.mp4 -c:v h264_nvenc -preset p4 -b:v 5M output.mp4
```

**Intel (QSV)**:
```bash
ffmpeg -i input.mp4 -c:v h264_qsv -preset medium -b:v 5M output.mp4
```

**AMD (VAAPI)**:
```bash
ffmpeg -i input.mp4 -c:v h264_vaapi -b:v 5M output.mp4
```

### When to Use FFmpeg Advanced Processing

**Use FFmpeg when**:
- Need professional-quality encoding
- Applying complex video filters
- Batch processing multiple videos
- Optimizing for specific platforms
- Adding watermarks or overlays
- Extracting or replacing audio
- Creating slow motion or fast forward effects
- Color correction or grading

**Skip FFmpeg when**:
- Simple cuts and basic transitions (use merge-images-to-video.py)
- Basic subtitle addition (use add-subtitles.py)
- Simple audio addition (use add-audio.py)
- When quality is already sufficient

### Integration with Video Generator Workflow

**Step 7: Post-Processing** is the ideal place to apply FFmpeg enhancements:

1. **Quality Optimization**: Apply quality preset based on target platform
2. **Effects**: Apply effect preset for visual style
3. **Platform Optimization**: Optimize for social media, web, or archival
4. **Batch Processing**: Process multiple scene videos in one pass

See [Step 7: Post-Processing](#step-7-post-processing) for FFmpeg integration examples.

**Note**: FFmpeg processing is optional. Videos can be finalized without FFmpeg enhancement if they meet quality requirements.

## Remotion-Inspired Concepts

Inspired by Remotion's declarative animation and frame-precise control, these concepts enhance AI video generation with structured, predictable, and data-driven approaches.

### Core Concepts

**Declarative Animation Description**:
- **What**, not **How**: Describe the visual outcome, not the technical implementation
- **State transitions**: Define start and end states, let interpolation happen naturally
- **Motion types**: Use standard motion vocabulary (ease-in, ease-out, spring, bounce, elastic)
- **Timing control**: Specify precise timing with second-level granularity

**Frame-Precise Time Control**:
- **Scene boundaries**: Mark exact start and end times for each scene
- **Animation duration**: Specify how long transitions take (e.g., "0.5s slide-in", "2s fade")
- **Sequential vs parallel**: Define which animations happen together or sequentially
- **Audio sync**: Time visual elements to match audio beats or speech patterns

**Data-Driven Visual Generation**:
- **Dynamic content**: Visualize data directly (charts, graphs, progress bars)
- **Conditional visuals**: Change visuals based on data thresholds
- **Lists and iterations**: Generate repeated visual patterns for lists/arrays
- **Real-time simulation**: Show processes evolving over time

**Component-Based Visual Elements**:
- **Reusable templates**: Define visual patterns that repeat across scenes
- **Variation on theme**: Same structure, different content (e.g., "same card layout, different data")
- **Composition**: Build complex scenes from simple components
- **Inheritance**: Styles and behaviors propagate from parent to child elements

### Motion Vocabulary

Use these precise motion terms when describing animations:

| Motion Type | Description | Duration | Use Case |
|--------------|-------------|----------|-----------|
| `ease-in` | Accelerates at start | 0.3-0.5s | Element appears, fades in |
| `ease-out` | Decelerates at end | 0.3-0.5s | Element disappears, fades out |
| `ease-in-out` | Accelerates then decelerates | 0.5-1.0s | Natural movement |
| `spring` | Bouncy, elastic | 1.0-2.0s | Playful, attention-grabbing |
| `bounce` | Bounces at end | 0.8-1.5s | Energetic transitions |
| `elastic` | Stretches and snaps back | 1.0-2.0s | Playful, fun |
| `linear` | Constant speed | Any duration | Scrolling, continuous motion |
| `step` | Discrete jumps | 0.1-0.3s | Digital, technical effects |
| `overshoot` | Goes past then returns | 0.6-1.2s | Emphasized arrival |
| `wobble` | Side-to-side oscillation | 0.5-1.5s | Uncertainty, playfulness |

### Time Control Syntax

**Scene Timing**:
```
Scene N (Start-End): Title
  Duration: X seconds
  Animation: slide-in from left (0.5s ease-in)
```

**Animation Timing**:
```
Element: Text block
  - Appears at 0s: Fade in (0.3s ease-in)
  - Moves up at 2s: Translate -50px (0.8s ease-out)
  - Disappears at 4s: Fade out (0.3s ease-in)
```

**Parallel Animations**:
```
Elements: Text + Icon
  - 0s: Both fade in (0.3s ease-in-out) [PARALLEL]
  - 2s: Icon scales up (0.5s spring) [PARALLEL]
```

**Sequential Animations**:
```
Elements: List items
  - 0s: Item 1 slides in (0.3s ease-out) [SEQUENCE]
  - 0.2s: Item 2 slides in (0.3s ease-out) [SEQUENCE]
  - 0.4s: Item 3 slides in (0.3s ease-out) [SEQUENCE]
```

### Data-Driven Patterns

**List Visualization**:
```
For each item in list:
  - Template: Card with icon + title + description
  - Animation: Staggered slide-in (0.2s delay between items)
  - Position: Grid or staggered stack
```

**Chart Visualization**:
```
Data: [10, 25, 40, 30, 55]
- Bar chart: Bars grow from 0% to 100% (2s ease-out)
- Labels: Fade in sequentially with bars
- Highlight: Accent color on bar at index 3
```

**Progress Animation**:
```
Data: Progress from 0% to 100% over 5 seconds
- Visual: Progress bar fills (5s linear)
- Percentage: Counter animates from 0 to 100 (5s linear)
- Color: Changes from red to green as progress increases
```

**Timeline Animation**:
```
Timeline: 5 key points over 10 seconds
- 0s: Point A appears (0.3s fade-in)
- 2s: Line A→B draws (0.8s ease-out)
- 2.5s: Point B appears (0.3s fade-in)
- 5s: Line B→C draws (0.8s ease-out)
...
```

### Component Templates

**Reusable Visual Components** define consistent patterns:

**Card Component**:
```
Template:
┌─────────────────┐
│ [Icon]          │
│ Title Text      │
│ Description     │
└─────────────────┘
Variations:
- Size: Small, medium, large
- Colors: Primary, secondary, accent
- Border: Rounded or sharp corners
```

**Stat Card Component**:
```
Template:
┌─────────────────┐
│   12,456        │
│  +23% vs last    │
└─────────────────┘
Variations:
- Metric: Number, percentage, currency
- Trend: Arrow up/down/side, color-coded
```

**Timeline Component**:
```
Template:
●─────●─────●─────●
 A      B      C      D
Variations:
- Style: Solid, dashed, dotted lines
- Markers: Circles, squares, diamonds
- Direction: Horizontal, vertical
```

### Integration with Video Generation

**When Generating Prompts**:

Apply Remotion-inspired concepts in AI prompts:

**Instead of**: "Show the elements moving around"
**Use**: "Elements slide in from left to center using 0.5s ease-in animation"

**Instead of**: "Animate the chart"
**Use**: "Chart bars grow sequentially from 0% to 100% over 2 seconds, each bar with 0.2s staggered delay, ease-out timing"

**Instead of**: "Show the data points"
**Use**: "Data points appear as circles, connected by lines that draw from left to right over 1.5s with smooth ease-in-out animation"

**When Creating Storyboards**:

Include precise timing and animation specifications:

```
## Scene 1 (0-3s)

**Purpose**: Hook, grab attention
**Superpower**: Amplifier
**Animation**: Title slides in from left (0.5s spring), subtitle fades in (0.3s ease-in, 0.3s delay)
**Visual Content**: [describe]
```

### Example: Data-Driven Video

**Scenario**: Animated infographic showing quarterly revenue

**Remotion-Inspired Approach**:

```
## Scene 1 (0-3s)

**Title**: "Q4 Revenue Growth"
**Animation**:
  - Title appears: Zoom from 0% to 100% (0.5s spring)
  - Subtitle: Fade in (0.3s ease-in, 0.2s delay)

## Scene 2 (3-8s)

**Visual**: Bar chart showing 4 quarters
**Data**: [Q1: $2.3M, Q2: $2.8M, Q3: $3.1M, Q4: $4.2M]
**Animation**:
  - Bars grow sequentially from 0% to target height (2s total, 0.5s per bar, ease-out)
  - Labels fade in with each bar (0.2s ease-in, 0.2s delay)
  - Trend arrow: Q4 highlighted with accent color (0.3s spring)

## Scene 3 (8-11s)

**Visual**: Line graph connecting quarters
**Animation**:
  - Line draws from Q1 to Q4 (2.5s ease-in-out)
  - Area fills under line with gradient (1s fade-in, 1.8s delay)
  - Highlight markers appear sequentially (0.2s ease-in, staggered)
```

### Benefits of Remotion-Inspired Concepts

- **Precision**: Frame-accurate control over timing and motion
- **Predictability**: Consistent animation patterns across scenes
- **Reusability**: Component templates enable faster iteration
- **Data-Driven**: Visuals directly represent data, no manual design needed
- **Maintainability**: Clear structure makes updates easy

**Key Principle**: Describe animations declaratively with precise timing, use standard motion vocabulary, and leverage component templates for consistency.

## Chinese Text Humanization (from Humanizer-zh)

Inspired by Humanizer-zh's approach to natural, authentic Chinese expression, these principles enhance video text, subtitles, and voiceover scripts to resonate with Chinese-speaking audiences.

### Core Principles

**Natural Flow**:
- Avoid rigid, translation-style phrasing
- Use expressions native to Chinese communication
- Prefer active voice over passive constructions
- Let sentences breathe with natural pauses

**Tone Adaptation**:
- Match tone to video type and audience
- Formal: Educational, technical content (tutorials, explainers)
- Conversational: Stories, vlogs, personal content (story, promo)
- Humorous: Entertainment, light-hearted topics (promo, story)
- Energetic: Promotional, motivational content (promo, product-demo)

**Emotional Resonance**:
- Add appropriate exclamations where natural (哇、嘿、嗯、对了)
- Use onomatopoeia for vividness (轰、啪、滴答、哗啦)
- Apply rhetorical devices for impact (repetition, parallelism, contrast)
- Let emotion guide word choice intensity

**Rhythm & Pacing**:
- Alternate short and long sentences
- Create paragraph breathing room
- Repeat key information for emphasis
- Vary sentence structure to maintain interest

**Cultural Adaptation**:
- Use metaphors familiar to Chinese audience
- Avoid direct translations of idioms (use Chinese equivalents)
- Consider cultural context in examples and references
- Reflect Chinese communication patterns

### Text Optimization Techniques

| Dimension | Stiff Expression | Natural Expression | When to Use |
|------------|-----------------|-------------------|--------------|
| **Vocabulary** | "进行讨论" | "聊聊"、"探讨一下" | Conversational |
| | "实施计划" | "按计划来做"、"照着计划走" | Conversational |
| | "获得成功" | "成功了"、"搞定"、"大功告成" | Conversational |
| **Sentence Structure** | "这是...的..." | "简单来说，..." | Explanatory |
| | "通过...来实现" | "靠...来完成"、"用...来搞定" | Conversational |
| | "需要注意的是" | "要注意的是"、"别忘了" | Conversational |
| **Tone** | "请注意" | "来看看"、"想想看" | Conversational |
| | "综上所述" | "所以，总的来说"、"这么看来" | Conversational |
| | "非常重要" | "特别关键"、"这一点很重要" | Conversational |
| **Transitions** | "因此"、"此外" | "所以"、"而且"、"更重要的是" | Conversational |
| | "然而"、"但是" | "不过"、"但是"、"话虽这么说" | Conversational |
| **Emotion** | "非常好" | "太棒了"、"简直完美"、"超级赞" | Enthusiastic |
| | "不理想" | "不太行"、"差点意思"、"还有提升空间" | Conversational |
| **Surprise** | (无) | "哇"、"天哪"、"哇塞" | Enthusiastic |
| **Realization** | "我明白了" | "原来如此"、"这下懂了"、"哦~" | Conversational |
| **Agreement** | "是的"、"正确" | "对"、"没错"、"就是" | Conversational |

### Scenario-Based Tone Guidelines

**Formal/Educational (Tutorial, Explainer)**:
- Use precise terminology and clear explanations
- Maintain logical flow with structured presentation
- Avoid excessive colloquialisms
- Keep tone steady and professional

**Examples**:
- ❌ "这个玩意儿怎么用？"
- ✅ "如何使用这个工具？"
- ❌ "搞定"
- ✅ "完成"、"实现"

**Conversational/Story (Story, Warm, Lifestyle)**:
- Use daily conversation style
- Add natural fillers (嗯、对了、话说回来)
- Include emotional markers (哈哈、哇、原来如此)
- Create intimate, approachable tone

**Examples**:
- ❌ "产品具有以下特性"
- ✅ "这产品有几个特点，来听听"
- ❌ "用户反馈"
- ✅ "大家怎么说"

**Humorous/Lighthearted (Promo, Cute, Playful)**:
- Use exaggerated expressions for comedic effect
- Add rhetorical questions
- Incorporate playful language and banter
- Keep tone lively and engaging

**Examples**:
- ❌ "这个功能很好"
- ✅ "这个功能简直绝了，谁用谁知道！"
- ❌ "价格合理"
- ✅ "价格简直不要太友好"

**Energetic/Motivational (Promo, Product-Launch)**:
- Use exclamations and strong adjectives
- Repeat key messages for emphasis
- Use power words to drive action
- Create urgency and excitement

**Examples**:
- ❌ "这个产品很好"
- ✅ "这个产品太棒了！你绝对不能错过！"
- ❌ "现在购买"
- ✅ "立刻行动，手慢无！"

### Chinese Text Templates by Type

**Explainer Template**:
```
开头：用一句话点明主题（"今天我们来聊聊..."）
中间：用"简单来说"、"举个例子"等连接词
结尾：用"总的来说"、"所以"总结要点
```

**Example**:
```
"今天我们来聊聊什么是人工智能。
简单来说，AI就是让机器学会思考的技术。
举个例子，现在的智能音箱就是AI的一种应用。
总的来说，AI已经深入我们的生活了。"
```

**Tutorial Template**:
```
开头：明确学习目标（"这一课教你如何..."）
步骤：用"首先"、"然后"、"接着"、"最后"清晰标注
提醒：用"注意一下"、"别忘了"、"重点在这里"强调关键点
```

**Example**:
```
"这一课教你如何剪辑视频。
首先，把素材导入软件。
然后，在时间线上排列顺序。
接着，添加转场效果。
最后，导出视频。
注意一下，导出格式要根据平台选择。"
```

**Story Template**:
```
开头：用"还记得吗"、"话说回来"引入
过程：用"当时"、"后来"、"没想到"描述
高潮：用"突然"、"就在这时"制造转折
结尾：用"所以"、"最终"总结感悟
```

**Example**:
```
"还记得去年这个时候吗？
当时我们团队正为一个问题发愁。
没想到，一个小建议改变了一切。
现在回想起来，真的是无心插柳柳成荫啊。"
```

**Promo Template**:
```
开头：用感叹或提问吸引注意（"想知道吗？"、"太棒了！"）
优势：用"最重要的是"、"特别厉害的是"突出卖点
行动：用"立刻"、"现在"、"机会难得"驱动转化
```

**Example**:
```
"想知道如何把效率提升10倍吗？
这款工具可以帮你自动化繁琐工作！
最厉害的是，学习成本几乎为零！
现在就试试，手慢无！"
```

### Voiceover Script Humanization

**Voiceover-Specific Optimizations**:

**Pause Markers**:
- Add natural pauses using punctuation and spacing
- "首先... 然后... 最后..." (indicates tempo)
- "对了... 说到这里..." (natural transitions)

**Emotion Indicators**:
- Use语气词 to guide delivery (微笑地、兴奋地、平静地)
- Mark emphasis (↑ important | ↓ relax)
- Indicate speed (快一点 | 慢一点)

**Rhythm Control**:
- Short phrases for rapid delivery
- Longer sentences for thoughtful moments
- Repeat key phrases for memory

**Example Voiceover Script**:
```
[微笑地，亲切]
大家好，今天我们来聊聊人工智能。

[↑强调]
简单来说，AI就是让机器学会思考。

[快一点，轻松]
现在的智能音箱、自动驾驶，都是AI的应用。

[↓放松，总结]
所以，AI已经深入我们的生活了。

[微笑，结束]
谢谢大家的观看！
```

### Text Quality Checklist

**Before Finalizing Text**:

- [ ] Tone matches video type and audience
- [ ] Phrasing feels natural, not translated
- [ ] Emotion markers are appropriate
- [ ] Rhythm varies (short/long sentences mixed)
- [ ] Cultural references resonate
- [ ] Transitions flow naturally
- [ ] Key points are emphasized
- [ ] Voiceover markers guide delivery

**Common Pitfalls to Avoid**:

- ❌ Excessive use of "的" (de) particles
- ❌ Overuse of formal connectors (因此、此外、然而)
- ❌ Stiff, machine-translation style phrasing
- ❌ Lack of emotional variation
- ❌ Monotonous sentence rhythm
- ❌ Cultural context mismatches

### Integration with Video Generation

**When Generating Storyboards**:

Apply humanization principles to text fields:

**Text Overlay**:
- Make subtitles concise and conversational
- Use natural connectors (所以、而且、对了)
- Add emotional markers where appropriate

**Voiceover Script**:
- Write in spoken Chinese, not written
- Add pause markers for natural pacing
- Include emotion indicators for AI voice generation
- Use colloquial expressions for engagement

**Example**:

**Before Humanization**:
```
Text: "人工智能技术日益成熟。通过机器学习，计算机可以完成复杂任务。"
```

**After Humanization**:
```
Text: "AI技术越来越厉害了。
简单来说，就是让机器学会思考，
搞定那些复杂的活儿。"
```

### Benefits of Chinese Text Humanization

- **Naturalness**: Feels authentic, not machine-translated
- **Engagement**: Conversational tone connects with audience
- **Memorability**: Emotional markers and rhythm enhance recall
- **Cultural Fit**: Resonates with Chinese communication patterns
- **Accessibility**: Simple, natural language is easier to understand

**Key Principle**: Write Chinese as it's spoken, not as it's translated. Match tone to audience, add natural emotional markers, and vary rhythm for engagement.

## Canvas Design & Layout (from Canvas Design)

Inspired by canvas design principles, apply structured composition and layout strategies to create visually balanced and impactful video frames.

### Core Composition Principles

**Rule of Thirds**:
- Divide canvas into 3×3 grid
- Place focal points at intersection points
- Creates dynamic, balanced composition
- Avoid centering everything

**Golden Ratio**:
- 1.618 proportion (golden spiral)
- Naturally pleasing to human eye
- Use for sizing and spacing relationships
- Spiral flow guides viewer's eye

**Diagonal Composition**:
- Creates dynamic, energetic feel
- Guides viewer's eye along diagonal
- Good for motion and action
- Adds depth and movement

**Symmetry & Asymmetry**:
- Symmetry: Balanced, stable, formal
- Asymmetry: Dynamic, interesting, modern
- Choose based on video type and tone
- Break symmetry intentionally for impact

### Visual Hierarchy

**Three Levels of Visual Importance**:

| Level | Characteristics | Use Case |
|-------|-----------------|-----------|
| **Primary** | Largest, brightest, centered, most color | Main message, focal point, call-to-action |
| **Secondary** | Medium size, supporting colors, offset from center | Supporting content, examples, details |
| **Tertiary** | Smallest, muted colors, edges/background | Background elements, decoration, ambient details |

**Hierarchy Implementation**:
- Size difference: Primary 2-3x larger than Secondary
- Color contrast: Primary highest, Tertiary lowest
- Position: Primary at focal point, Tertiary at edges
- Motion: Primary moves most, Tertiary least or static

### Grid Systems

**Grid-Based Layouts**:

| Grid | Columns | Best For | Complexity |
|------|----------|-----------|-------------|
| **4-Column** | 4 | Simple layouts, large elements | Low |
| **6-Column** | 6 | Balanced layouts, versatile | Medium |
| **12-Column** | 12 | Complex layouts, flexible | High |
| **Mixed** | Variable | Custom layouts, adaptive | Variable |

**Grid Usage**:
```
4-Column Grid:
┌───┬───┬───┬───┐
│   │   │   │   │
└───┴───┴───┴───┘

6-Column Grid:
┌─┬─┬─┬─┬─┬─┐
│ │ │ │ │ │ │
└─┴─┴─┴─┴─┴─┘

12-Column Grid:
┌─┬─┬─┬─┬─┬─┬─┬─┬─┬─┬─┬─┬─┐
│ │ │ │ │ │ │ │ │ │ │ │ │ │
└─┴─┴─┴─┴─┴─┴─┴─┴─┴─┴─┴─┴─┴─┘
```

**Grid Spanning**:
- Primary element: Span 8-12 columns
- Secondary element: Span 4-8 columns
- Tertiary element: Span 2-4 columns
- Full-width: Span all columns

### Layout Patterns

**Common Layout Patterns**:

| Pattern | Structure | Best For | Example |
|---------|-----------|-----------|----------|
| **Single Column** | Centered vertical stack | Focus, tutorials, title cards | Title centered, content below |
| **Two Column** | Split 50/50 or 60/40 | Comparison, text + visual | Left text, right visual |
| **Split Screen** | Vertical 50/50 division | Contrast, before/after | Old vs new, A/B comparison |
| **Mosaic** | Grid of equal-sized elements | Gallery, showcase, playlist | Product grid, photo album |
| **Waterfall** | Staggered vertical elements | Social feed, timeline | Instagram-style layout |
| **Radial** | Center outward radiation | Emphasis, explosions | Focus point, central message |
| **Z-Layout** | Diagonal zigzag | Information flow, story progression | Narrative path |

**Layout Examples**:

**Single Column (Suitable for: 16:9, 9:16, 1:1)**:
```
┌─────────────────┐
│                 │
│  [标题/焦点]   │  Primary
│                 │
│  [主内容]     │  Secondary
│                 │
│  [次要内容]   │  Tertiary
│                 │
└─────────────────┘
```

**Two Column (Suitable for: 16:9, 4:3)**:
```
┌─────────────────┐
│ [左列] [右列] │  Secondary
│ [内容] [内容]  │  Secondary
│                 │
│ [底部内容]     │  Primary
└─────────────────┘
```

**Split Screen (Suitable for: 16:9, 4:3)**:
```
┌─────────────────┐
│ [左半] [右半]  │  Primary / Secondary
│ [内容] [内容]   │  Primary / Secondary
│                 │
│ [底部内容]     │  Tertiary
└─────────────────┘
```

**Radial (Suitable for: 1:1, 16:9)**:
```
┌─────────────────┐
│       ↑         │  Tertiary
│    ←[中心]→    │  Primary
│       ↓         │  Tertiary
│                 │
└─────────────────┘
```

**Mosaic (Suitable for: 16:9)**:
```
┌──────┬──────┐
│ [1]  │ [2]  │  Secondary
├──────┼──────┤
│ [3]  │ [4]  │  Secondary
└──────┴──────┘
   [Primary Title]
```

### Aspect Ratio Adaptation

**Layouts by Aspect Ratio**:

| Aspect Ratio | Recommended Layouts | Video Types |
|-------------|-------------------|-------------|
| **16:9** (Landscape) | Single column, Two column, Split screen, Mosaic | Tutorial, Explainer, Promo, Story |
| **9:16** (Portrait) | Single column, Waterfall, Radial | Instagram Reels, TikTok, Vertical content |
| **1:1** (Square) | Single column, Radial, Mosaic | Instagram Post, Social media, Balanced content |
| **4:3** (Classic) | Single column, Two column, Split screen | Vintage, Retro, Traditional content |

**Aspect Ratio Guidelines**:

**16:9 (Landscape)**:
- Best for: Tutorials, movies, presentations
- Use horizontal layouts
- Leverage width for side-by-side content
- Grid works well for multi-element

**9:16 (Portrait)**:
- Best for: Short videos, mobile-first
- Use vertical stacks
- Focus on single element at a time
- Scrolling waterfall pattern natural

**1:1 (Square)**:
- Best for: Social media posts, balanced content
- Centered composition works well
- Symmetrical layouts are effective
- Good for radial or mosaic patterns

**4:3 (Classic)**:
- Best for: Retro, vintage, traditional
- Classic layouts (single/two column) feel authentic
- Slightly more vertical than 16:9
- Good for nostalgic content

### Canvas Design by Video Type

**Tutorial**:
- Layout: Single column or Two column
- Grid: 6-column for structured steps
- Hierarchy: Clear step-by-step progression
- Focus: Step numbers, visual demonstrations

**Explainer**:
- Layout: Single column or Radial
- Grid: 4-column for simplicity
- Hierarchy: Title → Concept → Details
- Focus: Main message, supporting visuals

**Story**:
- Layout: Waterfall or Z-Layout
- Grid: Flexible mixed grid
- Hierarchy: Emotional beats vary in importance
- Focus: Character, emotional moments

**Promo**:
- Layout: Split screen or Radial
- Grid: 12-column for complex composition
- Hierarchy: Product primary, features secondary
- Focus: Product, call-to-action, brand

**Animated Infographic**:
- Layout: Mosaic or Z-Layout
- Grid: 12-column for data visualization
- Hierarchy: Chart primary, labels secondary
- Focus: Data points, trends, comparisons

### Canvas Design Integration with Existing Systems

**Frontend-Design Synergy**:
- Canvas composition extends aesthetic principles
- Spatial composition from frontend-design applies to canvas
- Backgrounds and details align with canvas hierarchy

**Remotion Components**:
- Remotion components align to canvas grid
- Component sizing follows grid columns
- Component positioning respects visual hierarchy

**Type × Style Alignment**:
| Type | Recommended Layout | Styles |
|-------|-------------------|---------|
| Tutorial | Single/Two Column | Chalkboard, Minimal, Technical-Schematic |
| Explainer | Single Column | All styles |
| Story | Waterfall/Z-Layout | Warm, Watercolor, Craft-Handmade |
| Promo | Split Screen/Radial | Bold-Editorial, Cyberpunk-Neon |
| Animated Infographic | Mosaic | Technical-Schematic, Minimal, Algorithmic |

### Canvas Design Checklist

**Before Finalizing Canvas Layout**:

- [ ] Aspect ratio is specified and layout adapted
- [ ] Grid system chosen (4/6/12-column or mixed)
- [ ] Visual hierarchy is clear (Primary/Secondary/Tertiary)
- [ ] Focal points follow composition rules (thirds, golden ratio)
- [ ] Layout pattern matches video type
- [ ] Negative space is intentional, not accidental
- [ ] Elements are aligned to grid
- [ ] Color and size reinforce hierarchy
- [ ] Motion follows layout flow

**Common Canvas Design Pitfalls**:

- ❌ Centering everything (boring, lacks dynamism)
- ❌ No visual hierarchy (flat, confusing)
- ❌ Inconsistent alignment (messy, unprofessional)
- ❌ Ignoring aspect ratio (awkward composition)
- ❌ Too many focal points (distracting)
- ❌ Grid misalignment (disjointed, chaotic)

### Integration with Video Generation

**When Creating Storyboards**:

Apply canvas design to scene descriptions:

```
## Scene N (Start-End)

**Canvas Layout**: Single column, 6-column grid
**Primary Element**: Centered at top intersection of thirds
**Secondary Elements**: Flank primary, span 2 columns each
**Tertiary Elements**: Bottom corners, minimal detail
**Composition**: Rule of thirds with diagonal flow
```

**When Generating Visual Prompts**:

Include canvas and layout instructions:

**Instead of**: "Show elements on screen"
**Use**: "Primary title centered at top-third intersection, 6-column grid, secondary elements flank at 2-column spans each, tertiary details at bottom corners"

**Benefits of Canvas Design**:

- **Balance**: Structured composition creates visual harmony
- **Focus**: Clear hierarchy guides viewer's eye
- **Consistency**: Grid-based layouts unify multiple scenes
- **Flexibility**: Layout patterns adapt to different content
- **Professionalism**: Intentional composition looks designed, not random

**Key Principle**: Use grid systems and visual hierarchy to create balanced, focused compositions. Match layout to aspect ratio and video type. Break rules intentionally for impact, not accidentally.

## Persuasive Copywriting (from Copywriting)

Inspired by persuasive copywriting principles, these techniques enhance video text, headlines, hooks, and calls-to-action to maximize engagement and conversion.

### Core Copywriting Principles

**Headline & Hook (标题和钩子)**:

| Principle | Description | Example |
|----------|-------------|----------|
| **3-Second Rule** | Grab attention in first 3 seconds | "你知道吗..." "这个秘密..." |
| **Curiosity** | Trigger curiosity or surprise | "为什么90%的人都..." |
| **Clear Benefit** | Tell viewers what they'll gain | "学会这3个技巧..." |
| **Numbers** | Specific numbers are persuasive | "5倍提升" "30天见效" |

**Call-to-Action (行动号召)**:

| Principle | Description | Example |
|----------|-------------|----------|
| **Clear Direction** | Tell viewers exactly what to do | "点击链接" "现在订阅" |
| **Urgency** | Create time scarcity | "最后3天" "限时优惠" |
| **Low Friction** | Reduce action barriers | "一键关注" "免费试用" |
| **Power Verbs** | Use strong action verbs | "解锁" "立即开始" "立即行动" |

### Copywriting Structure Models

**AIDA Model**:

```
A - Attention (注意): Grab attention with headline/hook
I - Interest (兴趣): Maintain interest with compelling content
D - Desire (欲望): Trigger desire with benefits and emotions
A - Action (行动): Drive action with CTA
```

**Example**:
```
A: "你知道吗？90%的创业者都犯了这3个错误"
I: "这些错误让努力付诸东流，让人心碎"
D: "但如果你学会这几个技巧，就能轻松避坑，成功翻倍"
A: "点击下方链接，立即获取完整指南"
```

**PAS Model**:

```
P - Problem (问题): Describe the problem viewers face
A - Agitation (煽动): Amplify the pain of the problem
S - Solution (解决): Provide the solution
```

**Example**:
```
P: "每天都在加班，却没什么进展"
A: "看着别人轻松成功，你是不是开始怀疑自己？"
S: "其实，只要掌握这几个方法，效率瞬间提升5倍"
```

**Story Arc (故事弧线)**:

```
Hook → Conflict → Resolution → Takeaway
```

**Example**:
```
Hook: "还记得刚开始做视频的时候吗？"
Conflict: "我也曾连续熬夜，点击率却不到1%"
Resolution: "直到我发现这个秘密，播放量暴涨10倍"
Takeaway: "这个方法，你也可以学会"
```

### Persuasive Techniques

**Social Proof (社会证明)**:
- "已经有10,000人学会了这个方法"
- "90%的用户都选择了这个方案"
- "大家都说这个工具好用"

**Authority (权威性)**:
- "根据专家研究..."
- "10年经验总结..."
- "行业顶级..."

**Scarcity (稀缺性)**:
- "仅限前100名"
- "最后3天"
- "独家优惠"

**Urgency (紧迫感)**:
- "立即行动，错过等一年"
- "限时免费"
- "今天就截止"

**Contrast (对比)**:
- "过去 vs 现在"
- "传统 vs 新方法"
- "付出 vs 收获"

**Emotional Triggers (情感触发)**:
- **Fear**: "别再错过..." "不想..."
- **Hope**: "想象一下..." "未来..."
- **Desire**: "梦想成真" "轻松搞定"
- **FOMO (错失恐惧)**: "别人都知道了"

### Chinese Copywriting Characteristics

**Strong Verbs (强动词)**:

| 普通表达 | 强力表达 | 语气提升 |
|----------|---------|---------|
| "使用这个方法" | "秒杀问题" | 更有冲击力 |
| "学会技巧" | "解锁能力" | 更有吸引力 |
| "开始行动" | "立即出击" | 更紧迫 |
| "尝试一下" | "立刻体验" | 更直接 |

**Digital Expression (数字化表达)**:
- ❌ "很多技巧" → ✅ "7个技巧"
- ❌ "提升很大" → ✅ "5倍提升"
- ❌ "很多人用" → ✅ "10,000人都在用"

**Short & Punchy (简短有力)**:
- 避免长句，使用短句
- 每句话传达一个信息
- 用感叹号加强语气

**Direct Address (直接称呼)**:
- 使用"你"、"我们"
- 创造对话感
- 建立连接

### Emotional Connection

**Empathy (共情)**:
```
"我知道你也在为这个问题烦恼"
"我也曾和你一样..."
```

**Shared Experience (共同经历)**:
```
"是不是每天都被消息轰炸？"
"大家都有过这种经历吧？"
```

**Desire Fulfillment (愿望满足)**:
```
"想象一下，工作效率提升10倍会怎样"
"终于，你可以轻松搞定所有事"
```

**Fear & Hope (恐惧和希望)**:
```
Fear: "别再浪费时间了，方法不对，努力白费"
Hope: "但今天，你找到了正确的方法"
```

### Copywriting by Video Type

**Tutorial (教程)**:
- Hook: "这个技巧，90%的人都不知道"
- CTA: "试试看，学会记得点赞"
- Tone: Helpful, expert, encouraging

**Example**:
```
Hook: "想知道怎么让视频点击率翻3倍吗？"
Content: "这个技巧，专业剪辑师都在用"
CTA: "关注我，学更多实战技巧"
```

**Explainer (讲解)**:
- Hook: "3分钟搞懂[复杂概念]"
- CTA: "转发给需要的朋友"
- Tone: Clear, educational, valuable

**Example**:
```
Hook: "AI到底是什么？3分钟彻底搞懂"
Content: "不搞技术，只说人话"
CTA: "收藏备用，转发给好奇的朋友"
```

**Promo (促销)**:
- Hook: "限时优惠！错过等一年"
- CTA: "立即购买，手慢无"
- Tone: Exciting, urgent, persuasive

**Example**:
```
Hook: "重磅！今天限时半价，仅此一天"
Content: "原价999，今天只要499"
CTA: "立即抢购，库存告急"
```

**Story (故事)**:
- Hook: "还记得吗？那时候..."
- CTA: "如果你也经历过，点个赞"
- Tone: Emotional, relatable, inspiring

**Example**:
```
Hook: "还记得第一次做视频的窘迫吗？"
Content: "连续熬夜一个月，播放量却只有个位数"
CTA: "点赞鼓励，下期分享逆袭方法"
```

### Copywriting Templates

**Headline Templates (标题模板)**:

| Type | Template | Example |
|------|----------|----------|
| **Question** | "你知道吗[惊人的事实]？" | "你知道吗，90%的人做视频都错了方向？" |
| **Number List** | "[数字]个[技巧/方法]搞定[问题]" | "5个技巧，让你的视频点击率翻倍" |
| **Promise** | "[时间/程度]学会[技能]" | "3分钟学会专业剪辑" |
| **Secret** | "这个[方法]，[数字]%的人都不知道" | "这个方法，80%的人都不懂" |
| **Contrast** | "过去[付出] vs 现在[轻松]" | "过去3小时，现在3分钟" |

**Hook Templates (钩子模板)**:

| Type | Template | Example |
|------|----------|----------|
| **Curiosity** | "你可能不知道..." | "你可能不知道，这个功能可以这么用" |
| **Surprise** | "想不到吧，[意外结果]" | "想不到吧，原来这么简单" |
| **Challenge** | "敢不敢[挑战动作]" | "敢不敢试试这个挑战？" |
| **Empathy** | "我知道你也在[烦恼]" | "我知道你也在为内容发愁" |
| **Authority** | "根据[专家/研究]，[结论]" | "根据专家研究，这个方法最有效" |

**CTA Templates (行动号召模板)**:

| Type | Template | Example |
|------|----------|----------|
| **Direct** | "[动作] + [目标]" | "关注获取更多技巧" |
| **Urgent** | "立即[动作]，[后果]" | "立即订阅，错过等一年" |
| **Benefit** | "[动作] + [利益]" | "点击链接，免费获取指南" |
| **Incentive** | "[动作] + [奖励]" | "点赞评论，送神秘礼包" |

### Copywriting Integration with Humanizer-zh

**Natural + Persuasive**:
- Humanizer-zh: Natural, authentic, conversational
- Copywriting: Persuasive, compelling, action-oriented

**Combined Approach**:
```
Pure Natural: "今天我们来聊聊AI"
Pure Persuasive: "立即学习AI，提升效率10倍"
Combined: "今天来聊聊AI，学会了效率瞬间提升10倍！"
```

**Balance**:
- Not too salesy: Maintain authenticity
- Not too passive: Include clear CTAs
- Match tone to video type

### Copywriting Checklist

**Before Finalizing Copy**:

- [ ] Headline/hook grabs attention in first 3 seconds
- [ ] Benefit is clear and specific
- [ ] Numbers are used where persuasive
- [ ] CTA is clear and actionable
- [ ] Urgency is created if appropriate
- [ ] Emotional triggers are intentional
- [ ] Social proof is included if relevant
- [ ] Tone matches video type and audience
- [ ] Direct address creates connection
- [ ] Chinese expressions are natural and strong

**Common Copywriting Pitfalls**:

- ❌ Generic headlines ("Welcome", "Introduction")
- ❌ Vague benefits ("improves", "helps")
- ❌ Weak CTAs ("learn more", "click here")
- ❌ No urgency or scarcity
- ❌ Overly salesy tone
- ❌ Long, rambling sentences
- ❌ No specific numbers
- ❌ Missing emotional connection

### Integration with Video Generation

**When Generating Storyboards**:

Apply copywriting principles:

```
## Scene 1 (0-5s)

**Hook**: "你知道吗？这个方法让效率提升10倍" (Curiosity + Number)
**Purpose**: Grab attention, create curiosity
**Text Overlay**: [benefit-focused text]
**CTA**: [at end of video] "立即行动，点击链接"
```

**When Generating Voiceover Scripts**:

Include persuasive elements:

```
[热情，兴奋]
大家好！

[好奇，期待]
今天来分享一个秘密，
90%的人都不知道...

[真诚，帮助]
学会了这个方法，
你也能轻松搞定...

[紧迫，鼓励]
别再等了，
现在就试试吧！
```

### Xiaohongshu-Style Copywriting (小红书文案)

**Characteristics**:

- **Fresh & Youthful**: Fresh, refined, youthful tone
- **Emoji-Rich**: Use emojis for visual interest (not excessive)
- **Short & Punchy**: Concise, impactful sentences
- **Number-Based**: Use numbers for structure ("10 tips", "5 steps")
- **Community-Focused**: Encourage engagement (follow, like, comment)
- **Authentic**: Honest, relatable, not overly salesy

**Title/Hook Templates** (小红书标题):

| Type | Template | Example |
|------|----------|----------|
| **Number List** | "[数字]个[技巧/方法]，[结果]" | "5个技巧，皮肤好到发光" |
| **Before/After** | "过去[痛点] → 现在[结果]" | "过去3小时 → 现在30分钟" |
| **Secret** | "这个[方法]，[数字]%的人都不知道" | "这个方法，80%的人都不懂" |
| **Urgent** | "别再[错误行为]了！" | "别再乱护肤了！" |
| **Question** | "[问题]？我来教你" | "痘痘总反复？我来教你" |
| **Promise** | "[时间/程度]搞定[技能]" | "3分钟学会淡斑" |

**Content Structure**:

```
[大标题 + 表情符号] ✨

[简短引言]
今天分享超实用的[主题]...

[列出要点]
1️⃣ 第一个技巧 [详细说明]
2️⃣ 第二个技巧 [详细说明]
3️⃣ 第三个技巧 [详细说明]

[关键提示]
💡 记住：[重点]

[CTA]
❤️ 关注我，下次不迷路
👍 点赞收藏，随时查看
💬 有问题评论区见
```

**Example Complete Copy**:

```
✨ 10个秋季护肤技巧，皮肤好到发光

姐妹们！秋天来了，
护肤也要换方法啦！
今天分享10个超实用技巧~

1️⃣ 温和清洁
不要过度去油，
选温和洁面乳，
早晚各一次就够了~

2️⃣ 及时补水
秋天皮肤容易干，
选清爽保湿产品，
随时补水别偷懒！

3️⃣ 防晒不能忘
秋季紫外线依然强，
出门一定要涂防晒！

💡 关键提示：
从今天开始试试看，
坚持一周就能看到效果！

❤️ 关注我，每天一个护肤小技巧
👍 觉得有用记得点赞~
💬 有问题评论区告诉我
```

**Xiaohongshu-Specific Guidelines**:

1. **Emoji Usage**:
   - Use 3-5 emojis per post (not excessive)
   - Place emojis at line starts or ends
   - Choose relevant, current emojis
   - Avoid outdated or unclear emojis

2. **Tone**:
   - Friendly, relatable (姐妹们, 宝子们)
   - Enthusiastic (超实用, 绝了, 必须学会)
   - Authentic (真实分享, 亲测有效)
   - Encouraging (试试看, 你可以的)

3. **Structure**:
   - Clear number-based list (1️⃣2️⃣3️⃣)
   - Short, readable paragraphs (2-3 lines max)
   - Emphasized key points (💡, ⭐, ✅)
   - Strong CTA (follow, like, comment)

4. **Length**:
   - Title: 10-20 characters (including emojis)
   - Body: 150-300 characters total
   - Keep it concise and scannable

5. **Keywords** (boost discoverability):
   - #秋季护肤 #护肤技巧 #干皮护肤
   - #护肤分享 #护肤日常
   - Use 3-5 relevant hashtags

**Common Xiaohongshu Phrases**:

- Opening: "姐妹们！", "宝子们！", "今天分享..."
- Emphasis: "真的绝了", "太好用了", "必须学会"
- Proof: "亲测有效", "真实分享", "我的使用感"
- CTA: "关注我不迷路", "记得点赞收藏", "评论区见"

**Video Integration**:

When creating Xiaohongshu-style videos:

```
Scene 1 (0-3s): Hook = Title + Emoji ✨
Scene 2-4 (3-30s): Content = Numbered points 1️⃣2️⃣3️⃣
Scene 5 (30-45s): Key tip = 💡 Highlighted point
Scene 6 (45-60s): CTA = ❤️ Follow/Like buttons
```

See [references/xiaohongshu-design.md](references/xiaohongshu-design.md) for complete Xiaohongshu design specifications.

### Benefits of Persuasive Copywriting

- **Engagement**: Strong hooks grab and hold attention
- **Conversion**: Clear CTAs drive desired actions
- **Memorability**: Emotional connections make content memorable
- **Clarity**: Clear benefits and numbers eliminate ambiguity
- **Urgency**: Time-sensitive prompts reduce procrastination

**Key Principle**: Grab attention in first 3 seconds, maintain interest with compelling content, trigger desire with benefits and emotions, and drive action with clear, compelling CTAs.

## Visual Skills (from axton-obsidian-visual-skills)

Inspired by visual thinking and structured knowledge representation, these skills transform complex information into organized, visual content perfect for video creation.

### Core Visual Skills

**6 Essential Skills**:

| Skill | Description | Best For | Video Type Application |
|-------|-------------|-----------|----------------------|
| **Mind Mapping** | Central idea with branching concepts | Brainstorming, content organization | Explainer, Story, Tutorial |
| **Flowcharts** | Process steps with decision points | Process explanation, workflows | Tutorial, Animated Infographic |
| **Concept Maps** | Connected concepts with labeled relationships | Understanding relationships, complexity | Explainer, Animated Infographic |
| **Timelines** | Chronological sequence of events | History, progress, narratives | Story, Promo, Documentary |
| **Org Charts** | Hierarchical structure of relationships | Organizational breakdowns, roles | Explainer, Tutorial |
| **Knowledge Graphs** | Network of connected information points | Complex systems, interconnections | Explainer, Animated Infographic |

### Mind Mapping (思维导图)

**Structure**:
```
        [主题/Central Idea]
              /  |  \
    [分支1] [分支2] [分支3]
      /  |  \     /  |  \
  [子1][子2]  [子3][子4]
```

**Video Transformation**:

| Mind Map Element | Video Equivalent | Scene Structure |
|-----------------|-------------------|-----------------|
| Central Idea | Main title/theme | Scene 1: Hook, introduce main topic |
| Main Branches | Key sections/scenes | Scenes 2-N: Each branch = 1-2 scenes |
| Sub-branches | Detailed points | Detailed content within scenes |
| Connections | Transitions | Smooth transitions between related scenes |

**Example Transformation**:
```
Mind Map:
[AI应用]
    /      |      \
[医疗]  [教育]  [创意]
              /  \
          [个性化学习][智能辅导]

→ Video:
Scene 1 (0-5s): "AI应用无处不在" (Central)
Scene 2 (5-15s): "医疗：AI诊断疾病" (Branch 1)
Scene 3 (15-25s): "教育：个性化学习" (Branch 2)
Scene 4 (25-35s): "创意：AI创作内容" (Branch 3)
```

**Best Practices**:
- Use central topic as video hook
- Level hierarchy: Main branches = main sections
- Group related sub-branches into same scene
- Create logical flow from center to periphery

### Flowcharts (流程图)

**Structure**:
```
[开始] → [步骤1] → [决策点]
                ↓          ↓
           [步骤2a]    [步骤2b]
                ↓          ↓
              [步骤3] → [结束]
```

**Video Transformation**:

| Flowchart Element | Video Equivalent | Scene Structure |
|-------------------|-------------------|-----------------|
| Start | Hook, introduction | Scene 1: "Let's begin..."
| Steps | Sequential scenes | Scenes 2-N: One step per scene |
| Decision Points | Branching narratives | Option for "if/else" scenarios |
| End | Conclusion, CTA | Final scene: "That's it! Now you know..."

**Example Transformation**:
```
Flowchart:
[开始] → [分析问题] → [选择方案]
                        /      ↓
                   [方案A]  [方案B]
                      ↓        ↓
                   [实施] → [结束]

→ Video:
Scene 1 (0-5s): "第一步：分析问题"
Scene 2 (5-15s): "第二步：选择最佳方案"
Scene 3 (15-25s): "方案A：快速但简单" (Branch A)
Scene 3 alt (15-25s): "方案B：慢但完整" (Branch B)
Scene 4 (25-35s): "第三步：实施所选方案"
Scene 5 (35-40s): "搞定！"
```

**Decision Point Handling**:
- Show both paths briefly or focus on one
- Use "or", "alternatively", "another approach" in narration
- Visuals can split-screen or sequential

### Concept Maps (概念图)

**Structure**:
```
       [概念A]
         /  \
    [关联]  [关系]
        \    /
       [概念B]
```

**Video Transformation**:

| Concept Map Element | Video Equivalent | Scene Structure |
|-------------------|-------------------|-----------------|
| Concepts | Core information | Scenes 1-N: Each concept = 1 scene |
| Connections | Relationships | Transitions and overlays showing relationships |
| Labels | Relationship types | Text overlays: "causes", "is part of", "relates to" |

**Example Transformation**:
```
Concept Map:
[气候变化]
   /    |    \
[原因]  [影响]  [解决]
         ↓         ↓
       [温室气体] [新能源]

→ Video:
Scene 1 (0-5s): "什么是气候变化" (Central Concept)
Scene 2 (5-15s): "原因：温室气体排放" (Connection 1)
Scene 3 (15-25s): "影响：极端天气增加" (Connection 2)
Scene 4 (25-35s): "解决：转向新能源" (Connection 3)
```

**Relationship Visualization**:
- Use connecting lines in visual scenes
- Arrows: "causes", "leads to", "results in"
- Group related concepts visually

### Timelines (时间线)

**Structure**:
```
时间: ─────────────────────────────────────────→
事件:   ●─────────●─────────●─────────●────
         t1        t2        t3        t4
```

**Video Transformation**:

| Timeline Element | Video Equivalent | Scene Structure |
|----------------|-------------------|-----------------|
| Chronological Order | Narrative flow | Scenes 1-N: Follow timeline |
| Time Points | Story nodes | Each point = 1 scene |
| Milestones | Emotional beats/highlights | Emphasized with motion/effects |
| Events | Key moments | Detailed content per event |

**Example Transformation**:
```
Timeline:
2020: [公司成立]
2021: [获天使投资]
2022: [产品上线]
2023: [用户破百万]
2024: [IPO上市]

→ Video:
Scene 1 (0-5s): "2020年，梦想开始" (t1)
Scene 2 (5-15s): "2021年，获得天使投资" (t2)
Scene 3 (15-25s): "2022年，产品正式上线" (t3)
Scene 4 (25-35s): "2023年，用户突破百万" (t4)
Scene 5 (35-40s): "2024年，IPO上市！" (t5 - Milestone)
```

**Timeline Enhancement**:
- Show timeline visually (horizontal scroll, vertical progress)
- Use motion to emphasize progression
- Milestone events: Dramatic animations, music swell

### Org Charts (组织结构图)

**Structure**:
```
            [CEO/Top]
              /    |    \
        [VP-A]  [VP-B]  [VP-C]
          /  \     /  \     /  \
    [Dir][Dir][Dir][Dir][Dir][Dir]
```

**Video Transformation**:

| Org Chart Element | Video Equivalent | Scene Structure |
|-----------------|-------------------|-----------------|
| Top Level | Overview, big picture | Scene 1: High-level introduction |
| Middle Level | Breakdown into categories | Scenes 2-N: Each level = 1-2 scenes |
| Bottom Level | Details, specifics | Detailed scenes within categories |
| Hierarchy | Information importance | Larger/more prominent visuals for higher levels |

**Example Transformation**:
```
Org Chart:
         [公司架构]
          /   |   \
   [技术]  [市场]  [运营]
     /  \     /  \     /  \
  [前端][后端][销售][客服][人事][财务]

→ Video:
Scene 1 (0-5s): "公司三大支柱：技术、市场、运营" (Top Level)
Scene 2 (5-15s): "技术：前端和后端团队" (Tech Branch)
Scene 3 (15-25s): "市场：销售团队打天下" (Market Branch)
Scene 4 (25-35s): "运营：人事和财务支持" (Ops Branch)
```

**Hierarchy Visualization**:
- Top level: Larger visuals, more prominent positioning
- Bottom level: Smaller visuals, supporting details
- Transitions: Show decomposition (zoom in from big to small)

### Knowledge Graphs (知识图谱)

**Structure**:
```
        [节点A]
       /    |    \
  [节点B]─[节点C]─[节点D]
       \    |    /
        [节点E]
```

**Video Transformation**:

| Knowledge Graph Element | Video Equivalent | Scene Structure |
|---------------------|-------------------|-----------------|
| Nodes | Information points | Each cluster = 1-2 scenes |
| Edges | Connections/relationships | Transitions, visual lines |
| Network | Overall system | Multi-scene exploration of connections |

**Example Transformation**:
```
Knowledge Graph:
    [AI]
   /  |  \
[ML][DL][NLP]
   |    |    |
[RNN][CNN][GPT]

→ Video:
Scene 1 (0-10s): "AI的三大核心" (Nodes: ML, DL, NLP)
Scene 2 (10-20s): "ML中的RNN应用" (Edge: ML→RNN)
Scene 3 (20-30s): "DL中的CNN突破" (Edge: DL→CNN)
Scene 4 (30-40s): "NLP中的GPT革命" (Edge: NLP→GPT)
Scene 5 (40-50s): "整个网络的协同" (Network overview)
```

**Network Visualization**:
- Show connections with animated lines
- Nodes appear sequentially with connections
- Use different colors for related node clusters
- Zoom out to show overall network

### Visual Skills by Video Type

| Video Type | Best Visual Skill | Reason |
|-----------|-----------------|---------|
| **Tutorial** | Flowcharts, Mind Maps | Step-by-step logic |
| **Explainer** | Concept Maps, Knowledge Graphs | Complex relationships |
| **Story** | Timelines | Chronological narrative |
| **Promo** | Mind Maps | Fast, engaging structure |
| **Animated Infographic** | All skills | Data and process visualization |
| **Cinematic** | Timelines, Knowledge Graphs | Complex systems |
| **Slideshow** | Org Charts | Hierarchical presentation |

### Visual Skills Integration with Existing Systems

**Synergy**:

| Visual Skill | Complementary System | Integration |
|-------------|---------------------|-------------|
| Mind Maps | Remotion Components | Branches = Component hierarchy |
| Flowcharts | Canvas Design | Nodes follow grid positioning |
| Concept Maps | Type × Style | Concepts align with visual style |
| Timelines | Superpowers | Time Bender superpower |
| Org Charts | Frontend-Design | Hierarchy = Visual hierarchy |
| Knowledge Graphs | Algorithmic Art | Network = Algorithmic patterns |

### Visual Skills in Workflow

**Step 2: Context Gathering**:
- Ask user: "What visual structure best represents your content?"
- Options: "Mind map", "Flowchart", "Concept map", "Timeline", "Org chart", "Knowledge graph"

**Step 4: Storyboard Generation**:
- Apply chosen visual skill structure
- Transform visual skill → scene sequence
- Document transformations in storyboard

**Example Storyboard with Visual Skill**:
```
## Visual Skill: Mind Map

## Scene 1 (0-5s)
**Mind Map Node**: Central [主题]
**Content**: Introduce main topic
**Visual**: Central node at center, branches fade in

## Scene 2 (5-15s)
**Mind Map Node**: Branch 1 [分支1]
**Content**: Explore first main branch
**Visual**: One branch expands with sub-branches
```

### Benefits of Visual Skills

- **Clarity**: Visual structure makes content easy to understand
- **Organization**: Systematic approach prevents confusion
- **Flexibility**: Different skills for different content types
- **Scalability**: Visual skills scale from simple to complex
- **Engagement**: Visual transitions maintain interest

**Key Principle**: Choose visual skill based on content structure. Transform systematically: nodes → scenes, edges → transitions, hierarchy → narrative flow.

## Design Thinking (from frontend-design)

Before generating any video, apply frontend-design principles to create distinctive, production-grade aesthetics:

**Core Questions**:
- **Purpose**: What problem does this video solve? Who uses it?
- **Tone**: Pick an extreme aesthetic direction (brutally minimal, maximalist chaos, retro-futuristic, organic/natural, luxury/refined, playful/toy-like, editorial/magazine, brutalist/raw, art deco/geometric, soft/pastel, industrial/utilitarian)
- **Constraints**: Technical requirements (platform, duration, aspect ratio)
- **Differentiation**: What makes this video UNFORGETTABLE? What's the one thing viewers will remember?

**CRITICAL**: Choose a clear conceptual direction and execute it with precision. Bold maximalism and refined minimalism both work - the key is intentionality, not intensity.

## Frontend Aesthetics Guidelines (from frontend-design)

When constructing video prompts and visual descriptions:

**Typography**:
- Choose distinctive, characterful fonts over generic ones (avoid Inter, Roboto, Arial unless specific requirements)
- Pair a unique display font with a refined body font
- Ensure readability: strong contrast, appropriate sizing, clean alignment

**Color & Theme**:
- Commit to a cohesive aesthetic with dominant colors and sharp accents
- Use CSS-variable-like consistency across all scenes
- Avoid timid, evenly-distributed palettes
- Be adventurous: try unexpected combinations that genuinely match the topic

**Motion & Animation**:
- Use animations for impact: orchestrated page loads with staggered reveals create more delight than scattered micro-interactions
- Prioritize smooth, fluid transitions for educational content
- Use dynamic motion for promotional content
- Focus on high-impact moments rather than continuous movement

**Spatial Composition**:
- Unexpected layouts over symmetric, centered defaults
- Asymmetry, overlap, diagonal flow, grid-breaking elements
- Generous negative space OR controlled density (intentional choice, not accidental)

**Backgrounds & Visual Details**:
- Create atmosphere and depth rather than solid color defaults
- Add contextual effects: gradient meshes, noise textures, geometric patterns, layered transparencies, dramatic shadows, decorative borders
- Match overall aesthetic (don't mix random elements)

**NEVER Use Generic AI Aesthetics** (from frontend-design):
- Overused font families (Space Grotesk, Inter, Roboto, Arial, system fonts)
- Cliched color schemes (especially purple gradients on white backgrounds)
- Predictable layouts and component patterns
- Cookie-cutter design that lacks context-specific character

**Key Principle**: Interpret creatively and make unexpected choices that feel genuinely designed for the context. No two videos should look the same. Vary between light and dark themes, different fonts, different aesthetics.

Remember: Claude is capable of extraordinary creative work. Don't hold back - show what can truly be created when thinking outside the box and committing fully to a distinctive vision.

## Two Dimensions

| Dimension | Controls | Examples |
|-----------|----------|----------|
| **Type** | Video structure, narrative approach | explainer, story, tutorial, promo, cinematic, slideshow, animated-infographic |
| **Style** | Visual aesthetics, mood | craft-handmade, chalkboard, minimal, bold-editorial, cute, warm, technical-schematic |

Type × Style can be freely combined. Example: `--type explainer --style chalkboard`

## Usage

```bash
# Auto-select type and style based on content
/video-generator path/to/content.md

# Specify type and style
/video-generator path/to/content.md --type explainer --style chalkboard

# Use preset
/video-generator path/to/content.md --preset ohmsha-style

# Specify video-specific dimensions
/video-generator path/to/content.md --duration medium --motion smooth --audio voiceover

# Direct content input
/video-generator
[paste content]

# Quick mode: skip confirmation, use auto-selection
/video-generator content.md --quick
```

## Options

| Option | Description |
|--------|-------------|
| `--type <name>` | Video type (see Video Type Gallery) |
| `--style <name>` | Visual style (see Visual Style Gallery) |
| `--preset <name>` | Preset shortcut (see Preset Gallery) |
| `--duration <level>` | Video duration: short (15-30s), medium (30-60s), long (60-120s) |
| `--motion <level>` | Motion intensity: static, smooth, dynamic, cinematic |
| `--audio <level>` | Audio: none, music-only, voiceover, music+voiceover |
| `--transition <type>` | Transition style: cut, fade, slide, wipe, creative |
| `--text <level>` | Subtitle style: none, minimal, full, kinetic |
| `--aspect <ratio>` | Aspect ratio: 16:9 (default), 9:16, 1:1, 4:3 |
| `--lang <code>` | Output language (en, zh, ja, etc.) |
| `--quick` | Skip confirmation, use auto-selection for missing options |
| `--superpower <name>` | Apply specific superpower (see Superpowers section) |
| `--superpowers <list>` | Apply multiple superpowers (comma-separated) |
| `--ffmpeg-quality <preset>` | FFmpeg quality preset (web-optimized, high-quality, ultra-quality, social-media, tiny, max-compression) |
| `--ffmpeg-effect <preset>` | FFmpeg effect preset (cinematic, dreamy, vintage, dramatic, clean, slow-motion) |
| `--ffmpeg-hw-accel` | Hardware acceleration (nvenc, qsv, vaapi) |
| `--skip-ffmpeg` | Skip FFmpeg post-processing |

## Partial Workflow Options

| Option | Description |
|--------|-------------|
| `--storyboard-only` | Generate storyboard only, skip prompts and videos |
| `--prompts-only` | Generate storyboard + prompts, skip video generation |
| `--videos-only` | Generate videos from existing prompts directory |
| `--regenerate N` | Regenerate specific scene(s) only (e.g., `3` or `2,5,8`) |

## Video Type Gallery

| Type | Description | Best For |
|------|-------------|----------|
| `explainer` | Concept explanation, simplified breakdowns | Tutorials, product demos, educational content |
| `story` | Narrative-driven, emotional arcs | Personal stories, brand narratives, testimonials |
| `tutorial` | Step-by-step instruction, clear progression | How-to guides, training videos |
| `promo` | High-energy, persuasive | Product launches, marketing campaigns |
| `cinematic` | Artistic, visually stunning | Brand films, artistic expression |
| `slideshow` | Image-based, smooth transitions | Photo stories, portfolio showcases |
| `animated-infographic` | Data-driven, animated charts | Data visualization, statistics |
| `pptx-to-video` | PowerPoint presentation to video conversion | Converting .pptx files to video format |

Full definitions: [references/video-types.md](references/video-types.md)

## Visual Style Gallery

| Style | Description | Best For |
|-------|-------------|----------|
| `craft-handmade` | Hand-drawn, paper craft texture (Default) | Educational content, tutorials |
| `chalkboard` | Chalk on blackboard, educational | Classroom, teaching, tutorials |
| `minimal` | Clean, whitespace-heavy | Product demos, executive briefings |
| `bold-editorial` | High contrast, magazine-style | Marketing, announcements |
| `cute` | Sweet, adorable, playful | Lifestyle, entertainment, youth content |
| `warm` | Cozy, friendly, approachable | Personal stories, testimonials |
| `technical-schematic` | Blueprint, engineering style | Tech tutorials, architecture |
| `pixel-art` | Retro 8-bit aesthetic | Gaming, retro content |
| `cyberpunk-neon` | Neon glow, futuristic | Tech, innovation, startups |
| `watercolor` | Soft painted, artistic | Lifestyle, travel, creative |
| `vintage` | Aged, nostalgic, period authenticity | Historical content, documentaries |
| `flat-vector` | Modern vector illustration | Corporate, professional |
| `algorithmic` | Generative, code-based aesthetics | Artistic expression, tech showcases |

Full definitions: [references/visual-styles.md](references/visual-styles.md)

## Preset Gallery

| Preset | Equivalent | Special Rules |
|--------|-----------|---------------|
| `ohmsha-style` | `--type explainer --style chalkboard --audio voiceover --transition slide` | Educational metaphors, step-by-step breakdown |
| `product-demo` | `--type explainer --style minimal --duration medium --audio voiceover` | Product showcase, clear features |
| `story-time` | `--type story --style warm --duration long --audio music+voiceover` | Emotional narrative, personal connection |
| `tech-tutorial` | `--type tutorial --style technical-schematic --audio voiceover` | Technical clarity, diagrams |
| `instagram-reel` | `--type explainer --style bold-editorial --duration short --aspect 9:16` | Vertical format, high impact |
| `tiktok-vibe` | `--type explainer --style cute --duration short --motion dynamic` | Playful, engaging, trending |
| `product-launch` | `--type promo --style bold-editorial --duration medium --audio music+voiceover` | High energy, persuasive |

Full preset definitions: [references/presets.md](references/presets.md)

## Video-Specific Dimensions

### Duration
| Level | Duration | Use Case |
|-------|----------|----------|
| `short` | 15-30 seconds | Social media, teasers |
| `medium` | 30-60 seconds (Default) | Standard explainer, tutorials |
| `long` | 60-120 seconds | In-depth tutorials, stories |

### Motion
| Level | Description | Use Case |
|-------|-------------|----------|
| `static` | Minimal movement, slideshow-style | Photo stories, serious content |
| `smooth` | Gentle, fluid motion (Default) | Tutorials, explanations |
| `dynamic` | Active, energetic movement | Promo, entertainment |
| `cinematic` | Film-quality, professional camera work | Brand films, art |

### Audio
| Level | Description | Use Case |
|-------|-------------|----------|
| `none` | No audio | Visual-only content |
| `music-only` | Background music only | Ambiance, mood setting |
| `voiceover` | Voice narration | Tutorials, explanations (Default) |
| `music+voiceover` | Voice + background music | Promo, stories |

### Transition
| Style | Description |
|-------|-------------|
| `cut` | Instant cuts, energetic |
| `fade` | Smooth fades, gentle (Default) |
| `slide` | Slide transitions, tutorial-friendly |
| `wipe` | Wipe effects, dynamic |
| `creative` | Unique transitions, artistic |

### Text (Subtitles)
| Level | Description | Use Case |
|-------|-------------|----------|
| `none` | No subtitles | Visual storytelling |
| `minimal` | Key phrases only | Clean, modern look (Default) |
| `full` | Complete transcription | Accessibility, educational |
| `kinetic` | Animated, engaging subtitles | Social media, entertainment |

## Auto Selection

Content signals determine default type + style + video dimensions:

| Content Signals | Type | Style | Duration | Audio |
|-----------------|------|-------|----------|-------|
| Tutorial, how-to, steps, learn | **tutorial** | technical-schematic / chalkboard | medium | voiceover |
| Product, launch, announce, promo | **promo** | bold-editorial | medium | music+voiceover |
| Story, personal, journey, emotion | **story** | warm / watercolor | long | music+voiceover |
| Concept, explain, what is | **explainer** | craft-handmade / minimal | medium | voiceover |
| Data, statistics, visualize | **animated-infographic** | technical-schematic | medium | voiceover |
| Social media, short, quick | **explainer** | bold-editorial / cute | short | voiceover |
| Gaming, retro, pixel | **explainer** | pixel-art | short | voiceover |
| PowerPoint, presentation, slides | **pptx-to-video** | minimal / clean | medium | voiceover or none |
| Pattern, system, reveal hidden | **explainer** | algorithmic / minimal | medium | voiceover |
| Transform, inspire, motivate | **story** | warm / bold-editorial | long | music+voiceover |
| Complex to simple, metaphor | **explainer** | chalkboard / craft-handmade | medium | voiceover |

**Superpower Auto-Selection**:

| Content Signals | Recommended Superpowers |
|-----------------|-------------------------|
| Tutorial, how-to, steps, learn | Pattern Hunter, Simplifier, Sensemaker |
| Product, launch, announce, promo | Amplifier, Perspective Shifter, Pattern Breaker |
| Story, personal, journey, emotion | Storyteller, Empathy Engine, Time Bender |
| Concept, explain, what is | Simplifier, Bridge Builder, Perspective Shifter |
| Data, statistics, visualize | Pattern Hunter, Sensemaker, Amplifier |
| Transform, growth, achievement | Storyteller, Amplifier, Time Bender |
| Hidden patterns, connections | Pattern Hunter, Bridge Builder, Sensemaker |
| Disruptive, innovative, paradigm shift | Pattern Breaker, Perspective Shifter, Amplifier |

Details: [references/auto-selection.md](references/auto-selection.md)

## Script Directory

**Important**: All scripts are located in the `scripts/` subdirectory of this skill.

**Agent Execution Instructions**:
1. Determine this SKILL.md file's directory path as `SKILL_DIR`
2. Script path = `${SKILL_DIR}/scripts/<script-name>.py`
3. Replace all `${SKILL_DIR}` in this document with the actual path

## Script Reference

| Script | Purpose | Usage |
|--------|---------|-------|
| `scripts/generate-video.py` | Generate video from prompts using video generation API | `generate-video.py --prompt "..." --output video.mp4` |
| `scripts/merge-images-to-video.py` | Merge image sequence into video with transitions | `merge-images-to-video.py --input images/ --output video.mp4 --transition fade` |
| `scripts/add-subtitles.py` | Add subtitles to video | `add-subtitles.py --input video.mp4 --subtitles subs.txt --output output.mp4` |
| `scripts/add-audio.py` | Add audio to video | `add-audio.py --input video.mp4 --audio audio.mp3 --output output.mp4` |
| `scripts/vibevoice-asr-transcribe.py` | VibeVoice-ASR audio transcription (60-minute, speaker ID, timestamps) | `vibevoice-asr-transcribe.py --input audio.mp3 --output transcription.json` |
| `scripts/ffmpeg-processor.py` | Advanced FFmpeg processing (quality, effects, filters) | `ffmpeg-processor.py input.mp4 output.mp4 --quality high-quality --effect cinematic` |

## Workflow

Copy this checklist and track progress:

```
Progress:
- [ ] Step 1: Pre-check
- [ ] Step 2: Setup & Analyze (Stage 1: Context Gathering)
- [ ] Step 3: Confirm Settings ⚠️ REQUIRED
- [ ] Step 4: Generate Storyboard (Stage 2: Refinement & Structure)
- [ ] Step 5: Generate Prompts
- [ ] Step 6: Generate Videos
- [ ] Step 7: Post-Processing
- [ ] Step 8: Finalize
- [ ] Step 9: Reader Testing (Stage 3) ⚠️ RECOMMENDED
```
- [ ] Step 6: Generate Videos
- [ ] Step 7: Post-Processing
- [ ] Step 8: Finalize
- [ ] Step 9: Reader Testing (Stage 3) ⚠️ RECOMMENDED
```

---

### Step 1: Pre-check

**1.1 Determine Input Type**

| Input | Output Directory | Next |
|-------|------------------|------|
| File path | Ask user (1.2) | → 1.2 |
| Pasted content | `videos/{topic-slug}/` | → 1.4 |

**1.2 Determine Output Directory** (file path input only)

Check `default_output_dir` in preferences (if EXTEND.md exists):

| Preference Value | Action |
|------------------|--------|
| `same-dir` | Use `{content-dir}/` |
| `videos-subdir` | Use `{content-dir}/videos/` |
| `independent` | Use `videos/{topic-slug}/` |
| Not configured | **MUST** ask with AskUserQuestion ↓ |

**AskUserQuestion** (when no preference):
- `{content-dir}/` - Same directory as content
- `{content-dir}/videos/` - Videos subdirectory
- `videos/{topic-slug}/` - Independent directory
- Save as default - Remember this choice

**1.3 Check Existing Videos**

Scan target directory for `.mp4/.mov/.webm` files.

If videos exist → AskUserQuestion: How to handle?
- `supplement` - Keep existing, generate only new scenes
- `overwrite` - Overwrite same-name files
- `regenerate` - Clear all and regenerate

**1.4 Load Preferences (EXTEND.md)**

Check for custom configurations:
```bash
test -f .baoyu-skills/video-generator/EXTEND.md && echo "project"
test -f "$HOME/.baoyu-skills/video-generator/EXTEND.md" && echo "user"
```

| Result | Action |
|--------|--------|
| Found | Read, parse, display summary |
| Not found | Continue with defaults |

**Supports**: Preferred type/style | Custom presets | Language | Video API credentials | Output directory

---

### Step 2: Setup & Analyze (Stage 1: Context Gathering)

**2.1 Initial Context Questions** (Adapted from doc-coauthoring)

Start by asking user for meta-context about the video:

1. What type of video is this? (explainer, story, tutorial, promo, cinematic, slideshow, animated-infographic)
2. Who's the primary audience? (beginners, experts, general, specific demographic)
3. What's the desired impact when viewers watch this? (educate, entertain, persuade, inspire)
4. Is there a specific format or style to follow? (brand guidelines, platform requirements)
5. Any other constraints or context to know?

**Inform user**: They can answer in shorthand or dump information however works best for them.

**2.2 Info Dumping** (Adapted from doc-coauthoring)

Encourage user to dump all context they have:
- Background on project/product/topic
- Related materials, links, or documents
- Why alternative approaches aren't being used
- Brand or organizational context
- Timeline constraints or length requirements
- Technical constraints or platform requirements

**Inform user**: Don't worry about organizing it - just get it all out. Offer multiple ways:
- Info dump stream-of-consciousness
- Share links to documents or resources
- Point to brand assets or style guides

**2.3 Analyze Content**

| Analysis | Description |
|----------|-------------|
| Content type | Tutorial / Story / Promo / Explainer / Data |
| Core message | Main point to convey |
| Target audience | Beginners / Experts / General / Specific |
| Visual opportunities | Scenes that benefit from video |
| Recommended type | Based on content signals |
| Recommended duration | Based on complexity and goal |

**2.4 Extract Key Points**

- Main thesis or product
- 3-5 key concepts to cover
- Narrative arc (for story type)
- Steps to demonstrate (for tutorial type)

**CRITICAL**: If content uses metaphors, do NOT visualize literally. Create **visual representations of the underlying concept**.

**2.5 Identify Video Structure**

For each scene:
- Scene purpose (hook, explanation, demo, conclusion)
- Key visual elements
- Text overlay (subtitle)
- Transition to next scene

**2.6 Superpower Selection** (from obra/superpowers)

After understanding content structure, identify which superpowers will amplify the core message:

**Question**: What should this video make the viewer feel, think, or do?

**Match superpowers to goals**:
- Reveal hidden patterns → **Pattern Hunter**
- Connect unexpected domains → **Bridge Builder**
- Create emotional connection → **Storyteller** or **Empathy Engine**
- Simplify complexity → **Simplifier**
- Maximize impact of key insights → **Amplifier**
- Shift perspective → **Perspective Shifter**
- Surprise and disrupt → **Pattern Breaker**
- Manipulate time perception → **Time Bender**
- Make sense of chaos → **Sensemaker**

**Select 1-3 superpowers** that best amplify the core message.

**Document the choice** in the storyboard with:
- Which superpower(s) applied
- Where in the video they appear
- How they're visually expressed

**2.7 Asking Clarifying Questions** (Adapted from doc-coauthoring)

After substantial context provided, ask clarifying questions:

Generate 5-10 numbered questions based on gaps in context. Include at least 1-2 questions about superpower preferences:
- "Should this video emphasize revealing hidden patterns or connecting unexpected concepts?"
- "Do you want maximum emotional impact or intellectual surprise?"
- "Should the content feel like a story or a clear explanation?"

**Inform user**: They can use shorthand to answer (e.g., "1: yes, 2: see #link, 3: pattern-hunter").

**Exit condition**: Sufficient context when questions show understanding and edge cases can be discussed.

---

### Step 3: Confirm Settings ⚠️

**Do NOT skip.** Use AskUserQuestion with 4-5 questions in ONE call.

**Q1: Video Type**
- [Recommended based on analysis] (Recommended)
- explainer / story / tutorial / promo / cinematic / slideshow / animated-infographic

**Q2: Visual Style**
- [Best compatible from auto-selection] (Recommended)
- [Other ✓✓ style 1]
- [Other ✓✓ style 2]
- [Other ✓ style]

Style selection based on Type × Style compatibility matrix (see auto-selection rules).

**Q3: Superpowers** (NEW)
- [Recommended based on content and goal] (Recommended)
- [Alternative superpower 1]
- [Alternative superpower 2]
- [Combination: Superpower 1 + Superpower 2]

Superpower selection based on content analysis and desired impact (see Superpowers section).

**Q4: Duration**
- short (15-30s) - Social media, teasers
- medium (30-60s) (Recommended) - Standard explainer
- long (60-120s) - In-depth content

**Q5: Audio**
- voiceover (Default) - Narration only
- music+voiceover - Narration + background music
- music-only - Background music only
- none - No audio

---

### Step 4: Generate Storyboard (Stage 2: Refinement & Structure)

**4.1 Section-by-Section Approach** (Adapted from doc-coauthoring)

Explain that storyboard will be built section by section. For each section:
1. Clarifying questions about what to include
2. 5-20 scene options brainstormed
3. User indicates what to keep/remove/combine
4. Scenes are drafted
5. Refined through surgical edits

**4.2 Scene Ordering** (Adapted from doc-coauthoring)

Start with whichever section has most unknowns (usually hook or core concept), then work through rest.

If structure is clear: Ask which section to start with.

**Suggest**: Start with scene that has most unknowns (hook/explanation), leave summary/CTA for last.

**4.3 Generate Initial Storyboard Structure**

Once structure is agreed, create initial storyboard with placeholders for all scenes.

**If access to artifacts is available**:
Use `create_file` to create storyboard.md artifact. This gives both Claude and user a scaffold to work from.

**4.4 Save as `storyboard.md`:

```yaml
---
type: explainer
style: chalkboard
duration: medium
audio: voiceover
superpowers: Pattern Hunter, Amplifier
scene_count: 5
---

## Scene 1 (0-5s)

**Purpose**: Hook, grab attention
**Superpower**: Amplifier (maximize impact)
**Duration**: 5 seconds
**Animation**: Title slides in from left (0.5s spring), subtitle fades in (0.3s ease-in, 0.2s delay)
**Visual Content**: [describe visual elements]
**Text Overlay**: [subtitle text]
**Transition**: fade

## Scene 2 (5-15s)

**Purpose**: Explain core concept
**Superpower**: Pattern Hunter (reveal hidden pattern)
**Duration**: 10 seconds
**Animation**: Elements appear sequentially (0.3s staggered delay, ease-out)
**Visual Content**: [describe visual elements]
**Text Overlay**: [subtitle text]
**Transition**: slide

## Scene 3 (15-23s)

**Purpose**: [scene purpose]
**Superpower**: [applicable superpower or none]
**Duration**: [seconds]
**Start Time**: [exact timestamp]
**Animation**: [precise animation description with timing]
**Visual Content**: [describe visual elements]
**Text Overlay**: [subtitle text]
**Transition**: [transition type]

...
```

**Remotion-Inspired Timing**:
- **Precise timestamps**: Mark exact start/end for each scene (e.g., 5-15s)
- **Animation timing**: Specify duration and motion type (e.g., "0.5s spring", "2s ease-out")
- **Sequential/Parallel**: Mark if animations happen together or staggered
- **Component reuse**: Reference component templates for consistency

**Requirements**:
- Each scene justified by narrative needs
- Type applied consistently
- Style reflected in visual descriptions
- Superpowers integrated where appropriate (not forced)
- Total duration matches selected level
- Scene transitions flow smoothly
- Visual designs embody chosen superpowers

**4.5 Superpower Integration** (NEW)

For each scene where a superpower is applied, specify:

**Visual Design**:
- How does the superpower manifest visually?
- What motion patterns reinforce the superpower?
- How does color support the superpower's emotional intent?

**Examples**:

**Pattern Hunter Scene**:
- Visual: Scattered data points → animated lines connect revealing pattern
- Motion: Smooth emergence, gradual revelation
- Color: Start muted, intensify as pattern emerges

**Amplifier Scene**:
- Visual: Key insight appears with dramatic zoom, kinetic typography explodes
- Motion: Punchy, high-impact, synchronized with audio
- Color: High-contrast, accent colors pop

**Bridge Builder Scene**:
- Visual: Split-screen with concept A → morph into concept B
- Motion: Fluid transition between domains
- Color: Gradient shift as domains merge

---

### Step 5: Generate Prompts

**5.1 Create Scene Prompts**

Follow [references/prompt-construction.md](references/prompt-construction.md). Save to `prompts/scene-{N}.md`.

**5.2 Select Video Generation API**

Check available APIs in EXTEND.md or ask user:
- Runway ML Gen-2
- Pika Labs
- Stable Video Diffusion
- Other

**5.3 Generate Prompts**

For each scene:
1. Create detailed prompt (visual description + style + motion)
2. Save as `prompts/scene-{N}.md`
3. Track progress

---

### Step 6: Generate Videos

**6.1 Generate Individual Scenes**

Use `scripts/generate-video.py`:

```bash
${SKILL_DIR}/scripts/generate-video.py \
  --prompt "$(cat prompts/scene-1.md)" \
  --output videos/{topic-slug}/scene-01.mp4 \
  --duration 5 \
  --aspect 16:9
```

**6.2 Progress Tracking**

After each scene: "Generated scene X/N (scene-XX.mp4)"

On failure: retry once, then log and continue

---

### Step 7: Post-Processing

**7.0 Audio Transcription** (OPTIONAL - from VibeVoice-ASR)

Use VibeVoice-ASR to transcribe video audio for subtitle generation:

**When to Use Audio Transcription**:
- Generate subtitles from voiceover audio
- Extract dialogue scripts from recorded audio
- Create speaker-synced subtitles for multi-speaker content
- Process long audio (up to 60 minutes) in single pass

**Transcribe Audio**:

Use `scripts/vibevoice-asr-transcribe.py`:

```bash
# Basic transcription
${SKILL_DIR}/scripts/vibevoice-asr-transcribe.py \
  --input videos/{topic-slug}/audio/voiceover.mp3 \
  --output videos/{topic-slug}/transcription.json

# With custom hotwords for domain-specific accuracy
${SKILL_DIR}/scripts/vibevoice-asr-transcribe.py \
  --input videos/{topic-slug}/audio/podcast.mp3 \
  --hotwords "technical terms" "product names" \
  --output videos/{topic-slug}/transcription.json

# Specify language
${SKILL_DIR}/scripts/vibevoice-asr-transcribe.py \
  --input videos/{topic-slug}/audio/voiceover.mp3 \
  --language zh \
  --output videos/{topic-slug}/transcription.json
```

**VibeVoice-ASR Features**:
- **60-minute single-pass processing**: Process entire long audio without fragmentation
- **Speaker identification**: Identify different speakers in dialogue
- **Timestamp synchronization**: Precise timing for subtitle sync
- **Custom hotwords**: Improve accuracy for domain-specific terms
- **50+ languages**: Support for multilingual content

**Output Format** (JSON):
```json
{
  "audio_path": "videos/{topic-slug}/audio/voiceover.mp3",
  "model": "microsoft/VibeVoice-ASR",
  "language": "zh",
  "hotwords_used": ["term1", "term2"],
  "transcription": "Full text transcription...",
  "structured": {
    "segments": [
      {
        "speaker": "Speaker 1",
        "start": 0.0,
        "end": 5.2,
        "text": "Welcome to our channel"
      }
    ]
  }
}
```

**Generate Subtitles from Transcription**:

After transcribing audio, convert structured output to subtitle formats (SRT/VTT):

- Use timestamps for subtitle timing
- Use speaker information for character identification
- Sync subtitles with video scenes

See [references/vibevoice-asr-guide.md](references/vibevoice-asr-guide.md) for complete VibeVoice-ASR documentation.

**7.1 Merge Scenes** (if multiple scenes)

Use `scripts/merge-images-to-video.py` for image sequences, or video editing for scene stitching.

**7.2 Add Audio** (if voiceover or music selected)

Use `scripts/add-audio.py`:

```bash
${SKILL_DIR}/scripts/add-audio.py \
  --input videos/{topic-slug}/final.mp4 \
  --audio voiceover.mp3 \
  --output videos/{topic-slug}/final-with-audio.mp4
```

**7.3 Add Subtitles** (if not none)

Use `scripts/add-subtitles.py`:

```bash
${SKILL_DIR}/scripts/add-subtitles.py \
  --input videos/{topic-slug}/final.mp4 \
  --subtitles subtitles.txt \
  --output videos/{topic-slug}/final-subtitled.mp4
```

**7.4 FFmpeg Advanced Processing** (OPTIONAL - from FFmpeg)

Apply professional-quality video processing using FFmpeg:

**When to Apply FFmpeg**:
- Need professional-quality encoding for specific platforms
- Applying visual effects (cinematic, vintage, dramatic, etc.)
- Optimizing file size while maintaining quality
- Adding watermarks or overlays
- Creating slow motion or speed effects
- Color correction and grading

**Quality Optimization**:

Use `scripts/ffmpeg-processor.py` with quality presets:

```bash
# Web-optimized for streaming
${SKILL_DIR}/scripts/ffmpeg-processor.py \
  input.mp4 output.mp4 \
  --quality web-optimized

# High-quality for archival
${SKILL_DIR}/scripts/ffmpeg-processor.py \
  input.mp4 output.mp4 \
  --quality high-quality

# Social media optimization
${SKILL_DIR}/scripts/ffmpeg-processor.py \
  input.mp4 output.mp4 \
  --quality social-media
```

**Visual Effects**:

Apply effect presets for visual enhancement:

```bash
# Cinematic look
${SKILL_DIR}/scripts/ffmpeg-processor.py \
  input.mp4 output.mp4 \
  --effect cinematic

# Dreamy, ethereal effect
${SKILL_DIR}/scripts/ffmpeg-processor.py \
  input.mp4 output.mp4 \
  --effect dreamy

# Vintage, nostalgic look
${SKILL_DIR}/scripts/ffmpeg-processor.py \
  input.mp4 output.mp4 \
  --effect vintage

# Dramatic, high-contrast
${SKILL_DIR}/scripts/ffmpeg-processor.py \
  input.mp4 output.mp4 \
  --effect dramatic
```

**Speed Manipulation**:

```bash
# Slow motion (0.5x speed)
${SKILL_DIR}/scripts/ffmpeg-processor.py \
  input.mp4 slow-motion.mp4 \
  --speed 0.5

# Fast forward (2.0x speed)
${SKILL_DIR}/scripts/ffmpeg-processor.py \
  input.mp4 fast.mp4 \
  --speed 2.0
```

**Combined Processing**:

Apply quality and effects together:

```bash
# High-quality cinematic effect with two-pass encoding
${SKILL_DIR}/scripts/ffmpeg-processor.py \
  input.mp4 final.mp4 \
  --quality high-quality \
  --effect cinematic \
  --two-pass

# Social media with dreamy effect
${SKILL_DIR}/scripts/ffmpeg-processor.py \
  input.mp4 social.mp4 \
  --quality social-media \
  --effect dreamy
```

**Batch Processing**:

Process multiple videos at once:

```bash
# Batch process all scene videos
${SKILL_DIR}/scripts/ffmpeg-processor.py \
  "scene-*.mp4" "processed_" \
  --batch \
  --quality high-quality \
  --effect cinematic
```

**Hardware Acceleration**:

Use GPU acceleration for faster processing:

```bash
# NVIDIA NVENC
${SKILL_DIR}/scripts/ffmpeg-processor.py \
  input.mp4 output.mp4 \
  --quality high-quality \
  --hw-accel nvenc

# Intel Quick Sync Video
${SKILL_DIR}/scripts/ffmpeg-processor.py \
  input.mp4 output.mp4 \
  --quality high-quality \
  --hw-accel qsv
```

**Skip FFmpeg**:

If the video already meets quality requirements, skip FFmpeg processing:

```bash
# Skip FFmpeg (quality is sufficient)
--skip-ffmpeg flag
```

**Note**: FFmpeg processing is optional and depends on quality requirements and platform specifications. Videos can be finalized without FFmpeg enhancement.

---

### Step 8: Finalize

**8.1 Output Summary**

```
Video Generation Complete!

Content: [path]
Type: [type] | Style: [style] | Duration: [level]
Location: [directory]
Scenes: X/N generated | Total duration: XX seconds

Scenes:
- scene-01.mp4 (5s) → Hook
- scene-02.mp4 (10s) → Concept explanation
- scene-03.mp4 (8s) → Demo
- ...

[If failures]
Failed:
- scene-XX.mp4: [reason]
```

**8.2 File Structure**

```
videos/{topic-slug}/
├── source-{slug}.{ext}
├── storyboard.md
├── prompts/
│   ├── scene-1.md
│   ├── scene-2.md
│   └── ...
├── scene-01.mp4
├── scene-02.mp4
├── ...
└── final.mp4
```

**Slug**: 2-4 word topic in kebab-case.
**Conflict**: Append `-YYYYMMDD-HHMMSS` if exists.

---

### Step 9: Reader Testing (Stage 3) ⚠️

**9.1 Why Reader Testing?** (Adapted from doc-coauthoring)

Test the storyboard and final video to ensure it works well for viewers who don't have the context you have. This catches:
- Ambiguous or unclear scenes
- Missing context or knowledge assumptions
- Blind spots that are obvious to you but not to others

**9.2 Step 1: Storyboard Testing**

Provide testing instructions:

**Option A: Self-Review**
1. Read through storyboard.md as if you're seeing it for the first time
2. For each scene, ask:
   - What's happening in this scene?
   - What's the purpose?
   - What visual elements are shown?
3. Identify any scenes that are unclear or confusing

**Option B: Fresh Claude Testing** (Recommended)
1. Open a fresh Claude conversation: https://claude.ai
2. Paste or share storyboard.md content
3. Ask Reader Claude generated questions

For each question, instruct Reader Claude to provide:
- The answer (what's happening in the scene)
- Whether anything was ambiguous or unclear
- What knowledge the storyboard assumes viewers already have

**Check**: Does Reader Claude give correct answers or misinterpret anything?

**9.3 Step 2: Additional Checks**

Also ask Reader Claude:
- "What in this storyboard might be ambiguous or unclear to viewers?"
- "What knowledge or context does this storyboard assume viewers already have?"
- "Are there any logical gaps or inconsistencies?"

**9.4 Step 3: Video Testing** (After video generation)

After final video is created:

**Option A: Self-Review**
1. Watch the final video
2. Check:
   - Do scenes flow smoothly?
   - Are subtitles clear and readable?
   - Is the pacing appropriate?
   - Does the audio match the visuals?
3. Identify any issues

**Option B: Fresh Claude Testing**
Share the video (or detailed description if video can't be uploaded) with a fresh Claude and ask:
- "What's the main message of this video?"
- "What are the key points covered?"
- "Is anything confusing or unclear?"

**9.5 Step 4: Iterate Based on Results**

Ask what testing revealed:
- What did Reader Claude get wrong or struggle with?
- What scenes were confusing or unclear?
- What context was missing?

**Loop back** to Step 4 (Generate Storyboard) to refine problematic scenes, then regenerate affected prompts and videos.

**9.6 Exit Condition**

When Reader Claude consistently answers questions correctly and doesn't surface new gaps or ambiguities, the storyboard and video are ready.

---

## Output Directory

```
videos/{topic-slug}/
├── source-{slug}.{ext}
├── storyboard.md
├── prompts/
│   └── scene-{N}.md
├── scene-{N}.mp4
├── audio/
│   ├── voiceover.mp3
│   └── background-music.mp3
├── subtitles.txt
└── final.mp4
```

## Modification

| Action | Steps |
|--------|-------|
| **Edit** | Update prompt → Regenerate scene → Merge final |
| **Add** | Identify position → Create prompt → Generate → Update storyboard → Merge |
| **Delete** | Delete files → Remove from storyboard → Merge final |

## References

| File | Content |
|------|---------|
| [references/video-types.md](references/video-types.md) | Video type specifications |
| [references/visual-styles.md](references/visual-styles.md) | Visual style gallery & compatibility |
| [references/prompt-construction.md](references/prompt-construction.md) | Prompt templates |
| [references/auto-selection.md](references/auto-selection.md) | Auto-selection rules |
| [references/presets.md](references/presets.md) | Preset definitions |
| [references/api-setup.md](references/api-setup.md) | Video generation API setup guide |
| [references/xiaohongshu-design.md](references/xiaohongshu-design.md) | Xiaohongshu design specifications |
| [references/vibevoice-asr-guide.md](references/vibevoice-asr-guide.md) | VibeVoice-ASR audio transcription guide |
| [references/xiaohongshu-design.md](references/xiaohongshu-design.md) | Xiaohongshu design specifications |

## Extension Support

Custom configurations via EXTEND.md. Supports:
- Preferred type/style
- Custom presets
- Video API credentials (Runway, Pika, etc.)
- Default video dimensions
- Language preferences

See EXTEND.md schema for details.

## Notes

- Video generation requires third-party API (Runway/Pika/etc.). Set up credentials in EXTEND.md or provide when prompted.
- Video generation may take time per scene. Be patient and track progress.
- Consider content length: break long content into multiple videos if duration > 120s.
- Test on sample content first for complex or custom styles.
## 资源索引

### 零配置方案（无需 API）
- **快速开始**：[references/zero-api-quick-start.md](references/zero-api-quick-start.md) - 5分钟快速上手，完全免费的视频生成方案
  - 方案 A：快速方案（Edge-TTS + Stable Diffusion WebUI）- 免费快速，无需配置
  - 方案 B：高质量方案（Ollama + ChatTTS + Stable Diffusion + SVD）- 完全本地，高质量
  
- **完整文档**：[references/local-no-api-solution.md](references/local-no-api-solution.md) - 完全本地化视频生成解决方案
  - Stable Diffusion 本地部署（无需 API）
  - Stable Video Diffusion 本地运行
  - ChatTTS / Edge-TTS 音频合成
  - Ollama + 本地 LLM 脚本写作
  - 完整工作流示例
  - 性能优化指南

### 完整工作流（推荐）
- `scripts/video-generation-workflow.py` - **完整视频生成工作流（推荐）** - Superpowers驱动的端到端视频生成系统，包含4个阶段：
  - Phase 0: 准备阶段（环境初始化、输入验证）
  - Phase 1: 意图分析与Superpower选择（意图分析、知识图谱检索、AI驱动的Superpower选择、Baoyu映射）
  - Phase 2: 内容生成（并行生成脚本、视觉、音频）
  - Phase 3: 整合与渲染（合并视觉、添加音频/字幕、应用Superpower特效、FFmpeg渲染）
  - Phase 4: 质量控制（质量检查、意图一致性、Superpower一致性、优化建议）
  
  **快速开始**：
  ```bash
  python scripts/video-generation-workflow.py \
    --request "Create a product promotion video" \
    --platform douyin \
    --goal persuade \
    --output ./output
  ```
  
- [references/complete-workflow-guide.md](references/complete-workflow-guide.md) - **完整工作流指南** - 详细的4阶段流程说明、输出结果结构、使用示例、高级配置、故障排除

### 脚本工具（单功能组件）
- `scripts/vibevoice-asr-transcribe.py` - VibeVoice音频转文字（60分钟长音频、说话人识别、时间戳）
- `scripts/tts-generator.py` - TTS音频生成（多服务支持、发音变体、音频缓存、质量优化）
- `scripts/workflow-orchestrator.py` - 工作流编排器（节点式设计、自动执行、分镜生成、AI意图分析）
- `scripts/knowledge-graph-manager.py` - 知识图谱管理器（时态追踪、混合检索、个性化推荐、上下文管理）
- `scripts/copywriter-generator.py` - 文案生成器（视频脚本、营销文案、分镜文案、解说词、SEO关键词、社交媒体文案）
- `scripts/ai-media-generator.py` - AI媒体生成器（Superpower感知生成、多服务支持、批量生成、智能缓存）
- `scripts/superpower-orchestrator.py` - Superpower工作流编排器（完整四阶段流程：意图分析→Superpower选择→映射→生成）

### 设计系统参考
- [references/video-types.md](references/video-types.md) - 8种视频类型完整定义（自动选择逻辑、场景映射）
- [references/visual-styles.md](references/visual-styles.md) - 14种视觉风格详解（色彩、构图、动画特性）
- [references/platform-presets.md](references/platform-presets.md) - 平台优化预设（抖音、B站、小红书等）
- [references/baoyu-design-systems.md](references/baoyu-design-systems.md) - Baoyu设计系统完整指南（文章插图、知识漫画、封面图、信息图）
- [references/vibevoice-asr-guide.md](references/vibevoice-asr-guide.md) - VibeVoice-ASR完整使用指南
- [references/multilingual-support.md](references/multilingual-support.md) - 多语言支持完整指南（智能语言检测、AI翻译、20+语言）
- [references/ts-integration.md](references/ts-integration.md) - TTS集成完整指南（多服务支持、发音变体、音频缓存）
- [references/ai-prompt-optimization.md](references/ai-prompt-optimization.md) - AI提示词优化完整指南（风格修饰符、质量修饰符、构图提示）
- [references/storyboard-workflow.md](references/storyboard-workflow.md) - 分镜工作流完整指南（角色一致性、场景结构、多场景生成）
- [references/graphiti-integration.md](references/graphiti-integration.md) - Graphiti知识图谱集成完整指南（时态追踪、混合检索、个性化推荐）
- [references/copywriting-generation.md](references/copywriting-generation.md) - 文案生成完整指南（视频脚本、营销文案、分镜描述、旁白脚本、SEO关键词、社交媒体内容）
- [references/ai-media-generation.md](references/ai-media-generation.md) - AI媒体生成集成指南（Stable Diffusion、DALL-E、Runway、Pika、Sora，Superpower映射规则）
- [references/superpower-workflow.md](references/superpower-workflow.md) - Superpowers完整工作流指南（四阶段流程：意图分析→选择→映射→生成，节点集成）
- [references/superpower-baoyu-mapping.md](references/superpower-baoyu-mapping.md) - Superpower × Baoyu Design Systems完整映射指南（10个Superpower × 4个Baoyu系统，精细视觉控制）

