# awesome-cli-tools
Collection of all terminal tools developed by myself.

## wtf-cli
A command tool for looking up abbreviation.

[Github Link](https://github.com/Haixiang6123/wtf-cli)
[NPM Link](https://www.npmjs.com/package/wtf-cli)

### Screenshot

[![asciicast](https://asciinema.org/a/amfz0RX1BXlJdEqGtdRzmj8Rm.svg)](https://asciinema.org/a/amfz0RX1BXlJdEqGtdRzmj8Rm)

### Install

```
$ brew install node

$ npm i -g wtf-cli
```

### How to use

Example: Look up the meaning of `wtf`.

```
$ wtf wtf
```

## thanos-snap-cli
Randomly delete half of files in current folder.

[Github Link](https://github.com/Haixiang6123/thanos-snap-cli)
[NPM Link](https://www.npmjs.com/package/thanos-snap-cli)

**Please make sure don't run `snap` under root directory!**

### Screenshot

[![asciicast](https://asciinema.org/a/g5RH9A8v9GIiVjl3XKn4l8zk5.svg)](https://asciinema.org/a/g5RH9A8v9GIiVjl3XKn4l8zk5)

### Install

```
$ brew install node

$ npm i -g thanos-snap-cli
```

### Usage

```
$ snap          # Create a /mock folder with some files

$ snap ./mock   # Snap the finger -> Delete half of the files in ./mock directory
```

## uci-reg-cli
A command line tool for querying course information from UCI

[Github Link](https://github.com/Haixiang6123/uci-reg-cli)
[NPM Link](https://www.npmjs.com/package/uci-reg-cli)

### Screenshot

[![asciicast](https://asciinema.org/a/LeTrH16cvp6Yq4NlSZY9fOcZP.svg)](https://asciinema.org/a/LeTrH16cvp6Yq4NlSZY9fOcZP)

### Install

```bash
$ brew install node

$ npm i -g reg-uci-cli
```

### How to use

Find course EECS 10.

```bash
$ reg-uci-cli -d eecs -c 10
```

Find all courses of Networked System department.

```bash
$ reg-uci-cli -d "net sys"
```

## Options

* `-d` Department 
* `-c` Course number
* `-t` Year term

## love-you-3000
A command tool to say "Love you" in 3000 times.

[Github Link](https://github.com/Haixiang6123/love-you-3000)
[NPM Link](https://www.npmjs.com/package/love-you-3000)

## Install

```
$ brew install node

$ npm i -g love-you-3000
```

## Usage

```
$ love-you-3000
```