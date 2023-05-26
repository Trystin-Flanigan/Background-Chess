# Phase 0: Analysis
---
### Goals:
- Learn the Rust Programming Language
- Learn Min/Max + Alpha Beta Algorithms
- Create a simple chess AI
    - Todo: Evaluate level of difficulty
        - Smarter Moves vs. Better Performance
        - Does the bot NEED to be smart when only playing against itself?
        - How intelligent am **I** personally capable of making the AI?
        - Should there be variable difficulty settings?
    - AI should rank its moves and try to choose its best options
    - AI should understand general chess rules, how pieces move, check/checkmates, pawns can become other pieces if they reach the end of the board, castling, etc, as well as *following* these rules
    - AI should be able to play against itself
    - AI should **NOT** significantly impact performance, with the purpose being to run this in the background we must ensure it does not use excessive resources
    - Configurable speed settings, varying from a reasonably paced chess game to comically fast (if possible)
- Create a chess board that can be displayed in the terminal
    - Find a way to make sure the output doesn't obnoxiously flood your terminal
    - Coordinate grid for play space (A1, B5, etc)
    - Unicode symbols for chess pieces? ~~apparently thats a thing?~~
- Allow a human player to play against the AI if they so please
    - Program should be able to handle unexpected / incorrect input
    - Human player can choose whether they'd like to play black or white
    - Human player chooses their move by declaring what they'd like to move where (D5 -> D6)
    - Human player should not be allowed to make illegal moves (putting king in check, trying to move in a way that isn't possible, etc)
    - Human should be able to either conceede if they'd like to give up and begin another game, this should be separate from just restarting the program again
- Gameplay elements
    - Checkmate detection
    - Prevent illegal moves

