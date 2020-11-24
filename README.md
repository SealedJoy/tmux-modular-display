# tmux-modular-display

Drop runnable (non-looping) scripts into a folder, they are given a new thread and ran every x seconds, the output is updated one line at a time for each script in the folder and is displayed to user via a pane.

As status_manager.py runs asynchronosly it can update individual scripts in realtime, or as close as the user delay is set on update.

This allows for smooth combinination of output from  both scripts that take a long time to generate output and those that are quick.

Requirements:

tmux,
python3, 
pypi package blessed


