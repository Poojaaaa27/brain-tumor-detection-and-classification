
# 🧠 Brain Tumor Detection and Classification

A deep learning-based web application that detects and classifies brain tumors from MRI scans using a Convolutional Neural Network (CNN). The trained model is integrated into a Flask web app with a simple user interface.

## 📌 Key Features
- Upload MRI images for brain tumor detection
- CNN-based model trained on MRI datasets
- Flask-powered web interface
- Display of prediction results with confidence
- Responsive frontend for smooth usage
- Preview of input MRI and detected output
## 📁 Directory Structure
```
.
│── .idea/
│── .venv/
│── models/
│ └── brain_tumour_detection_using_deep_learning (1).ipynb
│ └── model.h5
│── templates/
│ └── index.html
│── uploads/
│ └── Te-gl_0015.jpg
│ └── Te-meTr_0001.jpg
│ └── Te-noTr_0004.jpg
│ └── Te-pi_0107.jpg
│ └── Te-pi_0236.jpg
│ └── Te-piTr_0003.jpg
│── .gitignore
│── homepage.jpg
│── main.py
│── output.jpg
│── requirements.txt
│── tempCodeRunnerFile.py
```

## 🔧 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/Poojaaaa27/brain-tumor-detection-and-classification.git
cd brain-tumor-detection-and-classification
```

### 2. Install Dependencies
```bash
2. Create Virtual Environment & Install Dependencies
bash
Copy
Edit
python -m venv venv
venv\Scripts\activate       # Windows
source venv/bin/activate    # Mac/Linux

pip install -r requirements.txt
3. Run the Application
bash
Copy
Edit
python main.py
'''
4. Open in Browser
http://127.0.0.1:5000/
```
## 📊 Visual Outputs
<img src="homepage.jpg" alt="Home Page" width="500"/>
<img src="output.jpg" alt="MODEL Output" width="500"/>



---







HTML, CSS
