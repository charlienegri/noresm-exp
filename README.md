# NorESM Experiments

An overview of NorESM2 experiments including upgrades, code modifications and parameter settings.

The overview includes:

    NorESM2-MM CMIP6 DECK simulations
    NorESM2-LM CMIP6 DECK simulations
    NorESM2-MM CMIP6 historical simulations
    NorESM2-LM CMIP6 historical simulations
    NorESM2-MM CMIP6 scenario simulations
    NorESM2-LM CMIP6 scenario simulations
    NorESM2-MM spinup tree
    NorESM2-LM spinup tree

## Usage

### Building the book

If you'd like to develop and/or build the NorESM Experiments book, you should:

1. Clone this repository
2. Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
3. (Optional) Edit the books source files located in the `noresm_exp_book/` directory
4. Run `jupyter-book clean noresm_exp_book/` to remove any existing builds
5. Run `jupyter-book build noresm_exp_book/`

A fully-rendered HTML version of the book will be built in `noresm_exp_book/_build/html/`.

### Hosting the book

Please see the [Jupyter Book documentation](https://jupyterbook.org/publish/web.html) to discover options for deploying a book online using services such as GitHub, GitLab, or Netlify.

For GitHub and GitLab deployment specifically, the [cookiecutter-jupyter-book](https://github.com/executablebooks/cookiecutter-jupyter-book) includes templates for, and information about, optional continuous integration (CI) workflow files to help easily and automatically deploy books online with GitHub or GitLab. For example, if you chose `github` for the `include_ci` cookiecutter option, your book template was created with a GitHub actions workflow file that, once pushed to GitHub, automatically renders and pushes your book to the `gh-pages` branch of your repo and hosts it on GitHub Pages when a push or pull request is made to the main branch.

## Contributors

We welcome and recognize all contributions. You can see a list of current contributors in the [contributors tab](https://github.com/NorESMhub/noresm-exp/noresm_exp_book/graphs/contributors).

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).

## Licence
This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]


[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
