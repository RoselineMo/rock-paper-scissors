# rock-paper-scissors

Create interactive game

This game is designed to be played on the browser console, hence the JavaScript
is written inside index.html (instead of index.js as per best practice)

Pseudocode - Breaking the problem down

- 1st function getComputerChoice() - Randomly returns ‘Rock’, ‘Paper’ or ‘Scissors’
- 2nd function playRound() - Plays a single round of Rock Paper Scissors. This function takes two parameters: playerSelection, computerSelection and returns a string which declares the winner of the round - something like: "You Lose! Paper beats Rock"
- playerSelection parameter is made case-insensitive
- New function called game() - Uses previous functions to play a 5 round game, which keeps scores and reports a winner or loser at the end.
