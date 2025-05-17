# Handwritten Digit Recognition Web App

A web application that uses a trained neural network to recognize handwritten digits (0-9) from uploaded images.

## Features
- Upload handwritten digit images
- Real-time digit recognition
- Confidence score display
- Modern, responsive UI

## Setup Instructions

1. Install Python 3.11
2. Create and activate virtual environment:
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Train the model (if needed):
   ```bash
   python part1.py
   ```
5. Run the application:
   ```bash
   python app.py
   ```
6. Open http://localhost:5000 in your browser

## Project Structure
```
├── app.py              # Flask web application
├── part1.py           # Model training script
├── mnist_model.h5     # Trained model
├── requirements.txt   # Project dependencies
├── static/           # Static files (CSS)
└── templates/        # HTML templates
```

## Technologies Used
- Python 3.11
- TensorFlow
- Flask
- HTML/CSS/JavaScript 