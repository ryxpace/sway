## unmaintained needs contributors or maintainer

* WIP at the moment try it and report if you want to contribute!
* https://github.com/EndeavourOS-Community-Editions/sway/blob/main/setup_sway_isomode.bash
* [July 2024] start getting big fixes and changes from BluishHumility
  
# Sway-WM Setup and Theme for EndeavourOS

**Sway EndeavourOS Community Edition**

[![Maintenance](https://img.shields.io/maintenance/yes/2024.svg)]()

## To Install Sway

### With the EOS Installer

1. In the live environment, choose "Fetch your install customization file" from the Welcome app.
2. Type or paste the URL for the Sway user_commands.bash file.
```
https://raw.githubusercontent.com/EndeavourOS-Community-Editions/sway/main/setup_sway_isomode.bash
```
![welcome_install-file](https://github.com/user-attachments/assets/0e6d57c2-1254-4179-8084-8797b9644682)

3. Click <kbd> OK </kbd>, then proceed with the installation normally. Be sure to choose "no desktop" on the DE selection screen.

![installer_no-desktop](https://github.com/user-attachments/assets/ca5582a9-094e-45d7-af1a-ebcf45e4dea5)

### Manually (Post-Installation)

    git clone https://github.com/EndeavourOS-Community-Editions/sway.git

    cd sway

    sudo ./sway-install.sh
   
You can examine the contents of the script here: https://github.com/EndeavourOS-Community-Editions/sway/blob/main/sway-install.sh
    
## Post install

- Keyboard layout in: `~/.config/sway/config.d/input`
- Screen settings in: `~/.config/sway/config.d/output`
- Keybindings Cheatsheet: press keyboard icon in waybar

- If your experiencing issues with your cursor - edit file `/etc/greetd/regreet.toml` and uncomment `export WLR_NO_HARDWARE_CURSORS = "1"`     
 
## Get involved at our forum:
https://forum.endeavouros.com/t/sway-edition-general-conversation

## Tutorial for sway-wm settings:

 - Background handled by swaybg
 - Filebrowser = Thunar
 - Default Terminal-Emulator = Foot
 - Text-Editor = xed/nano
 - Bar = Waybar
 - Sound = Pulseaudio

Main shortcuts: `~/.config/sway/cheatsheet`


<kbd>MOD</kbd> key is set to the <kbd>WINKEY</kbd>/<kbd>LINKEY</kbd>

 - <kbd>MOD</kbd>+<kbd>Return</kbd> = open floating terminal (Foot)
 - <kbd>MOD</kbd>+<kbd>O</kbd> = open Browser (firefox)
 - <kbd>MOD</kbd>+<kbd>N</kbd> = open File Manager (thunar)
 - <kbd>MOD</kbd>+<kbd>D</kbd>= app menu (Fuzzel)
 - <kbd>MOD</kbd>+<kbd>Q</kbd> = close focused app [kill]
 - <kbd>Shift</kbd>+<kbd>PrtSc</kbd> = screenshot/bring up screenshot menu
 - <kbd>MOD</kbd>+<kbd>SHIFT</kbd>+<kbd>E</kbd> = power-menu
 - <kbd>MOD</kbd>+<kbd>R</kbd> = resize mode
 - <kbd>MOD</kbd>+<kbd>SHIFT</kbd>+<kbd>SPACE</kbd>  = float window
     - <kbd>MOD</kbd>+<kbd>HOLD DOWN</kbd> = drag floating window
 - <kbd>MOD</kbd>+<kbd>↑ ↓ → ←</kbd>  = switch focus respectively 
 - <kbd>MOD</kbd>+<kbd>SHIFT</kbd>+<kbd>MINUS</kbd> = send to scratchpad
 - <kbd>MOD</kbd>+<kbd>MINUS</kbd> = cycle through scratchpad
 
 
 

## Tiling:

Is set to default for swaywm and can be changed to:

- stacking: Only the focused window in the container is displayed. You get a list of windows at the top of the container. 
   - <kbd>MOD</kbd>+<kbd>S</kbd> = Vertical List
   - <kbd>MOD</kbd>+<kbd>W</kbd> = Horizontal List
     - navigate lists with <kbd>MOD</kbd>+<kbd>↑ ↓ → ←</kbd> 
   - <kbd>MOD</kbd>+<kbd>E</kbd> = Back to tiling
   


![sway](https://forum.endeavouros.com/uploads/default/original/3X/b/c/bc09b71d718cb09a8efd4545cc65366c5f855441.png)

![fuzzel](https://github.com/user-attachments/assets/88fdbf21-83b6-44b3-a2c4-c84cbfcac585)

Waybar :
![waybar](https://forum.endeavouros.com/uploads/default/original/3X/7/3/73b22b2a678c6836c3b2d15747b0ef28e064fbc2.png)

