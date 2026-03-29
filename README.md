<!--
  AfterRSA — GitHub Profile
  ========================
  Post-Quantum Cryptography
-->

<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  │
│   ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  │
│   ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  │
│   ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  │
│   ·  ·  ·  ·  ●━━━━━━━━━━━━━━━━━━━►·  ·  ·  ·  ·  ·  ·  │
│   ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  │
│   ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  │
│                                                             │
│                  Shortest Vector Problem                    │
└─────────────────────────────────────────────────────────────┘
```

# AfterRSA

**Post-Quantum Cryptography — theory, code, news and deep dives**

*The math that survives quantum computers.*

[![YouTube](https://img.shields.io/badge/YouTube-@AfterRSA-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtube.com/@AfterRSA)
[![Twitter](https://img.shields.io/badge/Twitter-@AfterRSA-000000?style=flat-square&logo=x&logoColor=white)](https://twitter.com/AfterRSA)
[![Website](https://img.shields.io/badge/Web-afterrsa.com-ffffff?style=flat-square&logo=safari&logoColor=black)](https://afterrsa.com)

</div>

---

## What is AfterRSA?

RSA has secured the internet for nearly 50 years.  
A sufficiently large quantum computer running Shor's algorithm will break it.

**AfterRSA** covers the cryptography being built to replace it — the algorithms, the mathematics, the implementations, and the research shaping the next era of digital security.

---

## Content Pillars

| | Pillar | What to expect |
|---|---|---|
| 🎓 | **Theory** | Lattice mathematics, reduction proofs, hardness assumptions, paper breakdowns |
| 💻 | **Code** | Python & Rust implementations, liboqs, benchmarks, side-channel analysis |
| 📰 | **News** | NIST PQC standards, CVEs, industry migration, Q-Day developments |
| 🔭 | **Deep Dives** | Long-form walkthroughs of Kyber, Dilithium, FALCON, FHE schemes |

---

## Topics Covered

```
Lattice-Based Cryptography    Learning With Errors (LWE)     Ring-LWE / Module-LWE
CRYSTALS-Kyber (ML-KEM)       CRYSTALS-Dilithium (ML-DSA)    FALCON / NTRU
Fully Homomorphic Encryption  BGV / BFV / CKKS               Bootstrapping
Shortest Vector Problem       Closest Vector Problem          Basis Reduction
NIST Post-Quantum Standards   Hybrid Schemes                  Migration Strategies
```

---

## Repositories

| Repo | Description |
|------|-------------|
| [`lwe-from-scratch`](https://github.com/AfterRSA) | LWE encryption implemented in Python — no libraries |
| [`kyber-annotated`](https://github.com/AfterRSA) | ML-KEM / Kyber with line-by-line annotations |
| [`pqc-benchmarks`](https://github.com/AfterRSA) | Performance comparisons: PQC vs classical algorithms |
| [`lattice-visualiser`](https://github.com/AfterRSA) | Interactive SVP/CVP visualisations |
| [`fhe-playground`](https://github.com/AfterRSA) | Beginner-friendly FHE experiments |

*Repositories go live alongside video releases.*

---

## The Mathematics

The security of post-quantum cryptography rests on problems believed to be hard for both classical and quantum computers.

**Learning With Errors (LWE):** Given samples $(a_i, b_i)$ where $b_i = \langle a_i, s \rangle + e_i \pmod{q}$, find the secret vector $s$. The noise $e_i$ makes this computationally infeasible.

**Shortest Vector Problem (SVP):** Given a lattice basis $B$, find the shortest non-zero vector $v \in \mathcal{L}(B)$. No known polynomial-time algorithm exists — classical or quantum.

**Ring-LWE:** LWE over polynomial rings $\mathbb{Z}_q[x]/(f(x))$ — same hardness, dramatically better performance.

---

## Following the Channel

New videos release regularly covering:

- 📖 NIST FIPS 203 (ML-KEM), FIPS 204 (ML-DSA), FIPS 205 (SLH-DSA)
- 🔬 IACR ePrint paper breakdowns
- ⚙️ Real implementations you can run
- 🌐 Industry migration to PQC — what's happening right now

**Subscribe** → [youtube.com/@AfterRSA](https://youtube.com/@AfterRSA)

---

<div align="center">

```
Cryptography doesn't end with RSA.
```

[afterrsa.com](https://afterrsa.com) · [@AfterRSA](https://twitter.com/AfterRSA)

</div>
