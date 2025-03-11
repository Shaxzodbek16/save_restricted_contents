# Telegram Restricted Content Saver Bot

A Telegram bot built with Aiogram that allows users to save and access restricted content from Telegram.

## Features

- Save restricted content from Telegram channels and groups
- Access saved content through the bot
- Support for various media types (photos, videos, documents, etc.)
- User-friendly commands for easy interaction

## Installation

```bash
# Clone the repository
git clone https://github.com/Shaxzodbek16/telegram-content-saver.git
cd telegram-content-saver

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Configuration

1. Create a `.env` file in the project root:

```
BOT_TOKEN=your_bot_token_from_botfather
```

2. Obtain a bot token from [@BotFather](https://t.me/BotFather) on Telegram

## Usage

```bash
# Start the bot
python main.py
```

### Bot Commands

- `/start` - Start the bot and get welcome message
- `/help` - Show available commands and usage instructions
- `/save` - Save content (forward a message to the bot)
- `/list` - List all saved content

## Technologies

- [Python](https://www.python.org/)
- [Aiogram](https://github.com/aiogram/aiogram) - Asynchronous Telegram Bot API framework
- [SQLite](https://www.sqlite.org/) (or your database of choice)

## License

MIT

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.