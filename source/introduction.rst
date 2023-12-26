.. _introduction:

============
Introduction
============

``ultra`` repository presents a segment-level thermal stability error budget for segmented space
telescopes crucial to Earth-like planet detection. The package uses multiple segmented primary
mirror architectures concluded from a survey by the SCDA (Segmented Coronagraph Design \& Analysis)
research team at the Space Telescope Science Institute (STScI) for an off-axis,
6m-aperture space telescope. The package leverages a detailed finite element model provided by
L3Harris Technologies to relate the temperature gradient at the location of the primary mirror
to wavefront variations on each segment. Both static and dynamic tolerances (in units of picometer and millikelvin)
can be allocated for each segment using the PASTIS (Pair-based Analytical model for Segmented Telescope Imaging from Space) sensitivity approach,
and a batch-estimation algorithm respectively. Using ``ultra`` we show a non-uniform tolerance allocation
across all segments of the primary mirror. In general, we see a trend that with an increase in segment numbers,
the tolerances for outer segments become less stringent. We see trade-offs between segment size, tolerance relaxation
and an optimal wavefront sensing time scale to achieve the desired target contrast.