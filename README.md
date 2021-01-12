# PedacHW

// The purpose of this homework is to get a further understanding of the PEDAC method.

- P: Problem - Understanding the problem. Be specific.
- E: Examples - Give as many examples as you can. Generate examples and find new examples.
- D: Data Structure - Type of input and outputs. Local info. Can we convert data points?
- A: Algorithm - Most important. A formal set of step by step instructions for solving the problem. Pseudo Code.
- C: Code - The code that will be written.

// Problem:

- Take 20 cards that are not in numerical order and put them into numerical order.
- Can only look at 2 at a time
- You may only swap the position of TWO cards (that you have turned over) at any time
- You may only refer to cards based on their position in your list (left-to-right).
- You may NOT keep track of the value of any cards in any manner other than by turning over TWO cards and considering their value. For instance, you may not "remember" any values, or write down their values elsewhere, etc.

//Example:

- Take cards and put them into numerical order 1,2,3,4,5,6 etc... Playing cards Ace of Hearts, Two of Hearts, Three of Hearts etc...

//Data Structure:

- The input will be mixed up shuffled cards and the output will be cards that are in numerical order.

//Algorithm:

- If you are not using a deck of playing cards, take 20 note cards and label each card, on one side of them 1 through 20.
- Shuffle the cards and mix them up so they are not in any order.
- Lay out the cards beside each other in one row, facedown with a little space in between each card.
- Take two cards at random from the row of cards and flip them over so they are face up with the value showing.
- If the flipped cards value on the right is less than the flipped cards value on the left.
- Swap the cards.
- If the flipped card on the right's value is higher than the flipped cards value on the left.
- Do not swap them and turn them back over so the blank side is showing.
- When you swap the cards positions turn them back facedown.
- Do not try and remember the cards values and positions.
- Choose two more cards at random to turn over, face up.
- Repeat this process until all of the cards are in order from lowest value to highest value, left to right.

//Code:
