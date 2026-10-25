# fish

You need fisher to install the tide plugin
## How to install?
Assuming you already have fish
```sh
curl -sL https://raw.githubusercontent.com/jorgebucaran/fisher/main/functions/fisher.fish | source && fisher install jorgebucaran/fisher # This will install the fisher plugin manager
```
then
```sh
fisher install IlanCosman/tide@v6 # This will install tide, it will then do a setup, you can just spam through it as you will later change the config
```


# Tide config

Clone this repo then in linux-ricing/fish/ do `source ./tide_config.fish`. It will import all tide variables, if there are no changes reopen your terminal or do `tide reload`
