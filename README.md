# 📝 Text Detection with OpenCV & Tesseract OCR

This Python project demonstrates **text detection and recognition** in **images**, **video files**, and **live webcam feed** using **OpenCV** and **Tesseract OCR**.

---

## 🔹 Features

- Detects **characters and text** in images and video frames  
- Draws **bounding boxes** around detected characters  
- Works on **images**, **video files**, and **live webcam feed**  
- Displays **detected text on the frame**  
- Press `'q'` to **exit the live feed**  

---

## 📂 Project Structure

- `images/` – Contains sample images and video for testing  
- `text_detection.py` – Main Python script for OCR detection  
- **Tesseract OCR** must be installed on your system  
  - Windows default path: `C:\Program Files\Tesseract-OCR\tesseract.exe`  

---

## ⚡ Installation

**Python dependencies:**
```bash
pip install opencv-python pytesseract matplotlib
