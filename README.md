
# 🛠️ **Real-Time Object Detection using YOLOv5 on Google Colab**

<p align="center">
  <img src="https://raw.githubusercontent.com/himanshu-chauhan-stack/RT_Object_Detection/refs/heads/main/content/sample_data/BANNER/frnt.png" width="600"/>
</p>

<p align="center">
  <a href="#"><img alt="Python" src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python"></a>
  <a href="#"><img alt="YOLOv5" src="https://img.shields.io/badge/YOLOv5-v7.0-orange?logo=github"></a>
  <a href="#"><img alt="License" src="https://img.shields.io/badge/License-MIT-green.svg"></a>
  <a href="#"><img alt="Colab" src="https://colab.research.google.com/assets/colab-badge.svg"></a>
</p>

> **Author:** Himanshu  
> **Framework:** YOLOv5 🚀 + Google Colab  
> **License:** MIT

---

## 📋 **Project Overview**

This project demonstrates **Real-Time Object Detection** using **YOLOv5** on Google Colab.  
It detects objects in images, videos, and webcam feeds with **high speed and accuracy**.

**✨ Features:**
- Detect objects in images & webcam
- Runs directly on **Google Colab** (No GPU required locally!)
- Powered by **PyTorch** + YOLOv5  
- Supports custom datasets (training)

---

## ▶️ **Live Demo (Run on Colab)**

| | |
|----|-------------------------------------------|
| <a href="https://colab.research.google.com/drive/11NlIcSTc7Fj-972QtefjgK0LDJ_6ODt6?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> | [Run YOLOv5 on Colab](https://colab.research.google.com/drive/11NlIcSTc7Fj-972QtefjgK0LDJ_6ODt6?usp=sharing) |

---

## ⚙️ **Tech Stack**

| Technology | Details |
|------------|---------|
| **Language** | Python 3.8+ |
| **Framework** | PyTorch |
| **Model** | YOLOv5s (pre-trained weights) |
| **Environment** | Google Colab |

---

## 🗂️ **Project Structure**

```
📁 Real-Time-Object-Detection
├── YOLOv5_Detection.ipynb   # Colab Notebook
├── runs/                    # Output detections
├── images/                  # Sample images
├── weights/                 # YOLOv5 weights
└── README.md
```

---

## 📝 **Algorithm Workflow**

```
Input Image → YOLOv5 Model → Object Detection (Bounding Boxes + Labels) → Output Image
```

---

## 📋 **Pseudocode**

```python
# Load YOLOv5 model
model = torch.hub.load('ultralytics/yolov5', 'yolov5s')

# Inference on an image
results = model('image.jpg')

# Display results
results.show()
```

---

## 📊 **Example Output**

<p align="center">
  <img src="https://raw.githubusercontent.com/himanshu-chauhan-stack/RT_Object_Detection/refs/heads/main/content/sample_data/BANNER/OP.png" width="1000"/>
</p>

---

## 🚀 **Installation (For Local)**

```bash
git clone https://github.com/ultralytics/yolov5
cd yolov5
pip install -r requirements.txt
```

---

## 💡 **Usage**

| Task | Command |
|------|---------|
| Detect objects in image | `python detect.py --source image.jpg` |
| Detect from webcam | `python detect.py --source 0` |

---

## 🤝 **Contributing**

Contributions and suggestions are welcome!  
Feel free to submit a pull request or open an issue.

---

## 📄 **License**

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.

---

## 🙌 **Acknowledgements**

- [Ultralytics YOLOv5](https://github.com/ultralytics/yolov5)
- Google Colab
- PyTorch
