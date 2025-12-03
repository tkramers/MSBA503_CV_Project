# MSBA 503 – Computer Vision Take-Home Assignment

This project compares two deep learning object detection models — YOLOv8n and Faster R-CNN — across a set of 10 images. I evaluated each model on three metrics:

Number of objects detected

Average confidence score

Inference time

I collected the images myself and ran both models on each image. The results were stored in a pandas DataFrame and aggregated into a summary table for comparison.

Models Used

YOLOv8n (Ultralytics) – a fast single-stage detector

Faster R-CNN (torchvision) – a slower but more detailed two-stage detector

Additional Feature Extraction

For Part A(ii), I also extracted the average RGB color values from each image using simple image processing. This provided basic scene characteristics separate from deep learning.

Files

msba503_takehome.ipynb – main notebook with code and outputs

Images are not uploaded to GitHub (per assignment instructions)

How to Run

Upload your own images into a folder

Update the image_dir path

Run the notebook from top to bottom
