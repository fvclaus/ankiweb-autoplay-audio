# AnkiWeb Autoplay Audio Userscript

This user script enables autoplay for AnkiWeb almost identical to the native apps. There is only one catch. It doesn't work on the first card, because browsers require users to interact with the page before playing an audio file. It works with multiple audio files (they are played in order one after the other) on both the front and the back side. 
<br>
<img src="doc/demo.gif" width="800"/>

# Installation
Install [Tampermonkey](https://www.tampermonkey.net/) and then open the user script: [here](https://github.com/fvclaus/ankiweb-autoplay-audio/raw/refs/heads/main/ankiweb_autoplay_audio.user.js).
It should open the Tampermonkey plugin
<img src="doc/tampermonkey_installation.png" width="800">

## Troubleshooting

Open the developer tools and check if the script is outputting something to the console:
<br>
<img src="doc/developer_tools.png" width="600"/>

