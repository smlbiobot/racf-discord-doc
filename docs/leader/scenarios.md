# Scenarios

This document illustrates a few of the most frequently-used scenarios to help you get started with using bot commands on the Discord server.

## Greeting new users

A new user named MortarMauler signed onto Discord. As leader, you need to help them out after they have mentioned who they are.

### In the RACF

1. Leader: Which clan are you in?
2. MortarMauler: I am in Alpha
3. Leader checks app and verify that MortarMauler is in fact in Alpha.
4. Leader: `!v2m MortarMauler alpha`
5. Leader: @MortarMauler Welcome! You can now chat in #family-chat

### Interested in joining our trophy-pushing clans

1. Leader: What are your current trophies + PB?
2. MortarMauler: 4,300 / 4,600 PB
3. Leader:  `!trophies show`
4. Leader: Please request Delta in-app and let me know when you have been accepted.
5. Leader: `!changerole @MortarMauler visitor`

### Interested in the eSports branch

1. Leader: `!changerole @MortarMauler visitor recruit`
2. Leader: @MortarMauler please see pinned messages in #esports-recruiting for eSports info.

### Just visiting

1. Leader: `!changerole @MortarMauler visitor`
2. Leader: @MortarMauler Welcome! You can now chat in #visitors

## Elder promotion

### Deciding who to promote

There is not enough elders in the clan to accept members, so you have decided to look for members who have been with us for a long time.

`!mm Alpha -x Leader Co-Leader high-elder elder`

This will list all members who are in Alpha but not a Leader / Co-Leader / High Elder / Elder. By default, the list will be sorted by time since joining the server. You should note that the time does not reflect how long they have been with RACF, and that they could have joined our Discord server 5 months ago as a visitor and only joined as member a couple of days earlier.

### Promoting

You have decided that MortarMauler is the one you wish to promote:

`!elder @MortarMauler`

This will add the _Elder_ role to the member and send them a DM telling them their new responsibilities as an elder.
