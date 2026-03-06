MetaDataWalker (MDW) — Longitudinal, Multimodal Human Locomotion Dataset

Owner / Creator: Michael Dee
Contact: metadatawalker@gmail.com

Dataset Type: First-person, longitudinal, multimodal video + audio + structured metadata
Scope: 5 phases, 6 months each, across Peru, Chile, Argentina, Bolivia
Subject: Single 51-year-old physically fit human (dataset owner)
Use Cases: Robotics, embodied AI, biomechanics, VR/AR simulation, human adaptation research

1. Dataset Overview

MetaDataWalker (MDW) is a longitudinal, multimodal dataset capturing real-world human adaptation to terrain, altitude, and environmental stress. It includes:

Egocentric video (FHD) capturing all naturally occurring movement

Audio, recorded opportunistically, documenting cognition, environmental reasoning, and reflections

Structured metadata, including location, terrain, motion, fatigue, gear, weather, psychological state, and nutrition/energy

High-intensity validation clips, recorded only when such conditions naturally occur, for precise biomechanics and AI modeling

Scope: 5 phases of 6 months each, providing longitudinal coverage in extreme and diverse terrains.

Unique Value:

First-person, longitudinal, multimodal data in extreme environments

Captures authentic human adaptation under variable conditions

Detailed metadata supports AI, robotics, VR/AR, and biomechanics applications

Audio/video recording is opportunistic, reflecting real-world activity rather than pre-planned actions

Daily Lifestyle: Cowboy camping, self-sufficient off-grid living, walking 30–75 minutes daily for resupply. Movement is determined by terrain, environmental conditions, and subject state.

2. Expedition Summary
Phase	Country	Base Region	Terrain	Duration	Key Features
1	Peru	Nazca Hills	Desert hills, sandy & rocky	6 months	Longitudinal off-grid capture; opportunistic recording of physical and environmental adaptation; multimodal video/audio/metadata
2	Chile	Atacama Highlands	Arid plateau, rocky slopes	6 months	Longitudinal off-grid capture; opportunistic recording; multimodal data; high-altitude exposure
3	Argentina	Puna Grasslands	Volcanic outcrops, uneven terrain	6 months	Longitudinal off-grid capture; opportunistic recording; multimodal data; uneven terrain exposure
4	Bolivia	Cerro Chacaltaya	High-altitude slopes, rocky paths	6 months	Longitudinal off-grid capture; opportunistic recording; multimodal data; extreme altitude exposure
5	Bolivia	Sajama Foothills	High-altitude foothills, volcanic terrain	6 months	Longitudinal off-grid capture; opportunistic recording; multimodal data; cross-border exposure

Expedition Notes:

Each phase captures real-world, adaptive human movement, reflecting terrain, fatigue, and environmental conditions.

Cowboy camping provides authentic off-grid environmental exposure.

Audio/video capture is opportunistic, augmented only during rare high-effort or urban segments.

High-intensity sessions are recorded when they naturally occur, sometimes using tripod or third-party observation for validation.

3. Audio Capture & Physical Locomotion

Audio: Captured opportunistically to record cognition, environmental reflections, and reasoning.

Physical Locomotion:

The dataset captures a range of naturally occurring movement, without pre-planning

Quadrupedal movement, walking, running, or other movements occur as conditions dictate

High-Intensity Validation: Recorded only when naturally occurring, ensuring data integrity for AI, robotics, or biomechanics

4. Core Dimensions & Research Questions

Dimensions Captured:

Human locomotion under variable terrain and environmental stress

Cognitive adaptation under fatigue, altitude, and off-grid living

Interaction between exertion, recovery, environment, and daily activity cycles

Opportunistic audio/video capture for multimodal context

Kinetic and biomechanical validation as it naturally occurs

Research Questions Examples:

How does fatigue and terrain variability affect gait and posture?

How are exertion, recovery, and performance correlated?

How does cognitive load evolve under minimalist, off-grid living?

Can full-body mechanics be inferred from first-person video and metadata?

How do naturally occurring high-effort movements affect biomechanical efficiency and cognitive load?

5. Environment & Terrain
Location	Terrain	Surface	Altitude / Stress	Notes
Nazca hills, Peru	Desert hills	Sandy & rocky	Moderate	Opportunistic movement capture; inclines, dry, loose surfaces
Atacama hills, Chile	Arid highlands	Rocky slopes, loose gravel	High	Sparse vegetation, wind exposure; adaptive activity capture
Puna grasslands, Argentina	Volcanic outcrops	Uneven grasslands	High	Opportunistic activity capture; endurance and adaptive movement
Cerro Chacaltaya, Bolivia	Slopes	Rocky paths	Extreme	Opportunistic high-effort activity under extreme altitude
Sajama foothills, Bolivia	Foothills, volcanic terrain	Mixed rocky	Extreme	Cross-border adaptive movement captured opportunistically
6. Metadata Structure

Sections & Variables:

Section	Key Variables
Context & Timing	Date, expedition day, country, region, nearest town, event trigger, segment start/end
Environment & Terrain	Elevation trend, slope, terrain type, surface type/condition, hazards, infrastructure, motion type
Physical & Gait	Gait changes, fatigue (1–5), pain/issues, footwear condition, pack weight, vitals
Weather & Stressors	Temperature, light, weather, heat/cold stress (1–5), hydration, wind speed/direction
Cognitive / Psychological	Mood (1–5), alertness (1–5), stress level (1–5), decision load, sleep/rest
Gear / Recording	Camera height/angle, FHD, clothing, poles/GPS/phone, other equipment
Nutrition / Energy (optional)	Food consumed, energy level, electrolytes/hydration
Notes / Observations	Decisions, environmental/social context, rare events

Example Metadata JSON:

{
  "date": "2026-03-06",
  "expedition_day": 145,
  "country": "Peru",
  "region": "Nazca Hills",
  "nearest_town": "Nazca",
  "event_trigger": "steep incline, fatigue high",
  "segment_start": "08:15",
  "segment_end": "08:45",
  "terrain": {
    "elevation_trend": "uphill",
    "terrain_type": "mixed",
    "surface_type": "rocky",
    "surface_condition": "loose",
    "motion_type": "walk"
  },
  "physical": {
    "gait_changes": "shortened stride, slower pace",
    "fatigue": 4,
    "pain": "mild knee discomfort",
    "pack_weight": 12
  },
  "weather": {
    "temperature": 22,
    "light": "morning bright",
    "wind": 10
  },
  "cognitive": {
    "mood": 4,
    "alertness": 3,
    "stress": 2,
    "decision_load": "medium",
    "sleep_quality": 4
  },
  "gear": {
    "camera_height": "1.6m",
    "camera_angle": "forward",
    "FHD": true,
    "clothing": "layers, breathable"
  }
}
7. Commercial Value & Use Cases

Rare longitudinal data: 5 phases × 6 months each

Multimodal & structured: Video + audio + rich metadata

Opportunistic, adaptive movement: Captures authentic behavior under real-world conditions

Extreme terrains: Desert, highlands, grasslands, volcanic, high-altitude

Immediate integration: Robotics, AI, VR/AR, biomechanics

Buyer-Ready Use Cases:

Robotics locomotion modeling

AI embodied cognition research

VR/AR environmental simulation

Biomechanics and wearable technology development

8. Licensing & Commercial Use

Full ownership: All video, audio, and metadata belong to creator

Commercial licensing available: Non-exclusive or exclusive deals

Explicit subject consent: Dataset owner is the subject, cleared for commercial use

Preview available: Buyers encouraged to request sample clips and metadata

9. Contact

For dataset access, licensing, or collaboration:
Email: metadatawalker@gmail.com

