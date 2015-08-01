---
layout: default
title: Academics
subtitle: Pedagogy, Posters, and Presentations
---
#Presentations

Below is a list of some of the talks I have given. If possible, I have provided links to a screencast or video. At the very least I strive to provide a copy of the slide deck used.

<ul>
{% for post in site.posts %}
    {% if post.type == 'talk' %}
    <li><span>{{ post.date | date_to_string }}</span> -- <a href="{{relative}}{{post.url | remove_first: '/'}}">{{post.title}} {{post.name}}</a></li>
    {% endif %}
{% endfor %}
</ul>

#Posters

Below are links to various posters I have given. Available in pdf form.

2015 Southwestern Quantum Information and Technology Workshop

> [Lost in (Hilbert) Space - Model Selection for Quantum Tomography](https://drive.google.com/open?id=0ByuLKbIlGFIiejFnX1ZibHRIb1E&authuser=0)

> Reconstructing the quantum state of a continuous variable system (e.g., an optical mode) using quantum tomography presents a unique problem:  the dimension of its Hilbert space is infinite.  Its density matrix has infinitely many parameters, which cannot all be estimated from finite data.  Brute force reconstruction (e.g., via the Radon transform or deconvolution) produces undesirable overfitting artifacts.  Smoothing is one solution, but has no good theoretical justification. 

> I introduce a statistically well-motivated approach based on model selection and log likelihoods.  Maximum likelihood estimates in a sequence of D-dimensional subspaces (spanned by the first D Fock states) are ranked by their log likelihood. This ranking allows one to find an estimate whose dimension is smaller while simultaneously providing a good fit to data. I apply this method to heterodyne tomography and demonstrate the method can indeed eliminate overfitting by choosing a good dimension (D) in which to reconstruct optical states. 

Pedagogy
==========

Below is a list of courses I have taught or been involved with. Most of the information about the labs I have participated in is available through the [labs website](http://physics.unm.edu/Regener/Lab/).

**Fall 2013**:

* Physics 503 - [Graduate Classical Mechanics](http://info.phys.unm.edu/~caves/courses/phys503-f13/info.html)

**Fall 2012**: 

* Ph 161L - [Syllabus](https://app.box.com/s/1edxkijegls21bpe5i8m)

* Ph 151L - [Syllabus](https://app.box.com/s/0dmrtcpbe0czophtpx1p)

**Spring 2013**:

* Ph 160L - [Syllabus](https://app.box.com/s/tr2ztqjjpgki43lkcr1m)

* Ph 102L - [Syllabus](https://app.box.com/s/g2b2nrhhkomeraz6jyb0)
