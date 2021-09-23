# Skyscrapers-Puzzle
Skyscrapers is a building placing puzzle based on an NxN grid with some clues along its sides. The object is to place a skyscraper in each square, with a height between 1 and N, so that no two skyscrapers in a row or column have the same number of floors. In addition, the number of visible skyscrapers, as viewed from the direction of each clue, is equal to the value of the clue. Note that higher skyscrapers block the view of lower skyscrapers located behind them. In the example below we have a 5x5 Skyscrapers puzzle with five columns and five rows. We now need to place 1-floor to 5-floor skyscrapers in each row and column according to the above rules… but how?

Skyscrapers puzzle  Skyscrapers solution
Starting techniques

Skyscrapers puzzles frequently contain the clue 1 and/or clue N which are very easy to start off with. Clue 1 means only the highest skyscraper in the row or column is visible and clue N means all skyscrapers in the row or column are visible:

1. Clues of 1
Clue 1 means only one skyscraper is visible when viewing the row or column from the direction of the clue. Therefore in the example below, the highest skyscraper with 5 floors must be placed next to the clue 1 to block the view of the remaining buildings.

Clues of 1 (A)  Clues of 1 (B)
2. Clues of N
Clue N, in an NxN grid, means all skyscrapers are visible when viewing the row or column from the direction of the clue. Therefore in the example below, the five skyscrapers must be placed in ascending order from the clue 5 so no building gets blocked.

Clues of N (A)  Clues of N (B)
