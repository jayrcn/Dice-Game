# Dice-Game

Rules In Hog:<br> 

Two players alternate turns trying to be the first to end a turn with at least GOAL total points, where GOAL defaults to 100. On each turn, the current player chooses some number of dice to roll, up to 10. That player's score for the turn is the sum of the dice outcomes. However, a player who rolls too many dice, has these potential risks in the game, these are the special rules:<br>

<ol>

<li> Sow Sad. If any of the dice outcomes is a 1, the current player's score for the turn is 1.</li><br>

<li>Boar Brawl. A player who rolls zero dice scores three times the absolute difference between the tens digit of the opponent’s score and the ones digit of the current player’s score, or 1, whichever is higher. The ones digit refers to the rightmost digit and the tens digit refers to the second-rightmost digit.</li><br>

<li>Fuzzy Factors. A fuzzy number is any number n where the greatest common divisor (GCD) of n and 100 is greater than 10. Recall that the GCD of a and b is the largest factor that is shared between both numbers (for example, the GCD of 10 and 15 is 5). After a player gains points for their turn, if their resulting score is a fuzzy number, add two times the tens digit of the GCD to the player's score.</li>

</ol> <br>


<b>Special Note: The folder has ALL the files including the miscellaneous ones, the ones that are show outside the folder are the same ones in the folder but, those files are the "main" ones, the one that has the code of all the functions to better see what files are the backbone of this project!</b>
