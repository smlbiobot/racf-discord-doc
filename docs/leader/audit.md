# Auditing

Leaders should perform periodic audits on their clans to make sure that the Discord membership + roles are the same as that in-app.

- Verify that members with the clan tag on Discord are in fact in the clan in-app. If not, remove clan tag from Discord (but do not remove the Member role).
- Note the list of members in the clan who are not on Discord and ask them to join the Discord server.
- Assign clan roles to members.
- After all the clans have completed their audits, people with only the Member role on the server but without any clan assignments can be changed to Visitor.

## Audit the entire family

`!racfaudit run` or `!racfa run` is our all-in-one bot command that will auto-audit the entire family. It does the following:

- Using the API, fetches every single member from our clans.
- Identify members who have not set their tags on Discord (where you should `!r v` them).
- Identify members who have the Elder role but not yet promoted in CR.
- Identify members who have specific clan tags but are not in fact in the clan.
- Identify members who do not have the correct clan roles.

### Show results specific only to your clan

`!racfa run -c alpha`

### Add/remove all necessary roles

`!racfa run --exec`


## Search members by name

`!racfaudit search`

alias `!rs` (no space)

Sample usage:

`!rs joh`

```
Jo͛hͥn̽ #8L9L9GL, Reddit Alpha, Co-Leader, 5278
John #9LL0VQ8L, Reddit Alpha, Co-Leader, 5225
John™ #PL22YQUY, Reddit Alpha, Elder, 5217
```

Note that it will detect and convert accented characters but `!rs john` will not find `Jo͛hͥn̽` as the last accent is in fact too complex.

### Add links to RoyaleAPI (-l or --link option)

`!rs -l wo`

```
Woody #8L9J29, Reddit Alpha, Leader, 5285
http://cr-api.com/player/8L9J29
swoleytien #PR0GV29C, Reddit Echo, Elder, 4844
http://cr-api.com/player/PR0GV29C
SenzTwo #2QG089JU2, Reddit Foxtrot, Member, 4396
http://cr-api.com/player/2QG089JU2
mr.wolf #29VUV8QPY, Reddit Golf, Member, 4403
http://cr-api.com/player/29VUV8QPY
Sword Slash #8YY289C8, Reddit Hotel, Elder, 4241
http://cr-api.com/player/8YY289C8
```

## Related Bot Commands

- [!mm](leader/manage-members.md). Role checks.
- [!crclan audit](leader/crclan.md). Membership checks.
