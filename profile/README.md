# Black Box Research Labs

Forensic architecture audit and technical due diligence for AI-augmented infrastructure.

We produce **Artifacts of Understanding** — execution evidence, SHA-pinned referential evidence, and cognitive evidence — so organizations can prove their AI-generated systems do exactly what they intended, and nothing else. Every finding ships with commit-level proof you can check yourself.

## Research

**[Neural Affinity Framework](https://arxiv.org/abs/2512.07109)** — Ingram & Merritt (2025). Empirical evidence for the Compositional Gap in Transformer architectures: 69.5% of fine-tuned tasks achieve >80% cell accuracy but fail to compose solutions globally. Validated against 302 specialist models. Predicts ARC-AGI-2 generalization failures.

Thesis: **LOCAL ≠ GLOBAL** — components pass review; integration breaks in production. Black Box audits the gap.

## Methodology

**[AIV Protocol](https://github.com/Black-Box-Research-Labs/aiv-protocol)** — A shift-left verification framework that generates immutable, auditable proof that AI-assisted code changes were understood, tested, and verified before deployment — not just a green CI badge.

**[Flashcore](https://github.com/ImmortalDemonGod/flashcore)** — Reference implementation (production SRS engine). AIV Protocol enforced in CI: packet validation gate, immutable evidence links, artifact-backed verification on every PR.

## Case Studies

**[Verification Friction in a Series A Agent Company](https://www.blackboxresearchlabs.com/case-studies/cs-verification-friction)** — An approved pull request accrued drift, automation failed to resolve conflicts, and the work was closed unmerged after 34 days. 1,007 lines of reviewed code converted to unshipped inventory. Industry pathology: verification load exceeding available bandwidth.

**[Oklahoma Blue Thumb Data Validation](https://github.com/Black-Box-Research-Labs/ok-blue-thumb-data-validation)** — Forensic audit of chloride measurement accuracy across citizen science vs. EPA professional monitoring. N=25 paired sites, GLMM, β=−0.433 (p=0.047). Presented at OCLWA 2026.

## Engage

[blackboxresearchlabs.com](https://www.blackboxresearchlabs.com) · miguel.ingram.research@gmail.com
