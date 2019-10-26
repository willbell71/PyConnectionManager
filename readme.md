# Python Connection Manager

## Pre-requistes

This may need you to install gtk for python, if it's not part of your distribution.<br/>
>`sudo dnf install python-gobject`

## Run app

>`python3 app.py`

## Glade

Use the `Glade` tool from software center to edit / design the layout.

## Reference

### GTK+

GTK+ - GUI Framework<br/>
[GTK+ Reference](https://developer.gnome.org/gtk3/stable/)

### VTE

Virtual Terminate Emulator - a shell widget for GTK+.<br/>
[GTK+ VTE Reference](https://developer.gnome.org/vte/unstable/VteTerminal.html)

### Pythong GTK+ 3 Tutorial

[GTK+ 3 Python Tutorial](https://python-gtk-3-tutorial.readthedocs.io/en/latest/)

### App UI Design

- 1. Main App Window<br/>

--- App Title Bar ( OS ) ---<br/>
--- Menu - File / Edit / View / Servers / Help ---<br/>
--- Toolbar - Local / Connect / Add / Edit / Remove<br/>
--- Main Area ---<br/>
    --- Left Panel - List of servers ---<br/>
    --- Right Panel - Tab Container ---<br/>
        --- Tab - Bash shell ---<br/>

- 2. Pop Up ( Add / Edit Connection )<br/>

--- Tab Container ---<br/>
    --- Tab - Properties ---<br/>
