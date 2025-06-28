# Gaming-Using-OpenCV
This project is an interactive computer vision-based game built using OpenCV in Python. It allows the user to play the classic Rock-Paper-Scissors game against the computer by detecting their hand gestures via webcam in real-time.
# 🎮 Rock-Paper-Scissors using OpenCV

A fun and interactive real-time **Rock-Paper-Scissors** game built with **Python and OpenCV**, where you play using hand gestures captured via webcam.

## 🛠️ Features

- 👋 Real-time hand gesture recognition
- 🎲 Computer move generated randomly
- 🧠 Gesture detection using contours and convexity defects
- 🏆 Displays winner and keeps score
- 🖥️ Simple and intuitive interface

## 📌 Technologies Used

- Python
- OpenCV
- Numpy
- Random

  ## 📷 How It Works

1. Webcam captures your hand gesture.
2. Region of Interest (ROI) is extracted and preprocessed.
3. Contours and defects are analyzed to detect if you played Rock, Paper, or Scissors.
4. Computer randomly chooses its move.
5. The result is displayed, and scores are updated.
6. It collects a Data first 100 samples each (total 400 Rock=100,Paper=100,Scissor=100 and Noting =100) .Generates the Acurracy Graph (close them so the main ai vs user game starts).
7. It also generates a window to check the accuracy of detection of Moves of player whether the users shows Rock ,Paper , Scissor or nothing.
