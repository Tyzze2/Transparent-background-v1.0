# Transparent-background-v1.0
A simple css theme for Betterdiscord client 
- Stable 117300 (cc0861f) 
- BetterDiscord 1.5.2 
- Host 1.0.9004 
- Windows 10 64-Bit (10.0.19042)

I have created a theme that I want to share because during my research I did not find any Discord theme with a transparent background (or at least the ones I found were paying).
Anyway, here is a theme that I created / modified for people who want this thing ...
Ps: This theme has been modified by me but the basic theme is Gibbu's "FrostedGlass"
Source :
https://github.com/Gibbu/BetterDiscor...

# Mod
To reduce the transparency you have to open the theme file, then change the default value of these lines :

  --serverlist-brightness: 0.3;
  --left-brightness: 0.3;
  --middle-brightness: 0.3;
  --right-brightness: 0;
  --popout-modal-brightness: 0.5; 

For example if I increase the value of "left-brightness" to 1 the background of your friends will be darker ( 1 is the maximum value )

///// UPDATE 29/08/2021 :
open your theme file, then replace
@import url('https://discordstyles.github.io/FrostedGlass/base.css');
with
@import url('https://discordstyles.github.io/FrostedGlass/dist/FrostedGlass.css');
