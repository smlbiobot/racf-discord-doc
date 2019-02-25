# Royale Rating Ladder

This is a tournament-standard custom Ladder which calculates your skill rating by playing Clash Royale games. The rating system is similar to Elo is much more advanced and can hone into your rating more accurately and quickly.

Please join this Discord server to participate in user-testing: http://discord.gg/BFGzZpn

```
!!rr verify C0G20PR2 anb8czxg
!!rr register a1
!!rr play @alpe123#2295
```

## Register and Play

Testing will happen on the bot named `R3.Alpha`. This bot uses the prefix `!!` so prepend all your commands with `!!`. All of the commands starts with `!!rr` followed by a subcommand.

### Verify

You must verify that you own the account in order to play. You will need:

- Player tag
- API token

```
!!rr verify [player_tag] [api_token]
!!rr verify C0G20PR2 anb8czxg
```

<img src="/img/rr/tag-api-token.png" style="width:100%; height: auto">


### Register

After you have verified your account ownership, you can register to a series to play. Current active series is `a1`

```
!!rr register a1
```

### Play

To play against another opponent:

```
!!rr play @alpe123#2295
```

- Your opponent will be asked to accept the match.
- If the match is accepted, you have 2 minutes to open CR and play the game.
- Once the game is completed, your ratings will be updated.

### Seek

Open seek: allows you to post a match and allow anyone else to accept

```
!!rr seek
```
- Anyone can react with ✅ to accept your seek
- If you wish to cancel your seek, you can react with 🚫

<img src="/img/rr/rr-seek.png" style="width:100%; height: auto">

## How this works

**Royale Rating** (RR) aims to give each player a score related to their skill. This allows us to rank players by that score.

Main formula:
```
RR = μ - 3σ
```
**Skill Score** (μ, mu):
- Winning increases your score.
- Losing decreases your score.
- Winning against a higher rated player gives a bigger increase.
- Losing against a lower rated player gives a bigger decrease.
- Draws against higher players increase your score, and decrease it when they are lower.

**Uncertainty** (σ, sigma):
- Playing more games gives a more precise rating, it decreases the uncertainty.
- Winning against higher players and losing to lower players gives a less precise rating, it increases the uncertainty.

**When the uncertainty (σ) decreases enough, your rating is considered to be precise, and RR ≈ μ.**

<img src="/img/rr/rr-curve@4x.png" style="width:100%; height: auto">
