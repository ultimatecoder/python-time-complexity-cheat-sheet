# Time and Space complexity of Python3 🕒


## Description 📃

Remembering complexity of each built-in function of Python is difficult for me
and I am sure it will be difficult for you too. This is a collection of runtime
and space complexity that I have calculated by observing the latest source code
of [CPython][cpython]. You can use this as a cheat sheet. Complexities mentioned
here are in [Big O][big_o] notation.

This cheat sheet does not have complexity of each built-in function, but I am
sure you will find the most commonly used functions. When I calculate runtime of
a new function and if that function not mentioned here, I add it here so that
next time I don't have to re-calculate it. If you have invested your efforts to
calculate runtime of any function which is not in this list, I request you to
share it by creating an issue or a pull request.


## Dependencies ⚒️

* [PDFTeX][pdftex]


## Commands 📦

```make build```

This command will genearte a PDF version of this cheat sheet at `output` folder.
Make sure [PDFTeX][pdftex] is already installed.


[cpython]: https://github.com/python/cpython
[pdftex]: https://tug.org/applications/pdftex/
[big_o]: https://en.wikipedia.org/wiki/Big_O_notation
