.. _introduction:

============
Introduction
============

Imaging and characterizing Earth-like planets (or exo-Earth) is one of the key science goals for the future `Habitable Worlds Observatory (HWO) <https://www.greatobservatories.org/hwo-start>`_. Exo-Earths are ten-billion times fainter than their host stars and to directly image them we require coronagraphs to block bright glare from the host star light. Performance of a coronagraph is limited by the quality of incoming wavefront. Thermal aberrations in the observatory's conditions can induce surface deformation and is identified as one of the major limiting factors for wavefront stability. Evaluating impact of surface deformation on the coronagraphic-science images, and thereby estimating the wavefront tolerance requirements will be a key aspect for designing primary mirror architecture and technologies for HWO.


Why ``ultra``?
=================
Using the ``ultra`` python package we demonstrate a wavefront error stability budget for future space missions pertinent to exo-Earth detection. The package supports wavefront-error-budget analysis for several segmented primary mirror architectures with their optimized `APLC <https://iopscience.iop.org/article/10.1086/427923/meta>`_ coronagraphs. The wavefront error drifts can be expressed in a basis of sinusoidal modes (high-spatial frequency) or segment-level Zernike modes (mid-spatial frequency) or global Zernike modes (low-spatial frequency). In addition, the package can also be used to estimate segment-level temperature requirements using finite element model (FEM) from L3Harris Technologies. The FEM model relates temperature gradient at the location of primary to surface deformation, and thereby to wavefront error. We can allocate static and dynamic tolerances (in units of picometer and mK) using the `PASTIS <https://github.com/spacetelescope/PASTIS>`_ (Pair-based Analytical model for Segmented Telescope Imaging from Space) sensitivity approach and a recursive batch estimation algorithm respectively established in `Leonid et al. (2021) <https://iopscience.iop.org/article/10.3847/1538-4365/ac126d>`_ for multiple segmented mirror architectures.


Getting ``ultra``
=================
To use the package users are recommended to have a basic working knowledge of `Python <https://www.python.org/>`_, `Conda <https://docs.conda.io/projects/conda/en/stable/user-guide/index.html>`_ and `Git <https://git-scm.com/>`_. The instructions on how to install and launch ``ultra`` package are mentioned in :ref:`installation` and :ref:`workflow` respectively.
