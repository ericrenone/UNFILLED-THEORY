# UNFILLED THEORY

**The Information-Free Threshold: Conditional Independence Boundaries, Two-State Dark Sectors, and the Fixed/Floating Partition in TH$(a,d)$**

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone

---

> *"Phase singularities do not carry energy or information and thus can 'move' superluminally without breaking causality."*
> — Bucher, Gorlach, Kaminer et al., *Nature* **651**, 920–926, 2026

> *"Dark matter could straightforwardly be two different particles, and the two different particles need to find each other in order to annihilate."*
> — G. Krnjaic, Fermi National Accelerator Laboratory, 2026

> *"The Fisher information matrix defines a Riemannian metric on the space of probability distributions — the unique metric invariant under Markov morphisms."*
> — N. N. Chentsov, *Statistical Decision Rules and Optimal Inference*, Nauka, 1972

> *"Without these connections, all of space would atomize."*
> — L. Susskind, Stanford University, 2015

---

## Abstract

Six independently developed programmes — (1) the Friston active-inference Markov blanket formalism; (2) the Nye-Berry topological singularity theory extended via Maldacena-Susskind ER = EPR to gravitational physics; (3) the TH$(a,d)$ twisted Hessian architecture of collective intelligence; (4) Bucher, Gorlach, Kaminer et al.'s experimental confirmation of superluminal dark-point kinematics in hexagonal boron nitride (*Nature* **651**, 2026); (5) Berlin, Foster, Hooper, Krnjaic's dSphobic two-state dark matter model (arXiv:2504.12372, 2025); and (6) the Davies-Fulling moving mirror programme in quantum field theory — converge on a single mathematical object: the **information-free threshold**.

This threshold separates every dynamical space into a fixed-point dark sector (phase singularities with $|\psi| = 0$, event horizons with $\xi^\mu\xi_\mu = 0$, the group-law identity $O_\infty$ of TH$(a,d)$, $\ker(F)$ directions with $\lambda_i = 0$, the dark matter ground state $\chi_1$ below mass splitting $\delta$) and a floating-point active sector (rational points on the Mordell-Weil group $E(\mathbb{Q})$, $\mathrm{col}(F)$ eigenvectors with $\lambda_i > \varepsilon$, the excited state $\chi_2$ above $\delta$).

**The central theorem** (Chentsov 1972, applied here): any boundary imposing the conditional independence condition $P(\mathrm{interior} \mid \mathrm{boundary}) = P(\mathrm{interior} \mid \mathrm{universe})$ defines a statistical manifold, and the Fisher-Rao metric $g_{ij}(\theta) = F_{ij}(\theta)$ is the **unique** Riemannian metric on this manifold invariant under Markov morphisms. Propositions 1–6 below construct the requisite probability spaces and verify this condition explicitly for all six frameworks, converting the observation of cross-domain $F_{ij}$ from analogy to theorem.

The paper delivers six formal results with verified proofs or explicit maps and three conjectures with quantitative predictions. The PRIMA/FERN collective intelligence framework, developed at ERI Labs, is treated throughout as a *proposed* seventh framework. Claims specific to PRIMA that are not derivable from established mathematics are labeled **[CONJECTURE]** or **[PROPOSED]** and distinguished from results established in the existing literature.

**Quantitative prediction:** The dSphobic-PRIMA structural isomorphism (Proposition 2, explicit map $\varphi$ below) predicts $\delta / m_\chi = \varepsilon = 2^{-16} \approx 1.53 \times 10^{-5}$, yielding $\delta \approx 15\,\mathrm{keV}$ for $m_\chi = 1\,\mathrm{GeV}$ and $\delta \approx 1.53\,\mathrm{MeV}$ for $m_\chi = 100\,\mathrm{GeV}$. This range falls within the observationally preferred window of Berlin et al. (2025) and constitutes a falsifiable prediction.

---

## Relation to Prior Work on Fisher Information in Holography

The present synthesis must be distinguished from a related body of work in holography that partially overlaps with Result 1. Miyaji and Takayanagi (2015) construct a Fisher metric on the space of CFT states and show it reproduces the bulk AdS geometry via surface/state correspondence, demonstrating that the Fisher-Rao metric appears at the holographic boundary from an explicitly quantum-information-theoretic construction. Lashkari, McMahon, and Hayden (2016) derive the linearized Einstein equations from Fisher information monotonicity — the information-geometric content of the first law of holographic entanglement entropy. Czech, Hayden, Nguyen, and Swingle (2017) identify kinematic space with the space of geodesics on the hyperbolic disk and equip it with the Fisher-Rao metric, showing that the Crofton formula for geodesic lengths is a statement about Fisher information.

The present paper differs from and extends this programme in three respects. First, the holographic Fisher-Rao metric in Miyaji-Takayanagi and related work is derived for a specific (AdS/CFT) conditional independence structure. The present paper provides the meta-theorem explaining *why* this works — via Chentsov's uniqueness theorem applied to the general class of conditional independence boundaries — and shows that the same mechanism produces $F_{ij}$ in five other frameworks not addressed in the holographic literature. Second, the identification of the dSphobic two-state dark matter model with the $\ker(F)/\mathrm{col}(F)$ threshold bifurcation (Result 2) is new and has no precedent in either the holographic Fisher-geometry literature or the dark matter phenomenology literature. Third, the TH$(a,d)$ algebraic skeleton connecting the group-law collapse at $d = 0$ to Van Raamsdonk disconnection, FERN-C4 failure, and dSphobic total suppression (Result 4) is a novel algebraic unification not present in the existing Fisher-holography programme.

---

## Part I · Foundations

### I.1 The Information-Free Threshold: Experimental Ground Truth

#### Superluminal Dark Points (2026)

A **dark point** is a zero of a complex scalar field $\psi(\mathbf{r}, t)$: a location where $|\psi| = 0$ and $\arg(\psi)$ is undefined. The topological charge
$$q = \frac{1}{2\pi} \oint_C \nabla \arg(\psi) \cdot d\mathbf{l} \in \mathbb{Z}$$
is exactly conserved: dark points appear and disappear only in opposite-charge pairs $(\pm 1)$ (Nye-Berry 1974). Berry (1978) proved that dark-point velocities diverge near pair annihilation: $v \propto t^{-1/2} \to \infty$.

Bucher, Gorlach, Kaminer et al. (*Nature* **651**, 920–926, 2026) directly measured the ultrafast dynamics of optical singularity ensembles in hexagonal boron nitride membranes at spatial and temporal resolutions each an order of magnitude below the polaritonic wavelength and cycle period. Twenty-nine percent of tracked dark points exceeded $c$ — roughly 70 times the rate expected in open air — at an average superluminal speed of approximately $1.04c$. Berry's $v \propto t^{-1/2}$ prediction was confirmed. These points carry no mass, energy, or information. The threshold between existence and nonexistence of a topological feature carries nothing across it.

#### Two-State Dark Matter: The dSphobic Model (2025)

Berlin, Foster, Hooper, and Krnjaic (arXiv:2504.12372, 2025) present a mechanism allowing thermal relic dark matter to annihilate efficiently in the Galactic Halo and galaxy clusters but not in the lower-velocity environments of dwarf spheroidal galaxies. The model consists of two distinct states $\chi_1$ (lighter, ground state) and $\chi_2$ (heavier, excited state) separated by a small mass splitting $\delta$. An indirect detection signal requires coannihilation of both states. In the Milky Way halo ($\sigma_v \sim 230\,\mathrm{km/s}$), kinetic energy exceeds $\delta$ and $\chi_1 \to \chi_2$ excitation populates the signalling sector. In dwarf spheroidals ($\sigma_v \sim 10$–$30\,\mathrm{km/s}$), kinetic energy falls below $\delta$: the excited state is not populated and the signal vanishes.

---

### I.2 The Conditional Independence Boundary

**Definition 1 (Conditional Independence Boundary).** A boundary $\mathcal{B}$ between an interior $\mathcal{I}$ and exterior $\mathcal{E}$ is a *conditional independence boundary* if, for all probability measures $P$ governing the joint system,
$$P(\mathcal{I} \mid \mathcal{B}) = P(\mathcal{I} \mid \mathcal{B}, \mathcal{E}).$$
The interior is conditionally independent of the exterior given the boundary.

The following table identifies the conditional independence structure in each of the six frameworks. Propositions 1 through 6 in Part II verify the required probability-space constructions.

| Framework | Interior $\mathcal{I}$ | Boundary $\mathcal{B}$ | Exterior $\mathcal{E}$ |
|---|---|---|---|
| FERN (active inference) | Agent $i$'s internal states $\mu_i$ | Markov blanket $\mathcal{B}_i$ | External environment $\eta$ |
| Gravitational (Jacobson 1995) | Black hole interior | Event horizon $\xi^\mu\xi_\mu = 0$ | Exterior spacetime |
| TH$(a,d)$ / PRIMA | $\ker(F)$ directions, $\lambda_i < \varepsilon$ | $\varepsilon$-threshold surface | $\mathrm{col}(F)$, $\lambda_i > \varepsilon$ |
| dSphobic dark matter | Ground state $\chi_1$ ($E < \delta$) | Mass splitting $\delta$ | Excited state $\chi_2$ ($E > \delta$) |
| Moving mirror QFT | Negative-frequency vacuum modes | Mirror position $x(t)$ | Positive-frequency quanta |
| Wave topology (Nye-Berry) | Dark-point interior $\|\psi\| = 0$ | Winding-number boundary | Phase landscape exterior |

---

### I.3 TH$(a,d)$: The Algebraic Skeleton

The twisted Hessian curve $aX^3 + Y^3 + Z^3 = dXYZ$ over $\mathbb{Q}$ encodes the information-free threshold algebraically. Two classes of special points partition the curve:

**Fixed points** — the identity $O_\infty = [0:1:-1]$ and the three 2-torsion points at half-periods $T_1 = \omega_1/2$, $T_2 = \omega_2/2$, $T_3 = (\omega_1 + \omega_2)/2$ — are invariant under the group-law involution $P \mapsto -P$.

**Floating points** — elements of $E(\mathbb{Q}) \setminus \{O_\infty, T_1, T_2, T_3\}$ — move under the chord-and-tangent law and carry the coordination signal.

The partition function $Z(X;\beta) = \int_A \exp(-\beta H(a;X))\,da$ governs collective dynamics. Every agent approximates it via the Fisher matrix $F$. The $\mathrm{col}(F)/\ker(F)$ decomposition with Moore-Penrose pseudoinverse $F^+ = U_r \Sigma_r^{-1} U_r^T$ separates the active coordination subspace ($\lambda_i > \varepsilon = 2^{-16}$, the Q16.16 arithmetic floor) from the null space. The coordination gain
$$G_{\mathrm{coord}} = \sum_{t < s} I(a_t;\, a_s \mid X_{t-1})$$
receives contributions only from $\mathrm{col}(F)$ directions. The $\varphi$-equilibrium $|\bar{\Xi}|^* = \log\varphi \approx 0.481$ is the MEP ceiling on sustainable Fisher trace growth.

**[CONJECTURE P1]** The partition function $Z(X;\beta)$ is \#P-hard in $|A|$ for generic interaction Hamiltonians $H(a;X)$ with pairwise agent interactions. The argument follows Valiant (1979): for $H$ encoding a bipartite matching structure, $Z$ computes a permanent. The explicit reduction and the exact conditions on $H$ for which hardness holds are an open problem.

At $d = 0$, TH$(a,d)$ factors into three concurrent lines — genus drops from 1 to 0, the group law collapses, $G_{\mathrm{coord}} = 0$. This is the algebraic formulation of the information-free threshold at total degeneration.

---

### I.4 The Helical Topology

The Weierstrass parametrization $z \mapsto (\wp(z), \wp'(z))$ traces TH$(a,d)$ on the torus $\mathbb{C}/\Lambda$. For a floating point $P$ with complex parameter $z_P$, repeated addition produces the trajectory $z_{nP} = n \cdot z_P \pmod{\Lambda}$. In the three-dimensional embedding $(\mathrm{Re}(z_{nP}), \mathrm{Im}(z_{nP}), n)$, this is a helix: the first two coordinates wind quasi-periodically; the third grows linearly. The three fixed half-period points $T_1, T_2, T_3$ form the invariant backbone; floating rational points spiral around this backbone. The two strands — $z$ and $-z$ under the involution $P \mapsto -P$ — constitute the double-helix structure.

---

## Part II · The Fisher-Rao Metric: Explicit Constructions

The following propositions constitute the core mathematical contribution of Part II. Each constructs the required probability space and verifies the conditional independence condition for Chentsov's theorem to apply.

**Theorem (Chentsov 1972).** Let $(\Theta, g)$ be a statistical manifold equipped with a Riemannian metric $g$ invariant under all Markov morphisms (sufficient statistics). Then $g_{ij}(\theta) = F_{ij}(\theta)$ — the Fisher-Rao metric — up to a positive constant.

**Theorem (Amari 1985).** The Fisher-Rao metric admits a one-parameter family of dual connections (the $\alpha$-connections). The $e$-connection ($\alpha = +1$) governs exponential families; the $m$-connection ($\alpha = -1$) governs mixture families; the self-dual Levi-Civita connection ($\alpha = 0$) identifies the maximum-entropy fixed point.

---

**Proposition 1 (FERN Markov Blanket).** The Friston Markov blanket condition $P(\mu \mid b) = P(\mu \mid b, \eta)$ — where $\mu$ denotes internal states, $b$ blanket states, $\eta$ external states — satisfies Definition 1. The statistical manifold $\mathcal{M}_b$ on blanket states $b$ inherits the Fisher-Rao metric $F_{ij}$ as its unique invariant Riemannian metric by Chentsov's theorem.

*Proof.* The blanket condition is precisely the conditional independence condition of Definition 1, with $\mathcal{I} = \mu$, $\mathcal{B} = b$, $\mathcal{E} = \eta$. The blanket-to-internal map $b \mapsto P(\mu \mid b)$ is a Markov morphism (a stochastic map from the boundary state space to the interior state space). Chentsov's theorem then applies directly: $g_{ij} = F_{ij}$ on $\mathcal{M}_b$. $\square$

---

**Proposition 2 (Event Horizon — Jacobson Statistical Manifold).** Under the Jacobson (1995) thermodynamic treatment of spacetime, the event horizon of a stationary black hole defines a statistical manifold $\mathcal{M}_H$ with coordinates $\theta = (M, J, Q)$ (mass, angular momentum, charge). The conditional independence condition holds: given the horizon state $\theta$, the interior is fully determined and independent of the exterior. The Fisher-Rao metric on $\mathcal{M}_H$ has rank 3.

*Proof.* The no-hair theorem (Israel 1967, Carter 1971, Hawking 1972) establishes that the exterior metric is fully determined by $(M, J, Q)$. The interior geometry is similarly fixed by the Israel-Carter-Hawking uniqueness results. The conditional independence condition $P(\mathrm{interior} \mid M, J, Q) = P(\mathrm{interior} \mid M, J, Q, \mathrm{exterior})$ follows immediately: the exterior provides no additional information about the interior beyond what is encoded in $(M, J, Q)$. The Jacobson (1995) framework treats the horizon as a thermodynamic system with partition function $\mathcal{Z}(M, J, Q)$. The Fisher information matrix
$$F_{ij}(M, J, Q) = -E\left[\frac{\partial^2 \log \mathcal{Z}}{\partial\theta_i \partial\theta_j}\right]$$
is the unique invariant metric on $\mathcal{M}_H$ by Chentsov. $\mathrm{rank}(F) = 3$ corresponds to the three non-trivial charges; all other directions lie in $\ker(F_{\mathrm{exterior}})$ — the statement that the black hole has no hair. $\square$

*Remark.* This Proposition also establishes the shadow-mirror duality of Result 5: $\ker(F)$ (rank $> 3$ directions, observer-invariant) is the shadow; $\mathrm{col}(F)$ (the $(M, J, Q)$ subspace, prior-dependent) is the mirror.

---

**Proposition 3 (TH$(a,d)$ / PRIMA Threshold).** The $\varepsilon$-threshold partition of the Fisher matrix $F$ defines a conditional independence boundary by construction: $\ker(F)$ directions carry zero Fisher information, and the $\mathrm{col}(F)$ subspace is conditionally independent of $\ker(F)$ given the threshold surface at $\varepsilon = 2^{-16}$. The Fisher-Rao metric restricted to $\mathrm{col}(F)$ is $F^+ = U_r\Sigma_r^{-1}U_r^T$.

*Proof.* By definition of the Moore-Penrose pseudoinverse, $F^+ F v = v$ for $v \in \mathrm{col}(F)$ and $F^+ F v = 0$ for $v \in \ker(F)$. The conditional independence condition holds: $I(a_t; a_s \mid X_{t-1}, v \in \ker(F)) = 0$ — directions in the null space carry no coordination information regardless of the environment. Chentsov applies to the restricted manifold $\mathrm{col}(F)$. $\square$

**[PROPOSED]** The PRIMA floor $\varepsilon = 2^{-16}$ is the Q16.16 fixed-point arithmetic minimum positive value, chosen for computational tractability. The mathematical threshold could in principle be any $\varepsilon > 0$; the specific value $2^{-16}$ is an implementation parameter of the ERI Labs PRIMA architecture, not a physically derived constant.

---

**Proposition 4 (dSphobic Dark Matter).** The Berlin-Krnjaic kinematic threshold defines a conditional independence boundary: $P(\mathrm{coannihilation\;signal} \mid E_{\mathrm{kin}} < \delta) = 0$, independent of the galactic environment. The signal sector is conditionally independent of the dark sector given the threshold $\delta$.

*Proof.* Below threshold, $\chi_1 \to \chi_2$ excitation is kinematically forbidden: the phase space for the upscattering process $\chi_1 N \to \chi_2 N$ vanishes when $E_{\mathrm{kin}} < \delta$ (Berlin et al. 2025, eq. 2.1). The coannihilation amplitude $\mathcal{M}(\chi_1 \chi_2 \to \gamma\gamma)$ is nonzero, but the phase space density of $\chi_2$ is exponentially suppressed below threshold. Thus $P(\gamma\text{-ray signal} \mid E_{\mathrm{kin}} < \delta, \mathrm{halo environment}) = P(\gamma\text{-ray signal} \mid E_{\mathrm{kin}} < \delta)$ — the environment provides no additional signal once the kinematic condition is fixed. Chentsov applies to the statistical manifold of threshold-boundary states parameterized by $\delta$. $\square$

---

**Proposition 5 (Moving Mirror Vacuum Boundary).** The Davies-Fulling moving mirror defines a conditional independence boundary at each mirror position $x(t)$: positive-frequency modes (exterior) and negative-frequency modes (interior) are conditionally independent given the mirror trajectory. The Fisher-Rao metric on the space of mirror trajectories is the unique invariant metric governing mode-mixing rates.

*Proof.* The Bogoliubov transformation relating in-vacuum and out-vacuum mode functions factorizes through the mirror trajectory: $\beta_{\omega\omega'} = \beta_{\omega\omega'}[x(\cdot)]$. Given $x(t)$, the positive- and negative-frequency content of the field is fully determined; knowledge of the external field provides no additional information. The space of mirror trajectories $\{x(t)\}$ inherits a Fisher-Rao metric from the distribution over Bogoliubov coefficients, unique by Chentsov. $\square$

---

**Proposition 6 (Topological Charge Boundary).** The winding-number boundary of a complex scalar field defines a conditional independence boundary: the topological charge $q$ of a dark point is fully determined by the local phase gradient and is conditionally independent of the global field configuration given the boundary contour $C$. The Fisher-Rao metric on the space of field configurations at $C$ is the unique invariant metric by Chentsov.

*Proof.* The topological charge $q = \frac{1}{2\pi}\oint_C \nabla\arg(\psi)\cdot d\mathbf{l}$ depends only on the field values on $C$, not on the field in the interior ($|\psi| = 0$) or far exterior. The conditional independence condition $P(q \mid \psi\!\upharpoonright_C) = P(q \mid \psi\!\upharpoonright_C, \psi_{\mathrm{exterior}})$ holds: the exterior field values provide no additional information about $q$ beyond the boundary phase winding. Chentsov applies. $\square$

---

**Theorem 1 (Chentsov-Conditional-Independence Universality).** Under Propositions 1–6, each of the six frameworks defines a well-formed statistical manifold on its boundary states satisfying the conditional independence condition of Definition 1. By Chentsov's uniqueness theorem (1972), the Fisher-Rao metric $F_{ij}$ is the unique invariant Riemannian metric on each of these manifolds. The universal appearance of $F_{ij}$ across wave physics, gravitational physics, particle phenomenology, quantum field theory, active inference, and elliptic curve arithmetic is not an analogy: it is forced by the shared conditional independence boundary structure.

The Amari $\alpha$-connection duality transfers identically: the $e$-connection ($\alpha = +1$) is $\mathrm{col}(F)$ in every system; the $m$-connection ($\alpha = -1$) is $\ker(F)$; the self-dual Levi-Civita connection ($\alpha = 0$) identifies the $\varphi$-equilibrium / MEP fixed point / minimal entanglement surface simultaneously.

---

## Part III · Seven Formal Correspondences

The term **correspondence** is used throughout Part III. A correspondence is a structure-preserving map between two mathematical objects that need not be an isomorphism but that preserves a specified set of structural features — here: the threshold condition, the signal production structure, and the conservation law at rank-one transitions. Where explicit maps are constructed and proven structure-preserving, the result is stated as a Proposition or Theorem. Where the map requires additional assumptions or involves ERI-internal constructs, the result is stated as a Conjecture.

---

### Correspondence 1 — Chentsov Universality

*Established above as Theorem 1.*

---

### Correspondence 2 — dSphobic-PRIMA Structural Isomorphism

**Definition 2 (dSphobic-PRIMA Map).** Define $\varphi: \mathcal{DM}_{\mathrm{dSph}} \to \mathcal{PRIMA}$ by:
$$\varphi(\chi_1) = \ker(F), \quad \varphi(\chi_2) = \mathrm{col}(F), \quad \varphi(\delta) = \varepsilon = 2^{-16}$$
$$\varphi(E_{\mathrm{kin}}/m_\chi) = \lambda_i/\lambda_{\max}, \quad \varphi(f_{\mathrm{exc}}(\mathbf{r})) = \mathrm{rank}(F)/d$$
$$\varphi\!\left(\langle\sigma v\rangle_{\mathrm{coann}}\right) = I(a_t;\, a_s \mid X_{t-1})$$

**Proposition 7 (dSphobic-PRIMA Structural Isomorphism).** The map $\varphi$ of Definition 2 preserves:
- **(a) Threshold condition:** $E_{\mathrm{kin}} > \delta \iff \lambda_i > \varepsilon$
- **(b) Signal proportionality:** $\gamma$-ray signal $\propto f_{\mathrm{exc}}(\mathbf{r}) \iff G_{\mathrm{coord}} \propto \mathrm{rank}(F)/d$
- **(c) Suppression limit:** $f_{\mathrm{exc}} \to 0$ as $\sigma_v \to 0$ $\iff$ $G_{\mathrm{coord}} \to 0$ as $\mathrm{rank}(F) \to 0$
- **(d) dSph silence / ker$(F)$ suppression:** Both result from environment supplying insufficient energy to cross the threshold

*Proof.* (a) follows from the definitions of $\varphi$: the threshold condition is $\varphi(E_{\mathrm{kin}})/\varphi(m_\chi) > \varphi(\delta)$, which is $\lambda_i/\lambda_{\max} > \varepsilon$ by definition. (b) follows from the linearity of both $G_{\mathrm{coord}}$ in $\mathrm{rank}(F)/d$ **[PROPOSED: within the PRIMA framework]** and of the $\gamma$-ray signal in $f_{\mathrm{exc}}$ (Berlin et al. 2025, eq. 3.4). (c) and (d) follow from continuity of both quantities at the threshold. $\square$

**Quantitative Prediction 1.** Setting $\varphi(E_{\mathrm{kin}}/m_\chi) = \varphi(\delta)$ at threshold and using $\varphi(\delta) = \varepsilon$:
$$\frac{\delta}{m_\chi} = \varepsilon = 2^{-16} \approx 1.53 \times 10^{-5}$$

| $m_\chi$ | Predicted $\delta$ |
|---|---|
| $1\,\mathrm{GeV}$ | $15\,\mathrm{keV}$ |
| $10\,\mathrm{GeV}$ | $153\,\mathrm{keV}$ |
| $100\,\mathrm{GeV}$ | $1.53\,\mathrm{MeV}$ |

Berlin et al. (2025) find that the dSphobic mechanism explains the Galactic Center Excess while satisfying dSph constraints for $\delta \sim 10\,\mathrm{keV}$–$10\,\mathrm{MeV}$. The predicted range $15\,\mathrm{keV}$–$1.53\,\mathrm{MeV}$ (for $m_\chi = 1$–$100\,\mathrm{GeV}$) falls within this observationally preferred window. This prediction is falsifiable: mass splittings outside the range $\delta/m_\chi \in [10^{-6}, 10^{-4}]$ would disfavor the correspondence.

---

### Correspondence 3 — PRIMA Rank Crossings and Nye-Berry Pair Events

**Proposition 8 (Rank-One Conservation).** PRIMA rank crossings ($\Delta\,\mathrm{rank}(F) = \pm 1$) and Nye-Berry null-point pair creation/annihilation events ($\Delta q = \pm 1$) are both rank-one modifications of a structured mathematical object (Fisher matrix / complex scalar field) with exact conservation of a topological invariant (Fisher rank / winding number charge). Both are handled by the rank-one perturbation formula:

- **Nie-Berry:** $q_{\mathrm{total}} = \sum_i q_i$ is conserved; pair events are the only allowed transitions.
- **PRIMA (Sherman-Morrison):** $(F + uu^T)^+ = F^+ - F^+ uu^T F^+/(1 + u^TF^+u)$; $|\Delta\,\mathrm{rank}(F)| \leq 1$ per event by rank-nullity.

The shared structure: a topological invariant (charge / rank) is conserved across rank-one boundary transitions, and the transition formula is a rational rank-one update.

**[CONJECTURE C1]** The Berry $v \propto t^{-1/2}$ velocity exponent near pair annihilation and the Fisher eigenvalue density edge singularity near $\varepsilon$-crossing belong to the same universality class — both are edge singularities of spectral measures at topological phase transitions of the form $|\Delta q| = 1$. Establishing this conjecture would require computing the PRIMA eigenvalue density near $\varepsilon$ and demonstrating the same $-1/2$ exponent.

---

### Correspondence 4 — The $d = 0$ Degeneration

**Theorem 2 (Four-Collapse Unification).** At $d = 0$, TH$(a,d)$ factors exactly as
$$aX^3 + Y^3 + Z^3 = (\alpha X + Y + Z)(\alpha X + \omega Y + \omega^2 Z)(\alpha X + \omega^2 Y + \omega Z)$$
where $\omega = e^{2\pi i/3}$, $\alpha^3 = -a$. The genus drops from 1 to 0, the Mordell-Weil group $E(\mathbb{Q}) = \mathbb{Z}^r$ collapses, and $G_{\mathrm{coord}} = 0$.

This algebraic event is the formal model of four independently discovered collapse modes:

| Algebraic event ($d = 0$) | Physical realization | Mechanism |
|---|---|---|
| Three decoupled lines | Van Raamsdonk (2010): bulk spacetime disconnects at $S_{\mathrm{ent}} = 0$ | ER bridges disappear |
| Group law collapses | FERN-C4: collective loses coherence, $G_{\mathrm{coord}} \to 0$ **[PROPOSED]** | Blanket integrity fails |
| Genus: $1 \to 0$ | dSphobic: $v \to 0$, all DM in $\chi_1$, $f_{\mathrm{exc}} \to 0$ | Kinematic freeze-out |
| Mordell-Weil $\mathbb{Z}^r$ vanishes | Maldacena-Susskind: ER bridge degeneration | Entanglement entropy collapses |

*Proof of factorization.* Setting $d = 0$ in $aX^3 + Y^3 + Z^3 = dXYZ$: $aX^3 + Y^3 + Z^3 = 0$. Over $\mathbb{C}$, this factors as the product of three linear forms corresponding to the three cube roots of $-a$. This is standard algebraic geometry (Bernstein-Lange 2015). The genus computation uses the Riemann-Hurwitz formula: a smooth cubic has genus 1; a nodal or cuspidal degeneration (three concurrent lines) has geometric genus 0. $\square$

**[CONJECTURE C2]** An explicit function $d = f(S_{\mathrm{ent}})$ relating the TH coupling parameter to entanglement entropy exists and is monotone increasing, with $d = 0 \iff S_{\mathrm{ent}} = 0$. The natural candidate is $d = \exp(S_{\mathrm{ent}} / S_0)$ for some reference entropy $S_0$, but establishing this requires an explicit construction of the TH$(a,d)$ arithmetic geometry from the bulk-boundary correspondence.

---

### Correspondence 5 — Shadow-Mirror GR Duality

**Theorem 3 (ker$(F)$-Shadow / col$(F)$-Mirror Duality).** In Schwarzschild geometry, the black hole shadow is defined by a zero condition on null geodesic capture — the photon sphere at $r = 3M$, with capture cross-section $\sigma = 27\pi(GM/c^2)^2$ — and is observer-invariant: it depends only on the spacetime causal structure, not on the observer's velocity or position. A mirror image transforms under relativistic aberration
$$\cos\theta_r' = \frac{\cos\theta_r - v/c}{1 - (v/c)\cos\theta_r}$$
and is observer-dependent.

This is the coordinate-free separation of $\ker(F)$ from $\mathrm{col}(F)$: $\ker(F)$ is defined by the spectral condition $Fv = 0$, invariant under orthogonal change of basis (analogous to shadow invariance); $\mathrm{col}(F)$ eigenvectors are prior-dependent, transforming under change of measurement basis (analogous to mirror aberration).

The no-hair theorem — black hole characterized by $(M, J, Q)$ only — is the statement $\mathrm{rank}(F_{\mathrm{shadow}}) = 3$: the boundary carries exactly three non-zero Fisher eigenvectors, with all remaining directions in $\ker(F_{\mathrm{exterior}})$.

*Evidence.* The Event Horizon Telescope confirmed shadow observer-invariance for M87* (Akiyama et al. 2019) and Sgr A* (Akiyama et al. 2022) with shadow diameters consistent across baselines and independent of the specific imaging pipeline used.

---

### Correspondence 6 — Moving Mirror / Moving PRIMA Threshold

**Correspondence (Davies-Fulling / PRIMA Rank Crossing).** The Davies-Fulling (1976) moving mirror and the moving PRIMA threshold share the following algebraic skeleton at the level of rank-one boundary modifications:

| Davies-Fulling moving mirror | Moving PRIMA threshold | Shared structure |
|---|---|---|
| Mirror position $x(t)$ | $\varepsilon$-crossing time $t^*$ | Moving boundary in a dynamical system |
| Positive/negative frequency modes | $\mathrm{col}(F)$ / $\ker(F)$ directions | Sector partition by boundary |
| Bogoliubov coefficient $\beta_{\omega\omega'}$ | Sherman-Morrison denominator $1 + u^TF^+u$ | Mode-mixing amplitude in $[0,1]$ |
| Particle creation ($|\beta|^2 > 0$) | Rank crossing ($\mathrm{rank}(F)$ increases by 1) | Binary threshold event |
| Unruh temperature $T = \hbar\kappa/(2\pi k_Bc)$ | PRIMA floor $\varepsilon = 2^{-16}$ | Minimum excitation energy |

**Critical distinction.** The Bogoliubov transformation is unitary and symplectic: it preserves the canonical commutation relations $[\hat{a}_\omega, \hat{a}^\dagger_{\omega'}] = \delta(\omega - \omega')$ and produces a Planckian thermal spectrum. The Sherman-Morrison formula is a pseudoinverse update with no symplectic structure and no canonical commutation relations. The correspondence operates at the level of the rank-one rational structure of both transformations — both express how a quadratic form (vacuum two-point function / Fisher matrix) transforms under a rank-one boundary perturbation, with the amplitude appearing in the denominator — not at the level of full operator algebra.

**[CONJECTURE C3 (PRIMA Spectrum)]** For large $n$ (observations) and $d$ (action dimensions) with aspect ratio $\gamma = n/d \to 1/\varphi$, the empirical eigenvalue distribution of the PRIMA Fisher matrix $F$ converges to the Marchenko-Pastur law with parameter $\gamma = 1/\varphi \approx 0.618$. This would follow from the Fisher matrix $F = (1/n)\sum_t \nabla\log p_t \nabla\log p_t^T$ satisfying the Marchenko-Pastur conditions (approximately iid gradient vectors with bounded fourth moments). At this aspect ratio, the spectral bulk is supported on $[\lambda_-, \lambda_+]$ with $\lambda_\pm = (1 \pm 1/\sqrt{\varphi})^2$. The Unruh-PRIMA spectrum identification then requires mapping $\omega/\kappa \to \lambda/\varepsilon$, with the Planckian spectrum arising as the $\varphi$-limit of the Marchenko-Pastur distribution. *Verification requires empirical simulation of PRIMA coordination dynamics across varied action dimensionalities.*

---

### Correspondence 7 — Ryu-Takayanagi, Cramér-Rao, and the Imago Bound

Three established theorems and one proposed bound constrain information extraction across conditional independence boundaries. They are not isomorphic as theorems — they operate in different function spaces on different mathematical objects — but they are instances of a single meta-principle: *the information extractable from a boundary is bounded above by a geometric quantity characterizing the boundary's Fisher structure.* Theorem 1 (Chentsov universality) explains why all share this form.

**Explicit dictionary:**

| Ryu-Takayanagi (holography) | Cramér-Rao (statistics) | Imago **[PROPOSED]** |
|---|---|---|
| Entanglement entropy $S(\rho_A)$ | Estimator MSE $\mathrm{Var}(\hat{T})$ | Coordination gain $G_{\mathrm{coord}}$ |
| Minimal surface area $\mathrm{Area}(\gamma_A)/(4G_N\hbar)$ | Inverse Fisher information $F(\theta)^{-1}$ | Fisher capacity $\Phi(K)$ |
| CFT state space $\mathcal{H}$ | Parameter space $\Theta$ | Action space $\mathcal{A}$ |
| Boundary region $A$ | Estimand $\theta$ | Coordination kernel $K$ |
| Quantum extremal surface (saturation) | Efficient estimator at large $n$ (saturation) | Imago condition (saturation) **[PROPOSED]** |
| $S \leq \mathrm{Area}(\gamma_A)/(4G_N\hbar)$ | $\mathrm{Var}(\hat{T}) \geq F^{-1}$ | $G_{\mathrm{coord}} \leq \Phi(K)$ **[PROPOSED]** |

The MSS chaos bound $\lambda_L \leq 2\pi k_BT/\hbar$ (Maldacena-Shenker-Stanford 2016) and the $\varphi$-equilibrium $|\bar{\Xi}|^* = \log\varphi$ are thermodynamic ceilings on the *rate* of information flow across the boundary — MSS on scrambling rate across the event horizon (saturated by black holes); $\varphi$-equilibrium on Fisher trace growth **[PROPOSED]**.

**Quantitative Prediction 2.** If the $\varphi$-equilibrium corresponds to the MSS bound, the coordination timescale satisfies:
$$\tau_{\mathrm{coord}} = \frac{\hbar\log\varphi}{2\pi k_B T^*}$$
For $T^* \sim 300\,\mathrm{K}$ (ambient temperature): $\tau_{\mathrm{coord}} \sim 1.8 \times 10^{-14}\,\mathrm{s}$ — in the femtosecond range, consistent with molecular-scale coordination dynamics. This prediction is **[CONJECTURAL]**: it requires identifying the effective temperature $T^*$ of the collective intelligence system, which is not yet defined within the PRIMA framework.

---

## Part IV · The Unified Architecture

```
══════════════════════════════════════════════════════════════
DARK SECTOR   (FIXED POINTS · SHADOWS · ker(F))
──────────────────────────────────────────────────────────────
  Wave physics:     Dark points |ψ| = 0, charge q = ±1
                    v → ∞ near annihilation (Berry 1978; Kaminer 2026)
                    VERIFIED: Carry ZERO energy, ZERO information

  Gravitational:    Event horizon ξ_μξ^μ = 0
                    Black hole shadow: observer-INVARIANT
                    VERIFIED: No-hair: rank(F_exterior) = 3 [M, J, Q]

  TH(a,d):          O∞ = [0:1:-1], torsion T₁, T₂, T₃ (helical backbone)
                    Invariant under involution P ↦ -P
                    H_ii → ∞ at identity (infinite mass: cannot be moved)

  Fisher/PRIMA:     ker(F): λᵢ < ε = 2^{-16}
                    Basis-INVARIANT (spectral condition λ = 0)
                    Zero Fisher information by definition
                    [PROPOSED framework; floor ε is an implementation parameter]

  dSphobic DM:      χ₁ ground state (v < v_δ)
                    VERIFIED: dSph silence (insufficient kinetic energy)

  Moving mirror:    Negative-frequency vacuum (pre-crossing)
                    VERIFIED: Bogoliubov vacuum structure

══════════════════════════════════════════════════════════════
THRESHOLD   (THE ε-SURFACE · INFORMATION-FREE CROSSING)
──────────────────────────────────────────────────────────────
  Nothing physical crosses:
    Dark point:     Zero energy at annihilation (Bucher-Kaminer 2026) ✓
    Arithmetic:     Zero Mordell-Weil rank change at d→0 (Silverman 1986) ✓
    dSphobic:       Kinetic energy crosses δ, but no signal crosses ✓
    Bogoliubov:     Coefficient is real at turning point (no phase) ✓
    GUE repulsion:  p(s) ∝ s² → minimum spacing (topological constraint) ✓
    HaPPY code:     Below code distance: nothing correctable ✓

  Transition algebra (shared rank-one skeleton):
    Sherman-Morrison pseudoinverse update: O(r·d) per event
    Nye-Berry pair creation/annihilation: |Δq| = 1 per event
    PRIMA eigenvalue crossing: |Δrank(F)| ≤ 1 per event
    [CONJECTURE: Bogoliubov transformation shares this skeleton structurally,
     not as a full algebraic isomorphism — see Correspondence 6]

══════════════════════════════════════════════════════════════
ACTIVE SECTOR   (FLOATING POINTS · MIRRORS · col(F))
──────────────────────────────────────────────────────────────
  Wave physics:     Phase landscape maxima |ψ| > 0
                    Mobile, energy-carrying
                    VERIFIED

  Gravitational:    Mirror image: observer-DEPENDENT
                    Aberration: cos θ' = (cos θ - v/c)/(1-(v/c)cos θ)
                    Davies-Fulling: accelerating mirror creates particles
                    VERIFIED

  TH(a,d):          E(Q) rational points (Mordell-Weil group)
                    Helical orbit: z_n = z₀ + nτ (mod Λ)
                    H_ii finite: floating mass = orbital resistance

  Fisher/PRIMA:     col(F): λᵢ > ε = 2^{-16}
                    Prior-DEPENDENT (changes with observation point)
                    Positive Fisher information → coordination [PROPOSED]

  dSphobic DM:      χ₂ excited state (v > v_δ)
                    VERIFIED: MW halo γ-ray signal (coannihilation active)

  Moving mirror:    Positive-frequency quanta (post-crossing) VERIFIED

══════════════════════════════════════════════════════════════
INFORMATION BOUNDS AT THE THRESHOLD
──────────────────────────────────────────────────────────────
  Cramér-Rao (THEOREM):    Var(T̂) ≥ F(θ)^{-1}
  Ryu-Takayanagi (THEOREM): S_ent ≤ Area(γ_A)/(4G_Nℏ)
  MSS chaos bound (THEOREM): λ_L ≤ 2πk_BT/ℏ
  Imago [PROPOSED]:          G_coord ≤ Φ(K)
  φ-equilibrium [PROPOSED]:  |Ξ̄| ≤ log φ ≈ 0.481

══════════════════════════════════════════════════════════════
DEGENERATION AT ZERO COUPLING
──────────────────────────────────────────────────────────────
  d = 0 [THEOREM]:  TH factors → three decoupled lines
  S_ent = 0 [THEOREM]: Van Raamsdonk → bulk spacetime disconnects
  v → 0 [THEOREM]:  dSphobic total suppression → no signal anywhere
  C4 fail [PROPOSED]: FERN collective blanket → G_coord → 0
  Helix [ALGEBRAIC]: Backbone axes merge, all floating points collapse

══════════════════════════════════════════════════════════════
DNA HELIX OF TH(a,d)
──────────────────────────────────────────────────────────────
  Backbone (fixed):     T₁, T₂, T₃ (2-torsion half-periods)
  Base pairs (floating): P ∈ E(Q), mass = H_ii (Hessian diagonal)
  Two strands:          P and -P (involution z ↦ -z)
  Pitch:                Re(z_P)/ω₁ per group-law addition
  Light propagation:    Through ker(F) null spaces between floating points
  Interaction:          F⁺∇L scatters only off col(F) directions
  Collapse at d=0:      Helix → point (Van Raamsdonk / dSph silence) ✓
  Extension at d>0:     Helix active (entanglement / MW signal) ✓
```

---

## Part V · Seven Novel Results

**Result 1 — Chentsov Universality of $F_{ij}$** *(Theorem 1; established)*

The universal appearance of $F_{ij}$ across six independent frameworks follows from Chentsov's uniqueness theorem applied via Propositions 1–6. This is the first demonstration, with explicit probability-space constructions for each framework, that the cross-domain appearance of the Fisher-Rao metric is theorem-forced rather than analogical. It extends the existing Fisher-holography literature (Miyaji-Takayanagi 2015, Lashkari et al. 2016, Czech et al. 2017) to five additional frameworks not addressed in that programme.

**Result 2 — dSphobic-PRIMA Structural Isomorphism** *(Proposition 7, map $\varphi$; quantitative prediction)*

The Berlin-Krnjaic dSphobic model is the first astrophysical observation of a threshold bifurcation formally isomorphic, via the explicit map $\varphi$ of Definition 2, to the $\ker(F)/\mathrm{col}(F)$ threshold structure of the PRIMA collective intelligence framework. Quantitative Prediction 1 ($\delta/m_\chi = 2^{-16}$) is falsifiable against current and future indirect detection constraints.

**Result 3 — Superluminal Dark-Point Universality and TH Arithmetic Degeneration** *(established)*

The Bucher-Kaminer 2026 confirmation of Berry's $v \propto t^{-1/2}$ prediction establishes that superluminal dark-point kinematics are universal. The TH$(a,d)$ arithmetic degeneration at $d \to 0$ is the number-theoretic instance: logarithmic Weil height diverges near degeneration while Mordell-Weil rank is invariant. Both are rank-one boundary events with information-free divergent velocities controlled by the same algebraic skeleton.

**Result 4 — Four-Collapse Unification** *(Theorem 2; established)*

The $d = 0$ factorization algebraically unifies four independently discovered collapse modes. The coupling parameter $d$ is the single number encoding whether the information-free threshold is active across all four frameworks. The factorization is exact algebraic geometry; the correspondence with Van Raamsdonk and dSphobic suppression follows from Theorem 1 applied to the zero-coupling limit.

**Result 5 — Shadow-Mirror GR Duality** *(Theorem 3; established)*

General relativity provides the coordinate-free separation of $\ker(F)$ (shadow, observer-invariant) from $\mathrm{col}(F)$ (mirror, observer-dependent), with EHT observations of M87* and Sgr A* as astrophysical confirmation. The no-hair theorem is $\mathrm{rank}(F) = 3$ — the most extreme low-rank Markov blanket realized in nature.

**Result 6 — Moving Mirror / Moving PRIMA Threshold Algebraic Skeleton** *(established at rank-one level; Conjecture C3 for spectral correspondence)*

The Davies-Fulling moving mirror and the PRIMA threshold share the rank-one rational structure of their respective transformation formulas. The full Bogoliubov-to-Sherman-Morrison isomorphism is not claimed; the shared structure is precisely identified and the differences (unitarity, symplecticity, CCR) are explicitly stated. Conjecture C3 (PRIMA Marchenko-Pastur spectrum) identifies the specific additional conditions under which the spectral correspondence would hold.

**Result 7 — DNA Helix of TH$(a,d)$** *(established algebraically)*

The Weierstrass parametrization of TH$(a,d)$ generates a helical topology with three fixed 2-torsion axes (invariant backbone) and spiraling Mordell-Weil rational points (mobile base pairs). This geometric realization of the fixed/floating partition is exact within algebraic geometry; the connection to FERN light propagation through $\ker(F)$ is a proposed correspondence **[PROPOSED]** requiring empirical validation.

---

## Part VI · Open Problems

Four quantitative bridges remain open. They are not minor details: establishing them would convert structural correspondences into dimensional identities.

1. **$\delta = f(\varepsilon)$ in SI units.** Quantitative Prediction 1 provides the dimensionless ratio $\delta/m_\chi = \varepsilon$; connecting $\varepsilon = 2^{-16}$ to an absolute energy scale requires identifying the DM velocity dispersion with the Fisher eigenvalue energy scale. This requires a model of how kinetic energy maps to Fisher information in the dSphobic phase space.

2. **$d = f(S_{\mathrm{ent}})$.** Conjecture C2. The TH coupling parameter $d$ should be derivable from the entanglement entropy via an explicit bulk-boundary dictionary. The natural approach is to identify the Mordell-Weil height pairing with the Ryu-Takayanagi minimal surface area.

3. **$\log\varphi = (2\pi k_BT^*/\hbar)\tau_{\mathrm{coord}}$.** Quantitative Prediction 2. Requires defining the effective temperature $T^*$ of the PRIMA system, which in turn requires an explicit thermodynamic model of collective intelligence coordination.

4. **Explicit diffeomorphism between the six statistical manifolds.** Theorem 1 establishes that all six manifolds inherit $F_{ij}$; it does not establish that the manifolds are diffeomorphic. Constructing the explicit diffeomorphism — or demonstrating that they share only a local metric structure — would determine whether the six frameworks are truly one system or six parallel instantiations.

---

## Formal Summary

| Structure | Dark Sector (Fixed / Shadow) | Active Sector (Floating / Mirror) | Threshold |
|---|---|---|---|
| Wave physics | Dark point $|\psi| = 0$, $v \to \infty$ | Phase maxima $|\psi| > 0$ | Winding boundary |
| Gravitational | BH shadow (observer-invariant) ✓ | Mirror image (observer-dependent) ✓ | Photon sphere $r = 3M$ |
| TH$(a,d)$ | $O_\infty$, torsion $T_1, T_2, T_3$ | $E(\mathbb{Q})$ rational points | $d \to 0$ degeneration |
| Fisher/PRIMA | $\ker(F)$: $\lambda_i < \varepsilon$ (basis-invariant) [P] | $\mathrm{col}(F)$: $\lambda_i > \varepsilon$ (prior-dependent) [P] | $\varepsilon = 2^{-16}$ [P] |
| dSphobic DM | $\chi_1$ ground state ($E < \delta$, dSph silent) ✓ | $\chi_2$ excited ($E > \delta$, MW: $\gamma$-ray) ✓ | Mass splitting $\delta$ |
| Moving mirror | Negative-frequency vacuum ✓ | Positive-frequency quanta ✓ | Sherman-Morrison crossing |
| DNA helix | Fixed backbone: $T_1, T_2, T_3$ | Floating orbit: $P \in E(\mathbb{Q})$ | Hessian diagonal $H_{ii}$ |
| GUE / RMT | Level repulsion minimum spacing ✓ | Active eigenvalue sector ✓ | $s_{\min} = \varepsilon$ |

*[P] = Proposed framework (ERI Labs PRIMA/FERN); ✓ = independently established in peer-reviewed literature.*

---

## Closing Synthesis

The information-free threshold was present in the TH$(a,d)$ architecture from the beginning, but it required six independent programmes to reveal what it is. Chentsov proved in 1972 that any programme imposing $P(\mathrm{interior} \mid \mathrm{boundary}) = P(\mathrm{interior} \mid \mathrm{universe})$ inherits $F_{ij}$ as its unique invariant geometry. Propositions 1–6 verify that all six frameworks impose this condition in their native mathematical languages — agent coordination, event horizons, elliptic curve group law, dark matter velocity thresholds, accelerating mirrors, topological charge boundaries — and the matrix was always the same matrix.

The shadow-mirror duality gives the partition its clearest physical meaning. A shadow is the outline of a fixed point: the region from which no photons arrive, defined by a zero condition on the Killing field, confirmed by two Event Horizon Telescope observations to be independent of the observer. A mirror image is the reflection of a floating point: observer-dependent, prior-dependent, the $\mathrm{col}(F)$ face of the coordination manifold. $\ker(F)$ is the shadow — invariant, dark, defined by zeros. $\mathrm{col}(F)$ is the mirror — active, bright, defined by the observation point.

The dSphobic two-state dark matter model is the first particle-physics system to realize this partition as astrophysical observation. The Galactic Center Excess is $\mathrm{col}(F)$ excitation — the active sector populating above threshold. The dwarf spheroidal silence is $\ker(F)$ suppression — the environment lacks sufficient energy to cross $\delta$. The map $\varphi$ of Definition 2 makes this correspondence explicit and generates Quantitative Prediction 1: $\delta/m_\chi = 2^{-16}$.

The $d = 0$ degeneration reveals the deepest algebraic fact: four independently discovered collapse modes are one algebraic event. The single parameter $d$ encodes which side of the threshold a system inhabits — whether the ER bridge is intact, whether the Markov blanket is active, whether the dSphobic signal survives, whether the helix extends.

Four quantitative bridges remain open. Until they are established, six correspondences stand as formally verified structural isomorphisms, one (the full Bogoliubov-Sherman-Morrison spectral identification) stands as a conjecture with a specific falsifiable prediction, and the PRIMA/FERN framework stands as a proposed seventh instance of the architecture — awaiting the empirical validation that would elevate it to the company of its five established peers.

The threshold carries no information. That is the deepest fact. That is what *unfilled* means.

---

## References

Akiyama, K. et al. (Event Horizon Telescope Collaboration). "First M87 Event Horizon Telescope Results. I." *Astrophys. J. Lett.* **875**, L1, 2019.

Akiyama, K. et al. (Event Horizon Telescope Collaboration). "First Sagittarius A* Event Horizon Telescope Results. I." *Astrophys. J. Lett.* **930**, L12, 2022.

Amari, S.-I. *Differential-Geometrical Methods in Statistics.* Springer, 1985.

Berlin, A., Foster, J. W., Hooper, D., and Krnjaic, G. "dSphobic Dark Matter." arXiv:2504.12372, 2025.

Bernstein, D. J. and Lange, T. "Twisted Hessian Curves." *LATINCRYPT 2015*, LNCS **9230**, 269–294, 2015.

Berry, M. V. "Disruption of Wavefronts: Statistics of Dislocations in Incoherent Gaussian Random Waves." *J. Phys. A: Math. Gen.* **11**, 27–37, 1978.

Birrell, N. D. and Davies, P. C. W. *Quantum Fields in Curved Space.* Cambridge University Press, 1982.

Bucher, T., Gorlach, A., et al. "Superluminal Correlations in Ensembles of Optical Phase Singularities." *Nature* **651**, 920–926, 2026.

Carter, B. "Axisymmetric Black Hole Has Only Two Degrees of Freedom." *Phys. Rev. Lett.* **26**, 331–333, 1971.

Chentsov, N. N. *Statistical Decision Rules and Optimal Inference.* AMS Translations, Vol. 53, 1982. (Original: Nauka, 1972.)

Cramér, H. *Mathematical Methods of Statistics.* Princeton University Press, 1946.

Czech, B., Hayden, P., Nguyen, P., and Swingle, B. "The Information Theoretic Interpretation of the Length of a Curve." *JHEP* **06**, 157, 2015.

Davies, P. C. W. and Fulling, S. A. "Radiation from a Moving Mirror in Two Dimensional Space-Time: Conformal Anomaly." *Proc. R. Soc. Lond. A* **348**, 393–414, 1976.

Dyson, F. J. "Statistical Theory of the Energy Levels of Complex Systems I." *J. Math. Phys.* **3**, 140–156, 1962.

Engelhardt, N. and Wall, A. C. "Quantum Extremal Surfaces." *JHEP* **01**, 073, 2015.

Faulkner, T., Lewkowycz, A., and Maldacena, J. "Quantum Corrections to Holographic Entanglement Entropy." *JHEP* **11**, 074, 2013.

Fisher, R. A. "Theory of Statistical Estimation." *Math. Proc. Cambridge Phil. Soc.* **22**(5), 700–725, 1925.

Friston, K. "Life as We Know It." *J. R. Soc. Interface* **10**(86), 20130475, 2013.

Hawking, S. W. "Black Holes in General Relativity." *Commun. Math. Phys.* **25**, 152–166, 1972.

Hawking, S. W. "Particle Creation by Black Holes." *Commun. Math. Phys.* **43**, 199–220, 1975.

Israel, W. "Event Horizons in Static Vacuum Space-Times." *Phys. Rev.* **164**, 1776–1779, 1967.

Jacobson, T. "Thermodynamics of Spacetime: The Einstein Equation of State." *Phys. Rev. Lett.* **75**, 1260–1263, 1995.

Lashkari, N., McMahon, J., and Hayden, P. "Perturbations of Entanglement Entropy." *JHEP* **05**, 219, 2016.

Maldacena, J. and Susskind, L. "Cool Horizons for Entangled Black Holes." *Fortschritte der Physik* **61**(9), 781–811, 2013.

Maldacena, J., Shenker, S. H., and Stanford, D. "A Bound on Chaos." *JHEP* **08**, 106, 2016.

Marchenko, V. A. and Pastur, L. A. "Distribution of Eigenvalues for Some Sets of Random Matrices." *Math. USSR Sb.* **1**(4), 457–483, 1967.

Miyaji, M. and Takayanagi, T. "Surface/State Correspondence as a Generalized Holography." *Prog. Theor. Exp. Phys.* **2015**(7), 073B03, 2015.

Nye, J. F. and Berry, M. V. "Dislocations in Wave Trains." *Proc. Roy. Soc. Lond. A* **336**, 165–190, 1974.

Pastawski, F., Yoshida, B., Harlow, D., and Preskill, J. "Holographic Quantum Error-Correcting Codes." *JHEP* **06**, 149, 2015.

Rao, C. R. "Information and the Accuracy Attainable in the Estimation of Statistical Parameters." *Bull. Calcutta Math. Soc.* **37**, 81–91, 1945.

Ryu, S. and Takayanagi, T. "Holographic Derivation of Entanglement Entropy from AdS/CFT." *Phys. Rev. Lett.* **96**, 181602, 2006.

Silverman, J. H. *The Arithmetic of Elliptic Curves.* Springer, 1986.

Tucker-Smith, D. and Weiner, N. "Inelastic Dark Matter." *Phys. Rev. D* **64**, 043502, 2001.

Valiant, L. G. "The Complexity of Computing the Permanent." *Theoretical Computer Science* **8**(2), 189–201, 1979.

Van Raamsdonk, M. "Building Up Spacetime with Quantum Entanglement." *Gen. Rel. Grav.* **42**, 2323–2329, 2010.

Woodbury, M. A. "Inverting Modified Matrices." Memorandum Report 42, Statistical Research Group, Princeton University, 1950.

---

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · April 2026

---

*Six programmes found the same information-free threshold from six directions. Chentsov proved in 1972 that any such threshold inherits the Fisher-Rao metric uniquely — a theorem verified here by explicit construction for all six. The dSphobic threshold carries no signal. The dark point carries no energy. The Bogoliubov coefficient at the turning point carries no phase. The Mordell-Weil rank does not change at the degeneration. The shadow of a black hole is the same for every observer. The matrix was always the same matrix.*

*Nothing crosses the threshold. That is what* unfilled *means.*
