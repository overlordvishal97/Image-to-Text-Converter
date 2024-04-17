# Image-to-Text-Converter
This Python script converts images containing text into editable Word documents using optical character recognition (OCR) technology.

# Purpose
The purpose of this script is to automate the process of extracting text from images and saving it in a readable format. It can be useful for tasks such as transcribing scanned documents, extracting text from images, or digitizing text from printed materials.

# Dependencies
Python 3.x
Python packages:
docx
Pillow (PIL)
pytesseract
warnings

# Installation
Install Python 3.x from Python.org.
Install required Python packages using pip:
pip install python-docx Pillow pytesseract

# Usage
Ensure that Tesseract OCR is installed on your system. You can download it from here.
Update the input_dir variable with the directory containing the image files you want to process.
Update the output_dir variable with the directory where you want to save the resulting Word documents.

# Run the script:
python image_to_text_converter.py

# Workflow
The script iterates through all image files (.png, .jpg, .jpeg) in the specified input directory.
It extracts text from each image using Tesseract OCR.
The extracted text is saved in a new Word document in the specified output directory.
The script then compares the extracted text with the text in the Word document to ensure accuracy.
If the text matches, the image file is removed from the input directory.

# Note
Make sure to have Tesseract OCR installed and configured properly on your system for accurate text extraction.
This script assumes that the input images contain legible text for optimal results.

# License
This project is licensed under the MIT License.
