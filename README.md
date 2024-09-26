# PHYC30320
Python Code used in PHYC30320 laboratory work in the third year of my Bachelors

## Simulation of a Driven Pendulum
Here we study the effect of the changes of parameters a0 and w0 on the motion of a driven pendulum. Here a0 and w0 are constants parameterizing the amplitude and angular frequency and the external driving torque, respectively.
- Numerical solutions of non-linear differential equations of a driven pendulum are obtained using the Runge Kutta fourth order method.
- Regions of chaotic and regular motion of the driven pendulum are examined via simulations showing trajectories of velocity, position, as well as their phase portraits.
- These dynamic regimes (of parameters a0 and w0) are compared to the free pendulum case.
- Chaos is evident by making slight changes to the initial conditions and showing the large deviations in motion it causes over time.

## Fast Fourier Transform
Here we study the constituent wavelengths of multiple lasers via Fourier transform spectroscopy. 
- The Fourier transform of interferograms are calculated using a Fast Fourier transform algorithm.
- The wavelength spectrums are found for each laser, allowing identification of the dominant wavelength of the laser in question.
- This is done for three lasers: Blue, Green, and a Helium Neon (HeNe) laser.

## Ramsauer Townsend Effect
Here the Ramsauer Townsend effect is examined with data from a Xenon 2D21 thyratron. We observe the scattering effects of low-energy electrons from the Xenon atoms.
- Two sets of data were obtained and studied, between applied voltages of 0-15eV (Set 1) and 0-2eV (Set 2).
- Results obtained showed that a minimum in collision probability occurred when the electron energy was near 1eV, consistent with theory.
- Manipulation of the data corrects for the electron momentum, taking into account applied and shield voltages, as well as contact and thermionic potentials.
- A chi squared fit is used to determine values of the contact and thermionic potentials.
- The mean free path of the thermionic electrons in the Xenon gas is shown to vary, dependant on the electron momentum.
- The analysis was performed with and without an uncertainties package (https://pythonhosted.org/uncertainties) which aided in simple error propagation.
