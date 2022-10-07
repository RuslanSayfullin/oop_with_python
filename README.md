# oop_with_python
Master OOP by Building Games and GUIs.  This repository is about a software development technique called 
object-oriented programming (OOP) and how it can be used with Python.

Chapter 1. PROCEDURAL PYTHON EXAMPLES
========================================================================================================================

Higher or Lower Card Game
My first example is a simple card game called Higher or Lower. In this
game, eight cards are randomly chosen from a deck. The first card is shown
face up. The game asks the player to predict whether the next card in the
selection will have a higher or lower value than the currently showing card.
For example, say the card that’s shown is a 3. The player chooses “higher,”
and the next card is shown. If that card has a higher value, the player is
correct. In this example, if the player had chosen “lower,” they would have
been incorrect.
If the player guesses correctly, they get 20 points. If they choose
incorrectly, they lose 15 points. If the next card to be turned over has the
same value as theHigherOrLowerProcedural.py previous card, the player is incorrect.
Code: HigherOrLowerProcedural.py

Bank Account Simulations
In this second example of procedural coding, I’ll present a number of
variations of a program that simulates running a bank. In each new version
of the program, I’ll add more functionality. Note that these programs are not
production-ready; invalid user entries or misuse will lead to errors. The
intent is to have you focus on how the code interacts with the data
associated with one or more bank accounts.
To start, consider what operations a client would want to do with a bank
account and what data would be needed to represent an account.
Code: Bank1_OneAccount.py