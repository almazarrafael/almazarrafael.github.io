---
layout: post
title: Keypad Lock
subtitle: An electronic Arduino based Keypad Lock.
gh-repo: almazarrafael/Keypad-Lock
image: /img/overviewsquare.jpg
tags: [electronics]
---
This is a keypad lock that can be used to relay to an actual lock/motor. The keypad itself can also be swapped out for a different form of verification. This is more of a concept project meant for learning and not an actual product that should be used as a lock.

<h1> <center> <font color="#DB324D"> function  </font> </center> </h1>

1. Input a 4-digit code.
2. The program checks whether the code matches the passcode after it's reached 4 digits.
3. If it does match then access is granted and it sends out a logic 1 out to a green LED or if it's denied it sends it to the red LED.

<h1> <center> <font color="#DB324D"> what i learned </font> </center> </h1>

1. How keypads work and how to take input from them
2. How to use an I2C (pronounced I squared C) LCD Display.

<h1> <center> <font color="#DB324D"> resources </font> </center> </h1>

- [My GitHub Repo](https://github.com/almazarrafael/Keypad-Lock)
- [I2C LCD Display Arduino Library](https://github.com/fdebrabander/Arduino-LiquidCrystal-I2C-library)
- [Arduino Keypad Guide](https://playground.arduino.cc/Code/Keypad/)
- [Arduino I2C LCD Display Guide](http://www.techydiy.org/how-to-connect-an-i2c-lcd-display-to-an-arduino-uno/)

<h1> <center> <font color="#DB324D"> notes </font> </center> </h1>

I had to use a different LCD display that had a built in chip into the back so it only needed 4 pins instead of a regular one with 16 pins. I also had to figure out how keypads work and how to use them. With some very intense research (googling), I found libraries that suit my needs for this project. One of the guides showcased the same project but didn't show any code so I had to figure that out on my own. All in all, it was a pretty easy project but now I know how to use keypads and an I2C LCD Display for my future projects. In the future, I hope to use the same locking concept but instead using an RFID receiver and tags.

<h1> <center> <font color="#DB324D"> images </font> </center> </h1>
<center>
<img src="https://cdn.discordapp.com/attachments/577007309461389312/579849154285797377/overview.jpg" alt="Overview">
<br>
<br>
<img src="https://cdn.discordapp.com/attachments/577007309461389312/579853557164015617/denied.jpg" alt="Access Denied">
<br>
<br>
<img src="https://cdn.discordapp.com/attachments/577007309461389312/579853556979335189/granted.jpg" alt="Access Granted">
</center>
