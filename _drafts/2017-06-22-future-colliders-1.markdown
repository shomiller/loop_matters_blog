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

Electron-Positron colliders are particularly useful because they are clean -- both the electron and positron (as far as we know) have no constituents, and because they have exactly opposite quantum numbers, almost any new particle can be created in the collision. Their interactions are also extremely well understood in the standard model, limiting theoretical uncertainties. Finally, it's relatively easy to alter the polarizations of the two incoming beams to search for more exotic couplings.

The drawback to lepton colliders is that it's more difficult to achieve very high energies. To get to high energies, colliders often cycle beams of particles through circular paths using large magnets. However, charged particles moving in circles lose energy through synchrotron radiation at a rate inversely proportional to the fourth power of the particle's mass. Since electrons and positrons are extremely light (about 1/2000 times the mass of the proton), they lose energy in synchrotron radiation much faster than proton beams. Synchrotron radiation is inversely proportional to the radius, so achieving high energies in lepton colliders involves extremely large colliders (such as the LEP tunnel now used for the LHC). Because of this, lepton colliders are often linear colliders, where the beams are accelerated towards each other along a long straight path, and the limitation is instead on how quickly they can be accelerated and how long the collider can be.

For hadron colliders, the problem of synchrotron radiation is less severe, so circular colliders can be effectively used to cycle the beams many times and achieve extremely high energies. Protons are also composite objects, built out of quarks and gluons held together by the strong force. This has lots of advantages: the interactions of the strong force lead to much higher cross sections for proton-proton colliders than their electron-positron counterparts, and the diversity of constituents inside the proton allows us to study a lot of different processes at once.

However, because the proton is composite, the energy and momentum of the proton is actually carried by all the different constituents. As such, while we can achieve high energies with our proton beams, the fundamental particles participating in the interactions are only carrying a fraction of that energy. The energy they're carrying is also not specified by the beam, so it's difficult to tune the interactions to occur at a specific energy as can be done with lepton colliders. Finally, the strong interactions involve processes that can't be calculated to arbitrary accuracy by hand and theoretically we're forced to rely on numerical methods. This leads to larger theoretical uncertainties and comparison with data is not quite as clean as for pure QED interactions.

### Prospects for Future Colliders

There are a variety of different plans underway for future colliders, but they can be roughly broken down into two long-term design plans. The first is the construction of a new linear collider to collide electrons and positrons. The second, longer term plan, is to construct a new circular collider tunnel that would first collide electrons and positrons (similar to LEP, but at higher energies), then eventually be upgraded to a hadron collider like the LHC. There are also several different possible sites for these future colliders -- which will actually be built is essentially up to politics and funding abilities, but it's likely that one of each of the aforementioned designs will be pursued eventually.

**At CERN:**

As a lot of the infrastructure and expertise is already in place, CERN is a natural site to consider for future colliders. The linear collider working group there takes the name of the Compact Linear Collider (or CLIC), which hopes to achieve center of mass energies ranging from 500 GeV to 3 TeV. While this is much lower than the current reach of the LHC (13 TeV), it will enable much more detailed study of the Higgs boson because of the clean environment of lepton collisions. Reaching up to 3 TeV would also enable direct production of particles with masses far above the current bounds set by the LHC, where statistics play a much larger role.

At the same time, CERN is also studying the prospects for a Future Circular Collider (FCC), which would require a new ~80 km long tunnel at CERN. The ultimate goal of such a project would be a 100 TeV proton-proton collider (FCC-hh), which would directly probe the highest energies ever, as well as provide enough energy and luminosity to precisely study parameters such as the Higgs self-coupling (MUCH more on this later!). As an intermediate step, the accelerator could be used as a electron-positron collider (FCC-ee) similar to LEP, that would explore energies from 90 to 350 GeV -- high enough to study the Higgs boson decay modes with precision (a so-called "Higgs factory"). There's also an option for an FCC-he, which would collide electrons and protons.

Finally, I can’t help but mention one possibility that I’m personally involved in – the “High Energy” (or “HE”) LHC. The idea in this case is to use the dipole magnets already being developed for FCC studies in the current LHC tunnel instead, nearly doubling the energy achievable with the LHC to about 27 TeV. The upshot of this is that simply replacing the magnets that accelerate particles is substantially cheaper than an entirely new project, and could even conceivably be done in the next 15-20 years. The 27 TeV run would likely replace a significant portion of the planned run for HL-LHC, and would give us a significant amount of data at a much higher energy, where the prospects for discovering new physics may be much improved. This idea is still in its infancy though, and work is just now beginning to understand in detail the benefits of going to higher energy and what the prospects are for the current detectors at the LHC of taking data at these energies.

<img style="float: center;" height="500" src="{{ site.baseurl }}/assets/FCC_schematic.png" alt="FCC Schematic"><br>
*"Schematic of an 80-100 km long tunnel at CERN that would be used for the FCC. [Courtesy: CERN](http://home.cern/about/accelerators/future-circular-collider)"*

**The ILC:**

Note more recent prospects at 250 GeV? (and note the history over the last 10-20 years…)


**In China:**

One intriguing and exciting development in the planning for future colliders is the possibility that China might enter the game in the near future. Similar to the FCC designs at CERN, there are lots of plans for a ~54 km ring, somewhat smaller than the FCC design, that would be built outside Beijing. The collider would consist of the Circular Electron Positron Collider (CEPC), a dedicated Higgs factory which would operate at ~240 GeV, as well as a hadron collider -- the Super Proton-Proton Collider, or SPPC, which would reach energies around 70-80 TeV.

One of the reasons this prospect is so exciting is because it would open the door to China becoming one of the biggest players on the world stage in fundamental physics. While there are a number of extremely influential Chinese physicists in the field (including the namesake of my institute, C. N. Yang), the majority of them have spent a great deal of their career at institutions outside of China. In the past decade though, China has made a concerted effort to enter the stage in particle physics, with several successful experiments such as the Daya Bay, which has produced several important results in neutrino physics. Being home to the largest collider on the planet though, would be a much more significant step.

For these and other reasons, the Chinese collider project has become extremely controversial, with several notable physicists such as Nima Arkani-Hamed and David Gross actively campaigning for the project to happen, and others, including C. N. Yang himself, arguing against the project. Some of this debate was made public earlier this year, when Yang and Gross published their opinions in an editorial form. If you’re interested, you can read [Yang’s original article](http://www.worldscientific.com/doi/abs/10.1142/S0217751X16300532) here, and [Gross’s response here](http://www.worldscientific.com/doi/abs/10.1142/S0217751X16300544). Peter Woit also highlighted some aspects of the debate [on his blog](https://www.math.columbia.edu/~woit/wordpress/?p=8949). Regardless of what happens with the CEPC and SPPC, the emergence of China in particle physics will undoubtedly be a big factor for the future of particle physics.

https://cds.cern.ch/record/2110739/files/CERN-ACC-2015-165.pdf

Future Colliders:
- ILC (Japan?)
- at CERN: CLIC, FCC-ee, FCC-hh, HE-LHC
- in China: SppC (and the ee version?)
