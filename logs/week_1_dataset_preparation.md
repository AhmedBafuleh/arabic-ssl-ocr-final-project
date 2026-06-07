# Week 1 Dataset Preparation

## Objective

The objective of this step was to prepare a small working Arabic OCR dataset sample for the first prototype.

## Dataset Used

The project initially considered the KHATT Arabic OCR dataset. However, during testing in Google Colab, the dataset could not be loaded because its Hugging Face version depends on an older custom dataset loading script.

Because of this compatibility issue, the project used `mssqpi/Arabic-OCR-Dataset`, which loaded successfully in Google Colab and provided both Arabic text images and ground-truth Arabic text labels.

## Completed Work

A small working sample of 200 Arabic OCR image-text pairs was saved into the Google Drive project folder.

The following preparation steps were completed:

1. Arabic OCR samples were loaded from Hugging Face.
2. Image files were saved into the project folder.
3. Metadata was saved in CSV format.
4. Arabic text labels were cleaned.
5. Images were converted to grayscale.
6. Images were resized and padded/cropped to a fixed size of 512 × 64.
7. The dataset was divided into training, validation, and testing sets.

## Dataset Split

* Training samples: 160
* Validation samples: 20
* Testing samples: 20

## Created Local Data Files

The following files were created locally in Google Drive:

* `data/raw/sample_metadata.csv`
* `data/raw/sample_images/`
* `data/processed/processed_metadata.csv`
* `data/processed/images/`
* `data/splits/train.csv`
* `data/splits/val.csv`
* `data/splits/test.csv`

## Notes

The image dataset itself will not be uploaded to GitHub because it may become large. GitHub will be used mainly for documentation, notebooks, scripts, logs, and final project tracking.







