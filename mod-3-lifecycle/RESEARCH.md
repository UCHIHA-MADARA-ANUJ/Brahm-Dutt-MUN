# 📖 MOD 3 — DEEP RESEARCH: Legal Review & Reassessment of LAWS Throughout Their Lifecycle
## The core problem: a one-time Article 36 review cannot govern a machine-learning system that evolves after deployment.
## Every fact sourced (see sources inline).

---

## §1 — ARTICLE 36: WHAT IT REQUIRES (AND WHAT IT DOESN'T)

### The obligation
- **Article 36, Additional Protocol I (1977):** *"In the study, development, acquisition or adoption of a new weapon, means or method of warfare, a High Contracting Party is under an obligation to determine whether its employment would, in some or all circumstances, be prohibited by this Protocol or by any other rule of international law."*
- Morocco ratified AP I in **2011** → legally bound by Article 36.

### What it DOES
- Requires a **legal review before deployment** — during study, development, acquisition, or adoption.
- Applies to **"new" weapons** — including weapons **modified** in a way that alters their function *(ICRC Guide to Weapons Reviews, 2006: "an existing weapon that is modified in a way that alters its function, or a weapon that has already passed a legal review but that is subsequently modified").*
- Requires assessment against ALL applicable international law (IHL, human rights law, treaty obligations).

### What it DOESN'T do
- Does **NOT specify how** reviews should be conducted — no methodology, no standard, no format *(ICRC: "Article 36 does not specify how a determination of the legality of weapons… is to be carried out").*
- Does **NOT require transparency** — reviews are national procedures with no international oversight.
- Does **NOT require reassessment** after deployment — it is prospective (before deployment), not ongoing.
- Does **NOT require reporting** to any international body.

> 🔑 **Morocco's line:** *Article 36 is a checkpoint, not a continuous guard. For conventional weapons, a checkpoint is enough. For a system that learns and evolves, it is not.*

---

## §2 — THE LIFECYCLE PROBLEM: WHY ONE-TIME REVIEW FAILS FOR ML/AI

### Machine learning systems evolve after deployment
- ML systems **update their own parameters** based on real-world data — this is called **"in situ learning"** *(Springer, "Legal reviews of in situ learning in autonomous weapons," 2023).*
- The system reviewed in the laboratory is **NOT the system operating on the battlefield six months later** — its behaviour has drifted, adapted, and potentially changed in legally significant ways.
- **Training datasets degrade**; **adversarial inputs corrupt** targeting models; **software updates introduce new behaviours** that were never reviewed.

### Emergent behaviours
- ML systems exhibit **"emergent behaviours"** — behaviours not present during testing that emerge during deployment in unpredictable environments *(tandfonline, "Leadership Challenges from LAWS Deployment").*
- Research shows that *"the introduction of new parameters or slightly heterogenous data… will confound LAWS' ML processes"* — particularly in dynamic battlespace conditions.

### Technical debt and fragility
- ML systems are typically **"5% executive code and 95% glue code"** — making them fragile and difficult to audit *(tandfonline).*
- **Configuration drift:** if a weapon updates on new data, *"its old, manually set thresholds may be invalid"* — requiring real-time validation across the weapon class.

> 🔑 **Morocco's line:** *You cannot review a river. You can only review the water at one moment. A machine-learning weapon is a river — and Article 36 reviews the water once, at the source, and walks away.*

---

## §3 — THE NUMBERS: THE REVIEW SYSTEM IS BROKEN AT SCALE

- **174 states** are parties to Additional Protocol I (bound by Article 36).
- Only **12 to 15** are known to have a weapons review mechanism *(SIPRI Insight, 2015: "Implementing Article 36 Weapon Reviews in the Light of Increasing Autonomy").*
- That means **~159 states bound by Article 36 have NO known review process.**
- Those that DO review (US, UK, Australia, Germany, etc.) keep their methodologies **classified** — no international standard, no transparency, no peer review.
- The ICRC: *"With so little evidence of States parties to AP I meeting their obligation under Article 36… this would be a welcome development."*

> 🔑 **Your hit:** *159 states are legally required to review their weapons and don't. The 12 that do won't show their work. That is not a review system. That is an honour system — and autonomous weapons are too dangerous for an honour system.*

---

## §4 — THE GGE CONSENSUS ON LIFECYCLE COMPLIANCE

The GGE has ALREADY agreed (by consensus) that lifecycle compliance matters:

- **2020 Guiding Principles:** *"Human responsibility for decisions on the use of weapons systems must be retained since accountability cannot be transferred to machines. This should be considered across the entire life cycle of the weapons system"* *(CCW/GGE.1/2020/WP.7).*
- **2023 GGE Report:** states must ensure compliance *"throughout the lifecycle of a weapon system"* — including limiting target types, duration, geographic scope; providing training; conducting legal reviews.
- **Guiding Principle (e):** states should conduct legal reviews in line with Article 36 and share best practices.
- **Guiding Principle (c):** human-machine interaction *"may take various forms and be implemented at various stages of the life cycle of a weapon."*

> 🔑 **Morocco's line:** *The GGE has already agreed on lifecycle compliance by consensus. The question is not WHETHER — it is HOW. And the answer is: mandatory, transparent, periodic reassessment — not a one-time secret review.*

---

## §5 — THE LIFECYCLE STAGES (where review must apply)

Per academic and state practice *(ANU thesis, 2023; Just Security, 2025; CCW/GGE.1/2024/CRP.1):*

| Stage | What happens | Where review is needed |
|---|---|---|
| **1. Design & development** | Engineers set parameters, training data, algorithms | Inform legal requirements; embed IHL compliance from the start |
| **2. Testing & evaluation (T&E / V&V)** | Verify the system works as intended | Initial Article 36 review; test for bias, predictability, reliability |
| **3. Procurement & acquisition** | State decides to buy/adopt | Confirm legal compliance before adoption |
| **4. Deployment & use** | System operates in real conflict | **ONGOING MONITORING** — does the system still comply after real-world data? |
| **5. Modification & software updates** | ML adapts; software patches; new data | **TRIGGER A NEW REVIEW** — any modification that alters function requires reassessment |
| **6. Retirement/disposal** | System decommissioned | Ensure no residual capability is transferred |

> 🔑 **The gap:** Article 36 covers stages 1–3 (before deployment). Stages 4–6 are **ungoverned** — and that is exactly where machine-learning systems change.

---

## §6 — PROPOSED REFORMS (what Morocco should advocate)

### A. Mandatory lifecycle review (not one-time)
- **Initial review** before deployment (existing Article 36).
- **Periodic reassessment** after fielding — coordinated with the ML algorithm's learning cycle *(Springer, 2023: "each review would address the present behaviour of the weapon system plus the set of behaviours the system might reasonably be able to adopt prior to the next review").*
- **Trigger-based review** — any software update, behavioural change, or environmental shift that could affect legal compliance triggers a new review.

### B. International standardisation
- Current reviews are national, unstandardised, and opaque. Morocco should propose an **international standard for Article 36 review of autonomous systems** — methodology, criteria, documentation.
- Model: the **CWC's OPCW** (standardised inspection methodology) or the **IAEA safeguards** (standardised nuclear verification).

### C. Transparency
- Reviews must be **reportable** — at minimum, states confirm they have conducted a review and its outcome (compliant/non-compliant).
- NOT full disclosure of classified methods — but confirmation that a review occurred and the result.
- Model: **UN Register of Conventional Arms** (states report transfers voluntarily — Morocco proposes making AWS reviews similarly reportable).

### D. Functional review (new step)
- A **"functional review"** step — not just reviewing the weapon's design, but analyzing the **IHL targeting law** that regulates the AWS's functions (distinction, proportionality, precaution) *(ANU thesis, 2023).*
- Three stages: **informative** (design phase) → **determinative** (pre-deployment review) → **governance** (ongoing monitoring during use).

### E. Bias audits throughout the lifecycle
- Bias testing at design, testing, AND post-deployment (datasets drift; new data introduces new biases).
- Per Pakistan's 2023 GGE working paper: comprehensive testing, documentation of datasets, gender/racial bias audits.

---

## §7 — COUNTRY-SPECIFIC ANGLES

### 🇺🇸 United States
- DoD Directive 3000.09 requires testing and evaluation throughout development; for AI: "rigorous developmental and operational T&E."
- After deployment: system data collected; changes undergo V&V.
- BUT: reviews are **classified**; no international standard; no transparency; no reporting.
- **Replicator** systems being fielded rapidly — are they being reviewed at each software update?
- **POI angle:** "The US conducts reviews — in secret, once, and never shares the result. How does a classified, one-time review guarantee compliance for a system that receives daily software updates?"

### 🇷🇺 Russia
- Opposes any new limitations; says "no convincing grounds."
- Russia argues Article 36 reviews are a matter of **national discretion** — no standardisation needed.
- **POI angle:** "Russia says Article 36 is a matter of national discretion. Is 'trust us' the international standard Russia proposes for weapons that select and kill autonomously?"

### 🇦🇺 Australia
- Published its Article 36 review process *(CCW/GGE.2/2018/WP.6)* — one of the few transparent ones.
- Argues a treaty is "premature" — but supports Article 36 reviews and lifecycle compliance.
- **POI angle (recruit, not wound):** "Australia is one of the few states that has published its review process. Will Australia champion making that transparency an international standard — not just a national best practice?"

### 🇩🇪 Germany
- "Article 36 is of utmost importance"; has formalised review procedures.
- Supports lifecycle compliance and human-machine interaction across the lifecycle.
- **POI angle (recruit):** "Germany has called Article 36 'of utmost importance' — will Germany co-sponsor mandatory lifecycle reassessment as a binding obligation?"

### States WITHOUT review mechanisms (159 of 174)
- **POI angle (general):** "159 states are legally bound by Article 36 and have no known review mechanism. How does this committee propose to address a 91% non-compliance rate with the existing obligation — before adding new ones?"

---

## §8 — ANTICIPATED ATTACKS + DEFENSES

**Q: "Article 36 already requires review — why do we need new rules?"**
> A: "Article 36 requires a review before deployment. It does NOT require reassessment after deployment. For conventional weapons, that is sufficient. For a system that learns and evolves, it is not. The law was written in 1977 — before machine learning existed."

**Q: "Lifecycle review is impractical — you can't review every software update."**
> A: "You don't review every line of code. You require states to REPORT any update that could affect legal compliance — and trigger a new review only when the system's behaviour changes. The CWC manages this with the OPCW's challenge inspection model."

**Q: "This is national security — reviews must stay classified."**
> A: "Morocco does not ask for classified methodology. We ask for confirmation that a review occurred and its outcome. A state that confirms 'we reviewed this system and it complies' reveals nothing — except that it takes its obligations seriously."

**Q: "Morocco's own drones — are THEY reviewed?"**
> A: "Morocco ratified AP I in 2011 and is bound by Article 36. Our drones are remotely-piloted (human-in-the-loop) — reviewed under existing procedures. That is precisely why Morocco champions making Article 36 reviews an international standard: because we already meet ours."

---

## §9 — THE CLAUSE THIS BUILDS

> **Lifecycle review clause:** *"Requires States parties to conduct an initial Article 36 legal review before deployment of any autonomous weapon system; to conduct periodic reassessment after fielding, coordinated with the system's learning cycle; to trigger a new review upon any software update, behavioural change, or modification that could affect legal compliance; and to report to [a Conference of States Parties / the Secretary-General] that such reviews have been conducted and their outcome."*

---
*Review once, govern forever. That is not oversight — it is negligence. 🇲🇦*
