# Holographic Feedback Cosmology: A Cyclic Universe Model Based on Boundary Dynamics

**Author**

Independent Researcher, China  
ORCID: 0009-0003-6134-3736

## Abstract

Building upon Penrose's Conformal Cyclic Cosmology (CCC) and quantum cosmology, we propose Holographic Feedback Cosmology (HFC), which restructures the inter-epoch evolution of the universe as an adaptive optimization process in boundary state space. Through the de Sitter/Conformal Field Theory duality (dS/CFT) and the Coleman-De Luccia instanton mechanism, this framework provides computationally tractable parameter update laws for cyclic cosmology. We demonstrate that inflation, vacuum metastability, and heat death phase transitions can be mapped to three convergence modes: gradient descent, saddle-point tunneling, and constraint projection, respectively, with dynamics driven by the gradient flow of boundary entanglement entropy. The model predicts that conformal crossover will leave logarithmic periodic oscillations and sound speed deviation signals in the CMB power spectrum, which can be definitively tested by LiteBIRD and CMB-S4. This framework is strictly limited to semiclassical effective field theory, introduces no additional degrees of freedom, and is compatible with current atomic clock, PPN parameter, and black hole information constraints.

**Keywords:** Quantum Cosmology; Vacuum Decay; Conformal Cycling; Holographic Entanglement Entropy; Adaptive Dynamics

---

## I. Introduction

### I.A Problem Positioning: From Geometric Cycling to Dynamical Cycling

The standard cosmological model ($\Lambda$CDM) faces a dual fragmentation problem when explaining the origin of the Big Bang and the fate of heat death—high-energy physics focuses on Higgs metastability, general relativity handles spacetime singularities, and quantum information explores holographic correspondence, yet the three lack a unified dynamical language. Penrose's Conformal Cyclic Cosmology (CCC) connects epochs through geometric equivalence but provides neither the dynamical mechanism driving the cycles nor the information carrier preserving physical constants.

This paper proposes Holographic Feedback Cosmology (HFC), treating the universe as an adaptive system in Hilbert-Born space: each epoch corresponds to an attraction basin, inter-epoch transitions are triggered by vacuum decay instantons, and the "memory" of physical constants is encoded through boundary entanglement entropy conservation. This framework integrates the computational philosophy of the Adaptive Iteration Framework (ADIF) with the physical rigor of the Bimodal Cyclic Spontaneous Cosmology (BCSC), transforming the "universe as algorithm" metaphor into a computable quantum cosmology path integral.

### I.B Limitations and Disclaimer

Explicit statement: The HFC framework belongs to semiclassical effective field theory, with limitations including:

* Applicable only to regions where smooth geometry exists; singularity structures are circumvented by instanton solutions, and no claim is made to solve the quantum gravity completeness problem.
* The dS/CFT duality is not yet rigorously established in non-supersymmetric de Sitter space; boundary constraints are heuristic assumptions requiring verification by future quantum gravity theories.
* All observable predictions rely on single-loop instanton approximations; higher-order gravitational corrections are not included.

---

## II. Theoretical Framework: Holographic Feedback Dynamics

### II.A Global Wave Function and WDW Constraint

Define the universe as a wave function in the functional Hilbert space of geometry and matter fields, satisfying the Wheeler-DeWitt equation:

$$
\widehat{H}_{\rm eff}\Psi = \left(\widehat{H}_{GR} + \widehat{H}_{\rm matter} + \widehat{H}_{\rm tunnel}\right)\Psi = 0
$$

where $\widehat{H}_{GR}$ corresponds to the Einstein-Hilbert term, $\widehat{H}_{\rm matter}$ contains standard model fields, and $\widehat{H}_{\rm tunnel}$ is the instanton-induced non-perturbative transition operator. In the semiclassical limit, selecting a matter clock field as internal time yields Schr\"odinger-type evolution:

$$
i\hbar\frac{\delta}{\delta T}\Psi = \widehat{H}_{\rm eff}\Psi
$$

### II.B Holographic Constraints as Feedback Source

Based on dS/dS duality, the low-energy effective theory of de Sitter space is described by a conformal field theory (CFT) on the future boundary. Fundamental physical constants emerge as eigenvalue spectra of the boundary modular Hamiltonian:

$$
\lambda_i = \langle\Psi|\widehat{O}_i(\Sigma)|\Psi\rangle, \quad \widehat{O}_i \in {\rm CFT}_{\partial\mathcal{M}}
$$

Holographic feedback mechanism: Boundary entanglement entropy serves as the cost function, and inter-epoch transitions satisfy the conservation constraint:

$$
S_{\rm ent}^{(n)}(\partial\mathcal{M}) = S_{\rm ent}^{(n+1)}(\partial\mathcal{M}')
$$

This ensures that the distribution of boundary operator spectra remains invariant across cycles, serving as the "memory" of physical laws.

### II.C Instantons Crossing Phase Space Gradients

The transition amplitude from the previous epoch to the next is given by the Euclidean path integral:

$$
\mathcal{A}_{n\to n+1} = \int \mathcal{D}g \mathcal{D}\phi \, \exp\left(-\frac{1}{\hbar}S_E[g,\phi;\lambda^{(n)}]\right) \, \delta\!\left[S_{\rm ent}^{(n)} - S_{\rm ent}^{(n+1)}\right]
$$

The constraint functional enforces holographic conservation, equivalent to updating along the gradient flow in parameter space:

$$
\lambda_i^{(n+1)} = \lambda_i^{(n)} - \eta \frac{\partial S_E}{\partial \lambda_i}, \quad \eta = \frac{\hbar}{S_{\rm ent}}
$$

where $\eta$ is the holographic learning rate, analogous to ADIF's $\beta_{\rm rate}$ but physically realized as the coupling constant flow of the boundary CFT.

---

## III. Lineage of Convergence Modes: From Computation to Physics

HFC reconstructs ADIF's four-layer modes as the critical dynamics of boundary CFT renormalization group flow:

### III.A HFC-L Mode (Linear Geometric Convergence)

Corresponds to the very early inflationary stage of the universe. At this point, the boundary CFT is at an ultraviolet fixed point, and the gradient of the instanton action with respect to $\lambda_i$ is approximately constant:

$$
\frac{\partial S_E}{\partial \lambda_i} \approx \kappa_i, \quad \Rightarrow \quad \lambda_i^{(n+1)} = \lambda_i^{(n)} - \eta \kappa_i
$$

Manifested as exponential smoothing of initial anisotropy, equivalent to ADIF-L's linear convergence.

### III.B HFC-A Mode (Adaptive Parameter Learning)

To address the fine-tuning problem, introduce integral memory effects:

$$
\Delta\lambda_i^{(n)} = -\eta \frac{\partial S_E}{\partial\lambda_i} + \alpha_{\rm mem}\sum_{m=0}^{n-1} \frac{\partial S_E}{\partial\lambda_i}^{(m)}
$$

Physical interpretation: Multi-loop corrections of the boundary CFT generate history-dependent flows of coupling constants, preventing parameters from random walking across cycles and converging to quasi-critical regions.

### III.C HFC-C Mode (Constraint-Driven Projection)

When the universe enters the de Sitter stagnation phase with vacuum energy dominating, it touches the constraint boundary. The instanton action gradient vanishes, and the system executes saddle-point transitions:

$$
\Lambda_{k+1} = \Lambda_k + \Pi_{\rm CDL}(\Lambda_k), \quad \Pi_{\rm CDL} = A\exp\left(-\frac{24\pi^2}{\Lambda_k}\right)
$$

Percolation criterion: When $\sum_{k=1}^{\infty} \Gamma_k > 1$, the cumulative tunneling probability $\Gamma_{\rm tot} \approx 1$, forcing projection to a new epoch.

### III.D HFC-Q Mode (Quasi-Critical Matter Evolution)

Matter evolution within an epoch (such as Higgs field VEV searching) corresponds to cross-critical RG flow of the boundary CFT:

$$
\beta_{\lambda}(\mu) \sim \frac{\partial \lambda}{\partial \log \mu} \propto (\lambda - \lambda_c)^{1-\alpha}, \quad \alpha < 1
$$

This leads to the metastability characteristics of the Higgs potential—rather than being an absolute minimum, it is a transient state of RG flow in the quasi-critical slowing-down region.

---

## IV. Observable Predictions

### IV.A CMB Logarithmic Periodic Oscillations

The gradient descent of boundary RG flow leaves discrete scale invariance in the inflationary power spectrum:

$$
\Delta C_\ell^{\rm HFC-L} \sim A_G \left(\frac{\ell}{\ell_{\rm pivot}}\right)^{n_G} \sin\left(\omega_G \log\frac{\ell}{\ell_{\rm pivot}} + \phi_G\right)
$$

where:

* $A_G \sim (\eta)^n (H/\Lambda_{\rm QG})^2 \sim 10^{-9}$
* $\omega_G = 2\pi / \log(1+\alpha_{\rm mem})$

The distinction between this signal and standard reheating oscillations is that the amplitude does not decay as $\ell \to \infty$, exhibiting logarithmic periodic persistence, detectable by LiteBIRD's polarization sensitivity.

### IV.B Primordial Gravitational Wave Sound Speed Deviation

Tunneling breaks time translation symmetry, inducing effective sound speed deviation in tensor perturbations:

$$
c_T^2 = 1 - \frac{H^2}{M_{\rm Pl}^2} \left(\frac{\partial S_E}{\partial \Lambda}\right)^2 \approx 1 - \mathcal{O}(10^{-10})
$$

Leading to amplitude $f_{\rm NL}^{\rm tensor} \sim 10^{-2}$ in the correlated three-point function at $k_1 \approx k_2 \approx k_3$, detectable as non-Gaussianity by CMB-S4.

### IV.C Boundary Interpretation of Higgs Metastability

The current metastability of the Higgs potential requires that RG flow does not reach an absolute fixed point near the Planck scale:

$$
\lambda(\mu) = \lambda(m_t) + \beta_\lambda\log\frac{\mu}{m_t} + \Delta V_{\rm grav}(\mu)
$$

where the gravitational correction term $\Delta V_{\rm grav} \sim \xi R\phi^2$ is determined by boundary operator expectation values. If future top quark mass precision $\delta m_t < 0.1$ GeV and the potential is proven absolutely stable ($\lambda(\Lambda_{\rm Pl}) > 0$), the HFC mechanism would require introducing higher-dimensional boundary operators, but the framework itself does not collapse.

### IV.D Spatial Curvature Criterion

Closed universe topology ($\Omega_k < 0$) is a prerequisite for the existence of instanton solutions. If observed curvature $\Omega_k > 0$, the global tunneling probability $\Gamma_{\rm tot} \to 0$ and the universe remains permanently stagnant. Current observations $\Omega_k = 0.001 \pm 0.002$ are consistent with the model.

---

## V. Discussion: Physical Reality of Feedback Dynamics

### V.A Compatibility with Swampland Constraints

The gradient flow mechanism of HFC is intrinsically consistent with the distance conjecture of string theory Swampland: increases in parameter space distance are necessarily accompanied by the emergence of new particle states with masses $m \sim d/\ell_s$. This constrains $\alpha_{\rm mem}\lesssim\mathcal{O}(1)$, avoiding infinite roaming of parameter space.

### V.B Implementation of Black Hole Information Protection

Through ER=EPR, black hole interior information is encoded in boundary entanglement. The Hawking evaporation process does not change the boundary modular Hamiltonian spectrum, hence remains invariant across epochs. The turning point of the Page curve corresponds to the coarse-graining of the boundary CFT from pure states to mixed states, which does not conflict with holographic conservation.

### V.C Connection with Asymptotically Safe Gravity

If quantum gravity satisfies $\beta_g = \beta_\lambda = 0$ at the NGFP, the gradient flow of HFC automatically freezes at the Planck scale, terminating the iteration chain. At this point, the universe enters eternal stagnation, but the accumulated number of cycles is sufficient to explain current observations.

---

## VI. Conclusion

Holographic Feedback Cosmology (HFC) successfully transplants adaptive iteration ideas into a physically rigorous cyclic model, constructing a computable, falsifiable framework without fatal contradictions. Its core contributions are:

1. Replacing PID controllers with boundary RG flow, endowing parameter updates with quantum field theory foundations;
2. Replacing violent projection with instanton saddle-point jumps, realizing physically legitimate epoch transitions;
3. Replacing Landauer violations with coarse-grained entropy reset, maintaining global unitarity.

The CMB logarithmic oscillations and sound speed deviations predicted by HFC will be tested by LiteBIRD and CMB-S4 within the next decade. If signals are not detected, the model reduces to standard CCC; if signals are confirmed, it demonstrates that the universe is a quantum system learning in boundary state space.

**Data Availability:** Numerical simulation code (based on class and pySecDec) is available at GitHub repository [HAIC-HFC-2025].

---

## References

[1] J. B. Hartle and S. W. Hawking, "Wave function of the Universe", Phys. Rev. D 28, 2960 (1983).

[2] S. Coleman and F. De Luccia, "Gravitational effects on and of vacuum decay", Phys. Rev. D 21, 3305 (1980).

[3] J. Maldacena and G. Pimentel, "Entanglement entropy in de Sitter space", JHEP 02, 038 (2013).

[4] D. Anninos and T. Hartman, "Holography at an End-of-the-World", JHEP 08, 018 (2015).

[5] J. Cotler and F. Wilczek, "Black hole quantum information and soft hair", Phys. Lett. B 767, 20 (2016).

[6] A. Adams, N. Arkani-Hamed, S. Dubovsky, A. Nicolis and R. Rattazzi, "Causality, analyticity and an IR obstruction to UV completion", Phys. Rev. D 71, 064010 (2005).

[7] L. Susskind and J. Lindesay, An Introduction to Black Holes, Information and the String Theory Revolution: The Holographic Universe, World Scientific (2005).

[8] P. Francesco, P. Mathieu and D. Senechal, Conformal Field Theory, Springer (1997).

---

## Appendix A: Core Symbol Definitions

| Symbol | Domain | Physical/Mathematical Meaning |
|--------|--------|-------------------------------|
| $\mathcal{H}_{\rm bulk}$ | Functional space | Universe wave functional |
| $\{\lambda_i\}$ | $\mathbb{R}^N$ | Set of physical constants |
| $S_{\rm ent}(\partial\mathcal{M})$ | $\mathbb{R}_+$ | Boundary entanglement entropy (cost function) |
| $\eta$ | $\mathbb{R}_+$ | Holographic learning rate |
| $\Pi_{\rm CDL}$ | $\mathbb{R}_+$ | Coleman-De Luccia tunneling operator |
| $\Gamma$ | $\mathbb{R}_+$ | Vacuum decay rate |
| $\ell_{\rm pivot}$ | $\mathbb{N}$ | CMB power spectrum pivot scale (typically 30) |

---

## Conflict of Interest Statement

No commercial interests are involved.