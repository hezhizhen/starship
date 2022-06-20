# My Starship Configuration

## Install

```shell
# install starship
brew install starship
# clone configurations
mv ~/.config/starship{,.backup} || true
git clone https://github.com/hezhizhen/starship.git ~/.config/starship
# set environment variable
export STARSHIP_CONFIG=.config/starship/starship.toml
```
