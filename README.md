# Zam!Bot

This Discord bot is designed to play music from YouTube in voice channels. It offers various features such as queuing songs, controlling volume, pausing/resuming playback, skipping songs, shuffling the queue, and more. Additionally, it provides basic interaction commands like introduction and answering questions.

## Features

- Play music from YouTube
- Queue songs
- Control volume
- Pause/resume playback
- Skip songs
- Shuffle the queue
- Basic interaction commands (introduction, answering questions)

## Requirements

- Python 3.7 or higher
- discord.py
- youtube_dl
- async_timeout

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/SanelRyan/ZamBot.git
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up your Discord bot and obtain a token.

4. Create a `.env` file in the root directory of the project and add your Discord bot token:

   ```
   TOKEN=your-discord-bot-token
   ```

5. Optionally, configure other environment variables in the `.env` file.

## Usage

1. Run the bot:

   ```bash
   python bot.py
   ```

2. Invite the bot to your Discord server using the invite link generated when setting up your bot.

3. Use the bot's commands to play music, control playback, interact, etc.

## Commands

- `join`: Join a voice channel.
- `summon`: Summon the bot to a voice channel.
- `leave`: Leave the voice channel.
- `volume`: Set the volume of the player.
- `now`: Display the currently playing song.
- `pause`: Pause the currently playing song.
- `resume`: Resume a currently paused song.
- `stop`: Stop playing song and clear the queue.
- `skip`: Vote to skip a song.
- `queue`: Show the player's queue.
- `shuffle`: Shuffle the queue.
- `remove`: Remove a song from the queue.
- `loop`: Loop the currently playing song.
- `play`: Play a song from YouTube.

## Credits

This bot is based on [discord.py](https://github.com/Rapptz/discord.py) and [youtube_dl](https://github.com/ytdl-org/youtube-dl). Special thanks to the developers of these libraries.

## License

[MIT License](LICENSE)

