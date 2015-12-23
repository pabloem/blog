---
layout: post
title: When PageRank fails
tags:
  - research
  - cs

---

Manuel Sebastian Mariani, Matús Medo, and Yi-Chen Zhang at the University of Fribourg in Switzerland have been working
on [a new paper](http://arxiv.org/abs/1509.01476) where they take a deep serious look at the PageRank algorithm; and its
behavior on networks that grow over time. The paper was mentioned on the MIT Technology Review's ['Emerging Technology from
the ArXiv' list](http://www.technologyreview.com/view/541416/other-interesting-arxiv-papers-week-ending-september-19-2015/)
a couple weeks ago, and I gave it a read (partly because I have to present it at school). I figured I would write a small
post about it, since PageRank is such an important algorithm.

## What is PageRank?
Well, first things first. For those who have never heard the name, or who have heard it; but might not have learned the
specifics of how the PageRank algorithm works - or what it is; let's learn that first.

The PageRank algorithm was develoed at Stanford University by now-billionaires Larry Page and Sergey Brin, in 1996.
