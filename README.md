# install compton
# install nitrogen

# install rofi
rofi-theme-selector - change theme rofi
# custom theme rofi in .config
mkdir rofi/
cd rofi/
touch config.rasi
https://github.com/lr-tech/rofi-themes-collection


# install poly-bar
sudo apt-get install polybar
# there is polibar config /etc/polibar/
https://www.youtube.com/watch?v=tOBDUBEMAKM

add the following lines to your configuration i3:
exec_always --no-startup-id $HOME/.config/polybar/launch.sh
and remove these
bar {
    i3bar_command i3bar
}
The first line executes the startup script; the second disables i3's default bar


# i3-gaps install guide
https://lottalinuxlinks.com/how-to-build-and-install-i3-gaps-on-debian/

# i3-lock 
https://github.com/meskarune/i3lock-fancy


# if wifi does't work
https://www.linuxbabe.com/debian/connect-to-wi-fi-from-terminal-on-debian-wpa-supplicant
