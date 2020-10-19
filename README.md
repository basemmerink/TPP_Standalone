# TPP Standalone
A standalone client of Twitch Plays Pokemon, that can be imported into OBS as browser source

# How to
- Download TPP.html
- Open it using any text editor (notepad, notepad++, Atom, etc..)
- Locate the oauth token and your twitch username at the top
- Change Baasbase into your twitch username, make sure to put it between the single quotes.
- Change the oauth token to the token generated at https://twitchapps.com/tmi/ (you will probably need to login using the twitch account with which you will be streaming this)
- Save the html file
- Create a new browser source in OBS
- Source is a local file -> the html file you just downloaded and edited
- Width: 640
- Height: 1152

And that's it! You are now free to resize the panel, and use alt+resize to remove the bottom part if you don't want the chat messages to appear on screen

# Saving and loading
If you are the streamer you can use **!save** to save the current state of the gameboy.  
Next time you will load the scene, it will automatically load the last saved state.  
If you want to start over, use **!delete** to delete the save state. *Warning: This does not ask for confirmation and can not be undone*.

# Credits
Using this is free. But please credit https://twitch.tv/baasbase somewhere in a twitch panel or on a label on screen. That way you will support me in making more awesome stuff like this ❤
