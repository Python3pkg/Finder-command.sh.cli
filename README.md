<!--
README generated with readmemako.py (github.com/russianidiot/readme-mako.py) and .README dotfiles (github.com/russianidiot-dotfiles/.README)
-->

<p align="center">
    <b>Finder commands (OS X)</b>
</p>

#### Install

`[sudo] pip install Finder-command`

`[sudo] sudo npm install -g Finder-command`

#### Usage
```bash
# finder --help
usage: .finder---help COMMAND [options]

Available commands:
	todo
```

#### Example

```bash
# comment
$ Finder comment $path "new comment"
$ Finder comment $path
new comment
$ Finder comment $path "" # unset comment

# label
# 0 = none
# 1 = orange
# 2 = red
# 3 = yellow
# 4 = blue
# 5 = purple
# 6 = green
# 7 = grey 
$ Finder label $path
0

$ Finder label $path 2 # set red
$ Finder label $path
2
```

[Examples/](https://github.com/russianidiot/Finder-command.sh.cli/tree/master/Examples)

#### Issues
*	'execution error: Finder got an error: Application isnt running. (-600)' - restart Finder or OS X

Feedback
[![GitHub issues](https://img.shields.io/github/issues/russianidiot/Finder-command.sh.cli.svg)](https://github.com/russianidiot/Finder-command.sh.cli/issues)
[![Join the chat at https://gitter.im/russianidiot/Finder-command.sh.cli](https://badges.gitter.im/russianidiot/Finder-command.sh.cli.svg)](https://gitter.im/russianidiot/Finder-command.sh.cli)
[![GitHub followers](https://img.shields.io/github/followers/russianidiot.svg?style=social&label=Follow)](https://github.com/russianidiot)
