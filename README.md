EmbodiedLab: Long-Horizon Egocentric Locomotion Dataset
TL;DR — Key Signals
✓ Single-person, fully documented expedition — complete traceability, auditable provenance ✅
✓ Event-driven capture — records only meaningful changes in terrain, surface, environment, or physiological state 🌄
✓ Forward-facing, silent, uncompressed video — optimized for AI, robotics, and computer vision research 🎥
✓ GPS-anchored segments with separate metadata — supports trajectory reconstruction, mapping, SLAM, geospatial analysis 📍
Dataset Overview
Continuous expeditionary walk through Ecuador, Peru, Chile, and Argentina, capturing long-horizon egocentric locomotion with a focus on desert and arid terrain environments.
Optimized for:
Egocentric perception & navigation
Long-horizon trajectory modeling
SLAM & visual localization
Robotics terrain traversal & planning
Human locomotion & fatigue modeling
Core principle: Event-driven recording triggers only when meaningful changes occur, producing sparse, high-information footage ideal for research and model training.
Capture Paradigm — Event Triggers Include:
Terrain geometry transitions (flat → incline → decline, curvature changes)
Surface changes (paved, dirt, sand, rocky, loose aggregate)
Environmental shifts (weather, heat, wind, visibility)
Physiological state changes (perceived fatigue, heat stress, gait adaptation — subjective observations only, no biometric sensors)
Infrastructure encounters (settlements, bridges, man-made obstacles)
Note on the Atacama Desert: Due to the vastness and extreme terrain, it may not be feasible to walk the entire stretch. Some segments may be traversed via vehicle or hitchhiking, and all such instances are documented in metadata for transparency and auditable provenance.
Result: High-signal segments with reduced redundancy and temporally coherent sequences suitable for long-horizon modeling.
Perspective & Modality
Single forward-facing camera
No audio or narration
Consistent egocentric viewpoint
Pure visual input, optimized for vision-based AI and robotics systems
GPS Anchoring & Metadata
Start and end-of-day GPS anchors plus per-segment metadata
Metadata includes:
Terrain & surface type
Environmental conditions
Physiological state indicators (subjective observations only, e.g., perceived fatigue, heat stress; no biometric sensor data)
Segment timing & expedition progression
Optional GPS anchor references
Purpose: Enables trajectory reconstruction, mapping, SLAM evaluation, while preserving discretion and analytical value
Metadata stored separately to maintain purity of visual data
Verification workflow confirms completeness and integrity prior to storage
Storage & Data Integrity
Videos stored unmodified in original capture format
Dual storage: local and cloud
Verification workflow ensures:
Segment completeness
Playability
Clear, auditable chain of custody
Provenance & Verification ✅
Chain of Custody: Every video segment is tracked from capture → local storage → cloud ingestion → distribution. Full logs maintain who handled the file and when, ensuring auditable provenance.
Hash Verification: Upon desktop ingestion, each file has a SHA‑256 hash generated and logged. This allows buyers to verify the exact integrity of every segment before use.
Segment Integrity Checks: The verification workflow ensures:
Complete segments (no missing frames)
Playable files (uncompressed FHD)
Metadata matches video segments
Transparency: Any deviations, e.g., vehicle-assisted segments in the Atacama, are explicitly documented in metadata.
Bottom line: Buyers can confidently confirm that each file is exactly as captured in the field, fully auditable, and traceable.
Single-Person, Single-Source Advantages
Complete traceability — fully documented segments
Compliance-friendly — no multi-party ownership or consent ambiguity
Uniform quality — consistent camera angle, metadata strategy, and capture paradigm
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
Some desert segments (e.g., Atacama) are vehicle-assisted/hitchhiked due to extreme terrain
Designed for research, modeling, and benchmarking, not continuous commercial mapping
Prospective Buyer Questions — Anticipated & Answered
1️⃣ Is this data real and high-quality?
Continuous field capture across Ecuador, Peru, Chile, and Argentina, FHD, event-driven, forward-facing egocentric video. Focus on desert/arid terrain with realistic human locomotion. Segments are sparse, high-information, and fully traceable.
2️⃣ Is it reliable and unaltered?
Files undergo desktop ingestion where SHA‑256 hashes are generated and logged. From this point onward, integrity is fully verifiable, ensuring immutability for downstream AI and robotics applications.
3️⃣ Is it usable at scale?
Standardized files (FHD, 30 fps, MP4) with consistent naming and separate detailed metadata including GPS, terrain, environmental, and physiological observations. Designed for direct use in SLAM, trajectory modeling, and robotics pipelines.
4️⃣ What makes it unique?
Long-horizon, single-person egocentric locomotion across natural terrain, including desert sections such as the Atacama. Due to the desert’s vastness, some segments are vehicle-assisted/hitchhiked — fully documented in metadata. Continuous capture preserves rare terrain transitions and human gait/fatigue patterns unavailable via scraping or synthetic data. Fully auditable and single-source.
Contact & Licensing
Contact: Michael Dee — fieldwalk.data@gmail.com
Licensing: Single-source, fully auditable dataset. Licensed for research, AI training, and robotics applications.
Free sample access available for qualified researchers
Commercial use requires explicit permission and licensing agreement
About
Created by Michael Dee — one person, one phone, one continuous expedition
