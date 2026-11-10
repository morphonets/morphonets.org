---
layout: page
title: Computational Neuroanatomy
permalink: /computational-neuroanatomy/
nav: false
---
<p class="lead"><em>Computational Neuroanatomy: A Hands-on Curriculum in Python</em> is a free, self-paced series of runnable notebooks that teaches neuroanatomy in Python using real data. The series is ordered by increasing complexity, from a single reconstruction to atlas-scale analysis and ML-ready ground truth.</p>

<p><a href="https://pysnt.readthedocs.io/en/latest/notebooks/index.html"><strong>Start the curriculum</strong></a> (hosted on Read the Docs)</p>

## At a glance

- **Audience:** neuroscientists and image analysts comfortable with basic Python. No prior SNT or Java experience is needed
- **Format:** 9 self-contained notebooks, each stating its learning objectives, estimated time, and requirements. About 4 to 5 hours in total
- **Data:** real reconstructions and volumes (e.g., MouseLight, NeuroMorpho.org, remote OME-Zarr), analyzed with SNT through [PySNT](https://github.com/morphonets/pysnt) alongside NumPy, pandas, NetworkX, napari, and scikit-learn
- **Access:** open and free, no registration. Notebooks can be read online or downloaded and run locally

## Tutorials

<style>
.nb-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(14rem,1fr));gap:.9rem;margin:1rem 0 1.5rem}
.nb-card{display:flex;flex-direction:column;border:1px solid #e5e5e5;border-radius:6px;overflow:hidden;text-decoration:none;color:inherit;background:#fff;transition:box-shadow .15s,transform .15s}
.nb-card:hover{box-shadow:0 3px 10px rgba(0,0,0,.15);transform:translateY(-2px)}
.nb-card img{display:block;width:100%;height:8rem;object-fit:cover;background:#f5f5f5}
.nb-body{display:flex;flex-direction:column;flex:1;padding:.5rem .6rem .6rem}
.nb-num{font-size:.7rem;font-weight:bold;color:#6b6b6b;letter-spacing:.05em}
.nb-title{display:block;font-size:.85rem;line-height:1.25;margin:.1rem 0 .4rem;color:#313131}
.nb-meta{margin-top:auto;font-size:.7rem;color:#666}
.nb-lvl{display:inline-block;padding:0 .4rem;border-radius:3px;color:#fff;margin-right:.3rem}
.nb-Beginner{background:#2e7d46}.nb-Intermediate{background:#a8620a}.nb-Advanced{background:#b3382a}
</style>
<div class="nb-grid">
<a class="nb-card" href="https://pysnt.readthedocs.io/en/latest/notebooks/01_single_cell_analysis.html"><img src="/static/curriculum/t01.jpg" alt="" loading="lazy"><span class="nb-body"><span class="nb-num">T01</span><span class="nb-title">Single Cell Analysis</span><span class="nb-meta"><span class="nb-lvl nb-Beginner">Beginner</span>20-30 min</span></span></a>
<a class="nb-card" href="https://pysnt.readthedocs.io/en/latest/notebooks/02_napari_viewer.html"><img src="/static/curriculum/t02.jpg" alt="" loading="lazy"><span class="nb-body"><span class="nb-num">T02</span><span class="nb-title">Visualizing Reconstructions in napari</span><span class="nb-meta"><span class="nb-lvl nb-Beginner">Beginner</span>10-15 min</span></span></a>
<a class="nb-card" href="https://pysnt.readthedocs.io/en/latest/notebooks/03_hemisphere_analysis.html"><img src="/static/curriculum/t03.jpg" alt="" loading="lazy"><span class="nb-body"><span class="nb-num">T03</span><span class="nb-title">Hemisphere Analysis</span><span class="nb-meta"><span class="nb-lvl nb-Beginner">Beginner</span>30 min</span></span></a>
<a class="nb-card" href="https://pysnt.readthedocs.io/en/latest/notebooks/04_convex_hull.html"><img src="/static/curriculum/t04.jpg" alt="" loading="lazy"><span class="nb-body"><span class="nb-num">T04</span><span class="nb-title">Volumetric Quantifications</span><span class="nb-meta"><span class="nb-lvl nb-Intermediate">Intermediate</span>30-40 min</span></span></a>
<a class="nb-card" href="https://pysnt.readthedocs.io/en/latest/notebooks/05_tree_intersection.html"><img src="/static/curriculum/t05.jpg" alt="" loading="lazy"><span class="nb-body"><span class="nb-num">T05</span><span class="nb-title">Spatial Intersection Between Trees</span><span class="nb-meta"><span class="nb-lvl nb-Intermediate">Intermediate</span>30-40 min</span></span></a>
<a class="nb-card" href="https://pysnt.readthedocs.io/en/latest/notebooks/06_persistence_landscape.html"><img src="/static/curriculum/t06.jpg" alt="" loading="lazy"><span class="nb-body"><span class="nb-num">T06</span><span class="nb-title">Unsupervised Classification of Projection Neurons</span><span class="nb-meta"><span class="nb-lvl nb-Intermediate">Intermediate</span>40 min</span></span></a>
<a class="nb-card" href="https://pysnt.readthedocs.io/en/latest/notebooks/07_curvature_optimization.html"><img src="/static/curriculum/t07.jpg" alt="" loading="lazy"><span class="nb-body"><span class="nb-num">T07</span><span class="nb-title">Curvature Optimization with Automated Path Tracing</span><span class="nb-meta"><span class="nb-lvl nb-Advanced">Advanced</span>45 min</span></span></a>
<a class="nb-card" href="https://pysnt.readthedocs.io/en/latest/notebooks/08_crossover_detection.html"><img src="/static/curriculum/t08.jpg" alt="" loading="lazy"><span class="nb-body"><span class="nb-num">T08</span><span class="nb-title">Crossover Detection</span><span class="nb-meta"><span class="nb-lvl nb-Advanced">Advanced</span>15-20 min</span></span></a>
<a class="nb-card" href="https://pysnt.readthedocs.io/en/latest/notebooks/09_big_data.html"><img src="/static/curriculum/t09.jpg" alt="" loading="lazy"><span class="nb-body"><span class="nb-num">T09</span><span class="nb-title">Handling Large-Scale Neuronal Data</span><span class="nb-meta"><span class="nb-lvl nb-Advanced">Advanced</span>30 min</span></span></a>
</div>

## Source, license, and feedback

The source of every notebook is on [GitHub](https://github.com/morphonets/pysnt/tree/main/docs/notebooks). Text and figures are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), code under the PySNT [license](https://github.com/morphonets/pysnt/blob/main/LICENSE.md), and datasets are subject to their original terms. Corrections, new tutorials, and feedback are welcome on the [forum](https://forum.image.sc/tag/snt) or as [issues](https://github.com/morphonets/pysnt/issues).

## Citing

> Ferreira TA, PySNT and SNT contributors. *Computational Neuroanatomy: A Hands-on Curriculum in Python*. [morphonets.org/computational-neuroanatomy](https://morphonets.org/computational-neuroanatomy/), [doi:10.5281/zenodo.24090107](https://doi.org/10.5281/zenodo.24090107)

See also the [SNT citation guidelines](https://imagej.net/plugins/snt/faq#how-do-i-cite-snt).
