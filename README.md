# Dice Rolling Game (C++)

A beginner C++ console game that simulates rolling a pair of dice, with special
outcome detection (snake eyes, boxcars, lucky rolls) and a repeat loop.

## What it does

- Rolls two six-sided dice
- Shows each die value and the sum
- Detects and announces:
  - **Snake eyes** (double 1s)
  - **Boxcars** (double 6s)
  - **Lucky roll** (sum of 7 or 11)
- Lets the user roll again or quit

## Who it's for

Students learning C++ basics: random numbers, conditionals, loops, and console
I/O.

## Features

- `rand()` + `srand(time(0))` for random dice values
- Special outcome messages for doubles, snake eyes, boxcars, and lucky rolls
- do-while loop to roll repeatedly without restarting
- Case-insensitive "y/n" prompt to continue or exit

## Compile and run

Prerequisites: a C++ compiler (e.g. `g++`).

```bash
# clone
git clone https://github.com/subhanbhatti50134-jpg/Dice-Rolling-Game.git
cd Dice-Rolling-Game

# compile
g++ "Program Code" -o dice_game

# run
./dice_game
```

Windows (PowerShell):

```powershell
g++ "Program Code" -o dice_game.exe
.\dice_game.exe
```

## Notes

- The source file is named `Program Code` (with a space), so it must be quoted
  when compiling.
- The repository also contains a `README.md` with a short description; this
  file expands it with compile and run instructions.
- Compilation was not tested in this environment; the GitHub Actions workflow
  verifies it builds with `g++`.

## License

This repository does not yet carry an open-source license. See
`LICENSE_DECISION.md` for recommended options.
