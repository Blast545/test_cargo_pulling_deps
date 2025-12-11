## OBJECTIVE

We want to provide users of Rust in the ROS ecosystem alternatives to pull everything from crates.io in the Rust way.

We are concerned about package curation/cohesion and we would like to find a way to provide users of the ROS ecosystem
with crates that are curated in some way (yet to be defined) that can co-exist with pulling packages from crates.io


-> What debians does
   Debian overrides completely crates.io using "Directory Sources", we can not follow this approach (at least not entirely)
-> Alternatives:
   Can we combine path installation with crates.io?
   Do we have to maintain a third-party mirror and mix it with crates.io usage?
        -> If this is the idea, how can we support local installation from that mirror + modifications? (via patches)

## Alternatives: TBD / Investigated