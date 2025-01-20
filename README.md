# Phishing-Email-Detector-Double-Updated-Prototype
A Flask-based web application for detecting phishing emails using machine learning and rule-based techniques, featuring file uploads and a flagged email dashboardP
(This one inputs the multiple emails as .eml files and then detects the Phishing traits in them.)


# Phishing Email Detection Web Application

This is a Flask-based web application designed to detect phishing emails. The application leverages machine learning and rule-based techniques to identify fraudulent emails and provides a web interface for users to upload `.eml` files for analysis. Flagged emails are displayed on a dashboard with detailed traits and alerts.

---

## Features

- **Machine Learning Detection**: Uses a trained ML model to classify emails as "Phishing" or "Legitimate".
- **Rule-Based Detection**: Provides additional insights by analyzing emails for common phishing traits, such as:
  - Suspicious keywords.
  - Links leading to phishing websites.
  - Attempts to collect sensitive personal information.
  - Excessive capitalization or poor grammar.
- **File Upload**: Accepts multiple `.eml` files for email analysis.
- **Dashboard**: Displays flagged phishing emails with associated traits and alerts.

---

## Prerequisites

Before running the application, ensure the following dependencies and setups are in place:

1. **Python 3.7+** installed on your system.
2. Install all required Python libraries from the `requirements.txt` file.
3. A trained machine learning model and a vectorizer should be available (or create one using the `train_model` script). 

---

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/phishing-email-detector.git
   cd phishing-email-detector
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Ensure the upload folder exists:

   ```bash
   mkdir uploaded_eml_files
   ```

4. Run the Flask application:

   ```bash
   python app.py
   ```

5. Open your browser and navigate to `http://127.0.0.1:5000/`.

---

## Usage

1. Visit the homepage.
2. Upload `.eml` files using the provided form.
3. The app processes these files and displays detection results for each uploaded email.
4. Flagged phishing emails are displayed in the dashboard accessible from the navigation menu.

---

## Project Structure
