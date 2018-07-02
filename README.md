# poker_game
# I made a blackjack game and started by establishng the suits and card types and importing a shuffle function
# I made my deck with the make_deck() function 
#
# In card_value, I tried to establish the ranks of the cards but I am not sure it worked well.
#
# In the aces function, I tried to establish the ace card function and how it switches between 1 and 11 by setting up a trump card. If the value is less than 21, the program breaks.
# 
# player_in establishes whether the player has busted yet with a boolean
#
# Then I get into the hit versus draw function. If the player inputs 1, player_in = True and gets another card. If the player input 2, player_in = False. I use the append function which adds an element to the end of the player_hand function when implemented
#
# I set the player_score_label and the player_score both equal to the player's hand_value, then do the same thing with the dealer
#
# I tried to use % to input the dealer's hand into the dealer_hand_string. If the player_score is > 21, the dealer wins.
#
# If the dealer's hand is < 17 they have to hit. Then the dealer_score_label and dealer_score is set equal to the dealer's hand value again
#
# The last function decides the winner. If the player_score is less than 100 and the dealer_score is equal to 100, the player wins. If the player_score is greater than the dealer_score, the player also wins. If the scores are the same, it is a tie. Else, the dealer wins.
