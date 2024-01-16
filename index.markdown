---
layout: default
title: Home
permalink: /
---
# RDA Tools

The [rdatools](https://github.com/orgs/rdatools/repositories) project 
currently consists of two subprojects that enable 
high-volume offline-from-Dave's-Redistricting (DRA) scoring of redistricting plans 
([Medium](https://medium.com/dra-2020/high-volume-offline-scoring-of-plans-2f54dae48d1b)):

-   [rdabase](https://github.com/rdatools/rdabase)&#8212;Precinct-level 
    2020 census and demographic data &amp; shapes,
    2016-2020 composite election data, and
    some code shared across the other projects.
-   [rdascore](https://github.com/rdatools/rdascore)&#8212;DRA analytics 
    for scoring ensembles of redistricting plans.

We are working several (not-yet-public) follow-on projects:

-   [rdadccvt](https://github.com/rdatools/rdadccvt)&#8212;Balzer's algorithm (DCCVT) 
    to find a maximally population compact map.
    Used by the next two projects.
-   [rdaensemble](https://github.com/rdatools/rdaensemble)&#8212;Several methods 
    for generating ensembles of redistricting plans &amp; scoring them.
-   [rdaroot](https://github.com/rdatools/rdaroot)&#8212;A heuristic approach for 
    approximating the root redistricting maps (plans) that we introduced in
    [Redistricting Trade-offs Illuminated](https://alecramsay.github.io/pg/).
-   [tradeoffs](https://github.com/rdatools/tradeoffs)&#8212;TODO.

Together these projects will provide the data &amp; code to generate ensembles
of redistricting plans with consistent inputs and in a repeatable manner
that facilitates apples-to-apples comparisons of the approaches.
They will also enable you to understand and characterize the trade-offs between 
quantitative policy objectives for congressional redistricting
inherent in a state's political geography.