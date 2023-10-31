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
