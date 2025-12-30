# Harmful_Project_Detection
**Harmful Object Detection System for Visually Impaired**
-- **Project Overview**

The Harmful Object Detection System is a Python and Django-based application designed to help visually impaired individuals identify potentially harmful objects in real-time using computer vision techniques. The system integrates object detection logic with a web interface to make it user-friendly and accessible.

This project demonstrates a practical implementation of AI-assisted object detection aimed at improving safety and accessibility. It handles data processing using libraries such as NumPy and Pandas, and the backend is built using the Django framework for scalability and real-world usage.

-- **Key Features**

-- Real-time harmful object detection logic implemented in Python
-- Django web framework for backend handling and UI rendering
-- Uses data libraries like NumPy and Pandas for efficient processing
-- Designed to assist visually impaired users by detecting objects that could be dangerous
-- Modular and extendable for future improvement with machine learning models

-- **Technologies Used**

Category	Tools
Backend	Python, Django
Object Detection	OpenCV / Custom detection logic
Data Handling	NumPy, Pandas
Web Interface	Django Templates (HTML)
Version Control	Git & GitHub

-- **Project Structure**

Harmful_Project_Detection/
├── app/  
├── templates/  
│   └── index.html  
├── models.py  
├── views.py  
├── settings.py  
├── urls.py  
├── requirements.txt  
├── manage.py  
└── README.md


-- app/ – Core Django application files
-- templates/ – HTML UI templates
-- models.py / views.py – Backend logic and data models
-- urls.py – Routes for application
-- requirements.txt – Python dependencies

-- **Requirements**

Make sure you have:

Python 3.x

Django

NumPy

Pandas

OpenCV (if using image detection logic)

Install dependencies:

pip install -r requirements.txt

** Steps**

-- Clone the repository

-- git clone https://github.com/Sidhardha-Saradhi/Harmful_Project_Detection.git


-- Navigate to project folder

cd Harmful_Project_Detection

Run the Django server

python manage.py runserver


## Demo / Project Execution

This project is currently demonstrated via source code and sample outputs.

### How to Run
1. Clone the repository
2. Install dependencies
3. Run the backend detection function with an image input

### Sample Output
Input: Image containing a harmful object  
Output: "Harmful object detected!"

### Note
Due to hardware and deployment limitations, this project is presented as a code-based demo.



Open the browser and go to:

http://127.0.0.1:8000
