# MONTY-HALL-SIMULATION
Python  |  Mini Project  |  A brain teaser probability puzzle

# Motivation
The Monty Hall Problem, a probability puzzle, has been a topic of interest due to potential biases in human decision-making. An automated Python program was developed using Python's built-in random function to eliminate unpredictability and ensure fair simulation. The project aims to demonstrate automation's advantages in probability-based scenarios and emphasize precision and fairness in dealing with random events.

# Introduction
The Monty Hall problem is a brain teaser, in the form of a probability puzzle, loosely based on the American television game show. The problem was originally posed (and solved) in a letter by Steve Selvin to the American Statistician in 1975. It became famous as a question from reader Craig F. Whitaker's letter quoted in Marilyn vos Savant's "Ask Marilyn" column in Parade magazine in 1990:

>Suppose you're on a game show, and you're given the choice of three doors: Behind one door is a car; behind the others, goats. You pick a door, say No. 1, and the host, who knows what's behind the >doors, opens another door, say No. 3, which has a goat. He then says to you, "Do you want to pick door No. 2?" Is it to your advantage to switch your choice?

<p align="center">
  <img src="https://github.com/A-Chandini-Devi/MONTY-HALL-SIMULATION/blob/main/Monty-Hall-Problem-1.jpg" alt="3 Doors with 1 car and 2 goats" width="600" height="400">
</p>

 
Savant suggested that a contestant should switch to the other door to win a car, which has a 2/3 probability of winning under standard assumptions. This probability remains unchanged after the host reveals a goat behind one of the unchosen doors. The probabilities depend on specific assumptions about how the host and contestant choose their doors. Under these conditions, there is more information about doors 2 and 3 than when door 1 was chosen. Switching doors is different from choosing between two remaining doors at random, as the former uses previous information. Despite explanations, simulations, and formal mathematical proofs, many people still rejected her explanation. The Monty Hall problem is a veridical paradox, related to the Three Prisoners problem and Bertrand's box paradox.


# Paradox
The probability of winning a car after switching is 2/3 under standard assumptions, focusing on the host's behavior. The host must open a door not picked by the contestant, reveal a goat, and offer the chance to switch between doors. Variations in these assumptions can change the probability of winning by switching doors. The car is assumed to be randomly hidden behind doors.

# Counter Solution
The car race game involves two unchosen doors and one car. A player who stays with their initial choice wins in one out of three equally likely possibilities, while a player who switches wins in two out of three. The switching strategy depends on whether the contestant initially chose a goat (2 out of 3 doors) or the car (1/3) probability. The game's probability depends on the player's initial choice, and the door opened depends on the player's initial choice. There is a 1/3 probability that the car is behind each door before the host opens a door. If the car is behind door 1, the host must open door 3, but if it's behind door 1, the host can open either door.

Then the possible outcomes can be seen in this table:
<p align="center">
  <img src="https://github.com/A-Chandini-Devi/MONTY-HALL-SIMULATION/blob/main/Montey%20Hall%20Problem3.png" alt="Possible outcome table refer wikipedia" width="800" height="100">
</p>

In two out of three cases, changing your selection after one door is revealed increases your chances of winning. This is because there is a higher probability of choosing a door with a goat behind it in the first go, and Monty is guaranteed to reveal another door with a goat behind it.
<p align="center">
  <img src="https://github.com/A-Chandini-Devi/MONTY-HALL-SIMULATION/blob/main/Montey%20Hall%20Problem4.png" alt="Possible outcome Flowchart explained" width="700" height="700">
</p>

When the contestant sticks to his/her first choice his/her chances of wining is (33%) - 3 WINS out of 9 chances	whereas when he/she switches the choice the Win percentage is **(66%)** - 6 WINS out of 9 chances.

# Conclution
The solution is that **switching - 66%** will let you win twice as often as sticking with the original choice, a result that seems counterintuitive to many. The Monty Hall problem famously embarrassed a large number of mathematicians with doctorate degrees when they attempted to "correct" Marilyn vos Savant's solution in a column in Parade Magazine.

