# AgroVision 🌾

An intelligent AI-powered plant disease detection web application developed to help farmers and agricultural users identify plant diseases efficiently and obtain treatment recommendations through deep learning techniques.

## Features ✨

- Disease prediction using CNN-based deep learning models
- AI-powered plant disease detection from leaf images
- Krishi Mitra chatbot for farming assistance
- Treatment and preventive recommendations
- Daily agricultural news bulletin and updates
- Disease gallery with plant information
- Multilingual support (English / Kannada)
- User-friendly and responsive interface
- Real-time prediction with confidence score
- Report generation and recommendation support

---

## Dataset 📊

This project utilizes the **New Plant Diseases Dataset** from Kaggle.

📥 **Dataset Link:**  
https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

### Dataset Information

- Dataset Name: New Plant Diseases Dataset
- Source: Kaggle / PlantVillage
- Size: Approximately 54,000+ plant leaf images
- Classes: Multiple plant species and disease categories
- Format: Image dataset
- Train/Test Split: 80/20
- Preprocessing: Resizing, normalization, and noise reduction

---

## Results 📈

- Disease Classification Accuracy: **96%**
- Precision: **95%**
- Recall: **96%**
- F1 Score: **95%**
- Average Prediction Time: **< 2 seconds**

---

## Tech Stack 🛠️

### Backend
- Python
- Flask
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas

### Frontend
- HTML5
- CSS3
- JavaScript

### Development Tools
- Visual Studio Code
- Jupyter Notebook
- Git/GitHub

---

## Project Structure 📁

```bash
AgroVision/
│
├── flask_app.py
├── start_servers.py
├── main.js
├── style.css
├── dataset-catalog.json
├── package.json
│
├── HTML Pages
│   ├── index.html
│   ├── predict.html
│   ├── chat.html
│   ├── news.html
│   ├── gallery.html
│   ├── about.html
│   └── contact.html
│
├── Images/
├── Model/
├── Dataset/
└── README.md
```

---

## Installation & Setup 🚀

### Clone Repository

```bash
git clone https://github.com/yourusername/AgroVision.git

cd AgroVision
```

### Install Python Dependencies

```bash
pip install flask tensorflow keras opencv-python numpy pandas matplotlib
```

### Run Flask Backend

```bash
python flask_app.py
```

### Start Application

```bash
python start_servers.py
```

---

## Usage 💡

1. Open the application homepage  
2. Navigate to Predict Disease page  
3. Upload a plant leaf image  
4. Click Analyze Disease  
5. View prediction results with confidence score  
6. Access chatbot recommendations  
7. Download prediction report if required  

---

## System Workflow 🔄

Leaf Image Upload  
↓  
Image Preprocessing  
↓  
Feature Extraction  
↓  
CNN Classification  
↓  
Disease Detection  
↓  
Prediction Result  
↓  
Treatment Recommendation  
↓  
Report Generation  

---

## Key Modules

### Image Upload Module
Allows users to upload plant leaf images for analysis.

### Preprocessing Module
Performs image resizing, normalization, and noise reduction.

### CNN Prediction Module
Analyzes image features and classifies plant diseases.

### Recommendation Module
Provides treatment suggestions and preventive measures.

### Krishi Mitra Chatbot
Offers AI-based agricultural guidance and support.

### News Bulletin Module
Displays latest agricultural updates and alerts.

---

## Future Enhancements 🎯

- Mobile application development
- Real-time camera detection
- IoT integration
- Weather-based recommendations
- Drone-based crop monitoring
- Enhanced multilingual support

---

## Contributing 🤝

Contributions and improvements are welcome.

---

## License 📄

This project is available under the MIT License.

---

## Developed By 👨‍💻

Disha M T  
Vivekananda College of Engineering and Technology  

---

AgroVision — AI Powered Smart Farming Solution 🌱
