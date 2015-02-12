IPython-popup
=============

Experimenal support for the creation of popup in IPython. The popup will have a codecell connected to the kernel of another notebook.
The small demo here links two widgets in different window together. (one slider from the notebook linked to one slider in the popup)


# Install

To install call:
    ipython install-nbextension --symlink --user popup


# Run

- start ipython notebook in this folder.

- load the http://localhost:8888/notebook/test.ipynb notebook and execute the first cell.

- in another window open http://localhost:8888/nbextensions/popup/hackme.html and click on execute.

The two widgets are now linked.
