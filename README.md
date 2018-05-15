# Intro 
For lazy poeple :) 

This script do the following tasks:
* git add modified files
* git commit using message given in parameter
* git push

# How to 
## Install
Copy gacp script in /usr/local/bin/ and add execution right:
```
sudo chmod 755 /usr/local/bin/gacp
```

## Usage
```
Usage: /usr/local/bin/gacp -m "MESSAGE" -p $(pwd)
```
* -p: path to your git dir 
* -m: Commit message

Enjoy :*