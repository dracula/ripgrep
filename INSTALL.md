### [ripgrep](https://github.com/BurntSushi/ripgrep)

#### Prerequisites

Ensure [ripgrep](https://github.com/BurntSushi/ripgrep) is configured to use a configuration file. If not already set up, follow the [official configuration guide](https://github.com/BurntSushi/ripgrep/blob/master/GUIDE.md#configuration-file).

#### Activating theme

Add the following color configuration to your ripgrep config file:

```shell
# Dracula theme for ripgrep - https://draculatheme.com/ripgrep
--colors=path:fg:0xbd,0x93,0xf9
--colors=line:fg:0x50,0xfa,0x7b
--colors=column:fg:0x50,0xfa,0x7b
--colors=match:fg:0xff,0x55,0x55
```

> 🧩 **Color Scheme:**
>
> - **Path**: Purple (`#bd93f9`);
> - **Line numbers**: Green (`#50fa7b`);
> - **Column numbers**: Green (`#50fa7b`);
> - **Match highlights**: Red (`#ff5555`);
