# CardGame-WarGame

For this assignment, we will program a variation of the card game called WAR using the Stack
structure. The main part of this assignment is the development of the Stack class.

Our WAR game variation

There are two players playing the game. Each of the players are dealt a set of cards (with equal
number of cards) from a shuffled deck of cards. When the game starts, the players open up the top
card. The open cards are compared to see which one is higher. In the comparison, the King card is the
highest while the Ace card is the lowest.
In the event of a tie, the suit of the card will determine the winner of the match. The suits are ranked as
follows (from the highest suit rank): Spades, Hearts, Diamonds, Clubs. The suit with the higher rank
wins. The winner of the match gets a point. Note that there will always be a winner in a match.
The game continues until all the player cards have been played and the player with the higher score
wins the war.

Developing the Game

Before the game can be developed, a number of required classes need to be developed.

1. The Card Class
The Card class should describe a specific card, ie., the Ace of Spaces. It should have the usual
getters and setters and any addditional methods that will be needed to determine the outcome of
the card match.

2. The CardDeck Class
The CardDeck class contains the standard deck of 52 cards (4 suits with each suit containing 13
different ranks of cards). To hold the cards, you must use a generic DoublyLinkedList
structure.
Use this class to initally populate the deck with the 52 cards (much like opening a new deck).
In addition, you can also use this class for the shuffled deck of cards that will be used in the
game.

3. The Shuffler Class
This class is used to shuffle a deck of cards. You will need to use this class before the game
can be started.
You may want to research how to shuffle a deck of cards, using Java. The details of how the
deck is shuffled is left to you. However, what is important here is that the deck of cards are
shuffled and that the results of each shuffle are different.

4. The LinkedList Implementation of the Stack class
For the Stack class you must use the LinkedList Implementation of the Stack structure. This
development is a major component of this assignment. You must create a StackInterface class
as well.

5. The WarGame Class (which is the main processor class)
This is the processor class that actually plays the game. It starts off with getting a deck of
cards, shuffling the deck, and dealing the cards to the players. The number of cards that the
players get is determined by the user of your game.
Once the cards are dealt, then the game begins and scoring is done using the game description
above.

For the game, the shuffled deck, and the cards that the players have, should be implemented
using the LinkedListStack
