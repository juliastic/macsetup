# Setup of new M1 Mac - Cheat Sheet

1. Connect with Apple ID & sync iCloud data
2. Change resolution of display → preferences
3. Install software
   1. Xcode → after installation run at least once
   2. iTerm2
   3. Homebrew (https://stackoverflow.com/a/67271753)
      * Execute: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
      * IF FILE NOT CREATED: `touch ~/.zshrc`
      * At the end: `export PATH=/opt/homebrew/bin:$PATH`
      * Run `source ~/.zshrc`
      * Verify: `brew help`
   5. zsh: `brew install zsh`
   6. oh-my-zsh: `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"` (https://github.com/ohmyzsh/ohmyzsh)
       * Configure its themes https://github.com/ohmyzsh/ohmyzsh/wiki/Themes (Agnoster is my go-to choice)
       * Modify `~/.zshrc`
       * Run `source ~/.zshrc`
       * Install required fonts & amend settings in iTerm2
   7. Sourcetree (https://www.sourcetreeapp.com/)
   8. Alfred (https://www.alfredapp.com/)
   9. Sublime: `brew install --cask sublime-text` (https://formulae.brew.sh/cask/sublime-text)
      * Set up "subl" command: Add `export PATH="/Applications/Sublime Text.app/Contents/SharedSupport/bin:$PATH"` to `~/.zprofile`
      * Run `source ~/.zprofile` (https://www.sublimetext.com/docs/command_line.html)
   10. IntelliJ Toolbox (https://www.jetbrains.com/toolbox-app/) (optional)
   11. Microsoft Office Suite (App Store)
   12. Visual Studio Code (https://code.visualstudio.com/docs/setup/mac)
   13. Java: `brew install openjdk`
   14. Mail program of your liking, e.g. Thunderbird (`brew install --cask thunderbird`) or Spark (App Store)
   15. Telegram, Signal, Spotify & WhatsApp: 
   ```
   brew install --cask telegram
   brew install --cask signal
   brew install --cask spotify
   brew install --cask whatsapp
   ```
3. Connect with Github account (https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git)
4. Create Developer folder: `mkdir ~/Developer` (for a nice icon) & fetch relevant projects
5. Setup task bar & dark mode → preferences
