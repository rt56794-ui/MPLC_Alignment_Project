# MPLC_Alignment_Project
Simulation only - no lab data
Scalar diffraction theory is used to simulate Hermite-Gaussian propagation through a batch of MPLCs given misalignment parameters and a batch of phase mask configurations
The PyTorch Adam optimiser is used alongside learning rate scheduling to estimate what those misalignment parameters were
MPLC Phase Masks are trained through the Gerchberg-Saxton algorithm and Sigma-annealed smoothing to transform a gaussian beam into the University of Exeter logo
The performance of the MPLC is tested with no misalignments, then with untrained misalignment parameters, then with optimised misalignments 
Optimised misalignments are the untrained misalignments minus estimated untrained misalignment parameters calculated by the optimiser
The optimiser improves performance by a lot - in simulation
