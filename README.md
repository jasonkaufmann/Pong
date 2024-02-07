# Pong Game in Unity

This project is a Unity-based implementation of the classic Pong game. It features a simple two-player setup where players can control paddles to hit a ball back and forth.

## Features

- **Basic Pong Mechanics:** Control paddles to keep the ball in play.
- **Score Tracking:** Keep track of how many times each player scores.
- **End Game Scenario:** The game ends when a player reaches the maximum score.
- **Ball Speed Increase:** The ball's speed increases randomly when it hits a paddle.

## Game Scripts

- `Ball.cs`: Controls the ball's movement, scoring, and game state.
- `Player.cs`: Manages player input and paddle movement.

## Getting Started

### Prerequisites

- Unity 2020.3 or later.
- A code editor such as Visual Studio.

### Installation

1. Clone the repository to your local machine.
    ```sh
    git clone https://github.com/jasonkaufmann/Pong.git
    ```

2. Open the project in Unity by navigating to the cloned repository folder.

3. Once Unity loads the project, open the `Scenes` folder and load the main game scene.

### How to Play

- Use the `Vertical` axis input (arrow keys or `W`, `S` for player one, and up, down arrows for player two) to move each paddle.
- The ball starts moving after a countdown and increases speed randomly upon hitting paddles.
- Score points by getting the ball past your opponent's paddle.
- The first player to reach the maximum score of 5 points wins the game.

### Building the Game

To build the game for your desired platform, follow these steps:

1. Go to `File > Build Settings` in Unity.
2. Select your target platform from the list.
3. Click on `Build` and choose where to save the built game.
4. Follow the prompts to complete the build process.

## Contributing

If you have suggestions for improvements or encounter any issues, please feel free to fork the repository, make changes, and submit a pull request with your updates.

## Contact

For any additional questions or comments, you can reach out via email or check out the game's repository on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
