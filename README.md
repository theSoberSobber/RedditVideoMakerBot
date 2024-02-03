# Reddit Video Maker Bot 🎥
- THIS FORK IS NOT INTENDED FOR CONTRIBUTING TO UPSTREAM, THESE ARE MY MODIFICATIONS AND PROBABLY WON'T WORK FOR ANYONE ELSE
- Make sure you're on windows, I'll remove any and everything not Windows related in this fork.
- You need to keep clicking retry on the reddit site in the screenshot phase or it will timeout playwright.

# Todo - 
- make it read the post like for r/aita, config for that
- remove unnecessary tts crap and just use googlertranslte or pyttsx with male heavy voice

## Installation 👩‍💻

1. Clone this repository
2. Run `pip install -r requirements.txt`
3. Run `python -m playwright install` and `python -m playwright install-deps`
4. Run `python main.py`
5. Visit [the Reddit Apps page.](https://www.reddit.com/prefs/apps), and set up an app that is a "script". Paste any URL in redirect URL. Ex:google.com
6. The bot will ask you to fill in your details to connect to the Reddit API, and configure the bot to your liking
7. Enjoy 😎
8. If you need to reconfigure the bot, simply open the `config.toml` file and delete the lines that need to be changed. On the next run of the bot, it will help you reconfigure those options.

(Note if you got an error installing or running the bot try first rerunning the command with a three after the name e.g. python3 or pip3)

If you want to read more detailed guide about the bot, please refer to the [documentation](https://reddit-video-maker-bot.netlify.app/)

## LICENSE
[Roboto Fonts](https://fonts.google.com/specimen/Roboto/about) are licensed under [Apache License V2](https://www.apache.org/licenses/LICENSE-2.0)
