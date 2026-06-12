# 1. Update packages
pkg update && pkg upgrade

# 2. Install Python and required tools
pkg install python python-pip git

# 3. Install requirements
pip install -r requirements.txt

# Alternative if above fails:
pip3 install pyrogram pytgcalls cryptg colorama

# 4. Run the bot
python bot.py