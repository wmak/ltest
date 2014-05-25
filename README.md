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
Clone ltest via git:
```bash
git clone https://github.com/wmak/ltest.git
```
Then in the ltest folder either add ltest to a properly sourced /bin folder in
your home directory:
```bash
ln -s ltest $HOME/bin/ltest
```
*or* add it to your local/bin folder:
```bash
sudo ln -s ltest /usr/local/bin/ltest
```

## Update
To update ltest, navigate to the directory where ltest was cloned and pull
because it was symbolically linked earlier this will change the code everywhere
else as well.
```bash
git pull
```
