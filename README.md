  Iris Tumor Detection using CNN

  Overview

The  Iris Tumor Detection using CNN  project leverages convolutional neural networks (CNNs) to detect tumors in iris images. This AI-powered web application offers a user-friendly interface for early diagnosis through advanced image analysis techniques.

  Features
-  Secure User Authentication:  Registration and login functionality.
-  Image Upload:  Allows users to upload iris images for analysis.
-  Tumor Detection Feedback:  Utilizes a CNN model for detection and displays results in real-time.
-  Responsive Design:  Ensures accessibility across devices.

---

  Why It's Important
- Early detection of iris tumors can improve health outcomes and enable timely treatment.
- Provides a scalable, accessible tool for initial screening.

---

  Tech Stack

-  Frontend:  HTML, CSS, Bootstrap
-  Backend:  Django
-  AI Frameworks:  TensorFlow / PyTorch
-  Database:  PostgreSQL
-  Deployment:  Cloud-hosted (e.g., Heroku/AWS)

---

  Architecture

-  Frontend:  Handles user interaction and uploads.
-  Backend:  Manages data and integrates the CNN model for predictions.
-  Model Integration:  Analyzes uploaded images for tumor presence.

---

  How to Use

1.  Register/Login:  Create an account or log in to access features.
2.  Upload an Image:  Submit an iris image through the dashboard.
3.  Receive Feedback:  View tumor detection results in real-time.

---

  Requirements

-  Software/Tools:  
  - Python (3.8 or higher)
  - Django
  - TensorFlow/PyTorch
  - OpenCV
-  Hardware: 
  - Minimum 4GB RAM
  - GPU for faster predictions (optional)

---

  Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/iris-tumor-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd iris-tumor-detection
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the server:
   ```bash
   python manage.py runserver
   ```
5. Access the application at `http://127.0.0.1:8000`.

---

  Testing

-  Unit Testing:  Verifies functionality of individual components.
-  Integration Testing:  Ensures seamless interaction between the frontend, backend, and model.
-  System Testing:  Tests the entire workflow end-to-end.

Run tests using Django’s test module:
```bash
python manage.py test
```

---

  Deployment

The application is designed for deployment on cloud platforms such as Heroku or AWS. Use the provided `Procfile` and `requirements.txt` for streamlined setup.

---

  Future Enhancements

-  Improved Detection Accuracy:  Train the model with more diverse datasets.
-  Multi-Language Support:  Extend accessibility to non-English speakers.
-  Mobile App:  Develop a mobile version for easier access.

---

  Contributors

- Govindu Prasanth Rohith 
- Team 3 Members

---

  Acknowledgements

- AI frameworks: TensorFlow, PyTorch
- Web hosting: Heroku/AWS
