# Seoul256 Windows Terminal Color Scheme
A conversion of [junegunn/seoul256](https://github.com/junegunn/seoul256.vim) Vim color scheme to Windows Terminal color scheme format.  

The conversion was done using the [stevensnicole/winterm-themes](https://github.com/stevensnicole/winterm-themes/blob/master/README.md#setting-up-your-own-theme-and-converting-one-from-iterm2-1) README. The Powershell tool was used to convert [seoul256.itermcolours](https://github.com/junegunn/seoul256.vim/blob/master/iterm2/seoul256.itermcolors) to an intermediate format which I used to fill out the json format used by Windows Terminal. The intermediate output is saved to `seoul256.txt`. The JSON is filled out was filled out without thinking too much about it, if any colors are not used correctly, feel free to adjust them.

## Usage

1. Copy the contents of [seoul256.json](https://github.com/solanyn/seoul256-windows-terminal-color-scheme/seoul256.json) to your Windows Terminal `settings.json` file, under `profiles` -> `schemes`.

2. Select `seoul256` as your new color scheme for any given shell.

3. Enjoy!
