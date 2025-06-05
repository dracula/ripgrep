### [ripgrep](https://github.com/BurntSushi/ripgrep)

#### Set up the theme

First, prepare ripgrep
[to use a configuration file](https://github.com/BurntSushi/ripgrep/blob/master/GUIDE.md#configuration-file)
unless it already is.

Then, add the following lines to the configuration file:

```shell
# https://draculatheme.com/ripgrep
--colors=path:fg:0xbd,0x93,0xf9
--colors=line:fg:0x50,0xfa,0x7b
--colors=column:fg:0x50,0xfa,0x7b
--colors=match:fg:0xff,0x55,0x55
```
