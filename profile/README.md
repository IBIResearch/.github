# IBI Research

**Website**: [Organization Website](https://www.tuhh.de/ibi/home)

The Institute for Biomedical Imaging (IBI) is a joint research department of the University Medical Center Hamburg-Eppendorf (UKE) and the Hamburg University of Technology (TUHH). We focus on medical imaging, i.e., non-invasive visualization of regions of the human body, which is crucial for the diagnosis, treatment, and follow-up of many diseases. High-quality, safe, and efficient imaging can support better medical decisions and help avoid unnecessary procedures. Our research centers on tomographic imaging, with a particular emphasis on Magnetic Resonance Imaging (MRI) and the emerging modality of Magnetic Particle Imaging (MPI). Specifically, we develop MPI hardware, investigate novel signal processing, image reconstruction, and image processing algorithms, and assess their medical applicability. In close collaboration with our clinical partners at UKE, we also pursue translational research aimed at integrating state-of-the-art acquisition and reconstruction methods into clinical practice.

This organization collects research software developed at IBI and published in the respective scientific publications. For an overview of our research activities, please visit our [website](https://www.tuhh.de/ibi/research).

## Packages

* [SphericalHarmonicExpansions.jl](https://github.com/IBIResearch/SphericalHarmonicExpansions.jl): A Julia package to handle spherical harmonic functions.
* [ImageUtils.jl](https://github.com/IBIResearch/ImageUtils.jl)
* [RedPitayaDAQServer](https://github.com/IBIResearch/RedPitayaDAQServer): Advanced DAQ Tools for the RedPitaya (STEMlab 125-14).




## Repositories Related to Published Works

<html>
<table>
  <tr>
    <th>Repository</th>
    <th>Description</th>
    <th>Paper</th>
  </tr>
  
  <tr>
    <td><a href="https://github.com/IBIResearch/mpi-sm-restoration">mpi-sm-restoration</a></td>
    <td> Training and evaluation of deep learning models for system matrix restoration in magnetic particle imaging using simulated data. </td>
    <td> A. Tsanda, S. Reiss, M. Boberg, and T. Knopp (2025). Deep Learning for Restoring MPI System Matrices Using Simulated Training Data. arXiv preprint. doi: <a href="http://dx.doi.org/10.48550/arXiv.2511.23251">10.48550/arXiv.2511.23251</a>.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/IBIResearch/SphericalHarmonicExpansionOfMagneticFields">SphericalHarmonicExpansionOfMagneticFields</a></td>
    <td>Representation of a static magnetic fields using solid harmonic expansions.</td>
    <td>M. Boberg, T. Knopp, and M. Möddel (2025). Unique compact representation of magnetic fields using truncated solid harmonic expansions. European Journal of Applied Mathematics. 36(5):1012-1039. doi: <a href="https://doi.org/10.1017/S0956792524000883">10.1017/S0956792524000883</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/IBIResearch/EllipsoidalHarmonicExpansions">EllipsoidalHarmonicExpansions</a></td>
    <td> Ellipsoidal Harmonic Expansions for Effective Measurement and Representation of Magnetic Fields. </td>
    <td> K. Scheffler, L. Meyn, F. Foerger, M. Boberg, M. Möddel, and T. Knopp (2025). Efficient measurement and representation of magnetic fields in tomographic imaging using ellipsoidal harmonics. Communications Physics. 8. (112). doi: <a href="http://dx.doi.org/10.1038/s42005-025-02012-5">10.1038/s42005-025-02012-5</a>.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/IBIResearch/GPU-Accelerated-MultiPatch">GPU-Accelerated-MultiPatch</a></td>
    <td> GPU-accelerated multi-patch reconstruction using MPIReco.jl </td>
    <td> N. Hackelberg, M. Boberg, and T. Knopp (2025). GPU Accelerated Multi-Patch Reconstruction. International Journal on Magnetic Particle Imaging. 11. (1 Suppl 1), 1-2. doi: <a href="http://dx.doi.org/https://doi.org/10.18416/IJMPI.2025.2503048">10.18416/IJMPI.2025.2503048</a>.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/IBIResearch/HandsfreeReco">HandsfreeReco</a></td>
    <td> Solving the MPI Reconstruction Problem with automatically tuned regularization parameters. </td>
    <td> K. Scheffler, M. Boberg, and T. Knopp (2024). Solving the MPI reconstruction problem with automatically tuned regularization parameters. Physics in Medicine & Biology. 69. (4). doi: <a href="http://dx.doi.org/10.1088/1361-6560/ad2231">10.1088/1361-6560/ad2231</a>.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/IBIResearch/EquilibriumModelWithAnisotropy">EquilibriumModelWithAnisotropy</a></td>
    <td> Modeling the physics of magnetic nanoparticles for the usage in model-based magnetic particle imaging. </td>
    <td> M. Maass, T. Kluth, C. Droigk, H. Albers, K. Scheffler, A. Mertins, and T. Knopp (2024). Equilibrium Model With Anisotropy for Model-Based Reconstruction in Magnetic Particle Imaging. IEEE Transactions on Computational Imaging. 10. 1588 - 1601. doi: <a href="http://dx.doi.org/10.1109/TCI.2024.3490381">10.1109/TCI.2024.3490381</a>.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/IBIResearch/MPSTransferFunction">MPSTransferFunction</a></td>
    <td> Application of an MPS transfer function to measured data. </td>
    <td> F. Thieben, T. Knopp, M. Boberg, F. Foerger, M.Graeser, and M. Möddel (2023). On the Receive Path Calibration of Magnetic Particle Imaging Systems. IEEE Transactions on Instrumentation and Measurement. 72. 1-15. doi: <a href="http://dx.doi.org/10.1109/TIM.2022.3219461">10.1109/TIM.2022.3219461</a>. </td>
  </tr>
  <tr>
    <td><a href="https://github.com/IBIResearch/IncreasedDynamicRange">IncreasedDynamicRange</a></td>
    <td>Two-step reconstruction of widely differing particle concentrations in magnetic particle imaging.</td>
    <td>M. Boberg, N. Gdaniec, P. Szwargulski, F. Werner, M. Möddel, and T. Knopp. (2021). Simultaneous imaging of widely differing particle concentrations in MPI: problem statement and algorithmic proposal for improvement. Physics in Medicine & Biology, 66(9), 095004. doi: <a href="http://dx.doi.org/10.1088/1361-6560/abf202">10.1088/1361-6560/abf202</a>. </td>
  </tr>
  <tr>
    <td><a href="https://github.com/IBIResearch/OptimizedSystemMatrixSampling">OptimizedSystemMatrixSampling</a></td>
    <td> Generation of optimized sampling patterns for system matrices in magnetic particle imaging.</td>
    <td> M. Grosser and T. Knopp (2021). Optimized sampling patterns for the sparse recovery of system matrices in Magnetic Particle Imaging. International Journal on Magnetic Particle Imaging. 7. (2), 1-15. doi: <a href="http://dx.doi.org/10.18416/IJMPI.2021.2112001">10.18416/IJMPI.2021.2112001</a>.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/IBIResearch/EasyAxisOrientationEstimation">EasyAxisOrientationEstimation</a></td>
    <td> Estimation of the spatial orientation of immobilized magnetic nanoparticles with parallel aligned easy axes. </td>
    <td> M. Möddel, F. Griese, T. Kluth, and T. Knopp (2021). Estimating the Spatial Orientation of Immobilized Magnetic Nanoparticles with Parallel-Aligned Easy Axes. Phys. Rev. Applied. 16. L041003. doi: <a href="http://dx.doi.org/10.1103/PhysRevApplied.16.L041003">10.1103/PhysRevApplied.16.L041003</a>. </td>
  </tr>
  <tr>
    <td><a href="https://github.com/IBIResearch/DictionaryBasedBackgroundEstimation">DictionaryBasedBackgroundEstimation</a></td>
    <td> Joint reconstruction of background and particle concentration of magnetic particle imaging data.</td>
    <td> T. Knopp, M. Grosser, M. Graeser, T. Gerkmann, and M. Möddel (2021). Efficient Joint Estimation of Tracer Distribution and Background Signals in Magnetic Particle Imaging using a Dictionary Approach. IEEE Transactions on Medical Imaging, 40(12). doi: <a href="http://dx.doi.org/https://doi.org/10.1109/TMI.2021.3090928">10.1109/TMI.2021.3090928</a>. </td>
  </tr>
</table>
</html>
