# copen

`copen` is a wrapper around visual studio code's `code` cli command that uses autojump to fuzzy match folders.

Basically it's a replacement for doing this:

```sh
$ j proj
~/path/to/my-project
$ code .
```

Instead with copen, just do this:

```sh
copen proj
```

## Install

`copen` assumes you have [autojump](https://github.com/wting/autojump) and visual studio already installed.

If you have wget, run this:

```
wget -O /usr/local/bin/code-open https://raw.githubusercontent.com/Flaque/copen/master/copen; chmod +x /usr/local/bin/code-open 
```

If you don't have wget and are on macos, then install wget:

```
brew install wget
```
