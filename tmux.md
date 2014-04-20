---
layout: default
title: tmux
---

# {{ page.title }}

## Start

`tmux` - start new

`tmux new -s <myname>` - start new with session name

`tmux a #` - attach to screen

`tmux a -t <myname>` - attach a session by name

`tmux ls` - list sessions

`tmux kill-session -t myname` - kill session

## Sessions

`Ctl+b s` - list sessions 

`Ctl+b $` - name session

## Window

`Ctl+b c` - new window

`Ctl+b w` - list windows

`Ctl+b f` - find window

`Ctl+b ,` - name window

`Ctl+b &` - kill window

## Panes

`Ctl+b %` - vertical split

`Ctl+b "` - horizontal split

`Ctl+b o` - swap panes

`Ctl+b q` - show pane numbers

`Ctl+b x` - kill pane

`Ctl+b +` - break pane into window (e.g. to select text by mouse to copy)

`Ctl+b -` - restore pane from window

`Ctl+b space` - toggle between layouts

