# Ping Pong Game

A classic Pong game built with Python's `turtle` module.

## Overview

This is a two-player Pong game featuring:
- Two paddles (left and right)
- A ball that bounces off walls and paddles
- Score tracking for both players
- Increasing ball speed on paddle bounces

## Files

- `main.py` - Main game loop and controls
- `ball.py` - Ball class with movement and collision logic
- `paddle.py` - Paddle class with up/down movement
- `scoreboard.py` - Score tracking and display

## How to Play

1. Run the game:
   ```bash
   python main.py
   ```

2. **Right Paddle Controls:**
   - `Up Arrow` - Move up
   - `Down Arrow` - Move down

3. **Left Paddle Controls:**
   - `W` - Move up
   - `S` - Move down

4. Score points by making your opponent miss the ball!

## Requirements

- Python 3.x
- `turtle` module (built-in with Python)

## Game Rules

- The ball bounces off top and bottom walls
- Score 1 point when the opponent's ball goes past their paddle
- Ball speed increases with each paddle bounce
- Ball resets to center after a point is scored
