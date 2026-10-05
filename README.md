# Anima Online
the first of its kind, open sourced, community platform


*compartmentalized for security and to be less "monolithic"*
*(compute code doesn't need to be on a server dedicated to memory, for example)*

## [anima-compute](./anima-compute)
the main node that handles rendering, crud ops and http

## [anima-database](./anima-database)
the node that handles database ops

## [anima-memory](./anima-memory)
the node that handles mem ops

## [anima-shared](./anima-shared)
the node that handles shared ops such as mTLS (ran on every machine)

## [anima-subnode](./anima-subnode)
misc subnode for future stuff itll probably need

node communications: mTLS LAN, <20ms target for db and mem ops