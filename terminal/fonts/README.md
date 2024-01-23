# Fonts

All tools dependant of terminal colors and fonts.
To make everything in that repo works [Nerd Fonts](https://www.nerdfonts.com/font-downloads) are required

One fonts is enough. I am using [Hack](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.1.1/Hack.zip)


## Installing fonts

```bash
#!/bin/sh
HACK_INSTALL_PATH="$HOME/.local/share/fonts"

mkdir ${HACK_INSTALL_PATH}
cd "$(mktemp -d)"
curl https://github.com/ryanoasis/nerd-fonts/releases/download/v3.1.1/Hack.zip -O hack.zip
unzip Hack.zip
cp *ttf ${HACK_INSTALL_PATH}
fc-cache -f -v
fc-list | grep "Hack"
rm -rf ttf && rm zip
cd -
```