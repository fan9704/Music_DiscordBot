# MusicBot

[![GitHub stars](https://img.shields.io/github/stars/Just-Some-Bots/MusicBot.svg)](https://github.com/Just-Some-Bots/MusicBot/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Just-Some-Bots/MusicBot.svg)](https://github.com/Just-Some-Bots/MusicBot/network)
[![Python version](https://img.shields.io/badge/python-3.8%2C%203.6%2C%203.7-blue.svg)](https://python.org)
[![Discord](https://discordapp.com/api/guilds/129489631539494912/widget.png?style=shield)](https://discord.gg/bots)

MusicBot is the original Discord music bot written for [Python](https://www.python.org "Python homepage") 3.8+, using the [pycord](https://github.com/Pycord-Development/pycord) library. It plays requested songs from YouTube and other services into a Discord server (or multiple servers). Besides, if the queue becomes empty MusicBot will play through a list of existing songs with configuration. The bot features a permission system allowing owners to restrict commands to certain people. As well as playing songs, MusicBot is capable of streaming live media into a voice channel (experimental).

![Main](https://i.imgur.com/FWcHtcS.png)

## Setup
Setting up the MusicBot is relatively painless - just follow one of the [guides](https://just-some-bots.github.io/MusicBot/). After that, configure the bot to ensure its connection to Discord.

The main configuration file is `config/options.ini`, but it is not included by default. Simply make a copy of `example_options.ini` and rename it to `options.ini`. See `example_options.ini` for more information about configurations.

### Commands

There are many commands that can be used with the bot. Most notably, the `play <url>` command (preceded by your command prefix) will download, process, and play a song from YouTube or a similar site. A full list of commands is available [here](https://just-some-bots.github.io/MusicBot/using/commands/ "Commands").

### Further reading

* [Support Discord server](https://discord.gg/bots)
* [Project license](LICENSE)

### Depoly to Heroku
! should add buildpack cause this system not support Unix-like system
1. https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
2. https://github.com/xrisk/heroku-opus
! If you didn,t add these two buildpack music bot won,t play music not matter any condition

### User Guide
[Command]

play some youtube music
1. !play [youtube_url] 

Search a command relation method
2. !help [command]

Music playlist queue
3. !queue

Now music bot playing Music
4. !np

skip this music
5. !skip

shuffle this music queue
6. !shuffle

Clear this music queue
7. !clear

pasue now playing
8. !pause

resume now playing
9. !resume

modify music sound
10. !volume [number] 

Connect music bot to your current channel
11. !summon

add this currenet song to autoplaylist
12. !save