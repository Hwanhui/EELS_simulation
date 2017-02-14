# EELS_simulation

Core-loss edges in EELS are generated due to the excitation of core electrons to the empty energy level above the Fermi energy. The initial (𝑖) and final (f) states of the excitation have uncertainties in their energy due to a finite lifetime. (Heisenberg uncertainty principle) The uncertainty in the energy induces the energy broadening of each state, which is referred to as the energy level width Γ.

In this code, the energy broadening of the initial and the final state is implemented to a simulated EELS spectrum. 
The energy level width of the initial state, Γi, is relatively small and almost constant for a chosen core-loss edge. (See the left box of (a)) The energy level width of the final state, Γf, is relatively big (0~6 eV) and varies with the final energy relative to the onset energy of core-loss edge. (See the right box of (a)) The input EELS data is convolved with Lorentzian function with the FWHM of Γi and Γf, consecutively. The example input and resulting EELS spectra are shown in (b).
