# Face Recognition System 👤

A real-time face recognition system that identifies individuals with **95% accuracy**. Built using **Python**, **OpenCV**, **Dlib**, and **Haar Cascade** for face detection. This project demonstrates the core concepts of face detection, feature extraction, and recognition in a controlled environment.

---

## Features ✨
- **Real-Time Recognition**: Detects and recognizes faces in real-time using a webcam.
- **High Accuracy**: Achieves **95% accuracy** in identifying individuals.
- **Database Integration**: Uses **SQLite** to store and manage face data.
- **User-Friendly**: Simple and intuitive interface for easy interaction.

---

## Technologies Used 🛠️
- **Python**: Core programming language.
- **OpenCV**: For image processing and face detection.
- **Dlib**: For facial landmark detection and recognition.
- **Haar Cascade**: For face detection.
- **SQLite**: For database management.
- **K-Nearest Neighbors (KNN)**: For face recognition.

---

## How It Works 🚀
1. **Face Detection**: Utilizes Haar Cascade classifiers to detect faces in real-time video feeds.
2. **Feature Extraction**: Converts detected faces to grayscale and resizes them for processing.
3. **Face Recognition**: Applies the trained KNN classifier to identify individuals by comparing input faces with the dataset.
4. **Output Display**: Displays the recognized face along with the person's name in real-time.

---


Dataset Creation 📂
Data Collection: Images are captured using a Python script with OpenCV. Faces are detected and saved with a unique ID for each individual.

Challenges:

Capturing images under different lighting conditions.

Minimizing background noise to improve model accuracy.

Training the Model 🧠
Preprocessing: Convert images to grayscale and resize them.

Labeling: Assign unique labels to each individual.

Training: Use K-Nearest Neighbors (KNN) to train the classifier on the dataset.

Validation: Test the model to ensure accuracy.

## Installation and Setup 🛠️
1. Clone the repository:
   ```bash
   git clone https://github.com/bhaskarchowdary826/Face-Recognition-System.git

2. Install the require dependencies from requirements.txt

3. Run the model successfully.


Advantages ✅
Contactless Recognition: No physical contact required.

High Security: Facial features are difficult to replicate.

Scalability: Can handle large databases of faces.

Integration: Easily integrates with existing security systems.

Disadvantages ❌
Vulnerability to Spoofing: Can be tricked by photos, videos, or masks.

Lighting and Obstructions: Performance may vary under different lighting conditions or with facial obstructions.

Identical Twins: Cannot distinguish between identical twins.

Applications 🌍
Security and Surveillance: Enhance security systems with real-time face recognition.

Healthcare: Patient identification and access control.

Banking and Finance: Secure authentication for transactions.

Consumer Electronics: Unlock devices using facial recognition.

Smart Homes: Personalized experiences based on recognized users.

Future Improvements 🔮
Deep Learning Models: Improve accuracy using models like FaceNet.

Multiple Face Detection: Recognize multiple faces in a single frame.

User-Friendly GUI: Add a graphical interface for easier interaction.

Contributing 🤝
Contributions are welcome! Feel free to open an issue or submit a pull request.



Connect with Us 🌐
Bhaskar Goditi: GitHub | Email



