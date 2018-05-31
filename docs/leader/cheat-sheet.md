# Cheat Sheet

| Command | Example | Description
| --- | --- | ---
| `!r v @person playertag` | `!r v @SML C0G20PR2` | Use this on all members or visitors that give you a player tag. This is needed for the audit.
| `!v @person` | `!v @Bob` | If they are a visitor or don't reply. However if they are a visitor and provide a player tag they can be done with the previous command.
| `!crsettag playertag @person` | `!crsettag C0G20PR2 SML` | To set a player tag to a player. This is needed for audit and to use `!cpg` for player profile.

Please give people a chance to respond in #welcome before adding roles because they will not be able to see that channel once they are a visitor. If you give roles make sure to continue to help them in `#visitors`.

Give people that break rules more than three minutes to correct it or get kicked, this is bad practice. Most of the time they can be reminded of the rules and we can all move on in a good direction.

More info: [Role Assignment](leader/new-user)

| Command | Description
| --- | ---
| `!changerole @person role` | Will add a role you have permission to add depending on rank.
| `!changerole @person role1 role2` | Will add multiple roles at once.
| `!changerole @person -role1 -role2` | Will remove a role or multiple roles.
| `!changerole @person role1 -role2 role3` | You can add as many roles as you need to change, using the `-` modifier to remove, and no modifier to add.

You can use the GUI to add roles by clicking on names on desktop or going into server settings on mobile.

More info: [Role Management](leader/manage-roles)

| Command | Description
| --- | ---
| `!racfa run -c alpha` | Runs and audit on a single clan in `#audits`. This is just to help you see your clan better. The entire family will still be run (as we won’t know where that member went otherwise).
| `!rolehist @person` | Use to see role history. Was xyz an elder? When was he promoted? Did he join the server a year ago as a visitor and only joined us recently as a member?
| `!clans` | Shows the list of clans and requirements for those interested in joining.
| `!cpg `| Shows your CR info and chest cycle in `#bot-commands`

More info: [Audit](leader/audit)
