# Cleanup

Deletes messages.

Subcommand | Description
--- | ---
after     | Deletes all messages after specified message.
bot       | Cleans up command messages and messages from the bot.
messages  | Deletes last X messages.
self      | Cleans up messages owned by the bot.
text      | Deletes last X messages matching the specified text.
user      | Deletes last X messages from specified user.

## Examples

Command | Description
--- | ---
`!cleanup bot 4` | Deletes last 4 bot commands and messages from the bot.
`!cleanup messages 10` | Deletes last 10 messages.
`!cleanup text "test message" 3` | Deletes last 3 messages matching the specified text.
`!cleanup user 6` | Deletes last 6 messages from specified user.
