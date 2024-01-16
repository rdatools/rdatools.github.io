# rdatools.github.io

RDA Tools project web site

## Development Notes

The projects (packages) have a somewhat complex dependency structure.
Revise them and (re)install them in the following order:

1. rdabase
2. rdascore &#8212; depends on rdabase
3. rdadccvt &#8212; depends on rdascore
4. rdaensemble &#8212; depends on rdabase, rdascore, and rdadccvt
5. tradeoffs &#8212; depends on rdabase, rdascore, and rdaensemble
