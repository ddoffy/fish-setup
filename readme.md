# Install fish shell
```
sudo dnf install fish -y
```

# install fisher
```
curl -sL https://git.io/fisher | source && fisher install jorgebucaran/fisher
```

# Install fzf for fish
```
fisher install PatrickF1/fzf.fish
```

# Install fisher plugins
```
fisher install oh-my-fish/theme-bobthefish
fisher install oh-my-fish/plugin-brew
fisher install oh-my-fish/plugin-extract
fisher install oh-my-fish/plugin-osx
fisher install oh-my-fish/plugin-grc
fisher install jorgebucaran/fish-bax
fisher install jethrokuan/fzf
fisher install jorgebucaran/fish-nvm
fisher install laughedelic/brew-completions
fisher install acomagu/fish-async-prompt
fisher install sadanand-singh/fish-sodope

```

# theme-bobthefish configuration, add the following to ~/.config/fish/config.fish
```
set -g theme_powerline_fonts yes
set -g theme_nerd_fonts yes
set -g theme_display_git_stashed_verbose yes
set -g theme_display_git_master_branch yes
set -g theme_display_git_untracked yes
set -g theme_display_git_dirty yes
set -g theme_display_nvm yes
set -g theme_display_virtualenv yes
set -g theme_color_scheme zenburn

```
