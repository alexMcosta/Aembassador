# Aembassador

An AI that plays Keyforge Decks X amount of times to see who has the highest chance of winning according to an AI.

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
4. Assess your situation same as oppenents to come up with an aggression focus.
    - Agression Focus is the rating that you will give to the following areas
    - Aember Gaining - What is the maximum amount of Aember I can gain this turn?
    - Aember Control - What is the most Aember I can take from my opponent? Or the highest I can make their keys cost?
    - Board Gaining - Should I Dominate the board?
    - Board Control - Is their board out of control?


## Situation Flags
Do to the nature of card games, cards can affect the rules of the game. We will need to make flags that alter this games vacuumed reality. Such things as Miasma making a player unable to forge a key regardless of their amount of aember or Archimedes making its neighbors archive when destroyed. Each card that has the ability to change the rules of the game will add its situation flag to a pool that each action will check. Some cards affects will add situation flags to your opponents pool. Such as the cards that make it so if your opponents creature reaps it gets stunned.


