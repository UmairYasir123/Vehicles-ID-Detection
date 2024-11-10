# Car Number Plate Detection

This project implements a real-time car number plate detection system using **YOLO** (You Only Look Once) for object detection and **EasyOCR** for text recognition. The system is designed to process video footage, detect car number plates, and extract text from them. It also logs the detected plates along with timestamps into a **MySQL** database for tracking and analysis.

## Features
- **Real-Time Detection**: Processes video frames in real-time to detect car number plates.
- **OCR Integration**: Uses EasyOCR to extract text from detected number plates.
- **Database Logging**: Logs detected number plates with timestamps into a MySQL database for tracking and analysis.
- **Optimized for Varied Conditions**: The system is designed to work under different lighting conditions, improving the reliability of plate detection.

## Technologies Used
- **Python**: The main programming language used for implementation.
- **OpenCV**: For video frame processing and object detection.
- **YOLO (You Only Look Once)**: A powerful real-time object detection model used to detect car number plates.
- **EasyOCR**: An OCR library used to extract text from the detected number plates.
- **MySQL**: A relational database used to store detected number plates and timestamps for tracking and analysis.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourrepository.git
