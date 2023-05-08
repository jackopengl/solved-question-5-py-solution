Download Link: https://assignmentchef.com/product/solved-question-5-py-solution
<br>
5/5 - (2 votes)

Assume a sport in which two players (A and B) score points and the winner is a player who has at least 4 points and wins by at least 2 points.

Write function point() that prompts the user for a player who wins a point and returns “A” if player A wins, “B” if player B wins, and ”Q” if the user quits the game.

Write function game() that keeps the score in the game and prints the winner of the game.

Write function display() that prints the current score in accordance with tennis rules for a game.

Function main() just calls function game().

More Explanation:

Function point() Prompts the user for the player who wins a point.

The function:

• Returns “A” if the user enters “A” or “a” to indicate that player A wins.

• Returns “B” if the user enters “B” or “b” to indicate that player B wins.

• Returns “Q” if the user enters “Q” or “q” to quit the program.

• Returns “E” if user enters anything else.

Function game() Uses indefinite (while) loop until the game is finished or the user quits.  In each iteration of the loop:

• Calls function point() to get input from the user.

• Increments score of the player A if point() returns “A”.

• Increments score of player B if point() returns “B”.

• Quits the program if point() returns “Q”.

• Prints error message if point() returns “E”.

• If the game is over, prints the winner and returns to main(), which terminates the program.

• Calls function display() to print the score of the game.

Game is over and the winner is a player who has at least 4 points and wins by 2 points.

Function display(scoreA,scoreB)

Input are scores (positive integers) of the player A and B.

Mapping of the first 3 points to displayed values:

0 point displayed as 0

1 point displayed as 15

2 points displayed as 30

3 points displayed as 40

Deuce means that both players have at least 3 points and same number of points.

Deuce is displayed as 40 for both players.

After a deuce, the score for the player who has 1 more point is displayed as “Adv” and the score of the other players as “ “ (empty string).

Function main() just calls function game().

Sample printouts:

The program keeps a score and prints winner in a tennis game.

Who wins a point, player A or player B?  A

Score of Player A: 15

Score of Player B: 0

Who wins a point, player A or player B?  b

Score of Player A: 15

Score of Player B: 15

Who wins a point, player A or player B?  C

Invalid input. Please enter A, B or Q (to quit).

Score of Player A: 15

Score of Player B: 15

Who wins a point, player A or player B?  a

Score of Player A: 30

Score of Player B: 15

Who wins a point, player A or player B?  q

You quit the game.

Who wins a point, player A or player B?  a

Score of Player A: 15

Score of Player B: 0

Who wins a point, player A or player B?  A

Score of Player A: 30

Score of Player B: 0

Who wins a point, player A or player B?  b

Score of Player A: 30

Score of Player B: 15

Who wins a point, player A or player B?  b

Score of Player A: 30

Score of Player B: 30

Who wins a point, player A or player B?  a

Score of Player A: 40

Score of Player B: 30

Who wins a point, player A or player B?  b

Score of Player A: 40

Score of Player B: 40

Who wins a point, player A or player B?  a

Score of Player A: Adv

Score of Player B:

Who wins a point, player A or player B?  b

Score of Player A: 40

Score of Player B: 40

Who wins a point, player A or player B?  b

Score of Player A:

Score of Player B: Adv

Who wins a point, player A or player B?  b

Player B wins the game

contact : <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="ea8b8481839e89858e83848daa8d878b8386c4898587">[email protected]</a> for other module and project solutions