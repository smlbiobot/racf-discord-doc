# Role Assignment in Welcome

See also [Cheat Sheet](leader/cheat-sheet)

## Auto-assignment with player tag

If the user provides his player tag for you, you can use `!racf verify` to automatically assign roles:

### Clash Royale

`!racf verify @SML C0G20PR2`

`!r v @SML C0G20PR2`

This command does the following

- Register player tag with `!crprofile`, `!crclan` and `!racfaudit`.
- Look up player profile and retrieve clan information.
- Verify that the clan belong to one of our clan.
- Assign clan roles.
- Verify that the clan allow Membership assignment.
- Assign standard member roles: Member, Tourney.
- Change nickname to user IGN.

?> Alias `!r v` (note space between r and v)

### Brawl Stars

?> Depreciated. There are no BS API left.


## Visitors

If visitors provide you with their player tags, `!r v` will also assign them with the Visitor roles automatically when the bot noticed that they are not in one of our clans.

If the visitor said that they are just visiting, you can run:

`!visitor @SomeVisitor`

`!v @SomeVisitor`

## Visitors interested in joining

If the visitor mentioned that they are interested in joining our clans, after you have run `!v` against them, you can go to the `#visitors` channel and show them our trophy requirements:

`!clans`

## General rules

- Try to take care of new users in #welcome efficiently.
- In general, it is better to assign them a visitor / member role before furthering conversation in #visitors.
- Users without role assignments won’t be able to chat in any channels that is why assigning them with the `visitor` role is always better than lengthy conversations in `#welcome`.
