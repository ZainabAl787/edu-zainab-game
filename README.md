EDU.ZAINAB@ — School & Toy Adventure
====================================

FILES
-----
index.html   Complete self-contained game. No external libraries or image downloads.
README.txt   This guide.

PLAY LOCALLY
------------
1. Download and extract edu_zainab_platformer.zip, or open index.html directly.
2. For the best experience, open index.html in current Chrome, Edge, Safari, or Firefox.
3. On desktop: Arrow keys or A/D move, Space/Up/W jumps.
4. On phone/tablet: use the on-screen left, right, and jump controls.
5. Tap/click Sound: On to turn off music and sound effects (or back on).

PUBLISH A PUBLIC LINK WITH GITHUB PAGES
---------------------------------------
1. Sign in to GitHub and create a new public repository, for example: edu-zainab-game.
2. Upload index.html to the root of the repository. README.txt is optional.
3. Open repository Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch, then select the main branch and /(root), and Save.
5. After GitHub Pages finishes publishing, its settings page will show the public URL. Open that URL on your phone, iPad, and computer to check it.

ALTERNATIVE: NETLIFY DROP
-------------------------
1. Keep index.html in a folder on your computer.
2. Sign in to Netlify and use its manual deploy / drag-and-drop page.
3. Drag the folder containing index.html into the deploy area. Netlify will provide a public URL.

EDIT OR ADD QUESTIONS
---------------------
Open index.html in a text editor and find QUESTION_BANK near the top of the script.
Each question has: title, art, prompt, choices (exactly 3), answer (0-based index), and explain.
For example, answer: 1 means the SECOND choice is correct. Keep six questions if you want the HUD to remain 0 / 6; if adding/removing questions, also adjust the six-cloud layout and any text that says six.

CHARACTER NOTE
--------------
No character photo was attached to the request, so the game currently draws an original, simple vector student mascot. To match a specific student's real face and clothing, provide the photo and the sprite can be prepared with a transparent background and integrated in a follow-up edit.

TESTING
-------
The game is built as a single-page HTML5 Canvas game and uses no external dependencies. It includes responsive layout, keyboard and pointer/touch controls, six quiz clouds, three lives, collectible stars, mushroom collisions, generated sound/music, win/try-again screens, and a restart button. Always open the published URL on the target devices to perform a final visual check.
