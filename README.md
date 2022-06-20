# My Starship Configuration

## Install

```shell
# install starship
brew install starship
# clone configurations
mv ~/.config/starship{,.backup} || true
git clone https://github.com/hezhizhen/starship.git ~/.config/starship
# set environment variable for fish
set -gx STARSHIP_CONFIG ~/.config/starship/starship.toml
```

## Screenshots

![](https://user-images.githubusercontent.com/7611700/174540008-13ad8c8b-7db0-44cb-86d5-41aa60be1c09.png)

## Credits

- [Pastel Powerline Preset](https://starship.rs/presets/pastel-powerline.html)
