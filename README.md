
# 🍜 Vietnamese Food and Ingredient Detection with YOLOv8 and AndroidApp

## 📜 Overview
This project aims to build an Android application capable of detecting Vietnamese food and its ingredients using a YOLOv8 model. The YOLOv8 model was trained and optimized for TensorFlow Lite to enable real-time detection on mobile devices. The application demonstrates the integration of machine learning with mobile app development, providing a practical solution for food recognition.

---

## 🚀 Features
- **Real-time Detection**: Utilizes YOLOv8 for accurate food and ingredient detection.
- **TensorFlow Lite Integration**: Optimized for mobile devices with lightweight TFLite models.
- **Modern UI**: Built using Jetpack Compose for a clean and interactive user experience.
- **Custom Dataset**: Trained on a custom dataset specific to Vietnamese food and ingredients.

---

## 🛠️ Tech Stack
- **Model**: YOLOv8, TensorFlow Lite.
- **Mobile App**: Android Studio, Kotlin, Jetpack Compose.
- **Tools**: Python, OpenCV, Google Colab for model training and conversion.

---

## 📂 Folder Structure
```
Food Detection/
│
├── android_app/               # Android application source code
│   ├── app/                   # App-level configurations and source code
│   ├── manifests/             # Android manifest files
│   ├── assets/                # TensorFlow Lite model and label files
│   └── res/                   # App resources (images, layouts, etc.)
│
├── yolo_models/               # YOLOv8 model and converted TFLite files
│   ├── food_detection_best.pt # Trained YOLOv8 model
│   ├── food_detection_best.tflite # TensorFlow Lite model
│   └── metadata.yaml          # Model metadata
│
├── dataset.v2i.yolov8/        # Dataset used for training the model
│
├── Result images/             # Detection result examples
│
├── Train_YOLOv8_model.ipynb   # Training script for YOLOv8
├── Convert_YOLOv8_to_TensorFlow_Lite.ipynb # Conversion script
└── README.md                  # Documentation file
```

---

## 🏁 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/TuyenTrungLe/Vietnamese-Food-Detection-with-YOLOv8-and-AndroidApp.git
cd Vietnamese-Food-Detection-with-YOLOv8-and-AndroidApp
```

### 2. Prerequisites
- **Android Studio**: Install the latest version.
- **Python 3.9+**: For training and converting models.
- **Git**: For cloning and managing the repository.

### 3. Model Training
If you want to retrain the model:
1. Open `Train_YOLOv8_model.ipynb` in Google Colab or Jupyter Notebook.
2. Train the model using the provided dataset.
3. Export the YOLOv8 model to TensorFlow Lite using `Convert_YOLOv8_to_TensorFlow_Lite.ipynb`.

### 4. Running the Android App
1. Open the `android_app` folder in Android Studio.
2. Ensure the TensorFlow Lite model (`.tflite`) is present in the `assets` folder.
3. Build and run the app on an Android device or emulator.

---

## 📸 Example Results
### Sample Detection
Here are some examples of the detection capabilities:

<table>
  <tr>
    <td><img src="https://github.com/TuyenTrungLe/Vietnamese-Food-Detection-with-YOLOv8-and-AndroidApp/blob/main/Result%20images/com_suon.jpg" alt="Sample 1" width="350"/></td>
    <td><img src="https://github.com/TuyenTrungLe/Vietnamese-Food-Detection-with-YOLOv8-and-AndroidApp/blob/main/Result%20images/bun_dau.jpg" alt="Sample 2" width="350"/></td>
    <td><img src="https://github.com/TuyenTrungLe/Vietnamese-Food-Detection-with-YOLOv8-and-AndroidApp/blob/main/Result%20images/banh_hoi_heo_quay.jpg" alt="Sample 3" width="350"/></td>
  </tr>
</table>

---

## 📧 Contact
- **Author:** Le Tuyen  
- **Email:** trungtuyenlevn@gmail.com  
- **GitHub:** [TuyenTrungLe](https://github.com/TuyenTrungLe)

---

## 🤝 Contributing
Contributions are welcome! If you'd like to improve the project, feel free to fork the repository and submit a pull request.

---

## 📜 License
This project is licensed under the MIT License. See the `LICENSE` file for details.
