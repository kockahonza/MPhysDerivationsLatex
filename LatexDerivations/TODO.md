Investigate further relation between "single complex phase -- aka E_{ij} = e^{i\phi} T_{ij}" -- and normality, uniaxiality and "eigenvalues" conditions. Currently have:
    - SCP => normality
    - normality and uniaxiality (as in a single non-degenerate eigenvalue) and symmetry => imply E = psi(NN - delta/d) => SCP
    - want to check a general normality, symmetry and whatever evs (suspect if they have a common complex phase then we get E have SCP)

Counting DOF for various sets of constraints                                                            for -> 2D, 3D
    - SCP reduces dof to 1 + d^2 (without symmetry etc.)                                                    -> 5, 10
    - SCP and symmetry gives 1 + (d(d+1))/2 dof                                                             -> 4, 7
    - SCP, symmetry and tracelessness would give 1 + (d(d+1))/2 - 1 = (d(d+1))/2                            -> 3, 6
    - normality gives d^2 (for a d x d unitary matrix) + d * 2 for the d unconstrained evs                  -> 8, 15
    guessing now:
    - normality, symmetry and tracelessness gives                                                           -> ?, 7
        but it does not have a SCP!
    - normality, symmetry, traceless and single phase of eigenvalues (same as the betas)                    -> ?, 6


2*(d^2) / (d^2 + 2d) = (2d)/(d + 2) = 2 - 4/(d+2)


My notes on the reasoning behind E theory as is
    1 - Need to be able to diagonalize it - requiring normality along with symmetry and traceless makes that possiblle and gives rise to a biaxial form equivalent to that of Q
    2 - Forming F could be explored more rigorously from either the mathematical or the physical reasoning side, however as E is complex and F is real it is reasonable to assume that all terms in F will be of form |E_?? E_?? .. E_?? possiby other tensors too|^2, well if we start counting with as little occurences of E as possible and go by order of gradients we get the terms we use in the 1 constant approx
    3 - we go up to second order derivatives and try to assign physical sense to all terms, then we introduce the projection operators as we expect cost of gradients parallel and perpendicular to N (assuming nearly uniaxial) to be different
    4 - compute the functional derivatives, dealing with constraints in various ways - not done yet, will elaborate later
