# bash-colors

[![Join the chat at https://gitter.im/arkadius/bash-colors](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/arkadius/bash-colors?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This is a simple script providing markup-like syntax for colorizing your scripts.<br>
The idea was inspired by [SOF post](http://stackoverflow.com/a/5947802)<br>
As a knowledge base for possible variants of ascii colors and formats was used [blog post](http://misc.flogisoft.com/bash/tip_colors_and_formatting).

## Usage

```bash
source /path/to/bash-colors
echo -e "My favorite color is ${green}green${reset}"
```

If you have a file with markups you can use *colorize* function

```bash
cat file-with-markups | colorize
```

If you want to have available markups always after system startup just add `source /path/to/bash-colors` to your *~/.bashrc* file

## Available colors and formats

To check all possible colors and formats run `./test` or take a look at result:

![screenshot](https://github.com/arkadius/bash-colors/blob/screenshot/screenshot.png)

## License

The bash-colors is released under version 2.0 of the Apache License.
