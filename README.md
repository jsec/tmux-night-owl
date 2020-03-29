# tmux-gruvbox-light

A tmux color scheme based on the [gruvbox](https://github.com/morhetz/gruvbox) color palette and based on the [tmux-gruvbox](https://github.com/egel/tmux-gruvbox) dark theme.

Currently this is only tested on systems with 24-bit color support. Making the theme degrade gracefully for 8-bit palettes is in the works.

## Screenshot

![tmux gruvbox light](https://github.com/jsec/tmux-gruvbox-light/raw/master/screenshots/tmux-gruvbox.png)

## Installation

Install with TPM:

```bash
set -g @plugin 'jsec/tmux-gruvbox-light'
```

or add to your `tmux.conf` file:

```bash
source-file "/path/to/repository/tmux-gruvbox-light.conf"
```

## Roadmap

- Clean up theme
- Add support for 256 color palettes.

## License

MIT
