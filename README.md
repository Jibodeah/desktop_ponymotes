# Desktop Ponymotes

## About

*Desktop Ponymotes* is a small program capable of downloading all the emotes from [BPM](http://ponymotes.net/bpm/) onto your computer. Where you can do whatever you want with them.

## Features

* Downloads new/updated emotes only.
* Fully configurable filtering. Filter based on emote names, tag, and/or subreddit.
* Capable of dealing with removed emotes. (They get moved to the 'archive' folder in your emote directory)

## Install

1. Satisfy the dependencies. (See below)
2. Download `desktop_ponymotes.py`, put it anywhere you want.

### Dependencies

* Python 3.3 or above.
* Third party python modules:
    * [requests](http://docs.python-requests.org/en/latest/)
    * [coloredlogs](http://coloredlogs.readthedocs.org/en/latest/)

`pip install requests coloredlogs`

## FAQ

### I accidentally deleted a few emotes from my library! Can I download only the ones I'm missing?

Yes! Simply run the program with the options `-f --skip-already-downloaded`.

### How do I enable download of NSFW emotes?

Set `allow_nsfw` to `true` in config.ini. The line should then read:

    allow_nsfw = true

## Special Thanks

* DinsFire, for allowing me to use the backend he built for his [PonyMotes Android App](http://dinsfire.com/projects/reddit-emotes/)

* Typhos, for making [BPM](http://ponymotes.net/bpm/) itself.

## Contact

You can find me here on github, or at [/u/Jibodeah](https://www.reddit.com/user/Jibodeah) on reddit.

Bugs? Wishes? Create an issue here on github, or message me on reddit.
