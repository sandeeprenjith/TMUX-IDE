# TMUX-IDE

TMUX-IDE is a coding environment built using TMUX. 


### Table of Contents

- [TMUX](#tmux)
- [Why](#why)
- [Features](#features)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)

### TMUX

TMUX is a terminal multiplier. 
Read more about TMUX [here](https://github.com/tmux/tmux/blob/master/README)

### Why

Why I wanted a new IDE. 

* I prefer to work from the terminal
* I prefer to code in VIM
* I prefer lesser distractions to flashy features

### Features

* Splits screen into three panes
	- The main pane is for coding in VIM
	- The second pane shows the files and directories in the current working directory
	- The third pane is for running the scripts while keeping the code in sight

### Dependencies

* TMUX

#### Installation instructions

Debian / Ubuntu bases systems

```
apt install tmux

```

Centos / RHEL

```
yum install tmux

```

For other systems. [Instructions here](https://github.com/tmux/tmux/wiki)

### Installation 

Clone the repo

```
git@github.com:sandeeprenjith/TMUX-IDE.git

```

or 

```
https://github.com/sandeeprenjith/TMUX-IDE.git

```
Copy the files to a directory in your $PATH(example: /usr/bin)

```
cp lscwd  /usr/bin
cp tde /usr/bin

```

### Usage

tde \<session name\>

> session name can be any name

```
tde test

```

View usage video: https://youtu.be/CmuhR4woFDM
