# Impact of Diagnostic Time and Demographic Features on Sepsis Mortality

### Seth Cattanach and Thomas Clare, University of Notre Dame
### CSE-40817 Healthcare Analytics - Fall 2018 - Capstone Project

#### Note about files:

* *project.ipynb* contains the final version of the project code. To run, Jupyter notebooks must be installed properly on the user's system. The project requires several data science and scientific computing packages (patsy, SciPy, Pandas, Lifelines, etc.) that can be installed with *pip* (example: *pip install lifelines* will satisfy dependencies for the survival analysis components of this project, including Cox regression and Kaplan-Meier curves)
* *report.pdf* is the final project report, which includes discussion of project goals, outcomes, and related work
* *slider_demo.ipynb* and *Project-Step-1.ipynb* are early attempts at various parts of the project; for example, the slider demo is an early version of the project code that tests interactive functionality with iPython widgets. These two notebooks can largely be ignored as *project.ipynb* contains the full working code based on these early versions.

This project was initially inspired by an analysis of sepsis mortality and identification methods done by Alistair Johnson and others. Their work is cited below:


@misc{alistair_johnson_2018_1256723,
  author       = {Alistair Johnson and Tom Pollard},
  title        = {sepsis3-mimic},
  version      = {1.0.0},
  publisher    = {Zenodo},
  month        = may,
  year         = 2018,
  doi          = {10.5281/zenodo.1256723},
  url          = {https://doi.org/10.5281/zenodo.1256723}
}
