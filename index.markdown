---
layout: default
title: Home
permalink: /
---
# RDA Tools

The [rdatools](https://github.com/orgs/rdatools/repositories) project 
consists of several repositories:

-   [rdabase](https://github.com/rdatools/rdabase)&#8212;contains precinct-level 
    2020 census and demographic data &amp; shapes,
    2016-2020 composite election data, and
    some code shared across the other projects.
-   [rdascore](https://github.com/rdatools/rdascore)
    &#8212;enables high-volume offline-from-Dave's-Redistricting (DRA) scoring 
    ([Medium](https://medium.com/dra-2020/high-volume-offline-scoring-of-plans-2f54dae48d1b))
    of scoring ensembles of redistricting plans.
-   [rdaensemble](https://github.com/rdatools/rdaensemble)&#8212;contains several methods 
    for generating ensembles of redistricting plans &amp; one for scoring them.
-   [tradeoffs](https://github.com/rdatools/tradeoffs)&#8212;contains a bevy of tools using the repositories above
    to analyze the trade-offs in redistricting for a state as well as 
    the [Trade-offs in Redistricting](https://rdatools.github.io/tradeoffs/) web site.
-   [rdadccvt](https://github.com/rdatools/rdadccvt)&#8212;Balzer's algorithm (DCCVT) 
    to find a maximally population compact map.
-   [rdaroot](https://github.com/rdatools/rdaroot)&#8212;A heuristic approach for 
    approximating the root redistricting maps (plans) using Balzer's algorithm
    that we introduced in [Redistricting Trade-offs Illuminated](https://alecramsay.github.io/pg/).

Together these projects provide the data &amp; code to generate ensembles
of redistricting plans with consistent inputs and in a repeatable manner
that facilitates apples-to-apples comparisons of the approaches.
They also enable you to understand and characterize the trade-offs between 
quantitative policy objectives for congressional redistricting
inherent in a state's political geography.