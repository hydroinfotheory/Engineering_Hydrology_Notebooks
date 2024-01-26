## Jupyter Book and Binder

Launch the main notebook in "interactive mode" using Binder:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dankovacek/run_of_river_intro.git/main)

The notebook files themselves are saved under [content/notebooks/](https://github.com/dankovacek/Engineering_Hydrology_Notebooks/tree/main/content/notebooks).

## Notes on Compiling and Updating the Book 

Info for [building books and hosting on Github Pages](https://jupyterbook.org/publish/gh-pages.html)

After updating any content, rebuilt the repo:

`jupyter-book build content/`

Then, update the github pages site. Use the gh-pages branch update tool:

`ghp-import -n -p -f content/_build/html`

[Visit the site](https://hydroinfotheory.github.io/Engineering_Hydrology_Notebooks/) at Github sites

`https://hydroinfotheory.github.io/Engineering_Hydrology_Notebooks/`

