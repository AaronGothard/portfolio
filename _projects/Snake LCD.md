---
name: Snake Game
tools: [Python, CAD]
image: "/assets/images/Snake Game/snake-game-icon.jpg"
description: Snake played on an 8x8 led matrix
sequence: 3
---
#### <b>Snake in Python<b>
<p style="font-size:15px; padding: 0 0 1em 0;">October, 2021</p>
As a side project while I was ahead of schedule in my Amazon Future Engineer program, I used some of the spare hardware (an 8x8 lcd matrix and a joystick) to make the game snake in python.
<br><br>
I began this journey by getting to know the 8x8 LCD as well as how it interfaces with the arduino. The matrix accepts an array of 8, 8 bit integers. Each of these bits represents an LED that is either turned on or off depending on the value of the array. This being my first experience with binary I had a few hurdles to overcome. I began by making a program that displayed text that scrolls across the screen. This utilized a library of arrays for each letter and number, which ended up making it to the final program. After getting the display working, I moved on to the joystick, which was much simpler. I just separated the input into 3 different values: left/right, up/down, and pushdown button input.
<br><br>
Now that the hardware was all good to go, I set out to create the game snake. The overall structure of it is pretty simple:
<br>1. Use the joystick to assign a velocity in both axes
<br>2. Add that value to the snake's position
<br>3. Checked to see if it was on an apple
<br>4. If yes: Add one to the length of the snake and re-assign a random position for the apple
<br>5. Display the current snake and apple on the matrix
<br><br>
After getting this functional and properly working, I decided to 3D model housings for the display and the joystick which I then printed on our Ender 3 3D Printer.
<br><br>
A full demonstration is shown below, and the source code is hosted on my github <a href="https://github.com/AaronGothard/Snake-Python/blob/main/ArduinoSnake.py">here</a>
<br><br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/WlHp1nSYgAQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen autoplay muted></iframe>

