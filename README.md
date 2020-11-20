# DeepSS docs

## Build

If you'd like to develop on and build the deepss docs, you should:

- Clone this repository and run
- Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
- (Recommended) Remove the existing `docs/_build/` directory
- Run `jupyter-book build docs/`

A fully-rendered HTML version of the book will be built in `docs/_build/html/`.

## Publish

Publish the book by running `build_and_publish.sh`. This will build the book and push the build static html files to the [https://github.com/janclemenslab/deepss/tree/gh-pages]() and make it accessible via [https://janclemenslab/deepss]()

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book) and [https://github.com/c-w/ghp-import]().
