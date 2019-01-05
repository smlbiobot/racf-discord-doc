# Cheat Sheet

## Role Assignments

| Command | Example | Description
| --- | --- | ---
| `!r v @person playertag` | `!r v @SML C0G20PR2` | Use this on all members or visitors that give you a player tag. This is needed for the audit and is the go-to command.
| `!re @person playertag` | `!re @SML C0G20PR2` | Use this on recruits to send them to `#recruit`
| `!cwr @person` | `!cwr @SML` | Show clan war readiness of a Discord user.
| `!reject @person` | `!reject @SML` | Send a message to the user and remove the recruit role.
| `!rmre @person` | `!rmre @SML` | Remove recruit roles without sending message.

In most cases,  `!r v` does everything you need and can be used as a reset.
If you offer someone a spot in a clan in #recruit add the corresponding recruit role for your clan. For example add EchoRecruit to them using the `changerole` command.

More info:
- [Role Assignment](leader/new-user)
- [Recruitment](leader/recruit)

## Adding and removing roles

| Command | Description
| --- | ---
| `!changerole @person role` | Will add a role you have permission to add depending on rank.
| `!changerole @person role1 role2` | Will add multiple roles at once.
| `!changerole @person -role1 -role2` | Will remove a role or multiple roles.
| `!changerole @person role1 -role2 role3` | You can add as many roles as you need to change, using the `-` modifier to remove, and no modifier to add.

You cannot use the GUI to add roles by clicking on names on desktop or going into server settings on mobile.

More info: [Role Management](leader/manage-roles)

## Listing roles

| Command | Description
| --- | ---
| `!mm bravo` | Find everyone with the Bravo role.
| `!mm bravo elder` | Find everyone with the Bravo and elder role.
| `!mm bravo -x AlphaFamilyLead elder` | Find everyone in Bravo who is not a leader nor elder. Good for finding long-term members to promote to elders.

More info: [Member Management](leader/manage-members)

## Member search

| Command | Description
| --- | ---
| `!rs name` e.g. `!rs sml` | Search to show if a member with that name is in the RoyaleAPI clan family. (This is a text search so don’t add `@` before the name)
| `!v @person` | If they are a visitor or don’t reply. However if they are a visitor and provide a player tag, you should associate player tags with them with `!r v`.

## Audit

| Command | Description
| --- | ---
| `!racfa run -c alpha` | Runs and audit on a single clan in `#audits`. This is just to help you see your clan better. The entire family will still be run (as we won’t know where that member went otherwise).
| `!rolehist @person` | Use to see role history. Was xyz an elder? When was he promoted? Did he join the server a year ago as a visitor and only joined us recently as a member?
| `!clans` | Show the list of clans and requirements for those interested in joining.
| `!cpg `| Show your CR info and chest cycle in `#bot-commands`

More info: [Audit](leader/audit)
