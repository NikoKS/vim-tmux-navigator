Vim Tmux Navigator
==================

This plugin is a fork of [christoomey's vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator). This fork is created to add a nesting feature to the plugin so that navigation would work for a tmux window inside a ssh session inside a tmux window.

This fork also remove the auto-cycling behavior for tmux as I found it to be confusing

**How?**
1. Add edge detection to tmux navigation
2. Add check if running process is ssh

Usage
-----
For a full usage instruction, please refer to the [original repo page](https://github.com/christoomey/vim-tmux-navigator)
