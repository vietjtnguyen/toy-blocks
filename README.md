A simple vim terminal colorscheme that focuses on using named colors and not direct hex or RGB values. This essentially defers to the user's terminal for final coloring (such as iterm color schemes, of which one is provided). Colors are chosen for visual distinction amongst syntax elements.

# Screenshots

C++ source with provided iterm color scheme:

![](./screenshots/cpp-with-toy-blocks.png)

Python source with provided iterm color scheme:

![](./screenshots/python-with-toy-blocks.png)

Javascript source with provided iterm color scheme:

![](./screenshots/javascript-with-toy-blocks.png)

C++ source with iterm's "Tango Dark" color scheme:

![](./screenshots/cpp-with-tango-dark.png)

Javascript source with iterm "Molokai" color scheme:

![](./screenshots/javascript-with-molokai.png)

# Install

Install using your favorite vim plugin manager (for example, [vim-pathogen](https://github.com/tpope/vim-pathogen)).

# Usage

```VimL
syntax on
colorscheme toy-blocks
```

# iterm Color Scheme

An iterm color scheme is also included which is a dark color scheme that is a slight variation on the standard iterm color scheme for better legibility, particularly with the blue.

## Colors

Below is the colors from the provided iterm color scheme but as CSS with the RGB components listed.

```css
.black.normal { color: rgb(0, 0, 0); }
.red.normal { color: rgb(201, 80, 75); }
.green.normal { color: rgb(49, 195, 56); }
.yellow.normal { color: rgb(199, 196, 0); }
.blue.normal { color: rgb(83, 128, 217); }
.magenta.normal { color: rgb(200, 98, 199); }
.cyan.normal { color: rgb(99, 198, 199); }
.white.normal { color: rgb(199, 199, 199); }
.black.bright { color: rgb(104, 104, 104); }
.red.bright { color: rgb(255, 110, 103); }
.green.bright { color: rgb(157, 234, 122); }
.yellow.bright { color: rgb(255, 230, 89); }
.blue.bright { color: rgb(126, 173, 255); }
.magenta.bright { color: rgb(255, 119, 255); }
.cyan.bright { color: rgb(96, 253, 255); }
.white.bright { color: rgb(255, 255, 255); }
```

# Name

The use of primary colors reminds me of kids ***toys***. The deference to the user's terminal for final coloring means the scheme is mostly a "building ***block***" for your final color scheme.
