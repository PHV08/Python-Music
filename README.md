# Discord Music Bot

A simple and efficient music bot for Discord that allows users to play music directly in voice channels. Built using Python and the Discord.py library, this bot is perfect for music lovers who want to enhance their Discord experience.

## Features

- Play music from various sources
- Skip tracks
- Adjust volume
- Display currently playing song information
- Help command for user guidance
- Customizable presence

## Requirements

- Python 3.8 or higher
- Discord.py library
- FFmpeg
- PyNaCl (for voice support)

## Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/discord-music-bot.git
cd discord-music-bot

Step 2: Install Dependencies
Make sure you have pip installed. Run the following command to install the required packages:

```bash
Copy code
pip install -r requirements.txt
Step 3: Set Up the Bot
Create a new application on the Discord Developer Portal.
Navigate to the "Bot" tab and click "Add Bot".
Copy the bot token and replace YOUR_BOT_TOKEN in the code with your actual token.
Adjust any other configurations as needed (such as prefix and commands).
Step 4: Run the Bot
Make sure FFmpeg is installed and accessible from your system path. Then run the bot using:

bash
Copy code
python main.py
Commands
!play {song name}: Play a song in the voice channel.
!skip: Skip the currently playing song.
!volume {percentage}: Set the volume (0-100%).
!help: Show a list of available commands.
Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

Credits
Author: PHV#3071
Project Repository: GitHub
Donations
If you enjoy this project and would like to support its development, consider donating through Buy Me a Coffee.

Thank you for your support!
