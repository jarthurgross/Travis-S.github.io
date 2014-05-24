---
layout: default
title: Musings
---
As part of my undergraduate experience at Caltech, I did some [blogging](http://caltech.typepad.com/caltech_as_it_happens/strong-minds-healthy-bodies/) for the [Admissions Office](http://admissions.caltech.edu/). So perhaps there is still some part of me which wishes to improve my writing and communications skills. If anything, I am more apt to post content on my [Google Plus Profile](http://www.google.com/+TScholten).

During my first few years at Caltech, I wrote quite a bit of poetry. I have made a couple of collections available online. They are entitled [A Long Walk](https://app.box.com/s/c87krb40j0mlqirykpa6) and [Summer Musings](https://app.box.com/s/tctkl613kvn42uc9givp).

In 2011, I took a trip to Swizerland. Here are my [recollections](https://app.box.com/s/0eneuydhs4l65d3818r9) of that trip.

September 3, 2013 - [Failure to Govern](http://www.unm.edu/~tscholten/ftg.pdf)

<ul>
{% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{post.url}}">{{post.title}}</a></li>
{% endfor %}
</ul>
