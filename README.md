# About

This repo includes `*.nanorc` files that config syntax highlight for Nano editor.

Most of the `*.nanorc` files in this repo are revised from [scopatz/nanorc](https://github.com/scopatz/nanorc) and [GNU nano](https://git.savannah.gnu.org/cgit/nano.git/tree/syntax).

# Supported Language

Language | Config File |
---      | ---         |
C        | c.nanorc    |
C++      | cpp.nanorc  |
[Readline Init File](https://www.gnu.org/software/bash/manual/html_node/Readline-Init-File.html) | inputrc.nanorc |
Bash Script | sh.nanorc |
[Ngspice](https://ngspice.sourceforge.io/index.html) Netlist | sp.nanorc |

# Installation

Step 1. Download the files you need, or use the following command to clone the whole repository.

```sh
git clone https://github.com/jeang-bo-yuan/nanorc-syntax-highlight
```

Step 2. Open the file, `~/.nanorc`, and add the `include` to include the config files. For example:

```nanorc
include "/path/to/c.nanorc"
include "/path/to/cpp.nanorc"
# ... etc
```

Wildcard is also available.

```nanorc
include "/path/to/repo/*.nanorc"
```

# License

see [LICENSE](LICENSE)
