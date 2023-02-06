    

<center>
    <h4 align="center">This is a spotify ad blocker i found. It works pretty well for me.</h4>
    <p align="center">
        <strong>Last updated:</strong> uuuuuhhh now i guess <br>
        <strong>Last tested version:</strong>this one
    </p> 
</center>

### Features:

- It blocks all video, audio, and banner ads
- no more logging
- you can skip any track
- you can optionally block spotify updates
- you can enable experimental features which are fun
- And you can hid basically anything you want on the home screen
### Installation/Update:

- close spotify
- paste this in a terminal:

```
bash <(curl -sSL https://raw.githubusercontent.com/KieranK07/AdsSuck/main/install.sh)
```

#### optional stuff:
`-c`  Clear app cache -- use if UI-related patches aren't working  
`-e`  Experimental features -- enables experimental features  
`-E`  Exclude feature -- disables specified feature(s) [currently disabled]  
`-f`  Force patch -- forces re-patching if backup detected  
`-h`  Hide podcasts, episodes and audiobooks on home screen  
`-o`  Old UI -- skips forced 'new UI' patch  
`-p`  Premium subscription setup -- use if premium subscriber  
`-P`  Path to Spotify.app -- set custom Spotify app path  
`-u`  Update block -- blocks automatic updates  

Use any combination of flags.  
The following example clears app cache, adds experimental features, leaves new UI enabled and blocks updates:
    
```
bash <(curl -sSL https://raw.githubusercontent.com/KieranK07/AdsSuck/main/install.sh) -ceu
```


### Uninstall:

- Close Spotify.
- Run The following command in Terminal:

```
bash <(curl -sSL https://raw.githubusercontent.com/SpotX-CLI/SpotX-Mac/main/uninstall.sh)
```

or

- Reinstall Spotify

### Notes:

- Audio/video ads during Podcast playback are currently NOT blocked with SpotX.
- Spicetify users: When using SpotX-Mac + Spicetify, the current script requires running SpotX first.

### DISCLAIMER

- Ad blocking is the main concern of this repo. Any other feature provided by SpotX-Mac or consequence of using those features will be the sole responsibility of the user, not BlockTheSpot/SpotX/SpotX-CLI/SpotX-Mac.

### Credits

- Thanks to [SpotX - amd64fox](https://github.com/amd64fox/spotx).
- Thanks to [@jetfir3](https://github.com/jetfir3) for the extended contribution
