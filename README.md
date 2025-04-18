# ♻️ AI-Powered Plastic Waste Detection from Aerial Images

## 🌍 Project Overview
Computer vision system that detects and classifies plastic waste in drone/satellite imagery to assist local authorities or NGOs in targeting clean-up operations.

## ✨ Features
- Real-time detection (15+ FPS)
- Multi-class classification (bottles, bags, etc.)
- GIS integration for location mapping
- Edge device compatible

## 🛠️ Tech Stack
- **Framework**: YOLOv5/PyTorch
- **Annotation**: LabelImg/CVAT
- **Processing**: OpenCV
- **Deployment**: Flask/Docker

## ⚙️ Installation
```bash
# Clone repo
git clone https://github.com/yourusername/your-repo.git
cd your-repo

# Install dependencies
pip install -r requirements.txt  # For YOLOv5