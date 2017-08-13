# Members

We wrote this guide to help new members on how to use Discord. This will guide you through how our server is setup and explain some useful commands you can run.

## Channels

Discord servers are broken down into channels with different topics. As a member, you are able to see the following channels:

- **#welcome.** This channel is read-only for all except co-leaders and leaders. It is used to greet visitors and used for role assignments only.
- **#visitors.** This is the public chat for everyone.
- **#family-chat.** This is the members-only chat. Everyone from the clan family chats here. There are no clan-specific chats on our server.
- **#strategy.** Need help with a deck? Have pro-tips to share? This channel is for you. Trolling on this channel is strictly prohibited. Please try to be helpful in offering advice.
- **#rant.** Rant your hearts out
- **#discordgram.** Instagram on Discord. You can only post photos here. You will need to run bot commands to add a comment to the photo. See [Discordgram](discordgram.md) for more info.
- **#bot-comamnds.** This is where you should run most of the bot commands. In fact, many of the commands mentioned in this guide are disabled in the chat channels to prevent spam.
- **#casino.** This is where you gamble with Discord credits. See [Casino](casino.md) for more info.

## Bot Commands

A number of bot commands were written specifically for the RACF Discord server.

### Change clan (!changeclan)

Used when you change from one RACF clan to another. Syntax:

`!changeclan Alpha`

`!changeclan Delta`

The *eSports* role require leader approval and as such is not supported by this command. If you got accepted into Alpha eSports, please contact one of the leaders (Slayer / Xhadian / SaintBelekin) to update your roles.

### Toggle role (!togglerole)

A number of roles are self-assignable / self-removable by members. Syntax:

`!togglerole Heist`

`!togglerole Practice`

* **Heist. **Used to play the game !heist in #casino. Mentionable. (Default: disabled)
* **Practice. **Used for weekly practice. Self-assign in order to see the #practice channel as well as notifications and info for practice sessions. (Default: enabled)
* **Tourney.** Used for tournament notification. Self-assign in order to get notifications for tournaments. Mention the role to alert others with tournament information, e.g. `@Tourney Name: Awesome Tournament / Password: AwesomePass / 10k gem 1000-player x2000 cards` (Default: enabled)
* **Recruit.** Self-assign to see recruiting information about Alpha eSports. (Default: disabled)


### Pay (!pay)

Transfer credits to one or more people. Divide credits equally if multiple users are specified. Since credits can only be integers, there will be some rounding errors.

`!pay 50 SML`

`!pay 100 SML 6John Meridian`

### Rules + Roles (!racf)

This displays links to the RACF rules, roles, and discord invite link.

### Farmers (!farmers)

This fetches the Farmers data from Nuclino and display in the Discord chat as a table. A newer version will store data as JSON on the server, but this is a work-around in the meanwhile.

Type `!farmers` to show the latest farmers.

Type `!farmers 2` to show the farmers on Week 2 since we started recording data.
