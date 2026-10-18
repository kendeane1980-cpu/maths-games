# Penalty Shootout

A timed column-addition game for children, made to be played on a phone. Every right answer is a penalty scored past the keeper.

**Play:** https://kendeane1980-cpu.github.io/maths-games/

## How to play

- **1 player:** choose 2 or 3 digit sums, with or without carrying, how many penalties and how much time. Score them all before full time.
- **2 players on one phone:** players take alternate kicks, like a real shootout, and pass the phone between turns. Each player picks their own level, so an adult and a child can play each other. Each player's clock runs only while they work out their sum and stops when they press Shoot. Most goals wins, and the fastest total time breaks a tie.

## How it works

- The whole game is one file, `index.html`, with no build step and no server.
- Sums are generated fresh in the browser every game.
- Best times, names, kits and settings are saved in the phone's own browser storage (`localStorage`). Nothing is sent anywhere.
- Fonts come from Google Fonts. Everything else, including the sounds, is made in the page.

## Updating

Edit `index.html` and push to `main`. GitHub Pages republishes the site within a minute or two.

## Add to your home screen

- **iPhone:** open the game in Safari, tap Share, then Add to Home Screen.
- **Android:** open it in Chrome, tap the ⋮ menu, then Add to Home screen.
