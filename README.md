This dataset captures long-horizon egocentric locomotion, beginning in Santa Marta, Colombia, using a terrain- and state-triggered capture paradigm.

Video segments are recorded only when meaningful transitions occur, such as changes in terrain geometry, surface composition, weather conditions, or physiological state — and where allowed due to power availability.

All footage is forward-facing, silent, and uncompressed, providing clean visual input optimized for computer vision, robotics, and machine learning research.

Capture Paradigm

The dataset represents a continuous expeditionary walk, producing temporally coherent sequences suitable for long-horizon modeling.

Recording is event-driven rather than time-driven. Segments are initiated when the environment or human state changes in ways that are informative for downstream analysis.

Triggers include:

Terrain geometry transitions (flat → incline → decline, curvature changes)

Surface changes (paved, dirt, sand, rocky, loose aggregate)

Environmental shifts (weather, heat, wind, visibility)

Physiological state changes (fatigue, heat stress, gait adaptation)

Infrastructure encounters (settlements, bridges, man-made obstacles)

This results in sparse, high-information footage rather than redundant continuous recording.

Perspective and Modality

Single forward-facing camera angle

No speech or narration

No audio reliance

Consistent egocentric viewpoint

This design minimizes confounds and maximizes usability for vision-based systems, egocentric perception models, and navigation research.

GPS Anchoring

Each segment may include an optional GPS anchor recorded in metadata.

GPS anchoring enables:

Geospatial correlation

Trajectory reconstruction

Mapping and path analysis

Alignment with external geographic or environmental datasets

Exact locations are not embedded in video and can be abstracted as needed, preserving discretion while retaining analytical value.

Metadata Handling

Metadata is logged externally and maintained separately from video files.

This preserves the purity of the visual data while providing contextual ground truth for research and modeling.

Metadata may include high-level descriptors of:

Terrain and surface type

Environmental conditions

Physiological state indicators

Segment timing and expedition progression

Optional GPS anchor references

The metadata strategy prioritizes signal over exhaustiveness, maintaining mystery without sacrificing research utility.

Storage and Data Integrity

Videos are stored unmodified in their original capture format

No compression, re-encoding, trimming, or editing is applied

Files are stored both:

Locally on a desktop system

In cloud storage

A verification workflow ensures:

Each file is playable

Each segment is complete

Integrity is confirmed prior to any optional local cleanup

This establishes a clear and auditable chain from capture to storage.

Intended Use Cases

The dataset is designed for high-value applications including:

Egocentric perception and navigation

Long-horizon trajectory modeling

SLAM and visual localization evaluation

Robotics terrain traversal and planning

Human locomotion and fatigue modeling

Environmental and geospatial analysis

Robustness and domain generalization studies

Dataset Characteristics and Limitations

Real-world conditions are not controlled

Environmental variability is inherent and intentional

GPS accuracy reflects consumer-grade devices

Single-subject, first-person perspective

These properties are fundamental to the dataset’s authentic, expeditionary nature and should be considered in downstream use.
