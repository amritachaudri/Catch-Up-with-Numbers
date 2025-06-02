# Catch-Up-with-Numbers

Rules of the Game
 1. Two players take turns at choosing numbers from the set of natural numbers, {1, 2, 3, …, n}. The highest 
natural number n in this set is agreed on before the game. Once a number has been chosen, it is deleted from 
the set and cannot be chosen again.
 2. Call the player to make the first move P1, and the second player P2. I will refer to them both as "it". At the 
outset, P1 chooses one of the n original numbers.
 3. Thereafter, P1 and P2 successively choose one or more of the remaining numbers, but each must stop—and 
turn play over to the other player—when the sum of its choices up to that point equals or just exceeds its 
opponent's previous sum.
 4. The goal of the players is to have a higher sum than an opponent at the end of play— and by as much as 
possible—or that failing, to have the same sum. If neither of these goals is achievable, a player prefers to lose 
by as small amount as possible.
 5. The game ends when all numbers have been chosen. If one player has a higher sum than the other, that player 
wins. If not the game ends in a tie.
 For example, assume n=5, so the numbers at the start are {1, 2, 3, 4, 5}. Sample choices of players are as below:
 P1's first choice: P1 chooses one of the 5 numbers at random. Each number has the same probability of being 
chosen. P2's first choice: For purposes of illustration, assume that P1 chooses {3}. Then there are eight possible 
subsets of the remaining numbers whose sum equals or exceeds 3: {4}, {5}, {1, 2}, {1, 4}, {1, 5}, {2, 1}, {2, 4}, {2, 
5}
 P2 chooses one of these possibilities at random. Again, all possibilities have an equal probability of being picked. 
In six of these cases, the subsets comprise two numbers, wherein the first number—either 1 or 2—is less than 3, 
so a second number (the second number in each subset) is needed to make the sum for P2 equal to or greater 
than 3. After P2 chooses one of the eight subsets at random, either two or three numbers remain.
 P1's second choice: P1 will choose again, and at random, a subset of the remaining numbers such that, when they 
are added to P1's present score of 3, equals or exceeds P2's score. Depending on the numbers that P1 chooses 
when it makes a second choice, P2 may or may not have a second choice that equals or exceeds P1's last total.
 In summary, when a player randomises, it chooses with equal probability any of the subsets of available numbers 
that equal or exceed an opponent's last total
