# raspbian-motioneye-discord
For Raspbian and Motioneye, command to use for sending notification and picture to discord

I.INSTALLATION
  * install discord_webhook to format discord messages
    * https://pypi.org/project/discord-webhook/
    * sudo pip install discord-webhook
    
  * copy raspbian-motioneye-discord.py to motioneye folder (should be /home/pi/motioneye/)
  * edit raspbian-motioneye-discord.py
      - paste your DISCORD webhook URL
      - edit Camera lib filder if different
    
 II.USE IN MOTIONEYE
  * in command field, type :
    python /home/pi/motioneye/raspbian-motioneye-discord.py &
