# Fraud Detection using OCR

## Approach
This project uses OCR (Tesseract) to extract text from ID images and detect suspicious documents based on:
- Blur detection
- Text extraction failure

## Tools Used
- Python
- OpenCV
- Pytesseract
- NumPy

## Architecture
Input Image → Preprocessing → OCR → Quality Checks → Verdict

## How to Run
1. Install dependencies:
   pip install -r requirements.txt

2. Install Tesseract OCR and set path

3. Run the notebook

## Sample Inputs & Outputs
- images/genuine_id.jpg → Genuine
- images/suspicious_id.jpg → Suspicious
