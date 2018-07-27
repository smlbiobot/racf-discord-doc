# Member Management

The `!mm` command is used to list members by a combination of role inclusion and exclusion. The basic syntax is:

`!mm Alpha Competitive --exclude Elder`

`!mm Alpha Competitive -x Elder`

which lists all members who are part of the Alpha clan, who has the Competitive role, but is not an elder.

## Full usage

```
!mm [-h] [-x EXCLUDE [EXCLUDE ...]]
     [-o {id,mention,mentiononly}] [-r1] [-e] [-s {join,alpha}]
     [-r {embed,csv,list,none}] [-m MACRO]
     [roles [roles ...]]
```

Type `!help mm` if you need help on using all the options.

## Find people with the member tag but are otherwise not assigned to any clans:

`!mmnoclan`

is an alias (shortcut) to:

`!mm member -x alpha bravo charlie delta echo foxtrot golf hotel esports special`

To quickly output a list of user mentions so you can contact everyone without a clan tag in a message:

`!mmnoclan --output mentiononly`

## Find people on the server without any role assignment:

`!mmnorole`

is an alias to

`!mm --everyone -x member guest visitor bot`

## Additional options

Ideally, run these options in a leader-specific channel instead of `#bot-commands` as it could lead to potential abuse by regular members.

```
!mm bravo -x alphafamilylead elder -o id
```

Options | Alias | Functionality
--- | --- | ---
`--output id` | `-o id` | Append a list of user ids for the result.
`--output mention` | `-o mention` | Append a string of user mentions for users displayed. This was created such that you can easily grab + mention people in that list in a message.
`--output mentiononly` | `-o mentiononly` |  Don’t display the long list and only display the list of member mentions.
`--result embed` | `-r embed` | Default: show results a Discord embed.
`--result none` | `-r none` |  Don’t show results at all. This is useful if you just want to know the count of the results, and/or optionally grab user mentions / ids.
`--result csv` | `-r csv` | Output as a list of comma separated values.
`--result list` | `-r list` | Output as a list. One member per line.
`--sort alpha` | -- | Output list that’s sorted in alphabetical order. Default is to sort by join date.
