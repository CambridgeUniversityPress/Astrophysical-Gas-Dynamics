# *Astrophysical Gas Dynamics*

Jupyter notebooks, python code, and selected data files and sources for the figures from *Astrophysical Gas Dynamics* by Barbara Ryden.

## Overview
*Astrophysical Gas Dynamics* by Barbara S. Ryden is the fourth volume in *The Ohio State Astrophysics Series* of 
textbooks published by Cambridge University Press.  The audience for this series is graduate students and upper-level undergraduates studying
astronomy and physics.

Most of the original figures in this book were created by the Richard Pogge (OSU), the technical editor of the OSAS book series, the majority of 
which are plots of data or calculations made using Python programs implemented as Jupyter notebooks. We are making all the notebooks available 
on GitHub as an ancillary to the book.

Instructors and students using *Astrophysical Gas Dynamics* are welcome to use these notebooks to make high-resolution versions
of the book figures for presentations, adapt them for use in class, or to use as the basis for problem sets or projects in courses 
adopting this book.  Over time we hope to collect and present other notebooks that will enable further explorations of topics in the book, 
become part of computational problem sets or individual and group projects, etc. This way, the figures become a starting point for learning
and new explorations rather than being frozen into print.

## Software Requirements

All notebooks were developed in Python 3 using the [Anaconda Python distribution](https://www.anaconda.com). 

Required packages are `numpy`, `scipy`, `pandas`, `matplotlib`, `pathlib` and `astropy`, all part of Anaconda. 

LaTeX is required for math symbols in the notebooks.

**Note**: Please update
matplotlib to later than version 3.8 as we make use of some low-level features that required changes to the code 
that are not backwards compatible with older versions.

## Downloads

### Download and Install

To download a copy of this repository onto your local computer, go to the folder on your computer where you want to install it and type

> `git clone https://github.com/CambridgeUniversityPress/Astrophysical-Gas-Dynamics`

This will create the `Astrophysical-Gas-Dynamics` folder containing the entire repository.  You may rename this repository after
installation to shorten the name if you wish (e.g., `/path/to/wherever/AGD`).

### Update the notebooks and data

To update your copy, go into the top-level folder you created above (e.g., `/path/to/wherever/AGD`) and type

> `git pull`

If there are no updates, your local copy will be unaffected.

## Use and Attribution

The notebooks and their contents are original works of the authors and often include data obtained from public archives or from 
professional colleagues (always from published sources).  We ask that users preserve all literature citations to the original work
from which such data were derived, and give proper credit when using them. 

If you use these notebooks, please cite the  *Astrophysical Gas Dynamics* book (see below), including the figure number and the 
repository (include the GitHub url) with the original code. If the plot you are using (or replotting) includes data, also include a
citation of the data source (journal article, online database, etc.).

### Book Citation

DOI: coming soon

#### BibTeX
BibTeX citation text ready to cut-and-paste. 
```
@book{Ryden_2025,
       author = {Ryden, Barbara},
       title = {Astrophysical Gas Dynamics},
       year = {2026},
       doi = {10.1017/coming soon}
}
```

### License Notice

All files in this repository are licensed under a [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/), 
to foster broader use of the notebooks and their data by teachers and students.

