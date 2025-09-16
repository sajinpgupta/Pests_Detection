# 🪰 Pests Detection – Fly Notebook

This repository contains a Jupyter notebook (`Fly.ipynb`) for detecting flies on yellow sticky traps using **YOLOv8**, **CLIP**, and **OpenCV**.  
The workflow demonstrates how computer vision can help automate pest monitoring in agriculture.

---

## 🚀 Features
- Preprocessing trap images (OpenCV, PIL).
- Object detection with **YOLOv8** (`ultralytics`).
- Classification using **CLIP**.
- Visualization of detections with bounding boxes.

---

## 📂 Project Structure
Pests_Detection/
│── Fly.ipynb # Main notebook
│── Images/ # Place your input trap images here
│── requirements.txt # Dependencies

---

## 🔧 Installation

Clone the repository:
```bash
git clone https://github.com/sajinpgupta/Pests_Detection.git
cd Pests_Detection

Install dependencies:
pip install -r requirements.txt

▶️ Usage

Place your trap images in the Images/ folder.

Open the notebook:
jupyter notebook Fly.ipynb

Update image_path inside the notebook to point to your images.

Run all cells.

YOLOv8 will detect possible flies.

CLIP will help refine classification.

Results will be visualized with bounding boxes.
📊 Example Workflow

Load an image from the Images/ folder.

Apply preprocessing (OpenCV + PIL).

Run YOLOv8n (lightweight model) to detect flies.

Use CLIP to classify/refine detections.

Visualize results with bounding boxes.

⚡ Notes

Swap yolov8n.pt with yolov8s.pt or yolov8m.pt for higher accuracy.

Keep image sizes small if running on a low-resource laptop.

For best performance, run on a machine with GPU (CUDA).
📜 License

This project is for educational and research purposes. Please cite if you use it.
