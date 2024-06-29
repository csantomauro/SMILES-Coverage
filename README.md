Advanced Algorithms and Parallel Programming Challenge

In the chemistry domain, it is possible to represent a molecule in different ways. The richest formats describe the molecule topology and its atom's 3D displacement. On the other hand of the spectrum, we have compact notations that store only the molecule's topology in a single line. In this challenge, we focus on the SMILES notation (Ex. C(C(F)(F)F)(OC(F)F)Cl, [H]/[NH+]=C(\N)/c1ccc(cc1)OCCCCCOc2ccc(cc2)/C(=[NH+]/[H])/N) that belongs to the latter category. 

The goal of the challenge is to parallelize the application, using either OpenMP or MPI. You get one point if the application produces a correct output when running in parallel. You get an additional point if the application wall time reduces while increasing the parallelism level, following the ideal scaling.
