# ProjectCricket
This is the front end repository for Project Cricket. Project Cricket is a Emory CS 370: Computer Science practicum project in which the goal is to use Large Language Models to allow users to generate characters to fight in a series of simulations against pre-existing enemies. 

## Background images

The `Loading.html` page will randomly choose a background image on each visit from a small configurable list. To add your own images:

- Create the folder `assets/backgrounds/` relative to the project root (so the path from `Loading.html` is `assets/backgrounds/`).
- Add image files named like `bg1.jpg`, `bg2.jpg`, etc., or update the array in `Loading.html` with your preferred filenames.
- If no images are found, `Loading.html` uses a subtle fallback gradient.

Example: `assets/backgrounds/bg1.jpg`, `assets/backgrounds/bg2.jpg`.
