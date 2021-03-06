[![Build Status](https://travis-ci.org/omenking/swap-n-pop.svg?branch=master)](https://travis-ci.org/omenking/swap-n-pop) ![Test](https://ci.appveyor.com/api/projects/status/github/omenking/swap-n-pop?branch=master&svg=true)


## Goal

An online competitve TA/PdP/PPL clone.

## Project Tenets

There's multiple TA/PdP/PPL clones in development but they did not
adhere to the teants below.


### 1. Open-Source

Open-source allows exploits to be found and patched.
Open-source creates community ownership.
Open-source encourages collaboration.

### 2. TDD (Test Driven Development)

The community can trust this clone to be faithful frame-by-frame
to the game/panel mechanics because the specs prove it.

### 3. Auto-Update

Out-of-sync versions is frustrating. Its important the game can
automatically update and with ease.

### 4. Cross-Platform

OSX, Windows, Linux.

### 5. First-Class Lag Compensation

If we want a game as competitive as SFV or other modern online
fighting games, we need to adopt modern lag compensation techniques (UPD P2P).

### 6. No-Frills Codebase

Its important to keep tooling simple for easy long term maintenance
and so people can jump into the codebase with minimal effort.

eg.
I prefer coffescript and I could have easily installed webpack to support
my preference to optimized my preferred workflow. But I decided its more
important to forgo personal preferences and use what comes with whats
supported with Chrome as long as doesn't put undue burden on
development.
