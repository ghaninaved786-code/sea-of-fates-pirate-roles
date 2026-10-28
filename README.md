# ⚓ Sea of Fates: Pirate Roles (Prototype 2)

A playable prototype for **Sea of Fates**, an anime-inspired open-world pirate RPG pitch. This prototype shows a rough idea of what each of the 10 pirate crew roles does by giving every role its own short mini-game.

It is a single HTML file with no dependencies, no build step and no install.

## How to run

1. Download `sea-of-fates-pirate-roles.html`.
2. Open it in any modern browser (desktop or phone).

To host it on GitHub Pages, rename the file to `index.html` and enable Pages for the repository.

## How to play

1. Enter a **username**.
2. Type the **role** you want to play (or tap one of the role chips), then press **Set Sail**.
3. Play that role's mini-game. A mistake or timeout ends the run, and the score goes on the leaderboard.
4. Every role has an **Ability** button that unlocks once you reach a score threshold, then goes on cooldown after use.

## The 10 roles

| Role | Mini-game | Ability (unlock score) |
|---|---|---|
| **Captain** | An enemy attack pattern appears. Pick its counter from 4 options within a few seconds. A book lists every pattern and its counter. | Hint highlights the correct option (3) |
| **Combatant** | Parry and attack duel. Press Attack or Parry while the marker is inside the small hit zone. One hit wins, and each new enemy has a smaller zone. | Next tap always succeeds (3) |
| **Cook** | Collect the recipe's ingredients from the map, then cook by tapping the correct number (1 to 3) repeatedly. One wrong tap spoils the dish and you collect everything again. | Faster collecting and cooking (3) |
| **Navigator + Thief** | Type the location where each shown item is found, using the info book. If time runs out you are imprisoned and must tap Jailbreak in the zone within 1 second. | Free from jail and the correct place is highlighted (5) |
| **Musician** | Tap the note shown under the timer. Options change every turn and the timer shrinks. | Any tap counts as correct for 3 turns (5) |
| **Shipwright** | Pick equipment from the store (one at a time), bring the one the ship needs and repair. 4 repairs fix a ship. | Buy up to 3 helper bots, each costing more points (always available) |
| **Archaeologist** | Choose a language (German, Spanish, Japanese, Korean, French) and translate the English sentence. Choosing English is the hardest mode. | Reveals the exact translation (3) |
| **Doctor** | Type the cure for the disease shown, using the medical book. | Extra time to answer (3) |
| **Sniper** | Dodge at least 7 bots with the joystick. Change picks a target, Shoot fires (2 second cooldown) and always hits the target. Shooting a close bot causes recoil damage. | Next 2 shots fire 2 bullets each (5) |
| **Helmsman** | Keep the drifting ship in the middle of the bar with Left and Right. | Ship stays balanced for 2 seconds (10) |

## Notes

- **Japanese and Korean answers are typed in romanized letters only**, not the original script. A few common spellings are accepted.
- The **leaderboard** is saved in the player's own browser (`localStorage`). It is not shared between players.
- **Sniper controls:** joystick, or arrow keys / WASD on desktop.
- Light and dark mode follow the device setting.

## Known limitations

- This is a rough design prototype. Balance, difficulty and content amounts are placeholders.
- Sniper bots walk through walls. Walls only block the player and bounce the bullet.
- No sound or animation polish.

## Roadmap

Separate prototypes are planned to explain other parts of the game in detail, such as **Navy roles** and **Celestial roles**.

## Credits

Game design and concept: Lone (Naved Ghani).
