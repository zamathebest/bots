
# Bots  
Bots is an open source EDI translator. This is the documentation repository.

# Bots Documentation
The documentation is written in reStructuredText format. Sphinx is used to generate the HTML documentation site.

## Building the Docs

### Requirements
* Python
* Pip packages:
    * sphinx
    * sphinx_rtd_theme

### Building
1. Clone the repository `git clone git@github.com:bots-edi/docs.git`
1. Run `make html`

### Publishing
The documentation site uses GitHub Pages, specifically the https://github.com/bots-edi/bots-edi.github.io repository.

1. Clone the repository `git clone git@github.com:bots-edi/bots-edi.github.io.git`
1. Build the documentation (see above)
1. Copy the contents of the _build/html folder to the `bots-edi.github.io` repository.
1. Commit

# Credits
This work was started by @abhishek-ram at https://github.com/abhishek-ram/bots/tree/sphinx-docs/docs and @skilchen at https://github.com/skilchen/bots/tree/master/docs
