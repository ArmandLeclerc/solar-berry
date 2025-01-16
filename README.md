# There is Berry phase in solar acoustic modes

This repository holds the numerical scripts used to support the claims of the paper of Leclerc &amp; Laibe, 2025 regarding Berry phase in acoustic solar modes.

ray_tracing_Sun_Berry.ipynb is a Jupyter notebook containing all the python treatment of the equations discussed in the article. It computes the frequencies of normal modes directly from the 1D model,
using the Dedalus library as reference points. The Bohr-Sommerfeld equation of the ray-tracing technique is also solved on a phase space. The frequencies are compared to the available observed ones.

The 1D model is the S model (standard model of the Sun), in file S_model.data.FGONG

The observed frequencies are in erate_all_multiplets_online_only.dat, from Kiefer & Broomhall 2021.
