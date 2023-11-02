# Structure
## AI.jack
### Fields
- maxSpeed: int
- paddle: Paddle (initailised at init)
### Methods
- move: (ballY: int) -> void
    - takes difference of ballY and paddleY to calculate direction and moves in that direction
- destroy etc.
## Paddle.jack
### Fields
- x, y, w, h (all int)
- maxSpeed: int
- currentDir: int
### Methods
- setDirection(direction: int) -> void
- move() (uses this.currentDir)
- draw()
- destroy()
- getters of all the fields
