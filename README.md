# Maze Game - Puzzle Game Project in C++ with Raylib

## Project Description

This project involves developing a maze-based puzzle game using object-oriented programming (OOP) in C++ and the Raylib graphics library. The game offers an immersive experience where the player navigates through a randomly generated maze in each new game session. The game features three difficulty levels (easy, medium, hard), which affect the size and complexity of the maze.

## Features

### 1. Automatic Maze Generation
- Procedural generation of mazes at the start of each game.
- Ensures connectivity: every position in the maze is reachable, and a solution always exists.

### 2. Three Difficulty Levels
- **Easy**: Small maze with few traps or obstacles.
- **Medium**: Medium-sized maze with more complex paths and additional obstacles.
- **Hard**: Large maze with multiple deceptive paths and complex obstacles.

### 3. Graphical Interface with Raylib
- 2D visualization using Raylib.
- Walls are represented by blocks, and the player controls a character.
- Player movement is controlled using arrow keys.

### 4. Game Mechanics
- The player starts at the entrance of the maze and must reach the exit.
- A timer displays the time taken to solve the maze.
- Option to reset the game at any time, generating a new maze.

### 5. Save and Score System (Optional)
- Records the player's time at the end of each game.
- Displays a leaderboard of the best scores.

## Technical Requirements

- **Language**: C++
- **Graphics Library**: Raylib (2D graphical interface)
- **Programming Model**: Object-Oriented Programming (OOP)

## Key Classes

### 1. Maze
- Represents the maze grid and contains methods for random generation.
- **Properties**: width, height, 2D array of cells (walls or paths).
- **Methods**: procedural generation, solution verification, rendering.

### 2. Player
- Represents the player-controlled character.
- **Properties**: x position, y position, movements.
- **Methods**: movement, interaction with the maze.

### 3. Level
- Manages difficulty levels (easy, medium, hard).
- **Methods**: adjusts maze size and obstacles based on the selected difficulty.

### 4. Game
- Manages the main game loop.
- **Properties**: game state, timer, user interface (menu, end screen).
- **Methods**: event handling, game start, and reset.

## Technical Challenges

- Implementing a procedural maze generation algorithm (e.g., Depth-First Search or Prim's algorithm).
- Handling collisions to ensure the player cannot pass through walls.
- Ensuring that every generated maze is solvable.

## Expected Results

By the end of this project, the game will be fully functional, with an intuitive graphical interface, smooth gameplay, and mazes of varying difficulty generated automatically. The game will be playable on different platforms thanks to Raylib's portability.

## Deliverables

- Source code (organized and commented in English or French).
- Detailed report.

## Possible Extensions (Optional)

- Adding moving obstacles or traps.
- Introducing different visual themes for each difficulty level.
- Local multiplayer with a second player controlled by another key or controller.

## How to Add This Project to GitHub

1. **Create a New Repository on GitHub**:
   - Go to [GitHub](https://github.com) and log in to your account.
   - Click the "New" button to create a new repository.
   - Name your repository (e.g., `Maze-Game`).
   - Choose between a public or private repository.
   - Click "Create repository".

2. **Initialize a Local Git Repository**:
   - Open a terminal on your local machine.
   - Navigate to your project folder.
   - Initialize a Git repository with the following command:
     ```bash
     git init
     ```

3. **Add Files to the Local Repository**:
   - Add all project files using the command:
     ```bash
     git add .
     ```
   - Commit the added files:
     ```bash
     git commit -m "Initial commit"
     ```

4. **Link the Local Repository to GitHub**:
   - Copy the URL of your GitHub repository (available on the repository page).
   - Add the URL as a remote with the command:
     ```bash
     git remote add origin https://github.com/your-username/Maze-Game.git
     ```

5. **Push Files to GitHub**:
   - Push the files to GitHub using the command:
     ```bash
     git push -u origin main
     ```

6. **Verify on GitHub**:
   - Go to your GitHub repository page to ensure all files have been pushed successfully.

## Conclusion

You now have a fully functional maze game project hosted on GitHub. You can continue developing new features, fixing bugs, and collaborating with other developers using GitHub's features. Happy coding!
