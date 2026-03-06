---
title: "Fast and universal single-molecule localization using multi-dimensional point spread functions"
collection: publications
category: manuscripts
permalink: /publication/fast-and-universal-smlm
excerpt: ''
date: 2024-11-06
venue: 'Optics Express'
# slidesurl: ''
paperurl: 'https://doi.org/10.1364/OE.531588'
# bibtexurl: ''
# citation: ''
---
The recent development of single-molecule imaging techniques has enabled not only high accuracy spatial resolution imaging but also information rich functional imaging. Abundant information about single molecules can be encoded in its diffraction pattern and be extracted precisely (e.g. 3D position, wavelength, dipole orientation). However, sophisticated high dimensional point spread function (PSF) modeling and analyzing methods have greatly impeded the broad accessibility of these techniques. Here, we present a graphics processing unit (GPU) -based B-spline PSF modeling method that could flexibly model high dimensional PSFs with arbitrary shape without greatly increasing the model parameters. Our B-spline fitter achieves 100 times speed improvement and minimal uncertainty for each dimension, enabling efficient high dimensional single-molecule analysis. We demonstrated, both in simulations and experiments, the universality and flexibility of our B-spline fitter to accurately extract the abundant information from different types of high dimensional single-molecule data, including multicolor PSF (3D + color), multi-channel four-dimensional 4Pi-PSF (3D + interference phase) and five-dimensional vortex PSF (3D + dipole orientation).