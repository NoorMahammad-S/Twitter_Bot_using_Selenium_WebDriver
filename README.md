# ```Automation Project ```

# Internet Speed Twitter Bot

This is a Python script for a Twitter bot that measures your internet speed using Speedtest.net and tweets your internet service provider 
when your actual internet speed doesn't meet the promised speed. The bot is designed to run on Google Chrome using the Selenium WebDriver.

## Requirements

Before you get started, you'll need the following:

- Python 3.x
- Google Chrome installed on your system
- ChromeDriver (included in this repository for Windows, but you may need to download it separately for other platforms)
- Selenium Python library
- A Twitter account for tweeting to your internet service provider

## Installation

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/NoorMahammad-S/internet-speed-twitter-bot.git
   cd internet-speed-twitter-bot
   ```

2. Install the required Python libraries:

   ```
   pip install selenium
   ```

3. Edit the following variables in the code with your Twitter email and password:

   ```python
   TWITTER_EMAIL = "your email id"
   TWITTER_PASSWORD = "your password"
   ```

   Replace `"your email id"` and `"your password"` with your Twitter account credentials.

## Usage

1. Run the Internet Speed Twitter Bot:

   ```
   python internet_speed_bot.py
   ```

2. The bot will measure your internet speed using Speedtest.net and compose a tweet mentioning your internet service provider if the actual speed doesn't meet the promised speed.

3. The tweet will be posted on your Twitter account.

## Important Notes

- This script is for educational purposes and should be used responsibly.
- You may need to adjust the XPath expressions in the code to match the layout of the websites, as they can change over time.
- Ensure that your Twitter account has been verified and does not have restrictions on tweeting.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
