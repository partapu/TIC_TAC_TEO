# TIC_TAC_TEO
Model predicts the winning of person in the game tic_tac_teo based on his moves in the game.
The size of dataset is 959 * 10 (rows and columns)
The columns are and their lables:
TL-TOP LEFT      (x,o,b)
TM-TOP MIDDLE    (x,o,b)
TR-TOP RIGHT     (x,o,b)
ML-MIDDLE LEFT   (x,o,b)
MM-MIDDLE MIDDLE (x,o,b)
MR-MIDDLE RIHGT  (x,o,b)
BL-BOTTOM LEFT   (x,o,b)
BM-BOTTOM MIDDLE (x,o,b)
BR-BOTTOM RIGHT  (x,o,b)
CLASS            (TRUE,FALSE)
class is a target variable which predicts whether the player will wins the match or losses the match.
dataset is clean and have no missing values in it.
The model trained is classifier.
I used KNN which gives more accuracy compared to other classifiers.
