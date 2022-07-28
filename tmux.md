# **TMUX DOC**

Is a tool to manager another windows and panes in the same linux terminal.

## **USAGE**
- Start a new session:
```
> tmux
> tmux new
```

- See how many windows are up:
```
> tmux ls
> tmux list-sessions
```

- Close the pane or window:
```
> exit
```

## **CHEATSHEET**
- Enter in manage tmux mode:
```Ctrl + b + [option]```

- List of options:
  - ? (help)
  - c (create a new window or session)
  - p (go to previous window)
  - n (go to next window)
  - % (split pane with vertical layout)
  - " (split pane with horizontal layout)
  - o (go to next pane)
  - [arrow keys] (go to pane in the same direction)
