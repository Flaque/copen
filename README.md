# copen

Copen is a wrapper around visual studio code's `code` cli command that uses autojump to fuzzy match folders.

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
