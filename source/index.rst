.. ultra_docs documentation master file, created by
   sphinx-quickstart on Thu Oct 19 16:24:04 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

``ultra``: a python package for pm-level wavefront tolerance analysis for exo-earth imaging
============================================================================================
``ultra`` is a python package developed to estimate maximum allowable wavefront-error drifts for Earth-like
planet imaging with future space telescopes. The package comprises various analytical tools to simulate
wavefront error propagation through a coronagraphic system, to calculate static tolerances using PASTIS algorithm
and dynamic tolerances with a close-loop recursive algorithm. The package supports wavefront-error budget analysis for
multiple segmented-primary mirror architectures with their optimized coronagraphic masks.

.. figure:: images/surface_pm_s.png
   :align: center
   :alt: Example

   Figure : Analysis results for a 19-segment SCDA telescope design

Getting started with ``ultra``
================================
Contents
--------
.. toctree::
   :maxdepth: 1
   :caption: Contents

   introduction.rst
   installation.rst
   workflow.rst

----------------------

Acknowledgements
================
- The `Space Telescope Science Institute collaborators <https://www.stsci.edu/>`_, in particular the ULTRA team.
- Ball Aerospace, L3 Harris Technologies.
