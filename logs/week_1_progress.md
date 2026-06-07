# Week 1 Progress Log

## Week 1 Objective
Set up the development environment, create the GitHub repository, prepare the folder structure, and select the Arabic OCR dataset.

## Completed Tasks
- Created GitHub repository.
- Created first Google Colab notebook.
- Installed required Python libraries.
- Prepared README file.
- Created initial project folder structure in Google Drive.
- Selected KHATT Arabic OCR dataset as the first dataset candidate.

## Next Tasks
- Load KHATT dataset.
- Inspect sample images and ground-truth text.
- Prepare preprocessing pipeline.
- Create train/validation/test split.

## Dataset Update

The KHATT dataset was initially selected as a candidate Arabic OCR dataset. However, when testing it in Google Colab, it could not be loaded because its Hugging Face version depends on an older custom dataset loading script. The newer Hugging Face datasets library no longer supports loading this type of script directly.

Because of this compatibility issue, the project will use `mssqpi/Arabic-OCR-Dataset`, which is available in a modern format and can be loaded more easily in Google Colab. This change keeps the project aligned with the original objective of building an Arabic OCR prototype while avoiding dataset-loading problems during implementation.
## Notes
This week focuses on project setup and dataset preparation before training the OCR models.
