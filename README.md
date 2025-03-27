# Music-recommendation-system-based-of-facial-gestures 

## Overview  
This project is a web-based **emotion-based music recommender** that suggests music based on real-time facial emotion detection. By leveraging **MediaPipe and Keras**, the system identifies the user's mood through facial expressions and recommends suitable music accordingly. The web app is built using **Streamlit**, with **OpenCV** handling image processing, and **streamlit-webrtc** enabling webcam access in the browser.  

## How It Works  
- The application captures live video from the user's webcam.  
- Using **MediaPipe**, it detects facial landmarks and processes the input.  
- A deep learning model built with **Keras** then classifies the user's emotion.  
- Based on the detected emotion, the system recommends an appropriate music playlist.  
- The web app provides an interactive interface for users to explore and play suggested songs.  

## Technologies Used  
- **MediaPipe** – Detects facial features in real time.  
- **Keras** – Trains the deep learning model for emotion classification.  
- **OpenCV** – Handles video frame processing.  
- **Streamlit** – Creates the web application interface.  
- **Streamlit-WebRTC** – Enables real-time webcam capture in the browser.  

## Setup Instructions  
If you want to try this project on your system, follow these steps:  

1. Clone this repository:  
   ```sh
   git clone https://github.com/your-username/emotion-music-recommender.git
   cd emotion-music-recommender
   ```  
2. Install the required dependencies:  
   ```sh
   pip install -r requirements.txt
   ```  
3. Run the application using Streamlit:  
   ```sh
   streamlit run app.py
   ```  

## Future Improvements  
- Enhancing the emotion detection model for better accuracy.  
- Adding integration with Spotify, YouTube, or other music streaming services.  
- Improving UI design for a better user experience.  


