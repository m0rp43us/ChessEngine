Writing a chess engine in python to get familiar behind the CS side of chess.
following Eddie's livecoding : [Youtube playlist](https://www.youtube.com/playlist?list=PLBwF487qi8MGU81nDGaeNE1EnNEPYWKY_)

will improve on the code and add some puzzles and openings,base code found here : https://github.com/mikolaj-skrzypczak/chess-engine

---------------------------------------------------------------------------------------------------------------------------------

After some deep thoughts i figured out to just write the whole project in Node.js and make it serve both as an API and a WS server.

possible features are :

- chess puzzles
- Guessing the opening
- Learning Openings
- Elo rating
- Leaderboard
- Maybe playing against the time and an opponent (chezz puzzles and openings)
- playing against the same ELO rated bot (maybe maia : https://maiachess.com/)

## update 09/03/2023

building a puzzles DB through a scrapper and lichess puzzles db 

lichess puzzles db can be found here : https://database.lichess.org/#puzzles

code that i wrote to put a mongodb : https://github.com/m0rp43us/chess_db
