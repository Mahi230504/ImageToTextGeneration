# Image-to-Text Extraction Using EasyOCR

This project demonstrates how to extract text from images using the EasyOCR library. The extracted text is displayed in the console, along with confidence scores, and the image is optionally displayed with bounding boxes around the detected text.

## Features
- Recognizes text in images using EasyOCR.
- Supports multiple languages.
- Displays detected text and confidence scores.
- Visualizes text recognition with bounding boxes on the image.


## Installation
1. Clone the repository or download the script:
   ```bash
   git clone https://github.com/Mahi230504/ImageToTextGeneration.git
   cd image-to-text-easyocr


image_path = "image_with_text.jpg"  # Replace with your image path

python extract_text_easyocr.py

reader = easyocr.Reader(['en', 'es'])  # Example: English and Spanish
