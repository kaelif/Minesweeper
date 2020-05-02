# Minesweeper (AI player)
Remember that time you almost had your Myspace set up JUST the way you wanted it, but then Karen just HAD to make a phone call? You played minesweeper for what felt like hours until she plugged the internet back in? What a useless skill you developed, right?

Well, have you ever really thought about how much strategy is involved? All those mini calculations you make within a split second as you make each move? I know, it's hard to remember, try it out real quick: http://minesweeperonline.com/. Take your time, I'll be here when you get back!

Back? Cool! Okay so your brain does a lot, right? Well, I thought the same thing. The program in this repository uses artificial intelligence to mimic the exact process that our brain uses to determine mines are placed. It begins by using symbolic logic to determine with absolute certainty where a nearby mine is placed and makes moves accordingly. With each move made, more information about the placement of mines becomes available is stored by the program.

Of course, there are circumstances where it's impossible to determine where every mine is using pure logic. Check out the "No logical moves" file in this repository. Even the most sophisticated computer wouldn't be able to win this game with absolute certainty. Once the program has gotten to this point, where it's exhausted all of the information it has available, it uses probability to find the least risky move.

Requirements:
  - Pygame
