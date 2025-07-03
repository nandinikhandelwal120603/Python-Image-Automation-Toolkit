

# 🖼️ Python Image Automation Toolkit

A collection of Python scripts for automating image-related tasks:

✅ Capture images from webcam
✅ Manipulate images (no external image libraries)
✅ Add image + text to PDF
✅ Extract text from images (OCR)
✅ Create GIFs from images

---

## 🚀 Scripts & Features

### 1️⃣ **Webcam Image Capture**

Capture images from your webcam and save them locally.

📌 **Run:**

```bash
python3 take_pictures_from_webcam.py --directory path/to/save --name MyImage
```

👉 If no `--directory` is provided, images are saved to the current directory.
👉 If no `--name` is provided, a default name is used.

---

### 2️⃣ **Image Manipulation Without External Libraries**

Manipulates images using only native Python (no OpenCV, Pillow, etc).

✅ Channel-wise addition
✅ Invert colors
✅ Mirror vertical / horizontal
✅ Blur (2 methods)
✅ Resize
✅ Lightness adjustment
✅ Brightness / contrast

📌 **Run:**

```bash
python3 image_manipulation.py
```

👉 Update the script with your image path and desired operations.

---

### 3️⃣ **Add Image + Text to PDF**

Generates a PDF file containing an image and custom text.

✅ Uses `reportlab`

📌 **Install dependency:**

```bash
pip install reportlab
```

📌 **Run:**

```bash
python3 script.py
```

👉 Replace `img.jpg` in the script with your image path.
👉 Put your text in `input.txt`.
👉 Outputs: `output.pdf`

---

### 4️⃣ **OCR (Extract Text from Image)**

Extracts text from images using Tesseract OCR.

✅ Uses `pytesseract`, `Pillow`

📌 **Install dependencies:**

```bash
pip install pytesseract pillow
```

📌 **Run:**

```bash
python3 ocr_script.py
```

👉 Update the script with:

* `path_to_tesseract` — path to your Tesseract executable
* `image_path` — path to your image

---

### 5️⃣ **Image to GIF Generator**

Converts multiple images into a GIF.

📌 **Run:**

```bash
python3 imageTogif.py
```

👉 Update the script or provide image list paths inside the script.

---

## ⚙️ Requirements

✅ **Python 3.x**

✅ **Libraries:**

```
pytesseract>=0.3.10
pillow>=10.0.0
reportlab>=4.0.4
```

*(Some scripts use only standard Python libraries — no extra installation required.)*

📌 **Install all dependencies:**

```bash
pip install -r requirements.txt
```

---

## 📂 Project Structure

```
python-image-automation-toolkit/
├── take_pictures_from_webcam.py
├── image_manipulation.py
├── script.py                  # PDF creator
├── ocr_script.py
├── imageTogif.py
├── input.txt                   # Input text for PDF
├── LICENSE
└── README.md
```

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🤝 Contributing

Feel free to contribute!
👉 Add more Python scripts for automation
👉 Improve existing scripts
👉 Submit PRs with enhancements


