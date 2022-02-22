# Setup of new M1 Mac - Cheat Sheet

1. Connect with Apple ID & Sync iCloud Data
2. Install software
   1. Xcode -> after installation run at least once
   2. iTerm2
   3. Homebrew (https://stackoverflow.com/a/67271753)
   4. zsh: `brew install zsh`
   5. oh-my-zsh: `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"` (https://github.com/ohmyzsh/ohmyzsh)
       * configure its themes https://github.com/ohmyzsh/ohmyzsh/wiki/Themes (Agnoster is my go-to choice)
       * modify `~/.zshrc` & run `source ~/.zshrc`
       * install required fonts & amend settings in iTerm2
   6. Sourcetree (https://www.sourcetreeapp.com/)
   7. Alfred (https://www.alfredapp.com/)
   8. Sublime: `brew install --cask sublime-text` (https://formulae.brew.sh/cask/sublime-text)
   9. Set up "subl" command: Add `export PATH="/Applications/Sublime Text.app/Contents/SharedSupport/bin:$PATH"` to `~/.zprofile` & run `source ~/.zprofile` (https://www.sublimetext.com/docs/command_line.html)
   10. IntelliJ Toolbox (https://www.jetbrains.com/toolbox-app/) (optional)
   11. Microsoft Office Suite (App Store)
   12. Telegram, Signal, Spotify & WhatsApp: 
   ```
   brew install --cask telegram
   brew install --cask signal
   brew install --cask spotify
   brew install --cask whatsapp
   ```
3. Connect with Github account (https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git)
4. Create Developer folder: `mkdir ~/Developer` (for a nice icon) & fetch relevant projects
