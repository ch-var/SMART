SMART
=====

**SMART** (**Spectral energy distributions Markov chain Analysis with Radiative Transfer models**) is a publicly available open-source spectral energy distribution (SED) fitting code. Implementing a Bayesian Markov chain Monte Carlo (MCMC) method, **SMART** fits the ultraviolet to millimetre SEDs of galaxies exclusively with radiative transfer models that currently constitute four types of pre-computed libraries, which describe the starburst, active galactic nucleus (AGN), host galaxy and polar dust components. **SMART** promises to be a useful tool for studying galaxy evolution in the James Webb Space Telescope (JWST) era.


Documentation
=============

To learn how to run **SMART** and for a helpful user guide, please read the manual [here](https://github.com/ch-var/SMART/commit/f8f7c03e5e77572f480abdd37f277920fe42b5c0).


Having issues?
=============

If you are experiencing problems using **SMART**, do not hesitate to write a mail at varnava.haris@gmail.com. 


Attribution
=============

If you find this tool useful in your research, please cite `Varnava & Efstathiou (2024)
<[https://arxiv.org/abs/1202.3665](https://academic.oup.com/mnras/advance-article/doi/10.1093/mnras/stae1141/7660585)>`_ if you find this code useful in your
research. The BibTeX entry for the paper is::

<https://arxiv.org/abs/1202.3665>`_ if you find this code useful in your
research. The BibTeX entry for the paper is::

  @article{10.1093/mnras/stae1141,
      author = {Varnava, Charalambia and Efstathiou, Andreas},
      title = "{SMART: Spectral energy distributions Markov chain Analysis with Radiative Transfer models}",
      journal = {Monthly Notices of the Royal Astronomical Society},
      pages = {stae1141},
      year = {2024},
      month = {04},
      abstract = "{In this paper we present the publicly available open-source spectral energy distribution (SED) fitting code SMART (Spectral energy distributions Markov chain Analysis with Radiative Transfer models). Implementing a Bayesian Markov chain Monte Carlo (MCMC) method, SMART fits the ultraviolet to millimetre SEDs of galaxies exclusively with radiative transfer models that currently constitute four types of pre-computed libraries, which describe the starburst, active galactic nucleus (AGN) torus, host galaxy and polar dust components. An important novelty of SMART is that, although it fits SEDs exclusively with radiative transfer models, it takes comparable time to popular energy balance methods to run. Here we describe the key features of SMART and test it by fitting the multi-wavelength SEDs of the 42 local ultraluminous infrared galaxies (ULIRGs) that constitute the HERschel Ultraluminous Infrared Galaxy Survey (HERUS) sample. The Spitzer spectroscopy data of the HERUS ULIRGs are included in the fitting at a spectral resolution, which is matched to that of the radiative transfer models. We also present other results that highlight the performance and versatility of SMART. SMART promises to be a useful tool for studying galaxy evolution in the James Webb Space Telescope (JWST) era. SMART is developed in Python and is available at https://github.com/ch-var/SMART.git.}",
      issn = {0035-8711},
      doi = {10.1093/mnras/stae1141},
      url = {https://doi.org/10.1093/mnras/stae1141},
      eprint = {https://academic.oup.com/mnras/advance-article-pdf/doi/10.1093/mnras/stae1141/57364876/stae1141.pdf},
}
    }


License
=======

Copyright 2024 Charalambia Varnava and contributors

**SMART** is a free tool made available under the MIT License. For details see the LICENSE file.
