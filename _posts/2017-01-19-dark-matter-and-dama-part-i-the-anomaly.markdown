---
author: shomiller
comments: true
date: 2017-01-19 02:13:41+00:00
layout: post
permalink: dark-matter-and-dama-part-i-the-anomaly
title: 'Dark Matter and DAMA, Part I: The anomaly'
tags:
- Dark Matter
- Particle Physics
---

As the new year begins with no new tantalizing signals from the LHC, perhaps it's a good time to look back at an older experimental anomaly that has somehow survived with no satisfying explanation for almost two decades: the annual fluctuations in the DAMA experiment. As one might expect for an anomaly that's been around this long, there's a lot of material (and some controversy) to unpack here. In this posting I'm going to try and explain what DAMA set out to do and what they observed. Next time around, I'll try to dig into some of the controversies -- both scientific and political -- that have prevented a consensus interpretation of DAMA's results.


# Direct Detection of Dark Matter


DAMA is one of many so-called 'direct detection' experiments searching for dark matter in the local part of our galaxy. The basic premise is as follows: we have good cosmological reasons to believe that there is some type of massive particle permeating our galaxy, and in particular our solar system. These particles are massive, but their mass could be essentially anything, they must be electrically neutral (or else we'd have seen them), but they could in principle interact with ordinary matter through some much weaker force. Thus, these particles would whiz around in our solar system, constantly passing through us and everything around us similar to the way most neutrinos do. While we don't know exactly what type of particle could constitute the dark matter, we know that it can't be described by anything in the standard model, and while there are countless theoretical models that propose various candidates, none have any experimental evidence thus far.

But for now, let's suppose that the dark matter particles do have some very weak interaction with the electrons and protons we're accustomed to (the so-called "weakly interacting massive particle", or "WIMP" hypothesis). Then, if we take a big tank of ordinary matter and watch carefully, eventually a dark matter particle in the solar system will collide with some of the matter in our tank, causing the nucleus of the particle we're watching to recoil with some energy that we can in principle measure. This technique is what's called direct detection (to distinguish it from "indirect detection", which searches for two dark matter particles colliding and annihilating to produce standard model particles -- I'll talk more about this in a post to come!)


# DAMA's twist: Annual modulations


One of the most difficult things about the direct detection methods we've talked so far is how to eliminate background. Since the detection material is made of ordinary matter, it interacts ordinarily through radioactive sources and cosmic rays and it's not unexpected to see some signal in the detector even in the absence of dark matter. Most experiments deal with this by carefully shielding against and quantifying their backgrounds and/or discriminating them by some other means. The DAMA experiment takes a different approach.

The underlying idea behind DAMA is that the dark matter is distributed roughly randomly in a spherical shape throughout the galaxy, and thus since the ordinary matter in our galaxy is rotating, there is a sort of "wind" of dark matter particles passing through our solar system in one direction. Since the earth rotates around the sun roughly in this same plane, during parts of the year the earth's movement will be with this wind -- decreasing the flux of dark matter particles passing through the earth, while the other part of the year the earth's movement will be against the wind, correspondingly increasing the flux. In contrast, the usual radioactive and cosmic backgrounds in a detector have no reason to oscillate in such a way. Thus, a detector can bypass the need to distinguish between dark matter particles and backgrounds if they can see some sort of annual oscillation in their data: if the oscillation has a one year period and the right phase, it must be the dark matter!


# The Results:


DAMA set out to observe exactly this annual modulation, and to many in the community's surprise, it wasn't long before there was a clear oscillation in their data. The plot below shows the number of detection events per day as a function of time, with the constant part of the signal subtracted out. The solid line overlaid shows the fit to an ordinary sine-wave with a period of one year, and the phase fixed to peak when the earth is moving maximally against the rotation of the galaxy. You can [read the rest of the paper](http://link.springer.com/article/10.1140%2Fepjc%2Fs10052-010-1303-9) for more details and some of the other check's DAMA has done, but the data is quite clear: DAMA is observing something interacting with their detector that has exactly the annual fluctuations we expect from dark matter.

![DAMA/LIBRA Signal]({{ site.baseurl }}/assets/DAMA_signal.png "Oscillation observed by DAMA with recoil energies between 2-6 keV, adapted from [doi:10.1140/epjc/s10052-010-1303-9](http://link.springer.com/article/10.1140%2Fepjc%2Fs10052-010-1303-9)")

If you believe everything I've said so far, it's hard not to look at the plot above and believe that the dark matter question must be settled. It's not hard to take the amplitude of the graph above, combined with the energy of the nuclear recoils in the detector and the known density of dark matter in our galaxy that we can obtain from cosmology and extract information about the mass and interaction strength of the dark matter particle. In terms of the statistical confidence level used to describe the strength of a signal, DAMA's result shows a whopping 8.9σ detection, far surpassing the usual 5σ threshold to claim "discovery".

Given all this, it's somewhat surprising that the community by and large doesn't regard the DAMA result as evidence of dark matter detection.In my next post, I'll discuss why this is the case, and give a brief overview of how the story might be resolved in the coming years -- stay tuned!

References:
[1] Bernabei, R., Belli, P., Cappella, F. et al., "Final model independent result of DAMA/LIBRA-phase 1". Eur. Phys. J. C (2013) 73: 2648. doi:[10.1140/epjc/s10052-013-2648-7](http://link.springer.com/article/10.1140%2Fepjc%2Fs10052-013-2648-7).
