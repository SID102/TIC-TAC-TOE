# TIC-TAC-TOE GAME

Welcome to the Tic Tac Toe game repository! This is a classic two-player game built using React.

## Table of Contents

- [Getting Started](#getting-started)
- [How to Play](#how-to-play)
- [Prerequisites](#prerequisites)
- [Game Details](#game-details)

## Getting Started

### How to play

Tic-Tac-Toe is a classic two-player game where the goal is to be the first to get three of your marks (either "X" or "O") in a row, either horizontally, vertically, or diagonally on a 3x3 grid. 
#### Objective: Be the first player to complete a row, column, or diagonal with three of your marks.

### Prerequisites

Before you can run the Tic Tac Toe game, make sure you have react setup in your PC you can refer the following page for more detail regarding installation of react on windows( https://learn.microsoft.com/en-us/windows/dev-environment/javascript/react-on-windows) or you can use codesandbox in place of this.

### Game Details

You are first shown with a 3X3 grid 

![Game Board](https://github.com/SID102/TIC-TAC-TOE/assets/69961979/63ab6ccc-d336-44b1-b152-e8d94c4156d5)

This is the board where you are going to play the game.
On above of this grid there is a section which shows which player have to make the turn and also the winner of the game.

![Info section](https://github.com/SID102/TIC-TAC-TOE/assets/69961979/8b1cfd87-ca79-4774-a620-3ef64a84e8b9)

There is a section which shows the steps and stores the state of the game at that perticular step.By clicking on that steps user board will transform to the board of that step.

![Time Travel Section](https://github.com/SID102/TIC-TAC-TOE/assets/69961979/42e0378c-75b0-4282-b4cd-4b681580a809)

Eg of time travel:- 

![9th step board](https://github.com/SID102/TIC-TAC-TOE/assets/69961979/122e0196-8361-438e-bd8b-74dc91bf5760)



![Board changed to 6th step board](https://github.com/SID102/TIC-TAC-TOE/assets/69961979/00df5e76-a791-4212-aa22-18626b79fdef)

A user can also start with new moves from previous step , only change occur is that all the history after that step will be cleared and new history will start creating based on new steps.

Once a player wins it will be shown on the upper part of the page and no more moves can be made after that.

![Winner Declaration](https://github.com/SID102/TIC-TAC-TOE/assets/69961979/d0fa15e2-34b3-4bd7-8dfd-7b4666dc43b0)






