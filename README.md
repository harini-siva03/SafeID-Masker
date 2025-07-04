# 🔐 SafeID Masker – Personal Information Masking Tool

A web-based application developed for a hackathon challenge that detects and masks sensitive personal information from scanned ID documents, including Social Security Numbers (SSNs) and names. The tool is built using Flask, OCR, and image processing libraries to ensure data privacy in document handling.

## 🚀 Problem Statement

In an era where privacy and security are paramount, protecting sensitive personal information is a critical need. This hackathon project addresses that challenge by creating a tool that:

- Accepts digital images of scanned ID documents
- Detects sensitive information such as:
  - Social Security Numbers (SSNs)
  - Names
- Applies masking (black rectangles) to hide this information
- Provides a downloadable or displayable masked image to the user

## 🌐 Features

- 📤 Upload scanned ID images through a web interface
- 🔍 Extract text from images using Optical Character Recognition (Tesseract OCR)
- 🧠 Identify sensitive information using Regex and optional Named Entity Recognition (NER)
- 🖤 Mask detected regions using OpenCV with black rectangles
- 📥 Download or preview the masked image

## 🛠 Tech Stack

| Component         | Technology                     |
|------------------|---------------------------------|
| Backend          | Python, Flask                   |
| OCR              | Tesseract OCR                   |
| Image Processing | OpenCV, Pillow                  |
| Text Detection   | Regex, SpaCy (optional for NER) |
| Frontend         | HTML, CSS                       |
| Deployment       | Localhost or Render/Heroku      |





