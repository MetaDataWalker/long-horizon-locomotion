MetaDataWalker

**Long-Horizon Egocentric Embodied Locomotion Dataset**  
**Last updated:** March 2025

---

## TL;DR

**MetaDataWalker** is a single-subject, fully documented, long-horizon egocentric dataset capturing continuous embodied human locomotion and decision-making during a real-world expedition across **Colombia, Ecuador, Peru, Chile, and Bolivia**.

The dataset records **movement and decisions as a coupled biological process**, evolving over time in response to terrain, environment, and internal physical state. Data consists of raw, forward-facing, silent, uncompressed Full HD video with consistent metadata, auditable provenance, and cryptographic integrity verification. Decision-making context is captured via contemporaneous audio logs, released as privacy-sanitized transcripts aligned to video segments.

The dataset prioritizes **longitudinal depth, ecological realism, and continuity** over subject diversity, making it suitable for research into embodied AI, robotics, and adaptive locomotion beyond controlled laboratory conditions.

---

## Core Principles

- Single human subject for viewpoint and behavioral consistency  
- Long-horizon continuity across countries, climates, and elevations  
- Biological navigation only (no GPS-based routing or turn-by-turn guidance)  
- Locomotion and decision-making captured together as a unified process  
- Raw data preservation with minimal preprocessing  
- Full auditability and verifiable provenance  

---

## Dataset Overview

MetaDataWalker captures a continuous expeditionary walk through **Colombia, Ecuador, Peru, Chile, and Bolivia**, spanning:

- Tropical and arid lowlands  
- Rocky mountain passes  
- Coastal corridors  
- Dense urban environments  
- Remote rural routes  
- High-altitude Andean plateau environments  

The dataset preserves ecological validity while supporting research into embodied systems operating under **unstructured, real-world conditions over extended time horizons**.

Walking behavior and decisions are inherently coupled. Terrain negotiation, balance maintenance, pacing, route choice, stopping behavior, and risk tolerance emerge as a **single adaptive biological process**, not discrete tasks. Visual, audio, and metadata modalities are maintained separately but are temporally and contextually linked, enabling multimodal research while retaining full traceability.

**Estimated total size:** ~200–300 GB (final size dependent on terrain density, capture frequency, and expedition duration)

---

## Data Composition

**Formats**
- Raw Full HD video (1920×1080), silent  
- Decision rationale transcripts (raw audio not distributed)  
- Screenshots with embedded GPS and altitude  
- Structured metadata (JSON / CSV)  

**Capture Characteristics**
- Forward-facing egocentric viewpoint  
- In-camera HDR, stabilization, and optimizations disabled  
- Approximately 1-minute video segments  
- Continuous capture driven by environmental relevance, not scripted triggers  

---

## Optimized For

- Egocentric perception and navigation  
- Long-horizon trajectory modeling  
- SLAM and visual localization  
- Terrain traversal and motion planning  
- Embodied AI and adaptive control  
- Altitude- and fatigue-constrained locomotion  
- Biologically grounded decision modeling  

---

## Embodied Adaptation & Decision Context

The dataset captures **real-time adaptation** in both movement and decision-making. Walking behavior evolves continuously in response to:

- Terrain geometry and surface compliance  
- Traction variability and surface condition  
- Environmental stressors (heat, wind, urban density, altitude)  
- Internal physical state (fatigue, pain, energy availability, heat stress)  

Decisions are expressed implicitly through gait modulation, posture, pacing, route selection, stopping behavior, and risk avoidance, and explicitly through contemporaneous audio reasoning.

Decision categories include:

- Route selection and deviation  
- Pacing and rest timing  
- Risk tolerance and hazard avoidance  
- Energy and water management  

Audio transcripts document **timing, rationale, and contextual triggers**, providing a longitudinal signal for modeling adaptive human behavior under dynamic physical and environmental constraints.

High-altitude environments, particularly in Bolivia, introduce sustained physiological load that influences pacing, gait stability, and decision thresholds. These effects are captured implicitly through behavioral adaptation and decision rationale rather than through medical instrumentation.

---

## Relevance to Robotics & Embodied Systems

Embodied systems must operate in environments characterized by:

- Irregular terrain  
- Variable traction and surface compliance  
- Environmental stress  
- Cumulative fatigue and disturbance  

MetaDataWalker captures human locomotion under such conditions, including moments where balance is challenged but maintained through continuous micro-adjustments rather than failure and recovery.

Observed behaviors include:

- Minor slips and transient traction loss  
- Rapid foot placement and stance correction  
- Upper-body compensation and momentum regulation  
- Smooth gait adaptation following disturbance  

These naturally occurring transitions provide reference data for:

- Humanoid and legged robotics  
- Assistive mobility and prosthetics  
- Biomechanics and human movement modeling  
- Simulation and digital twin environments  
- Safety and failure-avoidance modeling  

---

## Capture Paradigm

Recording is **fully context-driven**, with no predefined triggers or scripted scenarios.

Data is captured whenever terrain, environmental conditions, or embodied state indicate relevance.

- Video segments: ~1 minute  
- Audio rationale: recorded contemporaneously, released as transcripts  
- Screenshots: environmental context, signage, terrain details  

Vehicle-assisted or hitchhiked segments are explicitly documented for transparency and exclusion.

---

## Data Modalities

**Video**
- Raw Full HD (1920×1080), silent  
- Forward-facing egocentric viewpoint  
- No stabilization, HDR, or overlays  

**Audio**
- Decision rationale recordings  
- Raw audio not distributed  
- Privacy-sanitized transcripts released  

**Screenshots**
- Environmental context, signage, terrain  
- Embedded EXIF GPS and altitude  
- No added graphics or annotations  

**Metadata**
- Structured JSON/CSV per segment  
- Baseline and augmented fields  

---

## GPS & Location Data

**Purpose:** Measurement only, not navigation.

- Navigation decisions are made biologically using eyesight, maps, signage, and local advice  
- Location services active only at segment start/end and screenshot capture  
- Video segments (~1 minute) include start and end coordinates  
- Screenshots provide additional geo-referenced context  

**Provided Data**
- Start of day: GPS coordinate + altitude  
- Each video segment: start/end GPS + altitude  
- Each audio segment: start/end GPS + altitude  
- Screenshots: GPS + altitude embedded in EXIF  
- End of day: GPS coordinate + altitude  

---

## Metadata Schema

Metadata is structured in two tiers: **Baseline** and **Augmented**.

### Baseline Fields
DATE, EXPEDITION DAY, COUNTRY, COUNTRY DAY, REGION, NEAREST PLACE, TIMEZONE, EVENT TRIGGER, SEGMENT START TIME, SEGMENT END TIME, ELEVATION TREND, TERRAIN, TEMPERATURE, INFRASTRUCTURE, SURFACE, SURFACE CONDITION, STABILITY, TRACTION, LIGHT, WEATHER, GAIT CHANGES, MOTION, FOOT PLACEMENT, HAZARDS, HEAT STRESS, WATER END, FATIGUE, PAIN/ISSUES, FOOTWEAR CONDITION, PACK WEIGHT, CAMERA HEIGHT, CAMERA ANGLE, NOTES

### Augmented Fields

**Arid Zones**
- SAND TYPE  
- SURFACE STABILITY  
- DUST  
- CRACK DENSITY  
- VEGETATION  
- HEAT REFLECTION  
- WIND  
- WATER AVAILABILITY  

**Urban Zones**
- TRAFFIC DENSITY  
- PEDESTRIAN DENSITY  
- CROSSINGS  
- OBSTACLE TYPE  
- SURFACE VARIABILITY  
- NOISE LEVEL  
- LIGHTING  
- NAVIGATION METHOD  
- URBAN TYPE  
- SIDEWALK CONDITION  

---

## Audio & Privacy

- Audio captures real-time decision rationale  
- Raw audio files are not distributed  
- Transcripts generated using AI-assisted transcription and manually reviewed  
- Names, addresses, and third-party speech removed  
- Transcripts are timestamp-aligned to video segments  

All data is collected in public spaces and aligned with local laws and ethical research standards.

---

## Quality Control Indicators

- Disturbance-driven adaptations preserved  
- Non-failure stabilization sequences retained  
- Balance-challenging conditions captured without catastrophic falls  
- Continuous stabilization emphasized over post-fall recovery  

---

## Data Integrity & Provenance

- End-to-end chain of custody: capture → local device → cloud → desktop ingestion  
- All transfers logged with timestamps  
- Cryptographic integrity verification (SHA-256 baseline checks)  
- Segment completeness, playability, and metadata alignment verified  

The dataset is auditable and legally compliant. Single-subject sourcing simplifies licensing and attribution. Scope is intentionally narrow; researchers should consider this when interpreting generalization.

---

## Subject & Safety Context

- Single, consistent human subject for viewpoint stability  
- Movement reflects natural responses to terrain, traction, fatigue, and environmental exposure  
- No supports, tethers, corrective aids, or staged recovery behaviors  
- Safety ensured via conservative exposure limits and immediate cessation if traversal exceeds safe thresholds  

---

## Licensing & Access

- **Research / AI / robotics:** Free sample access for qualified researchers  
- **Commercial use:** Explicit permission and licensing agreement required  
- **Privacy:** Audio transcribed; raw audio not distributed; GPS limited to segment start/end and screenshot EXIF only  

---

## Contact

**Michael Dee**  
One person. One phone. One continuous expedition.  
📧 metadatawalker@gmail.com
