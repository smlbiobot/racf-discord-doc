# Basic Bot Commands

## General

Command | Description
--- | ---
8 | Ask 8 ball a question
choose | Chooses between multiple choices.
flip | Flips a coin… or a user.
hug | Because everyone likes hugs
lmgtfy | Creates a lmgtfy link
ping | Pong.
poll | Starts/stops a poll
roll | Rolls random number (between 1 and user choice)
rps | Play rock paper scissors
serverinfo | Shows server’s informations
stopwatch | Starts/stops stopwatch
urban | Urban Dictionary search
userinfo | Shows users’s informations

## Image

Command	| Description
--- | ---
gif | Retrieves first search result from giphy
gifr | Retrieves a random gif from a giphy search
imgur | Retrieves a picture from imgur

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
