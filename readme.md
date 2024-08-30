# Toggle

Written in 2024 by Daniel Hellsson at Orbital Systems

## Overview

The point of the script is to be associated with a shortcut key and allow that key to show and hide
some application that is frequently used.

# Function

This is a small script that looks for the process name given as an argument. If the process is found,
the script checks if the process has a visible window. If it does, it hides the window.
If the window is not visible, it shows the window.
If the process is not running, then it is started.

## For example

If associated with a shortcut key, such as "ESC" or ', then the application can be used to make any
terminal behave as a quake-terminal and appear and disappear when the shortcut key is pressed.
