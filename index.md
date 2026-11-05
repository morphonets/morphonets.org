---
layout: default
title: Morphonets
---
<p align="center"><img src="static/MorphonetsLogo.png" alt="Morphonets, SNT, SNT Stream, and PySNT logos" width="600"></p>
<h1 align="center">Welcome To Morphonets!</h1>


Morphonets is an open, community-driven effort to provide tools for tracing, visualization, quantification, and modeling of neuroanatomical data, from [Fiji](https://fiji.sc)/[ImageJ](https://imagej.net) to [Python](https://github.com/morphonets/pysnt) and [napari](https://napari.org). The tools we create are leveraged by the powerful stack of [SciJava](https://scijava.org)-based software.
Our immediate focus is cellular neuroscience, but the software we develop has been successfully applied to other areas of the biosciences.



## Projects
Morphonets has incorporated several projects that were previously scattered across the Fiji ecosystem of plugins. Currently, the following major projects are being developed under the Morphonets umbrella:

- [SNT](https://github.com/morphonets/SNT): The open-source framework for quantification of neuronal anatomy. SNT supports the full reconstruction workflow: semi- and fully automated tracing, proofreading, visualization (2D, 3D and large-volume viewers), morphometry, Sholl and other comparative analyses, and connectivity-oriented graph analysis. It can be driven from the GUI, from multi-language scripts, and reads/writes community standard formats ([documentation](https://imagej.net/plugins/snt/), [publication](https://rdcu.be/c9LJe))

- [SNT Stream](https://imagej.net/plugins/snt/snt-stream): The big data cousin of SNT. SNT Stream enables tracing and analysis of terabyte-scale volumes, including remote OME-Zarr and N5 datasets, with interactive 3D visualization powered by BigDataViewer and BigVolumeViewer ([documentation](https://imagej.net/plugins/snt/snt-stream))

- [PySNT](https://github.com/morphonets/pysnt): A Python wrapper for SNT. It brings SNT's tracing and analysis capabilities to the Python ecosystem (e.g., Jupyter notebooks and NumPy/pandas-based pipelines), without requiring a separate Fiji workflow ([documentation](https://pysnt.readthedocs.io), [PyPI](https://pypi.org/project/pysnt/))

- [napari-snt](https://github.com/morphonets/napari-snt): A [napari](https://napari.org) plugin that bridges napari and SNT. It sends polylines drawn in napari to SNT and receives SNT reconstructions back as napari layers, so that the strengths of both platforms can be combined

- [Sciview-Cx3D](https://github.com/morphonets/cx3d): An image-based modeling framework powered by Cx3D and [sciview](https://github.com/scenerygraphics/sciview)  ([documentation](https://imagej.net/plugins/snt/modeling))

- Sholl Analysis: Originally a [stand-alone project](https://github.com/tferr/ASA#sholl-analysis), _Sholl Analysis_ has been incorporated into SNT ([documentation](https://imagej.net/plugins/sholl-analysis), [publication](https://rdcu.be/c9LI8))


## Learning Resources

- [Computational Neuroanatomy with PySNT](https://pysnt.readthedocs.io/en/latest/notebooks/index.html) is a hands-on, self-paced curriculum of runnable notebooks that teaches neuroanatomy in Python using real data. Each notebook states its learning objectives and estimated time, and the series is ordered by increasing complexity: from a single reconstruction to atlas-scale analysis and ML-ready ground truth. It assumes basic Python only, and no prior SNT or Java experience.

- For scripting inside Fiji, SNT ships with dozens of ready-to-run [script templates](https://imagej.net/plugins/snt/scripting) in Groovy and Python covering analysis, batch processing, tracing, rendering, and big data. Open them from the Script Editor (*Templates › Neuroanatomy*) and adapt them to your own data.

- Also available is a series of community resources, from [forum posts](https://forum.image.sc/tag/snt/) to [screencast tutorials](https://imagej.net/plugins/snt/screencasts).


## Getting Involved
[Anyone can contribute](https://imagej.net/plugins/snt/contribute)! Contact us on [GitHub](https://github.com/morphonets) or the [Image.sc Forum](https://forum.image.sc/)
