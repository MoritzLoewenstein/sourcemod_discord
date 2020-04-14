## Intro
This offers a native to send discord messages via a webhook.

## Requirements
This plugin only requires [SteamWorks](http://users.alliedmods.net/~kyles/builds/SteamWorks/).

## How to use
At the top of your `plugin.sp` :  
```
#include <discord>
#define DISCORD_WEBHOOK <your webhook url>
```
Where you want to send a message:
```
Discord_SendMessage(DISCORD_WEBHOOK, "Your Message");
```

## Contribute
Pull request for fixes/features are welcome.
If you have an issue you cant fix, create an issue.
