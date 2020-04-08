# dotfiles

## i3-Gaps

![Screenshot](https://github.com/RenatohRibeiro/dotfiles/blob/master/Home.png)

## Spicetify - (Spotify "mod")

![Screenshot](https://github.com/RenatohRibeiro/dotfiles/blob/master/Spotify.png)

| Dependency                                                                         | Description                                                 | Why/Where is it needed?         |
| ---------------------------------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------- |
| `i3-gaps`                                                                          | Window manager                                              | (explains itself)               |
| `polybar`                                                                          | Status bar                                                  | (explains itself)               |
| `rofi`                                                                             | Window switcher, application launcher and dmenu replacement | (explains itself)               |
| `picom`                                                                            | X Compositor                                                | Makes transparency to windows   |
| `nitrogen`                                                                         | Assistance in changing wallpapers                           | (explains itself)               |
| `spicetfy`                                                                         | Command-line tool to customize Spotify client               | (explains itself)               |

## Arch

If you use arch I will make things simpler for you, just install I3-gaps first, then copy and paste this below into the terminal

```
sudo pacman -S nitrogen spicetfy picom rofi polybar
```

-  If you do not have GIT installed, install it
```
sudo pacman -S git
```
-  After installing GIT write this command and restart your machine that my I3Gaps configuration will be configured on your machine


```
sudo git clone https://github.com/RenatohRibeiro/dotfiles && cd && cd ~/.config/polybar && chmod +x player-mpris-tail.py && pacman -S python-gobject python-dbus
```

