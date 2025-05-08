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

<div style="text-align: justify; text-justify: inter-word;">
  <p>HUSTLE-tools is a pipeline for downloading, reducing, and extracting 1D spectral time series from <a href="https://hst-docs.stsci.edu/wfc3ihb/chapter-8-slitless-spectroscopy-with-wfc3/8-2-slitless-spectroscopy-with-the-uvis-g280-grism">HST WFC3/UVIS G280</a> data. Developed as part of the <a href="https://www.stsci.edu/hst-program-info/download/hst/pdf/17183/">HUSTLE Treasury Program</a> and combining the the <a href="https://github.com/AbbyBoehm/HST-WFC3-G280-TSO_pipeline">Hazelnut</a> and lluvia pipelines, our goal is to increase community use of the G280 observing mode for obtaining exoplanet atmospheric spectra from 200 nm to 800 nm. This crucial ultraviolet-optical bandpass can constrain aerosol opacity and detect photochemically-produced hazes and molecules. G280 data contains many quirks that make it challenging to handle, including curved traces, overlapping orders, variable background signal, and high cosmic ray counts. Our user-friendly pipeline is modular, with each stage initialized by human-readable configuration files designated with the .hustle extension. Designed to be operable with minimal prior coding experience, our one-stop shop for G280 data reduction tackles all of the G280's challenges for you, so you can focus on getting the most from your data.</p>
</div>

[Check it out on GitHub!](https://github.com/Exo-TiC/HUSTLE-tools)

[Read the JOSS paper!]()

**Papers that have used HUSTLE-tools, Hazelnut, and/or lluvia:**
* [Boehm, V. A. et al. (2024). &quot;The HUSTLE Program: The UV to Near-infrared HST WFC3/UVIS G280 Transmission Spectrum of WASP-127b.&quot; <i>The Astronomical Journal</i>. 169(23).](https://iopscience.iop.org/article/10.3847/1538-3881/ad8dde/pdf)
* [Gasc&oacute;n, C. et al. (accepted). &quot;The HUSTLE Program: The UV to Near-IR Transmission Spectrum of the Hot Jupiter KELT-7b.&quot; <i>The Astronomical Journal</i>.]()

Juniper [v0.1]
------
![Logo coming soon!](/images/logo-juniper.png)

<div style="text-align: justify; text-justify: inter-word;">
  <p>Juniper is an in-development pipeline for reducing JWST spectroscopic time series observations. It currently supports NIRSpec observations of transiting and eclipsing exoplanets. The full-release build of Juniper will also support MIRI and NIRCam DHS time series observations, as well as phase curve fitting. Juniper is a modular pipeline divided into six stages. Each stage is initialized with a human-readable configuration file designated with the .berry extension, ensuring results are reproducible and easily shared with colleagues. Juniper aims to be user-friendly and executable with minimal coding background required.</p>
</div>

[Check it out on GitHub!](https://github.com/AbbyBoehm/Juniper)

[JOSS paper TBA!]()

**Papers that have used Juniper:**
* [MacDonald, R. et al. (accepted). &quot;Aerosols and Hydrocarbons in the Atmosphere of a White Dwarf Planet.&quot; <i>Nature</i>.]()