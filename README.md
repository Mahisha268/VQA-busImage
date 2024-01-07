# VQA-busImage

markdown
Copy code
# Object Detection and OCR with NVIDIA SSD

This project demonstrates object detection and optical character recognition (OCR) using the NVIDIA SSD model.

## Prerequisites

- Python 3
- PyTorch
- OpenCV
- Matplotlib
- Tesseract OCR

Install the required Python packages using:

```bash
pip install torch torchvision opencv-python matplotlib pytesseract
Make sure to have Tesseract OCR installed on your system. You can install it from https://github.com/tesseract-ocr/tesseract.


Download the pre-trained NVIDIA SSD model:
bash
Copy code
python download_model.py
Run the main script:
bash
Copy code
python main.py
The script will perform object detection on a sample image, display the results with bounding boxes, and extract text within specified bounding boxes using Tesseract OCR.

Configuration
You can customize the following parameters in the main.py script:

confidence_threshold: Set the confidence threshold for object detection.
License plate bounding box coordinates: Adjust the relative coordinates and dimensions for license plate bounding boxes.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
NVIDIA for providing the pre-trained SSD model.
The Tesseract OCR project for text extraction.
