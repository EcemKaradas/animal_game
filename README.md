🐾 Animal Games

A collection of seven small browser games, one for each animal. Every game is a single HTML file that runs in the browser: no installation, no build step, no server. It works on a computer and on a phone or tablet.

Play online: https://ecemkaradas.github.io/REPO-NAME/ (replace REPO-NAME with the name of this repository)

The games
Animal	Game	Controls
🐍 Snake	Eat fruits, grow longer and turn rainbow.	Arrow keys / swipe
🐰 Rabbit	Hop along the path, collect carrots and jump over obstacles.	Up / Down = change lane, Space = jump (swipe and tap on a phone)
🐒 Monkey	Swing from liana to liana with real pendulum physics, grab bananas and don't fall into the river. Climb the rope up and down, then let go and fly to the next liana.	Up / Down = climb, Right arrow or Space = let go (swipe and tap on a phone)
🐨 Koala	Climb a giant tree, switch sides, dodge coconuts and bees. The koala gets faster as you go.	Left / Right = switch sides (tap the left or right half on a phone)
🐸 Frog	Hold to charge a jump, then fly from lily pad to lily pad and catch flies. Pads sink, and dragonflies, leaping fish and birds get in the way.	Hold Space / Up to charge, release to jump (press and hold on a phone)
🐟 Fish	Eat smaller fish, run from bigger ones and grow.	Arrow keys / WASD (touch and drag on a phone)
🐭 Mouse	Run through mazes, eat all the cheese and dodge the cats and mousetraps. Golden cheese scares the cats.	Arrow keys / WASD (swipe on a phone)
Features in every game
Skins: unlock new looks for your animal with the coins you collect.
Accessories: hats, glasses, scarves, capes and more (head, face, neck and body slots), just for fun.
6 skills: ghost, slow motion, double coins, magnet, lucky golden and shield. Buy them with coins and use them with the keys 1 to 6.
Achievements: complete goals and claim coin rewards.
Continue: after a crash you can pay coins (200, 300 or 500) to continue.
Levels: the background changes softly with each level, and the game gets harder as you progress.
Own save data: every animal keeps its own coins, skins, accessories, skills and achievements, saved in the browser (localStorage).
Hub page: index.html lets you pick an animal and shows each game's coins and best score.
Project structure
index.html   hub page (choose an animal)
snake.html   rabbit.html   monkey.html   koala.html
frog.html    fish.html     mouse.html
README.md

Each game is fully self-contained: HTML, CSS and JavaScript in one file, drawn on a canvas. The hub links to the games, so keep all files in the same folder.

Run it locally

Download the files and open index.html in a browser. That's all.

Publish with GitHub Pages
Put all the .html files in the root of the repository (the file names must match exactly, for example frog.html, not frog (1).html).
Go to Settings → Pages, choose the main branch and the / (root) folder, and save.
After a minute or two the site is live at https://USERNAME.github.io/REPO-NAME/.
Notes
Progress is stored in your browser, so it stays on the device and browser you played with. Clearing site data resets it.
The hub's title is set in one place: the COLLECTION_NAME constant at the bottom of index.html.
