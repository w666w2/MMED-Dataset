# MMED: Multimodal Audio-Visual Micro-Expression Dataset

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

The MMED dataset will be released in this repository upon acceptance of the manuscript.

MMED is the **first speech-concurrent micro-expression dataset**, capturing spontaneous micro-expressions during high-stakes verbal communication in televised Werewolf (social deduction game) competitions.

🔐 Access Restriction: Due to the sensitive nature of facial micro-expression annotations, access to MMED annotations and splits is granted upon request. Please see [📥 Data Access](#-data-access) below for instructions.

## 📊 Overview

| Item | Value |
|------|-------|
| Total valid micro-expression samples | 191 |
| Subjects / Speakers | 16 |
| Source videos | 7 (publicly broadcast) |
| Emotion categories | Positive (56), Negative (37), Surprise (98) |
| Annotation protocol | FACS-certified, dual-annotator |
| Inter-annotator agreement | Dice coefficient r = 0.89 |
| Modalities | Video (onset/apex frames) + Audio (active speech) |
| Micro-expression duration | < 500 ms |

## 📁 Repository Structure

```
MMED/
├── README.md
├── LICENSE
├── annotations/
│   ├── mmed_annotations.xlsx     # Core annotation file
│   └── source_urls.txt           # Original video URLs + access timestamps
├── splits/
│   └── loso_splits.json          # LOSO-CV fold assignments (16 folds)
└── docs/
    └── annotation_manual.pdf     # Annotation guidelines (optional)
```

## 🎬 Accessing the Source Videos

**We do not redistribute raw videos, edited clips, video frames, or audio segments.** The annotation files reference publicly available broadcasts. The copyright of the source videos remains with the original rights holders. Researchers who wish to access the underlying footage must obtain it independently from publicly available sources. Original source URLs with access timestamps are provided in `annotations/source_urls.txt`.

## 📖 Citation





## 📜 License

The MMED annotations and documentation in this repository are licensed under the [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/) license for non-commercial research use only.

The copyright of the original source videos remains with their respective rights holders. No video, audio, or image content is distributed under this license.

## 🛡️ Privacy & Takedown Policy

All annotations are fully de-identified: contestants are referred to only by arbitrary numeric indices. No names, demographic attributes, or speech transcripts are included.

Should any individual featured in the source videos object to the inclusion of annotations pertaining to them, the corresponding entries will be removed from the dataset upon request.
