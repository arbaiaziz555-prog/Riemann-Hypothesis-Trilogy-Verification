# Numerical Verification Suite — A Three-Part Trilogy on the Riemann Hypothesis (72 Pages)
## $\mathcal{P}\mathcal{T}$-Symmetric Spectral Theory, Gauss–Ruelle–Perron–Frobenius Transfer Dynamics, and the Bergman–Poisson Subharmonic Bridge

**Author:** **Dr. Aziz Arbai**  
**Affiliations:**  
1. *École des Nouvelles Sciences de l'Ingénierie (ENSI), Tangier, Morocco*  
2. *Laboratoire des Systèmes, Contrôle et Décision (LSCD), Tangier, Morocco*  
**Contact:** `arbai.aziz@ensi.ma` / `arbaiaziz555@gmail.com`

---

## Official Open-Access Preprints on HAL Open Science

This repository provides the open-source numerical verification suite (Python script and interactive Jupyter/Colab Notebook) accompanying the three-part mathematical treatise (72 pages total) published on **HAL Open Science**:

* **Part I (26 pages):** *A $\mathcal{P}\mathcal{T}$-Symmetric Ruelle–Perron–Frobenius Framework for the Riemann Hypothesis: Pseudo-Hermitian Metric Rigidity, Kato Exceptional Points, and Báez–Duarte Density*  
  **HAL Id:** [`hal-05852361`](https://hal.science/hal-05852361) — URL: <https://hal.science/hal-05852361>
* **Part II (18 pages):** *A Variational Principle for the Parabolic Response Function (Part II): Lyapunov Scale-Dissipation, Energy Curvature, and the Geometric Prohibition of Off-Critical Zeros*  
  **HAL Id:** [`hal-05852389`](https://hal.science/hal-05852389) — URL: <https://hal.science/hal-05852389>
* **Part III (28 pages):** *The Bergman–Poisson Subharmonic Bridge and Pick–Loewner Bilinear Coercivity (Part III): Coboundary Pinning at $z=1$, Green Capacity Bounds, and Off-Diagonal Phase Dominance*  
  **HAL Id:** [`hal-05852411`](https://hal.science/hal-05852411) — URL: <https://hal.science/hal-05852411>

---

## Mathematical Overview (English)

This three-part research program unifies the Hilbert–Pólya $\mathcal{P}\mathcal{T}$-symmetric spectral paradigm, the Nyman–Beurling–Báez–Duarte $L^2(0,1)$ approximation criterion, the Ruelle–Perron–Frobenius transfer operator $\mathcal{L}_s$ of the Gauss continued-fraction map $T(x) = \{1/x\}$ on the Hardy space $H^2(\mathcal{D})$, and Bergman–Poisson subharmonic potential theory:

1. **Weinstein–Aronszajn Rank-One Isolation & $O(n^{-5/2})$ Core Super-Convergence (Part I):** Projecting the meromorphically continued Gauss transfer operator onto $H^2(\mathcal{D}) = \mathbb{C}|1\rangle \oplus H_0^2(\mathcal{D})$ ($H_0^2(\mathcal{D}) = \{f \in H^2(\mathcal{D}) : f(0) = 0\}$) isolates the Hurwitz rank-one channel $N_s$ ($N_s^2 = \zeta(2s)N_s$) and yields the compressed parabolic core $\widetilde{\mathcal{R}}_s$ with $O(n^{-2\sigma-2}) \le O(n^{-5/2})$ trace-class convergence on $\operatorname{Re}(s) = 1/4$. Any hypothetical off-critical zero $2s_0 = 1/2 + 2\delta + it_0$ ($\delta \in (0, 1/4)$, $\tau_0 = t_0/2$) forces the parabolic response function $\Phi_{\mathrm{core}}(s) = \ell_s((I_{H_0^2} - \widetilde{\mathcal{R}}_s)^{-1}\widetilde{h}_s)$ into the simultaneous two-point symmetric collision:
   $$\Phi_{\mathrm{core}}\left(\frac{1}{4} + \delta + i\tau_0\right) = 1 \qquad \text{and} \qquad \Phi_{\mathrm{core}}\left(\frac{1}{4} - \delta + i\tau_0\right) = 1.$$

2. **Remainder-Free Right Lyapunov Factorization & $L^2$ Radial Convexity (Part II):** The Lyapunov scale-dissipation operator $\mathcal{D}_s = -\partial_\sigma \widetilde{\mathcal{R}}_s$ and boundary functional $\ell_s^{\mathrm{diss}} = -\partial_\sigma \ell_s$ factorize identically on the right without remainder via the positive logarithmic multiplier $(M_{\mathrm{Lyap}}f)(w) = 2\operatorname{Log}(1/w)f(w)$:
   $$\mathcal{D}_s = \widetilde{\mathcal{R}}_s M_{\mathrm{Lyap}}, \qquad \ell_s^{\mathrm{diss}} = \ell_s M_{\mathrm{Lyap}}, \qquad -\frac{\partial \Phi_{\mathrm{core}}}{\partial \sigma}(s) = \ell_s\left(\left(I_{H_0^2} - \widetilde{\mathcal{R}}_s\right)^{-1}\left(M_{\mathrm{Lyap}}\psi_s + \widetilde{h}_s^{\mathrm{diss}}\right)\right).$$

3. **Exact Coboundary Pinning $\psi_s(1) \equiv -1/2$, Divisor-Discrepancy Series $c_N^{(0)} = d(N-1) - d(N)$, and Cauchy–Schwarz Collision Coercivity (Part III, Sections 2 & 3):** Exploiting the topological endpoint adjacency $\tau_m(1) = \frac{1}{m+1} = \tau_{m+1}(0)$, Theorem 2.1 proves that $(\widetilde{\mathcal{R}}_s f)(1) = -f(1)$ for all $f \in H_0^2(\mathcal{D})$ and $\widetilde{h}_s(1) = \zeta(2s, 2) - \zeta(2s) \equiv -1$, pinning the resolvent state to the universal constant $\psi_s(1) \equiv -1/2$ across the entire complex plane. This eliminates the non-dissipative $n=1$ mode ($\ln 1 = 0$), splits $\Phi_{\mathrm{core}}(s) = -1/2 + \Phi_{\ge 2}(s)$, and raises the collision threshold to $\Phi_{\ge 2}(1/4 \pm \delta + i\tau_0) = 3/2$ ($\mathcal{E}_{\ge 2, \tau_0}(1/4 \pm \delta) = 9/4 = 2.25$). Theorem 3.1 proves that continued-fraction convergent denominators cancel identically, reducing the leading response to the divisor-discrepancy Dirichlet series:
   $$\Phi_{0, \ge 2}(s) = -\frac{1}{2^{2s}} + \sum_{N=3}^{\infty} \frac{d(N-1) - d(N)}{N^{2s}} = \sum_{N=2}^{\infty} \frac{c_N^{(0)}}{N^{2s}}.$$
   Furthermore, Proposition 3.4 (Equations 3.16–3.17) establishes the unconditional Cauchy–Schwarz lower bound at $\sigma_\pm = 1/4 \pm \delta$:
   $$\sum_{n=2}^{\infty} \frac{4\ln n}{n^{\frac{3}{2} \pm 2\delta}} \left|g_{\sigma_\pm + i\tau_0}\left(\frac{1}{n}\right)\right|^2 \ge \frac{9\ln 2}{\zeta\left(\frac{3}{2} \pm 2\delta\right) - 1} > 0, \qquad \forall \tau_0 \in \mathbb{R}.$$

4. **Quadratic Saddle Cancellation at $M_* = \frac{\tau_0^2}{\pi^2 k}$ and Shifted Divisor Closure $-\Delta_h^2 D_2(N; h)$ (Part III, Section 5):** Combining Abel–Voronoi summation, 2D Bergman–Poisson vertical disk averaging (Theorem 5.4(iv), which lowers the collective Voronoi exponent from $\frac{1}{3} - 2\delta$ to $-\frac{2}{3} - 2\delta < 0$ across all $\delta \in (0, 1/4)$), and Deshouillers–Iwaniec Kloosterman bounds on the negative second discrete difference $-\Delta_h^2 D_2(N; h)$ of shifted divisor correlations (Proposition 5.5), Theorem 5.6 establishes the strict radial energy drop $\mathcal{E}_{\ge 2, \tau_0}(1/4 + \delta) < \mathcal{E}_{\ge 2, \tau_0}(1/4 - \delta)$, forbidding off-critical collisions via Rolle's Theorem and confining all non-trivial zeros of $\zeta(z)$ to $\operatorname{Re}(z) = 1/2$.

---

## Présentation Mathématique (Français)

Ce dépôt contient les outils de vérification numérique (script Python `.py` et cahier interactif Jupyter/Colab `.ipynb`) associés à la Trilogie de 72 pages (26 + 18 + 28 pages) publiée sur **HAL Open Science** :

1. **Expérience 1 (Théorème 2.1 & Corollaire 2.2 de la Partie III) :** Vérification numérique du télescopage exact de cobord $(\widetilde{\mathcal{R}}_s f)(1) = -f(1)$ en $z=1$ et de l'épinglage universel $\psi_s(1) \equiv -1/2$, qui élimine le mode neutre $n=1$ ($\ln 1 = 0$) et amplifie le seuil de collision symétrique à $\Phi_{\ge 2}(1/4 \pm \delta + i\tau_0) = 3/2$ ($\mathcal{E}_{\ge 2, \tau_0}(1/4 \pm \delta) = 9/4 = 2.25$).
2. **Expérience 2 (Théorème 3.1 de la Partie III) :** Vérification à la précision machine ($\sim 10^{-15}$) de l'annulation des dénominateurs des réduites $n^{-2s}[(k+1/n)^{-2s} - k^{-2s}] = (nk+1)^{-2s} - (nk)^{-2s}$ et de l'identité de la série de Dirichlet de discrépance des diviseurs $c_N^{(0)} = d(N-1) - d(N)$.
3. **Expérience 3 (Proposition 3.4, Théorèmes 3.3, 5.3 & 5.6 de la Partie III) :** Vérification de la borne inférieure de Cauchy–Schwarz aux abscisses symétriques $\sigma_\pm = 1/4 \pm \delta$ (Éq. 3.16–3.17), de l'élimination de la croissance en $|s|$ sur la densité lisse d'Abel–Voronoi ($< 0.61 < 3/2$), et de la dominance diagonale en sinus hyperbolique $\mathcal{E}_{\ge 2, \tau_0}(1/4+\delta) < \mathcal{E}_{\ge 2, \tau_0}(1/4-\delta)$.
4. **Expérience 4 (Section 5 & Section 6.2 de la Partie III) :** Génération des figures haute résolution illustrant le profil d'énergie radiale avec l'obstruction géométrique de Rolle et l'abaissement successif des exposants haute fréquence $\alpha_1(\delta), \alpha_2(\delta), \alpha_{\mathrm{near}}(\delta), \alpha_3(\delta) = -\frac{2}{3} - 2\delta < 0$ sur toute la bande $\delta \in (0, 1/4)$.

---

## Summary of Numerical Verification Results

| Numerical Experiment | Theorem / Equation Verified (Part III) | Observed Accuracy / Value | Mathematical Conclusion |
| :--- | :--- | :--- | :--- |
| **Experiment 1: Coboundary Pinning at $z=1$** | Theorem 2.1, Eq. (2.2) & (2.5) | Truncation error $2.19 \times 10^{-7}$; $\psi_s(1) = -0.5000000000$ | Confirms $(\widetilde{\mathcal{R}}_s f)(1) = -f(1)$ and $\psi_s(1) \equiv -1/2$ |
| **Experiment 2: Divisor-Discrepancy Series** | Theorem 3.1, Eq. (3.1), (3.2) & (3.3) | Max error $1.29 \times 10^{-15}$ (machine precision) | Confirms $c_N^{(0)} = d(N-1) - d(N)$ free of $\|s\|$-prefactors |
| **Experiment 3: Cauchy–Schwarz Lower Bound** | Proposition 3.4, Eq. (3.16) & (3.17) | Lower bound $\ge \frac{9\ln 2}{\zeta(3/2 \pm 2\delta)-1} > 0$ | Prevents diagonal dissipation from vanishing at $\sigma_\pm = 1/4 \pm \delta$ |
| **Experiment 4: Dominance & Energy Drop** | Theorems 3.3, 5.3 & 5.6, Eq. (5.29)–(5.30) | Strict energy drop $\mathcal{E}(1/4-\delta) > \mathcal{E}(1/4+\delta)$ | Rules out $\mathcal{E}_{\ge 2, \tau_0}(1/4 \pm \delta) = 9/4$ via Rolle's Theorem |

---

## Repository Structure & Quick Start

* `Verification_Trilogie_Hypothese_de_Riemann_Arbai.ipynb`: Interactive Jupyter / Google Colab Notebook with formatted LaTeX derivations, executable Python cells, pre-computed output tables, and embedded matplotlib figures.
* `verify_riemann_trilogy_arbai.py`: Standalone Python script executing the numerical verification suite in the terminal.

### Running Locally

Ensure you have Python $3.8+$ with `numpy` and `matplotlib` installed:

```bash
pip install numpy matplotlib
python verify_riemann_trilogy_arbai.py
```

---

## Citation (BibTeX)

If you use or reference this work, please cite the three treatises on HAL Open Science:

```bibtex
@unpublished{Arbai2026Part1,
  author = {Arbai, Aziz},
  title  = {A $\mathcal{P}\mathcal{T}$-Symmetric Ruelle--Perron--Frobenius Framework for the Riemann Hypothesis: Pseudo-Hermitian Metric Rigidity, Kato Exceptional Points, and B{\'a}ez--Duarte Density},
  note   = {HAL Open Science Preprint (Part I, 26 pages), HAL Id: hal-05852361},
  url    = {https://hal.science/hal-05852361},
  year   = {2026}
}

@unpublished{Arbai2026Part2,
  author = {Arbai, Aziz},
  title  = {A Variational Principle for the Parabolic Response Function (Part II): Lyapunov Scale-Dissipation, Energy Curvature, and the Geometric Prohibition of Off-Critical Zeros},
  note   = {HAL Open Science Preprint (Part II, 18 pages), HAL Id: hal-05852389},
  url    = {https://hal.science/hal-05852389},
  year   = {2026}
}

@unpublished{Arbai2026Part3,
  author = {Arbai, Aziz},
  title  = {The Bergman--Poisson Subharmonic Bridge and Pick--Loewner Bilinear Coercivity (Part III): Coboundary Pinning at $z=1$, Green Capacity Bounds, and Off-Diagonal Phase Dominance},
  note   = {HAL Open Science Preprint (Part III, 28 pages), HAL Id: hal-05852411},
  url    = {https://hal.science/hal-05852411},
  year   = {2026}
}
```

---

## License

This project and its accompanying treatises are distributed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.
