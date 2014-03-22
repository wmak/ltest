# To run 
```bash
ltest <command to run> <file to monitor>
```

# Example
This will run `make html` whenever ltest notices a change in the current folder
```bash
ltest "make html" ./
```

# Recommended way to install
```bash
sudo ln -s ltest /usr/local/bin/ltest
```
