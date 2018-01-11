# MCNP_Tutorial
Follow the tutorial of MCNP at
http://homepages.cae.wisc.edu/~bohm/neep412/

Basic command:
>$ mcnp6 ip n=[inputfile] (display geometry)

>$ mcnp6 n=[inputfile] (run the transport)

>$ mcnp6 n=[inputfile] tasks 4 (run in parallel with 4 cores)

It generates the following files:
[inputfile]o (results)
[inputfile]r (checkpoint file)
[inputfile]s (geometry plot command)

Need to remove above files to run mcnp again.

[inputfile] is the "surface card".