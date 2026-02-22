EmbodiedLab: Long-Horizon Egocentric Locomotion Dataset
TL;DR — Key Signals
✓ Single-person, fully documented expedition — complete traceability, auditable provenance ✅
✓ Event-driven capture — records only meaningful changes in terrain, surface, environment, or physiological state 🌄
✓ Forward-facing, silent, uncompressed video — optimized for AI, robotics, and computer vision research 🎥
✓ GPS-anchored segments with separate metadata — supports trajectory reconstruction, mapping, SLAM, geospatial analysis 📍
Dataset Overview
This dataset captures a continuous expeditionary walk through Ecuador, Peru, Chile, and Argentina, focusing on desert and arid terrain environments. It documents long-horizon egocentric locomotion with high fidelity and traceable provenance.
Optimized for:
Egocentric perception & navigation
Long-horizon trajectory modeling
SLAM & visual localization
Robotics terrain traversal & planning
Human locomotion & fatigue modeling
Core principle: Event-driven recording triggers only when meaningful changes occur, producing sparse, high-information footage ideal for research and AI model training.
Capture Paradigm — Event Triggers Include:
Terrain geometry transitions: flat → incline → decline, curvature changes
Surface changes: paved, dirt, sand, rocky, loose aggregate
Environmental shifts: weather, heat, wind, visibility
Physiological state changes: perceived fatigue, heat stress, gait adaptation (subjective observations only; no biometric sensors)
Infrastructure encounters: settlements, bridges, man-made obstacles
Note on the Atacama Desert: Some stretches may be vehicle-assisted or hitchhiked due to extreme terrain. All such instances are documented in metadata for full transparency and auditable provenance.
Result: High-signal segments with reduced redundancy and temporally coherent sequences suitable for long-horizon modeling.
Perspective & Modality
Single forward-facing camera
No audio or narration
Consistent egocentric viewpoint
Pure visual input optimized for vision-based AI and robotics systems
GPS Anchoring & Metadata
Start and end-of-day GPS anchors, plus per-segment metadata
Metadata includes:
Terrain & surface type
Environmental conditions
Physiological state indicators (subjective observations only)
Segment timing & expedition progression
Optional GPS anchor references
Purpose: Enables trajectory reconstruction, mapping, and SLAM evaluation while preserving analytical value. Metadata is stored separately to maintain the purity of visual data. Verification workflows confirm completeness and integrity prior to storage.
Storage & Data Integrity
Videos stored unmodified in original capture format
Dual storage: local and cloud
Verification workflow ensures:
Segment completeness
Playability (uncompressed FHD)
Metadata matches video segments
Provenance & Verification ✅
Chain of Custody: Every video segment is tracked from capture → local storage → cloud ingestion → distribution, with full logs of who handled each file and when.
Hash Verification: SHA‑256 hashes generated at desktop ingestion allow buyers to confirm file integrity.
Segment Integrity Checks: Ensure complete, playable segments that match metadata.
Transparency: Vehicle-assisted or hitchhiked segments in extreme terrain are explicitly documented.
Bottom line: Buyers can confirm that each file is exactly as captured in the field, fully auditable, and traceable.
Single-Person, Single-Source Advantages
Complete traceability — fully documented segments
Compliance-friendly — no multi-party ownership or consent ambiguity
Uniform quality — consistent camera angle, metadata, and capture paradigm
High signal, low noise — only meaningful content captured
Simplified licensing & distribution — ready for research and AI model training
Intended Use Cases
Egocentric perception & navigation
Long-horizon trajectory modeling
SLAM & visual localization evaluation
Robotics terrain traversal & planning
Human locomotion & fatigue modeling
Environmental & geospatial analysis
Robustness & domain generalization studies
Limitations
Single-subject perspective
GPS reflects consumer-grade device accuracy
Real-world environmental variability is inherent
Some desert segments (e.g., Atacama) may be vehicle-assisted or hitchhiked
Designed for research, modeling, and benchmarking, not continuous commercial mapping
Prospective Buyer Questions — Anticipated & Answered
1️⃣ Is this data real and high-quality?
Yes — continuous field capture across Ecuador, Peru, Chile, and Argentina, FHD, event-driven, forward-facing egocentric video. Focus on desert/arid terrain with realistic human locomotion. Segments are sparse, high-information, and fully traceable.
2️⃣ Is it reliable and unaltered?
Yes — files undergo desktop ingestion where SHA‑256 hashes are generated and logged. Integrity is fully verifiable for downstream AI and robotics applications.
3️⃣ Is it usable at scale?
Yes — standardized files (FHD, 30 fps, MP4) with consistent naming and detailed metadata including GPS, terrain, environmental, and physiological observations. Ready for SLAM, trajectory modeling, and robotics pipelines.
4️⃣ What makes it unique?
Long-horizon, single-person egocentric locomotion across natural terrain, including desert sections such as the Atacama. Vehicle-assisted or hitchhiked segments are documented in metadata. Preserves rare terrain transitions and human gait/fatigue patterns unavailable via scraping or synthetic data. Fully auditable and single-source.
Contact & Licensing
Contact: Michael Dee — fieldwalk.data@gmail.com
Licensing: Single-source, fully auditable dataset. Licensed for research, AI training, and robotics applications.
Free sample access available for qualified researchers
Commercial use requires explicit permission and licensing agreement
About
Created by Michael Dee — one person, one phone, one continuous expedition.
