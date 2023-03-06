# Dracula for [tmux](https://github.com/tmux/tmux/wiki)

> A dark theme for [tmux](https://github.com/tmux/tmux/wiki)

All instructions can be found at [draculatheme.com/tmux](https://draculatheme.com/tmux).

## Install

```
set -g @plugin ememilyly/dracula-tmux
```

## My changes
Powerline support best effort as I don't use it

### Add fully custom time string (previous time variables removed)

  ```
  set -g @dracula-date-format '%a %d %b %H:%M:%S %Z'
  ```
  
### Add blocks plugin for pretty solid colour blocks in status bar ☺️

  ```
  # color of blocks from dracula color vars
  set -g @dracula-block-colors 'cyan pink white pink cyan'
  # or use hex colors
  set -g @dracula-use-hex-blocks true
  set -g @dracula-blocks-colors '#8be9fd #ff79c6'
  ```

### Custom left icon colors

  ```
  set -g @dracula-left-icon-fg 'pink'
  set -g @dracula-left-icon-bg 'cyan'
  # colours when prefix active
  set -g @dracula-left-icon-prefix-fg 'pink' # defaults to @dracula-left-icon-fg
  set -g @dracula-left-icon-prefix-bg 'white'
  ```
  
### Custom window status colors
  
  ```
  set -g @dracula-window-status-current-fg 'white'
  set -g @dracula-window-status-current-bg 'pink'
  set -g @dracula-window-status-fg 'white'
  set -g @dracula-window-status-bg 'gray'
  ```

## License

[MIT License](./LICENSE)
