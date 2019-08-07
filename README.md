# Corason Singularity Image

This repository contains a Singularity definition file for a version of the
`nselem/corason` docker image that will work properly under Singularity. The
only difference from the original docker image is that the CORASON perl scripts
have been moved out of `/root` and into `/opt/corason` and the `$PATH` updated.
