---
layout: default
title: Morphonets
---
<p align="center"><img src="static/MorphonetsLogo.png" alt="<a href='https://github.com/morphonets/misc/blob/master/MorphonetsLogo.ijm'>The Morphonets logo was created by an IJ macro!</a>" width="200" height="200"></p>
<h1 align="center">Welcome To Morphonets!</h1>


Morphonets is an open, community-driven effort to provide tools for tracing, visualization, quantification, and modeling of neuroanatomical data, from [Fiji](https://fiji.sc)/[ImageJ](https://imagej.net) to [Python](https://github.com/morphonets/pysnt) and [napari](https://napari.org). The tools we create are leveraged by the powerful stack of [SciJava](https://scijava.org)-based software.
Our immediate focus is cellular neuroscience, but the software we develop has been successfully applied to other areas of the biosciences. 



## Projects
Morphonets has incorporated several projects that were previously scattered across the Fiji ecosystem of plugins. Currently, the following major projects are being developed under the Morphonets umbrella:

- [SNT](https://github.com/morphonets/SNT): The open-source framework for quantification of neuronal anatomy. SNT supports the full reconstruction workflow: semi- and fully automated tracing, proofreading, visualization (2D, 3D and large-volume viewers), morphometry, Sholl and other comparative analyses, and connectivity-oriented graph analysis. It can be driven from the GUI, from scripts (Groovy, Python, etc.), or from the command line, and reads/writes community standard formats such as SWC and OME-Zarr ([user-based documentation](https://imagej.net/plugins/snt/), [publication](https://rdcu.be/c9LJe))
- [PySNT](https://github.com/morphonets/pysnt): A Python wrapper for SNT. It brings SNT's tracing and analysis capabilities to the Python ecosystem (e.g., Jupyter notebooks and NumPy/pandas-based pipelines), without requiring a separate Fiji workflow ([documentation](https://pysnt.readthedocs.io), [PyPI](https://pypi.org/project/pysnt/))
- [napari-snt](https://github.com/morphonets/napari-snt): A [napari](https://napari.org) plugin that bridges napari and SNT. It sends polylines drawn in napari to SNT and receives SNT reconstructions back as napari layers, so that the strengths of both platforms can be combined
- Sholl Analysis: Originally a [stand-alone project](https://github.com/tferr/ASA#sholl-analysis), _Sholl Analysis_ has been incorporated into SNT ([user-based documentation](https://imagej.net/plugins/sholl-analysis), [publication](https://rdcu.be/c9LI8))
- [Sciview-Cx3D](https://github.com/morphonets/cx3d): A image-based modeling framework powered by Cx3D and [sciview](https://github.com/scenerygraphics/sciview)  ([user-based documentation](https://imagej.net/plugins/snt/modeling))


## Downloads
SNT is available in [Fiji](https://imagej.net/Fiji) by means of two [update sites](https://imagej.net/Update_Sites): *Neuroanatomy* and optionally *sciview*:

1.  Run the Fiji Updater (*Help › Update...*, the penultimate entry in Fiji's *Help>* menu)
2.  Click *Manage update sites*
3.  Select the *Neuroanatomy* checkbox. Optionally, you can also select the *sciview* checkbox
4.  Click *Apply changes* and Restart

Python users can install PySNT with `pip install pysnt` (see the [installation guide](https://pysnt.readthedocs.io/en/latest/install.html)).



# Getting Involved
Contact us on [GitHub](https://github.com/morphonets) or the [Image.sc Forum](https://forum.image.sc/)
