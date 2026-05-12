# PHAS0042 — Quantum Mechanics
## Thorough Revision Guide (built from past papers)

Built from a topic-by-topic analysis of every accessible past paper:
**2018 (PHAS3226), 2019 (PHAS0042A6UA), 2020/21 (PHAS0042A6UC),
2022/23 Practice Paper, 2022/23 (PHAS0042A6UE), 2023/24 (PHAS0042A6UF),
2024/25 (final paper)** — 7 papers in total.

> **Caveat vs the PHAS0040 guide.** The 0040 guide was built from *5 past
> papers + 3 assessed problem sets + 5 PSTs*. For 0042 only the past papers
> were uploaded to this repo, so the topic-priority matrix here is based on
> exam questions alone. The user has confirmed that this year's PSTs and
> problem sheets are *identical* to last year's (the lecturer didn't change
> them), so the same trends apply — but if you want a higher-precision
> guide, drop the PST/problem-sheet PDFs in and I can refine it.

---

## 1. Format facts you must know cold

* Since **2020/21** the exam is **3 questions, answer all** (not the old
  6+2 Section A/B split from 2018/19). The 2024/25 paper kept this format.
* Duration: **3 hours**. Materials booklet attached (this is your
  formula sheet — includes ladder operators, J± action, perturbation
  formulae, variational principle, Pauli matrices, Clebsch–Gordan table).
* Each of the 3 questions is ~20 marks and **bundles 2–3 topics**.
  There is no "pick your topics" any more — you must be competent
  across the entire syllabus.

---

## 2. The big picture: what 0042 actually tests

The course looks broad on paper but the exam is built from a **small
recipe book** of techniques. Practically every question is some
combination of these six skills:

| # | Skill | What it looks like in the exam |
|---|---|---|
| **S1** | **QHO ladder algebra** | Rewrite Ĥ in terms of â±; compute matrix elements ⟨k\|...\|n⟩ |
| **S2** | **Matrix representation of Ĥ in a chosen basis** | Build a 2×2, 3×3 or 4×4 matrix, then diagonalise |
| **S3** | **Perturbation theory** (1st and 2nd order, non-degenerate; sometimes degenerate) | E_n^(1) = ⟨ψ\|Ŵ\|ψ⟩, E_n^(2) = Σ \|W_kn\|² / (E_n − E_k) |
| **S4** | **Variational method** | Compute ⟨H⟩_α, ∂⟨H⟩/∂α = 0, get upper bound |
| **S5** | **Adding two angular momenta / two spins** | Sing/triplet decomposition, write S² in terms of S1·S2, build matrix in product basis, diagonalise |
| **S6** | **Change of basis** | d = Sc, A^(χ) = S A^(ψ) S†, transform a Hamiltonian between two bases |

If you can execute these six recipes fluently, you cover **>90% of the
marks** on every paper I've seen. The rest is bookwork (Dirac notation,
identical particles, Pauli exclusion).

---

## 3. Topic priority matrix

Counts are out of the **5 most recent papers** (2020/21, 22/23 Practice,
22/23, 23/24, 24/25). Older 2018 and 2019 papers used a different
format so I list them separately when relevant.

| Chapter / Topic | Appears | Typical marks | Tier |
|---|---|---|---|
| **QHO ladder ops + matrix element calculations (S1, S2)** | 5/5 | 8–15 | **A — must** |
| **Perturbation theory, 1st + 2nd order, non-degenerate (S3)** | 5/5 | 6–13 | **A — must** |
| **Two spin-½ coupling: S₁·S₂, singlet/triplet, build & diagonalise matrix (S5)** | 5/5 | 10–17 | **A — must** |
| **Variational method with parametrised trial state (S4)** | 5/5 | 6–10 | **A — must** |
| **Spin-½ matrices / Pauli / σ·n̂ eigenstates** | 5/5 | 4–8 | **A — must** |
| **Angular momentum ladder operators (J±, [Jz,J±] etc.)** — derivations | 3/5 | 3–10 | **B — high** |
| **Change of basis S, d = Sc, A^(χ) = SA^(ψ)S†** | 3/5 | 5–13 | **B — high** |
| **Identical particles / symmetric vs antisymmetric / Pauli exclusion** | 2/5 | 3–9 | **B — high** |
| **Degenerate perturbation theory** | 2/5 | 5–8 | C — medium |
| **Coherent states / eigenstates of â−** | 1/5 | 5 | C — light |
| **Time evolution under Ĥ (Û(t) on a state)** | 1/5 | 5 | C — light |
| **CHSH/Bell inequality** | 0/5 (in booklet, not yet examined) | ? | C — outside bet |

**Tier A (~50+ marks every paper)**: don't even consider going into the
exam without these. S1+S2+S3+S4+S5 are essentially the entire test.

**Tier B**: very likely to appear as a sub-part of a larger question.

**Tier C**: spend ≤ 30 min each.

---

## 4. The structural template of every recent paper

The three questions follow a remarkably stable template:

| Question | Usual ingredients |
|---|---|
| **Q1** | Spin-½ matrices + change of basis **OR** identical particles + variational. Tests S2, S4, S6. |
| **Q2** | Adding angular momenta (often j₁=½, j₂=½; sometimes j₁=1, j₂=½). Derive S² = S₁² + S₂² + 2S₁·S₂, build matrix of H = αS₁·S₂ + (extra term), diagonalise. Tests S5 + ladder operator derivations. |
| **Q3** | QHO with a perturbation (linear, cubic, quartic, or x̂p̂-type), compute 1st and 2nd order corrections, then often a variational comparison. Tests S1+S3+S4. |

A useful mental model: **Q1 is the "linear algebra / spin" question, Q2
is the "two-spin coupling" question, Q3 is the "QHO + perturbation +
variational" question.** Knowing this lets you plan time before you start.

---

## 5. Topic-by-topic deep dive

For each topic: (a) where it has been tested, (b) what to memorise with
key equations typeset, (c) closed-book recall prompts, (d) common traps.

---

### S1 — QHO ladder operator algebra (Tier A, 5/5 papers)

**Where this has been tested**
* 2018 Q9: â±, [â−,â+]=1, anharmonic −λx̂³, second-order ground state
* 2019 Q8: â±, xp and px on |n⟩, evaluate ⟨px⟩ and ⟨[x,p]⟩ in given state
* 2020/21 Q1: Ĥ = QHO + g₁ x̂p̂ + g₂ p̂x̂, matrix in {|0⟩, |2⟩} basis, eigenvalues; coherent state α: ⟨α|â+|α⟩ = α*
* Practice 22/23 Q1: Ĥ = QHO + k₂x̂², matrix in lowest 3 eigenstates, diagonalise
* 2022/23 Q1: Pair of QHOs with perturbation ig(â+ − â−); commutators [â+â−, â±]; uncertainty ΔĤ ΔP̂z
* 2023/24 Q3: QHO + λx̂, perturbation + variational
* 2024/25 Q3: QHO + λκx̂⁴, (â− + â+)⁴|0⟩, perturbation up to 2nd order

**Key equations (memorise!)**

```
â+ = (1/√2)(αx̂ − i p̂/(ℏα)),    â− = (1/√2)(αx̂ + i p̂/(ℏα)),  α = √(mω/ℏ)
[â−, â+] = 1
Ĥ_QHO = ℏω(â+â− + 1/2) = ℏω(N̂ + 1/2)
â−|n⟩ = √n |n−1⟩      â+|n⟩ = √(n+1) |n+1⟩
x̂ = (1/(α√2))(â+ + â−)
p̂ = i(ℏα/√2)(â+ − â−)
```

**Position and momentum matrix elements (write these on a card)**

```
⟨k|x̂|n⟩ = (1/(α√2)) [ √(n+1) δ_{k,n+1} + √n δ_{k,n-1} ]
⟨k|p̂|n⟩ = i(ℏα/√2) [ √(n+1) δ_{k,n+1} − √n δ_{k,n-1} ]
```

**The (â− + â+)^k recipe (essential for x̂^k perturbations)**

For an x̂⁴ perturbation, you need (â− + â+)⁴|0⟩. Expand by repeated
application of â±. The 2024/25 result is the canonical one:

```
(â− + â+)⁴ |0⟩ = 3|0⟩ + 6√2 |2⟩ + √(4!) |4⟩
```

For x̂³: x̂³|0⟩ = (1/(α√2))³ × [3|1⟩ + √6 |3⟩] (see 2018 Q9(e)).

**Closed-book recall prompts**
* Derive [â−, â+] = 1 from [x̂, p̂] = iℏ.
* Write x̂ and p̂ in terms of â±.
* Compute ⟨n|x̂²|n⟩ and ⟨n|p̂²|n⟩. Hence verify ΔxΔp for state |n⟩.
* For |ψ⟩ = √3|0⟩ − |2⟩ (unnormalised), evaluate ⟨p̂x̂⟩.
* (â− + â+)⁴|0⟩ = ? (2024/25 Q3(c) verbatim)
* What is the action of x̂² on |n⟩? (Three components: |n−2⟩, |n⟩, |n+2⟩.)

**Common traps**
* Forgetting the **i** in p̂ = i(ℏα/√2)(â+ − â−). Sign errors in p̂x̂ vs x̂p̂ propagate to the whole answer.
* Confusing â+† = â− (not â+!) — the dagger swaps them.
* Mis-counting √n factors when chaining â±. Write each step explicitly.

---

### S2 — Matrix representation of operators in a basis (Tier A)

This is the *connective tissue* of the course: it shows up in nearly
every sub-part. The recipe is always the same:

```
H_{j,k} = ⟨φ_j| Ĥ |φ_k⟩
```

then diagonalise. Tips:

* **Pick the smallest sensible truncation.** If only states {|0⟩, |2⟩}
  couple to each other under the perturbation, work in a 2×2 block
  (2020/21 Q1(b)).
* **Always check Hermiticity** — every off-diagonal pair must be
  complex conjugates. Examiners love to ask "Is the resulting matrix
  Hermitian?" (2020/21 Q1(b) explicitly asks).
* **Reorder the basis** to make the matrix block-diagonal whenever you
  can. The Hamiltonian Σ Ŝ₁·Ŝ₂ + λŜ_z² 4×4 in 2023/24 Q2(d) and
  2024/25 Q2(d) splits into two 2×2 blocks if you put |↑↑⟩,|↓↓⟩
  together and |↑↓⟩,|↓↑⟩ together.

**Common traps**
* Forgetting that ⟨k|â+|n⟩ = √(n+1) δ_{k,n+1} (so it's the *upper*
  off-diagonal in the matrix when you order |0⟩,|1⟩,|2⟩... downward).
* Diagonalising a non-Hermitian matrix without realising. If you get
  complex eigenvalues from what should be a physical H, you have a
  sign/i error.

---

### S3 — Perturbation theory (Tier A, 5/5 papers)

**Where this has been tested**
* 2018 Q7, Q9(f): square well perturbation V₀, anharmonic −λx̂³ 2nd-order
* 2019 Q4: bookwork
* 2020/21 Q3(a): infinite well + λC sin(3bx), 1st and 2nd order
* Practice 22/23 Q1(d): QHO + k₂x̂² as a perturbation
* 2022/23 Q3: σ_x + ασ_z 1st and 2nd order; **degenerate** 3-level
* 2023/24 Q3(a-b): QHO + λx̂, 1st and 2nd order ground state
* 2024/25 Q3(d-g): QHO + λκx̂⁴, 1st **and 2nd** order ground state, then n-th level

**Key equations (always on formula sheet but burn them in anyway)**

```
E_n^(1) = ⟨ψ_n^(0)| Ŵ |ψ_n^(0)⟩
E_n^(2) = Σ_{k ≠ n}  |W_kn|² / ( E_n^(0) − E_k^(0) )
|ψ_n^(1)⟩ = Σ_{k ≠ n}  W_kn / ( E_n^(0) − E_k^(0) ) |ψ_k^(0)⟩
```

**The standard workflow for any "perturb a QHO" question**

1. Write the perturbation Ŵ in terms of â±.
2. Compute Ŵ|n⟩ — usually a finite sum of |n±k⟩.
3. E_n^(1) = ⟨n|Ŵ|n⟩ → only the components of Ŵ|n⟩ proportional to |n⟩
   contribute. (For odd powers of x̂, this is 0 by parity!)
4. For E_n^(2), keep only the |k⟩ that Ŵ|n⟩ actually couples to.
   The denominators are (E_n − E_k) = ℏω(n − k).

**Worked recipe (2024/25 Q3, λκx̂⁴ ground state)**

```
Ŵ |0⟩ = λγ × [ 3|0⟩ + 6√2 |2⟩ + √24 |4⟩ ]    where γ = ℏ²/(4)
E_0^(1) = 3 λγ                              (coefficient of |0⟩)
E_0^(2) = − [ (6√2)² / 2ℏω + (√24)² / 4ℏω ] λ²γ² / ℏω
       = − [ 72/2 + 24/4 ] (λγ)²/ℏω = − 42(λγ)²/ℏω
```

**The slick trick for the *general* n-th level x̂⁴ correction**

```
E_n^(1) = ⟨n| (â− + â+)⁴ |n⟩  × λγ
       = ⟨ϕ|ϕ⟩ × λγ  where |ϕ⟩ = (â−+â+)² |n⟩
```

So you only need to compute (â−+â+)²|n⟩ once (three terms), then take
the norm-squared. This is what 2024/25 Q3(f-g) is hinting at.

**For degenerate perturbation theory** (less common — but 2022/23 Q3(b)
asked it), build the W matrix in the degenerate subspace and
diagonalise to find the first-order splitting.

**Closed-book recall prompts**
* Write E_n^(1) and E_n^(2) from memory.
* Why is E_n^(1) = 0 for an x̂³ perturbation? (Parity.)
* For QHO + λx̂, what is E_0^(1)? What about E_0^(2)? (2023/24 Q3(a-b) verbatim.)
* When does perturbation theory fail? (When λ ≳ E_gap; 2022/23 Q3(a)(iii).)

**Common traps**
* Including the k = n term in the second-order sum. Don't.
* Sign of (E_n − E_k): for n > k the denominator is positive; for n < k
  it is negative. This is why ground state second-order corrections
  are always ≤ 0.
* Forgetting to square the matrix element |W_kn|² in E^(2).

---

### S4 — Variational method (Tier A, 5/5 papers)

**Where this has been tested**
* 2018 Q10: δ-function potential, Gaussian trial, find best b
* 2019 Q10: V = c|x|, Gaussian trial, find best α
* 2020/21 Q3(b): infinite well + λC sin(3bx), trial ψ₁ + q ψ₂
* Practice 22/23 Q3(b): V = cx, trial ψ_α(x) = Ax e^(−αx)
* 2023/24 Q3(c-e): QHO + λx̂, trial |ψ_θ⟩ = cos θ |0⟩ + sin θ |1⟩
* 2024/25 Q1(d-e): coupled spins, trial |↑↑⟩ + a|↓↓⟩

**The recipe (always the same!)**

1. Pick / be given a trial state |ψ_α⟩.
2. Compute ⟨ψ_α|Ĥ|ψ_α⟩ and ⟨ψ_α|ψ_α⟩ (normalisation).
3. Minimise E(α) = ⟨H⟩ / ⟨ψ|ψ⟩ over α (set ∂E/∂α = 0).
4. Plug back in → upper bound for E_0.

**Two flavours that recur:**

**(a) Continuous-parameter trial** (Gaussian width, exponential decay):
solve d⟨H⟩/dα = 0 analytically. Usually a calculus exercise; standard
integrals are given.

**(b) Linear combination of basis eigenstates** like |ψ_θ⟩ = cos θ |0⟩
+ sin θ |1⟩. Here ⟨ψ_θ|Ĥ|ψ_θ⟩ expands into ⟨0|H|0⟩cos²θ + ⟨1|H|1⟩sin²θ
+ 2 Re⟨0|H|1⟩ cos θ sin θ. Use double-angle identities to find optimal θ.

The flavour (b) variant has been the *exact* form on the last two
papers (2023/24 Q3(c) and 2024/25 Q1(d)). **This is what to drill.**

**Closed-book recall prompts**
* State the variational principle (the inequality).
* For trial state |ψ_θ⟩ = cos θ|0⟩ + sin θ|1⟩ applied to Ĥ = QHO + λx̂,
  derive ⟨H⟩_θ. Find tan 2θ at the minimum. (2023/24 Q3(c-d) verbatim.)
* For trial state |↑↑⟩ + a|↓↓⟩ applied to Ĥ = −Δ(σx⊗σx + σz⊗σz),
  find the optimal a and the energy. (2024/25 Q1(d) verbatim.)
* How can the result of the variational method be improved? (Add more
  parameters / basis states / orthogonal corrections.)

**Common traps**
* Forgetting to **normalise** the trial state when computing ⟨H⟩.
  If you skip the ⟨ψ|ψ⟩ denominator you get the wrong minimum.
* When the optimal parameter is at a boundary (e.g. a = 0), don't
  conclude that — re-examine your trial state, you may have missed a
  cross term.
* Mixing up the sign of cross terms when applying double-angle
  identities.

---

### S5 — Two spins / addition of angular momenta (Tier A, 5/5 papers)

This is the most heavily-weighted technique in the entire course. Every
recent paper has a Q2 built around it.

**Where this has been tested**
* 2018 A5(c) + B8: singlet/triplet of S₁·S₂; L̂ + Ŝ basis
* 2019 A5 + B9: singlet/triplet energy gap; NV centre S=1 system
* 2020/21 Q2(d-e): Ĥ = C₁₂ S₁·S₂ + β₀(Ŝ_z1 + Ŝ_z2)
* Practice 22/23 Q2: Ĥ = AŜ² + βŜ_z²
* 2022/23 Q2: j₁=1, j₂=½, Ĥ = C₁₂ J₁·J₂ + A(Ĵ_z1 + Ĵ_z2)²
* 2023/24 Q2: Ĥ = λ S₁·S₂ + B_z(Ŝ_z1 + Ŝ_z2), 4×4 matrix, diagonalise
* 2024/25 Q2: Ĥ = Γ S₁·S₂ + λ Ŝ_z², matrix in total-spin basis

**Key identities (this list is the question)**

```
Ŝ² = Ŝ₁² + Ŝ₂² + 2 Ŝ₁·Ŝ₂
Ŝ₁·Ŝ₂ = (1/2)( Ŝ² − Ŝ₁² − Ŝ₂² )
       = Ŝ_z1 Ŝ_z2 + (1/2)( Ŝ_{1+} Ŝ_{2−} + Ŝ_{1−} Ŝ_{2+} )
```

**Singlet/triplet** (for two spin-½):

```
|1,+1⟩ = |↑↑⟩
|1,  0⟩ = (1/√2)( |↑↓⟩ + |↓↑⟩ )
|1,−1⟩ = |↓↓⟩
|0,  0⟩ = (1/√2)( |↑↓⟩ − |↓↑⟩ )
```

**The standard exam workflow:**

1. Write Ŝ₁·Ŝ₂ using ladder operators.
2. Build the 4×4 matrix of Ĥ in the product basis {|↑↑⟩, |↑↓⟩, |↓↑⟩, |↓↓⟩}.
3. Reorder rows/columns so it block-diagonalises (typically the
   |↑↑⟩,|↓↓⟩ block decouples from the |↑↓⟩,|↓↑⟩ block).
4. Diagonalise each 2×2 (eigenvalues from the characteristic equation).
5. Identify the eigenvectors as physical |S,M⟩ states where possible.

**Useful eigenvalues to know cold (eigenvalues of Ŝ₁·Ŝ₂):**

```
Triplet (S=1): Ŝ₁·Ŝ₂ → +(1/4) ℏ²
Singlet (S=0): Ŝ₁·Ŝ₂ → −(3/4) ℏ²
Energy gap (singlet vs triplet) for H = −(E/ℏ²)S₁·S₂: ΔE = E.
```

**For j₁ = 1, j₂ = ½ (2022/23 Q2):** J = 3/2 or 1/2. Use the
Clebsch–Gordan table (provided in the booklet) to write |J,M⟩ in
terms of |m₁,m₂⟩.

**Closed-book recall prompts**
* List the four states |S,M⟩ for two spin-½ in terms of |↑↓⟩.
* Show that Ŝ₁·Ŝ₂ = (1/2)(Ŝ² − Ŝ₁² − Ŝ₂²).
* Express Ŝ₁·Ŝ₂ using ladder operators.
* In the singlet, compute ⟨Ŝ_z1⟩, ⟨Ŝ_z2⟩, ⟨Ŝ_{1x} Ŝ_{2x}⟩. (2024/25 Q2(c) verbatim.)
* For j₁ = 1, j₂ = ½, list the allowed values of J and M.

**Common traps**
* Forgetting that **|↑↓⟩ is not an eigenstate of Ŝ²**. The product
  basis only diagonalises Ŝ_z (and S₁², S₂²).
* Writing Ŝ_{1+} Ŝ_{2−} as Ŝ_{1+} ⊗ Ŝ_{2−} but forgetting that
  Ŝ_{1+}|↑⟩₁ = 0 (you can't raise an already-up spin). Several
  matrix elements are automatically zero — watch parity of m.
* Mis-applying the ℏ. The eigenvalue of S² is S(S+1)ℏ², not S(S+1).

---

### S6 — Change of basis / matrix transformation (Tier B, 3/5 papers)

**Where this has been tested**
* 2019 B7: derive d = Sc and A^(χ) = S A^(ψ) S†, apply to spin
* 2020/21 Q2(a-c): rotation matrix S, time evolution
* 2023/24 Q1: derive the formula, apply to Ŝ_x + Ŝ_y + Ŝ_z spin Hamiltonian

**Key equations**

```
S_{mn} = ⟨χ_m | ψ_n⟩       (overlap matrix)
d = S c
A^(χ) = S A^(ψ) S†          (transform of an operator's matrix)
```

S is **unitary**: S† S = I. This is the standard derivation that the
examiner asks for in the first few marks.

**Closed-book recall prompt**
Using the closure relation Σ_n |ψ_n⟩⟨ψ_n| = I, derive d_m = Σ_n S_{mn} c_n
where S_{mn} = ⟨χ_m|ψ_n⟩. (~5 marks of guaranteed bookwork.)

**Common traps**
* Mixing up which way the † goes. The rule is: starting matrix
  sandwich is S(...)S†; the *inverse* transform is S†(...)S.
* Forgetting that S is unitary, so S† = S⁻¹.

---

### Spin-½ matrices, Pauli, σ·n̂ eigenstates (Tier A subskill)

Appears in essentially every paper, usually as a 2–4 mark sub-part.

**Memorise**

```
σ_x = (0  1)    σ_y = (0 −i)    σ_z = (1  0)
      (1  0)          (i  0)          (0 −1)

σ_x|↑⟩ = |↓⟩,    σ_x|↓⟩ = |↑⟩
σ_z|↑⟩ = |↑⟩,    σ_z|↓⟩ = −|↓⟩

Ŝ_i = (ℏ/2) σ_i

Eigenstates of n̂·σ̂ (angles θ, φ):
   |+⟩_{n̂} = ( cos(θ/2),  sin(θ/2) e^(iφ) )
   |−⟩_{n̂} = ( sin(θ/2), −cos(θ/2) e^(iφ) )
```

For the Hamiltonian Ĥ = γ(aŜ_x + bŜ_y + cŜ_z) with a² + b² + c² = 1
(2023/24 Q1(c-e)): eigenvalues are ±(γℏ)/2. Identify n̂ = (a,b,c).

---

### Identical particles (Tier B, 2/5)

**Where this has been tested**
* 2018, 2019 Section A bookwork
* Practice 22/23 Q3(a): bosons vs fermions in a well + spin state combinatorics
* 2024/25 Q1(a-b): which of 4 states is symmetric / antisymmetric / product; valid spin state for He ground state

**What to memorise**

* Bosons (integer spin): total wavefunction **symmetric** under exchange.
* Fermions (half-integer spin): total wavefunction **antisymmetric**.
* If spin part is symmetric (triplet), spatial part must be
  antisymmetric (and vice versa) for fermions.
* Helium ground state: both electrons in 1s → spatial symmetric →
  spin part must be **antisymmetric** = singlet (ψ₂ in 2024/25 notation).
* Slater determinant (provided in booklet): general N-fermion
  antisymmetrised wavefunction.

**Common traps**
* Forgetting that a "product state" means one that *factorises*, e.g.
  |↑⟩⊗|↑⟩, not the entangled (|↑↓⟩ ± |↓↑⟩)/√2.
* Calling |↑↑⟩ + |↓↓⟩ a product state — it's entangled.

---

### Angular momentum ladder operators (Tier B derivations, 3/5)

**Standard derivations that have appeared verbatim**

* Show [Ĵ_z, Ĵ_+] = ℏ Ĵ_+ (2022/23 Q2(a)).
* Hence show Ĵ_+ acting on |j,m⟩ produces an eigenstate of Ĵ_z with
  eigenvalue (m+1)ℏ (2022/23 Q2(b); 2024/25 Q2(a)).
* Derive Ĵ_±|j,m⟩ = √(j(j+1) − m(m±1)) ℏ |j,m±1⟩ (2024/25 Q2(a)).
* Show Ĵ_± Ĵ_∓ = Ĵ² − Ĵ_z² ± ℏ Ĵ_z (2018 Q8(a), 2019 Q9(a)).

These are short (3–6 marks) and **basically free** if you've practised them.

---

## 6. Past papers by year (quick reference)

### 2018 (PHAS3226 — old format)
Section A (must do all 6): Hermitian properties · Dirac notation · commuting operators & uncertainty · spin-½ along arbitrary direction · superposition probabilities · operator matrix representation.
Section B (pick 2 of 4): Q7 perturbed square well (V₀) · Q8 angular momentum ladder + L+S basis · Q9 QHO + anharmonic −λx̂³ to 2nd order · Q10 variational on δ-function potential.

### 2019 (PHAS0042A6UA — old format)
Section A: Dirac · matrix Hamiltonian · uncertainty in x,p and L_x,L_y · singlet/triplet energy gap · bosons/fermions.
Section B: Q7 change of basis + spin H = α(cos η σ_z + sin η σ_y); Q8 QHO ladder + xp,px; Q9 spin ladder + NV centre S=1 H = D Ŝ_z² + C_s Ŝ·B; Q10 variational on V = c|x|.

### 2020/21 (PHAS0042A6UC)
Q1 QHO + g₁x̂p̂ + g₂p̂x̂; matrix in {|0⟩,|2⟩}; eigenvalues for g₁=iω; coherent state ⟨α|â+|α⟩.
Q2 Change of basis with rotation S(β); time evolution; two-spin H = C₁₂S₁·S₂ + β₀(Ŝ_z1+Ŝ_z2).
Q3 Infinite well + λC sin(3bx); 1st and 2nd order perturbation; variational with ψ₁ + qψ₂.

### Practice 22/23
Q1 QHO with stiffness perturbation k₁ → k₁+k₂; matrix in 3-state basis; degeneracy → eigenvalues; first-order PT comparison.
Q2 Two spin-½ → AŜ² + βŜ_z²; matrix, eigenvalues, expectation in given superposition.
Q3 Identical particles (bosons / fermions with specific spin state) + variational on V = cx with trial Axe^(−αx).

### 2022/23 (PHAS0042A6UE)
Q1 Pair of QHOs (y and z) + perturbation ig(â+−â−); commutator [â+â−, â±]; uncertainty ΔĤ ΔP̂_z.
Q2 Angular momentum derivations + j₁=1, j₂=½ coupled H = C₁₂ J₁·J₂ + A(Ĵ_z1+Ĵ_z2)².
Q3 Spin H = Aσ_x + ασ_z: 1st and 2nd order PT; **3-level degenerate PT** with given W matrix.

### 2023/24 (PHAS0042A6UF)
Q1 Change of basis bookwork (d=Sc, A^(χ)=SA^(ψ)S†); spin H = γ(aŜ_x+bŜ_y+cŜ_z); transform to y-basis.
Q2 Two spin-½: ⟨Ŝ_z1⟩ in singlet, derive S₁·S₂; 4×4 matrix of λS₁·S₂ + B_z(Ŝ_z1+Ŝ_z2); diagonalise as two 2×2 blocks.
Q3 QHO + λx̂: 1st and 2nd order; variational with |ψ_θ⟩ = cos θ|0⟩ + sin θ|1⟩; minimise via tan(2θ); compare.

### 2024/25 (most recent)
Q1 Symmetric/antisymmetric/product of 4 two-spin states; He ground state validity; Pauli on column vectors; variational on H = −Δ(σ_x⊗σ_x + σ_z⊗σ_z) with |↑↑⟩+a|↓↓⟩; sign flip of Δ.
Q2 Derive Ĵ_+ action; S² in terms of S₁², S₂², S₁·S₂; ⟨Ŝ_z1⟩,⟨Ŝ_z2⟩,⟨Ŝ_{1x}Ŝ_{2x}⟩ in singlet; matrix of Γ S₁·S₂ + λŜ_z² in total-spin basis; eigenvalues.
Q3 QHO + λκx̂⁴: write as λγ(â−+â+)⁴, show (â−+â+)⁴|0⟩ = 3|0⟩ + 6√2|2⟩ + √24|4⟩; 1st + 2nd order ground state; ⟨ψ|Â⁴|ψ⟩ = ⟨ϕ|ϕ⟩ trick; n-th level 1st-order correction.

---

## 7. Predictions for **2025/26** (analytical)

> **Disclaimer**: this is pattern-matching across 7 papers, not insider info.
> The PHAS0040 guide author claimed ~60% accuracy; expect similar here.
> Use predictions to *prioritise drilling*, not to skip topics.

### Confidence: very high (>90%) — these will appear in some form

1. **A QHO + perturbation question** — appears in every paper for the
   last 6 years. Both 1st and 2nd-order corrections to the ground
   state. Likely on Q3.

2. **A two-spin (S₁·S₂) coupling question** — appears in every paper
   for the last 5 years. Some Hamiltonian of the form
   αS₁·S₂ + β(something), then build a 4×4 matrix in the product
   basis, then diagonalise. Likely on Q2.

3. **A variational method calculation** — appears in 5/5 recent papers.
   The recent trend is "trial state = linear superposition of two
   basis eigenstates with a single parameter (a or θ)". This is the
   most-drillable variant.

4. **Spin-½ Pauli matrix manipulation** — guaranteed somewhere
   (showing σ_x|↑⟩ = |↓⟩ etc., or σ·n̂ eigenstates).

5. **At least one ladder-operator derivation** — either [Ĵ_z, Ĵ_+]
   or Ĵ±Ĵ∓ = Ĵ² − Ĵ_z² ± ℏĴ_z. Free marks.

### Confidence: high (60–80%)

6. **A QHO perturbation of a form NOT yet seen recently** — the last
   three papers cycled through pair-of-QHOs (22/23), λx̂ linear (23/24),
   λx̂⁴ quartic (24/25). Likely candidates for 25/26:
   * **λx̂³ cubic** (was on 2018 Q9, due for a comeback)
   * **λ(x̂p̂ + p̂x̂)** symmetrised form (variant of 2020/21 Q1)
   * **λx̂² stiffness shift** (variant of Practice Q1)
   * **A coupled two-mode QHO with cross-coupling** like λx̂₁x̂₂
   My single guess: **a cubic x̂³ perturbation on Q3**, mirroring the
   2018 question. The (â−+â+)³ recipe is the obvious "next step
   harder" from the 2024/25 quartic.

7. **A two-spin question that's slightly more elaborate than 24/25** —
   the trend is rising complexity. Possibilities:
   * j₁ = 1, j₂ = ½ (last seen 2022/23) → due for a return.
   * **Three spin-½ particles** — has not appeared yet but would be
     a natural escalation (build 8×8 matrix using symmetry).
   * Two-spin with a **magnetic field gradient** B₁Ŝ_z1 + B₂Ŝ_z2
     (asymmetric field — breaks total-S conservation).

8. **An identical-particles sub-question** — appeared 2024/25 Q1 and
   Practice 22/23 Q3. Could be ~3–5 marks asking which spin state is
   antisymmetric, or constructing a Slater determinant.

9. **Change of basis bookwork** (derive d = Sc) — appeared 23/24 but
   *not* 24/25. Cycle suggests it returns. ~5 marks of guaranteed
   bookwork if it does.

### Confidence: medium (30–60%)

10. **Degenerate perturbation theory** — appeared 2022/23 Q3(b) with
    a 3-level system. Could appear on a paired-QHO problem where
    |0,1⟩ and |1,0⟩ have the same E^(0).

11. **A time-evolution question** Û(t) = e^(−iĤt/ℏ) on a 2-state
    spin system — appeared 2020/21 Q2(b-c) but rare elsewhere.

12. **Bell/CHSH inequality** — listed in the booklet but I have not
    seen it examined in any past paper. Outside bet — but if the
    course content emphasises it, worth a 30-min skim.

### Confidence: low

13. **Coherent states** (eigenstates of â−) — appeared 2020/21 Q1(d)
    once. Unlikely to repeat soon, but the formula ⟨α|â+|α⟩ = α* is
    worth knowing.

### My best single-paper guess for 2025/26

| Q | Predicted content |
|---|---|
| **Q1** | Spin-½ matrix manipulation + change of basis bookwork (returning from 23/24 absence) + a short variational or identical-particles sub-part. ~20 marks. |
| **Q2** | Two-spin coupling Hamiltonian, but with j₁=1, j₂=½ (mixing 22/23 with the 23/24 / 24/25 style) — derive J₁·J₂ using ladders, build 6×6 matrix, exploit block-diagonal structure to get eigenvalues. ~20 marks. |
| **Q3** | QHO + cubic λx̂³ perturbation: show 1st-order vanishes by parity, compute 2nd-order ground state, then variational comparison with trial state cos θ|0⟩ + sin θ|3⟩. ~20 marks. |

---

## 8. Suggested 2-week revision plan

**Week 1 — Topic-by-topic active recall**
* Day 1–2: S1 (QHO ladder) — practice writing (â−+â+)^k|0⟩ for k=2,3,4 from memory. Drill 2018 Q9, 2019 Q8, 2024/25 Q3.
* Day 3: S3 (perturbation theory) — drill 2018 Q7, 2020/21 Q3(a), 2023/24 Q3(a-b), 2024/25 Q3(d-g).
* Day 4: S4 (variational) — drill 2018 Q10, 2019 Q10, 2023/24 Q3(c-e), 2024/25 Q1(d).
* Day 5: S5 (two spins) — drill 2020/21 Q2(d-e), Practice Q2, 2023/24 Q2, 2024/25 Q2.
* Day 6: S2+S6 (matrix rep + change of basis) — drill 2019 B7, 2023/24 Q1.
* Day 7: review weak spots from the week.

**Week 2 — Full timed papers**
* Day 8: 2020/21 closed-book, 3 hours.
* Day 9: mark + drill weak spots.
* Day 10: 2022/23 closed-book.
* Day 11: mark + drill.
* Day 12: 2023/24 closed-book.
* Day 13: 2024/25 closed-book (this is the most representative of 25/26 style).
* Day 14: error-notebook review + sleep.

**Skim** (in time gaps): 2018 and 2019 papers — old format, but the
Section B questions are excellent technique drills.

---

## 9. The 60-second cheat sheet

If you only had 60 seconds before the exam, this is the page to memorise:

```
QHO:    â+ = (1/√2)(αx̂ − ip̂/(ℏα))      [â−,â+] = 1
        x̂ = (1/(α√2))(â+ + â−)         p̂ = i(ℏα/√2)(â+ − â−)
        â−|n⟩ = √n |n−1⟩               â+|n⟩ = √(n+1) |n+1⟩

PT:     E^(1) = ⟨n|Ŵ|n⟩
        E^(2) = Σ_{k≠n} |W_kn|² / (E_n − E_k)

Var:    E(α) = ⟨ψ_α|Ĥ|ψ_α⟩ / ⟨ψ_α|ψ_α⟩ ≥ E_0;  ∂E/∂α = 0

Spin:   Ŝ_i = (ℏ/2)σ_i
        σ_x|↑⟩=|↓⟩, σ_z|↑⟩=|↑⟩
        Pauli matrices as given in booklet

J±:     Ĵ_±|j,m⟩ = √(j(j+1) − m(m±1)) ℏ |j,m±1⟩
        [Ĵ_z, Ĵ_±] = ±ℏ Ĵ_±
        Ĵ_+Ĵ_− = Ĵ² − Ĵ_z² + ℏĴ_z

2 spins: |1,±1⟩=|↑↑⟩,|↓↓⟩;  |1,0⟩=(|↑↓⟩+|↓↑⟩)/√2;  |0,0⟩=(|↑↓⟩−|↓↑⟩)/√2
        Ŝ₁·Ŝ₂ = (1/2)(Ŝ²−Ŝ₁²−Ŝ₂²)
        Triplet eigenvalue of Ŝ₁·Ŝ₂ = +ℏ²/4;  Singlet = −3ℏ²/4

Basis:  d = Sc,  S_{mn} = ⟨χ_m|ψ_n⟩,  A^(χ) = SA^(ψ)S†
```

Good luck.
