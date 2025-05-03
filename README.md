# Indian Sign Language Recognition System using OpenCV

This project is a real-time Indian Sign Language (ISL) recognition system that uses OpenCV and a trained Convolutional Neural Network (CNN) model to detect and classify hand gestures. It aims to enhance communication accessibility for individuals with hearing impairments.

## 👨‍💻 Team Members
- Md Ashique Ali
- Gumesh
- Nafees

## 🔧 Technologies Used
- Python
- OpenCV
- NumPy
- TensorFlow / Keras
- Haar Cascade Classifier
- CNN Model for Gesture Recognition

## 📁 Project Structure
project/
│
├── dataset/ # Dataset for training (images of gestures)
├── trained_model/ # Pre-trained CNN model
├── haarcascade/ # Haar cascade XML for hand detection
├── utils/ # Utility functions
├── main.py # Main application file to run the detection
├── requirements.txt # Python dependencies
└── README.md # Project documentation

bash
Copy
Edit

## 🚀 How to Run the Project

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/isl-recognition-opencv.git
cd isl-recognition-opencv
Step 2: Set Up a Virtual Environment (Optional but Recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
Step 3: Install Required Packages
bash
Copy
Edit
pip install -r requirements.txt
Step 4: Run the Application
bash
Copy
Edit
python main.py
Step 5: Usage
Ensure your webcam is working.

Show a sign from the trained dataset in front of the webcam.

The system will detect the hand and display the recognized sign on the screen.

Training the Model (Optional)
If you want to retrain the model:

bash
Copy
Edit
python train_model.py
Make sure you have enough labeled gesture data in the dataset/ folder.

📌 Notes
Ensure all Haar cascade and model files are in the correct directory.

The application requires a decent lighting condition for accurate hand detection.

📄 License
This project is for academic purposes only. Feel free to modify it as per your need.
