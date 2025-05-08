---
permalink: /projects/
title: "Projects"
author_profile: true
redirect_from:
  - /projects.html
---

HUSTLE-tools [v0.2]
------
![Logo coming soon!](/images/logo-hustle-tools.png)

HUSTLE-tools is a pipeline for downloading, reducing, and extracting 1D spectral time series from [HST WFC3/UVIS G280](https://hst-docs.stsci.edu/wfc3ihb/chapter-8-slitless-spectroscopy-with-wfc3/8-2-slitless-spectroscopy-with-the-uvis-g280-grism) data. Developed as part of the [HUSTLE Treasury Program](https://www.stsci.edu/hst-program-info/download/hst/pdf/17183/), our goal is to increase community use of the G280 observing mode for obtaining exoplanet atmospheric spectra from 200 nm to 800 nm. This crucial ultraviolet-optical bandpass can constrain aerosol opacity and detect photochemically-produced hazes and molecules. G280 data contains many quirks that make it challenging to handle, including curved traces, overlapping orders, variable background signal, and high cosmic ray counts. Our user-friendly pipeline is modular, with each stage initialized by human-readable configuration files designated with the .hustle extension. Designed to be operable with minimal prior coding experience, our one-stop shop for G280 data reduction tackles all of the G280's challenges for you, so you can focus on getting the most from your data.

[Check it out on GitHub!](https://github.com/Exo-TiC/HUSTLE-tools)

Juniper [v0.1]
------
![Logo coming soon!](/images/logo-juniper.png)

Juniper is an in-development pipeline for reducing JWST spectroscopic time series observations. It currently supports NIRSpec observations of transiting and eclipsing exoplanets. The full-release build of Juniper will also support MIRI and NIRCam DHS time series observations, as well as phase curve fitting. Juniper is a modular pipeline divided into six stages. Each stage is initialized with a human-readable configuration file designated with the .berry extension, ensuring results are reproducible and easily shared with colleagues. Juniper aims to be user-friendly and executable with minimal coding background required.

[Check it out on GitHub!](https://github.com/AbbyBoehm/Juniper)