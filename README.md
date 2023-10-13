Rock, Paper, Scissors Game with Hand Tracking
This is a simple Rock, Paper, Scissors game with hand tracking, created using Python and the OpenCV library. It allows you to play Rock, Paper, Scissors against an AI opponent. You can make your choice by showing your hand gestures to your webcam, and the AI will make its choice. The winner is determined based on the traditional rules of Rock, Paper, Scissors.

Game Demo

Getting Started
To get started with this game, follow the instructions below.

Prerequisites
Python 3.x
OpenCV
cvzone
Installation
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/shailendrasingh-cyber/rock-paper-scissors.git
Install the required Python libraries using pip:

pip install opencv-python
pip install cvzone
Usage
Run the game script:

test1.py
The game will start, and you'll see a webcam feed with instructions on how to make your choice.

Show your hand gesture to the webcam based on your choice (Rock, Paper, or Scissors).

The AI opponent will make its choice, and the winner will be determined.

You can play multiple rounds, and the scores will be displayed on the screen.

Controls
Press 's' to start a new game.
Press 'q' to quit the game.
How It Works
This game uses hand tracking to detect and interpret your hand gestures. It then matches your gesture to Rock, Paper, or Scissors and plays against an AI opponent, following the classic rules of the game.

Acknowledgments
This project is based on the work of cvzone and their HandTrackingModule, a useful library for hand tracking with OpenCV.

Author
Shailendra Singh 
