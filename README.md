# working-with-multiple-screens-linux

Working with multiple screens inside a linux terminal

Using TMUX

## Tmux

Prefix (mac): ctrl + b 

- Install: ```sudo apt install tmux```
- Check version: ```tmux –version```
- 3 levels: session > window > panes

### 2.1. Session
- Sessions: use to separate different work (eg work and play)
- Start a new session with a name: ```tmux new -s "my session"```
- Rename a session: ```Prefix $```
- List all sessions: ```tmux ls```
- List all sessions (with a prefix, to scroll through): ```Prefix s```
- Go to a specific session: ```tmux a -t *mysession*```
- Disconnect from a session: ```Prefix d```
- Kill session: ```tmux kill-session -t mysession```

### 2.2. Window
- Window: ```Predix c```
- Rename windows: ```Prefix ,```
- Switch windows: ```Prefix <window number>```
- Previous window: ```Prefix p```
- Next window: ```Prefix n```
- Kill window: ```Prefix &```

### 2.3. Panes
- Split vertically: ```Prefix %```
- Split horizontally: ```Prefix "```
- Move to next screen: ```Prefix o```
- Change panes: ```Prefix <arrow keys>```
- Close a pane: ```Prefix x```
- Zoom into/out of pane: ```Prefix z```

### References
- ```https://tmuxcheatsheet.com/```
