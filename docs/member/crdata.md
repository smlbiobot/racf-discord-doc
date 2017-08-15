# Clash Royale Data

Real-time data from the Global 200 Leaderboard. Data updated hourly.

```
!crdata
!crdatae
```

Subcommand | Description
--- | ---
cards | Popular cards ordered by usage
decks | Cards decks ordered by usage
leaderboard | Leaderboard ordered by rank
search | Search decks by card inclusion, exclusion and elixir range
Similar | Similarity search

## !crdata vs !crdatae

`!crdata` and `!crdatae` are sister commands. `!crdata` will display 3 decks at a time while `!crdatae` will display 10 decks on each page. The main difference is that `!crdata` will show a single image which you can save to your device while `!crdatae` displays the deck results as emojis so they load faster.

<img src="img/crdata-search.png" />

<img src="img/crdatae-search.png" />

## Leaderboard

To see the leaderboard ordered by rank:

`!crdata leaderboard`

`!crdata lb`

## Decks

To see popular decks ordered by usage:

`!crdata decks`

## Cards

To see popular cards ordered by usage:

`!crdata cards`

## Search

To search decks on the leaderboard ordered by rank:

Example | Description
--- | ---
`!crdata search hog` | one card
`!crdata search hog log barrel` | multiple cards
`!crdata search hog log -barrel` | multiple cards and exclude some cards
`!crdata search hog is elixir=0-3` | multiple cards with elixir range
`!crdata search 3m hog -br elixir=2-4` | Find 3M Hog decks without battle ram between 2 and 4 elixir

## Similar decks

Find similar decks by supplying a list of cards:

`!crdata similar hog log barrel gg skarmy princess it knight`

Find decks that are similar to the 2nd deck on Global 200 leaderboard:

`!crdata similar 2`
