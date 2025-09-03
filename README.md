# Project Overview

This project focuses on building an OCR (Optical Character Recognition) system for Arabic text, with support for both printed and handwritten documents. Arabic OCR is a challenging task due to the cursive nature of the script, context-dependent letter shapes, diacritics, and variability in handwriting styles.

The goal of this project is to create a deep learning–based pipeline that can detect, recognize, and digitize Arabic text, making it editable, searchable, and usable for real-world applications such as document digitization, archiving, and data management.

## Methodology

The project explores and fine-tunes different models for OCR:

CNN + Transformer architectures for text recognition.

Language models (GPT-2) for post-processing and extracting key attributes from recognized text.

Tesseract OCR fine-tuning as a baseline.

### Pipeline Stages:

Preprocessing – normalization, resizing, and enhancement of input images.

Text Detection & Recognition – converting images of Arabic text into digital text.

Postprocessing – error correction and attribute extraction using language models.


## Datasets

This project makes use of open-source datasets, including:

KHATT dataset

MohamedRashad/arabic-img2md

## Applications

Digitization of handwritten and printed Arabic documents.

Making archives and manuscripts searchable.

Assisting in data extraction from real-world Arabic texts.


## Evaluation Metrics

Word Error Rate (WER)

Character Error Rate (CER)
