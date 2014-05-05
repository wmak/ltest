# To run 
```bash
ltest <file to monitor> <command to run>
```

## Example
This will run `make html` whenever ltest notices a change in the current folder
```bash
ltest ./ "make html"
```

## Installation
Either add ltest to a properly sourced
```bash
/bin
```
folder in your home directory or you may run this command:
```bash
sudo ln -s ltest /usr/local/bin/ltest
```
