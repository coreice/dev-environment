# dotfiles

In this repository I keep the .dotfiles that manage my terminal / development environment. This will be a forever _work in progress_ probably :-).

Some tools currently using:

- `zsh`
- `zinit` for zsh as plugin manager
- `Alacritty`
- `Powerlevel10k` for prompt theme
- `tmux` as multiplexer
- `nvim` as editor (still figuring that one out)

## zsh

- [A cool cheatsheet for keyboard shortcuts by David Souther for bash and zsh](https://cheatography.com/davidsouther/cheat-sheets/bash-zsh-shourtcuts/)

## Alacritty

Some helpful resources I used for setting up Alacritty:

- [Configuration options in TOML syntax](https://alacritty.org/config-alacritty.html)
- [The alacritty-theme repository](https://github.com/alacritty/alacritty-theme)
- [A better app icon for modern macOS systems](https://github.com/hmarr/dotfiles/blob/099af97f7165579bcc41579891c05dcbba567f16/bin/update-alacritty-icon.sh)

## Inspiration

My configuration is heavily inspired by the dotfiles from the following people / YouTubers:

- [dev-environment-files by @josean-dev](https://github.com/josean-dev/dev-environment-files/tree/main)
- [dotfiles by @omerxx](https://github.com/omerxx/dotfiles/tree/master)
- [dotfiles by @elliottminns](https://github.com/elliottminns/dotfiles/tree/main)

## Updates

- After years of using pretty much the same configuration consisting of iTerm2, oh-my-zsh and P10k, I started all over at the end of May 2024. I wanted something fress, quicker and less bloated. This is how I ended up with `Alacritty` and `zinit`.
- During research I also saw Wezterm and Kitty popping up. Probably also good choices but I like the simplicity of Alacritty. The only downside I see (for now) is lack of support for ligatures.
- Decided to stick with P10k because it looks less bloated then Starship, easier to setup and has all the features I need. Maybe I will switch to Starship one day but not for now.
