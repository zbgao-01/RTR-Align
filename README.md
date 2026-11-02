# RTR-Align

## 1. Overview

RTR-Align is a framework for recognizing and localizing safety violations on construction sites by aligning safety rules with image regions. In this study, we refined the annotations in the ConstructionSite10k dataset to support more accurate violation recognition and spatial localization.

## 2. Annotation Refinement Workflow

SAM3 and GPT5.5 suggested candidate targets for review. Two authors checked the original annotations and model suggestions against the images and applicable safety rules, then used Label Studio to correct bounding boxes, rule labels, and violation explanations where needed.

For quality control, two additional reviewers checked the revised annotations for completeness and consistency. The authors corrected flagged records and resubmitted them for review. When a case remained disputed, the authors and reviewers discussed the evidence, and Z.G. made the final decision.

[Google Drive – Annotation Refinement Workflow](https://drive.google.com/drive/folders/12Umfp0Gj9Ul-8dJZ3yWrgK8lWqWUYLZS?usp=drive_link)

## 3. Annotation Guidelines

Annotation refinement addresses three main issues.

1. **Merged instances.** Annotate each target separately when multiple targets are grouped within a single bounding box.
2. **Inaccurate boundaries.** Adjust bounding boxes to better fit the target regions in the image.
3. **Missing annotations.** Add annotations for omitted targets based on safety rules and visual evidence.

[Google Drive – Annotation Guidelines](https://drive.google.com/drive/folders/1Rj9pcB9QHkQoFtWhzcSc-LJF2j43waAV?usp=drive_link)

## 4. Refined Annotations

The refined annotations and related files released as part of this study are available through the Google Drive link below. This release does not include the original images from the ConstructionSite10k dataset. If you use the original images, please follow the dataset's licensing terms and obtain any necessary permissions.

[Google Drive – Refined Annotations](https://drive.google.com/drive/folders/1yRGvbbVyuIWYYs7Y0r-EN2N0Nbk1Z-xz?usp=drive_link)

## 5. System and User Prompts

The full system and user prompts used in this study are available at the link below.

[Google Drive – System and User Prompts](https://drive.google.com/drive/folders/1wGXWCY1t9lZP4aMGzsbLP78lHYGPHc_7?usp=drive_link)
