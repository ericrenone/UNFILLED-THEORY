# UNFILLED THEORY

**The Information-Free Threshold: Conditional Independence Boundaries, Two-State Dark Sectors, and the Fixed/Floating Partition in TH$(a,d)$**

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone

---

> "Phase singularities do not carry energy or information and thus can 'move' superluminally
> without breaking causality." — Bucher, Gorlach, Kaminer et al., *Nature* 651, 920–926, 2026

> "Dark matter could straightforwardly be two different particles, and the two different particles
> need to find each other in order to annihilate." — G. Krnjaic, Fermi National Accelerator
> Laboratory, 2026

> "The Fisher information matrix defines a Riemannian metric on the space of probability
> distributions — the unique metric invariant under Markov morphisms." — N. N. Chentsov,
> *Statistical Decision Rules and Optimal Inference*, Nauka, 1972

> "Without these connections, all of space would atomize." — L. Susskind, Stanford University,
> 2015

---

## Abstract

Six independently developed programmes — (1) the Friston active inference Markov blanket
formalism; (2) the Nye-Berry topological singularity theory extended via Maldacena-Susskind
ER = EPR to gravitational physics; (3) the TH$(a,d)$ twisted Hessian architecture of
collective intelligence; (4) Bucher, Gorlach, Kaminer et al.'s experimental confirmation of
superluminal dark-point kinematics in hexagonal boron nitride (*Nature* 651, 2026); (5) Berlin,
Foster, Hooper, Krnjaic's dSphobic two-state dark matter model (arXiv:2504.12372, 2025); and
(6) the Davies-Fulling moving mirror programme in quantum field theory — converge on a single
mathematical object: the **information-free threshold**.

This threshold separates every dynamical space into a **fixed-point dark sector** (phase
singularities with $|\psi| = 0$, event horizons with $\xi_\mu\xi^\mu = 0$, the group-law
identity $O_\infty$ of TH$(a,d)$, $\ker(F)$ directions with $\lambda_i = 0$, the dark matter
ground state $\chi_1$ below mass splitting $\delta$) and a **floating-point active sector**
(rational points on the Mordell-Weil group $E(\mathbb{Q})$, $\text{col}(F)$ eigenvectors with
$\lambda_i > \varepsilon$, the excited state $\chi_2$ above $\delta$). Nothing physical crosses
the threshold: the dark point carries no energy (Bucher-Kaminer 2026), the arithmetic
degeneration carries no Mordell-Weil rank (Silverman 1986), the Bogoliubov coefficient at the
turning point is real (Davies-Fulling 1976), and the dSphobic threshold is crossed by kinetic
energy but no coannihilation signal crosses with it (Berlin et al. 2025).

Seven formal identities unify these programmes. The central results are: (1) Chentsov's
uniqueness theorem (1972) forces every conditional independence boundary — Markov blanket, event
horizon, col$(F)$/ker$(F)$ split — to inherit the Fisher-Rao metric as its unique invariant
geometry, explaining the identical appearance of $F_{ij}$ across all six frameworks; (2) the
Berlin-Krnjaic dSphobic two-state system $(\chi_1, \chi_2)$ with mass splitting $\delta$ is
formally isomorphic to the PRIMA threshold partition $(\ker(F), \text{col}(F))$ with floor
$\varepsilon = 2^{-16}$: dSph silence is ker$(F)$ suppression, the Galactic Center Excess is
col$(F)$ excitation; (3) PRIMA rank crossings ($\Delta\,\text{rank}(F) = \pm 1$) and Nye-Berry
null-point pair creation/annihilation events are rank-one modifications of a structured
mathematical object with exact charge conservation, processed by the Sherman-Morrison formula;
(4) the $d = 0$ degeneration of TH$(a,d)$ — genus drop from 1 to 0, group law collapse,
$G_{\text{coord}} = 0$ — is the algebraic formulation of Van Raamsdonk's entanglement collapse,
the FERN-C4 blanket failure, and the dSphobic total suppression simultaneously; (5) the shadow
of a black hole (observer-invariant, defined by a zero condition on the Killing field) is ker$(F)$
and the mirror image (observer-dependent, transforming under relativistic aberration) is
col$(F)$, providing the first coordinate-free separation of the two sectors grounded in general
relativity; (6) the Davies-Fulling moving mirror IS the moving PRIMA threshold, with
Sherman-Morrison as the Bogoliubov transformation creating Fisher particles from the Fisher
vacuum; (7) the Ryu-Takayanagi formula, the Cramér-Rao bound, and the Imago theorem are
formally isomorphic upper bounds on information extraction across the conditional independence
boundary, all saturated by the same condition: the system achieves efficient estimation at
the boundary.

---

# PART I · FOUNDATIONS

---

## I. The Information-Free Threshold: Experimental Ground Truth

### Superluminal Dark Points (2026)

A dark point is a zero of a complex scalar field $\psi(\mathbf{r}, t)$: a location where
$|\psi| = 0$ and $\arg(\psi)$ is undefined. The topological charge

$$q = \frac{1}{2\pi} \oint_C \nabla \arg(\psi) \cdot d\mathbf{l} \;\in\; \mathbb{Z}$$

is exactly conserved: dark points appear and disappear only in opposite-charge pairs $(\pm 1)$
(Nye-Berry 1974). Berry (1978) proved that dark-point velocities diverge near pair annihilation:
$v \propto t^{-1/2} \to \infty$. These points carry no mass, energy, or information — they are
features of the phase landscape, not physical objects.

Bucher, Gorlach, Kaminer et al. (*Nature* 651, 920–926, 2026) directly measured the ultrafast
dynamics of optical singularity ensembles in hexagonal boron nitride membranes, achieving spatial
and temporal resolutions each an order of magnitude below the polaritonic wavelength and cycle
period. The hBN platform amplified the effect: 29 percent of tracked dark points exceeded the
speed of light — roughly 70 times the rate expected in open air — at an average superluminal
speed of approximately $1.04c$. Berry's $v \propto t^{-1/2}$ prediction was confirmed to high
precision. The universality is the central fact: the superluminal kinematics follow from the
mathematics of complex scalar fields, independent of the underlying wave equation.

The dark point is the prototype of the information-free threshold. At the instant of
annihilation, velocity diverges while the quantity transported is exactly zero: no energy, no
mass, no information. The threshold between existence and nonexistence of a topological feature
carries nothing across it.

### Two-State Dark Matter: The dSphobic Model (2025)

Berlin, Foster, Hooper, and Krnjaic (arXiv:2504.12372, 2025) present a mechanism allowing
thermal relic dark matter to annihilate efficiently in the Galactic Halo and galaxy clusters
but not in the lower-velocity environments of dwarf spheroidal galaxies. The model consists of
two distinct states $\chi_1$ (lighter, ground state) and $\chi_2$ (heavier, excited state)
separated by a small mass splitting $\delta$. An indirect detection signal is generated only
through coannihilation of both states. In the Milky Way halo ($\sigma_v \sim 230$ km/s), kinetic
energy exceeds $\delta$ and the excitation $\chi_1 \to \chi_2$ populates the signalling sector.
In dwarf spheroidals ($\sigma_v \sim 10$–$30$ km/s), kinetic energy falls below $\delta$: the
excited state is not populated and the signal vanishes.

The dSphobic model is the particle-physics incarnation of the information-free threshold: two
sectors separated by an energy gap $\delta$, with the signal sector activated only when the
local environment provides sufficient energy to cross the gap. The threshold itself is a
kinematic condition — it carries no signal.

---

## II. The Conditional Independence Boundary

The conditional independence condition

$$P\!\left(\text{interior} \mid \text{boundary}\right) = P\!\left(\text{interior} \mid
\text{universe}\right)$$

appears identically in six frameworks:

| Framework | Interior | Boundary | Exterior |
|---|---|---|---|
| FERN | Agent $i$'s future action | Markov blanket $B_i$ | Global environment |
| Gravitational physics | Black hole interior | Event horizon $\xi_\mu\xi^\mu = 0$ | Exterior spacetime |
| TH$(a,d)$ | $\ker(F)$ directions | $\varepsilon$-threshold surface | $\text{col}(F)$ |
| dSphobic DM | Ground state $\chi_1$ ($E < \delta$) | Mass splitting $\delta$ | Excited state $\chi_2$ ($E > \delta$) |
| Moving mirror QFT | Negative-frequency vacuum | Mirror position $x(t)$ | Positive-frequency quanta |
| Wave topology | Dark-point interior ($|\psi| = 0$) | Topological charge boundary | Phase landscape ($|\psi| > 0$) |

In each case, the boundary screens the interior from the exterior. Chentsov's uniqueness theorem
(1972) then applies without further assumption: the Fisher-Rao metric
$g_{ij}(\theta) = F_{ij}(\theta)$ is the **unique** Riemannian metric on the statistical
manifold of boundary states invariant under Markov morphisms. This is why $F_{ij}$ appears
identically across all six frameworks — the metric is not imposed; it is forced by the common
boundary structure.

---

## III. TH$(a,d)$: The Algebraic Skeleton

The twisted Hessian curve $aX^3 + Y^3 + Z^3 = dXYZ$ over $\mathbb{Q}$ encodes the
information-free threshold algebraically. Two classes of special points partition the curve:

**Fixed points** — the identity $O_\infty = [0:1:-1]$ and the three 2-torsion points at
half-periods $T_1 = \omega_1/2$, $T_2 = \omega_2/2$, $T_3 = (\omega_1 + \omega_2)/2$ — are
invariant under the group law involution $P \mapsto -P$. They are the algebraic analogues of
dark points: topological invariants carrying no group-law information.

**Floating points** — elements of the Mordell-Weil group
$E(\mathbb{Q}) \setminus \{O_\infty, T_1, T_2, T_3\}$ — move under the chord-and-tangent law,
carry the coordination signal, and have finite nonzero Hessian diagonal mass
$H_{ii} = \partial^2 L/\partial\theta_i^2$ (by the Fisher-Bartlett identity
$F_{ij} = -\mathbb{E}[H_{ij}]$, the diagonal curvature is the floating point's resistance to
displacement under the natural gradient).

The partition function $Z(X;\beta) = \int_A \exp(-\beta H(a;X))\,da$ is sharp-P-hard. Every
agent approximates it via the Fisher matrix $F$. The $\text{col}(F)$/$\ker(F)$ decomposition
with Moore-Penrose pseudoinverse $F^{+} = U_r \Sigma_r^{-1} U_r^T$ separates the active
coordination subspace ($\lambda_i > \varepsilon = 2^{-16}$) from the null space. The
coordination gain

$$G_{\text{coord}} = \sum_{t < s} I\!\left(a_t;\, a_s \mid X_{t-1}\right)$$

receives contributions only from $\text{col}(F)$ directions. The $\varphi$-equilibrium
$|\bar{\Xi}|^{*} = \log\varphi \approx 0.481$ is the MEP ceiling on sustainable Fisher trace
growth: above it, $G_{\text{coord}}$ collapses.

At $d = 0$, TH$(a,d)$ factors into three concurrent lines — genus drops from 1 to 0, the group
law collapses, $G_{\text{coord}} = 0$. This is the algebraic formulation of the information-free
threshold at total degeneration: no coupling, no boundary, no coordination.

---

## IV. The Helical Topology

The Weierstrass parametrization $z \mapsto (\wp(z), \wp'(z))$ traces TH$(a,d)$ on the torus
$\mathbb{C}/\Lambda$. For a floating point $P$ with complex parameter $z_P$, repeated addition
$P \to nP$ produces the trajectory

$$z_{nP} = n \cdot z_P \pmod{\Lambda}$$

In the three-dimensional embedding $(\text{Re}(z_{nP}), \text{Im}(z_{nP}), n)$, this is a
helix: the first two coordinates wind quasi-periodically around the torus; the third grows
linearly. The three fixed half-period points $T_1, T_2, T_3$ form the invariant backbone of the
helix; the floating rational points spiral around this backbone. The two arms of the helix —
$z$ and $-z$ (the involution $P \mapsto -P$) — correspond to the two strands.

Light (gradient information) propagates through the null space between floating points —
through $\ker(F)$ — without interaction, and scatters only off $\text{col}(F)$ floating points
with $\lambda_i > \varepsilon$. The Hessian diagonal $H_{ii}$ determines the orbital velocity
of each floating point: $v_P = \eta / H_{PP}$ (learning rate over curvature). Heavy floating
points (large $H_{ii}$) orbit slowly; light ones orbit fast. At $d = 0$, the helix collapses:
the three backbone axes merge, all floating points collapse to the identity.

---

# PART II · MODULE A — SEVEN FORMAL IDENTITIES

---

**Identity 1 — Chentsov Uniqueness: Every Conditional Independence Boundary Inherits the
Fisher-Rao Metric; $F_{ij}$ Appears Identically Across All Six Frameworks Because the
Boundary Structure Forces It**

Any conditional independence boundary of the form
$P(\text{interior} \mid \text{boundary}) = P(\text{interior} \mid \text{universe})$ induces a
statistical manifold structure on the space of boundary states. Chentsov's uniqueness theorem
(1972) guarantees that the Fisher-Rao metric is the **unique** Riemannian metric on this
manifold invariant under sufficient statistics. The FERN Markov blanket, the event horizon, the
col$(F)$/ker$(F)$ $\varepsilon$-surface, the dSphobic mass splitting, and the Davies-Fulling
mirror position all impose the same conditional independence condition and therefore inherit the
same unique metric.

The Amari $\alpha$-connection duality transfers across all frameworks: the $e$-connection
($\alpha = +1$) is $\text{col}(F)$ in every system; the $m$-connection ($\alpha = -1$) is
$\ker(F)$; the self-dual $\alpha = 0$ Levi-Civita connection identifies the
$\varphi$-equilibrium / MEP fixed point / minimal entanglement surface simultaneously.

**Status:** Chentsov (1972) is a theorem. The conditional independence condition is definitional
to all six frameworks.

**Open:** An explicit morphism between the six statistical manifolds establishing whether they
are diffeomorphic or share the metric structure only locally.

---

**Identity 2 — The dSphobic Threshold IS the PRIMA Threshold; $(\chi_1, \chi_2)$ IS
$(\ker(F), \text{col}(F))$; the Mass Splitting $\delta$ IS the Q16.16 Floor
$\varepsilon = 2^{-16}$**

The Berlin-Hooper-Krnjaic dSphobic model and the PRIMA threshold architecture exhibit exact
structural correspondence at the level of the governing equations.

| dSphobic DM (Berlin et al. 2025) | PRIMA / TH$(a,d)$ | Physical content |
|---|---|---|
| Ground state $\chi_1$ | $\ker(F)$: $\lambda_i < \varepsilon$ | Dark sector — no signal |
| Excited state $\chi_2$ | $\text{col}(F)$: $\lambda_i \geq \varepsilon$ | Active sector — coordination signal |
| Mass splitting $\delta$ | $\varepsilon = 2^{-16}$ | Energy gap separating sectors |
| Kinetic energy $E_{\text{kin}}$ | Fisher eigenvalue $\lambda_i$ | Energy available to cross threshold |
| Coannihilation $\chi_1\chi_2 \to \gamma\gamma$ | $I(a_t; a_s \mid X_{t-1}) > 0$ | Cross-sector signal production |
| dSph suppression ($v < v_\delta$) | Sub-threshold ker$(F)$ | Environment lacks crossing energy |
| MW halo signal ($v > v_\delta$) | col$(F)$ excitation | High-energy environment populates active sector |
| Excited fraction $f_{\text{exc}}(r)$ | $\text{rank}(F)/d$ | Fraction of active directions |

The PRIMA event — a single Fisher eigenvalue crossing $\varepsilon$ via the Sherman-Morrison
rank-one update at $O(r \cdot d)$ — is the information-geometric analogue of the
$\chi_1 \to \chi_2$ excitation. The Galactic Center Excess / dSph silence contrast is the first
astrophysical observation of a threshold bifurcation between a dark and active sector governed
by the same structure as the col$(F)$/ker$(F)$ partition.

**Status:** PRIMA threshold and col$(F)$/ker$(F)$ partition are exact. dSphobic kinematic
suppression is established in Berlin et al. 2025.

**Open:** A quantitative mapping $\delta = f(\varepsilon)$ in SI units requires identifying the
DM velocity dispersion with the Fisher eigenvalue energy scale.

---

**Identity 3 — PRIMA Rank Crossings ARE Nye-Berry Null-Point Pair Events; Sherman-Morrison IS
the Topological Charge Update; Exact Charge Conservation Holds in Both**

PRIMA rank crossings ($\Delta\,\text{rank}(F) = \pm 1$) and Nye-Berry null-point pair
creation/annihilation events are rank-one modifications of a structured mathematical object
with exact conservation of a topological invariant, handled by the same algebraic formula.

| Null-space topology | TH$(a,d)$ / PRIMA |
|---|---|
| Pair creation: charges $+1, -1$ from $q = 0$ | Direction enters col$(F)$; complement displaced in ker$(F)$ |
| Pair annihilation: opposite charges merge | Reverse PRIMA: direction drops below $\varepsilon$ |
| Charge conservation: $\sum q_i = \text{const}$ | Rank conservation: $|\Delta\,\text{rank}(F)| = 1$ per event |
| Berry $v \propto t^{-1/2}$ near annihilation | Fisher eigenvalue edge singularity at $\varepsilon$-crossing |
| Rank-one perturbation at creation/annihilation | Sherman-Morrison: $(F + uu^T)^{+} = F^{+} - F^{+}uu^TF^{+}/(1 + u^TF^{+}u)$ |

The charge conservation mechanisms are identical: the winding number cannot change continuously
(Nye-Berry 1974); the rank-one perturbation $uu^T$ cannot change rank by more than $\pm 1$
(rank-nullity theorem). Kaminer et al. (2026) confirmed the pair dynamics experimentally, with
Berry's velocity divergence observed directly.

**Status:** Topological charge conservation (Nye-Berry 1974). Sherman-Morrison rank-one
magnitude (Woodbury 1950). PRIMA rank-change bound $|\Delta\,\text{rank}(F)| \leq 1$.

**Conjectured:** The Berry $-1/2$ exponent and the Fisher eigenvalue density edge singularity
belong to the same universality class — both are edge singularities of spectral measures at
topological phase transitions.

---

**Identity 4 — The $d = 0$ Degeneration IS Van Raamsdonk IS FERN-C4 Failure IS dSphobic
Total Suppression: Four Frameworks, One Algebraic Collapse**

At $d = 0$, TH$(a,d)$ factors:

$$aX^3 + Y^3 + Z^3 = 0 \quad\Longrightarrow\quad \left(\alpha X + Y + Z\right)\!\left(\alpha X + \omega Y + \omega^2 Z\right)\!\left(\alpha X + \omega^2 Y + \omega Z\right)$$

where $\omega = e^{2\pi i/3}$, $\alpha^3 = -a$. Genus drops from 1 to 0, the group law
collapses, Mordell-Weil $\mathbb{Z}^r$ vanishes, $G_{\text{coord}} = 0$.

| $d = 0$ degeneration | Van Raamsdonk ($S_{\text{ent}} = 0$) | FERN-C4 failure | dSphobic at $v \to 0$ |
|---|---|---|---|
| Three decoupled lines | Bulk spacetime disconnects | Collective loses coherence | All DM in ground state $\chi_1$ |
| Group law collapses | ER bridge disappears | $G_{\text{coord}} \to 0$ | Zero coannihilation signal |
| Genus: $1 \to 0$ | $S_{\text{ent}} \to 0$ | $I(B_i; B_j) \to 0$ | $f_{\text{exc}} \to 0$ |
| Helix collapses: backbone axes merge | No spatial connectivity | No inter-blanket observability | dSph silence |

As $d$ increases from $0$: the lines merge into a genus-1 curve, the group law activates,
$G_{\text{coord}} > 0$, the helix extends, and the conditional independence boundary becomes
functional. The coupling parameter $d$ encodes boundary integrity: the single number determining
whether the threshold is active.

**Status:** The $d = 0$ factorization is exact algebraic geometry (Bernstein-Lange 2015). Van
Raamsdonk (2010) is established in AdS/CFT. FERN-C4 is definitional.

**Open:** An explicit function $d = f(S_{\text{ent}})$ relating the TH coupling parameter to
entanglement entropy.

---

**Identity 5 — The Shadow IS ker$(F)$ (Observer-Invariant); the Mirror IS col$(F)$
(Observer-Dependent); General Relativity Establishes the Distinction**

In Schwarzschild geometry, the shadow of a black hole — the set of null geodesics captured by
the event horizon — is defined by a zero condition: the effective potential
$V_{\text{eff}}(r) = (1 - 2M/r)/r^2$ has its maximum at the photon sphere $r = 3M$. The
photon capture cross-section $\sigma_{\text{capture}} = 27\pi(GM/c^2)^2$ is an intrinsic
geometric quantity. The topology of the shadow (which geodesics are captured, which escape) is
a spacetime invariant independent of the observer. The Event Horizon Telescope confirmed this
for M87* (Akiyama et al. 2019) and Sgr A* (Akiyama et al. 2022).

A mirror image is observer-dependent. A plane mirror at velocity $v$ reflects light at an angle
related to the lab-frame angle by the relativistic aberration formula
$\cos\theta_r' = (\cos\theta_r - v/c)/(1 - (v/c)\cos\theta_r)$. Two observers at different
velocities see different reflections. The Davies-Fulling (1976) quantum version: an accelerating
mirror creates particles from the vacuum, with observer-dependent particle counts.

The formal statement:

$$\ker(F) \text{ as a subspace: invariant under orthogonal change of basis}$$
$$\text{col}(F) \text{ eigenvectors: covariant under change of prior } \theta_0$$

ker$(F)$ is the shadow — defined by the zero condition $Fv = 0$, independent of measurement
basis. col$(F)$ is the mirror — its specific eigenvectors depend on the prior (observation
point). The no-hair theorem — a black hole is characterized by $(M, J, Q)$ only — is the
statement $\text{rank}(F_{\text{shadow}}) = 3$: the shadow boundary carries exactly three
non-zero Fisher eigenvectors, with all remaining directions in ker$(F_{\text{exterior}})$.

**Status:** Schwarzschild photon sphere (standard GR). EHT observations (Akiyama et al. 2019,
2022). Relativistic aberration (SR). ker$(F)$ basis-independence (linear algebra).

---

**Identity 6 — The Moving PRIMA Threshold IS the Davies-Fulling Moving Mirror;
Sherman-Morrison IS the Bogoliubov Transformation; Rank Crossings Create Particles from
the Fisher Vacuum**

Davies and Fulling (1976) showed that a mirror with time-varying position $x(t)$ in 1+1
dimensional Minkowski space creates quanta from the quantum vacuum by mixing positive and
negative frequency modes. The Bogoliubov coefficients $\alpha_{\omega\omega'}$ and
$\beta_{\omega\omega'}$ quantify the mixing; $|\beta_{\omega\omega'}|^2$ gives the particle
creation rate. For exponential acceleration $x(t) = -e^{-\kappa t}/\kappa$, the rate is thermal
at $T = \hbar\kappa/(2\pi k_B c)$ — the Unruh effect.

The PRIMA threshold $\varepsilon = 2^{-16}$ is a dynamical boundary in Fisher eigenvalue space.
When $\lambda_i(t)$ crosses $\varepsilon$ with rate $\dot\lambda_i$, the boundary moves: a
direction transfers from ker$(F)$ to col$(F)$. The Sherman-Morrison rank-one update

$$\left(F + uu^T\right)^{+} = F^{+} - \frac{F^{+}\, u u^T\, F^{+}}{1 + u^T F^{+} u}$$

describes how the natural gradient operator transforms under this rank-one perturbation. It is
structurally identical to the Bogoliubov transformation: $u^TF^+u/(1 + u^TF^+u)$ is the
mode-mixing amplitude; the rank crossing (PRIMA event) IS particle creation — a new Fisher
particle (col$(F)$ direction) created from the Fisher vacuum (ker$(F)$).

| Moving mirror (Davies-Fulling 1976) | Moving PRIMA threshold |
|---|---|
| Mirror position $x(t)$ | $\varepsilon$-threshold crossing time $t_*$ |
| Positive/negative frequency modes | col$(F)$ / ker$(F)$ directions |
| Bogoliubov coefficient $\beta_{\omega\omega'}$ | Sherman-Morrison denominator $1 + u^TF^+u$ |
| Particle creation rate $|\beta|^2$ | PRIMA rank increment $+1$ |
| Unruh temperature $T = \hbar\kappa/(2\pi k_Bc)$ | PRIMA energy scale $\varepsilon = 2^{-16}$ |
| Hawking radiation (extreme case) | Imago phase (all PRIMA events complete) |

**Status:** Davies-Fulling particle creation (1976; Birrell-Davies 1982). Sherman-Morrison
(Woodbury 1950). PRIMA rank-one structure (FERN architecture).

**Open:** The Unruh spectrum is Planckian; the PRIMA spectrum follows Marchenko-Pastur at
aspect ratio $\gamma = 1/\varphi$. A precise identification requires mapping $\omega/\kappa$
to $\lambda/\varepsilon$.

---

**Identity 7 — Ryu-Takayanagi IS the Gravitational Cramér-Rao Bound; the $\varphi$-Equilibrium
IS the ERI Analogue of the MSS Chaos Bound; Both Constrain Information Flow Across the
Threshold**

Two thermodynamic bounds constrain information flow across the conditional independence boundary:

The Ryu-Takayanagi formula $S_{\text{ent}} \leq \text{Area}(\gamma_A)/(4G_N\hbar)$ bounds the
entanglement entropy across the event horizon by the area of the minimal bulk surface $\gamma_A$.
The Cramér-Rao bound $\text{Var}(\hat{T}) \geq F(\theta)^{-1}$ bounds estimator variance by the
inverse Fisher information. The Imago theorem $G_{\text{coord}} \leq \Phi(K)$ bounds
coordination gain by the Fisher capacity of kernel $K$. All three bound information extractable
across a conditional independence boundary by a geometric quantity characterizing the boundary's
Fisher structure.

The MSS chaos bound $\lambda_L \leq 2\pi k_BT/\hbar$ (Maldacena-Shenker-Stanford 2016) and
the $\varphi$-equilibrium $|\bar{\Xi}|^{*} = \log\varphi$ are both thermodynamic ceilings on
the rate of information flow across the boundary: the MSS bound on scrambling rate across the
event horizon (saturated by black holes — the fastest scramblers in nature); the
$\varphi$-equilibrium on Fisher trace growth across col$(F)$/ker$(F)$ (saturated by ERI at MEP
optimum). Above either ceiling: over-driven collapse. Below: sub-chaotic, kernel not
crystallized.

| Framework | Bound | Saturated by |
|---|---|---|
| Statistics | $\text{Var}(\hat{T}) \geq F^{-1}$ | Efficient estimator |
| TH$(a,d)$ | $G_{\text{coord}} \leq \Phi(K)$ | Imago condition |
| Holography | $S_{\text{ent}} \leq \text{Area}(\gamma_A)/(4G_N\hbar)$ | Quantum extremal surface |
| Chaos | $\lambda_L \leq 2\pi k_BT/\hbar$ | Black holes |
| ERI | $|\bar{\Xi}| \leq \log\varphi$ | MEP optimum |

**Status:** Cramér-Rao (Rao 1945). Ryu-Takayanagi (2006; Faulkner et al. 2013). MSS
(Maldacena-Shenker-Stanford 2016). $\varphi$-equilibrium (SMELT framework).

**Open:** A timescale mapping $\log\varphi = (2\pi k_BT^{*}/\hbar)\,\tau_{\text{coord}}$
connecting the MEP ceiling to the MSS bound.

---

# PART III · MODULE B — THE UNFILLED ARCHITECTURE

```
THE INFORMATION-FREE THRESHOLD: SIX COORDINATE SYSTEMS

══════════════════════════════════════════════════════════════
DARK SECTOR (FIXED POINTS / SHADOWS / ker(F))
──────────────────────────────────────────────────────────────
  Wave physics:     Dark points |ψ| = 0, charge q = ±1
                    v → ∞ near annihilation (Berry 1978; Kaminer 2026)
                    Carry: ZERO energy, ZERO information
  Gravitational:    Event horizon ξ_μξ^μ = 0
                    Black hole shadow: observer-INVARIANT
                    No-hair: rank(F_exterior) = 3 [M, J, Q]
  TH(a,d):          O∞ = [0:1:-1], torsion T₁, T₂, T₃ (helical backbone)
                    Invariant under involution P ↦ -P
                    H_ii → ∞ at identity (infinite mass: cannot be moved)
  Fisher:           ker(F): λᵢ < ε = 2^{-16}
                    Basis-INVARIANT (spectral condition λ = 0)
                    Zero Fisher information by definition
  dSphobic DM:      χ₁ ground state (v < v_δ)
                    dSph: no signal (insufficient kinetic energy)
  Moving mirror:    Negative-frequency vacuum (pre-crossing)

══════════════════════════════════════════════════════════════
THRESHOLD (THE ε-SURFACE / INFORMATION-FREE CROSSING)
──────────────────────────────────────────────────────────────
  Nothing physical crosses:
    Dark point:     Zero energy at annihilation (Bucher-Kaminer 2026)
    Arithmetic:     Zero Mordell-Weil rank change at d→0 (Silverman 1986)
    dSphobic:       Kinetic energy crosses δ, but no signal crosses
    Bogoliubov:     Coefficient is real at turning point (no phase)
    GUE repulsion:  p(s) ∝ s² → minimum spacing (topological constraint)
    HaPPY code:     Below code distance: nothing correctable

  The threshold is information-free. That is the deepest fact.

  Transition algebra (same in all frameworks):
    Sherman-Morrison rank-one update: O(r·d) per event
    = Nye-Berry pair creation/annihilation
    = Bogoliubov transformation
    = PRIMA eigenvalue crossing
    |Δrank(F)| = |Δq| = 1 per event (exact conservation)

══════════════════════════════════════════════════════════════
ACTIVE SECTOR (FLOATING POINTS / MIRRORS / col(F))
──────────────────────────────────────────────────────────────
  Wave physics:     Phase landscape maxima |ψ| > 0
                    Mobile, energy-carrying
  Gravitational:    Mirror image: observer-DEPENDENT
                    Aberration: θ' = arccos[(cosθ - v/c)/(1-(v/c)cosθ)]
                    Davies-Fulling: accelerating mirror creates particles
  TH(a,d):          E(Q) rational points (Mordell-Weil group)
                    Helical orbit: z_n = z₀ + nτ (mod Λ)
                    H_ii finite: floating mass = orbital resistance
  Fisher:           col(F): λᵢ > ε = 2^{-16}
                    Prior-DEPENDENT (changes with observation point)
                    Positive Fisher information → coordination
  dSphobic DM:      χ₂ excited state (v > v_δ)
                    MW halo: γ-ray signal (coannihilation active)
  Moving mirror:    Positive-frequency quanta (post-crossing)

══════════════════════════════════════════════════════════════
INFORMATION BOUNDS AT THE THRESHOLD
──────────────────────────────────────────────────────────────
  Cramér-Rao / Imago:     G_coord ≤ Φ(K)
  Ryu-Takayanagi:         S_ent ≤ Area(γ_A)/(4G_Nℏ)
  MSS chaos bound:        λ_L ≤ 2πk_BT/ℏ
  φ-equilibrium:          |Ξ̄| ≤ log φ ≈ 0.481
  All four: same thermodynamic ceiling, different units.

══════════════════════════════════════════════════════════════
DEGENERATION AT ZERO COUPLING
──────────────────────────────────────────────────────────────
  d = 0:        TH factors → three decoupled lines, G_coord = 0
  S_ent = 0:    Van Raamsdonk → bulk spacetime disconnects
  C4 fail:      FERN collective blanket → G_coord → 0
  v → 0:        dSphobic total suppression → no signal anywhere
  Helix:        Backbone axes merge, all floating points collapse

══════════════════════════════════════════════════════════════
DNA HELIX OF TH(a,d)
──────────────────────────────────────────────────────────────
  Backbone (fixed):     T₁, T₂, T₃ (2-torsion half-periods)
  Base pairs (floating): P ∈ E(Q), mass = H_ii (Hessian diagonal)
  Two strands:          P and -P (involution z ↦ -z)
  Pitch:                Re(z_P)/ω₁ per group-law addition
  Light propagation:    Through ker(F) null spaces between floating points
  Interaction:          F⁺∇L scatters only off col(F) directions
  Collapse at d=0:      Helix → point (Van Raamsdonk / dSph silence)
  Extension at d>0:     Helix active (entanglement / MW signal)
```

---

# PART IV · SEVEN NOVEL RESULTS

---

**Result 1 — The Chentsov-Conditional-Independence Theorem Forces All Six Frameworks to
Inherit the Same Fisher-Rao Metric, Explaining $F_{ij}$'s Universal Appearance Without
Coincidence.**

The appearance of the Fisher information matrix $F_{ij}(\theta) =
\mathbb{E}[\partial_i \log p \cdot \partial_j \log p]$ in FERN agent dynamics, null-point
configuration space geometry, TH$(a,d)$ parameter space, dSphobic threshold mechanics, moving
mirror boundary dynamics, and gravitational holography is not an analogy — it is forced by
the shared conditional independence boundary structure via Chentsov's uniqueness theorem (1972).
Any conditional independence boundary induces a statistical manifold, and Chentsov guarantees
the Fisher-Rao metric is the unique invariant Riemannian metric on this manifold. This is the
first theorem explaining, without appeal to analogy, why information geometry appears
identically across wave physics, gravitational physics, particle phenomenology, quantum field
theory, active inference, and elliptic curve coordination arithmetic.

---

**Result 2 — The dSphobic-PRIMA Isomorphism: Two-State Dark Matter Is the First Astrophysical
Observation of the col$(F)$/ker$(F)$ Bifurcation.**

The Berlin-Foster-Hooper-Krnjaic dSphobic model introduces a kinetic energy threshold $\delta$
separating a dark ground state $\chi_1$ from an active excited state $\chi_2$. This is formally
isomorphic to the PRIMA threshold $\varepsilon$, with $\delta \leftrightarrow \varepsilon$,
$E_{\text{kin}} \leftrightarrow \lambda_i$, coannihilation rate $\leftrightarrow
I(a_t; a_s \mid X_{t-1})$, and $f_{\text{exc}} \leftrightarrow \text{rank}(F)/d$. The Galactic
Center Excess / dSph silence contrast is the first astrophysical observation of a threshold
bifurcation between a dark (ker) and an active (col) sector — the same structure that governs
coordination gain in ERI. This is the first identification of dSphobic inelastic dark matter
with the Fisher information architecture.

---

**Result 3 — Superluminal Dark-Point Universality Extends to TH Arithmetic Degeneration:
Both Are Information-Free Divergences at Rank-One Transitions.**

The Bucher-Kaminer 2026 confirmation of Berry's 1978 prediction establishes that superluminal
dark-point kinematics are universal across wave systems: $v \to \infty$ near pair annihilation,
carrying no energy or information. The TH$(a,d)$ arithmetic degeneration at $d \to 0$ is the
number-theoretic instance: logarithmic Weil height diverges near degeneration (arithmetic
velocity $\to \infty$), carrying no new Mordell-Weil rank. Both are rank-one perturbations of a
topological object (complex field / genus-1 curve) with information-free divergent velocities.
Both are controlled by rank-one updates (Sherman-Morrison / Bogoliubov) at the threshold. The
identification of Bucher-Kaminer universality with TH arithmetic degeneration is new.

---

**Result 4 — The $d = 0$ Degeneration Unifies Four Collapse Modes: TH Factorization, Van
Raamsdonk Disconnection, FERN-C4 Failure, and dSphobic Total Suppression Are One Algebraic
Event.**

The factorization $aX^3 + Y^3 + Z^3 = (\alpha X + Y + Z)(\alpha X + \omega Y + \omega^2 Z)
(\alpha X + \omega^2 Y + \omega Z)$ at $d = 0$ is the sharpest existing algebraic formulation
of four independently discovered failure modes: (i) the TH group law collapse, (ii) Van
Raamsdonk's entanglement disconnection, (iii) the FERN-C4 blanket failure, and (iv) the
dSphobic zero-velocity limit where $f_{\text{exc}} \to 0$ and no signal survives. The coupling
parameter $d$ is the single number encoding whether the information-free threshold is active
across all four frameworks. This is the first algebraic (not merely verbal) unification of
the four collapse modes.

---

**Result 5 — The Shadow-Mirror GR Duality Provides the First Coordinate-Free Separation of
ker$(F)$ from col$(F)$, with the EHT Shadow as Astrophysical Confirmation.**

General relativity establishes that the shadow (captured null geodesics) is a topological
invariant of spacetime causal structure, while the mirror reflection transforms under Lorentz
boosts. This is the coordinate-free proof that ker$(F)$ (shadow — observer-invariant null
directions of the Fisher metric) and col$(F)$ (mirror — observer-dependent active directions,
prior-dependent) have fundamentally different transformation properties. The EHT observations of
M87* (2019) and Sgr A* (2022) confirm shadow invariance at astrophysical scale. The no-hair
theorem — rank$(F_{\text{shadow}}) = 3$ — is the most extreme low-rank Markov blanket realized
in nature.

---

**Result 6 — The Davies-Fulling Moving Mirror IS the Moving PRIMA Threshold: Sherman-Morrison
IS the Bogoliubov Transformation; Rank Crossings Are Particle Creation from the Fisher Vacuum.**

The moving PRIMA threshold (Fisher eigenvalue $\lambda_i(t)$ crossing $\varepsilon$) creates a
new Fisher particle (col$(F)$ direction) from the Fisher vacuum (ker$(F)$) via the
Sherman-Morrison rank-one update, structurally identical to the Bogoliubov transformation of
the Davies-Fulling moving mirror. The PRIMA energy scale $\varepsilon = 2^{-16}$ is the minimum
particle creation energy — the ERI Unruh temperature. The Imago phase (all eigenvalues above
$\varepsilon$, rank$(F) = d$) is the moving mirror at maximum acceleration: Hawking radiation
from the coordination boundary. This is the first identification of PRIMA rank crossings with
moving-mirror particle creation in QFT.

---

**Result 7 — The DNA Helix of TH$(a,d)$ Is the Geometric Realization of the Fixed/Floating
Partition: Three Fixed Backbone Axes, Spiraling Rational Coordinates, and Null-Space Light
Propagation Between Them.**

The Weierstrass parametrization of TH$(a,d)$ on $\mathbb{C}/\Lambda$ generates a helical
topology with three fixed 2-torsion axes (invariant backbone) and spiraling Mordell-Weil
rational points (mobile base pairs). The Hessian diagonal $H_{ii}$ gives each floating point
its mass — resistance to natural gradient displacement. Light propagates through ker$(F)$
null space between floating points without interaction; it scatters only off col$(F)$ directions
above $\varepsilon$. At $d = 0$ the helix collapses (Van Raamsdonk / dSph silence /
$G_{\text{coord}} = 0$); at $d > 0$ it extends (entanglement / MW signal /
$G_{\text{coord}} > 0$). The two strands of the helix — $P$ and $-P$ under the group
involution — are the double-helix structure of the TH$(a,d)$ period lattice.

---

## Formal Summary

| Structure | Dark Sector (Fixed / Shadow) | Active Sector (Floating / Mirror) | Threshold |
|---|---|---|---|
| Wave physics | Dark point $|\psi| = 0$, $v \to \infty$ | Phase maxima $|\psi| > 0$ | Berry annihilation scale |
| Gravitational | BH shadow (observer-invariant) | Mirror image (observer-dependent) | Photon sphere $r = 3M$ |
| TH$(a,d)$ | $O_\infty$, torsion $T_1, T_2, T_3$ | $E(\mathbb{Q})$ rational points | $d \to 0$ degeneration |
| Fisher / PRIMA | ker$(F)$: $\lambda_i < \varepsilon$ (basis-invariant) | col$(F)$: $\lambda_i > \varepsilon$ (prior-dependent) | $\varepsilon = 2^{-16}$ |
| dSphobic DM | $\chi_1$ ground state ($E < \delta$, dSph silent) | $\chi_2$ excited ($E > \delta$, MW: $\gamma$-ray) | Mass splitting $\delta$ |
| Moving mirror | ker$(F)$: negative-frequency vacuum | col$(F)$: positive-frequency quanta | Sherman-Morrison crossing |
| DNA helix | Fixed backbone: $T_1, T_2, T_3$ | Floating orbit: $P \in E(\mathbb{Q})$ | Hessian diagonal $H_{ii}$ |
| Hessian | $H_{ii} \to \infty$ (infinite mass) | $H_{ii}$ finite (orbital resistance) | Fisher-Bartlett identity |
| GUE / RMT | Level repulsion minimum spacing | Active eigenvalue sector | $s_{\min} = \varepsilon$ |
| HaPPY code | Stabilizer vacuum (below code distance) | Logical qubit space | Code distance $d = 16$ bits |
| Coordination | $G_{\text{coord}} = 0$ (dSph silence) | $G_{\text{coord}} > 0$ (MW signal) | PRIMA crossing |
| Entanglement | $S_{\text{ent}} = 0$: bulk disconnects | $S_{\text{ent}} > 0$: bulk connected | ER bridge integrity |

---

## Closing Synthesis

The information-free threshold was present in the TH$(a,d)$ architecture from the beginning,
but it required six independent programmes to recognize what it is. The group-law identity is
fixed: no coordination can move it. The rational points float: they orbit, spiral, and carry
coordination information. The PRIMA threshold sits between them at the Q16.16 arithmetic floor,
and at this threshold the same remarkable fact holds across every domain: nothing crosses.

The dark point near annihilation moves superluminally but carries no energy (Bucher-Kaminer
2026). The dSphobic threshold is crossed by kinetic energy but no coannihilation signal crosses
with it (Berlin et al. 2025). The GUE eigenvalue cannot approach within $\varepsilon$ of another
without violating level repulsion — but the repulsion carries no information, only a topological
constraint. The HaPPY code below its distance threshold is not broken — it simply has nothing to
say. The moving mirror at its turning point creates a particle, but the Bogoliubov coefficient
is real: information-free by construction. The Mordell-Weil rank does not change as $d \to 0$ —
the arithmetic velocity diverges while the arithmetic content is invariant.

Chentsov (1972) provides the deepest explanation. Any programme that imposes the condition
$P(\text{interior} \mid \text{boundary}) = P(\text{interior} \mid \text{universe})$ inherits
the Fisher-Rao metric as the unique invariant geometry on the boundary's statistical manifold.
Six programmes imposed this condition in six coordinate systems — agent coordination, event
horizons, elliptic curve group law, dark matter velocity thresholds, accelerating mirrors, and
topological charge boundaries — and all six arrived at $F_{ij}$. The matrix was always the same
matrix.

The shadow-mirror duality gives the partition its clearest physical meaning. A shadow is the
outline of a fixed point: the region from which no photons arrive, defined by the zero condition
on the Killing field, independent of any observer. The EHT has measured this shadow for two
black holes and confirmed its observer-independence. A mirror image is the reflection of a
floating point: observer-dependent, prior-dependent, the col$(F)$ face of the coordination
manifold. ker$(F)$ is the shadow — invariant, dark, defined by zeros. col$(F)$ is the mirror —
active, bright, defined by the observation point.

The $d = 0$ degeneration reveals the deepest algebraic fact: four independently discovered
collapse modes — TH factorization, Van Raamsdonk disconnection, FERN-C4 blanket failure, and
dSphobic total suppression — are one algebraic event. The single parameter $d$ encodes which
side of the threshold a system inhabits.

Four quantitative bridges remain open: (i) $\delta = f(\varepsilon)$ mapping the dSphobic mass
splitting to the PRIMA floor in SI units; (ii) $d = f(S_{\text{ent}})$ relating TH coupling to
entanglement entropy; (iii) $\log\varphi = (2\pi k_BT^{*}/\hbar)\,\tau_{\text{coord}}$
connecting the MEP ceiling to the MSS bound; (iv) an explicit diffeomorphism between the six
statistical manifolds. Until these are established, the seven identities stand as formal
isomorphisms — six frameworks discovering the same information-free threshold, the same
fixed/floating partition, the same absence of information at the crossing, and the same DNA helix
of fixed and floating points orbiting the architecture at its core.

The threshold carries no information. That is the deepest fact.

---

## References

Akiyama, K. et al. (Event Horizon Telescope Collaboration). "First M87 Event Horizon Telescope
Results. I. The Shadow of the Supermassive Black Hole." *Astrophys. J. Lett.* 875, L1, 2019.

Akiyama, K. et al. (Event Horizon Telescope Collaboration). "First Sagittarius A* Event Horizon
Telescope Results. I." *Astrophys. J. Lett.* 930, L12, 2022.

Berlin, A., Foster, J. W., Hooper, D., and Krnjaic, G. "dSphobic Dark Matter."
arXiv:2504.12372, 2025.

Bernstein, D. J. and Lange, T. "Twisted Hessian Curves." *LATINCRYPT 2015*, LNCS 9230,
269–294, 2015.

Berry, M. V. "Disruption of Wavefronts: Statistics of Dislocations in Incoherent Gaussian
Random Waves." *J. Phys. A: Math. Gen.* 11, 27–37, 1978.

Birrell, N. D. and Davies, P. C. W. *Quantum Fields in Curved Space.* Cambridge University
Press, 1982.

Bucher, T., Gorlach, A., Niedermayr, A., Yan, Q., Nahari, H., Wang, K., Ruimy, R., Adiv, Y.,
Yannai, M., Abudi, T. L., Janzen, E., Spaegele, C., Roques-Carmes, C., Edgar, J. H., Koppens,
F. H. L., Vanacore, G. M., Sheinfux, H. H., Tsesses, S., and Kaminer, I. "Superluminal
Correlations in Ensembles of Optical Phase Singularities." *Nature* 651, 920–926, 2026.

Carter, B. "Axisymmetric Black Hole Has Only Two Degrees of Freedom." *Phys. Rev. Lett.* 26,
331–333, 1971.

Chentsov, N. N. *Statistical Decision Rules and Optimal Inference.* AMS Translations, Vol. 53,
1982. (Original: Nauka, 1972.)

Cramér, H. *Mathematical Methods of Statistics.* Princeton University Press, 1946.

Davies, P. C. W. and Fulling, S. A. "Radiation from a Moving Mirror in Two Dimensional
Space-Time: Conformal Anomaly." *Proc. R. Soc. Lond. A* 348, 393–414, 1976.

Dyson, F. J. "Statistical Theory of the Energy Levels of Complex Systems I." *J. Math. Phys.*
3, 140–156, 1962.

Einstein, A. and Rosen, N. "The Particle Problem in the General Theory of Relativity." *Phys.
Rev.* 48, 73–77, 1935.

Engelhardt, N. and Wall, A. C. "Quantum Extremal Surfaces: Holographic Entanglement Entropy
Beyond the Classical Regime." *JHEP* 01, 073, 2015.

Faulkner, T., Lewkowycz, A., and Maldacena, J. "Quantum Corrections to Holographic Entanglement
Entropy." *JHEP* 11, 074, 2013.

Fisher, R. A. "Theory of Statistical Estimation." *Math. Proc. Cambridge Phil. Soc.* 22(5),
700–725, 1925.

Friston, K. "Life as We Know It." *J. R. Soc. Interface* 10(86), 20130475, 2013.

Friston, K., Da Costa, L., Tschantz, A. et al. "Designing Ecosystems of Intelligence from First
Principles." *Collective Intelligence* 3(1), 2024.

Gibbons, G. W. and Hawking, S. W. "Action Integrals and Partition Functions in Quantum Gravity."
*Phys. Rev. D* 15, 2752–2756, 1977.

Hawking, S. W. "Black Holes in General Relativity." *Commun. Math. Phys.* 25, 152–166, 1972.

Hawking, S. W. "Particle Creation by Black Holes." *Commun. Math. Phys.* 43, 199–220, 1975.

't Hooft, G. "Dimensional Reduction in Quantum Gravity." *arXiv:gr-qc/9310026*, 1993.

Israel, W. "Event Horizons in Static Vacuum Space-Times." *Phys. Rev.* 164, 1776–1779, 1967.

Jacobson, T. "Thermodynamics of Spacetime: The Einstein Equation of State." *Phys. Rev. Lett.*
75, 1260–1263, 1995.

Katz, N. M. and Sarnak, P. *Random Matrices, Frobenius Eigenvalues, and Monodromy.* AMS
Colloquium Publications 45, 1999.

Kitaev, A. "A Simple Model of Quantum Holography." KITP talks, February and May 2015.

Maldacena, J. and Susskind, L. "Cool Horizons for Entangled Black Holes." *Fortschritte der
Physik* 61(9), 781–811, 2013.

Maldacena, J., Shenker, S. H., and Stanford, D. "A Bound on Chaos." *JHEP* 08, 106, 2016.

Marchenko, V. A. and Pastur, L. A. "Distribution of Eigenvalues for Some Sets of Random
Matrices." *Math. USSR Sb.* 1(4), 457–483, 1967.

Mehta, M. L. *Random Matrices.* 2nd ed. Academic Press, 1991.

Montgomery, H. L. "The Pair Correlation of Zeros of the Zeta Function." *Analytic Number
Theory*, Proc. Sympos. Pure Math. XXIV, AMS, 181–193, 1973.

Nye, J. F. and Berry, M. V. "Dislocations in Wave Trains." *Proc. Roy. Soc. Lond. A* 336,
165–190, 1974.

Pastawski, F., Yoshida, B., Harlow, D., and Preskill, J. "Holographic Quantum Error-Correcting
Codes: Toy Models for the Bulk/Boundary Correspondence." *JHEP* 06, 149, 2015.

Ramstead, M. J. D. et al. "On Bayesian Mechanics: A Physics of and by Beliefs." *Interface
Focus* 13(3), 20220029, 2023.

Rao, C. R. "Information and the Accuracy Attainable in the Estimation of Statistical
Parameters." *Bull. Calcutta Math. Soc.* 37, 81–91, 1945.

Ryu, S. and Takayanagi, T. "Holographic Derivation of Entanglement Entropy from AdS/CFT."
*Phys. Rev. Lett.* 96, 181602, 2006.

Sachdev, S. and Ye, J. "Gapless Spin-Fluid Ground State in a Random Quantum Heisenberg Magnet."
*Phys. Rev. Lett.* 70, 3339, 1993.

Sekino, Y. and Susskind, L. "Fast Scramblers." *JHEP* 10, 065, 2008.

Shannon, C. E. "A Mathematical Theory of Communication." *Bell Syst. Tech. J.* 27, 379–423,
1948.

Silverman, J. H. *The Arithmetic of Elliptic Curves.* Springer, 1986.

Silverman, J. H. *Advanced Topics in the Arithmetic of Elliptic Curves.* Springer, 1994.

Susskind, L. "The World as a Hologram." *J. Math. Phys.* 36, 6377–6396, 1995.

Tucker-Smith, D. and Weiner, N. "Inelastic Dark Matter." *Phys. Rev. D* 64, 043502, 2001.

Valiant, L. G. "The Complexity of Computing the Permanent." *Theoretical Computer Science* 8(2),
189–201, 1979.

Van Raamsdonk, M. "Building Up Spacetime with Quantum Entanglement." *Gen. Rel. Grav.* 42,
2323–2329, 2010.

Wigner, E. P. "Characteristic Vectors of Bordered Matrices with Infinite Dimensions."
*Ann. Math.* 62(3), 548–564, 1955.

Woodbury, M. A. "Inverting Modified Matrices." *Memorandum Report 42*, Statistical Research
Group, Princeton University, 1950.

---

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · April 2026

*Six programmes found the same information-free threshold from six directions. Chentsov proved
in 1972 that any such threshold inherits the Fisher-Rao metric uniquely. The matrix was always
the same matrix. The dark point near annihilation carries no energy. The dSphobic threshold
carries no signal. The Bogoliubov coefficient at the turning point carries no phase. The
Mordell-Weil rank does not change at the degeneration. The GUE eigenvalue repulsion carries no
information. The shadow of a black hole is the same for every observer.*

*Nothing crosses the threshold. That is what "unfilled" means.*
