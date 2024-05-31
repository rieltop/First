
# Telegram Bot for Parsing OLX

## Overview
This project is a Telegram bot designed to parse real estate listings from OLX and save the data to an Excel file. The bot also includes Google account authentication with two-factor authentication.

## Installation
1. Clone the repository.
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Configure your Google client credentials in `bot/config.py`.
4. Run the bot:
   ```
   python bot/main.py
   ```

## Usage
The bot will automatically parse new listings every 15 minutes and save the data to `ads.xlsx`.

## Testing
Run the tests using:
```
python -m unittest discover tests
```
