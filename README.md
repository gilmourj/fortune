fortune: Display random quotes
==============================

## Introduction

`fortune` is yet another implementation of the Unix-style `fortune` program
that displays a random message from a database of quotations. Conceptually,
it's similar to the BSD fortune program originally written by [Ken Arnold][].
Unlike Arnold's program, this version is written in [Python][] and should
run anywhere there's a Python interpreter.

Slight modifications to allow for all quotes to be displayed and to change
some package-specific conventions.

To run, clone the repo and, from the parent directory, run 
`python fortune [filepath]` or `python fortune -h` for help.

[Ken Arnold]: http://en.wikipedia.org/wiki/Ken_Arnold
[Python]: http://www.python.org/
[web page]: http://software.clapper.org/fortune/

## Copyright

Copyright &copy; 2008-2012 Brian M. Clapper

## License

BSD license.
