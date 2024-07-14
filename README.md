# AI Clinic

AI Clinic is a project for the 2040 Human Machine Integration hackathon. It serves as a hub for anyone who wants to use AI in healthcare, offering health monitoring, predictive diagnostics, and more.

## Features

- Health Monitoring Sensors: Continuous monitoring of vital signs such as glucose levels, heart rate, blood pressure, and more.
- AI Diagnostic Model: Predictive analytics based on sensor data and historical health records.
- AI Therapy Bots: AI-driven chatbots providing mental health support, including therapy sessions and mindfulness exercises.
- Personalized Health Coaching: AI nutritionist and fitness monitoring for personalized health and fitness plans.
- Privacy and Data Vault: Secure storage of health data using Proton Drive.
- Premium Subscription Models: Access advanced AI diagnostics and personalized health plans.

## Requirements

- Python 3.7+
- Flask
- Bootstrap (CDN)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/ManikSinghSarmaal/Ai-Clinic
cd ai-clinic
```
Create a virtual environment and activate it:
```
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
Install the required dependencies:
```
pip install flask
```
## Running the Application
1. Set the FLASK_APP environment variable:
```
export FLASK_APP=app.py  # On Windows use `set FLASK_APP=app.py`
```
2. Run the Flask application:
```
flask run
```
3. Open your browser and navigate to 'http://127.0.0.1:5000' to view the application.

## Project Structure
```
ai_clinic/
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── images/
│   │   └── logo.png
│   └── js/
│       └── script.js
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── features.html
│   ├── contact.html
│   └── about.html
│
└── app.py
```
