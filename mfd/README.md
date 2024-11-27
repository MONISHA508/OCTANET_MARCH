# **Face Recognition Project**


## **Overview**
This project is a real-time **Face Recognition System** that captures, processes, and recognizes faces using webcam input. Facial images are stored in an Oracle database, processed to generate face encodings, and matched against live video feed for recognition.


## **Features**
- **Image Capture**: Capture and save images directly to an Oracle database via a web interface.
- **Face Encoding**: Process stored images to generate unique 128-dimensional face encodings.
- **Real-Time Recognition**: Recognize faces in real-time using a webcam feed.
- **Database Integration**: Store face images and metadata in an Oracle database.


## **Technologies Used**
- **Python**: Main programming language.
- **Libraries**:
  - `face_recognition`: Face detection and encoding.
  - `OpenCV`: Webcam feed processing and display.
  - `cx_Oracle`: Oracle database connectivity.
  - `pickle`: Storing face encodings for faster recognition.
- **Oracle Database**: For storing images and metadata.
- **Flask**: Web framework for the front-end interface.


