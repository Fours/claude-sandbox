# claude-sandbox

A collection of self-contained browser games, each in a single HTML file with all styles and scripts included inline.

## Project Structure

Each game lives in its own `.html` file (e.g. `tic-tac-toe.html`). There are no build steps, dependencies, or external files — everything is self-contained.

## Working in this Repo

- Each session targets **one file**, which will be specified in the prompt.
- Only read and write that file. Do not create new files or modify others unless explicitly asked.
- Keep all HTML, CSS, and JavaScript in the single file — do not split into separate assets.
