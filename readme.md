# 🚗 Automatic License Plate Detection & Recognition

This project automatically detects and recognizes vehicle license plates from images and videos using **YOLO-based contour detection** and **EasyOCR** for Optical Character Recognition. It supports real-time and batch processing, and runs seamlessly in environments like **Google Colab** or your local machine.

---

## 📸 Key Features

- 📷 Image and video input support  
- 🔍 Accurate license plate detection using YOLO-style contour detection  
- 🧠 Text recognition via EasyOCR  
- 🎞️ Real-time video processing with frame skipping for speed  
- 📝 Output includes overlaid recognized license numbers  

---

## 🛠️ Tech Stack

- Python 3.x  
- OpenCV  
- EasyOCR  
- NumPy  
- imutils  
- Google Colab (optional)

---

## 🧑‍💻 Getting Started

### ✅ Run on Google Colab (Recommended)

1. Open the project notebook in **Google Colab**.  
2. Upload an image or video when prompted.  
3. View and download the processed output with bounding boxes and recognized text.

### 💻 Run Locally

Ensure you have Python 3.x installed. Then install the dependencies and run the script:

```bash
pip install opencv-python easyocr imutils numpy
python main.py
```
For GPU acceleration (optional but recommended for faster OCR):
```
pip install torch torchvision torchaudio
```

### 🖼️ Sample Output

The processed images/videos will show:

- License plates with bounding boxes
- Recognized license text overlaid on the frame

