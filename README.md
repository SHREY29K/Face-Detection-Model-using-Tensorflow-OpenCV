# 🚧 Project Status: Under Development 🚧

> This project is a work in progress. Core functionalities like image collection and preprocessing are implemented. Training loop, evaluation, and advanced extensions are under active development. Contributions and ideas are welcome!

---

# 👁️ Face Detection Model — *Under Development*

This repository contains a custom-built **Face Detection System** leveraging the power of **TensorFlow**, **OpenCV**, and **Albumentations**. The goal is to develop a lightweight, real-time, and accurate facial detection pipeline that can be further enhanced into advanced recognition tasks such as **iris detection** and **emotion-based facial sentiment recognition**.

---

## 🚀 Project Features

- 📸 Real-time face image capture from webcam using OpenCV
- 🏷️ Labeling powered by `labelme`
- 🧠 Face detection model built with **TensorFlow/Keras**
- ⚙️ Image augmentation using **Albumentations** for robust model training
- 🗃️ Organized image datasets for training/validation
- 🔍 Modular and expandable code structure

---

## 🧰 Technologies Used

| Component     | Description                               |
|---------------|-------------------------------------------|
| `TensorFlow`  | Model architecture & training             |
| `OpenCV`      | Real-time image processing and capture    |
| `Albumentations` | Fast & flexible data augmentation     |
| `Labelme`     | Manual annotation and labeling tool       |

---

## 🧪 Current Development

The project is actively in progress. So far, it includes:
- Automated webcam image capture
- Basic dataset collection and preprocessing
- Placeholder for training loop and evaluation (under construction)
- GPU memory growth settings to ensure optimal training performance

---

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/Face-Detection-TF
cd Face-Detection-TF

# Install requirements
pip install -r requirements.txt

# Or manually install essentials
pip install opencv-python tensorflow albumentations labelme matplotlib
```

---

## 🧑‍💻 Usage

```bash
# Launch the webcam and begin image collection
python collect_images.py

# Annotate your images
labelme data/images/

# Train your model (coming soon)
python train_model.py
```

---

## 📈 Future Enhancements

We aim to extend this project beyond simple face detection:

- 🔵 **Iris Detection:** Precision tracking of eye movements and iris localization
- 😊 **Facial Sentiment Recognition:** Emotion-based classifier (happy, sad, angry, etc.)
- 🧠 Integration with pre-trained models and transfer learning
- 🌐 Lightweight deployment for edge devices (Raspberry Pi, Jetson Nano)

---

## 🤝 Contributing

Pull requests are welcome! Feel free to fork the repo and propose features or report issues.

---

## 🧑‍🎓 Developed By

**Shrey Kothari**  
*AI/ML Enthusiast | Full-stack Developer | Hackathon Winner*  
[LinkedIn](https://www.linkedin.com/in/shrey-kothari) • [GitHub](https://github.com/SHREY29K)
