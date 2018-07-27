# Recruitment

Recruiting members for our clans is one of the most important responsibilities for Co-Leaders and Leaders. The exact procedure differs from clan to clan, but generally follow these steps:

* If a player requests to join your clan in-app:
    * Check that members meet the basic requirements (minimum 12 challenge wins, decent PB)
    * Use bot commands `!cwr`, `!cwrt` to check clan war readiness (CWR).
    * Accept / reject based on these criteria, and direct new member to join Discord.
    * If you wish to secure a player based on basic stats, you can accept first and check stats afterwards. If you decide to reject the player following the acceptance, you should kick with a message and ask them to join Discord to apply.
* If a player requests to join from Discord:
    * Run `!recruit` or `!re` command with the player’s tag. This will put the player in our `#recruit` channel and you can discuss with other clan leaders in `#recruit-discussion` regarding which clan would be the best fit.
* When a new player has joined your clan:
    * Direct them to join Discord
    * Run [`!r v`](leader/new-users) to verify their membership on Discord.

## Clan War Readiness (CWR)

**Clan War Readiness (CWR)** is how well your cards are leveled for the clan wars league you're playing in. Most of our clans look for 30 to 50%+ of your cards to be leveled within your league. Most of our clans are in the legendary league, so we'll focus there as an example:

Legendary League Standard is 12/10/7/4, so your Legendary League Readiness % is based on the number of cards at that level or higher.  Again, 30-50%+ is the standard we look for today.

In Legendary League, you can also see +1 levels (Legendary League Readiness or 13/11/8/5 -- max cards) when you battle, so a player with 50% Legendary Readiness is better off than someone with 5% Legendary when it comes to building strong decks to go to battle with.

!> CWR is a measure that is unique to our family, as implemented on [RoyaleAPI.com](https://royaleapi.com). Players may not be familiar with the term. You can show the definition of CWR by running the bot command [`!q cwr`](leader/quotes)

## Bot Commands

| Command | Alias | Description |
| --- | --- | --- |
| `!recruit @user` | `!re @user` | Add the Recruit role to user and place them into the `#recruit` channel |
| `!recruit @user C0G20PR2` | `!re @user C0G20PR2` | **Preferred.** Add the Recruit role to user and also assign player tag in the same step.  |
| `!cwready @user` | `!cwr @user` | Show the CWR of a user. Note: this will only work if a player tag has been associated. |
| `!cwreadytag @user` | `!cwrt @user` | Show the CWR of a player tag. This is great for checking CWR for any players. |

## Family Admin

### Public family access

* https://royaleapi.com/clan/family/100t/admin

You can get to Clan War Analytics (member performance in the last 10 wars), and many other tools for every single clan in the family.

### Private family portal

* https://royaleapi.com/fadmin/100t

This is a portal for managing all members regarding clan war performance and in-clan family recruitment. You will need to login with your Discord login. The site will verify that you are a leader in 100T and give you relevant access.

This portal offers most of the features you see on the public access pages, but also include some premium features that are unavailable in the public access pages. You can also easily get to these pages on your `Me` page after logging in: https://royaleapi.com/me

- Family-specific player stats
- Clan War readiness per clan
- Decks used in war, including practice count by members (checks for 7-day deck use before war battle)
- Player war battle history, clan cards collected, win stats
- Clan history in last 7 days: see where members come from and if they have left, which clan they have gone to
- Global Clan War time table (so you can avoid overlapping with other clans)
