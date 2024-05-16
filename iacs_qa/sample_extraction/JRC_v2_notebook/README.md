# IACS QA Sample Extraction
<div>
<img src="images/jrc_ec_logo.jpg" width="400"/>
</div>

The code included in this notebook, developed by the JRC, implements the procedure for Member States to define their samples for the IACS quality assessment. This involves extracting parcels from the ranked list provided by the Commission, following the selection rules in the Union Level Methodology 2024 (Chapters 3 and 4). Member States have discretion over the sample sizes, within the constraints of the Methodology.

The tool takes the ranked list in CSV format and returns a list of parcels assigned to buckets representing different interventions.

Authors: Mateusz Dobrychłop (mateusz.dobrychlop@ext.ec.europa.eu), Fernando Fahl (fernando.fahl@ext.ec.europa.eu), Ferdinando Urbano (ferdinando.urbano@ec.europa.eu)

## Release notes

**Version 2 (Jupyter Notebook)**

The solution is still in its beta testing phase. Implementation of some of the expected features and general optimization is planned for the upcoming weeks.

Current version of the tool follows an algorithm that offers a limited number of options, and exhibits less-than-optimal performance in computational speed. The following developments are planned for the near future:

* All parcels, covered and not covered by the HR images, are currently taken into account. This aspect will be controlled by a set of configuration parameters in an upcoming update (that will let the user prioritize covered parcels)

* Limiting the fraction of holdings (the *3% rule*) is not implemented yet (but will be soon)

* Some more flexibility regarding the output will soon be introduced. We are also working on making the output more informative.

* In the upcoming updates, a lot of emphasis will be placed on speed improvements.

## Jupyter Notebook

The solution is written in Python, and made available in the form of a **Jupyter Notebook**. It is an interactive document that allows you to combine executable code, text, images, and visualizations all in one easily accessible place. Documentation can be found [here](https://docs.jupyter.org/en/latest/).

To open and use this notebook, you will need an environment that supports Jupyter Notebooks. Some recommended options to look into:
* Running the notebook in your web browser [(link)](https://docs.jupyter.org/en/latest/running.html)
* JupyterLab [(link)](https://jupyterlab.readthedocs.io/en/latest/)
* Visual Studio Code [(link)](https://code.visualstudio.com/download)