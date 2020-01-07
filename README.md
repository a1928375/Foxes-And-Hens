# Foxes-And-Hens

This problem deals with the one-player game foxes_and_hens. This game is played with a deck of cards in which each card is labelled as a hen 'H', or a fox 'F'. 

A player will flip over a random card. If that card is a hen, it is added to the yard. If it is a fox, all of the hens currently in the yard are removed.

Before drawing a card, the player has the choice of two actions, 'gather' or 'wait'. If the player gathers, she collects all the hens in the yard and adds them to her score. The drawn card is discarded. If the player waits, she sees the next card. 

Your job is to define two functions. The first is do(action, state), where action is either 'gather' or 'wait' and state is a tuple of (score, yard, cards). This function should return a new state with one less card and the yard and score properly updated.

The second function you define, strategy(state), should return an action based on the state. This strategy should average at least 1.5 more points than the take5 strategy.
