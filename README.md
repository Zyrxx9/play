# Discord Rich Presence (WITH BUTTONS) !!
- Discord RPC with 2 clickable buttons and more!

## CONFIGURING/SETTING UP
- You must have an application created in [Discord Developers Portal](https://discord.com/developers/applications)
- If you do not already have one, create one, and put its id in config.json > line 2 replacing "ID-HERE" with your id between "".
- In your application, go to Rich Presence > Art Assets and upload your desired photo.
- Whatever you name that picture, you must insert that in config,json > line 3 replacing "NAME-OF-LARGE-IMAGE" with the name between "".
- Put any text in configjson > line 4 which will show once you click on the image.
- Put any text for details that'll display next to the large image in config.json > line 5.
- The last 4 lines is very explanatory. Simply name your button names and the url accordingly!
- You must have a game running on your discord app for the rpc status to connect! 
- Lastly, after configuring all that shit, simply run launch.bat !!
- Enjoy!

## CONFIG EXAMPLE
```js
{
    "clientid": "880509929990008832",
    "largeimage": "yt_logo",
    "details": "Watching YouTube",
    "button1": "Button 2",
    "url1": "youtube.com/ipuppytech",
    "button2": "Button 1",
    "url2": "youtube.com/ipuppytech"
}
````


