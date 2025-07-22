# git-hosting

This repository contains **visualizations, animations, and media outputs** from my academic research in **physics, engineering, and computational modeling**. It serves as a centralized archive for sharing **simulation results, figures, and GIFs** generated during analyses, numerical experiments, and algorithm development.

---

## 1. Moving Phase Screen (MegaScreen Simulation)

**Description:** Simulated phase distortions of a telescope aperture caused by atmospheric turbulence, generated with the **MegaScreen** library. The animation shows the evolution of a 2D phase screen under the frozen-flow hypothesis, where wind carries a static turbulence pattern across the aperture.

![Moving Phase Screen](https://raw.githubusercontent.com/Miguel88Alzate/git-hosting/main/phase_evolution_r0_3cm.gif)

---

## 2. Dynamic PSF Computed via FFT of the Moving Phase Screen (Telescope Pupil)

**Description:** The time-evolving Point Spread Function (PSF) is computed by applying a **Fourier Transform (FFT)** to the complex wavefront at the **telescope pupil**. This illustrates how turbulence dynamically modulates the diffraction pattern and blurs the incoming light during an observation.

![Dynamic PSF](https://raw.githubusercontent.com/Miguel88Alzate/git-hosting/main/moving_psf_r0_1.5cm.gif)

---

## 3. Distance Between Magnetic Barycenters Varying due to Earth's Atmospheric Turbulence

### 2.1 Magnetogram obtain with a Static PSF  
**Description:** The same PSF is used to aberrate all the polarization images that are combined to construct the Stokes parameters for the inversion process.  

![Barycenter Distance Magnetogram Static PSF](https://raw.githubusercontent.com/Miguel88Alzate/git-hosting/main/barycenter_distance_magnetogram_staticPSF.gif)

---

### 3.2 Magnetogram obtain with a dynamic PSF  
**Description:** Different PSFs are applied to aberrate each polarization image individually before combining them into the Stokes parameters for the inversion process.  

![Barycenter Distance Magnetogram Dynamic PSF](https://raw.githubusercontent.com/Miguel88Alzate/git-hosting/main/barycenter_distance_magnetogram_dynamicPSF.gif)



