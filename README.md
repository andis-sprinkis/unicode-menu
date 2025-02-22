# `ucmenu`

The Unicode character selector.

Use with a menu program to query the value, property or representation of a Unicode character.

## Available properties

- Value
- Unicode name
- Unicode code point, hexadecimal, standard
- Unicode code point, decimal
- Unicode code point, hexadecimal
- UTF-8 representation, hexadecimal
- UTF-16 representation, hexadecimal
- UTF-32 representation, hexadecimal
- UTF-8 representation, hexadecimal, escaped for URL
- Unicode code point, decimal, escaped for HTML or XML
- Unicode code point, hexadecimal, escaped for HTML or XML
- Unicode code point, hexadecimal, escaped for CSS
- Unicode code point, hexadecimal, escaped for CSS, 6 digits
- Wikipedia URL

## Usage

See

```sh
ucmenu -h
```

## Requirements

- A menu program, like `dmenu`, `wmenu`, `fzf`
- The Unicode Character Database (UCD)
    - [Home page](https://www.unicode.org/ucd/)
    - Package
        - [Arch Linux](https://archlinux.org/packages/extra/any/unicode-character-database/)
        - [Debian GNU/Linux](https://packages.debian.org/search?searchon=names&keywords=unicode-data)
        - [Fedora Linux](https://packages.fedoraproject.org/pkgs/unicode-ucd/unicode-ucd/)
        - [openSUSE](https://software.opensuse.org/package/unicode-ucd)
        - [Ubuntu](https://packages.ubuntu.com/search?keywords=unicode-data&searchon=names&suite=all&section=all)
