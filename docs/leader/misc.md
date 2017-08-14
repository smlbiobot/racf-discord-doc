# Miscellaneous Commands

## Kick 50/50

`!kick5050`

`!k5`

Remove a member’s clan tag and send them a DM telling them that they have been kicked for being 50/50 and ask that they join a feeder clan.

`!kick5050 UserName`

`!k5 UserName`

## Mention Role

Enable you to mention a role that‘s not mentionable.

`!mentionrole Delta Anyone who is 4.6k+ please move up to Charlie.`

## DM Users

This allows you to send a DM (Direct Message) to a list of users. Good for asking people to update their clan tags when auditing.

Typical workflow: you find a list of users without clan tags and output their Discord mentions:

`!mmnoclan --output mention`

…followed by copying the list of mentions and used as parameter to send DMs:

`!dmusers "Hi there you have no clan tag assigned. Please use the bot command !changeclan \
on the RACF server to update your roles. You will be converted into visitors if you don’t \
do so in 24 hrs." <@70901400430718976> <@!237016475406172161> <@223568673539883020> \
<@258257768182448129> <@!277614984731557889> <@304806109976330250> <@98452778896076800> \
<@262287777930936331> <@198274673996201984>`
