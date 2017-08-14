# Deck Builder (!deck)

The !deck command helps you organize your Clash Royale decks.

## Displaying a deck
Create an image of the deck with the 8 cards followed by a name surrounded in quotes. If no name is entered, the deck will be named simply as *Deck*.

`!deck get 3M knight log pump miner ig is skeletons "3M Cycle"`

![Getting a deck](https://raw.githubusercontent.com/smlbiobot/SML-Cogs/master/wiki/img/deck/deck-get.png)

## Saving a deck
Using the `!deck get` command will only display the deck. To actually save the deck to your personal collection, use the `!deck add` command.

`!deck add 3M knight log pump miner ig is skeletons "3M Cycle"`

![Adding a deck](https://raw.githubusercontent.com/smlbiobot/SML-Cogs/master/wiki/img/deck/deck-add.png)

As a default, you can store up to 5 decks in your personal collection on each server, but this setting can be changed by the admin (TODO).

## Listing saved decks
To display your stored decks, use the `!deck list` command.

`!deck list`

![Deck List output](https://raw.githubusercontent.com/smlbiobot/SML-Cogs/master/wiki/img/deck/deck-list-sml.png)

## Listing saved decks by another user

To list the decks added by another user, add that as the last parameter.

`!deck list @6John`

![Deck list another user](https://raw.githubusercontent.com/smlbiobot/SML-Cogs/master/wiki/img/deck/deck-list-6john.png)

## Renaming a deck

To rename a deck, you must know the deck_id, which is the number associated with a deck when you run the `!deck list` command. Multi-word names with spaces should be surrounded in quotes.

`!deck rename 1 "3M Minions Cycle`

![Renaming decks](https://raw.githubusercontent.com/smlbiobot/SML-Cogs/master/wiki/img/deck/deck-rename.png)

## Search for a deck

You can search for decks with a specifc card.

`!deck search bandit`

![Deck search bandit](https://raw.githubusercontent.com/smlbiobot/SML-Cogs/master/wiki/img/deck/deck-search-bandit.png)

You can search for multiple cards by adding more cards to your command.

`!deck search giant gy`

![Deck search giant graveyard](https://raw.githubusercontent.com/smlbiobot/SML-Cogs/master/wiki/img/deck/deck-search-giant-gy.png)

Search results are paginated as lists of 3. To continue to see results, type _y_ before the timeout. Timeout is set to 15 seconds by default, but can be changed by server admin (TODO).

## Acceptable card names

`!deck cards` will list all the acceptable card names and abbreviations.

![Deck cards](https://raw.githubusercontent.com/smlbiobot/SML-Cogs/master/wiki/img/deck/deck-cards.png)

## Help

You can also use `!deck` without any subcommand to see the built-in list of acceptable subcommands.

![Deck](https://raw.githubusercontent.com/smlbiobot/SML-Cogs/master/wiki/img/deck/deck.png)
