# cf-training

## Training material on the CF data tools [``cf-python``](https://ncas-cms.github.io/cf-python) and [``cf-plot``](http://ajheaps.github.io/cf-plot).

These are practical materials *used for NCAS training workshops*, but
they are self-contained and permanently available so are *also suitable for
outside (private) study* (in which case see the [Setup](#setup) section
below for guidance on setting up the required environment to run
the software and the Notebooks).

The format of the courses is a series of
[Jupyter (formerly known as IPython) Notebooks](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html).


## Structure

There will *soon* be two courses available:

* a **full course** (see the ``full_course`` directory) which contains all of
  the material for the full-day NCAS Data Tools training workshop. As a guide,
  it is *designed to take around ~1-2 days of dedicated study* to work
  through.

* a **short course** (see the ``short_course`` directory) which will contain
  a condensed summary of the full course, focusing on demonstrating core
  functionality. It is *designed to take 2-3 hours* to work through.

Note that at present only the full course is ready for use; the short course
is currently under development & will be ready in August 2020.


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
$ git clone https://github.com/NCAS-CMS/cf-training.git
```

then navigate to the notebooks directory of the relevant course and
[start up the notebook server](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#starting-the-notebook-server) there, e.g:

```console
$ cd full_course/notebooks/
$ jupyter notebook &
```

This will open a listing of the Notebooks available in the browser.
You will be able to open & run the Notebooks at your own pace.


### Course order

The recommended order in which to work through the full course Notebooks is as follows,
where all paths given are relative to ``full_course/notebooks/``:

| | Topic | Format | Notebook name & location |
|---|---|---|---|
| 1. | Introduction | Overview & walkthrough | ``introduction.ipynb`` |
| 2. | Reading and manipulating data | Walkthrough | ``cf_python.ipynb`` |
| 3. | Reading and manipulating data | Exercises | ``exercises/cf_python_exercise_*.ipynb`` [``*``=1-5] |
| 4. | Contour plots | Walkthrough | ``contour_plots.ipynb`` |
| 5. | Contour plots | Exercises | ``exercises/contour_exercise_*.ipynb`` [``*``=1-2] |
| 6. | Regridding data | Walkthrough | ``cf-python_regridding.ipynb`` |
| 7. | Regridding data | Exercises | ``exercises/regridding_exercise_*.ipynb`` [``*``=1-2] |
| 8. | Vector and line plots | Walkthrough | ``vector_line_significance.ipynb`` |
| 9. | Wrap up| Summary | ``wrap_up.ipynb`` |

Model solutions to the exercises can be found under the
``model_answers/`` directory but you are encouraged to find the solutions
yourself before consulting these. As well as the walkthroughs, there is
detailed documentation available to reference, found:

* [here](https://ncas-cms.github.io/cf-python/) for ``cf-python``; &
* [here](http://ajheaps.github.io/cf-plot/) for ``cf-plot``.
