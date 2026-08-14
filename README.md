## Setup guide
Put this repo to `.config/dconf`.

To apply configs from `cinnamon.dump` to your Cinnamon DE in use run:
```zsh
dconf dconf load /org/cinnamon/ < cinnamon.dump
```
On altering your Cinnamon DE config, you can apply updates to text-base dump by running:
```zsh
dconf dump /org/cinnamon/ > cinnamon.dump
```
