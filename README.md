# Pmax


This repository contains the Python code used for data processing, statistical
analysis and visualization described in the following paper:

Szakmar E, Morley CJ, Belteki G. **Analysis of peak inflating pressure and
inflating pressure limit during neonatal volume guaranteed ventilation.**
_Journal of Perinatology_, 2019 Jan;39(1):72-79.
doi: 10.1038/s41372-018-0228-2. Epub 2018 Sep 19. PubMed PMID: 30232377.

Link to the paper: https://www.nature.com/articles/s41372-018-0228-2

Contact: gusztav.belteki@addenbrookes.nhs.uk; gbelteki@aol.com

____


The outputs (numbers, tables, graphs) of the cells of the Jupyter Notebooks
(.ipynb files) have been suppressed in order to comply with copyrights.
Some of the corresponding data and graphs can be found in the paper and its
only supplementary material.

This code can be viewed in any web browser. If the code is displayed (rendered)
 in Github, copy and paste the URL (web adress) of the Notebook into **nbviewer**
(https://nbviewer.jupyter.org) for a read-only display.

To run the code, you need to use Jupyter.
The raw ventilator data are not shared but the user can run this code on his or
her own data obtained in the same format.

____

Packages required to run this Notebook:

Python version: 3.5.3

IPython version: 5.3.0

pandas version: 0.20.1

matplotlib version: 2.0.2

NumPy version: 1.12.1

SciPy version: 0.19.0

I recommend downloading these packages using the freely availably Anaconda
built: https://www.continuum.io/downloads

____

The Notebook also depends on the supplied helper files which should be in the
same directory as the .ipynb notebook files.

gb_loader.py

gb_stats.py

gb_transform.py

gb_visualizer.py
