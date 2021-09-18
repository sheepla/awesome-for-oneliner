# 🐚 Awesome CLI tools for One Liner

<div align="right">
<img src="https://img.shields.io/static/v1?label=LICENSE&message=CC0&color=blue&style=flat-square"/>
</div>

This is a list of useful commands in the Unix shell one-liner.

## Commands Collection

### moreutils

[moreutils](https://joeyh.name/code/moreutils/) - moreutils is a growing collection of the unix tools that nobody thought to write long ago when unix was young.

- `chronic` : runs a command quietly unless it fails
- `combine` : combine the lines in two files using boolean operations
- `errno` : look up errno names and descriptions
- `ifdata` : get network interface info without parsing ifconfig output
- `ifne` : run a program if the standard input is not empty
- `isutf8` : check if a file or standard input is utf-8
- `lckdo` : execute a program with a lock held
- `mispipe` : pipe two commands, returning the exit status of the first
- `parallel` : run multiple jobs at once
- `pee` : tee standard input to pipes
- `sponge` : soak up standard input and write to a file
- `ts` : timestamp standard input
- `vidir` : edit a directory in your text editor
- `vipe` : insert a text editor into a pipe
- `zrun` : automatically uncompress arguments to command

### dateutils

- [dateutils](https://github.com/hroptatyr/dateutils) - nifty command line date and time utilities; fast date calculations and conversion in the shell

### uniutils

- [uniutils](http://www.billposer.org/Software/unidesc.html) -  Programs for manipulating and analyzing Unicode text.

### Open USP Tsukubai

- [Open USP Tsukubai](https://github.com/usp-engineers-community/Open-usp-Tukubai) - Unix-style commands for corporate systems written in Python
  - [About Open USP Tsukubai](https://uec.usp-lab.com/tukubai)
  - [Manual](https://uec.usp-lab.com/tukubai_man)

## JSON 

* [dasel](https://github.com/tomwright/dasel) - Query and update data structures using selectors from the command line. Comparable to [jq](https://github.com/stedolan/jq) / [yq](https://github.com/kislyuk/yq) but supports JSON, YAML, TOML and XML with zero runtime dependencies.
* [jo](https://github.com/jpmens/jo) - A small utility to create JSON objects from command-line arguments
* [rjo](https://github.com/dskkato/rjo) - A small utility to create JSON objects from command-line arguments written in Rust
* [jq](https://github.com/stedolan/jq) - A JSON Query Language tool

- [jql](https://github.com/yamafaktory/jql) - A JSON Query Language tool written in Rust
- [tv](https://github.com/uzimaru0000/tv) - format JSON into table view

## HTML

- [htmlq](https://github.com/mgdm/htmlq) - like jq but for HTML
- [emmet-cli](https://github.com/Delapouite/emmet-cli) - A command to expand emmet expression

## AWK-like tools

- [opy](https://github.com/ryuichiueda/opy) - A Python wrapper which works like AWK
- [hawk](https://github.com/gelisam/hawk) - Haskell text processor for the command-line
- [frawk](https://github.com/ezrosent/frawk) - An efficient AWK like language written in Rust
- [rargs](https://github.com/lotabout/rargs) - xargs + awk with pattern matching support `ls *.bak | rargs -p '(.*)\.bak' mv {0} {1}`

## Text Editing

- [tate](https://github.com/mattn/tate) - A command to convert text to vertical writing
- [forest](https://github.com/KoharaKazuya/forest) - A command that formats and outputs text that represents a line-oriented structured tree structure.
- [teip](https://github.com/greymd/teip) - Select partial standard input and replace with the result of another command efficiently

## Translate

- [translate-shell](https://github.com/soimort/translate-shell) - Command-line translation tool written in AWK
- [deepl-cli](https://github.com/eggplants/deepl-cli) - DeepL Translator CLI written in Python

## Document Converter

- [pandoc](https://github.com/jgm/pandoc) - Universal markup converter written in Haskell

## Image Processing

- [imagemagick](https://imagemagick.org/index.php) - A tool to create, edit, compose, or convert digital images

- [textimg](https://github.com/jiro4989/textimg) - Command to convert from color text (ANSI or 256) to image

