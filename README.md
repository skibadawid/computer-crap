- download [iTerm](https://iterm2.com)
  - enable option left [link](https://apple.stackexchange.com/questions/154292/iterm-going-one-word-backwards-and-forwards) 
- download [Homebrew]([https://ohmyz.sh](https://brew.sh))
- download [oh-my-zsh](https://ohmyz.sh)
  - using `sudo` in terminal
- install [spaceship](https://github.com/spaceship-prompt/spaceship-prompt)
  - follow their directions in terminal (through Oh-My-Zsh)
  
    Clone this repo:
    `git clone https://github.com/spaceship-prompt/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt" --depth=1`
    
    Symlink spaceship.zsh-theme to your oh-my-zsh custom themes directory:

    `ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"`

    Set ZSH_THEME="spaceship" in your .zshrc.

- create and make changes to `.zshrc`
  - create `touch ~/.zshrc`
  - open `~/.zshrc`
  - copy pasta the contents of `zshrc.text` into the zshrc file
