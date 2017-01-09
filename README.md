# qwe
Launch stuff easily using shortcuts

# install (requires python 3 to be installed)

`$ sudo cp qwe /usr/bin/`

# configure:
Edit `~/.qwe` using your favorite editor

The configuration format is simple, one shortcut per line:

`<Shortcut> <Command>`

Lines prefixed with `#` are comments

`# comment`

Example `.qwe` config file:

```
# find the latest version in a git repository
version git tag -l | sort -V | tail -1
```

# example usage:

```$ qwe version```

# enable bash completion

```$ qwe --gen-bash-completion >> ~/.bash_completion```
