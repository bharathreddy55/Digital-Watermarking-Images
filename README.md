# Digital-Watermarking-Images

Digital Watermarking System

A compact but powerful system that embeds invisible watermarks into images and later extracts/verifies them. Built for students, devs, and professionals who need a fast, reliable way to prove ownership of digital media.

## 🚀 Features

Invisible Watermark Embedding – Modifies pixel data without ruining image quality.

Watermark Extraction – Pulls out the hidden signal for verification.

Noise & Attack Resistance – Survives compression, resizing, and minor edits (depending on method).

Clean, Modular Codebase – Easy to extend with new watermarking algorithms.

## 🧠 Tech Stack

Python

NumPy, OpenCV

Jupyter Notebook for demos & experimentation

## 📂 Project Structure
Digital_Watermarking_System/
│── embed.py           # Embed watermark into image
│── extract.py         # Extract watermark
│── utils.py           # Helpers: image loading, conversion, etc.
│── samples/           # Test images & watermarks
│── Digital_Watermarking_Systems.ipynb  # Notebook demo

## 🔥 How It Works

Load the image

Convert to frequency domain (DCT/DFT based)

Inject watermark bits into selected coefficients

Save the watermarked image

Run extraction to validate ownership

## ▶️ Usage
Embed
python embed.py --image input.jpg --watermark wm.png --out output.jpg

Extract
python extract.py --image output.jpg --out extracted.png

## 📌 Status

Core watermarking pipeline works. Future upgrades: deep-learning watermarking, stronger robustness, and mobile version.

📜 License

Bharath.
