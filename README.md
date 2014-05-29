dvbhdhomerun
============

A patch that helps dvbhdhomerun work better with tvheadend. This was upstreamed, so it's here purely for historical reasons. 

Patch that uses the tuner_count returned by recent versions of libhdhomerun, for compatibility with HDHomeRun Prime.
Also sets the DVB frontend name to the HDHomeRun tuner name, for convenience when used with TVHeadEnd.

- Paul Chambers, April 8, 2012.
