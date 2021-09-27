**Simulation of “Wheel of Fortune” Game Show**

![image](https://user-images.githubusercontent.com/77749755/134949258-f60cc8c2-b226-437f-a78c-1f42b8ea81b9.png)

 
**Description:**

The overall project is a recreation of the gameshow “Wheel of Fortune”, and I will give a brief description of how it works. Essentially it is a game of trying to guess a phrase through spinning a wheel with cash prizes, and then guessing certain letters and hoping those letters are in the phrase you are trying to guess. Guessing a consonant is free, however guessing a vowel requires you to “buy” the vowel with the money you have in the bank from spinning the wheel. At any point you can try to guess the phrase, but if you are wrong you lose all the money you earned. This project as is, is a very simple version of the game and does not have all of the real rules in place yet.

**Project Relevance:**

The educational goals that this project will be linked to is object-oriented design, test driven development, debugging, and UML. This is linked to object-oriented design through being coded in Java and using objects to create and play the game. Test driven development will be shown through the addition of unit tests to check that aspects of the current game are working correctly, as well as the process of designing through TDD will be used to implement the changes added to the project. Debugging will be used as there are a few things with the current program that need to be fixed and dealt with. Finally, UML will be used for this project to create a thorough diagram of what each of my classes, interfaces, etc. will look like in my project to help with the design process. 


**Proposed Contribution:**

I would add in all of the rules that are a part of the real “Wheel of Fortune” game show including: a system for the user to pay for vowels, being able to see your bank after each spin, creating a real wheel to see spin rather than randomized money values being created, etc. The wheel will also have a randomized list of prizes and dollar amounts that can be won. I will also add in a word bank of different categories to choose from as in the real game the phrase will be under a category, in the current project there is only one category and one phrase. I would update this with allowing the user to choose a category, and then randomizing which phrase they will be trying to guess. Also, will add a change of game mode which simulates the final round of wheel of fortune where the winning contestant gets to play a single game and is given 5 letters and get to choose 5 letters they want to guess. I will also add in unit tests to test that everything currently in the program is working correctly, as there are already a few bugs I found while testing out the program and I can use these tests to make sure they are properly corrected. These unit tests will also help me have a TDD approach to my project as I add them before adding in my new methods/classes to create all of these other rules to the game. Finally, I will be contributing by using UML to plan out my project.

**URL Reference:**

https://github.com/tuj10246/WheelOfFortune

**Building/Running:**

All of this code will be completed in Java and Junit tests will be used for testing of implementation. Ran on any IDE.

**Required Knowledge:**

Proficiency in Java and knowledge of how to use unit testing.















**(PREVIOUS README)....**

WHEEL

**This beginner-level java project recreates the classic game of Wheel of Fortune. It consisits of 3
 players, underscores/dashes to represent letters in the puzzle, and available letters.**



## INITIAL SCREEN

Welcome to the Wheel of Fortune

Available Letters - ABCDEFGHIJKLMNOPQRSTUVWXYZ

Here is the puzzle (Movie):

\-\-\- \-\-\-\-\-\- \-\-\-\- \-\- \-\-\-\-

Player 1 - would you like to Spin (1) or Guess (2) the puzzle? 

**If Player 1 spins, the wheel spins. A Random number from 1 to 10 represents the wheel. Each number respresents a spot on the wheel.**

**Wheel values are as follows:**

**Random Number 1:	$100**
**Random Number 2:	$300**
**Random Number 3:	$500**
**Random Number 4:	$700**
**Random Number 5:	$900**
**Random Number 6:	$2000**
**Random Number 7:	$3000**
**Random Number 8:	$5000**
**Random Number 9:	$-1000**
**Random Number 10:	$0**

*NOTE: My puzzle is "The Secret Life of Bees"*

*NOTE: Does not yet include a system to buy vowels. All letters can be guessed to gain money*

*Under Construction*
