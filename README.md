# TruthLens - Multimodal Deepfake Detection

TruthLens is a system designed to analyse **images, audio, video, and text** and provide an interpretable assessment of potentially manipulated or AI-generated content.

# Features

- **Image analysis** — deepfake prediction with visual heatmap explainability
- **Audio analysis** — prediction with suspicious audio segments
- **Video analysis** — prediction with suspicious timestamps and frames
- **Text analysis** — prediction with sentence-level analysis

TruthLens uses modality-specific models to analyse different types of digital media. The system then combines the resulting predictions through a late-fusion approach to produce an overall assessment.

## Modality-level accuracies:
- Image	= 99.7%
- Audio	= 95.0%
- Video	= 90.4%
- Text	= 94.2%
