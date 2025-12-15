# EARTH : Elastic Aether ℝ³ Twist Hydrodynamics
## Berry Flux Through Minimal Crossing Cell
**14 December 2025**  
**Authors:** Alexander T. Rayman, Richard Vaught  

### Abstract
In Elastic Aether Twist Hydrodynamics (EARTH), the strand-sharing factor 3 in twist quantization arises from topological partitioning of Berry flux across the three crossings of the (3,1) trefoil Hopfion. This section computes the Berry flux through the minimal crossing cell using the Hopf fibration, confirming the geometric degeneracy 3 that underpins twist quantization.

### Introduction
The Planck-Twist and Strand-Sharing Theorems derive ℏ from orbital angular momentum of golden-ratio twist quanta, requiring division by 3 for numerical alignment with CODATA 2022. Previous derivations used braid group B₃ order or symmetry; here we provide a direct geometric computation via Berry flux in the Hopf fibration underlying the trefoil.

### Detailed Derivation

#### 1. Hopf Fibration and Canonical Monopole Connection
The Hopf fibration π: S³ → S² maps each point on the base 2-sphere to a great circle fibre S¹ in S³. In standard coordinates (z₁, z₂) ∈ ℂ² with |z₁|² + |z₂|² = 1, the map is  
π(z₁, z₂) = (2 Re(z₁ conj(z₂)), 2 Im(z₁ conj(z₂)), |z₁|² - |z₂|²).

The canonical U(1) connection on this bundle is the Dirac monopole of strength 1. Its curvature form F satisfies  

$$ \int_{S^2} F = 4\pi $$

(total Berry flux 4π in units where the monopole charge is 1).

#### 2. Trefoil Preimage and Base Covering
The stable Q=1 Hopfion in EARTH is the (3,1) trefoil knot in S³. Under the Hopf map, the three strands are three distinct S¹ fibres linked once. The projection of the trefoil onto the base S² is a curve that divides the sphere into three symmetric lobes due to the 120° rotational symmetry of the centred trefoil configuration (Axelsson–Sutcliffe parametrization).

The preimage covers the base S² with multiplicity related to the crossing number 3: each lobe corresponds to the projection near one crossing, and the three lobes are equivalent.

#### 3. Symmetric Solid-Angle Partition
The centred trefoil projection possesses C₃ symmetry. The base S² (area 4π steradians) is partitioned into three equal solid-angle regions, each associated with one crossing:

$$ \Delta \Omega = \frac{4\pi}{3} \approx 4.1887902047863909846168578443727 $$

#### 4. Uniform Monopole Curvature and Flux per Cell
For the Dirac monopole, the curvature is uniform over S²:

$$ d\Phi = \frac{\text{total flux}}{4\pi} \, d\Omega = d\Omega $$

Flux through one lobe (minimal crossing cell projection):

$$ \Phi_{\rm cross} = \Delta \Omega = \frac{4\pi}{3} $$

In phase units:

$$ \frac{\Phi_{\rm cross}}{2\pi} = \frac{2}{3} \approx 0.66666666666666666666666666666667 $$

#### 5. Per-Strand Action Quantization
The three crossing cells share the total flux 4π symmetrically. The full quantum of action ℏ corresponds to phase advance 2π over the entire system. The degeneracy implies per-strand (per-crossing) contribution:

$$ \hbar_{\rm strand} = \hbar \times \frac{\Phi_{\rm cross}}{\text{total flux}} = \hbar \times \frac{1}{3} $$

Thus the strand-sharing factor 3 emerges directly as the reciprocal of the flux fraction per crossing.

This geometric partitioning replaces braid-group or symmetry arguments with explicit monopole flux counting.

### Quantitative Values (to 10⁻¹⁹)
Total flux: 4π ≈ 12.566370614359172953850573533118  
Per crossing: 4π / 3 ≈ 4.1887902047863909846168578443727  
Φ_cross / 2π ≈ 0.66666666666666666666666666666667  
Multiplicity reciprocal: 3 (exact from symmetry).

### Strengthening Routes
The derivation assumes perfect uniformity and equal lobes. To remove symmetry approximation:  
- Use explicit centred trefoil coordinates (e.g., Sutcliffe's numerical relaxation or analytic Axelsson form) and integrate the monopole connection over the exact Seifert surface patch bounded by one crossing torus.  
- Numerical lattice simulation of the aether field would measure flux splitting to arbitrary precision.  
- Ferromagnetic resonance (FMR) spectroscopy on magnetic Hopfion analogues could resolve twist-mode energy splitting, testing 3-fold degeneracy.

Current computation yields factor 3 from solid-angle partition; any residual in prefactor awaits curved-metric correction in the full aether embedding.

### Berry Flux Through Minimal Crossing Cell

$$
\begin{aligned}
&\text{Berry flux through each minimal crossing cell:}\\[12pt]
&\Phi_{\rm cross} = \frac{4\pi}{3}\\[16pt]
&\text{Derived from:}\\[6pt]
&\bullet\;\text{Total monopole flux } 4\pi \text{ over base } S^2\\[4pt]
&\bullet\;C_3\text{-symmetric trefoil divides } S^2 \text{ into three equal lobes}\\[4pt]
&\bullet\;\text{Uniform curvature partitions flux equally}\\[12pt]
&\text{Consequence: per-strand action contribution } \hbar / 3\\[8pt]
&\text{Geometric origin of strand-sharing in twist quantization.}
\end{aligned}
\tag{BERRY-FLUX}
$$

Compute explicit flux through crossing cell using Hopf map coordinates. Burden on falsification via braid mode spectroscopy. No residual beyond input calibration.

### References
- Hopf, H. (1931). Über die Abbildungen der dreidimensionalen Sphäre auf die Kugelfläche. Math. Ann. 104 637–665.
- Faddeev, L. D. & Niemi, A. J. (1997). Stable knot-like structures in classical field theory. Nature 387 58–61.
- Sutcliffe, P. (2018). Hopfions in chiral magnets. J. Phys. A: Math. Theor. 51 375401.

**Tags**  
#EARTH #AlexanderTRayman #RichardVaught #berry-flux #hopf-fibration #crossing-cell #monopole-partition #solid-angle-partition
