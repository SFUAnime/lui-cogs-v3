# lui-cogs-v3
Custom cogs for Red-DiscordBot v3, used by the SFU Anime Club.

## Cogs
Below are some of the cogs we have. 

### Ready
- `birthday`: Ping a guild member on their birthday, and assign a special role to
   them.
- `goodsmileinfo`: Post updates from Good Smile Company to a guild text channel.
- `highlight`: Get notified outside of at-mentions about words that you care about.
- `heartbeat`: Ping an uptime checker to report that all is well with the bot.
- `respects`: Press f to pay respects. Has the ability to group multiple `f`s into
  one message, and supports replies.
- `roleassigner`: Randomly assign roles to guild members from a pool of roles. Can
  also remove roles from guild members from a pool of roles. 
- `servermanage`: A cog to manage a server's icon and banner images. It can schedule
  icon and banner changes on certain days at midnight.
- `sfu`: Access publicly available information from Simon Fraser University,
  including campus webcams, course information, and road report.
- `spoilers`: A v3 port of our legacy v2 emoji-based spoiler cog, before Discord
  implemented spoilers natively in the client.
- `tags`: A v3 port of tags from Rapptz's RoboDanny bot, with additional functions
  such as limiting the number of tags per role, ability to transfer ownership of
  tags. Generic tags are disabled.
- `triggered`: A triggered GIF image creator.
- `welcome`: Welcome a new guild member with a custom message in a guild text
  channel. Also has the ability to send them a DM with a custom message, and logging
  member names and IDs when they join and leave a guild to a particular text channel.
- `wordfilter`: Regular expression-based filtering, with the ability to turn it off
  in exceptional cases such as moderators or above, or in certain channels. Includes
  hooks for other cogs to use.
- `yourlsClient`: Control your YOURLS instance from Discord! Configurable on a per
  guild basis.

### Experimental
- `afterhours`: An SFU Anime Discord-specific cog used to add special exceptions. It
  is used in tandem with the `tempchannels` cog. Its usage is limited outside the
  scope of this guild.
- `avatar`: Save avatar images of all users when they change, which is useful for
  making videos for the server. Requires backend console access.
- `catgirl`: A v3 port of my previous catgirl cog on v2. Needs refactoring. Adding
  new images requires backend console access.
- `rss`: An RSS feed poster. Requires backend console access.
- `smartreact`: A v3 port of smartreact from flapjax/FlapJack-Cogs. There is probably
  a v3 port from the original author.
- `stats`: WIP.
- `tempchannels`: Create 1 temporary channel that is automatically deleted after the
  configured duration expires.

## Important Notes
1. `highlight`
    - Requires `utils/paginator.py` from [Rapttz/RoboDanny](
      https://github.com/Rapptz/RoboDanny) to be installed in `redbot/core/utils/`.
      This requirement is being removed soon.
2. `tags`
    - Using the alias toggle requires modification to Red's Alias cog.
    - Requires `utils/paginator.py` from [Rapttz/RoboDanny](
      https://github.com/Rapptz/RoboDanny) to be installed in `redbot/core/utils/`.
      This requirement is being removed soon.
3. `wordfilter`
    - Requires `utils/paginator.py` from [Rapttz/RoboDanny](
      https://github.com/Rapptz/RoboDanny) to be installed in `redbot/core/utils/`.
      This requirement is being removed soon.


## Support
As this is a side project, I am not able to provide support in a particularly timely
manner. That being said, if you find any issues, please feel free to open an issue in
the [SFUAnime/Ren](https://github.com/SFUAnime/Ren) repo, and we can take a look into
it.
