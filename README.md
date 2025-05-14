# Testing-OpenSource-Image-Inpainting-models
# Image Inpainting: LaMa & Stable Diffusion Testing

This repository contains a notebook that explores and compares two advanced deep learning models for image inpainting:

- **LaMa** (Large Mask Inpainting) by Samsung AI Lab  
- **Stable Diffusion Inpainting** using Hugging Face Diffusers or Automatic1111 API

## 🧪 Description

The notebook demonstrates:
- Mask generation or manual mask loading
- Inpainting using the **LaMa** model for structure-aware filling
- Inpainting using **Stable Diffusion** for semantic-aware and high-fidelity results
- Side-by-side visual comparison of input, mask, and restored images

## 📌 Highlights

- Works with custom or sample images and masks
- Demonstrates strengths and limitations of structure-aware vs text-guided inpainting
- Suitable for object removal, restoration, or creative editing

## 🔧 Requirements

- Python 3.8+
- `torch`, `opencv-python`, `matplotlib`
- For Stable Diffusion:
  - Hugging Face's `diffusers` or access to an A1111 WebUI endpoint

> Note: Pretrained weights or model paths for LaMa and Stable Diffusion must be configured before running the notebook.

## 📁 Contents

- `inpainting_testing.ipynb` — Core notebook comparing LaMa and Stable Diffusion
- `images/` — Input samples
- `masks/` — Binary masks for inpainting
- `outputs/` — Model outputs

## 🧑‍💻 Author

Developed by [Dipak Gupta (PythonicDG)](https://github.com/PythonicDG)

