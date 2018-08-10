# macos-setup

This place serves to document how I set up my local development environments on Mac OS. Feel free to fork and make your own, and if you make something awesome, please share it back!

## [Shell](./shell.md)

### Shortcuts

- `⌘<space>` to open spotlight search, I use it to quickly open apps
- `^⌘<space>` to open the emoji window 🤓
- In Finder:
  - `⌘⇧D` to open Desktop
  - `⌘⇧H` to open Home
  - `⌘⇧.` to toggle show hidden files

### Screenshots

- `$ mkdir -p ~/screenshots`
- `$ defaults write com.apple.screencapture location ~/screenshots && killall SystemUIServer`

### Show Hidden Files

- Type this into your terminal: `defaults write com.apple.finder AppleShowAllFiles YES && killall Finder`
