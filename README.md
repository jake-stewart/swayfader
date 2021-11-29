# Swayfader
Adds fading between windows in Swaywm.

### Installation
1. Download the `swayfader.py` file.
2. Install `python3` and `python-pip` packages through pacman.
3. Install the i3ipc module: `sudo python3 -m pip install i3ipc`
4. add `exec python3 /path/to/swayfader.py` to your sway config to have the program launch at startup. Alternatively, run `python3 /path/to/swayfader.py` to start the program manually.

### Configuration
The opacities and fade durations can be configured through environment variables. For example, `SWAYFADER_CON_INAC` for inactive window opacity. When not set, the values have sane defaults.

`CON` refers to a normal tiled window, while `BOT` refers to a tiled window that has just lost focus to a floating window. Everything else should be self-explanatory.
