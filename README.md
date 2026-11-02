# Pong Game — Love2D

**Student:** Osaid Mohammed Abdalghafer Motawi  
**Class/Section:** One section (no section number assigned)

## About the Game

This project is a two-player Pong game developed in Lua using the LÖVE (Love2D) framework. Two players control paddles on opposite sides of the screen and try to hit the moving ball past their opponent to score points. The ball bounces off the top and bottom walls and reverses direction when it hits a paddle. Paddle movement and ball movement use delta time (`dt`) for frame-rate-independent motion, and paddle collisions are detected using axis-aligned bounding boxes (AABB). The game also includes a score display and a reset of the ball after each point.

## How to Run

1. Install [LÖVE (Love2D)](https://love2d.org/).
2. Download or clone this repository.
3. Open a terminal in the project folder (where `main.lua` is located).
4. On Windows, open **PowerShell** in the project folder and run:

   ```powershell
   & "C:\Program Files\LOVE\love.exe" .
   ```

   If LÖVE is added to your system PATH, you can alternatively run:

   ```bash
   love .
   ```

> The Windows command assumes LÖVE is installed at `C:\Program Files\LOVE\love.exe`.

## Controls

| Action | Key |
| --- | --- |
| Move left paddle up | `W` |
| Move left paddle down | `S` |
| Move right paddle up | `Up Arrow` |
| Move right paddle down | `Down Arrow` |
| Pause / resume | `Space` |

## My Own Changes

In addition to the tutorial's core gameplay, I customized the game with:

- **Different paddle colors:** The left paddle is green and the right paddle is blue.
- **Red circular ball:** The ball is drawn as a red circle instead of a white square.
- **Pause and resume:** Press `Space` to pause or resume the game; a "PAUSED" message appears while paused.
- **Increasing ball speed:** The ball's horizontal speed increases by 5% each time it hits a paddle.
- **Score tracking:** The game displays both players' scores and resets the ball after a point.

## Screenshot

![Pong game screenshot]()

## Demo Video

[Watch the Pong gameplay demo]()

> Before submitting, save your screenshot as `screenshots/pong-screenshot.png` and your recorded video as `demo/pong-demo.mp4`, or update these links to match your actual filenames.
