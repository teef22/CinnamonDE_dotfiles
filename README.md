## Setup guide
`dconf` setup of a binary form is stored in `~/.config/dconf/`. You can put this repo to that path for consistency.

To apply configs from `cinnamon.dump` to your Cinnamon DE in use run:
```zsh
dconf load /org/cinnamon/ < cinnamon.dump
```
On altering your Cinnamon DE config, you can apply updates to text-based dump by running:
```zsh
dconf dump /org/cinnamon/ > cinnamon.dump
```
