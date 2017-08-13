# Members

A number of bot commands were written specifically for the RACF Discord server.

## Change clan (!changeclan)

Used when you change from one RACF clan to another. Syntax:

`!changeclan Alpha`

`!changeclan Delta`

The *eSports* role require leader approval and as such is not supported by this command. If you got accepted into Alpha eSports, please contact one of the leaders (Slayer / Xhadian / SaintBelekin) to update your roles.

## Toggle role (!togglerole)

A number of roles are self-assignable / self-removable by members. Syntax:

`!togglerole Heist`

`!togglerole Practice`

* **Heist. **Used to play the game !heist in #casino. Mentionable. (Default: disabled)
* **Practice. **Used for weekly practice. Self-assign in order to see the #practice channel as well as notifications and info for practice sessions. (Default: enabled)
* **Tourney.** Used for tournament notification. Self-assign in order to get notifications for tournaments. Mention the role to alert others with tournament information, e.g. `@Tourney Name: Awesome Tournament / Password: AwesomePass / 10k gem 1000-player x2000 cards` (Default: enabled)
* **Recruit.** Self-assign to see recruiting information about Alpha eSports. (Default: disabled)

## Clash Royale Data (!crdata)

Real-time data from the Global 200 Leaderboard. Data updated hourly.

### Leaderboard

To see the leaderboard ordered by rank:

`!crdata leaderboard`

`!crdata lb`

### Decks

To see popular decks ordered by usage:

`!crdata decks`

### Cards

To see popular cards ordered by usage:

`!crdata cards`

### Search

To search decks on the leaderboard ordered by rank:

`!crdata search hog` (one card)

`!crdata search hog log barrel` (multiple cards)

`!crdata search hog log -barrel` (multiple cards and exclude some cards)

`!crdata search hog is elixir=0-3` (multiple cards with elixir range)

`!crdata search 3m hog -br elixir=2-4` (Find 3M Hog decks without battle ram between 2 and 4 elixir)

### Similar decks

Find similar decks by supplying a list of cards:

`!crdata similar hog log barrel gg skarmy princess it knight`

Find decks that are similar to the 2nd deck on Global 200 leaderboard:

`!crdata similar 2`

## Deck Builder (!deck)

The !deck command helps you organize your Clash Royale decks.

Full illustrated guide: [https://github.com/smlbiobot/SML-Cogs/wiki/Deck](https://github.com/smlbiobot/SML-Cogs/wiki/Deck)

### Deck Image

To get an image of the deck, type:

`!deck get 3M EB MM IG knight IS zap pump`

To optionally add a name to your deck, type:

`!deck get 3M EB MM IG knight IS zap pump "3M Ebarbs"`

### Card Names

You can type the card names in full or use abbreviations. Common abbreviations have been added. For the full list of available cards and acceptable abbreviations, type `!deck cards`

### Database

You can save your decks. To add a deck to your personal collection, type:

`!deck add 3M EB MM IG knight IS zap pump "3M Ebarbs"`

You can have up to 5 decks in your personal collection.

### List

To see the decks you have added, type `!deck list`

To see the decks that others have added, type `!deck list <username>`

### Rename

To rename a deck, type `!deck rename \[deck_id\] \[new_name\]`where deck_id is the number on your list, and new_name is the new name, obviously.

Remember to quote the name if you want it to contain spaces.

### Remove

To remove a deck, type `!deck remove \[deck_id `  where deck_id is the number on your deck list.

### Search

To search for a deck containing specific cards, type `!deck search miner`. To search for multiple card matches, type `!deck search miner princess`.

## Pay (!pay)

Transfer credits to one or more people. Divide credits equally if multiple users are specified. Since credits can only be integers, there will be some rounding errors.

`!pay 50 SML`

`!pay 100 SML 6John Meridian`

## Rules + Roles (!racf)

This displays links to the RACF rules, roles, and discord invite link.

## Farmers (!farmers)

This fetches the Farmers data from Nuclino and display in the Discord chat as a table. A newer version will store data as JSON on the server, but this is a work-around in the meanwhile.

Type `!farmers` to show the latest farmers.

Type `!farmers 2` to show the farmers on Week 2 since we started recording data.
