# cleangit
a shell script which makes force remove out all dirty info from current git branch

add executable permission and mv the scrip the `/usr/local/bin` or `/usr/lobal/sbin`

then

```shell
$ cleangit
```

The script will auto detect the current directory, make choice the current directory has `.git` repo. If `.git` repo is exists, the script will clear all dirty files unstaged, 
