MDW Expedition — Phase 1

Cerro Chacaltaya / El Alto Slopes, Bolivia

Overview

MDW Phase 1 captures a single human subject — a 51-year-old, physically fit individual from the UK — living, moving, and making decisions in a novel high-altitude environment. The dataset is longitudinal, first-person, and recorded entirely in real-world conditions. It is designed for robotics, embodied AI, and human performance research, while remaining faithful to the lived reality of one person adapting to terrain, weather, fatigue, and minimalist living on a new continent.

This is not a staged experiment or laboratory simulation. It is a continuous, real-world capture of how one human operates day-to-day under physical and cognitive stress, with no scripted tasks and no artificial constraints.

Primary setting: the mid-to-upper slopes of Cerro Chacaltaya, near El Alto, Bolivia (~4,100–4,250 m).
This environment offers steep inclines, long declines, rocky paths, loose gravel, exposed plateaus suitable for sprinting and crawling, and quiet zones for cowboy camping, while remaining within walking distance (~45 minutes) of urban resupply.

Purpose & Scope

The purpose of Phase 1 is to create a high-fidelity, first-person longitudinal dataset documenting how a single human system adapts physically and cognitively over time.

Core dimensions include:

Human locomotion and physical adaptation across varied terrain

Cognitive decision-making under fatigue, altitude, and environmental stress

Minimalist living through cowboy camping and lightweight self-sufficiency

Interaction between exertion, recovery, environment, and daily decision cycles

Optional urban segments (El Alto pedestrian movement, vehicle interaction, markets, cafés) are captured only when naturally encountered. These segments extend environmental diversity but do not dilute the dataset’s primary focus on terrain, movement, and adaptation.

At its core, this dataset represents a day-in-the-life capture of one human, continuously observed across changing internal states and external conditions.

Research Questions (Analyst-Focused)

This dataset is designed so that external researchers can investigate questions such as:

How do fatigue, altitude, and terrain variability influence real-world decision-making?

How does gait, posture, and movement strategy adapt across terrain and weather over time?

What patterns emerge between exertion, recovery, and subsequent performance?

How does minimalist, off-grid living affect cognitive load and resilience?

How reliably can full-body mechanics be inferred from egocentric video alone?

How do short, discrete activity segments influence longer-term physical and cognitive states?

Physical Locomotion & Testing

Physical movement is a core stressor in the dataset and is intentionally above average for the subject’s age.

Captured locomotion modes include:

Walking: terrain-adaptive, incline/decline, load-bearing

Running: uneven terrain, endurance-oriented

Sprinting: short, high-intensity bursts

Quadrupedal locomotion: low-to-ground movement emphasizing stability, proprioception, and full-body engagement

Quadrupedal movement is characterized by:

Torso held low (approximately 15–30 cm above ground)

Alternating diagonal and lateral limb coordination

Continuous core stabilization and balance adjustment

Deliberate pacing rather than speed optimization

Movement occurs across all weather conditions where safe and is always paired with fatigue, pain, and environmental metadata.

Audio notes may accompany movement to capture spontaneous assessment and decision-making. Audio remains untranscribed.

🔬 Enhanced Validation: Occasional External Kinematic Reference

To bridge first-person environmental observation with biomechanical analysis, the dataset includes strategically captured external video segments. These serve as ground-truth windows, enabling validation of gait, posture, and limb positioning inferred from egocentric footage.

External capture is deliberately sparse and opportunistic, used only at moments of high analytical value so as not to disrupt the first-person narrative or decision flow.

Methodology

Static Tripod Shots
At significant terrain features (steep inclines, loose gravel fields, flat plateaus), a lightweight tripod is placed approximately 5–10 meters from the subject. The subject traverses the terrain past the camera, yielding side-on or three-quarter views of full-body kinematics for 30–60 seconds.

Dynamic Second-Person Shots
When a second individual is present and does not influence environmental decision-making, they may capture dynamic tracking footage alongside the subject, providing longer-duration external kinematic sequences.

Analytical Value

These external segments allow researchers to:

Correlate egocentric environmental context with external body mechanics

Validate pose and gait estimation models derived from first-person video

Extract discrete biomechanical reference points without motion-capture rigs

Metadata Integration

External segments are flagged within the standard segment schema:

Field	Possible Values	Description
external_view	none / tripod_static / second_person_dynamic	External camera presence
external_distance	3m / 5m / 10m	Approximate camera distance
external_angle	side / front / rear / 45_deg	Relative camera angle

These clips function strictly as validation and calibration tools, not primary locomotion footage.

Environment: Cerro Chacaltaya / El Alto Slopes

The Phase 1 environment provides:

Steep inclines and extended declines

Rocky paths and loose gravel

Plateaus suitable for sprinting, crawling, and camping

Quiet zones for uninterrupted capture

Proximity to urban infrastructure without continuous urban noise

Urban and cultural exposure occurs only when naturally encountered.

Data Structure
Start-of-Day Metadata

Captured once per day:

Expedition day, location, timezone

GPS coordinates and altitude

Terrain and elevation trend

Infrastructure and surface type

Gear state (footwear, pack, sleeping bag, clothing)

Physical and cognitive state: fatigue, pain, mood, alertness, stress, sleep quality

Environmental conditions: temperature, light, weather, heat stress, water status

Notes

Segment Metadata

Captured per activity segment:

Event trigger

Segment start and end time

GPS coordinates and altitude (start and end)

Terrain, surface, hazards, motion type

Gait changes, fatigue, pain

Weather and environmental exposure

Camera height, camera angle, FHD flag

Pack weight, clothing

Optional nutrition and water

Qualitative notes

End-of-Day Metadata

Captured once per day:

Location and timezone

GPS coordinates and altitude

Cumulative fatigue, pain, mood, alertness, stress

Environmental exposure summary

Gear condition

End-of-day reflections

Audio Notes

Audio notes capture off-the-cuff cognition, environmental reasoning, and decision-making as they occur. They remain audio-only and augment structured metadata rather than replacing it.

Data Governance, Capture & Robotics Focus

Forward-facing egocentric camera for locomotion and environmental interaction

SHA-256 hashes applied to all files to ensure integrity, reproducibility, and collaboration readiness

Metadata, audio, and video stored in structured JSON/CSV formats

Multimodal data enables robotics and AI teams to:

Train real-world navigation systems

Model gait and posture under environmental stress

Study terrain–human interaction

Simulate cognitive load during physical exertion

Dataset reviewed daily for completeness and accuracy

Designed for immediate usability by robotics and embodied AI teams

Future Phases (Conceptual Expansion)

Future phases are optional and will proceed only if they extend analytical value. Each phase introduces new environmental stressors while preserving methodological continuity for cross-phase comparison.

Potential environments include:

Nazca, Peru — hyper-arid desert terrain, thermal stress, long sightlines

Atacama Desert, Chile — extreme aridity, sparse resources, elevation variability

Arica, Chile — coastal desert combined with dense urban interaction

Sucre, Bolivia — mid-altitude urban navigation and routine formation

Across all phases, core constants remain:

Single-subject, first-person capture

Structured daily and segment metadata

Forward-facing camera orientation

GPS and altitude recorded for all days and segments

SHA-256 file integrity

Phase 1 stands as a complete dataset regardless of future expansion.

Outcome

Phase 1 delivers a longitudinal, multimodal, first-person dataset documenting how one physically capable human adapts cognitively and physically to a new, high-altitude environment through continuous real-world exposure.

The dataset is intended for direct use in research on locomotion modeling, embodied cognition, human–environment interaction, and AI systems grounded in reality rather than simulation.

Contact

For access inquiries or collaboration:
metadatawalker@gmail.com
