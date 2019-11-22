# Quest

Minimal ticket (quest) system.

## Install
```
cp -R quest $HOME/.quest

export PATH=$PATH:$HOME/.quest/bin
```

##Use
```
quest new "title"
quest list
quest show N
quest edit N
quest close N

# Edit config
quest config

# Sync with git repo
quest init git@server.com:username/repo.git
quest sync
```
