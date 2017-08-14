# Casino

Casino is a mini game parlor on the Discord server. You can gamble in it with virtual Discord credits. Like other internet points, they don’t do anything besides bragging rights.

## Discord credits

In order to start getting credits, you must first open an account at the bank by typing `!bank register`. Then you can start collecting your salary with `!payday`. You can run payday every now and then. At the time of this writing, payday is set to give you 1,000 credits every hour. To see your current bank balance, type `!bank balance`.

Commands | Functionality
--- | ---
`!bank register` | Open an account.
`!payday` <br />`!pd`| Earn 1000 credits every 1 hour.
`!bank balance` <br />`!bb` | Your balance.
`!leaderboard` <br />`!lb`| Show the Leaderboard.

!casino exchange credits amount:: Credits to Chips


## Casino chips

There are two kinds of banks on the RACF Discord server. One is the normal bank. The other is the casino bank. To open an account with the casino, you must type `!casino join`. After that you can start earning chips with `!casino payday`. To check your chip balance, type `!casino balance`. Additionally, you may convert your regular credits to casino credits by using `!casino exchange`.

Commands | Functionality
--- | ---
`!casino join` | Open an account.
`!casino payday` <br />`!cpd` | Earn 100 chips every 20 minutes.
`!casino balance` | Your casino balance.
`!casino leaderboard` <br />`!clb` | Show the Casino Leaderboard.
`!casino exchange <currency> <amount>` | Exchange chips for credits and credits for chips.
`!casino exchange credits 20` | Convert 20 credits into casino chips.
`!casino exchange chips 40` | Convert 40 chips into credits.

## Games

Here are some standard casino games.

Commands | Functionality
--- | ---
`!bj <bet>` | Blackjack
`!coin <head/tail> 10` | Bet on heads or tails
`!cups <cup> <50-500>` | Pick the cup that is hiding the gold coin. Choose 1 to 4
`!dice <50-500>` | Roll 2, 7, 11 or 12 to win.
`!hilo <High/Low/7> 20` | Pick High, Low, 7. Lo is < 7 Hi is > 7.
`!war 20` | War Card Game.

## Heist

The objective of heist is to form a crew to hit targets (banks). The easiest way to understand what it does it to just participate in one. If you want to rally a crew to hit targets, you might want to mention the **@Heist** role. This is a self-assignable role on the server. You may toggle this role with `!togglerole heist`.

Commands | Functionality
--- | ---
`!heist play` <br />`!hplay` | Play in a heist.
`!heist revive` <br />`!hrevive` | If you die, this will revive you.
`!heist release` <br />`!hrelease` | If you are in jail, this will free you.
`!heist bailout` <br />`!hbailout` | If you want to pay your way out and join a heist.
`!heist stats` <br />`!hstats` | Show your current status (dead, alive or in jail.)
`!toggleheist` | If you want to know when the next Heist takes place. Members can use `!togglerole heist` also. `!toggleheist` was written mainly for visitors.
`!pay <amt> [members...]` | Split the money equally amongst everyone.
`!pay 50 SML` | Pay 50 credits to SML.
`!pay 100 SML 6John Meridian` | Split 100 credits equally to SML, 6John and Meridian. Some rounding errors may occur if it can’t be divided equally.
