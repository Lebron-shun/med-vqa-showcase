# Med-VQA Lung CT Showcase

This repository hosts a static, de-identified showcase page for the project:

**基于多模态大模型的肺部CT影像问答解读系统**

The page is designed as an online companion for a biomedical engineering competition report. It demonstrates a research prototype for lung CT question answering, report interpretation, clinical element review, missing-evidence refusal, and Evidence Gate safety control.

## Live Demo

After GitHub Pages is enabled, the page will be available at:

```text
https://Lebron-shun.github.io/med-vqa-showcase/
```

## What Is Included

- Static HTML/CSS/JavaScript page.
- De-identified case IDs used in the report: `05296`, `00942`, `01096`.
- Rendered CT PNG assets:
  - overview montage
  - dense axial montage
  - DICOM-derived slice PNGs
- QA examples, reference answers, model answers, and summary metrics.
- Report figures used for the public showcase.

## What Is Not Included

- No raw DICOM files.
- No patient identity information.
- No server paths, DICOM UIDs, or local absolute paths.
- No model weights, training datasets, or private evaluation outputs.

## Medical Disclaimer

This project is a research and education prototype. The web page is not a medical device and does not provide clinical diagnosis. All displayed answers and metrics are for competition demonstration and research discussion only. Any clinical interpretation must be reviewed by qualified radiologists using the original imaging data and clinical context.

## Project Positioning

The system is positioned as a doctor-review-oriented auxiliary workflow:

- report structuring
- evidence-driven Chinese QA explanation
- clinical element consistency review
- missing input refusal
- model safety audit and Evidence Gate

It is not presented as an autonomous lung nodule diagnosis system.

## Repository Structure

```text
.
├── index.html
├── assets/
│   ├── cases/
│   └── figures/
├── showcase_payload_public.json
├── README.md
├── LICENSE
└── PRIVACY_AND_SAFETY.md
```

## Local Preview

Open `index.html` directly in a browser, or run:

```bash
python -m http.server 8000
```

Then visit:

```text
http://127.0.0.1:8000/
```

