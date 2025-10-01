# New course

This is the latest (2024+) training course for the CF Data Tools, cf-python and cf-plot.

### Course format

In the form of Jupyter Notebooks. At present the course only contains the core content but extension modules will be added to cover certain topics in depth and to show the libraries in real practical use cases.

Consisting of (at present - to be extended):

* **core module** with taught and practical elements of corresponding section numbers from 1 to 6:
  * **six teaching Notebooks `cf_data_tools_intro_0[N].ipynb` for N: 1-6**
    of introduction, setup and six sections, designed to be lectured as a taught
    walkthrough interleaved with the corresponding practical sessions from the practical
    Notebook below after every 2-3 sections are taught, overall taking around 2 hours to teach
    (but can also be followed along with independently);
  * **six practical Notebooks `cf_data_tools_practical_0[N].ipynb` for N: 1-6**  with
     introductory context and reminders then six sections of practical questions with model answers
     for the sections matching the teaching Notebooks, designed to be worked through after the
     corresponding taught sections are presented from the above teaching
     Notebook (but can also be worked through independently). Model anwers are provided in the directory `practicals_model_answers`.


Note this material corresponds to the first trialled new course which was split into six separate Notebooks for both the taught and practical elements after attendee feedback. The old Notebooks, with all six of the same sections but in one longer Notebook for each case, are kept in `old_longer_notebooks`, but now deprecated.


### Course structure

Core module:

| Section | Topic | Teaching Notebook ('T*') | Corresponding practical Notebook ('P*') with model answers in `practicals_model_answers` |
|---|---|---|---|
| 1. | Reading dataset(s) and viewing the (meta)data at different detail levels | T1: ``cf_data_tools_intro_01.ipynb``  | P1: ``cf_data_tools_practical_01.ipynb`` |
| 2. | Editing the (meta)data and writing out the edited version to file | T2: ``cf_data_tools_intro_02.ipynb`` | P2: ``cf_data_tools_practical_02.ipynb`` |
| 3. | Reducing datasets by subspacing and collapsing | T3: ``cf_data_tools_intro_03.ipynb`` | P3: ``cf_data_tools_practical_03.ipynb`` |
| 4. | Visualising datasets as contour and vector plots | T4: ``cf_data_tools_intro_04.ipynb`` | P4: ``cf_data_tools_practical_04.ipynb`` |
| 5. | Analysing data: applying operations and plotting trends | T5: ``cf_data_tools_intro_05.ipynb`` | P5: ``cf_data_tools_practical_05.ipynb`` |
| 6. | Changing the underlying grid of data through regridding | T6: ``cf_data_tools_intro_06.ipynb`` | P6: ``cf_data_tools_practical_06.ipynb`` |


### Setup

As a computing environment requires (at least):

* service or server capable of running Jupyter Notebook, locally or hosted at location of choice
  which could be externally or in-browser;
* cf-python v. 3.16.2 or higher (latest version preferred);
* cf-plot v. 3.3.0 or higher (latest version preferred);
* Python v.3.8.0., the minimum Python version that is compatible with the above cf* minimum versions (latest stable version of Python preferred).
