# GCIT Card Text Extraction

This project focuses on **extracting text from student ID cards** using Optical Character Recognition (OCR) techniques. It is designed to automate the process of retrieving student details such as name, ID number, and department from scanned or photographed GCIT ID cards.

---

## 📌 Project Description

The system uses OCR to read textual data from image files of student cards. This tool can be useful for institutions or automated systems that need to digitize and process printed information for student registration, verification, or data entry tasks.

---

## ⚙️ Features

- Image preprocessing (grayscale, thresholding, etc.)  
- Text extraction using Tesseract OCR  
- Parsing and organizing extracted data  
- Support for multiple card image formats  
- Simple script-based implementation for batch processing

---

## 🛠️ Tech Stack

- Python  
- OpenCV  
- Pytesseract (OCR)  
- NumPy  
- PIL (Python Imaging Library)

---

## 🎯 Learning Outcomes

- Applied **OCR techniques** to extract structured text from unstructured image data  
- Learned **image preprocessing** for better OCR accuracy  
- Improved understanding of **text parsing and cleaning**  
- Gained experience working with **computer vision libraries** like OpenCV

---

## 🚀 How to Use

```bash
# Clone the repository
git clone https://github.com/PemaYangchenn/GCIT_card_text_extraction.git

# Navigate to the directory
cd GCIT_card_text_extraction

# Install required libraries
pip install -r requirements.txt

# Run the script
python extract_text.py
