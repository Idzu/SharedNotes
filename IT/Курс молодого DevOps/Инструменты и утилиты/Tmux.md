sudo apt install tmux

```shell
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

set -g default-shell /bin/zsh
setw -g mouse on

set -g @plugin 'tmux-plugins/tpm'
set -g @plugin 'tmux-plugins/tmux-sensible'

set -g @plugin 'tmux-plugins/tmux-resurrect'

run '~/.tmux/plugins/tpm/tpm'

ctrl + b и большая i