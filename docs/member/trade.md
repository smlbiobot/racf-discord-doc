# Trading

A special `!trade` command for members to add trades they have found in the wild.

Do this in `#trade-bot-commands` so it stays a members only feature.

- Give: What you are giving out
- Get: What you are getting / what you want
- Clan Tag: The clan tag without the `#` symbol

## List trades

| Command | Role | Description
| --- | --- | --- |
| `!trade list` | MOD | List all trades
| `!trade add` | Member | Add a trade
| `!trade remove` | Member | Remove a trade
| `!trade import` | Member | Import a CSV file containing multiple trades
| `!trade give` | Member | Filter trades by cards to give
| `!trade get` | Member | Filter trades by cards to get
| `!trade rarity` | Member | Filter trades by rarity
| `!trade auto_on` | Admin | Turn on automatic trade listing
| `!trade auto_off` | Admin | Turn off automatic trade listing
| `!trade reset` | Admin | Reset all trades

### Filter by Rarity

`!trade rarity epic`

`!trade r e`

Acceptable values:

- legendary
- epic
- rare
- common

### Filter by Cards

`!trade give nw`

`!trade gv nw`

List all known trades that will accept a Night Witch for trades

`!trade get iwiz`

`!trade gt iwiz`

List all known trades where can give your Ice Wizard to get something back.


!> Adding and removing trades affects the data in the database. If you don’t know what you are doing, don’t run these commands. Adding non-existent trades create headaches for everyone else. Removing trades that actually exists takes away the opportunity to trade from others.

## Adding trades

If you have found a trade in the wild, you can add it to the database by running:

`!trade [add|a] <give> <get> <clan_tag>`

`!trade add nw iwiz C00`

Someone in the clan tagged `C00` is looking for an Ice Wizard in exchange for your Night Witch.

## Removing trades

If you have visited a listed clan and that item is no longer listed, you can remove it by typing:

`!trade [remove|rm|r] <give> <get> <clan_tag>`

`!trade rm nw iwiz C00`

Avoid this step unless you are absolutely sure what you are doing. This is destructive and will remove the entries.

## Adding multiple trades by CSV

`!trade import` (attach CSV to the command before hitting Enter)

Expected format:

```csv
give,get,clan_tag
Wizard,Barb Hut,VQ9POJ
Pekka,Bowler,88QR9JOR
Witch,Cannon Cart,9GUPL8R
Baby Dragon,Dark Prince,9GG8OYVY
```

| give | get | clan_tag
| --- | --- | ---
| wizard | Barb Hut | VQ9POJ
| Pekka | Bowler | 88QR9JOR
| Witch | Cannon Cart | 9GUPL8R
| Baby Dragon | Dark Prince | 9GG8OYVY
