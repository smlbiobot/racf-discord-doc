# Trading

A special `!trade` command for members to add trades they have found in the wild.

- Give: What you are giving out
- Get: What you are getting / what you want
- Clan Tag: The clan tag without the `#` symbol

## List trades

Do this in `#bot-commands` as it is very spammy.

### All

We have created a channel called `#trade-bot` that updates every minute so there is no need to actually run this command.

`!trade list`

Help for all optional arguments

`!help trade list`

### Filter by Rarity

`!trade list --rarity epic`

shortcut:
`!trade list -r e`

Acceptable values:

- legendary
- epic
- rare
- common

### Filter by Cards

`!trade list --give nw`

List all known trades that will accept a Night Witch for trades

`!trade list --get iwiz`

List all known trades where can give your Ice Wizard to get something back.


!> Adding and removing trades affects the data in the database. If you don’t know what you are doing, don’t run these commands. Adding non-existent trades create headaches for everyone else. Removing trades that actually exists takes away the opportunity to trade from others.

## Adding trades

If you have found a trade in the wild, you can add it to the database by running:

`!trade [add|a] <give> <get> <clan_tag>`

`!trade add nw iwiz C00`

Someone in the clan tagged `C00` is looking for an Ice Wizard in exchange for your Night Witch.

## Removing trades

If you have visited a listed clan and that item is no longer listed, you can remove it by typing:

`!trade [remove|rm|r] <give> <get> <clan_tag>`

`!trade rm nw iwiz C00`

Avoid this step unless you are absolutely sure what you are doing. This is destructive and will remove the entries.
