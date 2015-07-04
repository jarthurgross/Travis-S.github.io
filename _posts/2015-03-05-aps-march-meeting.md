---
layout: talk
title: Applying Model Selection to Quantum State Tomography - Choosing Hilbert Space Dimension
date: 2015-03-05
location: San Antonio, Texas
type: talk
---

#Description#
This talk was presented for the 2015 American Physical Society's annual March meeting. 

#Abstract#
Reconstructing the quantum state of a continuous variable system (e.g., an optical mode) using quantum tomography presents a unique problem:  the dimension of its Hilbert space is infinite.  Its density matrix has infinitely many parameters, which cannot all be estimated from finite data.  Brute force reconstruction (e.g., via the Radon transform or deconvolution) produces undesirable overfitting artifacts.  Smoothing is one solution, but has no good theoretical justification. 

I introduce a statistically well-motivated approach based on model selection and log likelihoods.  Maximum likelihood estimates in a sequence of D-dimensional subspaces (spanned by the first D Fock states) are ranked by their log likelihood. This ranking allows one to find an estimate whose dimension is smaller while simultaneously providing a good fit to data. I apply this method to heterodyne tomography and demonstrate the method can indeed eliminate overfitting by choosing a good dimension (D) in which to reconstruct optical states. 

#Slide Deck#
<script async class="speakerdeck-embed" data-id="bb9e3de3d4994f8e813ddec649e3aaf2" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>

#Screencast#
<iframe width="560" height="315" src="https://www.youtube.com/embed/_31FztfVyZA" frameborder="0" allowfullscreen></iframe>