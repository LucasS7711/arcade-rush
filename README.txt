ARCADE RUSH — WEBSITE VERSION

FILES
- index.html: page structure
- style.css: page styling and responsive canvas sizing
- game.js: game logic, drawing, keyboard/mouse controls, sound

RUN IT ON YOUR COMPUTER
1. Extract ArcadeRush-Website.zip into a folder.
2. Open index.html in Chrome, Edge, or Firefox.
3. Click the game area once if the keyboard does not respond immediately.

PUBLISH IT FREE WITH GITHUB PAGES
1. Sign in to GitHub and create a new public repository named arcade-rush.
2. Upload index.html, style.css, and game.js to the repository's top level (not inside another folder).
3. Open the repository's Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select the main branch and / (root), then Save.
6. Wait a minute or two. GitHub will show the public website address in Settings → Pages.

NOTES
- The website version is a JavaScript/Canvas remake of the Java Swing game, not a direct execution of the Java file.
- Best time and best failure count are stored in the current browser using localStorage.
- Sound starts after the first key or mouse interaction because browsers restrict autoplay.
- Minesweeper: left click reveals; right click flags.
- TAB skips a stage; P pauses a speedrun; R restarts the current stage; ESC returns to the menu.
