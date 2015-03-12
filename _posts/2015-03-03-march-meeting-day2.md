---
layout: default
title: APS March Meeting - Day 2
subtitle: 
date: 2015-03-03
author: Travis Scholten
---
Today was a good day to listen to more talks.  The March meeting has such a diverse range of topics that it is essentially very easy to find _something_ to listen to.

**Highlights**

Today's highlights include:

* Learning about the physics of traffic flow

> According to an (the?) Urban Mobility Report, the estimated cost of traffic jams in the US is roughly 121 billion dollars per year. (I assume this is calculated by looking at the lost economic opportunity/production when people are stuck in traffic.) Models of traffic flow are important for figuring out better ways to keep traffic flowing smoothly and quickly. A key way of thinking about traffic flow is to consider the various _phases_ the flow might take. For instance, the flow might be "free", just moving along at a good clip, or "synchronized", with waves of jams propagating, or "jammed", with traffic actually grinding to a halt.

> One of the main problems in traffic flow is the fact that people drive too close together and have finite reaction time. For instance, if a car ahead of me brakes, then if I tapped my brakes at exactly the same time, then we would slow down together, and there would be no disturbance in the flow. However, because it takes me a finite amount of time to respond, by the time I start braking, I need to brake _even more_ to compensate for the increased closeness between the vehicles. This pattern continues down the line of cars until, at some point, somebody has to essentially stop, and a traffic jam is formed.

> As a result, it is important to keep the distance between cars reasonably large as well as encourage drivers to be polite. Otherwise, when people try to optimize their own traffic flow without considering the global flow, jams invariably form.

> Another interesting problem comes with interchanges and on/off ramps. According to the analysis discussed in this talk, sometimes it might make more sense to impose lane restrictions between the ramps - and thereby prevent people from changing lanes - in order to facilitate the flow of traffic onto the main throughway. Additionally, using bypass lanes (essentially spurs from one place to another), as well as carpool lanes, can help smooth traffic flow.

* The Fermion-Sign Problem in Quantum Monte Carlo and a Solution using a Majorana Representation

> Quantum Monte Carlo (QMC) is a technique for calculating properties of quantum-mechanical systems. Although I did not follow the contents of the talk exactly, the intuition is that classical Monte Carlo techniques - which are, as far as I understand, ways of computing integrals and the like using a probabilistic analysis - can be brought to bear on solving quantum-mechanical problems, but with some caveats.

> One way do to QMC is through determinant QMC, which involves calculating a partition function. However, when the particles in that quantum system are fermions, you end up getting an exponential explosion in the number of terms in the partition function. This is because the fermionic wavefunction needs to be antisymmetric (you get a minus sign when you exchange any two particles). 

> According to the speaker, some of these problems can be mitigated by using the _Majorana representation_ for the fermions, which allows the Boltzmann probability weights to factorize in an easy way. Then, we can "trace over" (??) the Majorana fermions and avoid the [sign problem](http://en.wikipedia.org/wiki/Numerical_sign_problem).


* Quantum Monte Carlo Simulations of Bosons with Complex Interactions

> I will admit this talk was very confusing to me. In a demonstration of how sometimes what you get out of a talk is not necessarily what the speaker intended, I learned that you can detect the onset of superfluidity in helium using a cute experiment. Take a torus and put a bunch of liquid helium in it. Then, spin up the torus and start lowering the temperature. At the onset of superfluidity, the superfluid helium particles will stop rotating relative to the lab frame. As a result, the angular speed of the torus will increase. (Conservation of momentum?) 

> The speaker demonstrated that, by taking the radius of that torus to infinity, then we conclude that the superfluid is invariant under Galilean transformations. (That is, a transformation where we add or subtract a constant velocity to the system.) A detailed analysis of the consequences of this leads to a new formula for calculating the superfluid density, which I hear is an important thing to know.

* Quantum Bochner's Theorem

> CQuIC's own Ninnat Dangniam gave a talk on generalizing the classical Bochner theorem to the quantum mechanical case. The starting point is to observe that we often use _quasiprobability representations_ of quantum states. For instance, the Wigner function is such a representation. Sometimes, we wish to focus on 
representations over discrete phase spaces, though those reasons are not fully clear to me.

> The main question Ninnat wanted to address is "For a given quasiprobability representation, does it actually correspond to a valid quantum state or measurement?" (Where "valid" in this case means the operator representation is positive.)  Of course, given the mapping from quantum states to the quasiprobability representation, we could simply take our representation, do the inverse mapping, and then compute the eigenvalues of the resulting "state". If those eigenvalues were all positive, then the representation did in fact correspond to a valid state.

> However, this process is annoying in that we have to go back to the Hilbert space representation of quantum states. Is there a way to answer this question without having to do so? The answer is yes. By constructing a matrix whose entries are related to the Fourier transform of the quasiprobability representation, it turns out that proving positivity of the associated "state" is equivalent to checking positivity of that matrix. So all we need to do is calculate some Fourier transforms.