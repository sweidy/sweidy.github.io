---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

MJO Indices:
I contributed to the [mjoindices toolbox](https://github.com/cghoffmann/mjoindices), including adding functionality for the rotated EOF method detailed in my [2022 paper](/publications/). 

Replay:
The replay (also known as the Incremental Analysis Update) methodology is a way to force a model to closely follow a target dataset, developed for NASA's GEOS model ([Bloom et al., 1996](https://doi.org/10.1175/1520-0493(1996)124<1256:DAUIAU>2.0.CO;2); [Takacs et al., 2018](https://doi.org/10.1175/MWR-D-18-0117.1)). I implemented the replay methodology in CESM2. The replay can be easily ported from github [here](https://github.com/sweidy/CESM), with documentation on how to run on this [Quickstart Guide](https://sweidy.github.io/CESM/versions/replay215/html/index.html). 