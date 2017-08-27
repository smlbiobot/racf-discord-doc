# Role Assignment in Welcome

## Scenarios

A new user named MortarMauler signed onto Discord. As leader, you need to help them out after they have mentioned who they are.

### In the RACF

1. Leader: Which clan are you in?
2. MortarMauler: I am in Alpha
3. Leader checks app and verify that MortarMauler is in fact in Alpha.
4. Leader: `!visitor2member MortarMauler alpha`
5. Leader: @MortarMauler Welcome! You can now chat in #family-chat

?> Alias `!v2m`

?> You can append as many roles as you like, e.g. `!v2m User alpha elder coc` will add all the default member roles as well as Alpha, Elder and CoC to the user.

### In our Brawl Stars bands

1. Leader: Which band are you in?
2. MortarMauler: I am in Alpha
3. Leader checks app and verify that MortarMauler is in fact in Alpha.
4. Leader:`!bs UserName BS-Alpha`


### Interested in joining our trophy-pushing clans

1. Leader: What are your current trophies + PB?
2. MortarMauler: 4,300 / 4,600 PB
3. Leader:  `!trophies show` or shortcut `!tr show` or even shorter `!trs`
4. Leader: Please request Delta in-app and let me know when you have been accepted.
5. Leader: `!changerole @MortarMauler visitor`

?> Alias `!visitor @MortarMauler`

?> Use `!tr show` or `!trs` for showing trophies.

### Interested in the eSports branch

1. Leader: `!changerole @MortarMauler visitor recruit`
2. Leader: @MortarMauler please see pinned messages in #esports-recruiting for eSports info.

?> Alias `!recruit @MortarMauler` does all of the above.

### Just visiting

1. Leader: `!changerole @MortarMauler visitor`
2. Leader: @MortarMauler Welcome! You can now chat in #visitors.

?> Alias `!visitor @MortarMauler` does all of the above.

## Auto-assignment with player tag

If the user provides his player tag for you, you can use `!racf verify` to automatically assign roles:

### Clash Royale

`!racf verify @SML C0G20PR2`

- Register player tag with `!crprofile` and `!crclan`.
- Look up player profile and retrieve clan information.
- Verify that the clan belong to a list of clans which allow role assignment (e.g. A-H, Mini, Mini2 but not eSports).
- Assign clan roles.
- Verify that the clan allow Membership assignment.
- Assign standard member roles: Member, Tourney, Practice.
- Change nickname to user IGN.

?> Alias `!r v` (note space between r and v)

### Brawl Stars

`!racf bsverify @SML 889QC9`

?> Alias `!r bv`
