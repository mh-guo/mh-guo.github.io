---
permalink: /
title: "Welcome!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Minghao Guo (郭明浩), currently a graduate student at the <a href="https://web.astro.princeton.edu/">Department of Astrophysical Sciences, Princeton University</a>, supervised by Profs. [James Stone](https://www.ias.edu/scholars/stone) and [Eliot Quataert](https://www.astro.princeton.edu/~quataert/). I am also a visiting graduate student at the [Institute for Advanced Study](https://www.ias.edu) and a member of the [Learning the Universe (LtU) collaboration](https://learning-the-universe.org). I was an undergraduate at <a href="https://www.pku.edu.cn/">Peking Unversity</a>.

My current research focuses on multiscale multiphase modeling on the dynamics of accretion flows onto black holes across a vast range of spatial and temporal scales in (general relativistic) magnetohydrodynamic (GRMHD) simulations. Simply using GRMHD simulations that resolve horizon scales to compute the feedback from the event horizon to galactic scales is generally infeasible due to the very restrictive time step constraints. To tackle this problem, we develop a series of method to accelerate the GRMHD simulations by $$\gtrsim 10^5$$ times for problems with large scale separation and apply it to various problems that need to cover vast spatial and temporal scales.

I love sharing our wonderful universe to the public, and I give outreach talks at [Astronomy On Tap Trenton](https://astronomyontap.org) and teach astronomy in the [Prison Teaching Initiative](https://mcgraw.princeton.edu/community-college-engagement/prison-teaching-initiative). Outside academia, I like the nature in general (climbing, hiking, swimming, gardening, etc).

Last updated July, 2025.

[Find my CV here](https://mh-guo.github.io/CV_Minghao_Guo.pdf)
======

Publications
======
Check out the full list at [ADS](https://ui.adsabs.harvard.edu/search/filter_database_fq_database=AND&filter_database_fq_database=database%3A%22astronomy%22&fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq_database=(database%3A%22astronomy%22)&p_=0&q=%3Dauthor%3A%22Guo%2C%20Minghao%22&sort=date%20desc%2C%20bibcode%20desc) and [Google Scholar]({{site.author.googlescholar}}). Below are selected works:

1. **Minghao Guo**, James M. Stone, Eliot Quataert, and Volker Springel, Cyclic Zoom: Multiscale GRMHD Modeling of Black Hole Accretion and Feedback, [ApJ 987, 202 (2025)](https://iopscience.iop.org/article/10.3847/1538-4357/add1da), [arXiv:2504.16802 [astro-ph.HE]](https://arxiv.org/abs/2504.16802) .

1. **Minghao Guo**, Eliot Quataert, Jonathan Squire, Philip F. Hopkins, and James M. Stone, Idealized Global Models of Accretion Disks with Strong Toroidal Magnetic Fields, [arXiv:2505.12671 [astro-ph.HE]](https://arxiv.org/abs/2505.12671) .

1. **Minghao Guo**, Chang-Goo Kim, and James M. Stone, Evolution of Supernova Remnants in a Cloudy Multiphase Interstellar Medium, [arXiv:2411.12809 [astro-ph.GA]](https://arxiv.org/abs/2411.12809).

1. **Minghao Guo**, James M. Stone, Eliot Quataert, and Chang-Goo Kim, Magnetized Accretion onto and Feedback from Supermassive Black Holes in Elliptical Galaxies, [ApJ 973, 141 (2024)](https://iopscience.iop.org/article/10.3847/1538-4357/ad5fe7), [arXiv:2405.11711 [astro-ph.HE]](https://arxiv.org/abs/2405.11711) .

1. **Minghao Guo**, James M. Stone, Chang-Goo Kim, and Eliot Quataert, Toward Horizon-scale Accretion onto Supermassive Black Holes in Elliptical Galaxies, [ApJ 946, 26 (2023)](https://iopscience.iop.org/article/10.3847/1538-4357/acb81e), [arXiv:2211.05131 [astro-ph.HE]](https://arxiv.org/abs/2211.05131) .

1. **Minghao Guo**, Junjie Zhao, and Lijing Shao, Extended reduced-order surrogate models for scalar-tensor gravity in the strong field and applications to binary pulsars and gravitational waves, [PhRvD 104, 104065(2021)](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.104.104065), [arXiv:2106.01622 [gr-qc]](https://arxiv.org/abs/2106.01622) .

1. **Minghao Guo**, Kohei Inayoshi, Tomonari Michiyama, and Luis C. Ho, Hunting for Wandering MassiveBlack Holes, [ApJ 901, 39 (2020)](https://iopscience.iop.org/article/10.3847/1538-4357/abacc1), [arXiv:2006.08203 [astro-ph.HE]](https://arxiv.org/abs/2006.08203) .

1. **Minghao Guo**, Min Du, Luis C. Ho, Victor P. Debattista, and Dongyao Zhao, A New Channel of BulgeFormation via the Destruction of Short Bars, [ApJ 888, 65 (2020)](https://iopscience.iop.org/article/10.3847/1538-4357/ab584a), [arXiv:1911.07002 [astro-ph.GA]](https://arxiv.org/abs/1911.07002) .


Research
======

I am widely interested in theoretical, numerical, and observational astrophysics. I major in physics with particular interest in astrophysics and broad background in mathematics and computer science. I am interested in a variety of intriguing topics in astronomy and astrophysics, especially black hole astrophysics, galaxy formation, cosmology, gravitational wave and gravity test. I generally use numerical techniques and tools ([AthenaK](https://github.com/IAS-Astrophysics/athenak)) to investigate the abundant phenomenon in various fields in astrophysics. I have experience on doing research involving theoretical, numerical and observational astrophysics, e.g., coevolution between supermassive black holes and host galaxies, black hole accretions as well as modified gravity and the application onto neutron stars.

My research interests include:
- Black holes, high energy astrophysics, accretion disk, general relativistic magnetohydrodynamics (GRMHD)
- Active galactic nuclei (AGN), galaxy formation and evolution, multiphase interstellar medium (ISM)
- Numerical methods and simulations, GPU computing, new numerical techniques
- Neutron stars, pulsars, gravitational waves, modified gravity theory

[Cyclic Zoom: Solving the multiscale problem]((https://iopscience.iop.org/article/10.3847/1538-4357/add1da))
------

![Cyclic Zoom](/images/fig_cyclic_zoom_method.png)

We present a "cyclic zoom" method to capture the dynamics of accretion flows onto black holes across a vast range of spatial and temporal scales in general relativistic magnetohydrodynamic (GRMHD) simulations. In this method, we cyclically zoom out (derefine) and zoom in (refine) the simulation domain while using a central mask region containing a careful treatment of the coarsened fluid variables to preserve the small-scale physics, particularly the magnetic field dynamics. The method can accelerate GRMHD simulations by $$\gtrsim 10^5$$ times for problems with large scale separation. We demonstrate the validity of the technique using a series of tests, including spherically symmetric Bondi accretion, the Blandford-Znajek monopole, magnetized turbulent Bondi accretion, accretion of a magnetized rotating torus, and the long-term evolution of an accreting torus about both Schwarzschild and Kerr black holes. As applications, we simulate Bondi and rotating torus accretion onto black holes from galactic scales, covering an extremely large dynamic range. In Bondi accretion, the accretion rate is suppressed relative to the Bondi rate by $$\sim(10r_\mathrm{g}/r_\mathrm{B})^{1/2}$$ with a feedback power of $$\sim 0.01 \dot{M} c^2$$ for vanishing spin, and $$\sim 0.1 \dot{M} c^2$$ for spin $$a\approx0.9$$. In the long-term evolution of a rotating torus, the accretion rate decreases with time as $$\dot{M}\propto t^{-2}$$ on timescales much longer than the viscous timescale, demonstrating that our method can capture not only quasi-steady problems but also secular evolution. Our new method likewise holds significant promise for applications to many other problems that need to cover vast spatial and temporal scales.

[Zoom-in simulations of black hole accretion and feedback](https://iopscience.iop.org/article/10.3847/1538-4357/ad5fe7)
------

<figure>
  <video autoplay muted loop playsinline controls style="width: 100%; height: auto;">
    <source src="https://mh-guo.github.io/videos/amh_proj_all_small.mp4" type="video/mp4">
  </video>
  <figcaption> Zoom-in MHD simulations of black hole accretion from galaxy down to event horizon.</figcaption>
</figure>

We use a series of zoom-in MHD simulations that cover the entire range from galaxy formation down to the event horizon of black holes. We model the fueling of supermassive black holes in elliptical galaxies from a turbulent medium on galactic scales, taking M87* as a typical case. The simulations use AthenaK, a new GPU-accelerated version of the Athena++ AMR code. The key physical ingredients are magnetic field, radiative cooling and a phenomenological heating model. In this way, we can model the accretion onto supermassive black holes using realistic initial conditions, which aims to study the coevolution between supermassive black holes and their host galaxies. The scaling of $$\dot{M} \sim r^{1/2}$$ roughly holds from $$\sim 10\,\mathrm{pc}$$ to $$\sim 10^{-3}\,\mathrm{pc}$$ ($$\sim 10\, r_\mathrm{g}$$) with the accretion rate through the event horizon being $$\sim 10^{-2}\, M_\odot\,\mathrm{yr^{-1}}$$. The accretion flow on scales $$\sim 0.03-3\,\mathrm{kpc}$$ takes the form of magnetized filaments. Within $$\sim 30\,\mathrm{pc}$$, the cold gas circularizes, forming a highly magnetized ($$\beta\sim 10^{-3}$$) thick disk supported by a primarily toroidal magnetic field. The cold disk is truncated and transitions to a turbulent hot accretion flow at $$\sim0.3\,\mathrm{pc}$$ ($$10^3\,r_\mathrm{g}$$). There are strong outflows towards the poles driven by the magnetic field. The outflow energy flux increases with smaller accretor size, reaching $$\sim 3\times10^{43}\,\mathrm{erg\,s^{-1}}$$ for $$r_\mathrm{in}=8\,r_\mathrm{g}$$; this corresponds to a nearly constant energy feedback efficiency of $$\eta\sim0.05-0.1$$ independent of accretor size. The feedback energy is enough to balance the total cooling of the M87/Virgo hot halo out to $$\sim 50$$ kpc. The accreted magnetic flux at small radii is similar to that in magnetically arrested disk models, consistent with the formation of a powerful jet on horizon scales in M87. Our results motivate a subgrid model for accretion in lower-resolution simulations in which the hot gas accretion rate is suppressed relative to the Bondi rate by $$\sim (10r_\mathrm{g}/r_\mathrm{B})^{1/2}$$.

See below for a video of the hydrodynamic case.

<figure>
  <video autoplay muted loop playsinline controls style="width: 100%; height: auto;">
    <source src="https://mh-guo.github.io/videos/Acc_video_render_zoom.mp4" type="video/mp4">
  </video>
  <figcaption> Zoom-in hydrodynamic simulations of black hole accretion from galactic scales.</figcaption>
</figure>

 We find that the accretion flow takes the form of multiphase gas at radii less than about a kpc. The cold gas accretion includes two dynamically distinct stages: the typical disk stage in which the cold gas resides in a rotationally supported disk and relatively rare chaotic stages ($$ \lesssim 10\% $$ of the time) in which the cold gas inflows via chaotic streams. Though cold gas accretion dominates the time-averaged accretion rate at intermediate radii, accretion at the smallest radii is dominated by hot virialized gas at most times.

Supernova remnant in a cloudy multiphase interstellar medium
------

![Supernova remnant](/images/fig_snr_render_cut.png)

We investigate the evolution of supernova remnants (SNRs) in a two-phase cloudy medium by performing a series of high-resolution (up to $$\Delta x\approx0.01\,\mathrm{pc}$$), 3D hydrodynamical simulations including radiative cooling and thermal conduction. We aim to reach a resolution that directly captures the shock-cloud interactions for the majority of the clouds initialized by the saturation of thermal instability. In comparison to the SNR in a uniform medium with the volume filling warm medium, the SNR expands similarly (following $$\propto t^{2/5}$$) but sweeps up more mass as the cold clouds contribute before shocks in the warm medium become radiative. However, the SNR in a cloudy medium continuously loses energy after shocks toward the cold clouds cool, resulting in less hot gas mass, thermal energy, and terminal momentum. Thermal conduction has little effect on the dynamics of the SNR but smooths the morphology and modifies the internal structure by increasing the density of hot gas by a factor of $$\sim 3-5$$. The simulation results are not fully consistent with many previous 1D models describing the SNR in a cloudy medium including a mass loading term. By direct measurement in the simulations, we find that, apart from the mass source, the energy sink is also important with a spatially flat cooling rate $$\dot{e}\propto t^{-11/5}$$. As an illustration, we show an example 1D model including both mass source and energy sink terms (in addition to the radiative cooling in the volume filling component) that better describes the structure of the simulated SNR.

Can one stand before the void, embraced by nature, and not ask why?
------
![Physics](/images/header_image_wallhaven.jpg)
