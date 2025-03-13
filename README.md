# Alphabetical Letters Game

**Alphabetical Letters Game** is a web-based, responsive game where players click on randomly placed letters in alphabetical order as quickly as possible. The game dynamically adjusts the letter sizes based on the device's screen and the number of letters. A dynamic leaderboard tracks players' best times and automatically resets at midnight (local time).

## Features

- **Responsive Design:**  
  The game layout and letter sizing adjust automatically to suit desktop and mobile devices.

- **Dynamic Letter Placement:**  
  Letters are randomly positioned within the game area while ensuring they are fully visible on the screen.

- **Automatic Font Sizing:**  
  The game calculates an optimal font size based on the container dimensions and the number of letters in play.

- **Persistent Leaderboard:**  
  Players' best times are saved using `localStorage`. The leaderboard is unique for different game modes (based on the number of letters).

- **Automatic Leaderboard Reset:**  
  The leaderboard automatically resets at a specified time (midnight local time by default) so that competition stays fresh every day.

## Demo

You can try the game by opening the [[live demo]](https://alphabeticalletters.com/)(#) (replace with your demo URL if available) or by running the code locally.
