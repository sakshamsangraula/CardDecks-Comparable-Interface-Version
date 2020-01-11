# CardDecks-Comparable-Interface-Version

This is the Interface version of the CardDecks project where the Comparable Interface is used. The Card class implements the Comparable Interface and overrides the compareTo method. It takes care of the exceptions (when comparing "K" and "Q" it should return a positive number- a string compareTo method would return a negative number) and returns the integer value of comparing the faces of 2 cards. 

The Dealer and Player classes both use the compareTo method to insert the cards in descending order. 

Programming Concepts: Interface(Comparable Interface), Overriding functions


The overview of the CardDecks project is below:

This is the Object-Oriented programming version of the CardDecks class. There are 3 classes: Card, Deck, and Main.

The Deck class creates new cards objects by calling the constructor of the Card class. Then it creates a deck of cards by adding all the cards to the deck ArrayList, shuffles all the cards, and implements the dealCards method which will remove numCards number of different cards from the original ArrayList and returns a new ArrayList with the the numCards number of cards(here numCards is 5).

The Main class prints out the deck before and after shuffling the cards. Then, it calls the dealCards method and prints out the sum of the values of the numCards number of cards and it calls the dealCards method to find sum of another 5 different cards.

The Card class returns the value of the card and it overrides the toString() method from the Object class to return the face and suit of the cards.

Programming Concepts used in this project: Object Oriented Programming concepts- Encapsulation(created 3 different class with their own private instance variables and methods), abstraction(used private identifiers), and Polymorphism(the toString() class of the Object class was overridden by both the Card and Deck class).
