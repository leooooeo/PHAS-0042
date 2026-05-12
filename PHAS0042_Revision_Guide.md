# PHAS0042 — Quantum Mechanics
## Thorough Revision Guide

Built from analysis of **all past papers, all PSTs, and all Assessed
Problem Sheets** available in this repo:

* **7 past papers**: 2018, 2019, 2020/21, 2022/23 Practice, 2022/23, 2023/24, 2024/25
* **4 PSTs**: PST1 (Dirac/basis), PST2 (uncertainty/OAM), PST3 (spin-½, CG),
  PST4 (perturbation theory)
* **3 Assessed Problem Sheets**: PS1 2025 (Dirac, basis, TDSE), PS2 2024
  (ladder uncertainty + 2 coupled QHOs), PS3 2024 (NV centre + CG + L·S)

User has confirmed the PSTs and Problem Sheets are **identical** between
2024/25 and 2025/26 cohorts (the lecturer didn't change them), so the
trends below carry over directly.

---

## 1. How this guide was built (read this first)

The PHAS0042 write-up is large and reads like a textbook; the
**exam recycles a small set of techniques**. By tagging every PST,
Problem Sheet and past-paper sub-question against the syllabus I
identified the 6 core skills the exam actually tests, and built a
priority matrix so you know what to drill.

The course is **derivation-heavy** (unlike PHAS0040 which is
memorisation-heavy). So the revision loop is:

> **read notes → close → re-derive the recipe from scratch → check →
> drill the recurring problem types.**

Each section below gives you (a) where it has been tested, (b) the
key equations typeset, (c) closed-book recall prompts, (d) traps.

---

## 2. Format facts you must know cold

* Since **2020/21** the exam is **3 questions, answer all**.
* Duration: **3 hours**.
* Materials booklet attached — formula sheet includes ladder operators,
  J± action, perturbation formulae, variational principle, Pauli
  matrices, **Clebsch–Gordan coefficient table**, Slater determinant,
  CHSH inequality.
* Each question ~20 marks and **bundles 2–3 techniques**.

---

## 3. The big picture: 6 core skills

| # | Skill | Used in |
|---|---|---|
| **S1** | **QHO ladder algebra** (â±, [â−,â+]=1, x̂,p̂ in ladder form) | every paper + PS2 + PST4 |
| **S2** | **Matrix representation of Ĥ in a chosen basis** | every paper + every PS |
| **S3** | **Perturbation theory** (1st + 2nd order, occasionally degenerate) | every paper + PST4 + PS3 |
| **S4** | **Variational method** | every recent paper + 2018/2019 |
| **S5** | **Coupling two angular momenta** (S₁·S₂, CG coefficients, total J basis) | every paper + PST3 + PS3 |
| **S6** | **Change of basis** (d=Sc, A^(χ) = SA^(ψ)S†) | recurring + PS1 + PST1 |

**>90% of every exam paper** is some combination of these six.

---

## 4. Topic priority matrix

Counts are out of the **5 most recent papers** (2020/21, 22/23 Practice,
22/23, 23/24, 24/25). PST/Problem-Sheet column tells you what was
also drilled in coursework.

| Topic | Past papers | PST/PS | Marks | Tier |
|---|---|---|---|---|
| **QHO ladder + matrix elements** | 5/5 | PS2, PST4 | 8–15 | **A — must** |
| **Perturbation theory (non-deg)** | 5/5 | PST4, PS3 | 6–13 | **A — must** |
| **Two-spin-½ coupling, singlet/triplet** | 5/5 | PST3, PS3 | 10–17 | **A — must** |
| **Variational method** | 5/5 | — | 6–10 | **A — must** |
| **Spin-½ Pauli / σ·n̂** | 5/5 | PS1, PST3 | 4–8 | **A — must** |
| **Change of basis** d=Sc, A^(χ)=SA^(ψ)S† | 3/5 | PS1, PST1 | 5–13 | **A — high** |
| **Angular momentum ladder derivations** | 3/5 | PST2, PST3 | 3–10 | **B — high** |
| **Higher-spin / j₁≠½ coupling (j₁=1, S=1 NV)** | 2/5 + 2019 | PS3 (NV!), PST3 (CG j=3/2, j=2) | 8–13 | **B — high** ⚠ |
| **Two-mode coupled QHOs** | 1/5 (22/23 Q1) | **PS2 Q2 verbatim** | 7+ | **B — high** ⚠ |
| **Orbital angular momentum commutators [L_i,L_j], [L²,H]** | 0/5 recent (2018 B8) | **PST2 Q3** | 3–6 | **B — medium** |
| **Identical particles / symmetry** | 2/5 | — | 3–9 | B — high |
| **Degenerate perturbation theory** | 2/5 | — | 5–8 | C — medium |
| **TDSE / time evolution** | 1/5 | PS1 Q3 | 5–6 | C — light |
| **Coherent states** | 1/5 (20/21 Q1d) | — | 5 | C — light |
| **CHSH/Bell inequality** | 0/5 | — (in booklet) | ? | C — outside bet |

**Critical observation (different from V1 of this guide).** The PSTs/PS
reveal two topics that look "low frequency" in the past papers but
are actually being **set up to appear**:

> **(i) NV-colour-centre style S=1 spin Hamiltonians with anisotropic
> ("strain") perturbations** — this is the *entire content* of
> Assessed PS3 2024, was the basis for 2019 Q9, and is unmistakably
> the lecturer's pet topic. **Strong candidate for 2025/26 Q1 or Q2.**
>
> **(ii) Two-mode coupled quantum harmonic oscillators** — Assessed
> PS2 2024 builds the 4×4 coupled-QHO matrix verbatim with the same
> coupling form (â+â− y² etc.) as 2022/23 Q1 of the exam. **Strong
> candidate for 2025/26 Q3.**

These two predictions are now upgraded from "outside bet" to "likely",
because PSTs/PS materials track the exam style closely.

---

## 5. The structural template of every recent paper

| Q | Pattern |
|---|---|
| **Q1** | Spin-½ matrices + change of basis (bookwork ~5m) **OR** identical particles + variational. Tests S2, S4, S6, Pauli matrices. |
| **Q2** | Two-particle angular momentum: S₁·S₂ + extra term, build matrix in product basis, diagonalise. Tests S5. |
| **Q3** | QHO with perturbation: 1st + 2nd order corrections, often a variational comparison. Tests S1+S3+S4. |

Knowing this template lets you plan time before opening the paper.

---

## 6. Topic-by-topic deep dive

### S1 — QHO ladder operator algebra (Tier A, 5/5)

**Where this has been tested**
* 2018 Q9: anharmonic −λx̂³, 2nd-order ground state
* 2019 Q8: xp and px on |n⟩, ⟨px⟩, ⟨[x,p]⟩
* 2020/21 Q1: QHO + g₁x̂p̂ + g₂p̂x̂; coherent state ⟨α|â+|α⟩=α*
* Practice 22/23 Q1: QHO + k₂x̂² (stiffness perturbation)
* 2022/23 Q1: Pair of QHOs with ig(â+−â−); [â+â−, â±]; uncertainty
* 2023/24 Q3: QHO + λx̂
* 2024/25 Q3: QHO + λκx̂⁴; (â−+â+)⁴|0⟩
* **PS2 2024 Q1**: [â−, â+]=1; Δx̂Δp̂ for (1/√3)|0⟩ + (√2/√3)|1⟩
* **PS2 2024 Q2**: 2 uncoupled QHOs with V = g(â−x + â+x)(â−y − â+y) — 4×4 matrix
* **PST4 Q2**: 2023/24 Q3 worked through

**Key equations**

```
â+ = (1/√2)(αx̂ − ip̂/(ℏα)),  â− = (1/√2)(αx̂ + ip̂/(ℏα)),  α = √(mω/ℏ)
[â−, â+] = 1
Ĥ_QHO = ℏω(â+â− + 1/2) = ℏω(N̂ + 1/2)
â−|n⟩ = √n |n−1⟩      â+|n⟩ = √(n+1) |n+1⟩
x̂ = (1/(α√2))(â+ + â−)
p̂ = i(ℏα/√2)(â+ − â−)
```

**Matrix elements to know cold**

```
⟨k|x̂|n⟩ = (1/(α√2)) [ √(n+1) δ_{k,n+1} + √n δ_{k,n-1} ]
⟨k|p̂|n⟩ = i(ℏα/√2) [ √(n+1) δ_{k,n+1} − √n δ_{k,n-1} ]
```

**(â− + â+)^k recipe** — essential for x̂^k perturbations:

```
(â− + â+)² |0⟩ = |0⟩ + √2 |2⟩
(â− + â+)³ |0⟩ = 3|1⟩ + √6 |3⟩       (used 2018 Q9)
(â− + â+)⁴ |0⟩ = 3|0⟩ + 6√2 |2⟩ + √24 |4⟩  (verbatim 2024/25 Q3c)
```

**Δx̂ Δp̂ for a superposition |ψ⟩ = c₀|0⟩ + c₁|1⟩ + ...** (PS2 2024 Q1b
and PST2 Q2): compute ⟨x̂⟩, ⟨x̂²⟩, then Δx̂² = ⟨x̂²⟩ − ⟨x̂⟩². For
states with only |0⟩,|1⟩,|2⟩ components, ⟨x̂⟩ ≠ 0 in general, but
the algebra is finite — write it out term-by-term.

**Closed-book recall prompts**
* Derive [â−, â+] = 1 from [x̂, p̂] = iℏ. (PS2 Q1a)
* Write Ĥ_QHO as ℏω(N̂ + 1/2) from â±.
* For |ψ⟩ = (1/√3)|0⟩ + (√2/√3)|1⟩, compute Δx̂, Δp̂, verify Δx̂Δp̂ ≥ ℏ/2. (PS2 Q1b-d verbatim)
* (â− + â+)³|0⟩ = ? and (â− + â+)⁴|0⟩ = ?
* For PST2 state (1/√6)|0⟩ + (√2/√6)|1⟩ + (1/√6)|2⟩, compute ⟨p̂⟩, ⟨p̂²⟩, Δp̂.

**Common traps**
* â+† = â− (NOT â+).
* Sign on the **i** in p̂ → easy to lose track in x̂p̂ vs p̂x̂.
* For x̂² (or higher even powers), forget the term proportional to |n⟩
  (the "no-change" diagonal piece) and you'll get the wrong E^(1).

---

### S3 — Perturbation theory (Tier A, 5/5 papers + entire PST4 + PS3)

**Where this has been tested**
* 2018 Q7 (square well), Q9 (anharmonic −λx̂³ 2nd-order)
* 2020/21 Q3: well + λC sin(3bx)
* Practice 22/23 Q1: QHO + k₂x̂²
* 2022/23 Q3: Aσ_x + ασ_z (1st + 2nd); **3-level degenerate**
* 2023/24 Q3: QHO + λx̂
* 2024/25 Q3: QHO + λκx̂⁴
* **PST4 Q1**: Aσ_z + α(σ_x+σ_z) — 1st-order shift; compares with exact 2×2 eigenvalues
* **PST4 Q2**: 2023/24 Q3 with full worked solution
* **PS3 Q1**: NV centre S=1 with strain — find eigenvalues of Ŝ²_x − Ŝ²_y

**Key equations**

```
E_n^(1) = ⟨ψ_n^(0)| Ŵ |ψ_n^(0)⟩
E_n^(2) = Σ_{k ≠ n}  |W_kn|² / ( E_n^(0) − E_k^(0) )
|ψ_n^(1)⟩ = Σ_{k ≠ n}  W_kn / ( E_n^(0) − E_k^(0) ) |ψ_k^(0)⟩
```

**The workflow for "perturb a QHO" (this is universal):**
1. Write Ŵ in terms of â±.
2. Compute Ŵ|n⟩ as a finite sum of |n ± k⟩.
3. E_n^(1) = ⟨n|Ŵ|n⟩ — keep only the |n⟩ piece. For odd powers of x̂,
   E^(1) = 0 by parity.
4. E_n^(2): keep only |k⟩ that Ŵ|n⟩ couples to. Denominators ℏω(n − k).

**Worked example (2024/25 Q3) memorise the structure:**

```
For Ŵ = λκx̂⁴ = λγ(â− + â+)⁴   where γ = ℏ²/(4·m²ω²·…) — check the units!
Ŵ |0⟩ = λγ [ 3|0⟩ + 6√2 |2⟩ + √24 |4⟩ ]
E_0^(1) = 3 λγ
E_0^(2) = − [ (6√2)² / (2ℏω) + 24 / (4ℏω) ] (λγ)² = −42 (λγ)²/(ℏω)
```

**For general n-th level x̂⁴ correction (slick trick from 2024/25 Q3f):**

```
⟨n|(â−+â+)⁴|n⟩ = ⟨ϕ|ϕ⟩  where |ϕ⟩ = (â−+â+)²|n⟩
```

Then |ϕ⟩ = (â−+â+)²|n⟩ = √(n(n−1))|n−2⟩ + (2n+1)|n⟩ + √((n+1)(n+2))|n+2⟩,
and ⟨ϕ|ϕ⟩ = n(n−1) + (2n+1)² + (n+1)(n+2).

**When is perturbation theory valid?** (2022/23 Q3a-iii; PST4 Q1a):
when |W_kn| ≪ |E_n − E_k| (the perturbation matrix element is smaller
than the unperturbed energy gap). If the perturbation is comparable
to or larger than the gap, you need a different method (diagonalise
directly, or switch the role of Ĥ₀ and Ŵ if Ŵ becomes large).

**Closed-book recall prompts**
* Write E_n^(1) and E_n^(2) from memory.
* Why E^(1) = 0 for x̂ or x̂³ perturbations? (Parity.)
* For QHO + λx̂, derive E_0^(2) = −λ²/(2mω²). (2023/24 Q3 verbatim, in PST4.)
* For Aσ_z + α(σ_x+σ_z), find 1st-order shift to both eigenvalues of Ĥ₀ = Aσ_z. (PST4 Q1b verbatim.)
* When does PT fail? (When λW becomes comparable to gap.)

**Common traps**
* Including k = n in the second-order sum.
* Wrong sign on denominator (E_n − E_k): for **ground-state** 2nd order,
  every denominator is **negative**, so the second-order shift is **negative**.
* Forgetting to **square** matrix elements in E^(2).

---

### S4 — Variational method (Tier A, 5/5)

**Where this has been tested**
* 2018 Q10: δ-function potential, Gaussian trial
* 2019 Q10: V = c|x|, Gaussian trial
* 2020/21 Q3b: well + λC sin(3bx), trial ψ₁ + q ψ₂
* Practice 22/23 Q3b: V = cx, trial Ax e^(−αx)
* 2023/24 Q3c-e: QHO + λx̂, **trial |ψ_θ⟩ = cos θ|0⟩ + sin θ|1⟩**
* 2024/25 Q1d-e: coupled spins, **trial |↑↑⟩ + a|↓↓⟩**

**Recipe (always identical)**

1. Pick / receive trial state |ψ_α⟩.
2. Compute ⟨ψ_α|Ĥ|ψ_α⟩ and ⟨ψ_α|ψ_α⟩.
3. Minimise E(α) = ⟨H⟩ / ⟨ψ|ψ⟩ over α (set ∂E/∂α = 0).
4. Plug back → upper bound for E_0.

**The two flavours that recur:**

**(a) Continuous-parameter trial** — set d⟨H⟩/dα = 0 analytically.
Standard integrals given.

**(b) Linear combination of basis eigenstates** |ψ_θ⟩ = cos θ|0⟩ + sin θ|1⟩.
Cross-term gives 2 cos θ sin θ Re⟨0|H|1⟩ → use double-angle identities
to find optimal θ. **This is the recent trend — the last two papers
(23/24 and 24/25) both used this flavour.** Drill it.

**Closed-book recall prompts**
* State the variational inequality.
* For |ψ_θ⟩ = cos θ|0⟩ + sin θ|1⟩ applied to QHO + λx̂, derive
  ⟨H⟩_θ and find tan 2θ. (23/24 Q3c-d verbatim.)
* For trial |↑↑⟩ + a|↓↓⟩ applied to Ĥ = −Δ(σx⊗σx + σz⊗σz),
  find optimal a and resulting energy. (24/25 Q1d verbatim.)
* How can the result be improved? (Add more parameters / basis states.)

**Common traps**
* Forgetting to normalise the trial state.
* Setting the trial state equal to a single basis state and getting
  the unperturbed answer — make sure your parametrisation actually
  spans the variational space.

---

### S5 — Adding angular momenta / two-particle spin (Tier A, 5/5)

This is the most heavily-weighted technique in the entire course.
**Q2 of every recent paper has been built around it.**

**Where this has been tested**
* 2018 A5+B8: singlet/triplet, L̂+Ŝ basis
* 2019 A5+B9: singlet/triplet gap; **NV centre S=1**
* 2020/21 Q2d-e: C₁₂ S₁·S₂ + β₀(Ŝ_z1+Ŝ_z2)
* Practice 22/23 Q2: AŜ² + βŜ_z²
* 2022/23 Q2: **j₁=1, j₂=½**, C₁₂ J₁·J₂ + A(Ĵ_z1+Ĵ_z2)²
* 2023/24 Q2: λ S₁·S₂ + B_z(Ŝ_z1+Ŝ_z2) → 4×4 matrix
* 2024/25 Q2: Γ S₁·S₂ + λŜ_z²
* **PST3 Q5**: **CG coefficients for j₁=3/2, j₂=½ and j₁=2, j₂=½**
* **PS3 Q2**: **Two coupled NV systems**, both S=1, full CG decomposition
* **PS3 Q3**: L̂+Ŝ general — show |ℓ,ℓ; s,s⟩ is an eigenstate of Ĵ²

**Key identities (memorise!)**

```
Ŝ² = Ŝ₁² + Ŝ₂² + 2 Ŝ₁·Ŝ₂
Ŝ₁·Ŝ₂ = (1/2)(Ŝ² − Ŝ₁² − Ŝ₂²)
       = Ŝ_z1 Ŝ_z2 + (1/2)(Ŝ_{1+} Ŝ_{2−} + Ŝ_{1−} Ŝ_{2+})

Two spin-½ singlet/triplet:
|1,+1⟩ = |↑↑⟩
|1, 0⟩ = (1/√2)( |↑↓⟩ + |↓↑⟩ )
|1,−1⟩ = |↓↓⟩
|0, 0⟩ = (1/√2)( |↑↓⟩ − |↓↑⟩ )

Eigenvalues of Ŝ₁·Ŝ₂:
Triplet (S=1): +ℏ²/4
Singlet (S=0): −3ℏ²/4
```

**Standard workflow:**
1. Write Ŝ₁·Ŝ₂ via ladders.
2. Build 4×4 matrix in product basis {|↑↑⟩, |↑↓⟩, |↓↑⟩, |↓↓⟩}.
3. Reorder so it block-diagonalises (|↑↑⟩,|↓↓⟩ block vs |↑↓⟩,|↓↑⟩ block).
4. Diagonalise each 2×2.
5. Identify eigenvectors as |S,M⟩ where possible.

**For higher j (PS3, PST3, 2022/23 paper):**
* **j₁=1, j₂=½**: J = 3/2 or 1/2. Total dim = 6.
  Use CG table from booklet to write |J,M⟩ in product basis.
* **Two S=1 NVs (PS3 Q2)**: J = 0, 1 or 2. Total dim = 9.
  Decompose |0,0⟩₁|0,0⟩₂, etc, using CG.

**For L̂ + Ŝ (PS3 Q3 + 2018 B8):**

```
Ĵ² = L̂² + Ŝ² + 2L̂·Ŝ = L̂² + Ŝ² + 2L̂_z Ŝ_z + L̂_+Ŝ_− + L̂_−Ŝ_+
```

The "stretched" state |ℓ,ℓ; s,s⟩ is automatically an eigenstate of Ĵ²
with J = ℓ + s (because L̂_+ and Ŝ_+ kill it). Eigenvalue (ℓ+s)(ℓ+s+1)ℏ².

**Closed-book recall prompts**
* List the four |S,M⟩ states for two spin-½.
* Show Ŝ₁·Ŝ₂ = (1/2)(Ŝ²−Ŝ₁²−Ŝ₂²). (Practice 22/23, 23/24, 24/25 ALL ask this.)
* Express Ŝ₁·Ŝ₂ using ladders.
* In the singlet, compute ⟨Ŝ_z1⟩, ⟨Ŝ_z2⟩, ⟨Ŝ_{1x}Ŝ_{2x}⟩. (24/25 Q2c)
* For j₁=3/2, j₂=½, write |J=2, M=1⟩ in the product basis. (PST3 Q5a, using CG table.)
* Show |ℓ,ℓ; s,s⟩ is an eigenstate of Ĵ² with eigenvalue (ℓ+s)(ℓ+s+1)ℏ².

**Common traps**
* **|↑↓⟩ is not an eigenstate of Ŝ².** Product basis only diagonalises Ŝ_z, Ŝ₁², Ŝ₂².
* Forgetting Ŝ_+|↑⟩ = 0 — many off-diagonal elements vanish automatically.
* Eigenvalue of Ŝ² is S(S+1)**ℏ²**, not S(S+1).

---

### NEW PRIORITY: NV-centre / S=1 anisotropic-spin Hamiltonians (Tier B → A)

The lecturer is **clearly invested in this topic**: it's the entire
Assessed PS3 (2024 — unchanged for 2025), appeared verbatim on 2019
Q9, and the 2024/25 paper hinted at it via two-spin operators in
coupled form. Worth a dedicated drill.

**The canonical Hamiltonian (PS3 Q1; 2019 Q9d):**

```
Ĥ = D Ŝ_z² − γ Ŝ·B      (the "crystal field" + Zeeman term)
   + Ĥ_strain
where Ĥ_strain = ε_y(Ŝ_x Ŝ_y + Ŝ_y Ŝ_x) + ε_x(Ŝ_x² − Ŝ_y²)
              = (r/2)[Ŝ_+² e^(−iφ) + Ŝ_−² e^(iφ)]
with r = √(ε_x² + ε_y²),  tan φ = ε_y / ε_x.
```

**The recipe**:
1. **S=1 ladder operators**:
   Ŝ_+|1,−1⟩ = √2 ℏ |1,0⟩, Ŝ_+|1,0⟩ = √2 ℏ |1,1⟩, Ŝ_+|1,1⟩ = 0
   Ŝ_z eigenvalues are −ℏ, 0, +ℏ.
2. The strain term **couples |1,1⟩ ↔ |1,−1⟩** through Ŝ_±². The
   |1,0⟩ state stays decoupled.
3. Build 3×3 matrix in the |1,1⟩, |1,0⟩, |1,−1⟩ basis. Reorder so
   it block-diagonalises into a 2×2 (the ±1 block) and a 1×1 (the 0 state).
4. Diagonalise the 2×2 → eigenvalues D ± r, eigenvectors are symmetric/
   antisymmetric combinations of |1,±1⟩.

**Closed-book recall prompts (PS3 Q1)**
* Express ε_y(Ŝ_xŜ_y + Ŝ_yŜ_x) + ε_x(Ŝ_x² − Ŝ_y²) in terms of Ŝ_±².
* Build the matrix of (Ŝ_x² − Ŝ_y²) for S=1.
* Diagonalise the S=1 Hamiltonian D Ŝ_z² + (Ŝ_+² + Ŝ_−²)·(r/2).
* For two coupled S=1 NV systems (PS3 Q2), compute ⟨Ŝ_{z1}⟩ in |J=1,M=1⟩.

---

### S2 — Matrix representation of operators (Tier A, connective tissue)

Every question uses this. Recipe:

```
H_{j,k} = ⟨φ_j| Ĥ |φ_k⟩
```

Then diagonalise. Tips:

* Truncate to the smallest sensible block.
* **Always check Hermiticity** — examiners explicitly ask (20/21 Q1b).
* **Reorder rows/columns** to block-diagonalise (4×4 → two 2×2s is the
  bread-and-butter of every two-spin question; 3×3 → 2×2 + 1×1 is
  the bread-and-butter of NV-style problems).

---

### S6 — Change of basis (Tier A in PS coverage; B in exam frequency)

**Where this has been tested**
* 2019 B7: derive d = Sc, A^(χ) = S A^(ψ) S†
* 2020/21 Q2a-c: rotation matrix S
* 2023/24 Q1: derive + apply to spin Hamiltonian
* **PST1 Q3**: change of basis with "Lowity" 3×3 matrix
* **PS1 2025 Q2b-c**: derive S = [⟨+|↑⟩, ⟨+|↓⟩ ; ⟨−|↑⟩, ⟨−|↓⟩] for σ_y eigenstates,
  verify unitary, transform H

**Key equations**

```
S_{mn} = ⟨χ_m | ψ_n⟩
d = S c
A^(χ) = S A^(ψ) S†
S is unitary: S† S = I
```

**Standard derivation that gets ~5 marks of free bookwork:** start
from Σ_n |ψ_n⟩⟨ψ_n| = I (closure), insert into ⟨χ_m|Ψ⟩, get
d_m = Σ_n ⟨χ_m|ψ_n⟩ c_n. Then for the operator: A_{mn}^(χ) =
⟨χ_m|Â|χ_n⟩ = Σ_{j,k} ⟨χ_m|ψ_j⟩ A_{jk}^(ψ) ⟨ψ_k|χ_n⟩ = (SA^(ψ)S†)_{mn}.

**Common traps**
* Wrong direction of †. Rule: A^(χ) = S A^(ψ) S†, equivalently
  A^(ψ) = S† A^(χ) S.
* Forgetting that S unitary means S† = S⁻¹.

---

### Spin-½ Pauli matrices (Tier A subskill, every paper)

```
σ_x = (0  1)    σ_y = (0 −i)    σ_z = (1  0)
      (1  0)          (i  0)          (0 −1)

σ_x |↑⟩ = |↓⟩,   σ_z |↑⟩ = |↑⟩,   σ_z |↓⟩ = −|↓⟩

Ŝ_i = (ℏ/2) σ_i

Eigenstates of n̂·σ̂ (polar angles θ, φ):
   |+⟩ = ( cos(θ/2),  sin(θ/2) e^(iφ) )
   |−⟩ = ( sin(θ/2), −cos(θ/2) e^(iφ) )
```

**PS1 2025 Q2 worked example to memorise**: for H = E σ_y, eigenvalues
±E with eigenvectors (1/√2)(|↑⟩ ± i|↓⟩) — note the **i**, which is
the hallmark of σ_y eigenstates.

---

### Angular momentum ladder operators (Tier B, but free marks)

**Standard derivations that have appeared verbatim**
* Show [Ĵ_z, Ĵ_+] = ℏ Ĵ_+ (22/23 Q2a)
* Show Ĵ_+|j,m⟩ ∝ |j,m+1⟩ with coefficient √(j(j+1)−m(m+1)) ℏ (22/23 Q2b, 24/25 Q2a)
* Show Ĵ_± Ĵ_∓ = Ĵ² − Ĵ_z² ± ℏĴ_z (2018 Q8a, 2019 Q9a)
* **Show [L̂_x, L̂_y] = iℏL̂_z** (PST2 Q3a)
* **Show [L̂², L̂_i] = 0** (PST2 Q3b)
* **Show [L̂², Ĥ] = 0 = [L̂_z, Ĥ]** for spherical V(r) (PST2 Q3c)

These are 3–6 mark gimmes if you've practised.

---

### Two-mode coupled QHOs (Tier B → A in PS coverage)

**Where this has been tested**
* 2022/23 paper Q1: pair of QHOs (y and z modes) with perturbation
  ig(â+−â−) — full matrix + uncertainty
* **PS2 2024 Q2**: 2 uncoupled QHOs (x, y) with coupling
  V = g(â−x+â+x)(â−y−â+y) → 4×4 matrix in {|0,0⟩,|0,1⟩,|1,0⟩,|1,1⟩}
* **PS2 2024 Q2c**: variant with V = g₂(â+x â−x ŷ²), 3×3 matrix in n₂=1 sector

**Recipe**: same as single-mode QHO, but now you have **two independent
ladder operator sets** {â±x, â±y}. Acting one set on a product state
|n_x, n_y⟩ only affects that quantum number. Cross-terms like
â+x â−y couple |n_x, n_y⟩ ↔ |n_x+1, n_y−1⟩.

**Common traps**
* Forget that [â±x, â±y] = 0 (different modes commute).
* When the coupling has nested operators like â+x â−x, **simplify first**
  using â+â− = N̂, so V = g₂ N̂_x ŷ² → N̂_x is diagonal in the n_x basis.

---

### Identical particles (Tier B)

**Where this has been tested**
* 2018, 2019 A6 bookwork
* Practice 22/23 Q3a: bosons / fermions in well + spin state
* 2024/25 Q1a-b: symmetric vs antisymmetric vs product; He ground state

**Key facts**
* Bosons (integer spin): total wavefunction symmetric.
* Fermions (half-integer spin): total wavefunction antisymmetric.
* He ground state: both electrons in 1s (spatial symmetric) → spin part
  must be antisymmetric → **singlet** = (|↑↓⟩ − |↓↑⟩)/√2.
* Slater determinant is the general N-fermion antisymmetriser.
* A **product state** factorises (|↑⟩⊗|↑⟩); an entangled state does not
  (e.g. (|↑↓⟩ ± |↓↑⟩)/√2 are entangled).

---

## 7. Past papers + PSTs/PS by week

### Coursework timeline (this is the lecturer's emphasis curve)

| Week | Tutorial / Sheet | Topic |
|---|---|---|
| 2 | **Assessed PS1** | Dirac, normalisation, orthogonality, basis change (σ_y), TDSE |
| ~3 | PST1 | Wavefunctions ↔ Dirac, change of basis 3×3 |
| ~4 | PST2 | Δp̂ for QHO superposition, OAM commutators |
| 5 | **Assessed PS2** | [â−,â+]=1, Δx̂Δp̂, **two uncoupled QHOs with coupling** |
| ~6 | PST3 | Spin-½ matrix, j=1 matrices, **CG for j=3/2 and j=2** |
| 8 | **Assessed PS3** | **NV S=1 strain Hamiltonian, two coupled NV systems, L+S addition** |
| ~10 | PST4 | Perturbation theory (1st + 2nd) — explicit past-paper drill |

**Pattern**: the 3 assessed sheets walk you through Dirac → ladder
operators → spin coupling, in lock-step with what the exam tests
in Q1, Q3, Q2 respectively. Treating them as exam rehearsals is
essentially correct.

### Past paper summaries

(2018, 2019: old 6+2 format; the others: 3 questions.)

* **2018**: Q9 anharmonic −λx̂³ (2nd order); Q10 variational δ-potential.
* **2019**: Q8 QHO xp/px; **Q9 NV S=1**; Q10 variational V=c|x|.
* **2020/21**: Q1 QHO + g₁x̂p̂+g₂p̂x̂ + coherent state; Q2 change-of-basis +
  two-spin C₁₂S₁·S₂; Q3 well + λC sin(3bx) + variational.
* **22/23 Practice**: Q1 QHO + k₂x̂²; Q2 AŜ²+βŜ_z²; Q3 identical particles
  + variational V=cx.
* **2022/23**: Q1 paired QHOs + perturbation; **Q2 j₁=1, j₂=½**; Q3 spin
  perturbation (1st+2nd) + degenerate 3-level.
* **2023/24**: Q1 change-of-basis + spin H; Q2 two-spin λS₁·S₂+B_z(Ŝ_z1+Ŝ_z2);
  Q3 QHO+λx̂ + variational |ψ_θ⟩.
* **2024/25**: Q1 identical particles + Pauli + variational on coupled-spin
  Hamiltonian; Q2 two-spin Γ S₁·S₂ + λŜ_z² in total-spin basis;
  Q3 QHO+λκx̂⁴.

---

## 8. Predictions for **2025/26**

> Same caveat as before: this is informed pattern-matching across
> 7 papers + 4 PSTs + 3 PS. The PHAS0040 guide author claimed ~60%
> accuracy. Use it to prioritise drilling, not skip topics.

### Confidence: very high (>90%)

1. **QHO + perturbation on Q3** — guaranteed.
2. **Two-particle angular momentum / S₁·S₂ Hamiltonian on Q2** — guaranteed.
3. **Variational method calculation** somewhere on the paper — guaranteed.
4. **Pauli matrix manipulation** somewhere — guaranteed.
5. **At least one ladder-operator derivation** — guaranteed (free marks).

### Confidence: high (60–80%) — refined with PST/PS data

6. **The Q3 QHO perturbation will be one of:**
   * **(a) Cubic λx̂³** — was 2018 Q9, not seen since. The (â−+â+)³|0⟩
     identity is the natural "next harder" from 2024/25's quartic.
   * **(b) Two-mode coupled QHO with a perturbation** — Assessed PS2
     drills this verbatim; 2022/23 Q1 did this. ⚠ **Upgraded to
     equally likely as (a) because PS2 builds exactly this**.
   * (c) Mixed quadratic-linear g(â+²−â−²) or similar.

7. **Q2 will be a two-angular-momentum problem and could escalate to:**
   * **j₁ = 1, j₂ = ½** (last seen 2022/23) — due to return.
   * **Two coupled S=1 NV centres** (entire Assessed PS3 Q2). ⚠ Strong
     candidate because the lecturer has obviously written the PS to
     scaffold for it.
   * Two spin-½ with asymmetric field (B₁ ≠ B₂).

8. **An NV-centre / anisotropic-spin Hamiltonian** appearing somewhere
   in Q1 or Q2: ⚠ **upgraded to 60%+ from "outside bet"** based on
   the entire Assessed PS3 being devoted to it. The specific form
   D Ŝ_z² + r(Ŝ_+² e^(−iφ) + Ŝ_−² e^(iφ))/2 is essentially primed.

9. **Change-of-basis bookwork** (d=Sc, A^(χ)=SA^(ψ)S†) — appeared 23/24
   but not 24/25; PS1 2025 drills it again. ~70% it returns for ~5 marks.

10. **An identical-particles sub-question** — 24/25 had it, Practice
    had it. ~50/50.

### Confidence: medium (30–60%)

11. **Degenerate perturbation theory** — 22/23 Q3 had it. Could appear
    on a paired-QHO problem with |0,1⟩ and |1,0⟩ degenerate.

12. **L̂ + Ŝ addition** (stretched state, etc.) — PS3 Q3 drills it,
    last on exam in 2018. Returns ~40%.

13. **TDSE / time evolution** Û(t) on a 2-state system — PS1 Q3 drills it.
    20/21 Q2 did it. ~35%.

### Confidence: low

14. **Coherent states** (â−|α⟩=α|α⟩) — once in 20/21. Unlikely to repeat.
15. **CHSH/Bell** — in booklet but never examined. Outside bet.

### My single best-guess paper for 2025/26

| Q | Predicted content (refined with PS data) |
|---|---|
| **Q1** | **NV-centre style S=1 Hamiltonian** with strain perturbation: build matrix of D Ŝ_z² + ε(Ŝ_x² − Ŝ_y²) in S=1 basis, diagonalise (block 2×2 + 1×1), find eigenvalues D ± ε / 0. Possibly add a change-of-basis bookwork derivation. ~20 marks. |
| **Q2** | **Two coupled angular momenta, j₁=1, j₂=½** (returning from 22/23) **OR two coupled S=1 NV systems** (from PS3 Q2). Decompose with CG table from booklet, identify total-J eigenstates, compute expectation values. ~20 marks. |
| **Q3** | **Two-mode coupled QHO + perturbation** (from PS2 Q2): rewrite in ladder operators, build matrix in {|0,0⟩,|0,1⟩,|1,0⟩,|1,1⟩}, compute eigenvalues, possibly add a 1st-order PT or variational sub-part. **Backup guess: cubic λx̂³.** ~20 marks. |

Notice this is a **substantial revision** from V1 of the guide:
the PSTs/PS show the lecturer is much more interested in NV-style
S=1 problems and coupled QHOs than the past papers alone suggested.

---

## 9. Suggested 2-week revision plan

**Week 1 — Topic-by-topic active recall**
* Day 1: **S1 (QHO ladder)** — drill 2018 Q9, 2019 Q8, 2024/25 Q3, PS2 Q1. Memorise (â−+â+)² ³ ⁴ |0⟩.
* Day 2: **S3 (perturbation)** — drill PST4 (full!), 23/24 Q3, 24/25 Q3, 2022/23 Q3.
* Day 3: **S4 (variational)** — drill 23/24 Q3c-e, 24/25 Q1d, 2018 Q10, 2019 Q10.
* Day 4: **S5 (two-spin)** — drill 23/24 Q2, 24/25 Q2, Practice Q2, PS3 Q2.
* Day 5: **NV / S=1 system** (PS3 Q1, 2019 Q9d) — practice strain Hamiltonian until you can do it cold. **High-leverage day**.
* Day 6: **S2+S6 (matrix rep + basis change)** — PS1 Q2, PST1, 2023/24 Q1.
* Day 7: review weak spots; do PST2 (OAM commutators) and PST3 (CG coefficients).

**Week 2 — Full timed papers**
* Day 8: 2020/21 closed-book, 3h.
* Day 9: mark + drill weak spots.
* Day 10: 2022/23.
* Day 11: 2023/24.
* Day 12: 2024/25 (most representative).
* Day 13: Practice 2022/23 paper.
* Day 14: error-notebook review + sleep.

---

## 10. The 60-second cheat sheet

```
QHO:    [â−,â+] = 1
        â−|n⟩ = √n |n−1⟩          â+|n⟩ = √(n+1) |n+1⟩
        x̂ = (1/(α√2))(â+ + â−)    p̂ = i(ℏα/√2)(â+ − â−)
        (â−+â+)² |0⟩ = |0⟩ + √2 |2⟩
        (â−+â+)³ |0⟩ = 3|1⟩ + √6 |3⟩
        (â−+â+)⁴ |0⟩ = 3|0⟩ + 6√2 |2⟩ + √24 |4⟩

PT:     E^(1) = ⟨n|Ŵ|n⟩
        E^(2) = Σ_{k≠n} |W_kn|² / (E_n − E_k)
        For x̂^odd perturbations: E^(1) = 0 by parity

Var:    E(α) = ⟨ψ_α|Ĥ|ψ_α⟩/⟨ψ_α|ψ_α⟩ ≥ E_0;  ∂E/∂α = 0
        Trial cos θ|0⟩ + sin θ|1⟩ → use double-angle, tan 2θ at min

Spin:   Ŝ_i = (ℏ/2) σ_i
        σ_y eigenstates: (1/√2)(|↑⟩ ± i|↓⟩)
        Pauli identities as in booklet

J±:     Ĵ_±|j,m⟩ = √(j(j+1) − m(m±1)) ℏ |j,m±1⟩
        [Ĵ_z, Ĵ_±] = ±ℏ Ĵ_±
        Ĵ_+Ĵ_− = Ĵ² − Ĵ_z² + ℏĴ_z

2 spin-½: triplet (|↑↑⟩, (|↑↓⟩+|↓↑⟩)/√2, |↓↓⟩); singlet (|↑↓⟩−|↓↑⟩)/√2
        Ŝ₁·Ŝ₂ = (1/2)(Ŝ² − Ŝ₁² − Ŝ₂²)
                 = Ŝ_z1 Ŝ_z2 + (1/2)(Ŝ_{1+}Ŝ_{2−} + Ŝ_{1−}Ŝ_{2+})
        Triplet eigenvalue: +ℏ²/4;  Singlet: −3ℏ²/4

NV (S=1): Ŝ_+|1,−1⟩ = √2 ℏ|1,0⟩,  Ŝ_+|1,0⟩ = √2 ℏ|1,1⟩
        Strain term: ε_y(Ŝ_xŜ_y+Ŝ_yŜ_x) + ε_x(Ŝ_x²−Ŝ_y²)
                   = (r/2)(Ŝ_+² e^(−iφ) + Ŝ_−² e^(iφ))
        Couples |1,1⟩ ↔ |1,−1⟩; |1,0⟩ decouples

OAM:    [L̂_x, L̂_y] = iℏL̂_z;   [L̂², L̂_i] = 0;   [L̂_z, Ĥ_spherical] = 0

Basis:  d = Sc,  S_{mn} = ⟨χ_m|ψ_n⟩,  A^(χ) = SA^(ψ)S†
        S unitary, so S† = S⁻¹
```

Good luck.
