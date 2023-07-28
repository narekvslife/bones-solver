## Rules 

- Players take turns rolling 5 dice
- It is allowed to to rerol a subset of the dice up to two times
- Fixed number of rounds equal to the number of scoring combinations
- You can also get negative points 
- Two stages to this game. 
	- During the first stage players choose which combination they want to score.
	- During the second stage, combinations go in the order of the table.

## Table of combinations

- 1: (#number_of_dice_with_value_1 - 3) * 1
- ...
- 6: (#number_of_dice_with_value_6 - 3) * 6
- pair: sum of a pair
- 2+2: sum of two pairs (not kare)
- set: sum of 3 dice of the same value
- four of a kind (каре): sum of 4 dice of the same value
- 3+2: sum of a set and a pair (not poker)
- street: 1-5 20pts
- avenue: 2-6 25pts
- poker: 5 of a kind 50pts 
- sum: sum of all dice on the table
- max: value of max dice value on the table
- min: value of min dice value on the table

plus: you get 130pts for scoring >= across the 1-6 fields

## Formalization

We have:

- Rounds (17 + 17)
- Players
- Combinations

In the beginning of each player's turn she *has to* roll all five of the dice.
This gives us a starting point.

## Q&A

- Q: Does optimal strategy depend on the scores of other players?
  A: Looks like it should, becausethe goal is not to get the maximum value but rather to get more than everyone elsew.
- Q: Does greedy work here?

