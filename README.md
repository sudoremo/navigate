# navigate

A simple script to navigate between tmux and macOS windows. To install,
download the `navigate` script and save it somewhere in your `$PATH`.

## Prerequisites

* Install and start [Hammerspoon](http://www.hammerspoon.org/).

## Installation example

```bash
mkdir -p ~/bin
cd ~/bin
wget https://raw.githubusercontent.com/remofritzsche/navigate/master/navigate
chmod +x navigate
```

Then add the following line to your `~/.profile`:

```bash
export PATH=~/bin:$PATH
```

## Usage

Call `navigate left|right|top|bottom` to navigate to the left, right, top, bottom tmux pane and, if on the edge, to the respective macOS window.
