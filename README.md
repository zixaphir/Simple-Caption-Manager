# Simple Caption Manager
A simple web UI to write, modify and manage image caption files. Helpful when writing captions for images intended for training with Stable Diffusion etc.

![Simple Caption Manager - Preview Image](https://user-images.githubusercontent.com/6050484/234392098-cb47b4bc-1d23-4bc8-a900-cbb87d2c5f39.png)


## How to use
* Put folders with images in `/data/`. 
* If an image file has no caption file it will be created automatically.
* When captions are edited it updates the caption files instantly without asking to save anything (be careful).
* Click on images to view in bigger size; focus mode.

## Shortcuts
* Open directory selecter:  `Ctrl` + `O`.
  * Select directory using keyboard: `1-9`.
  * Navigate in directory list `Up/Down`, press `Enter` to select.
* Traverse between images when in focus mode: `Cmd` + `Left/Right`.

## Features
* Search and replace
* Append to captions
* Use filenames as captions
* Clear captions

## How to get running
1. Run `npm install` to install dependencies.
2. Run `npm run dev` in terminal, and open `http://localhost:5173/` in your browser.