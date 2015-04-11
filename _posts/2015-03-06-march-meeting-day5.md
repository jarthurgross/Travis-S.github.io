---
layout: default
title: APS March Meeting - Day 5
subtitle: Wrapping Up
date: 2015-03-06
author: Travis Scholten
---
Today was the last day of the March meeting. Given that I had to catch a plane later that evening, I only listened to some talks.

Given my interest in understanding how to do computational physics, 

* Automatic FLOW for Materials Discovery - Marco Fornari

materials design can be a difficult computational task
4 things - volume, velocity, variety, veracity
it is possible to use computational tools (AFLOW, VASP/QE) to generate
a materials database (AFLOWLIB consortium)
Utilizes DFT calculations for 650K compaounds.
interfaces with UNIX, SQL databases
AFLOWLIB utilizes python standard library, numpy, scipy, matplotlib
results in medium throughput 
one bottleneck is actually computing materials properties with DFT
suggests need for new DFT approaches - Phys Rev X paper

* Magnetic Genome Project - Stefano Sanvito

we need new magnetic materials  - need to find novel rare-earth free magnetic materials
(rare earths are expensive!)
for instance, data storage industry needs magnetic materials for hard drives
not too many magnetic materials have high enough T_{c} (temp @ which magnetic ordering is preserved?)
idea: magnetic genome project 
use code to compute magnetic properties and look for new materials


* Distributed databases for materials study of thermo-kinetic properties   - Cormac Toher

understanding thermal properties of materials has applications for termoelectrics, heat sinks, etc.
numerical techniques for this include the GIBBS library
what the hell is VASP, quantum espresso?
the main take-away here - these people have figured out a way to do autmated workflow for materials
discovery. from raw user input parameters, we generate input files to DFT calculations,
then run algorithms to do those calculations, and then plot quantities and provide
outputs

