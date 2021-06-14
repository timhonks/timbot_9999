# TimBot_9999
A general-purpose bot with several of its own little gimmicks. What started as a passion project early February has become what it is today: a fully-fledged bot with moderation, configurability, logging and other fun commands.

[Add TimBot 9999 to your server!](https://discord.com/oauth2/authorize?client_id=807464203358830605&scope=bot&permissions=8)

[Need support for TimBot? Join this server!](https://discord.gg/q439qazkT5)

**What we have to offer:**
* Built-in, configurable chat filter (can be enabled, edited and removed).
* Built-in "alt detection" system (it just kicks members whose account age is under 15 days old).
* Built-in anti-Discord invite link system (can be enabled or disabled - more to come).
* General-purpose moderation commands (ban, kick, mute, purge, slowmode, lock, etc.).
* Audit logs for commands used, messages deleted or edited, members joining or leaving, and invites created.
* Level system (and leaderboards and ranks, too!)
* Gimmick commands - just add the bot and you'll see.

# CHANGELOG:
## June 1st update (v1.0.0):
**New commands:**
* Created poll command.
* Created anti-ad config command (enable or disable).
* Added ghost kick subcommand for `t.kick`.

**Quality of life:**
* Chat filter can now be enabled or disabled.
* Altinator kicks unverified bots by default.
* When typing the server prefix, the help command shows up instead of the roleinfo help panel.
* When typing TimBot's default prefix, `t.`, while the server prefix isn't the default prefix, the server's prefix will be shown.
* Reworked help command panels to be less cluttered.
* Reworked rank command embed to look a whole lot cleaner.
* Rank command now shows your rank, level and xp; it's a proper rank command now lol

## June 8th update (v1.0.1):
**Quality of life:**
* Original message is deleted before poll embed shows up.
* Rank progress bar shortened to look cleaner on mobile.
* You are now required to write a reason when using the remindme command.
* When editing or deleting messages:
    * Editsnipes and snipes now won't work on filtered words.
    * The edited message will be deleted if it includes a filtered word or if it includes more than 1000 characters.
* Timed commands are now shown in proper English.
    * "2m" will now be shown as "2 minutes".
* XP earned raised from between 5-12 to 10-25.

### June 9th hotfix (v1.0.2):
* Fixed an error making all channels viewable if the bot is added and if there is no "Muted" role.

## June 14th update (v1.1.0):
**New commands!**
* dadjoke: Tell a dad joke. Over 20 dad jokes added!
* truthordare: Truth or dare? Feeling lucky? 5 truths or dares to pick out from with your friends.
**Audit log updates:**
* Voice state updates are now logged!
    * The bot will record when a user joins, leaves or moves between voice channels.
* When a nickname is changed by someone else, the executor is logged as well.
**Quality of life:**
* XP updates:
    * XP will be rewarded when in a voice call - just join and you will earn 5 xp per minute.
    * When a user ranks up, a rankup embed will be sent as well as a message pinging the user.
* Leaderboard updates:
    * Leaderboards are now dynamic - the top 50 members are now displayed in leaderboards.
    * You can clear a specific user's stats using `lb clear [@user]`.
    * You can edit a sepcific user's stats using `lb edit <@user> <level> [xp]`
    * When resetting leaderboards, the message embed will edit itself rather than send two different embeds.
    * Leaderbaord actions are now logged.
* Usercount updates:
    * Usercount now displays the total users, members, and bots in your server.
* 8ball updates:
    * 8ball is now send in an embed.
    * 15 new 8ball lines.
* 1 new pickup line.
* Removed alias `prune` from purge command.