# Tic Tac Toe — Series

A simple **Tic Tac Toe series game** built using **HTML, CSS, and JavaScript**.

## Features

* Enter names for both players.
* Player names cannot be empty or identical.
* Choose the number of matches:

  * 3 matches
  * 5 matches
  * Custom matches
* Play multiple Tic Tac Toe matches as a series.
* Match scores are displayed below each player's name.
* **Play Again** starts the next match.
* **New Series** starts a completely new series.
* After the final match:

  * Shows the series winner and final score.
  * Example: `Player X has won the series by 3-2`
  * **Play Again** is removed.
* For a 1-match series, it shows only the match result.
* Handles draw matches.
* X and O starting players alternate between matches.
* Responsive design for desktop and mobile.

## Technologies

* HTML5
* CSS3
* JavaScript

## Project Structure

```text
tic-tac-toe/
├── tic_tac_toe.html
```

## How to Run

1. Download or clone the project.
2. Keep all three files in the same folder.
3. Open `index.html` in any modern web browser.
4. Enter player names and select the number of matches.
5. Start playing.

## Game Flow

```text
Enter Player Names
        ↓
Select Number of Matches
        ↓
      Start
        ↓
    Play Match
        ↓
   Match Result
     ↙       ↘
Play Again   New Series
    ↓
Next Match
    ↓
Final Match
    ↓
Series Result
    ↓
New Series
```
