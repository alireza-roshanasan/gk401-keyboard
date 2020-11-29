# gk401-keyboard
control green gk401 keyboard backlight on ubuntu(20.04)

    git clone https://github.com/alireza-roshanasan/gk401-keyboard.git
    cd gk401-keyboard
    chmod +x ./backlight_toggle
    sudo cp ./backlight_toggle /usr/bin/
define shortcut to run **backlight_toggle** command

**if you had problem with switching layout do next steps:**

run below command to reset **gsettings**

    gsettings reset org.gnome.desktop.input-sources xkb-options
if you want to disable switching layout overlay:

*Tweaks -> Keyboard & Mouse -> Additional Layout Options -> Switching to another layout*

and select your switching layout shortcut