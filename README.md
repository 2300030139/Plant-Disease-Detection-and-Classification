🌿 Plant Disease Detection and Classification

Plant Disease Detection and Classification is a modern AI-based application designed to identify plant diseases from leaf images. This system helps farmers, researchers, and agricultural professionals detect diseases early and take preventive measures.

It uses machine learning / deep learning techniques to analyze plant leaf images and classify them into healthy or diseased categories with high accuracy.

## 🚀 Features

- 🌱 Disease Detection: Identifies plant diseases from leaf images using trained models
- 🧠 Deep Learning Model: Uses CNN / ML algorithms for accurate classification
- 📊 Multi-Class Classification: Supports multiple plant diseases
- 🖼️ Image Processing: Preprocessing of leaf images for better prediction
- 💻 User Interface: Simple interface for uploading images and viewing results
- ⚡ Fast Prediction: Quick results with optimized model

## 🛠️ Technology Stack

- Frontend: HTML, CSS, JavaScript (if UI exists)
- Backend: Python
- Libraries/Frameworks:
  - TensorFlow / Keras / PyTorch
  - NumPy, Pandas
  - OpenCV / PIL
- Model Type: Convolutional Neural Network (CNN)
  
## 📁 Project Structure

plant-disease-detector/
│
├── Crop Dataset/              # Dataset containing plant leaf images
│
├── backend/                  # Backend logic (Flask / model integration)
│   ├── model/                # Trained ML/DL model files
│   ├── utils/                # Helper functions (prediction, preprocessing)
│   └── app.py                # Flask application
│
├── frontend/                 # User interface
│   ├── templates/            # HTML files
│   ├── static/               # CSS, JS, images
│   └── index.html            # Main UI page
│
├── main.py                   # Runs the application
├── train.py                  # Model training script
├── requirements.txt          # Dependencies
└── README.md                 # Project documentation

## ⚙️ How It Works

1. User uploads a plant leaf image  
2. Image is preprocessed (resized, normalized)  
3. Model analyzes the image  
4. System predicts:
   - Disease name OR
   - Healthy plant  
5. Result is displayed to the user  

▶️ Getting Started
1. Clone the Repository
git clone https://github.com/2300030139/Plant-Disease-Detection-and-Classification.git
cd Plant-Disease-Detection-and-Classification

2. Install Dependencies
pip install -r requirements.txt

3. Run the Project
python main.py

5. Train the Model (Optional)
python train.py


📊 Dataset
Contains images of healthy and diseased plant leaves
Organized into different classes (disease categories)
Used for training and testing the model

🎯 Applications
Smart Farming
Crop Monitoring
Agricultural Research
Early Disease Detection

🔮 Future Enhancements
Mobile App Integration 📱
Real-time camera detection 🎥
More disease categories 🌾
Cloud deployment ☁️

📄 License
This project is licensed under the MIT License.

👩‍💻 Author
Navya
GitHub: https://github.com/2300030139
