# Neo-Mancala

My first substantial solo project: a console game based off of the ancient board game of Mancala, with a twist. I created it my first semester as a CS student.

It's rough and tumble, the code isn't as clean as the code I write today, but it works. I would say this is the project that made me fall in love with programming. Being able to brute-force a game into existence gave me a lot of confidence.

<p align="center"><img width="457" alt="Neo-Mancala" src="https://user-images.githubusercontent.com/44475953/59811696-f3e83100-92bf-11e9-8a39-d6a9298c1993.png"></p>

There are two players. You (Player 1) and Gerty (Player 2). 

*(Yes, named after the computer character, GERTY, from Moon :) )*

Gerty is a computer player, but don't be alarmed. He is smart, but predictable.

Each square on the board represents a selectable position. Each rectangle represents an end zone.

The position numbers (1 - 10) can be seen in the Position Key to the right of the board.

Your (Player 1)'s end zone is on the right. Gerty (Player 2)'s end zone is on the left.

The number inside of the square or rectangle represents the number of marbles there.  

The goal is to get as many marbles as possible into your end zone.

On your turn, select a position with marbles in it. 

All of the marbles will be taken out of that position, and they will move along the numerical path outlined in the Position Key.

One (1) Marble will be dropped in each position passed until all the marbles have been dropped.

* If a player passes their opponent's end zone, it is skipped and no marble is dropped.
* If a player passes over their OWN end zone, a marble is dropped.
* If a player finishes their turn by dropping a marble in their end zone, they get another turn.

The game ends when a player has 5 marbles in their end zone.

At that point, the marbles remaining in the 4 right-hand holes will go into Player 1's end zone on the right.

The marbles remaining in the 4 left-hand holes will go into Player 2's end zone on the left. 

The Player whose end zone has the most marbles at the end, wins.

Ready, Player One?!
