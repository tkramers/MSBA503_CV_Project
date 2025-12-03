# MSBA 503 – Computer Vision Take-Home Assignment

This project compares the performance of two deep learning object detection models — **YOLOv8n** and **Faster R-CNN** — using a set of 10 images. Each model was evaluated on three key metrics:

- **Number of objects detected**
- **Average confidence score**
- **Inference time**

All images were collected manually, and the outputs from both models were stored in a pandas DataFrame and summarized into a comparison table.

---

## Models Used

### **YOLOv8n (Ultralytics)**
- Fast, single-stage object detector optimized for real-time performance  
- Lightweight and efficient  

### **Faster R-CNN (torchvision)**
- Two-stage detector that is slower but often more detailed  
- Produces high-quality bounding boxes at the cost of longer inference times  

---

## Additional Feature Extraction (Part A-ii)

In addition to object detection, I extracted the **average RGB color values** from each image using basic image processing. This provides a simple, non-deep-learning way to describe scene characteristics.

---

## Files Included

- **`msba503_takehome.ipynb`** — Main notebook containing the full workflow, model execution, and outputs  

---

## How to Run the Notebook

1. Upload your own images into a folder  
2. Update the `image_dir` path in the notebook to point to your image folder  
3. Run the notebook from top to bottom  

---

