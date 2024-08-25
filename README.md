# Image-to-Text-Extraction-with-Tesseract-OCR

## Project Overview

This project demonstrates the use of Tesseract OCR to extract text from images in the IIIT-5K Word Dataset. The objective is to evaluate the performance of text extraction and quantify the success rate.

## Objective

- **Extract text** from images using Tesseract OCR.
- **Evaluate** the performance of text extraction.
- **Quantify** the percentage of images where text extraction fails.

## Dataset

- **Dataset**: IIIT-5K Word Dataset (test set)
- **Image Types**: .png, .jpg, .jpeg

## Tools and Libraries

- **Python**: Programming language used for the implementation.
- **Tesseract OCR**: Optical Character Recognition engine for text extraction.
- **Pillow (PIL)**: Python Imaging Library for image processing.
- **pytesseract**: Python wrapper for Tesseract OCR.

## Setup

1. **Install Tesseract OCR**:
   - Follow the [Tesseract Installation Guide](https://github.com/tesseract-ocr/tesseract) to install Tesseract.

2. **Install Python Libraries**:
   ```bash
   pip install pytesseract Pillow
