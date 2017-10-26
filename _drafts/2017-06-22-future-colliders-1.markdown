---
author: shomiller
comments: true
date: 2017-06-22 15:00:19+00:00
layout: post
slug: future-colliders-1
title: Future Colliders for Particle Physics Megapost, Pt. 1
tags:
- Particle Physics
- Collider Physics
- LHC
- Future Colliders
---

If you look through all my previous posts on physics topics so far, you'd be forgiven for believing that I work exclusively on dark matter. While I do work with dark matter sometimes and think it's one of the most promising avenues in particle physics in the coming years, most of my work thus far has actually been on particle physics at colliders. In that spirit, I thought it was about time I dedicated a post to one of the most debated questions in particle physics these days: what's coming after the LHC?

First, we should note that the LHC is nowhere near done doing physics. We are only halfway through Run 2, and it still has not reached it's design peak energy at 14 TeV. In the timeline below, you can see the integrated luminosity -- a measure of how much collision data has been taken thus far -- is around 100 fb^-1. By the end of Run 3 in the early 2020s, the integrated luminosity will be at three times this number, and that's still just getting started. One of the major long-term plans is an upgrade to the so-called High Luminosity LHC (or just HL-LHC). With these upgrades, the number of protons collided at once will be drastically increased and the detectors will be taking data at over five times the rate they are now. The final target for the LHC is to reach 3000 fb^-1 integrated luminosity -- we're not even a tenth of the way there!

<img style="float: center;" width="650" src="{{ site.baseurl }}/assets/lhc_timeline.png" alt="LHC Timeline">
*"Timeline of upgrades and data taking for the HL-LHC beyond 2015  [ATLAS Phase-II Upgrade Scoping Document](http://cds.cern.ch/record/2055248)"*

So why are future colliders such a hot topic in physics these days? There are a lot of somewhat sociological reasons -- while the LHC still has a lot of data left to take, in the years since the discovery of the Higgs boson it's become increasingly likely that there are no new particles or forces that are going to be discovered at the LHC. This is by no means a failure -- discovering and studying the mechanism of electroweak symmetry breaking was the design goal of the LHC and it has succeeded and will continue to give us a better understanding of properties of the Higgs -- but there's certainly a bit of disappointment in the field. This leads somewhat naturally to start considering higher energies or alternatives to discover beyond the standard model physics.

But there's also a practical reason for all the hype about future colliders: a collider with the size/energy of those being proposed is inherently extremely difficult to build, and requires years of planning, research, and development. Having a new collider functioning in the 2030's requires planning that's already a decade underway (For comparison, [preparations for the LHC began in the 1980's](https://timeline.web.cern.ch/timelines/The-Large-Hadron-Collider), and that was with a great deal of infrastructure already in place from LEP.)

### Hadron Colliders vs. Lepton Colliders

There are essentially two options for the next particle collider: A hadron collider, like the LHC, which collides protons with other protons, or a lepton collider (such as LEP, the precursor to the LHC), which collides electrons and positrons. A full review of the physics in particle colliders is far more than I can fit in a single blog post (see, for example, [Tao Han's lectures](https://arxiv.org/abs/hep-ph/0508097) for an advanced introduction), but I'll try to sketch the basic advantages and disadvantages of each briefly before discussing actual plans for future colliders. Of course, there are other options for colliders too: one could collide electrons and protons (as was done in the classic deep inelastic scattering experiments), or even muon and anti-muon pairs (there is some talk of doing this well in the future at FermiLab), but I'll focus on the more common options for now.

Electron-Positron colliders are particularly useful because they are clean -- both the electron and positron (as far as we know) have no constituents, and because they have exactly opposite quantum numbers, almost any new particle can be created in the collision. Their interactions are also extremely well understood in the standard model, limiting theoretical uncertainties. Finally, it's relatively easy to alter the polarizations of the two incoming beams to search for more exotic couplings.s

The drawback to lepton colliders is that it's more difficult to achieve very high energies. To get to high energies, colliders often cycle beams of particles through circular paths using large magnets. However, charged particles moving in circles lose energy through synchrotron radiation at a rate inversely proportional to the fourth power of the particle's mass. Since electrons and positrons are extremely light (about 1/2000 times the mass of the proton), they lose energy in synchrotron radiation much faster than proton beams. Synchrotron radiation is inversely proportional to the radius, so achieving high energies in lepton colliders involves extremely large colliders (such as the LEP tunnel now used for the LHC). Because of this, lepton colliders are often linear colliders, where the beams are accelerated towards each other along a long straight path, and the limitation is instead on how quickly they can be accelerated and how long the collider can be.

For hadron colliders, the problem of synchrotron radiation is less severe, so circular colliders can be effectively used to cycle the beams many times and achieve extremely high energies. Protons are also composite objects, built out of quarks and gluons held together by the strong force. This has lots of advantages: the interactions of the strong force lead to much higher cross sections for proton-proton colliders than their electron-positron counterparts, and the diversity of constituents inside the proton allows us to study a lot of different processes at once.

However, because the proton is composite, the energy and momentum of the proton is actually carried by all the different constituents. As such, while we can achieve high energies with our proton beams, the fundamental particles participating in the interactions are only carrying a fraction of that energy. The energy they're carrying is also not specified by the beam, so it's difficult to tune the interactions to occur at a specific energy as can be done with lepton colliders. Finally, the strong interactions involve processes that can't be calculated to arbitrary accuracy by hand and theoretically we're forced to rely on numerical methods. This leads to larger theoretical uncertainties and comparison with data is not quite as clean as for pure QED interactions.

Hopefully I've explained why there are several viable possibilities for future colliders. In my next post, I'll dive into some of the specific plans for the next generation of particle colliders at CERN, in Japan, and in China.
