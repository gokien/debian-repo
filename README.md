Gokien repository
=================

This repository is a Github Page holding a reprepro-based Debian repository
that serves Gokien's packages.

To include a package into this repository, first build that package, then run
this command (assuming the package's name is `gokien-os-overlay`):

    reprepro include precise /path/to/gokien-os-overlay_0.1_i386.changes
