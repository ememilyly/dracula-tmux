# Dracula for [tmux](https://github.com/tmux/tmux/wiki)

> A dark theme for [tmux](https://github.com/tmux/tmux/wiki)

All instructions can be found at [draculatheme.com/tmux](https://draculatheme.com/tmux).

## My changes

### Add fully custom time string, removing multiple old time settings

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

## License

[MIT License](./LICENSE)
