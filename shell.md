# Rockstar Shell 🎸

![Shell](./media/shell.png)

1. [Homebrew](https://brew.sh/)
   - Open Terminal
   - `$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
2. [iTerm2](https://www.iterm2.com/)
   - `$ brew cask install iterm2`
   - Close Terminal forever and open iterm2 😁
   - `⌘,` -> Preferences -> Appearance -> Theme, change it to `Dark` because cool devs use only dark themes 😎
   - Let's get even cooler, `⌘,` -> Preferences -> Profiles -> Colors -> Color Presets... and choose `Tango Dark`
   - Shortcuts
     - `⌘⇧D` split horizontally
     - `⌘D` split vertically
     - `⌘T` new tab
     - `⌘W` close currently focused terminal
     - `⌘[` / `⌘]` previous/next terminal
3. [zsh](http://zsh.sourceforge.net/)
   - `$ brew install zsh`
   - [oh my zsh](https://ohmyz.sh/)
     - `$ sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
4. Upgrade your style
   - edit `~/.zshrc` and set `ZSH_THEME="agnoster"`, or [choose another theme](https://zshthem.es/)
   - While in your `~/.zshrc`, add the following: `export DEFAULT_USER=$(whoami)` -- this will hide the `user@hotname` portion in the prompt.
   - install [Source Code Pro](https://github.com/powerline/fonts/blob/master/SourceCodePro/Source%20Code%20Pro%20for%20Powerline.otf)
   - Set the font in iTerm 2: `⌘,` -> Preferences -> Profiles -> Text -> Change Font, I prefer `Meslo LG M for Powerline`, 14pt
   - Just to make sure all the changes took effect, turn iTerm2 off and turn it on again (insert IT Crowd gif)
5. [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
   - `brew install zsh-autosuggestions`
   - Add the following to your `.zshrc`: `source /usr/local/share/zsh-autosuggestions/zsh-autosuggestions.zsh`
6. [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
   - `brew install zsh-syntax-highlighting`
   - Add `source /usr/local/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh` to the end of your `~/.zshrc` file
7. Integrate your slick new shell into VS Code
   - Since you are a rockstar, you're likely using VS Code. Add the following to your preferences to make sure your new customizations look just as nice in the VS Code integrated terminal.
   1. Go to settings: `⌘,`
   2. Add `"terminal.integrated.shell.osx": "zsh",` to ensure we're using zsh
   3. Add `"terminal.integrated.fontFamily": "Meslo LG M for Powerline",` so we have the right font family
   4. Also add `"terminal.integrated.fontSize": 14,` to set the font size
8. Resources for further customization:
   - https://gist.github.com/kevin-smets/8568070
   - https://code.tutsplus.com/tutorials/how-to-customize-your-command-prompt--net-24083
   - https://medium.com/@caulfieldOwen/youre-missing-out-on-a-better-mac-terminal-experience-d73647abf6d7
   - https://github.com/bhilburn/powerlevel9k/wiki/Show-Off-Your-Config
