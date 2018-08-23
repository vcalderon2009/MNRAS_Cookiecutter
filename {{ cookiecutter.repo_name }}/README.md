# Cookiecutter - Template for MNRAS Paper

_An easy, reasonably standardized, but flexible template for creating paper for 
the [**Monthly Notices of the Royal Astronomical Society**](https://academic.oup.com/mnras)_.

## Requirements to use the cookiecutter template
------------------------------------------------
- Python 2.7 or 3.5 and above
- [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```

### To start a new project, run:
------------

    cookiecutter https://github.com/vcalderon2009/MNRAS_Cookiecutter

For an example on how to properly do this, see the following video. It serves as a demonstration on how `cookiecutter` works.

[![asciicast](https://asciinema.org/a/9bgl5qh17wlop4xyxu9n9wr02.png)](https://asciinema.org/a/9bgl5qh17wlop4xyxu9n9wr02)


### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
├── Extras <- Folder with documents like main `aliases`, `packages`, etc.
│    ├── commands.tex <- List of commands used throughout the paper.
│    └── packages.tex <- List of packages to load for the paper.
│
├── Figures <- Directory for project figures.
│    └── .gitkeep
│
├── Paper
│    └── paper.tex
│
├── Script_files
│    ├── modify_bib.sh
│    ├── hyperlink-year-only-natbib-patch.tex.
│    └── nat2jour.pl
│
├── Style_files
│    ├── macros_dc.sty
│    ├── mnras.bst
│    └── mnras.cls
│
├── .gitignore <- File that dictates which files to ignore when using `git`.
├── Makefile <- Makefile with commands like `make main.tex` or `make clean`.
├── Makefile.inc <- File with input parameters for the `Makefile`.
├── Mendeley.bib <- Bibliography of the project. You can replace this file if needed.
├── README.md <- The top-level README for students
└── requirements.txt <- File with a list of packages required for running this.
```

## Contributing

Contributions are welcomed! If you have any suggestions, feel free to submit a _Pull Request_.

### Installing development requirements
------------

    pip install -r requirements.txt
