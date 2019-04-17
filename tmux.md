---
layout: page
title: tmux
docs: https://github.com/tmux/tmux/wiki
---
List tmux sessions
```bash
tmux ls
```
Start tmux session `#`
```bash
tmux
```
Start tmux session `my_session`
```bash
tmux new -s my_session
```
Attach last tmux session
```bash
tmux a
```
Attach tmux session `my_session`
```bash
tmux a -t my_session
```
Kill tmux session `my_session`
```bash
tmux kill-session -t my_session
```
Kill tmux server
```bash
tmux kill-server
```
A short summary of tmux:
- Tmux can take several commands. The default prefix for these commands is `C-b` (*control* **and** `b`)
- Detach from a session with `C-b` `d`
- View sessions and switch between them with `C-b` `s`
- Split the screen by creating panes with `C-b` `%` (vertical) and `C-b` `"` (horizontal)
- Switch between panes with `C-b` up, `C-b` down, `C-b` left and `C-b` right
- List windows with `C-b` `w`, create a new window with `C-b` `c`, switch with `C-b` `n` and `C-b` `p`
- `C-b` `:` starts command mode
