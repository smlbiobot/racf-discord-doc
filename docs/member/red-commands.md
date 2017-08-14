# Basic Bot Commands

## User Information

`!userinfo` displays user information of a user on the server. If you use the command without any parameters, it will return user information of yourself.

`!userinfo [Username or mention]` displays user information of another person on the server. For example, you can display information about SML by typing `!userinfo SML` or `!userinfo @SML`.

## Server Information

`!serverinfo` displays information about the RACF server.

## Urban Dictionary

`!urban` performs searches on the Urban Dictionary.

For example, type `!urban lol` to return the first definition for _lol_.

You an optionally add a number to get the nth definition. For example, typing `!urban lol 5` returns the 5th definition for _lol_ on UD.

## Help

`!help`: Have the bot send you all the commands available on the server

`!help [command name]`: Get help with a specific command. e.g. `!help userinfo` will provide help information on how to use the `!userinfo` command.

### Subcommands

Some commands have subcommands, which is the second word you type after the main command. For example:

```
!crdata

Clash Royale Global 200 data.

Commands:
  cardnames   Display valid card names and abbreviations.
  cards       List popular cards.
  decks       List popular decks.
  leaderboard List decks sorted by rank.
  search      Search decks on the Global 200.
  similar     Find similar decks with specific deck or rank on leaderboard.

Type !crdata command for more info on a command.
You can also type !crdata category for more info on a category.
```

- `crdata` is the command name.
- `cardnames`, `cards`, `decks`… are the **subcommands** for the `crdata` command.
- When the help told you to type `!crdata command` for more info on a command, it means that if you type `!crdata search` or `!crdata similar` you will see more info about that command.
