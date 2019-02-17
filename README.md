## Documentation
I made this branch to document the Anki source code.

Build the docs by running the following commands from the docs/ directory:
```bash
make html
```

When files were added or deleted run the following command to update the TOC:
```bash
sphinx-apidoc -f -o source/ ..
```

Anki
-------------------------------------

This is the development branch of Anki.

For stable builds, please see https://apps.ankiweb.net.

For non-developers who want to try this development code,
the easiest way is to use a binary package - please see
https://anki.tenderapp.com/discussions/beta-testing

To run from source, please see README.development.

[![Build Status](https://travis-ci.org/dae/anki.svg?branch=master)](https://travis-ci.org/dae/anki)
