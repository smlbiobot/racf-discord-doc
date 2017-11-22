# Trophy Requirements

The `!trophies` cog has been depreciated and disabled in favor of the `!clans` and `!bands`. They are included here in case the API is down and we need to re-enable it.

## API

The trophy requirement commands, `!clans` for Clash Royale and `!bands` for Brawl Stars, decipher the trophy requirements in each clan / band automatically from the in-game clan description.

- Set your trophy requirements in clan using numbers or numbers with commas, e.g. `4400` or `4,400`
- Do not use other random numbers in the description.
- Because of censorship, please set requirements for 4.2k as `4,2OO` (letter 0). The cog will convert them to numbers on Discord.
- If season has just reset, you may add `PB` after the number to designate that we are using personal best. Please don’t use these two characters to describe anything else, otherwise it will be displayed.

## Legacy

### Clash Royale

#### Show

To display the table, type `!trophies show`

Shortcut is `!tr show`

#### Set

Co-leaders and above have permissions to set the trophies requirement. e.g. `!trophies set Delta 4300`

By default, the trophy requirements take a number only. If you would like to set a PB, you can work around like this:

`!trophies set Delta 4,300 PB`

### Brawl Stars

Same as Clash Royale syntax but with the _bs_ prefix.

`!bstr show`

`!bstr set`
