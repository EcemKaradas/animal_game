# 🐾 Animal Games

A collection of seven original browser games, one for each animal. Each game is a single HTML file built with plain HTML, CSS and JavaScript on a canvas: no libraries, no frameworks, no build step. Works on desktop, phone and tablet.

## ▶ [Play it here: ecemkaradas.github.io/animal_game](https://ecemkaradas.github.io/animal_game/)

## The games

| | Game | What it is about |
| --- | --- | --- |
| 🐍 | **Snake** | Eat fruits, grow longer and turn rainbow. |
| 🐰 | **Rabbit** | Hop along the path, collect carrots and jump over obstacles. |
| 🐒 | **Monkey** | Swing from liana to liana with real pendulum physics, climb the rope and fly to the next one. |
| 🐨 | **Koala** | Climb a giant tree, switch sides and dodge coconuts and bees at growing speed. |
| 🐸 | **Frog** | Charge a jump, land on sinking lily pads and catch flies while dodging dragonflies, fish and birds. |
| 🐟 | **Fish** | Eat smaller fish, run from bigger ones and grow. |
| 🐭 | **Mouse** | Run through generated mazes, eat the cheese and outsmart the cats and mousetraps. |

## What is inside

- **Hand-written game physics:** a real pendulum with energy and pumping for the monkey, ballistic jump arcs for the frog, and fixed time-step flight integration.
- **Procedural levels:** randomly generated mazes with several cat behaviours (hunter, ambusher, wanderer) using path-finding, and obstacle placement that is checked to be reachable.
- **Difficulty that grows with the level,** with softly changing backgrounds.
- **A shared progression system in every game:** coins, unlockable skins, accessories, six skills (ghost, slow motion, double coins, magnet, lucky golden, shield), achievements with rewards, and a Continue option after a crash.
- **Separate save data for each animal,** stored in the browser with `localStorage`.
- **Everything is drawn in code:** all animals, skins and accessories are canvas drawings, with no image files.
- **Responsive and touch-friendly:** keyboard, mouse and touch controls.
- **A hub page** where you pick an animal and see each game's coins and best score.

## Tech

HTML5 Canvas · Vanilla JavaScript · CSS · `requestAnimationFrame` game loop · `localStorage` · GitHub Pages

## Project structure

```
index.html   hub page
snake.html   rabbit.html   monkey.html   koala.html
frog.html    fish.html     mouse.html
```
