autojump
========

[autojump](https://github.com/joelthelion/autojump) is a tool for quick navigating of your filesystem.

## How does it work

It maintains database of your entries, in which directory you usually go. These entries are sorted by priority:

```bash
$ autojump --stat
```

## Usage

```bash
$ j here
```

...will jump to `/path/to/dir/which/contains/here_in-its|name`

```bash
$ jc there
```

...will jump to sub-directory of current working directory

## Alternatives

 * [fasd](https://github.com/clvv/fasd)
 * [z](https://github.com/rupa/z)

