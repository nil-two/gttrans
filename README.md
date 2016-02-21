gttrans
=======

Adjust transparency of gnome-terminal.

```sh
# Make the transparency to 30%
gttrans -s 30

# Make the transparency to 50%
gttrans -s 50
```

Installation
------------

```sh
curl -L https://raw.githubusercontent.com/kusabashira/gttrans/master/gttrans > ~/bin/gttrans
chmod 755 ~/bin/gttrans
```

Usage
-----

```
$ gttrans <operation> [...]
modify transparency of gnome-terminal.

operations:
  gttrans {-h --help}              # show this help message
  gttrans {-g --get}               # show the current transparency
  gttrans {-s --set} <percentage>  # set the transparency
```

License
-------

MIT License

Author
------

kusabashira <kusabashira227@gmail.com>
