# Analyzer Planning

In order for the Analyzer to work as a whole we will need the following to happen:

1. We will need to be able to import a deck. Which going off other Keyforge decks entering the hyperlink of the deck from the [Master Vault](keyforgegame.com) and scrapping the data from that endpoint will be the best way to go.

2. We will need to design the database for high read and put since there will be a bunch of uploaded decks as well as a bunch of reads to gather cards. Ideas for tables are as follows:
    - Card Table: This table will hold all the cards... duh. it will include the cards rating and favor of the the 4 different deck play styles, mechanics, and any situation flags the card causes. As well as name, power. Need to brainstorm how to handle legacy and mavrick cards.
    - Deck Table: This will be all the uploaded decks. It will include name, who it belongs too, rating, wins, losses, deck type rating for each deck play style, and combos.
    - Combo Table: This will be a table that hols all known combos. Joining cards together.
    - User Table: this will connect users to decks. 