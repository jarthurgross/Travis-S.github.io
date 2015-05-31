---
layout: default
title: APS March Meeting - Day 5
subtitle: Wrapping Up
date: 2015-05-26
author: Travis Scholten
---
On the last day of March meeting, I had to catch a plane later that evening, and so I only listened to some talks.

Given my interest in understanding how to do computational physics, I attended a session specifically on problems related to computation and material science. It turns out there has been a big effort over the years to assemble databases of materials and their properties; now, the problem is querying these databases and adding new entries to them.

* Automatic FLOW for Materials Discovery - Marco Fornari

> In terms of materials design, an important and difficult task is computing their properties. There are computational tools such as AFLOW, VASP/QE, which can be used to compute properties for different materials. A major contribution to this work has been to create a new database using the resourced of the [AFLOWLIB consortium](http://www.aflowlib.org/). This database utilizes density functional theory to compute materials properties for order 650,000 compounds, and has interfaces for UNIX and SQL-style database queries. 

> The materials properties calculations are written in Python and utilize the "standard Python science stack" of numpy, scipy, and matplotlib. The main bottleneck in the entire process has been computing the properties using DFT, and suggests that in order to increase _throughput_ (number of materials which can be processed and analyzed), new DFT algorithms are necessary.

* [Magnetic Genome Project - Stefano Sanvito](http://meetings.aps.org/Meeting/MAR15/Session/Z18.2)

> Magnetic materials underpin a lot of today's technology. (For instance, the data storage industry needs these materials for hard drives.) However, most magnetic materials require rare-earth elements, which are expensive to purchase because they are in limited supply. As such, it would be great if we could _design_ new magnetic materials, but without having to use rare earths.

> The idea of the "Magnetic Genome Project" is to explore the parameter space of materials and determine whether new materials could be designed which had desirable magnetic properties.

* Distributed databases for materials study of thermo-kinetic properties   - Cormac Toher

> Again, materials properties are important. For those who are interested in thermal properties, there is a numerical library called the [Automatic Gibbs Library](http://arxiv.org/abs/1407.7789) which allows for high throughput screening of materials. 