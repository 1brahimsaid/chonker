# Chonker x86 Game 🐹

<p align="center">
  <img src="/img/chonker.jpeg"/>
</p>

# What is it?

This game was created using Assembly code and DOS. Hardware/software interrupts were used to respond to button presses. In turn those interrupts were used to create an Escape game in Microsoft Macro Assembler (MASM). This was done to understand interrupts and improve my ability to program in assembly. Probably one of the hardest things I have had to conceptualize and code!

# Interrupts

<p align="center">
  <img src="/img/flowchart.jpeg"/>
</p>

Interrupts offer an alternative way of responding to external events in a microprocessor system. The microprocessor can poll for changes in the environment by constantly looking for those changes, or it can wait until a device signals for a change.

#### INT 10H

BIOS interrupt used to set the video mode of the project.

#### INT 21H

Hardware interrupt for character presses.

# Frustration

Not all coding is fun and cool, here is a clip of this game failing 😂. The reason why this type of code is particularly difficult is because it is extremely low-level and typically what a compiler will spit out. Assembly follows a 1:1 ratio, between what the computer is told to do and what it does. This is how computers understand the code you type in your chosen program, and typically is not the easiest to read or understand. This type of code interacts directly with registers and other logic gates behind the scenes. Check out this video below see how frustrating this coding can be.

[![Frustration](http://img.youtube.com/vi/21oYjKJl1RE/0.jpg)](http://www.youtube.com/watch?v=21oYjKJl1RE)

> _Click to Proceed to the Video_
