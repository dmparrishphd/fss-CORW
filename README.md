fss
===

The fss shell function may be used as a wrapper
around commands so as to avoid name clashes
(except for the name "fss").

The fss function looks for files in a
particular directory and calls found files
matching the first argument as commands,
passing all other arguments to the called command.

Example
-------

Suppose you have your own version of `ls`:

    $ fss ls --color=very-nicely

The Name
--------

The name fss is inspired by the French _faisons
[quelque chose]_---"let's do [something]."

The Code
--------

[fss](https://github.com/dmparrishphd/fss-WORM/blob/main/usr/local/lib/fss/ouuid/o0645626370337132107073153605700326514076441/fss.sh)
