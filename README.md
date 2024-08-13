# Phishing Detection Web Application

## Overview

The Phishing Detection Web Application is a tool for identifying potentially malicious URLs using machine learning and VirusTotal integration. It features a web interface where users can submit URLs for analysis and receive feedback on whether the URL is likely to be a phishing attempt.

## Features

- **Machine Learning Model**: Classifies URLs as phishing or safe based on extracted features.
- **VirusTotal Integration**: Checks URLs against VirusTotal for additional threat analysis.
- **Web Interface**: User-friendly interface for inputting and analyzing URLs.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/username/Phising-Link-Detector-using-Flask-ML.git

    Navigate to the project directory:

    bash

cd Phising-Link-Detector-using-Flask-ML

Create and activate a virtual environment:

bash

python -m venv .venv
source .venv/bin/activate

Install the required packages:

bash

    pip install -r requirements.txt

Configuration

    Obtain an API key from VirusTotal and replace your_api_key_here in the app.py file.

Running the Application

    Start the Flask application:

    bash

    python app.py

    Open your web browser and go to http://127.0.0.1:5000.

Usage

    Enter a URL in the provided input field.
    Submit the URL for analysis.
    Review the result indicating if the URL is safe or potentially phishing.

License

This project is licensed under the MIT License - see the LICENSE file for details.
GitHub Repository

For more information, visit the Phising-Link-Detector-using-Flask-ML.


