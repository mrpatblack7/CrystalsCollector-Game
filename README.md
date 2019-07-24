# CrystalsCollector Game

## Live Link
 - https://mrpatblack7.github.io/CrystalsCollector-Game/
 <img width="432" alt="thumbnail_pic" src="https://user-images.githubusercontent.com/45779399/61766270-dcf89b00-ada5-11e9-8477-4172b84606c3.png">

## Description
 In this game the computer will randomly select a number. It is the players goal to get to that number by clicking on crystals of varying values. If you get to the number without going over you win that round and if you go over you lose that round.
 
## Game Play
Here's how the app works:
- There will be four crystals displayed as buttons on the page.
- The player will be shown a random number at the start of the game.
- When the player clicks on a crystal, it will add a specific amount of points to the player's total score.
- Your game will hide this amount until the player clicks a crystal.
When they do click one, update the player's score counter.
- The player wins if their total score matches the random number from the beginning of the game.
- The player loses if their score goes above the random number.
- The game restarts whenever the player wins or loses.

## Technologies Used
- jQuery for DOM manipulation
- HTML/CSS

## Code Explanation
- Crystals and their property-value pairs stored as JavaScript objects
- Crystal elements are dynamically created based off of variables and data in the JavaScript file
- Based on user input (mouse clicks), crystal elements are given certain classes
- Classes dictate behavior, placement, and styling, so they (along with their corresponding CSS) are the basis of the game's experience and look
- jQuery simplifies the process of selecting and modifying DOM elements
