# 🖼️ Image Cartoonizer

This project was developed as part of a **Computer Vision course assignment** at my university. It applies a series of image processing techniques to transform real-world photos into cartoon-style illustrations.

The cartoonization process focuses on flattening color regions and enhancing edges to mimic the stylized look of comic books or animated art.

## 🎯 Objective

The aim is to make real images appear as if they were hand-drawn cartoons. This involves:
- Flattening color regions
- Enhancing strong edges
- Producing a clean, stylized effect similar to what you'd find in comic books or animated films

## 🧠 Techniques Used

The cartoon effect is achieved by combining several filters:

- **Median Filter** – Reduces noise and preserves edges  
- **Laplacian Filter** – Detects edges with high accuracy  
- **Bilateral Filter** – Smooths colors while maintaining sharp edges  

By blending these steps, the program enhances edge structures while simplifying color regions for a stylized cartoon effect.

## 🛠️ Technologies

- Python
- OpenCV
- NumPy
- Matplotlib (optional, for displaying results)

## 🚀 How to Run

1. Install The Image_Cartoonizer.ipynb notebook.
2. Open the notebook using Google Colab.
3. Select an image from your device and run the code.
