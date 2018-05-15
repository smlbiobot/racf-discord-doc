# Clan Wars

- Data Tables: https://royaleapi.com/info/clan_wars

## Readiness

Battle readiness compiled by Sean (MVP)

https://public.tableau.com/profile/sean8402#!/vizhome/CR-Stats/ClanWarReadiness?publish=yes

- You can use the same graph to change clan, etc.

[tableau](../inc/embed/tableau.html ':include :type=html width=100% height=600px')

## Description

Sean has collected the card levels for every player in the family using the API. Using those data, he has categorized each player’s card level as being tourney standard, tourney +1, tourney +2, etc. Since each league has a base card level and an over-leveled level (base+1), you can determine a player‘s overall battle readiness for that league.

In the visualization below, you can set the base level in **Tourney Diff** and show which players have the card levels to play in different leagues; filter by card types; or use the clan selector to change to a different clan.

For example: Silver league’s base card level is Tourney + 1. Every card that a player has that is less than Tourney + 1 is removed. The resulting length of the bar denotes how many cards a player can play when in the Silver League.
