# Video Poker

## About

A 5-card poker game for [Arduboy](https://arduboy.com/) ported from [the Gamebuino version](https://github.com/delpozzo/videopoker-gamebuino).

<img src="src/videopoker.gif?raw=true" alt="Screenshot" width="300" height="300"/>

## Installation

See the [Arduboy Quick Start Guide](https://community.arduboy.com/t/quick-start-guide/2790) for help with uploading games to your Arduboy. Source code is located in the `src/` folder and pre-built binaries are located in the `bin/` folder.

## Instructions

### Controls

- **Left, Right** - Card selection.
- **Up, Down** - Increase / Decrease bet.
- **A Button** - Hold / Unhold card.
- **B Button** - Deal / Draw.
- **Left + Right** - Pause menu (press Left and Right at the same time).

To upload a new game, hold Up while powering on your Arduboy to enter flashlight mode.

### Gameplay

During the bet round, use **Up** or **Down** to increase or decrease your bet. The minimum bet is $5 and the maximum is $100. Press **B** to deal the cards. Select cards using **Left** or **Right**. Press **A** to toggle Hold on the selected card. Press **B** to exchange unheld cards for new ones from the deck. 

Winning hands and rewards are as follows:

**Royal Flush:** 250 x Bet

**Straight Flush:** 50 x Bet

**Four of a Kind:** 25 x Bet

**Full House:** 9 x Bet

**Flush:** 6 x Bet

**Straight:** 4 x Bet

**Three of a Kind:** 3 x Bet

**Two Pair:** 2 x Bet

**Pair of Jacks or Better:** 1 x Bet

### License

Video Poker for Arduboy and Gamebuino Copyright (C) 2018 Mike Del Pozzo

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or any later version.

See [LICENSE](LICENSE) for details.
