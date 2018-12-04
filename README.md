# Compiling/running files on Linux
Basic list of commands to compile and run files on Linux for various languages

## Github
### Push to existing
`git add .`

`git commit -m "comment"`

`git push origin BRANCH` (use `master` as default branch)

### Pull to existing
`git pull`

### Pull to new
`git init`

`git add .`

`git commit -m "comment"`

`git remote add origin LINK_TO_REPO`

`git push origin master`

## C/C++
Compile: `gcc -o program yourcode.c`

Run: `./program`

## Java
Compile: `javac yourcode.java`

Run: `java -cp . yourcode`

## Python
Compile/run: `python yourcode.py`

##youtube-dl
youtube-dl --extract-audio --audio-format mp3 -o "%(title)s.%(ext)s" <playlist-url> --ignore-errors
