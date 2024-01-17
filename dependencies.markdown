# Dependencies

The projects (packages) have a somewhat complex dependency structure.
Revise them and (re)install them in the following order:

1. rdabase
2. rdascore &#8212; depends on rdabase
3. rdadccvt &#8212; depends on rdascore -- for load_plan()
4. rdaensemble &#8212; depends on rdabase, rdascore, and rdadccvt
5. tradeoffs &#8212; depends on rdabase, rdascore, and rdaensemble