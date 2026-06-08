**#Temporal Tether**
Hey! Welcome to Temporal Tether.

Most simple games give you a paddle to hit a ball. I wanted to build something different. In this game, you control an anti-gravity anomaly. Instead of hitting the ball, you catch it in your field, reverse its gravity, and slingshot it around the screen.

The coolest part? There are zero image or audio files in this project. Every visual effect and sound (beeps, bounces, and crunches) is generated completely from scratch using math and code.

**How to run it**
You just need three standard Python libraries. Open your terminal and run:
pip install opencv-python numpy pygame

Make sure main.py, audio.py, and visuals.py are all sitting in the same folder.

Open your terminal in that folder and run:
python main.py

**How to play**
Steer: Use the Arrow Keys (or W, A, S, D) to move your gravity field.

Catch: When the falling red ball enters your field, it falls upwards and pulls toward your center.

Score: Whip your field around to launch the ball into the green targets. Just don't let it hit the floor!
