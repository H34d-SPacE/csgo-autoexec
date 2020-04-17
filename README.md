# CS:GO Autoexec
Here is my collection of configs used for my CS:GO autoexec config. It's useful and handy for me. I'm putting it out there incase someone else thinks it's useful for them. 
If you like it leave a like or comment on the video.

### Video Demonstration
Here's a little demo of my config in action.
* [![H34dSPace's CS:GO config demo](https://img.youtube.com/vi/MbmYBsV9rOU/mqdefault.jpg)](https://youtu.be/MbmYBsV9rOU)

## Installation

Download `_autoexec` folder and `autoexec.cfg`
Save them to your CS:GO config directory: 
* All Users(System install):
  * `${STEAM_DIR}/steamapps/common/Counter-Strike Global Offensive/csgo/cfg`
* Single User:
  * `${STEAM_DIR}/userdata/${SingleUserID}/730/local/cfg`

* **${STEAM_DIR}** typically `C:/Program Files/Steam`
* **${SingleUserID}** is your `STEAMID number`.

#### Set Launch Options
To force execute it every start you need to add the following to your launch options:
```
+exec autoexec
```
To get to your launch options:
* Go to game page in Steam Library
* Settings Cog
* Click `Properties`
* Click button `Set Launch Options...`
* Paste the code above in the box.
* Click `Ok`


## Configuration Explinations

**_main.cfg**

Runs the other files.

**scripts.cfg**

Contains a bunch of help aliases and binds 

**buys.cfg**

All the buy binds plus display

**audio.cfg**

Basic sound settings

**crosshair.cfg**

Crosshair configuration loader. Keep all crosshair configs in the crosshairs directory and set your default in crosshairs/default.cfg. Use the aliases set in here to change crosshairs.

**hud.cfg**

HUD placement, colours, etc

**mouse.cfg**

Mouse sensitivity settings

**viewmodel.cfg**

Adjust play viewmodel, left/right hand, etc

**optimizations.cfg**

You shouldn't need to touch this unless a particular setting is giving you troubles

**misc.cfg**

Other random configs

**practice.cfg**

Resets server variables for solo practice. Good for nade lineups and more.


## Credits
* [Base Concept(Ryzer)](https://github.com/ryzr/csgo-autoexec)
* [Config Ideas(KiloSwiss)](https://gist.github.com/KiloSwiss/a015b0620284ce74b5ed849ec599e51e)
* [MultiBound Keys](https://settings.gg/bananagaming)

## License

You're free to use, modify, redistribute, etc as you please. Attribution is appreciated.
