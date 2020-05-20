---
layout: post
title: 8 Bit Computer Program Counter
subtitle: A Program Counter (clock) for a 8 bit computer.
gh-repo: almazarrafael/4-bit-Computer
image: /img/PC.jpg
tags: [electronics]
---
A program counter that uses an ATTiny45. The speed of the clock can be adjusted with the potentiometer. It can also be toggled between the clock and a manual pulse for debugging. All of the buttons are also debounced.

<h1> <center> <font color="#DB324D"> function  </font> </center> </h1>

1. Produces a steady pulsing clock.
2. Can be slowed down or sped up for debugging purposes.
3. Manual pulse also for debugging purposes.
4. The buttons are debounced so it doesn't produce noice (unwanted/unintended signals).

<h1> <center> <font color="#DB324D"> what i learned </font> </center> </h1>

1. How to make a timer that also allows the use of inputs.
2. What an ATTiny is and how to program one and use one.
3. How to debounce a button.
4. What a program counter is and what it does in the computer.

<h1> <center> <font color="#DB324D"> resources </font> </center> </h1>

- [My GitHub Repo](https://github.com/almazarrafael/4-bit-Computer)
- [Ben Eater's Video on Clocks](https://www.youtube.com/watch?v=SmQ5K7UQPMM&t=78s)
- [Arduino Debouncing Guide](https://www.arduino.cc/en/Tutorial/Debounce)
- [ATTiny Programming with an Arduino Guide](https://www.instructables.com/id/Program-an-ATtiny-with-Arduino/)
- My friend, Fahad.

<h1> <center> <font color="#DB324D"> notes </font> </center> </h1>

My friend and I decided to attempt to make a 8 bit computer since we're both Computer Engineering majors. He's a lot more knowledgable when it comes to the major since he's much more far along. He taught me some of the basics knowledge required to making the computer and its architecture. This is the first step we decided to take and we used an ATTiny45 instead of building a clock from scratch because we didn't have that many parts to work with.

<h1> <center> <font color="#DB324D"> images </font> </center> </h1>
<center>
<img src="https://raw.githubusercontent.com/almazarrafael/4-Bit-Computer/master/PC_Schematic.PNG?token=ALHDSCTDJDYD6EHVTXB27TS6ZZOVQ" alt="Diagram">
<br>
<br>
<img src="https://raw.githubusercontent.com/almazarrafael/4-Bit-Computer/master/PC.jpg?token=ALHDSCTYJSWFMR62OOWKBFC6ZZOWQ" alt="Finished product">
<br>
<br>
<img src="https://raw.githubusercontent.com/almazarrafael/4-Bit-Computer/master/ATTiny_Programmer.jpg?token=ALHDSCWLDDS4ERKPF6FGAWK6ZZOTQ" alt="ATTiny Programmer">
</center>
*Circuit used to program the ATTiny45 using an Arduino.*
