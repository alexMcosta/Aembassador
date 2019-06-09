# Aembassador

An AI that plays Keyforge Decks X amount of times to see who has the highest chance of winning according to an AI.

## Pre Game
AI Assesses the deck. More brain storrming needed.

## How the AI plays
1. Check to see if it can forge a key
2. Check if it won.
3. Assess opponents situation
    - How many keys do they have?
    - What is their current Key cost?
    - How much Aember do they have?
    - Are they in check?
    - Which key is it?
    - What is the threat level of the board?
4. Assess your situation same as opponents to come up with an aggression focus.
    - Aggression Focus is the rating that you will give to the following areas
    - Aember Gaining - What is the maximum amount of Aember I can gain this turn?
    - Aember Control - What is the most Aember I can take from my opponent? Or the highest I can make their keys cost?
    - Board Gaining - Should I try to dominate the board?
    - Board Control - Do I need to dwindle their board?
    - Assassin mode - Is there an artifact or creature that is such a high threat that it needs to be dealt with more then anything but letting your opponent forge the third key? Is their an answer for it on the board? In your hand? Even in your deck? If there is an answer in your deck would it be best if the deck was cycled through?
5. Go over your hand (and archive) and asses which house would be the best option to choose based on Aggression Focus.
    - Look over known combos in hand and board
    - Look at creatures fight/reap/action abilities to see what their max value is.
    - In some instances it might be worth throwing a good card into an enemy card at a loss based on the situation.



## Situation Flags
Do to the nature of card games, cards can affect the rules of the game. We will need to make flags that alter this games vacuumed reality. Such things as Miasma making a player unable to forge a key regardless of their amount of aember or Archimedes making its neighbors archive when destroyed. Each card that has the ability to change the rules of the game will add its situation flag to a pool that each action will check. Some cards affects will add situation flags to your opponents pool. Such as the cards that make it so if your opponents creature reaps it gets stunned.


