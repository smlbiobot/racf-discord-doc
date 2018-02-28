# Role Management

`!changerole` is our universal role management command and is able to add and remove mutliple roles in a single command.

## Making changes to multiple roles

Syntax:

`!changerole member +role_to_add -role_to_remove`

`!changerole @member "+role to add" "-role to remove"`

Multi-word roles must be surrounded with quotes, with the operator to add (+) and remove (-) inside the quote. As above, member can be just the name or @mention. Examples:

### Adding a single role

`!changerole SML Delta`

### Adding multiple roles

`!changerole SML Delta Member`

### Removing role(s)

`!changerole SML -Delta -Member`

### Adding and removing role(s)

`!changerole SML Delta Member Tourney Recruit -Visitor`

### Adding and removing roles with spaces

`!changerole SML Delta "+Delta Lead" "-Foxtrot Lead"`


## Multi-add/remove role

These two commands `!multiaddrole` and `!multiremoverole` allow you to easily add / remove the same role to / from multiple users.

`!multiaddrole <role> [members...]`

`!multiaddrole rolename User1 User2 User3`

`!multiremoverole <role> [members...]`

`!multiremoverole rolename User1 User2 User3`

As with other role management commands, you can use name / name + discriminator / user mention for the user fields.

## Member to Visitor

`!member2visitor`

`!m2v`

Convert a list of members to visitors. This is usually used during auditing to convert a list of members without clan tags into visitors quickly. It will remove all default member roles (Member, Recruit, Tourney) and add the Visitor role in one go.

`!m2v <@70901400430718976> <@!237016475406172161>`

## Visitor to Member

`!visitor2member`

`!v2m`

Convert a visitor into a member while adding all default member roles (Member, Recruit, Tourney). Optionally include additional roles to add. e.g. Someone mentioned in #welcome that they are from Charlie and you have verified that they are in fact in Charlie in-app:

`!v2m UserName Charlie`



## Role History

`!rolehist` displays the the complete role history of any user, including the dates when roles are added / removed. Syntax: `!rolehist \[username\]` e.g. `!rolehist SML`

To re-initialize the database, type: `!rolehistinit `— this will re-populate the database in case new members have joined when the bot is down.
