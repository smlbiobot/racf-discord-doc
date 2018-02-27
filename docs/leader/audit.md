# Auditing

Leaders should perform periodic audits on their clans to make sure that the Discord membership + roles are the same as that in-app.

- Verify that members with the clan tag on Discord are in fact in the clan in-app. If not, remove clan tag from Discord (but do not remove the Member role).
- Note the list of members in the clan who are not on Discord and ask them to join the Discord server.
- Assign clan roles to members.
- After all the clans have completed their audits, people with only the Member role on the server but without any clan assignments can be changed to Visitor.

## All-in-one Bot Command

`!racfaudit run` or `!racfa run` is our all-in-one bot command that will auto-audit the entire family. It does the following:

- Using the API, fetches every single member from our clans.
- Identify members who have not set their tags on Discord (where you should `!r v` them).
- Identify members who have the Elder role but not yet promoted in CR.
- Identify members who have specific clan tags but are not in fact in the clan.
- Identify members who do not have the correct clan roles.

To filter and show only your own clan, type `!racfa run -c alpha`

To have the bot automatically add and remove all the roles, type `!racfa run --exec`

## Related Bot Commands

- [!mm](leader/manage-members.md). Role checks.
- [!crclan audit](leader/crclan.md). Membership checks.
