# aimWatch
This is the simple overwatch cheat that was written slowly and used a few times. It has been optimized for use with my sensitivity settings, I will include those. The cheat has been written in C# and the search algorithm is pretty fast. Itis not the prettiest code, but it works.

The software compiles as Dropbox.exe. I used a custom-made obfuscator and packer to create unique copies for me and my friends to lower the chance of getting banned.

## Features
 * Aimbot
 * Anabot
 * Widowbot (experimental, functional but situational)
 * Multiple resolutions supported (can be added easily)
 
### Aimbot
The aimbot works by using a custom pixel search function, looks for a specific color (with optional tolerance) and moves the mouse to the target. It is possible to enable force headshot for heroes like Widowmaker or Tracer in certain situations. To toggle force headshot, see the commands section below. By default the cheat only corrects the X-axis making it look a lot more legit.

### Anabot
The anabot works similar to the aimbot by looking for a specific color. When a teammate gets damaged the little arrow underneath their healthbar turns orange/yellow, this is the color the bot is looking for.

### Widowbot
The "widowbot" looks for the color of the outline around a hero. This only works on short to medium range since on long range the outline changes color to orange. With a few modifications you can probably detect multi-color. It is recommended to combine this with Force Headshot.

## Commands
### Force Headshot
To force headshot, just use numpad 1

### Anabot
To activate anabot, type in cmd "anabot.toggle"

### Force antishake
For the mouse to move less, type in cmd "aimbot.antishake"

## In-game settings

- I'm using sentivity 10.00 ~15.00
- 400 dpi (generic mouse)
- Works on 1920x1080 and 1280x720
- Windowed Borderless


## Future
- Additional settings read by a .ini file
- Create profiles
- Fix triggerbot

## Contact
You can post an issue in the repo and I will check them out. I will push changes I make when I feel like actually working on this project. I will see if I can write a wiki overtime.
