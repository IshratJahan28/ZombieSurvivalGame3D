# Zombie Survival Game

A zombie survival game built with Python for the CSE 423 course. Survive waves of zombies, hide behind your shield, collect treasure, and see how high a score you can reach.

## Controls

| Key | Action |
|-----|--------|
| Arrow keys | Move the player |
| Spacebar | Shoot bullets |

## Features

1. **Player movement and shooting:** move with the arrow keys and shoot bullets with the spacebar
2. **Zombie AI pathfinding:** zombies move toward the player instead of moving randomly
3. **Spawn from borders:** zombies appear from the edges of the screen
4. **Zombie-player collision damage:** the player takes damage when a zombie touches them
5. **Shield/wall behind the player:** a protective shield the player can hide behind
6. **Blinking danger zone:** a zone around the player blinks when a zombie gets close
7. **Zombie waves:** small zombies first, then medium zombies
8. **Zombie colors by strength:** zombie color depends on strength and changes with the score
9. **Multi-shot and headshot:** fire multiple bullets, and headshots deal extra damage
10. **Boss zombie:** a tougher boss zombie that appears later in the game
11. **Health packs:** pick-ups that restore health and help control the game
12. **Collect treasure:** collecting treasure increases the score
13. **Kill and restore pack:** killing zombies rewards the player with a restore pack
14. **Environment change:** the game environment changes as the game progresses
15. **Blood trail:** a blood trail effect adds to the survival atmosphere

## Tech used

- Python 3

## How to run

1. Install [Python 3](https://www.python.org/downloads/) if you don't have it.
2. Download or clone this repo.
3. Open a terminal in the project folder and run:

```
python ZombieSurvivalGame.py
```

If Python shows an error like `No module named ...`, install the missing module with `pip install module-name` and run the game again.

## Team

| Member | Features |
|--------|----------|
| Anika | Player movement and shooting, spawn from borders, shield/wall, blinking danger zone, zombie waves |
| Disha | Zombie AI pathfinding, collision damage, zombie colors by strength, multi-shot and headshot, boss zombie |
| Ishrat Jahan | Health packs, collect treasure, kill and restore pack, environment change, blood trail |

## My contribution

I built features 11 to 15:

- **Health packs:** pick-ups that restore health and help control the game
- **Collect treasure:** treasure that increases the score
- **Kill and restore pack:** a restore pack reward for killing zombies
- **Environment change:** the environment changes as the game progresses
- **Blood trail:** a blood trail effect

## Course

CSE 423, BRAC University
