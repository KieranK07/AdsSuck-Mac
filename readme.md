    

<center>
    <h4 align="center">This is my spotify ad blocker. It's made for macs so if you need windows adblockers, i'm working on one of those too.</h4>
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
bash <(curl -sSL https://raw.githubusercontent.com/KieranK07/AdsSuck-Mac/main/install.sh)
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
bash <(curl -sSL https://raw.githubusercontent.com/KieranK07/AdsSuck-Mac/main/install.sh) -ceu
```


### Uninstall:

- Close Spotify.
- paste this in a terminal:

```
bash <(curl -sSL https://raw.githubusercontent.com/KieranK07/AdsSuck-Mac/main/uninstall.sh)
```

or

- Reinstall Spotify

### Notes:

- audio/video ads during Podcast playback are currently NOT blocked with this thing.
- spicetify users: When using this program + Spicetify, the current script requires running it first.

### DISCLAIMER

- Ad blocking is the main concern of this repo. Any other feature provided by this or consequence of using those features will be the sole responsibility of the user, not me.
Note: this is a partial fork of SpotX.
