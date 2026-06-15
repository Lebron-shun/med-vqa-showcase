# Privacy And Safety Statement

This static website was prepared for public project demonstration.

## De-identification Scope

The repository only includes:

- de-identified case IDs
- rendered PNG images derived from CT data
- selected QA text and evaluation summaries
- report figures for competition presentation

The repository does not include:

- original DICOM files
- patient names or personal identifiers
- DICOM StudyInstanceUID, SeriesInstanceUID, SOPInstanceUID, or source file names
- internal server paths
- model weights or full training data

## Clinical Safety Scope

The showcase demonstrates a research prototype for assisted review. It should not be used for clinical decision-making.

The intended message is:

- the system can help organize reports, QA text, and clinical elements;
- the system can flag missing evidence and selected risky outputs;
- final interpretation belongs to qualified physicians;
- unverified ROI or slice evidence is blocked by Evidence Gate and should not enter the answer generation chain.

## Known Limitations

- The demonstrated predictions are offline examples, not real-time inference.
- Case-level image binding under wrong-patient image perturbation remains a known limitation.
- The system does not replace original DICOM review.
- The metrics shown here are for research reporting and competition demonstration.

