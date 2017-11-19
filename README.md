# Platform for CTF games in Attack-defense format
=========================================================
## Installation
---------
Automated installation is performed on a server with the operating system debian or ubuntu.

To install, you must go to the working directory of the project and run install.sh

    ./install.sh

## Requirements

* `sudo apt-get install python3 pip3 python3-psutil`
* `sudo apt install mongodb`
* `pip3 install pymongo`
* `pip3 install flask`

## Init game

	`python3 main.py init` or `python3 main.py init config.ini`

## 1. Start game
`python3 main.py start`
`python3 main.py start --slave`

## 2. Start sending flags
`python3 main.py flags`

## 3. Run scoreboard (address and port will be printed)
`python3 main.py scoreboard`
