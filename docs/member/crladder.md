# CR Ladder

This is a custom ladder that calculates user rating using [TrueSkill](https://www.microsoft.com/en-us/research/project/trueskill-ranking-system/), a rating system developed by Microsoft Research that has been used on Xbox LIVE for ranking and matchmaking service. The system is similar to [Elo](https://en.wikipedia.org/wiki/Elo_rating_system) and [Glicko](https://en.wikipedia.org/wiki/Glicko_rating_system) for those are are familiar with them.

The reason for choosing TrueSkill over other rating system is because TrusSkill supports team vs team rating whereas other systems strictly focuses on 1v1. This nuance is unimportant for now, however it may be useful for us later.

## How to play

This is not a fantasy game. In order to win, you will have to play against another player in Clash Royale who is also registered in the series. After you have battled, send a bot command to declare who you have played against and the bot will read from the API and updating your rating.

Unlike CR’s implementation of Elo, this system uses a confidence rating based on the number of games you play and adjust your rating accordingly.

We are currently in testing phase and have setup a ladder series called **abc**. This is the only series that is active right now.


- Use **#crladder-bot** for bot commands.
- Use **#crladder-seek** to seek people to play against.

Bot Command | Description
--- | ---
`!crladder register abc` | Self-**register** to be on the ladder series called **abc**.
`!crladder info abc` | **Info**. See current ranking of all the players who have played at least one game.
`!crladder info abc showall` | See current ranking of players who have registered. This is useful for looking up people to play against.
`!crladder info abc winloss` | Show total games / win / draw / loss info together with the ladder.
`!crladder info abc winloss showall` | Show W/D/L info for everyone. However, this is primarily pointless because people who have not played a game will have W/D/L all be 0.
`!crladder battle @Opponent` | After you have **battled** in Clash Royale, run this command to update your rating.
`!crladder battle @Opponent abc` | If you are registered to multiple active ladders, you will need to also add the name of the series.

!> You can only report one battle at a time. If you have played multiple games against the same person and did not report any of them, only the last one is rated.

## Series 1: abc: Deadline

We will conclude the series on January 18th, 2018 at midnight EST. The winner will get a **special color role** of your choice for 3 days. Good luck!


## Screenshots

`!crladder battle @Opponent`

<img src="/img/bot/crladder-battle.png" />

`!crladder info abc`

<img src="/img/bot/crladder-info.png" />

`!crladder info abc winloss`

<img src="/img/bot/crladder-info-winloss.png" />

## Source

- Code: https://github.com/smlbiobot/SML-Cogs/tree/master/crladder
- Battle Log API: http://cr-api.com
