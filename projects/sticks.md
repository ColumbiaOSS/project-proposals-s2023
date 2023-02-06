# Sticks

Sticks is a simple two-player game where the objective of the game is to
have your opponent run out of moves.

# How To Play

* Players start with two hands with one stick in each one.
* First player's turn is decided on a coin toss.
* The first player then HAS to select one of their hands and "touch" the other player's
hand.
* The opposite player then adds the number of sticks their opponent had to theirs.
  * Say P1 had two sticks in the hand that touched one of P2's hand, suppose
they had one stick, P2 would then have three sticks in that hand.
  * If P1 has four and P2 has three, then you add those two values and mod that
  value by 5. (i.e. (4 + 3) % 5 == 7 % 5 == 2 )
* After the first turn has happened, either player can choose to either "touch"
their opponent with either hand or "swap" sticks in their hand.
  * Say it's P1's turn and they have 2 sticks in their left hand and 4 sticks in
  their right hand. If they so choose, they can "touch" their opponent with either
  hand or they can add/subtract sticks from one hand and add it to the other. In
  the aforementioned example P1 has 2 sticks in one hand and 4 sticks in the other.
  He can choose to not "touch" his opponent and instead move the sticks around his
  hands. That is, he can have 3 sticks in each hand.
* If you have EXACTLY five sticks in one hand then that hand is out and you must
play with the other hand until you either win or lose.
  * However, if one of your hands is still in you can choose to add/subtract from
  your nonempty hand and add it to your empty hand.
  * Say P2 has 3 sticks in one hand and 0 sticks in the other. During his turn
  he can choose to have 1 stick in one hand and 2 sticks in another.
  * The game ends when one of the two players has 0 sticks on BOTH hands.


# Future Features
* Randomized start for both players
* Online connection so that both players can play on their window
* Multiplayer if possible
* Handicap mode for one player
