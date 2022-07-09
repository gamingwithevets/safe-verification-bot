<h1 align="center">[Discord] - <del>Fake</del> Safe Verification Bot</h1>
<p align="center">Original script by AstraaDev, safe version by GWE</p>
<p align="center">Allows to create a verification QR code, that the user will have to scan on their arrival on the server. Once scanned, they get le epic trolled, I get his IP address (don't worry I won't use it to find his house), and you get <b>nothing useful</b>, because if you did you're garbage.</p>

# Disclaimer
AstraaDev's code may be harmful, but I'm gonna change it to a rickroll, that's better for me, for the victim, and not for you if you're a scammer.

# Features

- Async QR Code Management
- Uses Websockets (no browser used)
- Personal (but same) QR Code (visible only to the user passing the verification)
- Gives a role to the user after verification
- Easy to use + Intuitive UI

# How to install
**Step 1.** Set up and invite your bot  
- Create a bot on the [Discord Developer page](https://discord.com/developers/applications).
- Go to the Bot tab, add a bot, then copy the token **(Important!)**
- Check all the intents
- Edit the `config.json` file. Make sure to input the bot token you copied earlier.
- Go to OAuth2 \> URL Generator.
- - For the scopes click `bot` and `applications.commands`. For the bot permissions click Administrator.
- - Copy the link and paste it in the address bar. Now simply add it to one of your ~~scam~~ servers.

**Step 2.** Run the Python script  
First, [go get Python](https://python.org) if you haven't.

Then, choose one of these two methods.

*Method 1:* Use an automated script **(Windows only!)**
Run the `setup.bat` file. This will automatically start the Python script.  
A new file will also be created, named `start_tool.bat` which you can use to run the Python script.

*Method 2:* Run the commands manually
- Open a terminal (Command Prompt/PowerShell on Windows).
- Before running the Python script, do these steps. If you already did, you can skip them.
- - Run `git clone https://github.com/AstraaDev/Fake-Verification-Bot.git` or download the script. If you have the script already you can skip this step.
- - Then, run `python -m pip install -r requirements.txt` inside the root of the repository folder.
- Run `python main.py` to run the Python script.
