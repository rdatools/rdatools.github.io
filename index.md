# RDA Tools

The [rdatools](https://github.com/orgs/rdatools/repositories) project consists of several interrelated subprojects:

-   [rdabase](https://github.com/rdatools/rdabase)&#8212;Provides 2020 precinct-level census, demographic, and election data and precinct shapes, 
    as well as some utility code shared across the other projects.
-   [rdascore](https://github.com/rdatools/rdascore)&#8212;Computes DRA analytics for an ensemble of redistricting plans.
-   [rdadccvt](https://github.com/rdatools/rdadccvt)&#8212;Balzer's algorithm (DCCVT) to find a maximally population compact map.
    Used by the next two projects.
-   [rdaensemble](https://github.com/rdatools/rdaensemble)&#8212;Implements several methods for generating ensembles of redistricting plans.
    Also enables you to compute DRA analytics for each plan in an ensemble.
-   [rdaroot](https://github.com/rdatools/rdaroot)&#8212;Implements a heuristic approach to approximating a root redistricting map (plan).

Together these projects provide the data &amp; code to generate ensembles
of redistricting plans with consistent inputs and in a repeatable manner
facilitating apples-to-apples comparisons of the approaches.
They also enable you to understand and characterize the trade-offs between quantitative policy objectives inherent in a state's
political geography.