# Dependencies

The projects (packages) have a somewhat complex dependency structure.
Revise them and (re)install them in the following order:

1. rdabase &#8212; None
2. rdascore &#8212; rdabase, rdapy
3. rdadccvt &#8212; rdabase
4. rdaensemble &#8212; rdabase, rdascore, rdadccvt
5. rdaroot &#8212; rdabase, rdadccvt, rdaensemble
6. tradeoffs &#8212; rdabase, rdapy, rdascore, rdaensemble