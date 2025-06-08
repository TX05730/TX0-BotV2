<h1 align="center">
  <br>
  <a href=""><img src=".imgs/photo_2025-05-28_16-53-09.jpg" alt="TX0 Bot"></a>

</h1>

<h4 align="center">A New Tool for easy Hacking. </h4>

<p align="center">

  <a href="http://python.org">
    <img src="https://img.shields.io/badge/python-v3-blue">
  </a>
  <a href="https://php.net">
    <img src="https://img.shields.io/badge/php-7.4.4-green"
         alt="php">
  </a>

  <a href="https://en.wikipedia.org/wiki/Linux">
    <img src="https://img.shields.io/badge/Platform-Linux-red">
  </a>

</p>


### Features:

- Obtain Device Information Without Any Permission !
- Access Location [SMARTPHONES]
- Access Webcam
- Access Microphone

<br>

### Update Log:

- Second (latest) Update on July 8th , 2025 .
- The overall structure of the tool is programmed from the beginning and is available as a web panel (in previous versions, the tool was available in the command line).
- Previous version's bugs fixed !
- Auto-download Ngrok Added !
- The templates have been optimized !
- Logs can be downloaded (NEW) !
- Clear log Added !
- It can be uploaded on a personal host (you won't have the Ngork problems anymore)
- You can start and stop the listener anytime ! (At will)
- Beautified user interface (NEW) !

> We have deleted Ngrok in the new version of TX0-Bot and entrusted the user with running and sharing the localhost . So please note that TX0-Bot runs a localhost for you and you have to start the Ngrok on your intended port yourself .
> <br>



## Usage

```bash
python3 TX0-BotV2.py -h

usage: TX0-BotV2.py [-h] [-k KML] [-p PORT] [-u] [-v] [-t TEMPLATE] [-d] [--telegram token:chatId] [--webhook WEBHOOK]

options:
  -h, --help                            show this help message and exit
  -k KML, --kml KML                     KML filename
  -p PORT, --port PORT                  Web server port [ Default : 8080 ]
  -u, --update                          Check for updates
  -v, --version                         Prints version
  -t TEMPLATE, --template TEMPLATE      Auto choose the template with the given index
  -d, --debugHTTP                       Disable auto http --> https redirection for testing purposes 
                                        (only works for the templates having index_temp.html file)
  --telegram                            Send info to a telegram bot, provide telegram token and chat to use
                                        format = token:chatId separated by a colon
  --webhook                             Send events to a webhook endpoint to be processed
                                        Note : endpoint must be unauthenticated and accept POST request

#########################
# Environment Variables #
#########################

Some of the options above can also be enabled via environment variables, to ease deployment.
Other parameters can be provided via environment variables to avoid interactive mode.

Variables:
  DEBUG_HTTP            Same as -d, --debugHTTP
  PORT                  Same as -p, --port
  TEMPLATE              Same as -t, --template
  TITLE                 Provide the group title or the page title
  REDIRECT              Provide the URL to redirect the user to, after the job is done
  IMAGE                 Provide the image to use, can either be remote (http or https) or local
                        Note : Remote image will be downloaded locally during the startup
  DESC                  Provide the description of the item (group or webpage depending on the template)
  SITENAME              Provide the name of the website
  DISPLAY_URL           Provide the URL to display on the page
  MEM_NUM               Provide the number of group membres (Telegram so far)
  ONLINE_NUM            Provide the number of the group online members (Telegram so far)
  TELEGRAM              Provide telegram token and chat to use to send info to a telegram bot
                        format = token:chatId separated by a colon
  WEBHOOK               Provide the webhook url to forward the events to 
                        Note : endpoint should be unauthenticated and accept POST method
                        

#### Attention! :

>This program is not yet complete and bugs may occur as the script is still in its beta phase. Updates for the script will be available on my Telegram channel.

[![Telegram](https://img.shields.io/badge/Telegram-Join%20Now-blue?logo=telegram)](https://t.me/+JFIQ4ln2Cug3ZTdi)

> This version can be run on both local host and your personal domain and host . However , you can use it for both situations. If your country has suspended the Ngrok service, or your country's banned Ngrok, or your victim can't open the Ngrok link (for the reasons such as : He sees such a link as suspicious, Or if this service is suspended in his country) We suggest using the tool on your personal host and domain .
> <br>

## Default username and password:

- `username` : `admin`
- `password` : `admin`
 
  <br>

### Dependencies

**`TX0 Bot`** requires following programs to run properly -

- `php`
- `python3`
- `git`
- `Ngrok`

<!-- ![demo](.imgs/Work3.gif) -->
<br>



# ⚠️ Disclaimer

[![WARNING](https://img.shields.io/badge/⚠️%20ATTENTION-IMPORTANT-red)]()

This tool is protected by copyright.  
Any modification, redistribution, or public use is strictly prohibited without the explicit permission of the developer.  

If you wish to use, modify, or distribute this tool, you must obtain prior written consent from the developer **or give full credits to the original creator**.

Unauthorized distribution or use will be considered a violation of copyright law.

---

**Developer:** [TX05730](https://github.com/TX05730)

**YouTube**

<a href="https://odysee.com/@thewhiteh4t:2/seeker_v126_demo:e">
  <img src="https://thumbnails.odycdn.com/optimize/s:1024:768/quality:85/plain/https://thumbs.odycdn.com/5ce9ed06e0ce8a995987dba0949dbc9a.webp">
</a>

</p>
