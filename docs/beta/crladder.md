# Elo Ladder

This is a tournament-standard custom Ladder which calculates your skill rating by playing Clash Royale games. For testing, we will use both Trueskill and traditional elo.

Please join this Discord server to participate in user-testing: http://discord.gg/BFGzZpn

```
!!crladder verify C0G20PR2 anb8czxg
!!crladder register a1
!!crladder play @alpe123#2295
```

## Register and Play

Testing will happen on the bot named `R3.Alpha`. This bot uses the prefix `!!` so prepend all your commands with `!!`. All of the commands starts with `!!crladder` followed by a subcommand.

### 1. Verify

You must verify that you own the account in order to play. You will need:

- Player tag
- API token

```
!!crladder verify C0G20PR2 anb8czxg
```

Watch this video to see how you can find both:

[![Player Tag and API Token](https://img.youtube.com/vi/IIQbrD2JWSs/maxresdefault.jpg)](https://www.youtube.com/watch?v=IIQbrD2JWSs "Player Tag and API Token")


### 2. Register

After you have verified your account ownership, you can register to a series to play. Current active series is `a1`

```
!!crladder register a1
```

### 3. Play

To play against another opponent:

```
!!crladder play @alpe123#2295
```

- Your opponent will be asked to accept the match.
- If the match is accepted, you have 2 minutes to open CR and play the game.
- Once the game is completed, your ratings will be updated.
