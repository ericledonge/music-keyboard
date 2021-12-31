# Musical Keyboard

Project inspired by James Q Quick initiative [Advent of Javascript](https://www.adventofjs.com/)

All the code is mine, don't blame James for that 😝

<img width="1146" alt="Capture d’écran, le 2021-12-30 à 21 11 59" src="https://user-images.githubusercontent.com/6333396/147799212-0cb5e507-3d90-4ca0-ac0a-531c5251da27.png">

# Demo

You can use it there: https://competent-euclid-a2df09.netlify.app

# Specs

Users should be able to:

- See the keyboard centered on the page
- Whenever a user hovers over a specific key it will change colors
  - White keys will change to yellow #ffd200 
  - Black keys will change to pink #f40082
- When a user clicks on a specific key, it will play an audio clip. 
  - The audio clips are numbered, but I did not specifically number the keys. You can pick which key should be associated with each audio file.
  - If a user clicks on one key, then immediately clicks on a second key. The 2 files should both play. Meaning, clicking on one key will not stop an existing audio file from playing.

# Tech Stack

React, TypeScript, Vite, Jest, Eslint, Prettier.
