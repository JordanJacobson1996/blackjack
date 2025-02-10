Blackjack
Objective: Beat the dealers hand without going over 21.

Card values:
- 2 through 10 is face value.
- Jack, Queen and King: 10 points.
- Ace: 1 or 11 up to the player.

1. Deck is shuffled.
2. All players make a bet before the start of a round. This is the buy in or minimum bet.
3. Dealer gives a card to each player as well as themselves. The dealers first card is face down.
4. Dealer deals a second card to each player; dealers second card is face up.
5. The player decides, stay or hit:
	Staying means dealer will not give the player another card.
	Hitting means the dealer adds another card to the players hand. Hitting can be done as many times as needed or until the hand is more than 21.
6. Once players have all stayed, the dealer reveals their original card and the card total.
	If hand is 16 or lower, they hit. 17  or over they stay.
7. Bets are paid out:
	If player won, because their hand was higher than the dealer they get paid out in a one to fashion. If one 	chip was bet, they get their original chip plus another one back.
	If player got a blackjack (21), they get paid out in a 3:2 ratio. If two chips were bet, they get 3 back 	(leaving a total of 5).
8. The deck is shuffled and the next round starts.
#####################################################################################################################
- Create a text based blackjack game.
- One player vs automated dealer.
- Player can stand or hit.
- Player can pick betting amount.
- Keep track of players money.
- Alert player to wins, losses or busts.

Classes:
- Deck class
	Attributes:
		List of all cards
	Methods:
		Shuffle
		Deal
- Card class
	Attributes:
		Suit
		Rank (string)
		Value
	Methods:
		__str__ method
- Player class
	Attributes
		Hand
		Money
		hand_value
	Methods:
		Add cards
		Bet
		Stay or hit
	
- Dealer class
	Attributes:
		Dealer hand
		Hand_value
	Methods:
		

