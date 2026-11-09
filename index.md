---
layout: default
title: Morphonets
---
<p align="center"><img src="static/MorphonetsLogo.png" alt="Morphonets, SNT, SNT Stream, and PySNT logos" width="600"></p>
<h1 align="center">Welcome To Morphonets!</h1>


Morphonets is an open, community-driven effort to provide tools for tracing, visualization, quantification, and modeling of neuroanatomical data, from [Fiji](https://fiji.sc)/[ImageJ](https://imagej.net) to [Python](https://github.com/morphonets/pysnt) and [napari](https://napari.org). Our tools stand on the shoulders of [SciJava](https://scijava.org) and its Python sibling [scyjava](https://github.com/scijava/scyjava).
Our immediate focus is cellular neuroscience, but the software we develop has been successfully applied to other areas of the biosciences.



## Projects
Morphonets has incorporated several projects that were previously scattered across the Fiji ecosystem of plugins. Currently, the following major projects are being developed under the Morphonets umbrella:

<style>
.pj-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(min(16rem,100%),1fr));gap:.9rem;margin:1rem 0 1.5rem}
.pj-card{display:flex;flex-direction:column;border:1px solid #e5e5e5;border-top:3px solid #515151;border-radius:6px;padding:.7rem .8rem;background:#fff;transition:box-shadow .15s,transform .15s}
.pj-card:hover{box-shadow:0 3px 10px rgba(0,0,0,.15);transform:translateY(-2px)}
.pj-head{display:flex;justify-content:space-between;align-items:baseline;margin-bottom:.3rem}
.pj-name{font-weight:bold;font-size:1rem;color:#313131}
.pj-tag{font-size:.65rem;text-transform:uppercase;letter-spacing:.05em;color:#fff;background:#6b6b6b;border-radius:3px;padding:0 .4rem}
.pj-card p{font-size:.82rem;line-height:1.4;margin:0 0 .5rem;color:#515151}
.pj-links{margin-top:auto;font-size:.78rem}
.pj-badges{margin-top:auto;display:flex;flex-wrap:wrap;gap:.3rem;padding-bottom:.5rem}
.pj-badges img{display:block;height:18px}
.pj-badges + .pj-links{margin-top:0}
.pj-links a{margin-right:.7rem}
.pj-grid.pj-2{grid-template-columns:repeat(auto-fit,minmax(min(20rem,100%),1fr))}
</style>
<div class="pj-grid">
<div class="pj-card"><div class="pj-head"><span class="pj-name">SNT</span><span class="pj-tag">Fiji</span></div><p>The open-source framework for quantification of neuronal anatomy: semi- and fully automated tracing, proofreading, 2D, 3D and large-volume visualization, morphometry, Sholl and other comparative analyses, and graph analysis.</p><div class="pj-badges"><a href="https://github.com/morphonets/SNT/releases"><img src="https://img.shields.io/github/v/release/morphonets/SNT?style=flat-square&include_prereleases&label=release" alt="SNT latest release" loading="lazy"></a></div><div class="pj-links"><a href="https://imagej.net/plugins/snt/">Documentation</a><a href="https://rdcu.be/c9LJe">Publication</a><a href="https://github.com/morphonets/SNT">GitHub</a></div></div>
<div class="pj-card"><div class="pj-head"><span class="pj-name">SNT Stream</span><span class="pj-tag">Fiji</span></div><p>The big data cousin of SNT: tracing and analysis of terabyte-scale volumes, including remote OME-Zarr and N5 datasets, with interactive 3D visualization powered by BigDataViewer and BigVolumeViewer.</p><div class="pj-badges"><a href="https://github.com/morphonets/SNT/releases"><img src="https://img.shields.io/github/v/release/morphonets/SNT?style=flat-square&include_prereleases&label=included%20in%20SNT" alt="SNT latest release" loading="lazy"></a></div><div class="pj-links"><a href="https://imagej.net/plugins/snt/snt-stream">Documentation</a></div></div>
<div class="pj-card"><div class="pj-head"><span class="pj-name">PySNT</span><span class="pj-tag">Python</span></div><p>A Python wrapper for SNT that brings its tracing and analysis capabilities to Jupyter notebooks and NumPy/pandas-based pipelines, without a separate Fiji workflow.</p><div class="pj-badges"><a href="https://pypi.org/project/pysnt/"><img src="https://img.shields.io/pypi/v/pysnt?style=flat-square&label=PyPI" alt="PySNT on PyPI" loading="lazy"></a></div><div class="pj-links"><a href="https://pysnt.readthedocs.io">Documentation</a><a href="/computational-neuroanatomy/">Curriculum</a><a href="https://pypi.org/project/pysnt/">PyPI</a><a href="https://github.com/morphonets/pysnt">GitHub</a></div></div>
<div class="pj-card"><div class="pj-head"><span class="pj-name">napari-snt</span><span class="pj-tag">napari</span></div><p>A napari plugin that bridges napari and SNT: it sends polylines drawn in napari to SNT and receives SNT reconstructions back as napari layers.</p><div class="pj-badges"><a href="https://github.com/morphonets/napari-snt"><img src="https://img.shields.io/badge/SNT%20add--on-napari%20bridge-2a8c82?style=flat-square" alt="SNT add-on: napari bridge" loading="lazy"></a></div><div class="pj-links"><a href="https://github.com/morphonets/napari-snt">GitHub</a></div></div>
<div class="pj-card"><div class="pj-head"><span class="pj-name">Sciview-Cx3D</span><span class="pj-tag">Modeling</span></div><p>An image-based modeling framework for neurodevelopment simulations powered by Cx3D and sciview.</p><div class="pj-badges"><a href="https://github.com/morphonets/cx3d"><img src="https://img.shields.io/badge/SNT%20add--on-optional-2a8c82?style=flat-square" alt="SNT add-on: optional" loading="lazy"></a></div><div class="pj-links"><a href="https://imagej.net/plugins/snt/modeling">Documentation</a><a href="https://github.com/morphonets/cx3d">GitHub</a></div></div>
<div class="pj-card"><div class="pj-head"><span class="pj-name">Sholl Analysis</span><span class="pj-tag">Fiji</span></div><p>Sholl analysis directly from images, with no tracing required, or from reconstructions. Originally a stand-alone project, now incorporated into SNT.</p><div class="pj-badges"><a href="https://github.com/morphonets/SNT/releases"><img src="https://img.shields.io/github/v/release/morphonets/SNT?style=flat-square&include_prereleases&label=included%20in%20SNT" alt="SNT latest release" loading="lazy"></a></div><div class="pj-links"><a href="https://imagej.net/plugins/snt/sholl">Documentation</a><a href="https://rdcu.be/c9LI8">Publication</a></div></div>
</div>

## Learning Resources

<div class="pj-grid pj-2">
<div class="pj-card"><div class="pj-head"><span class="pj-name">Computational Neuroanatomy</span><span class="pj-tag">Python</span></div><p>A self-paced series of runnable notebooks that teaches neuroanatomy in Python using real data, from a single reconstruction to atlas-scale analysis and ML-ready ground truth. Assumes basic Python only.</p><div class="pj-links"><a href="/computational-neuroanatomy/">Start the curriculum</a></div></div>
<div class="pj-card"><div class="pj-head"><span class="pj-name">Script Templates</span><span class="pj-tag">Fiji</span></div><p>More than 70 ready-to-run scripts in Groovy and Python covering analysis, batch processing, tracing, rendering, and big data. Open them from the Script Editor (Templates &gt; Neuroanatomy) and adapt them to your data.</p><div class="pj-links"><a href="https://imagej.net/plugins/snt/scripting">Documentation</a></div></div>
<div class="pj-card"><div class="pj-head"><span class="pj-name">Screencast Tutorials</span><span class="pj-tag">Video</span></div><p>Video tutorials for getting started with SNT and its main workflows.</p><div class="pj-links"><a href="https://imagej.net/plugins/snt/screencasts">Screencasts</a></div></div>
<div class="pj-card"><div class="pj-head"><span class="pj-name">Image.sc Forum</span><span class="pj-tag">Community</span></div><p>Questions, tips, and discussions about SNT from users and developers.</p><div class="pj-links"><a href="https://forum.image.sc/tag/snt/">Forum posts</a></div></div>
</div>

## Getting Involved
[Anyone can contribute](https://imagej.net/plugins/snt/contribute)! Contact us on [GitHub](https://github.com/morphonets) or the [Image.sc Forum](https://forum.image.sc/)
