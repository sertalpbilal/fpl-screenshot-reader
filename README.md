# FPL Screenshot Reader

*Under development*

The purpose of this package is to convert FPL screenshots into text for further team analysis.

## Ideas

- Using a free tier of ocr.space: http://ocr.space/
- Using Python with CV2 (filter by background) and PyTesseract
- Using tessaract.js: https://tesseract.projectnaptha.com/

## Implementations

### Python

**For Windows:**

- Download and install Tesseract https://github.com/UB-Mannheim/tesseract/wiki
- Add folder to environment path
- Add a new environment variable `TESSDATA_PREFIX` and set its value to tesseract directory e.g. `C:\Program Files\Tesseract-OCR`

