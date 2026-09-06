# StrikePoint

StrikePoint is a browser-based, round-based tactical first-person shooter. The game is designed around short competitive matches, tactical gameplay, weapon management, and objective-based rounds.

StrikePoint was created as a personal project to help me understand the fundamentals of programming with AI assistance. The game takes inspiration from some of my favorite competitive shooters, particularly VALORANT and Counter-Strike 2. I used ideas from these games as a starting point for things such as round structure, team objectives, buying weapons, the HUD, the scoreboard, and tactical gameplay, while building my own implementation and systems.

## About StrikePoint

StrikePoint is built around a 5v5 tactical shooter format where the player fights alongside AI-controlled teammates and opponents.

The main tactical mode uses a round-based system. Depending on the player's selected side, the objective changes. Counter-Terrorists defend the site and attempt to stop the bomb from being planted or defuse it after it has been planted. Terrorists attempt to attack the site, plant the bomb, and protect it until it detonates.

The game also includes other modes for players who want faster gameplay without the traditional bomb objective.

Current game modes include:

* Tactical 5v5
* Arena 2v2
* Arena 5v5

The arena modes focus more on direct firefights and respawning, while the tactical mode focuses on objectives, economy, positioning, and round management. The mode selection and round systems are implemented directly into the game.

## Gameplay

The main gameplay loop is based around preparing for a round, purchasing equipment, fighting the opposing team, and completing the objective or eliminating the other team.

The tactical mode includes:

* 5v5 teams
* Round-based matches
* AI teammates and opponents
* Bomb planting
* Bomb defusing
* Buy phase
* Weapon purchases
* In-game economy
* Health and armor
* Ammunition and reloads
* Weapon switching
* Weapon scopes
* Kill rewards
* Headshot tracking
* Score tracking
* Tactical radar
* Round timer
* Kill feed
* Scoreboard

The game also has a freeze/buy phase before rounds begin, allowing players to purchase weapons and prepare for the upcoming round.

## Weapons

StrikePoint includes a weapon system with multiple weapon categories and weapon slots. Weapons can be purchased, equipped, switched between, reloaded, and used with different firing and aiming behaviors.

The game also includes scoped weapons and a dedicated scope interface. Weapon ammunition is tracked using magazine and reserve ammunition, and the HUD updates based on the currently equipped weapon.

## AI Opponents

One of the main technical parts of StrikePoint is the AI-controlled players.

Instead of requiring multiple real players to test the game, StrikePoint uses AI-controlled teammates and opponents. This allows the game to function as a single-player experience while still maintaining the structure of a team-based shooter.

The AI players participate in the round simulation alongside the player, allowing the player to fight against and play alongside computer-controlled characters.

## User Interface

The HUD was designed around the type of information that is important in a competitive FPS.

During gameplay, the screen displays information including:

* Current team score
* Round timer
* Kill feed
* Objective information
* Ping
* Ammunition
* Current weapon
* Health
* Armor
* Money
* Kills
* Headshots
* Weapon slots
* Radar

The HUD also includes hit confirmation, kill confirmation, damage indicators, screen effects, and other feedback designed to make combat easier to understand.

## Radar

StrikePoint includes a tactical radar positioned in the upper-right portion of the screen.

The radar is designed to give the player additional information about the current battlefield while keeping the main view focused on the action. It has its own visual frame and remains separate from the main HUD scaling.

## Controls

The game uses standard FPS controls.

The default controls include:

* W, A, S, D — Movement
* Mouse — Aim
* Left Mouse Button — Fire
* Right Mouse Button — Aim or scope
* Space — Jump
* Ctrl — Crouch
* Shift — Walk
* R — Reload
* Q — Switch weapon
* E — Plant or defuse
* B — Open buy menu
* Tab — Scoreboard
* F — Flashlight
* Esc — Pause

The controls can also be rebound through the settings menu. The project stores its key bindings so that players can customize their controls.

## Settings and Performance

StrikePoint includes a settings system that allows players to change different parts of the game.

Settings currently include:

* Mouse sensitivity
* Field of view
* Master volume
* Crosshair gap
* PC performance profile
* Quality preset
* FPS target
* Dynamic performance mode
* FPS counter
* Retro pixel filter
* Announcer voice
* Ambient music
* Custom key bindings

There are also different performance profiles for low-end PCs, mid-range PCs, high-end regular PCs, and high-end gaming PCs.

The goal of these profiles is to allow StrikePoint to run on a wider range of hardware instead of only targeting high-end gaming computers.

## Visual Style

StrikePoint uses a dark tactical visual style with blue and orange team colors. The interface uses translucent panels, compact information displays, simple borders, and high-contrast text.

The game also has a retro-inspired rendering option that uses a low-resolution rendering process and a pixel-style post-processing effect.

The visual direction is influenced by modern competitive FPS interfaces while also experimenting with a more stylized and lower-resolution appearance.

## AI-Assisted Development

StrikePoint was developed using an AI-assisted programming approach.

I used AI as a coding partner throughout the development process. Instead of writing every part of the project completely manually, I used AI to help me create systems, understand code, debug problems, and experiment with different implementations.

This approach is sometimes referred to as "vibe coding." For me, the project was an opportunity to learn how AI can be used during the development of an actual application rather than just using it for small pieces of code.

I still had to decide what I wanted the game to do, test the results, find problems, and determine what should be changed.

## AI Models Used

I used two AI models during the development of StrikePoint.

### DeepSeek V4 Flash

DeepSeek V4 Flash was the main AI model I used during development.

I used it for a large portion of the coding process, including creating systems, modifying existing code, debugging, and explaining programming concepts.

### GLM-5.3-Flash

GLM-5.3-Flash from Z.AI was used as a secondary AI model.

I used it alongside my main model to get alternative solutions, test different approaches, and help with development when I needed another perspective.

## Inspiration

StrikePoint is heavily inspired by the competitive FPS games that I enjoy playing.

Some of the biggest influences on the project are:

* VALORANT
* Counter-Strike 2

These games influenced different parts of StrikePoint, including the tactical round structure, team-based objectives, economy and buy system, bomb objective, HUD layout, and overall competitive FPS design.

StrikePoint is not intended to reproduce either game. Instead, I used elements that I liked from those games as inspiration while experimenting with my own implementation.

## Development

StrikePoint is currently built as a browser game using HTML, CSS, and JavaScript, with a 3D game environment and rendering system.

A large portion of the project is contained within a single HTML file. This was intentional because it makes the project easier for me to develop, test, and deploy while I am learning.

The project contains systems for:

* Player movement
* Camera controls
* Weapons
* Shooting
* AI players
* Round management
* Game modes
* Economy
* Buying
* Bomb objectives
* HUD
* Radar
* Scoreboard
* Settings
* Performance management
* Key rebinding
* Visual effects
* Audio
* Menus

## Deployment

The plan is to publish StrikePoint as a web application so that players can access it directly through a browser.

I plan to use GitHub to store and manage the source code and Render to deploy the game.

The basic deployment workflow will be:

GitHub → Render → Web Browser

Using this setup will allow me to continue updating the game through the GitHub repository while having a publicly accessible version hosted through Render.

## Project Status

StrikePoint is currently in development.

The main gameplay systems are being developed and tested, but the project is still being improved. Features, balancing, visuals, performance, and gameplay mechanics may continue to change as development progresses.

## Future Plans

Some features I may add or improve in future versions include:

* More weapons
* More maps
* Improved AI
* Better weapon animations
* Additional game modes
* More detailed sound design
* Improved visual effects
* Better performance
* More advanced team AI
* Additional objectives
* Improved matchmaking-style systems
* More customization
* More detailed statistics
* Better mobile and lower-end hardware support

## Goal of the Project

The main goal of StrikePoint is not just to make a browser game.

I wanted to use the project as a way to learn how a larger game is structured and how different systems work together.

Building StrikePoint has allowed me to experiment with game development, JavaScript, 3D rendering, artificial intelligence, user interfaces, performance optimization, and deployment.

It is also an experiment in how far I can take a project while working with AI as part of my development process.

## License

This project is a personal development and learning project. More information about licensing and use will be added as the project approaches a public release.
