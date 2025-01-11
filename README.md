Discord Music Bot

A simple Discord music bot with the ability to join voice channels, play audio from YouTube URLs, and control playback. It also has a graphical interface to manage the bot's status and functionality.

Features

- Join Voice Channel: Use the !join command to have the bot join your voice channel.
- Play Audio from URL: Use the !play <URL> command to play audio from a YouTube link.
- Stop Audio: Use the !stop command to stop any audio currently playing.
- Shutdown Bot: Use the !shutdown command to shut down the bot.
- Graphical Interface: The bot has a Tkinter-based graphical interface to manage the bot's status and control it.

Installation

1. Clone this repository:
   git clone https://github.com/Kulisekdev/discord-music-bot.git

2. Install the required dependencies:
   pip install discord.py yt-dlp

3. Make sure you have `ffmpeg` installed on your system, as it is required for audio playback. You can download it here:
   https://ffmpeg.org/download.html

Usage

1. Run the script, and a Tkinter GUI window will open.
2. Enter your Discord bot token in the provided input field.
3. Click on "Run" to start the bot.
4. Use the following commands in your Discord server to interact with the bot:
   - !ping: Returns "Pong!"
   - !join: Makes the bot join the voice channel you are in.
   - !play <URL>: Plays audio from the specified YouTube URL.
   - !stop: Stops the currently playing audio.
   - !shutdown: Shuts down the bot.

Credits

Made by Kulíšek

- [Discord](https://discord.gg/aUQTeSymYR)
- [GitHub](https://github.com/Kulisekdev)

License

MIT License

