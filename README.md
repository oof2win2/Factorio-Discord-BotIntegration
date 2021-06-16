# Factorio-Discord-BotIntegration
[Mod on the Mod Portal](https://mods.factorio.com/mod/Factorio-Discord-BotIntegration)

## Features:

- Log completed research
- Log when a player dies
- Allow integration with [AwF Bot](https://github.com/James-Hackett/AwF-Bot) (show deaths, research in Discord)
- Is developed by the same people as the bot, which allows better integration

This is a mod that allows the Discord [AwF Bot](https://github.com/DistroByte/AwF-Bot) to log achievements, deaths, and many other things to work
It is recommended to run with the existing bot, as it is already pre-made to mostly work (with a few replacements, working on fixing that). It should have virtually no impact on the game, as it only listens to already-made events and logs stuff to the console (see Features).
The mod is made to run on headless, as the headless version can have `.tail` and `.out` files enabled easily, although it can be made to run on headed if required.

Features:
- Log completed research
- Log when a player dies
- Log player joins & leaves
- Log rocket launches

Example output from AwF-Bot on Discord:
![](https://i.imgur.com/V7DJdOx.png)

The log file is in `script-output/ext/awflogging.out` due to the fact that it is used on [AwF](http://awf.yt) this exact way. 
