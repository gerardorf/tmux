# tmux
Use tmux the way I like it!

## Prerequisites
- [tmux] (https://github.com/tmux/tmux)
- [powerline fonts](https://github.com/powerline/fonts)

## Installation
1. Clone this repo to local machine
```bash
$ git clone https://github.com/gerardorf/tmux ~/.tmux
```

2. Clone tmux themepack to local machine
```bash
$ git clone https://github.com/jimeh/tmux-themepack.git ~/.tmux-themepack
```

3. Source config and theme in your ~/.tmux.conf
```
source-file ~/.tmux/tmux.conf
source-file ~/.tmux-themepack/powerline/block/cyan.tmuxtheme
```
