# working-with-multiple-screens-linux

Working with multiple screens inside a linux terminal

Two options - Screen or tmux

## 1. Screen
- sudo apt install screen
- screen -S session_name
- Detaching and Reattaching Screen: To detach from screen and leave the window running in the background, use the keystroke: Ctrl + a and d
- see the session ID list with the command: screen -ls
- Once you have the ID, add it to the screen -r command: screen -r sessionID

## 2. Tmux

Prefix (mac): ctrl + b 

- sudo apt install tmux
- tmux –version
- 3 levels: session > window > panes

### 2.1. Session
- Sessions - use to separate different work (eg work and play)
- start session: tmux

### 2.2. Window
- Window: xxx
- Switch windows: Ctrl + B and type <window number>

### 2.3. Panes
- xxx
