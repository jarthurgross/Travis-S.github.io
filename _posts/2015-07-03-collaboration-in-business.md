---
layout: default
title: Collaboration in Business
subtitle: Office and Version Control
date: 2015-07-03
author: Travis Scholten
---

Recently I had to go about creating a slide deck in PowerPoint. Unfortunately, as far as I can tell, git has no way of doing a `diff` on the .pptx files - essentially it sees the file as one big binary "blob". Trying to figure out way to deal with this has lead me to think about version control, business, and collaboration. (In all fairness, I have had exactly the same problem using Keynote for my academic presentations.)

In the tech world, there is a push towards automating most of the problems of coding collaboration - determining who made a change, documenting why the change was made, making sure the changes do not break other parts of the code, etc. We have services like [Jenkins](https://jenkins-ci.org/) and [Travis CI](https://travis-ci.org/) for [continuous integration](https://en.wikipedia.org/wiki/Continuous_integration), and [git](https://git-scm.com/)/[GitHub](http://github.com) for version control. Of course, one cannot fully automate the collaboration process. Meetings have to be had, timetables determined, people put in charge, and whatnot.

While tech seems to understand the human side of collaboration, the business world struggles with the code side. Although tools exist to help facilitate collaboration (such as those provided by [Altassian](https://www.atlassian.com/)), these tools seem to be predominately used to help manage the people side of business - scheduling meetings, sending messages, establishing workflows. But when everyone is still using the Office suite of products, version control via git (and I would imagine Subversion or Mercurial) is essentially impossible. 

Of course, not all business is code. But code is becoming an increasing part of business. For instance, time series analysis may be done using Excel or SAS. While the latter can be put under version control with git, the former cannot. Given the penetration of the Office suite of products, I would wager the vast majority of businesses are working with tools which make it all but impossible to do sensible version control. As a result, there is a tremendous amount of efficiency which could be gained by making version control of those files easier. Or moving to a file format/tool for which version control *is* simpler.

At the very least, using version control on Office files (.docx, .xls, .pptx) **provided there are clear commit comments** would also go a long way towards improving the collaboration process in business. There's no reason for a file with a name such as `Important_File-final_edits-my_modifications-V2` to be on anyone's machine. If someone is doing actual text-based coding (such as Python, R, SAS, etc.), then there's no excuse not to use version control.

