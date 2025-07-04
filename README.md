# SafeID Masker 🛡️

A Flask-based web tool to detect and mask personal information like SSNs and names from scanned ID documents.

## 🚀 Features

- Upload scanned ID images
- Detect SSNs (e.g., 123-45-6789) and Names
- Mask them with black rectangles
- Simple Flask web interface
- Download final masked image

## 🧰 Tech Stack

- Python
- Flask
- Tesseract OCR
- OpenCV
- HTML/CSS

## 📦 Setup Instructions

1. Clone the repository:

   git clone https://github.com/your-username/SafeID-Masker.git
   cd SafeID-Masker

2. Create a virtual environment (optional but recommended):

   python -m venv venv  
   source venv/bin/activate  (or venv\Scripts\activate on Windows)

3. Install dependencies:

   pip install -r requirements.txt

4. Run the app:

   python app.py

Then visit http://127.0.0.1:5000 in your browser.

## 🗂 Project Structure


