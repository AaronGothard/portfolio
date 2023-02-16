---
name: Snake Game
tools: [Python, CAD]
image: "/assets/images/Snake Game/snake-game-icon.jpg"
description: Snake played on an 8x8 led matrix
sequence: 3
---
#### <b>Snake in Python<b>
<p style="font-size:15px; padding: 0 0 1em 0;">October, 2021</p>
As a side project while I was ahead of schedule in my Amazon Future Engineer program, I used some of the spare hardware (an 8x8 lcd matrix and a joystick) to make the game snake in python. There were many issues to work through, but after a few class periods I had it working.
<br><br>
The hardware is run on an Arduino UNO being programmed in python instead of its native, C++ based language. There are many drawbacks to this, but the class was meant to teach python. The software uses a simple motion system and some basic logic to determine the outcomes of each game. Once the game is started, you can control your snake via the joystick, and, if you're anything like me, you will die embarrassingly early in the game. A scrolling text box will tell you that you lost and show your score (7). After completing this, I designed a handle for the joystick and a case for the matrix module to improve the overall look and feel of the project.
<br><br>
A full demonstration is shown below, and the source code is hosted on my github <a href="https://github.com/AaronGothard/Snake-Python/blob/main/ArduinoSnake.py">here</a>
<br><br>
<video width="320" height="240" autoplay muted>
  <source src="assets/Snake using 8x8 Matrix and Joystick Python.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>

