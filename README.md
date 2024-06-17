# Emotion-Based Motivational Quotes App

This Streamlit application uses a webcam to detect the user's facial emotions and provides motivational quotes based on the detected emotion. The application utilizes a pre-trained Keras model for emotion detection and a CSV file containing quotes for different emotions.

## Requirements

To run this project, you'll need the following libraries:
- `streamlit`
- `opencv-python`
- `keras`
- `tensorflow`
- `numpy`
- `pyttsx3`
  
Data Set Link - https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset

You can install these libraries using pip:
```bash
pip install streamlit opencv-python keras tensorflow numpy pyttsx3
Usage
Clone the repository and navigate to the project directory:

bash
Copy code
git clone https://github.com/your-username/emotion-quotes-app.git
cd emotion-quotes-app
Place the required files in the project directory:

haarcascade_frontalface_default.xml: Haarcascade file for face detection.
model.h5: Pre-trained Keras model for emotion detection.
p2.csv: CSV file containing motivational quotes for different emotions.
Run the Streamlit app:

bash
Copy code
streamlit run app.py
Open your web browser and go to the URL provided by Streamlit to use the app.
