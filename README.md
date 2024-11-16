![AI Mine](https://raw.github.com/pepa65/aimine/main/aimine.png "AI Mine")

# AI Mine
https://github.com/pepa65/aimine

## What is this?
This is an AI Minesweeper. In the traditional Minesweeper, your task consists of two parts:
1. Select a random cell based on your sixth sense.
2. Identify a non-mine cell based on logical reasoning.

Task 2 is error-prone, unproductive, and a waste of time for humans!
Leave this boring task to the computer..! (Random clicking is way more exciting..?)

This program is a semi-automatic minesweeper that does task 2 automatically.
What you have to do is task 1: you can just test if you are lucky or not..!

## Why did you make this program?
I (Yusuke Endoh) created this program to symbolize the relationship between AI and humans in the near future.

In recent years, AI has begun to take fun jobs away from humans, such as writing, drawing, and programming.
The new role of humans is to take responsibility, that is, validate the output of the AI and make the final decision.

I expressed this relationship in Minesweeper.

## Sometimes this AI does not solve parts that can be solved logically. Why?
This is by design. AI still is not perfect and it needs human intelligence for verification, validation and correction..!

## What's the truth?
This AI only handles where it can infer locally from two close number cells.
So, it will *not* infer the following cases:
* Where it can infer from three or more number cells.
* Where it can infer globally from the remaining number of mines.

This AI algorithm is ported from my IOCCC 2020 winning entry ([code](https://www.ioccc.org/2020/endoh1/prog.c) / [doc](https://www.ioccc.org/2020/endoh1/index.html)).

## This AI is too slow.
Move the range slider at the bottom of the page to the right.

## 💣 is not a mine, it's a bomb.
Yes, it is. Looks like it's too late now that the fire is already lit.

(I couldn't find a Unicode emoji for a mine.)

## I've seen other Minesweepers with AI.
Yes, there are many existing Minesweeper AIs created by many different people for many different purposes.

My purpose in creating this AI is to take away the fun element of Minesweeper, to show its "luck game" nature, and to make the player feel helpless. 😏

## Mine2000 has too much luck factor!
I agree.

FYI: [Minesweeper 2000 project](http://dobo.o.oo7.jp/soft/mine2000/index.htm).

## This is not AI. It is just an algorithm.
Well, let's ask AI.

Me: "Can a program that semi-automatically solves Minesweeper be considered AI?"
ChatGPT: "Yes, a program that semi-automatically solves Minesweeper can be considered a form of artificial intelligence (AI)."

AI says it's AI, so why not AI..?
