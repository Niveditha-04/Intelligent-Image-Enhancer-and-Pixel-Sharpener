<div align="center">

# Intelligent Image Enhancer & Pixel Sharpener

**Desktop GUI tool for image enhancement, sharpening, grayscale conversion, and flexible custom cropping — with live before/after preview and local file export in under 100ms.**

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![OpenCV](https://img.shields.io/badge/OpenCV-Image%20Processing-5C3EE8?style=flat&logo=opencv&logoColor=white)](https://opencv.org)
[![Tkinter](https://img.shields.io/badge/Tkinter-GUI-FF6B6B?style=flat)](https://docs.python.org/3/library/tkinter.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat)](LICENSE)

</div>

---

## Features

| Operation | Description |
|-----------|-------------|
| **Enhance** | CLAHE · unsharp mask · kernel sharpening — 3 techniques to sharpen and restore detail |
| **Grayscale** | Convert to black & white with a single click |
| **Crop** | Flexible draggable boundaries — not locked to standard ratios; enter exact pixel dimensions |
| **Before / After Preview** | Live side-by-side comparison before saving |
| **Export** | Save processed image directly to your desktop |

---

## Results

| Metric | Value |
|--------|-------|
| Processing speed | **< 100ms** per image (desktop GUI) |
| Enhancement techniques | **3** — CLAHE · unsharp mask · kernel sharpening |
| Core operations | **4** — select · enhance/filter · crop · save |
| Live preview | Before / after comparison |

---

## Demo

### 1 — Select an image from your local desktop

![Select Image](Video/select.gif)

### 2 — Crop with flexible boundaries and custom dimensions

![Crop Image](Video/crop.gif)

### 3 — Apply enhancement or convert to black & white

![Filter Image](Video/filter.gif)

### 4 — Save the final image to your desktop

![Save Image](Video/save.gif)

---

## Sample Outputs

| Original | Enhanced | Black & White |
|----------|----------|---------------|
| ![Sample 1](images/sample.jpeg) | — | ![Sample 1 B&W](images/sample-Black_white.jpeg) |
| ![Sample 2](images/sample2.jpeg) | ![Sample 2 Enhanced](images/sample2-Enhanced.jpeg) | ![Sample 2 B&W](images/sample2-Black_white.jpeg) |

---

## Tech Stack

| Layer | Tool |
|-------|------|
| GUI | Tkinter |
| Image processing | OpenCV · PIL / Pillow |
| Numerical ops | NumPy |
| Rendering | Pygame · Matplotlib |
| Language | Python |

---

## Setup & Run

**Prerequisites:** Python 3.x

```bash
pip install numpy opencv-python pygame pillow matplotlib

# Run the application
python image_enhancer.py
The GUI will open — browse your local files, apply enhancements, crop, and save
