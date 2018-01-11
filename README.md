# MCNP_Tutorial
Follow the tutorial of MCNP at
http://homepages.cae.wisc.edu/~bohm/neep412/

Other References:
http://www.mne.k-state.edu/~jks/MCNPprmr.pdf
http://homepages.cae.wisc.edu/~bohm/neep412/lucasMCNPTutorialspring2010.pdf

Basic command:
>$ mcnp6 [options] i=[inputfile] (generate out* src* com* files)

>$ mcnp6 [options] n=[inputfile] (generate extended files)

>$ mcnp6 n=[inputfile] tasks 4 (run in parallel with 4 cores)

It generates the extended files:
[inputfile]o (results)
[inputfile]r (checkpoint file)
[inputfile]s (geometry plot command)
Need to remove above files to run mcnp again.

[inputfile] is the "card" containing cell cards, surface cards and data cards.

cell cards (volumes)
surface cards (surface enclose the volumes)
data cards (material data)

[options]:
i = process input file
p = plotgeometry
x = process cross sections
r = transport the particle
z = plot tally results or cross section data
For example:
>$ mcnp6 ip n=[inputfile]