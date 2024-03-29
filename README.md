# Brick Breaker Game on BareMetalOS

### Game Background:

Our game is based on the classic arcade game released in 1976 by Atari called Breakout, in which the objective of the game is for the player to control a paddle and try to bounce a ball to break all of the bricks on the screen.

**How to play:**

- The main objective of the game is to eliminate all of the brick using a paddle and a ball.
- The player can use the A and D key on the keyboard to control the paddle’s left and right movement, with the objective of bouncing the ball.
- The main task here is to keep the ball in play by hitting it with the paddle.
- The game is over when the user has destroyed all of the bricks or when the user’s life is 0.
- Players earn points for each brick destroyed.

**Game Logic:**

- In stage 1, breaking 30 bricks or tiles to collect 30 points to move to stage 2. If the life number is equal to zero, the user will lose.
- In stage 2, keep breaking another 35 bricks or tiles to collect another 35 points to win the game. The life number will transfer from stage 1 to stage 2. If the life number is equal to zero, the user will lose.

**Game Design and Implementation:**

- Background: For the background, I used the given function drawPixelARGB32() from the tutorial material to draw the background first.
- Sprite: Every object in the game is a sprite. Each sprite has a X and Y position and a direction to move the object. For the bricks, the sprite does have a direction but it does not move. The direction is mainly for the ball, paddles and obstacle bricks. The sprite object is a struct.

### Game UI

`Game Introduction`

<img width="768" alt="Screenshot 2024-02-11 at 16 09 59" src="https://github.com/andtr-2021/bricks-breaker-baremetalos-game/assets/79509067/eea27a4a-16ca-4533-841c-e60005e2d15f">

`Level 1: Game Play.`

<img width="780" alt="Screenshot 2024-02-11 at 16 10 38" src="https://github.com/andtr-2021/bricks-breaker-baremetalos-game/assets/79509067/7e8c1a57-52fa-41d3-a7d9-ff1a6ccf17d1">

`Game Over:`

<img width="778" alt="Screenshot 2024-02-11 at 16 11 00" src="https://github.com/andtr-2021/bricks-breaker-baremetalos-game/assets/79509067/bf989edf-12c8-4d5e-ac34-2a67d8c14f46">

`Level 2 Intro:`

<img width="762" alt="Screenshot 2024-02-11 at 16 11 09" src="https://github.com/andtr-2021/bricks-breaker-baremetalos-game/assets/79509067/90849f4f-c40d-42cb-8c51-c7d0304e9f68">

`Level 2: Game Play`

<img width="864" alt="Screenshot 2024-02-11 at 16 11 21" src="https://github.com/andtr-2021/bricks-breaker-baremetalos-game/assets/79509067/c667bda6-b059-48c7-b26a-71e4fce2f1ff">

`You Win:`

<img width="778" alt="Screenshot 2024-02-11 at 16 11 29" src="https://github.com/andtr-2021/bricks-breaker-baremetalos-game/assets/79509067/3a5cc712-5947-493e-99ed-a95b3398a0ec">

### Authors

- Le Pham Ngoc Hieu
- Park Anh Kiet
- Mai Chieu Thuy
- Do Truong An
