# Toggle Role

`!togglerole` is runnable by anyone on the server to toggle their roles.

As a moderator, you can setup what roles users can toggle. Toggleable roles are tied to specific roles. For example, you might wish to allow Members to toggle the CoC role but disallow Visitors to toggle that same role. As such, roles are separate from one another.

When a user run the command, it will check to see all the roles the user has permission to toggle, and either perform the action or complain.

## Settings

`!toggleroleset`

Subcommand | Description
--- | ---
add | Add a toggleable role.
list | List all toggleable roles.
remove | Remove a toggleable role.

Please note that the bot does not check role permissions. If a moderator decides to add Leader as a toggleable role for Co-Leaders, even though Leader is hierarchically higher than a Co-Leader, it will allow it if the bot is allowed to perform the action.

## Examples

Example | Description
--- | ---
`!toggleroleset add Member CoC` | Adds CoC to be a toggleable role for Members.
`!toggleroleset add Visitor Heist` | Adds Heist to be a toggleable role for Visitors.
