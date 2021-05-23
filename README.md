Now anyone can make their own **customized** discord bot

#### Introduction

Use this module to create professional discord bots in just a few lines of code. Created by Gfrkad to fulfill the wishes of gamers who want an awesome custom bot for their discord server.

- Short Code
- Easy to Learn and Understand
- Regular updates to functionality

### Code Format

```Python
from discord_bot_maker import DBot

d = DBot(prefix_tuple, TOKEN)
d.createCommand(trigger = trigger, reply = reply1, reply2 = reply2, emoji = emoji, image = link, help = help)
d.bRun()
```

### Example Program
```Python
from discord_bot_maker import DBot

d = DBot((".", "-", "bot", ), "{YOUR_TOKEN_HERE}")

d.createCommand(trigger = "jump", reply = "whoop!", reply2 = "I just jumped", emoji = "😄", image = "jumping.gif", help = "jumps")

d.bRun()
```

### Pre Made commands:

 - `commandHi(aliases : list, help : str, message : str, description : str, gif : str)` Adds Hi Command
 - `commandHelp(title : str, description : str)` Adds Help Message Command

### More Information

 - The Prefix Tuple can include as many prefixes as you may like
 - The **TOKEN** must be copied from [Discord Developer Portal](https://discord.com/developers/applications)
 - You can create as many commands as you like
 - The `bRun()` command is required to run the bot

##### Join our discord server [here](https://discord.gg/E5wXQGjxsd)
*version = 0.1.6*
