# Git Thief

Simple python script to install and update Git repositories in a directory.

### Requirements
- Python 3.10.4 or greater
- Git Installed

### Configuration
- TOOLS.conf - Full Git URL's "https://www.github.com/emaple-user/repo" or "example-user/repo"

### Usage
- Optional Install requirements
```
pip3 install -r requirements.txt
```

```
usage: gitthief.py [-h] [-A] [-U] PATH

  ______ _     _______ _           _  ___ 
 / _____|_)_  (_______) |         (_)/ __)
| /  ___ _| |_ _      | | _   ____ _| |__ 
| | (___) |  _) |     | || \ / _  ) |  __)
| \____/| | |_| |_____| | | ( (/ /| | |   
 \_____/|_|\___)______)_| |_|\____)_|_|   
                                          

GitTheif 1.0.0

An installer and updater for Git repositories.

positional arguments:
  PATH          path to store tools

options:
  -h, --help    show this help message and exit
  -A, --ALL     install all tools
  -U, --UPDATE  update installed tools (this will update ALL tools)
```