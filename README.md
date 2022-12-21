# working-with-multiple-screens-linux
Working with multiple screens inside a linux terminal

- sudo apt install screen
- screen -S session_name
- Detaching and Reattaching Screen: To detach from screen and leave the window running in the background, use the keystroke: Ctrl + a and d
- see the session ID list with the command: screen -ls
- Once you have the ID, add it to the screen -r command: screen -r sessionID
