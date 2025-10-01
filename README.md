# cf-tools-training

## Training material on the CF Data Tools [``cf-python``](https://ncas-cms.github.io/cf-python) & [``cf-plot``](http://ajheaps.github.io/cf-plot).

### 🏁 Go [here for the new course](https://github.com/NCAS-CMS/cf-tools-training/tree/master/new_course) (i.e. the `new_course` directory here)

*Note:* this repository was previously called 'cf-training' but was renamed to
avoid any potential for confusion or name clashing issues
with the new repository for training resources relating to the CF Conventions
directly,
['cf-convention/cf-training'](https://github.com/cf-convention/cf-training).
(Any URL links to the old name should redirect automatically.)

These are practical materials *used for NCAS training workshops*, but
they are self-contained and permanently available so are *also suitable for
outside (private) study* (in which case see the [Setup](#setup) section
below for guidance on setting up the required environment to run
the software and the Notebooks).

The format of the courses is a series of
[Jupyter (formerly known as IPython) Notebooks](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html).


## Format and structure

🏁 The latest course (2024+) is contained under the directory `new_course` and this is the training that
should be used now. View the `new_course` and it's README document, which documents this new
training, [here](https://github.com/NCAS-CMS/cf-tools-training/tree/master/new_course).

For purposes of archival, old courses are also stored here under directories
named `deprecated_*_course`, though these should not be used for training as they can't be
guaranteed to work under newer versions of the libraries.


## Prerequisites

Both libraries are Python-based but don't require any previous Python
knowledge to use.


## Setup


### Environment setup

If you wish to work through these materials in your own time, you will
need to set up the following to install ``cf-python`` and ``cf-plot`` and to
run the Jupyter Notebooks on a machine of your choice:

1. Install ``cf-python`` and ``cf-plot`` with all dependencies: see the
   installation instructions
   [here](https://ncas-cms.github.io/cf-python/installation.html) which
   covers the installation of both libraries. Note you will need some of
   the [listed optional dependencies](https://ncas-cms.github.io/cf-python/installation.html#optional)
   for certain parts of the course e.g. for the regridding component.
2. Install the Jupyter Notebook software if you do not have it already. There
   are instructions on how to do so
   [on the Jupyter site](https://jupyter.readthedocs.io/en/latest/install.html).


### Downloading and working through the course

When you have completed the above, copy this repository to your machine
either by downloading the tarball from the GitHub User Interface or by
running ``git clone``, e.g:

```console
$ git clone https://github.com/NCAS-CMS/cf-tools-training.git
```

then navigate to the notebooks directory of the relevant course and
[start up the notebook server](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#starting-the-notebook-server) there, e.g:

```console
$ cd full_course/notebooks/
$ jupyter notebook &
```

This will open a listing of the Notebooks available in the browser.
You will be able to open & run the Notebooks at your own pace.
