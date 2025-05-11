# 🚗 Automatic Number Plate License Detection

This is a web application built using **Streamlit**, **OpenCV**, and **EasyOCR** to automatically detect and recognize vehicle license plate numbers from uploaded images.

## 🌟 Features

- Upload images in various formats (JPG, PNG, BMP, WEBP).
- Automatic license plate detection using image processing.
- Optical Character Recognition (OCR) with EasyOCR.
- Display the detected number plate text along with bounding boxes.
- Simple, interactive UI powered by Streamlit.

## 📸 Demo

![Demo](demo_screenshot.png)

> Upload an image of a vehicle, click **Detect License Plate**, and see the magic!

## 📦 Dependencies

Install the required Python packages:

```bash
pip install streamlit opencv-python-headless pillow easyocr imutils numpy
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
```

To run this code :
```
streamlit run app.py
```
