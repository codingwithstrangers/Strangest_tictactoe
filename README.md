<div align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNjAyMXphYmdkeWhsZjdzNWIyMjg0MGt5N3Rxd3dvZnFjZ2NuZXExMSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/jvOHlU7qhcnsEGuTQZ/giphy.gif" width="250"/>
</div>

<div align="center">
  <img src="https://imgur.com/xU6oPRJ.jpg" width="300"/>
</div>

# Strangest Tic-Tac-Toe

Strangest Tic-Tac-Toe is a unique version of the classic game where a human player ("Stranger") competes against an AI opponent ("Skynet"). This project was created for practice and to improve my skills in HTML, CSS, and JavaScript.

## How the Game Works

1. **Initialization:**  
   The game starts with a random selection of the first player using the `randomplayer()` function.

2. **Player Turns:**  
   - The human player selects a cell by clicking, triggering the `player1_pick_spot()` function.
   - The AI, "Skynet," takes its turn using the `skynet_pick_spot()` function.

3. **Win Conditions:**  
   After each move, the game checks for a winner using the `check_game_status()` function. If a player wins, their score is updated, and a match point circle is filled.

4. **Game End:**  
   The game ends when a player wins two rounds, and a message is displayed announcing the overall winner.

5. **Resetting:**  
   Players can reset the board after each round or reset the entire game once a winner is determined.

## Project Structure

- **HTML Structure:**
  - **Header Section:** Displays player avatars, usernames, and a "VS" symbol, along with turn indicators and ranks.
  - **Main Section:** Contains the Tic-Tac-Toe grid for gameplay.
  - **Stats Section:** Shows the win counts and match points (circles) for each player.

- **CSS Styles:**
  - **Grid Layout:** Organized using CSS Grid, dividing the page into header, main, and stats sections.
  - **Responsive Design:** Adapts to different screen sizes using media queries.
  - **Styling Details:** 
    - Players' avatars are set as background images.
    - Grid cells alternate between white and green, with black borders.
    - The scoreboard and match points visually reflect the game status.

- **JavaScript Functionality:**
  - **Game Variables:** Track player moves, scores, and filled circles.
  - **Win Conditions:** An array defines all possible winning combinations on the grid.
  - **AI Logic:** The `skynet_pick_spot()` function ensures the AI selects a random empty cell.
  - **Player Move Logic:** The `player1_pick_spot()` function manages the human player's moves.
  - **Game Status Check:** The `check_game_status()` function determines the game's outcome after each move.
  - **Scoreboard Update:** Functions like `updateCircles()` and `update_scoreboard()` keep the visual elements up-to-date.
  - **Reset Functions:** `reset_board()` and `reset_game()` clear the board and reset the game, respectively.

## Why I Made This

This project was created as a practice exercise to improve my coding skills. It also provided a fun challenge by incorporating a simple AI opponent.

## How to Use

- Download the project and open the `index.html` file in your browser.
- Enjoy playing against "Skynet"!

## Features

- [x] Basic AI opponent
- [ ] Responsive design
- [ ] Add animations

## Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Safari).

## Bugs and Future Improvements

Feel free to submit issues, fork the repository, and make pull requests. Your contributions are welcome! Known issues include:

- [ ] Lack of responsiveness on mobile devices.
- [ ] AI's move logic could be improved to be more strategic.
- [ ] DOM needs better tracking for scores and rounds won.

## Need Help?

[![Twitter Follow](https://img.shields.io/badge/Twitter-Follow%20%40strangestcoder-1DA1F2?style=for-the-badge&logo=twitter)](https://x.com/strangestcoder)
[![Twitch Status](https://img.shields.io/badge/Twitch-Live%20Codingwithstrangers-9146FF?style=for-the-badge&logo=twitch)](https://www.twitch.tv/codingwithstrangers)
