# Find Your Grind Coding Exercise - C#
## Snap!

This exercise is intended to help us gauge your competency with backend concepts as well as how you design and structure your code. Please use **.Net Core or .Net 5** for this exercise.

Please attempt the following at your own convenience, but please do not spend more than 90 minutes. If you hit 90 minutes and have more to do, please add an **OVERFLOW.md** file with notes on what else you would have included.

Please think of this exercise as your chance to shine, please show off your talents and skills, but please remember the audience. We'd love to see production ready code, but there is no need to add things like monitoring and alerting!

After completing and submitting your exercise, we would love to hear any feedback you may have on this coding exercise!

## The Task!

Write a program that simulates the card game Snap between two computer players.

### Game Setup
Choose a number of packs of [playing cards](https://en.wikipedia.org/wiki/Standard_52-card_deck), and combine them into a single *deck*. Shuffle the deck.

### Playing the game
Cards are played sequentially from the top of the deck into the *pile*.

If two cards played sequentially *match* (see "Match Conditions" below), the first player to declare "Snap!" takes all the cards in the pile. *For the purposes of this simulation, the program should choose a random player as having declared "Snap!" first.*

Play then continues with the next card in the deck, starting a new pile. The game ends when no more cards can be drawn from the deck and no player can declare "Snap!". (Any remaining cards in the pile may be discarded.)

The player that has taken the most cards is the winner. The game can end in a draw.

### Match Conditions
The match condition determines when two cards *match* for the duration of the game. There are three valid options:

 - The **suits** of two cards must match
   - Example: "3 of hearts" and "5 of hearts" match because they are both **hearts**.
 - The **values** of two cards must match
   - Example: "7 of hearts" and "7 of clubs" match because they both have the value **7**.
 - Both **suit and value** must match
   - Example: "Jack of spades" **only matches** another "Jack of spades"

### The program
As input, the program should ask for:

1. How many packs of cards to use for the deck
1. Which *Match Condition* to use

It should then simulate the game and declare either the winning player, or a draw.
