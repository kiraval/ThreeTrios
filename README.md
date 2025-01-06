# ThreeTrios
The game Three Trios is played by two players using a standard cell grid and personalized cards. It is an adaptation of Triple Triad, an old card game. Each player is dealt a hand of cards and is either red or blue. To start the game, each participant is dealt an equal number of cards from a deck of cards. Additionally, there are no cards on the grid at the beginning. Although our grid will be rectangular in our game, its size, and contents can be changed via a file. In our game, an odd number of card cells is required for a grid to be valid.  
  
Player Red goes first. Each round has two phases: the placing phase and the battle phase, in that sequence. During the placing phase, the current turn player (say, player A) places a card in an empty cell. During the battle phase, the newly placed card battles the neighboring cards of the opposing player (say, player B). Any of player B's cards that lose during the battle phase are turned. This implies they become player A's cards while remaining on the grid. After the battle phase, the turn is passed to the other player.  
  
The game ends when all of the empty card cells have been filled. The winner is determined by counting the number of cards each player has on the grid and in their hands. The player who owns the most cards wins. If no such player exists, the game is tied.

## Starting the game
With the resources zip unzipped in the same location as the jar file, you can run the following command in terminal:  
`java -jar ThreeTrios.jar [player type] [player type]`  
**Player Types**: `human`, `ai`  
If the player type is `ai` then you must follow it with one of the following game strategies:  
`maxflip` - Chooses the move that will flip the most cards  
`corner` - picks the right uppermost corner of the board
