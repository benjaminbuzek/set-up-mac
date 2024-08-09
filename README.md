# set-up-mac

This repository contains instructions and scripts for setting up a new Mac. Follow the steps to configure essential tools, applications, and settings to get your Mac up and running. All paid applications or services are indicated by $.

This setup is mostly based on personal preferences and needs.

## ⚙️ General Settings

- [ ] Install [Homebrew](https://brew.sh/) package manager
- [ ] Install [dotfiles](#)

### Finder

- [ ] Add Developer directory
- [ ] Show Library directory with `chflags nohidden ~Library`

### Dock

- [ ] Activate "Automatically hide and show the Dock"
- [ ] Changed default web browser to Google Chrome

### Mail

- [ ] Add all E-Mail accounts
- [ ] Configure IMAP/SMTP settings 

### Fonts

- [ ] Install [SF Fonts](https://developer.apple.com/fonts/)
- [ ] Install [JetBrains Fonst](https://www.jetbrains.com/lp/mono/)
- [ ] Install [Nerd Fonts](https://www.nerdfonts.com/font-downloads)
  - [ ] FiraCode Nerd Font
  - [ ] FiraMono Nerd Font

## ⚙️ Developer Settings

### Setup Git

- [ ] Install [Git](https://git-scm.com/download/mac)
- [ ] ($) Install [Tower]() Git client

### Setup Terminal

- [ ] Install [iTerm2](https://iterm2.com/index.html) terminal
- [ ] Install [Starship](https://starship.rs/) custom prompt

### Setup JetBrains

- [ ] Install [JetBrains Toolbox](https://www.jetbrains.com/toolbox-app/)
- [ ] ($) Install JetBrains IDEs
  - PyCharm
  - IntelliJ
  - Ryder
  - WebStorm

### Setup VS Code

- [ ] Install [VS Code](https://code.visualstudio.com/download)

## ⚙️ Other

### App Store Applications

- [ ] Install [Goodnotes](https://apps.apple.com/at/app/goodnotes-6/id1444383602?l=en-GB)
- [ ] Install [WhatsApp Desktop](https://apps.apple.com/at/app/whatsapp-messenger/id310633997?l=en-GB)

### Third-Party Applications

- [ ] Install [Discord](https://discord.com/)
- [ ] Install [Google Chrome](https://www.google.com/intl/en-gb/chrome/)
  - Add [Clear Cache](https://chromewebstore.google.com/detail/clear-cache/cppjkneekbjaeellbfkmgnhonkkjfpdn)
  - Add [DeepL Translate](https://chromewebstore.google.com/detail/deepl-translate/cofdbpoegempjloogbagkncekinflcnj)
  - Add [Grammarly](https://chromewebstore.google.com/detail/grammarly-ai-writing-and/kbfnbcaeplbcioakkpcpgfkobkghlhen)
  - Add [uBlock Origin](https://ublockorigin.com/de) ad blocker
  - (Academic) Add [Google Scholar](https://chromewebstore.google.com/detail/google-scholar-button/ldipcbpaocekfooobnbcddclnhejkcpn)
  - (Academic) Add [Semantic Scholar](https://chromewebstore.google.com/detail/semantic-scholar/kboocjlbbkedggcpllfoigfnhieejebk)
  - (Academic) Add [Zotero Connect](https://chromewebstore.google.com/detail/zotero-connector/ekhagklcjbdpajgpjgmbionohlpdbjgc)
- [ ] Install [Google Drive Desktop sync](https://support.google.com/drive/answer/10838124?hl=en-gb)
- [ ] Install [Logi Options](https://www.logitech.com/en-gb/software/options.html)
- [ ] Install [Obsidian](https://obsidian.md/)
  - Setup sync with Apple iCloud
- [ ] Install [Signal Desktop](https://signal.org/)
- [ ] Install [Zoom](https://zoom.us/)
- [ ] Install [Zotero](https://www.zotero.org/support/installation)
  - Setup sync with WebDAV Server

### Services

- [ ] Configure iMessage
- [ ] Disable app dock bouncing `defaults write com.apple.dock no-bouncing -bool TRUE`
- [ ] Configure hosts file [`/etc/hosts`](https://gist.github.com/consti/8022703)
- [ ] 
