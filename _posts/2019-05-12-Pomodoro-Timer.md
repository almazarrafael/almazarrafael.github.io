---
layout: post
title: Pomodoro Timer
subtitle: An electronic Arduino based Pomodoro timer.
gh-repo: almazarrafael/Pomodoro-Timer-Arduino
image: /img/pomodoro.png
tags: [electronics]
---
This Pomodoro timer feautures different modes with varying amounts of timer which is counted down in seconds. You can also pause the timer and resume it whenever you want to. [Pomodoro technique.](https://en.wikipedia.org/wiki/Pomodoro_Technique)

<h1> <center> <font color="#DB324D"> function  </font> </center> </h1>

1. A timer that displays how many seconds you have left.
2. Study timer: 25 mins
3. Short break timer: 5 mins
4. Long break timer: 10 mins
5. After each timer has passed it goes to the next mode.
6. You can also pause the timer and then resume it with the same button.

<h1> <center> <font color="#DB324D"> what i learned </font> </center> </h1>

1. How to take input using a push button.
2. How to display and wire an LCD module.
3. How to make a rudimentary timer using delay().
4. How to receive input while the program is running.

<h1> <center> <font color="#DB324D"> resources </font> </center> </h1>

- [My GitHub Repo](https://github.com/almazarrafael/Pomodoro-Timer-Arduino)
- [Pomodoro Technique](https://en.wikipedia.org/wiki/Pomodoro_Technique)
- [Arduino LCD Display Guide](https://www.arduino.cc/en/Tutorial/LiquidCrystalDisplay)

<h1> <center> <font color="#DB324D"> notes </font> </center> </h1>

I had to figure out a way to make a timer that didn't keep the program stalled at delay(). I had to use a for loop that would delay for 1 sec each loop. The problem with this was that you would have to hold down the button for 1-2 seconds for it to actually receive the input and there was a chance for it to keep recieving the input afterwards. I added a two second delay between each input beind received to prevent unwanted inputs. The former issue could be solved by counting milliseconds instead of seconds.

<h1> <center> <font color="#DB324D"> images </font> </center> </h1>
<center>
<img src="https://i.ibb.co/XbHFDQ2/pomodoro-diagram.png" alt="Diagram">
<br>
<br>
<img src="https://cdn.discordapp.com/attachments/577007309461389312/578139617509769216/image0.png" alt="Finished product">
</center>
*The contrast can be adjusted by adding a potentiometer to the contrast pin of the LCD*
