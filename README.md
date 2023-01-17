# .tmux

## Installation

1. Clone the repo
    ```
    git clone git@github.com:jeradg/.tmux.git ~/.tmux
    ```
2. Create symlink to main conf file:
    ```
    ln -s ~/.tmux/.tmux.conf ~/.tmux.conf
    ```
3. Create symlink to environment-specific conf file, ex.:
    ```
    ln -s ~/.tmux/env/linux.conf ~/.tmux/env.conf
    ```
4. Run `install-terminfo.sh` to set up the `tmux-256color` TERMINFO profile to add italics support to tmux.
