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

-If you do not have GIT installed, install it
```
sudo pacman -S git
```
-After installing GIT write this command and restart your machine that my I3Gaps configuration will be configured on your machine


```
cd && git clone https://github.com/RenatohRibeiro/dotfiles && cd dotfiles/.config && mv i3 $HOME/.config && cd && cd dotfiles/.config && mv polybar $HOME/.config  && cd ~/.config/polybar && chmod +x player-mpris-tail.py && sudo pacman -S python-gobject python-dbus && cd && cd dotfiles && mv wallpapers $HOME && cd && rm -rf dotfiles
```

