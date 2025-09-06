# Real-Time Face Recognition System

### Project Overview
This project develops a robust and accurate face recognition system capable of identifying individuals in both static images and live video streams. It is an end-to-end solution that combines a deep learning-based face detector with a face recognition model to match faces against a known database. This project serves as a strong demonstration of proficiency in modern computer vision techniques and real-time application development.

### Dataset
The system uses a custom dataset of images of famous celebrities (e.g., actors, musicians, public figures) to create a database of known face encodings. This approach allows the model to be trained on a diverse and recognizable set of individuals. The project also includes functionality to detect faces in unseen images and videos.

### Methodology
1.  **Face Encoding:** The project first processes a pre-defined dataset of known faces. It uses the `face_recognition` library to detect the faces and generate a 128-dimensional face encoding (a numerical representation of the face) for each person. These encodings are stored in a database for fast lookup.
2.  **Real-Time Detection and Recognition:** For live video streams or static images, the system performs the following steps:
    - **Face Detection:** It detects all faces in the current frame or image.
    - **Face Encoding:** It generates a face encoding for each detected face.
    - **Comparison:** It compares each new face encoding with the known encodings in the database.
    - **Identification:** It identifies the person by finding the closest match and displays their name in the video feed.
3.  **Performance Optimization:** The project is optimized to run in real time by processing video frames efficiently, demonstrating a practical approach to building performant computer vision systems.

### Concluded Results
The face recognition system successfully identifies individuals with high accuracy and low latency, showcasing its effectiveness for applications like security, access control, and personalized user experiences. This project highlights strong skills in computer vision, deep learning fundamentals, and building practical, high-impact AI systems.

### Technologies Used
- Python
- `face_recognition`
- OpenCV
- NumPy
- Jupyter Notebook
