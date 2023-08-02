# G2SO4
1) There is no particular order to the files, but to use some files you will see you may need to run first a code which contains the definitions of the unipotent and root subgroups of G2 (such as the code "matching"). Please do let us know if any part of those files are not easy to read/unclear. 
 
2) We have not made much comments on our lines of codes and computations, since we are expecting the reader is either familiarized with the definitions, or is following closely our paper "PARABOLICALLY INDUCED REPRESENTATIONS OF p-ADIC G2 DISTINGUISHED BY SO4 I" and/or that of Omer Offen "On parabolic induction associated with a p-adic symmetric space"

3) The second branch "old strategy" stores all files corresponding to an approach whose results were not conclusive in SageMath, justifying our use of the "main" approach using directly the x_i's. 
In this approach, we modified the elements x to x' = u.x = u.x.(theta (u)^{-1} = u.x.t0.u^-1.t0. Note that for x', the w (and hence the L) remains the same as x (as PxP = Px'P). So we needed to calculate u such that there existed an element m \in L such that the following equation had a solution u.x.t0.u^-1.t0 = mw (Note that above we have the freedom to choose m which we can use for our convenience). Once we knew u, we could determined the x's and then we calculated L_x', and U_x'. The computations of those (x')'s are available in this branch. We also calculated the values of L with the formula L = M(w tau) = M cap wMw^-1 page 217 of Offen's paper -see the bibliography- rather than with the formula page 212: L = M cap eta theta(eta^-1 M eta) eta^-1.
 
4) The word "matching" employed in the files' names refer to the process of matching the double coset representatives eta_i with Weyl group elements in the set W_b\W/W_b. The numbering of the double coset representatives (the expressions x_3, or x_5 for instance) follows from the brace at the end of Section 7.2 in our paper.  
5) The process of verifying the admissibility, openess and closedness of the orbits for each representative is done in "
admissibility_openess_closed"
6) We initially tried to verify those conditions (admissibility, openess and closedness) using the corresponding "w" identified using the "matching". Some of the relevant codes can be found in "admissibility_with_w".
7) The file "tau_p213" refer to some technical condition given in the paper of Offen that we have verified (see the paper "PARABOLICALLY INDUCED REPRESENTATIONS OF p-ADIC G2 DISTINGUISHED BY SO4 I")

