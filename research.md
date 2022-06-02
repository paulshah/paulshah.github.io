---
layout: page
title : Current Research
image: 
  path: /assets/img/Hubble_UDF_1.png
description: >
  Tracing dark matter by gravitational lensing 
sitemap: false
---

## Weak lensing of Type Ia Supernovae

The gravitational potential of a foreground galaxy or cluster bends light and changes the shape of a 
background image (known 
as [shear](https://en.wikipedia.org/wiki/Weak_gravitational_lensing)) in exactly the same way a lens does. 
The image is also magnified, however since the effect is usually small and we don't 
know how luminous the background galaxy would have been without the lens, it's hard to make use of this. 

We do know the luminosities of Type Ia supernovae to within about 0.1 magnitudes. They are also bright enough to be 
seen at distances where lensing could have a measurable effect. However, the probability distribution of lensing is very 
skewed, and there are many more SN Ia that are slightly dimmer (because their lines of sight do not pass close to foreground 
galaxies) than those that are brighter. Although the [Pantheon](https://arxiv.org/pdf/1710.00845.pdf) 
sample comprises 1,048 SN Ia, detecting lensing remains challenging.  
 
## Detecting weak lensing magnification
We use the Pantheon catalog in combination with photometric galaxy data from 
[SDSS](http://skyserver.sdss.org/dr16/en/tools/chart/navi.aspx), to build a model estimator for the amount of weak lensing of 
a given SN Ia. Our model has two free parameters : the mass-to-light ratio of the dark matter halo and the radial slope of the 
density profile. We find this estimator correlates with the residuals of the SN Ia to a Hubble diagram fit at a significance 
of 3.6$$\sigma$$, showing that it is robust. We also derive Bayesian posteriors for the mass-to-light ratio and 
radial slope. We find that the [NFW](https://arxiv.org/pdf/astro-ph/9611107.pdf) profile is consistent with the data, and the 
mass-to-light ratio suggests $$\sim 0.5$$ of the dark matter in the Universe is bound to galactic haloes.

<img src="/assets/img/Mag_scatter.png" width="650">

The estimated magnification of SN Ia in Pantheon is plotted on the x-axis, and their Hubble diagram residuals on the y-axis. 
The axes have been roughly normalised to units of standard deviation. The effect of lensing is seen as the grouping of points 
in the top right and bottom left quadrants. 
{:.figcaption}

The scatter of weak lensing is found to be $$\sim 0.06$$ magnitudes at redshift $$z=1$$, and proportional to $$d^{3/2}$$ where 
$$d$$ is the comoving distance to the source. 

<img src="/assets/img/std_mag.png" width="600">

The scatter in SN Ia magnitudes increases with distance.
{:.figcaption}

## Cosmology in an inhomogeneous universe
Cosmologists rely on model distance formulae derived under the assumption of 
homogeneity and isotropy. But we live in a clumpy universe : how valid are those formulae? Our model, having been 
calibrated using galaxy and SN Ia photometric data, can now be used to calculate a distance correction on any 
given line of sight. It is not the full answer, as we do not allow for obscuration or strong 
lensing, but it means we can de-lens luminosity distances and recalculate cosmological parameters. We find that although 
Pantheon shows a bias towards over-dense lines of sight at moderate significance, this only lowers the matter density 
$$\Omega_m$$ by 0.5%. 

<img src="/assets/img/KStest2_side.png" width="650">

The lensing magnification of Pantheon SN Ia in a mid redshift bucket is consistent with a random line of sight, however a 
deeper bucket shows here Pantheon has a bias to over-dense lines of sight.
{:.figcaption}

## Papers
[The weak lensing magnification of Type Ia supernovae](https://arxiv.org/pdf/2203.09865.pdf) P.Shah, P.Lemos and 
O. Lahav

[Correcting Type Ia supernova luminosity distances for weak lensing](https://tbc) In Prep, P.Shah, P.Lemos and O.Lahav

## Hubble Constant

There are as many opinions on the Hubble constant as there are ways to calculate it! Two sets of results that are much discussed are 
from the SHOeS team (who use geometrical distances to calibrate Cepheid magnitudes, and Cepheids to calibrate Type Ia supernovae), and from the 
Planck team (who use the power spectrum of the CMB plus the assumption that the universe is $$\Lambda$$CDM). These two results tempt the 
explanation that it is an "early" vs "late" tension, and perhaps a solution can be found in modifying the expansion history away from 
$$\Lambda$$CDM by some novel physics. However, this is to discount local distances from TRGBs that are inconsistent with Cepheids (although this 
is disputed by some authors), plus data from galaxy surveys which when combined with a density constraint from BBN is consistent with CMB results. 
Additionally, the Planck results have a peculiar internal inconsistency dubbed $$A_{\rm lens}$$, although the significance of this is unclear.  

Our review of this topic had three aims. Firstly, we aim to provide a pedagogical introduction to the results. Our paper 
should be accessible to undergraduates, while at the same time providing enough detail on systematics to satisfy the more experienced reader.
Secondly, our aim was to provide an impartial (and perhaps imperfect!) opinion as to the historical and future development of most of the main 
probes of $$H_0$$. Thirdly, for astronomers in a hurry, we make recommendations about what value to use. 

<img src="/assets/img/H0_heatmap3.pdf" width="600">

[A buyer's guide to the Hubble constant](https://arxiv.org/pdf/2109.01161.pdf) P.Shah, P. Lemos and O. Lahav, A&A Review, Vol 29, Issue 1, Dec 2021

Continue with [Publications](/publications/){:.heading.flip-title}
{:.read-more}
