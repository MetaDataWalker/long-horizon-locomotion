Long-Horizon Egocentric Locomotion Dataset

One-person, fully traced expedition — clean, legally safe, and fully auditable provenance ✅

Event-driven capture — records only meaningful changes in terrain, surface, environment, or physiological state

Forward-facing, silent, uncompressed video — optimized for AI, robotics, and computer vision research

GPS-anchored segments with metadata — supports trajectory reconstruction, mapping, and SLAM while preserving discretion

Dataset Overview

This dataset captures long-horizon egocentric locomotion, beginning in Santa Marta, Colombia, using a terrain- and state-triggered event capture paradigm. It is optimized for egocentric perception, long-horizon trajectory modeling, SLAM, navigation, and robotics research.

Capture Paradigm

The dataset represents a continuous expeditionary walk, generating temporally coherent sequences appropriate for long-horizon perception and planning tasks.

Recording is event-driven rather than time-driven. Segments are initiated when changes occur that are informative for analysis or model training.

Trigger conditions include:

Terrain geometry transitions (flat → incline → decline, curvature changes)

Surface changes (paved, dirt, sand, rocky, loose aggregate)

Environmental shifts (weather, heat, wind, visibility)

Physiological state changes (fatigue, heat stress, gait adaptation)

Infrastructure encounters (settlements, bridges, man-made obstacles)

This approach prioritizes information density over duration, reducing redundancy while preserving contextual continuity.

Perspective and Modality

Single forward-facing camera

No speech or narration

No audio reliance

Consistent egocentric viewpoint

This design minimizes confounding variables and maximizes usability for vision-based systems, egocentric perception models, and navigation research.

GPS Anchoring

Start and end-of-day anchors, plus per-segment metadata

Supports geospatial correlation, trajectory reconstruction, mapping, and path analysis

Exact locations can be abstracted to preserve discretion while retaining analytical value

Metadata Handling

Metadata is logged externally and separately from video files

Includes high-level descriptors of:

Terrain and surface type

Environmental conditions

Physiological state indicators

Segment timing and expedition progression

Optional GPS anchor references

This preserves the purity of visual data while providing contextual ground truth for research and modeling.

Storage & Data Integrity

Videos are stored unmodified in original capture format

Stored both locally and in cloud storage

Verification workflow ensures:

Each file is playable

Each segment is complete

Integrity is confirmed prior to any optional local cleanup

Establishes a clear, auditable chain from capture to storage.

Single-Person, Single-Source Advantages

Complete provenance and traceability — every segment is fully documented ✅

Compliance-friendly — aligns with GDPR and EU AI Act transparency expectations for AI training data

Consistent quality — uniform camera angle, metadata strategy, and capture paradigm

High signal, low noise — event-driven capture ensures meaningful content

Simplified licensing and distribution — no multi-party ownership issues

Ideal for validation and benchmarking — fully transparent and auditable dataset

Intended Use Cases

Egocentric perception and navigation

Long-horizon trajectory modeling

SLAM and visual localization evaluation

Robotics terrain traversal and planning

Human locomotion and fatigue modeling

Environmental and geospatial analysis

Robustness and domain generalization studies

Dataset Characteristics and Limitations

Real-world conditions are inherently variable

Single-subject, first-person perspective

GPS accuracy reflects consumer-grade devices

Designed for research, modeling, and benchmarking, not continuous commercial mapping

Citation & Compliance

This dataset aligns with data transparency and provenance requirements under emerging AI regulation:

“Under the EU Artificial Intelligence Act, providers of general-purpose AI models must publish high-level summaries of the data sources used in training, including major domains and dataset origins — increasing transparency and supporting lawful, responsible use.”

Licensing and attribution are simplified due to single-source ownership.
