# Dino game hack

The first line of code `Runner.instance_.setSpeed(100000)` sets the speed of the dinosaur to an extremely high value of 100000, which effectively makes the game unplayable as the dinosaur would be moving too fast to jump over obstacles. 

The second line of code `Runner.prototype.gameOver = () => {}` overrides the `gameOver()` method of the `Runner` prototype, which is responsible for ending the game when the dinosaur collides with an obstacle. By setting it to an empty arrow function, this effectively disables the game over functionality, allowing the game to continue indefinitely.
