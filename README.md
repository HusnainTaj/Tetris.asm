# Tetris.asm
Simple Tetris game clone written in 16-bit x86 assembly for my Computer Organization and Assembly Language (COAL) semester project.

## How to run
### 1. afdbox (recommended)
Run by simply double clicking `tetris.asm` using [afdbox](https://github.com/HusnainTaj/afdbox)

### 2. Manual
1. Download `tetris.asm`
2. Compile using a 16-bit x86 compiler. e.g. NASM
3. Run the generated `.com` file in a DOS machine. use DOSBox

## Controls
Use Left/Right Arrow keys to move the falling brick.

## Objective
Your goal is to control the bricks to create complete horizontal lines and not let the bricks reach the top of the playing field for as long as you can.

## Time Limit
You will have 5 mins to fill/clear as many rows as you can.

## Bricks
There are four different types of bricks which will fall from four points from the top randomly.

Next Brick will also be shown in the bottom right corner.

## Scoring
Clearing a line will rewards 10 points.
Score is displayed at the top left corner of the game screen.

## Screenshots

![Main Menu](https://github.com/HusnainTaj/Tetris.asm/assets/85726252/8fd1f2c4-763f-4bd9-88eb-13dabcefd7f8)

![Game](https://github.com/HusnainTaj/Tetris.asm/assets/85726252/9d175e59-3fb9-4433-9435-2b0c6fe2b1d0)

![End Screen](https://github.com/HusnainTaj/Tetris.asm/assets/85726252/81829cb0-6313-4a42-9bef-a2db8d843342)
