# Aperture × PsiGuard — Waypoint T1–T275 Post-Disclosure Results

**Repository status:** POST-DISCLOSURE COMPARATIVE RECORD  
**Comparison operation:** native `source_turn` join only  
**Aperture recomputation after disclosure:** **NO**  
**Aperture retuning after disclosure:** **NO**  
**Certified Aperture Run / Passport:** `APERTURE-CER-6753eadcdd506`

This repository is the **post-disclosure companion** to the frozen pre-disclosure Waypoint experiment published on 2026-10-19.

The parent repository preserved the complete Aperture result **before** PsiGuard coordinates were revealed. This repository begins only after Bradley Carter reviewed that frozen package, confirmed that it matched his native T1–T275 record one-to-one, and disclosed PsiGuard's native turn labels.

**Parent pre-disclosure repository:**  
`Substratex/aperture-psiguard-waypoint-blind-study`  
Originally assembled and first published under the working name `psyguard-waypoint-repo-final`.

The governing experimental question remains:

> **Can two independently developed systems, operating from different architectures and evidentiary assumptions, identify related stability transitions in the same long-horizon AI trajectory—and where do prospective detection and retrospective reconstruction diverge?**

## The answer from the first blind comparison

**Yes, partially — but not trivially and not as detector equivalence.**

The frozen Aperture trajectory and PsiGuard's independently generated intervention record show **partial prospective structural and temporal correspondence with informative disagreement**.

PsiGuard disclosed 11 native `intervened` turns:

`T35, T59, T61, T151, T158, T160, T172, T180, T196, T206, T228`

Bradley also disclosed:

- `uncertain`: `T1–T4, T178, T179`
- `no_reading`: `T21, T116, T209, T210`
- all other turns: native `holding`

PsiGuard does **not** maintain a separate wandering state. The repository preserves Bradley's native ontology rather than inventing a post-hoc equivalent.

## Primary results

Because PsiGuard intervention occurs **mid-answer**, the strongest strictly prospective comparison is the frozen Aperture state at the prior admissible horizon `T−1`.

- Aperture candidate state was already active at `T−1` for **9 of 11 interventions (81.8%)**.
- Candidate state was active at the exact intervention horizon for **8 of 11 interventions (72.7%)**.
- **6 of 11 interventions** occurred within a strict ±1-turn neighborhood of a temporary formal-boundary issuance horizon.
- Two interventions occurred **one turn after** a temporary formal Aperture boundary issuance:
  - `T157 → T158`
  - `T205 → T206`
- Two additional interventions occurred **two turns after** a temporary formal issuance:
  - `T170 → T172`
  - `T226 → T228`
- `T196` is the strongest same-turn correspondence: PsiGuard intervened on the same source turn where the frozen Aperture prefix was `Collapse`, candidate-active, and temporarily issued formal `t*=T196`.
- `T151` is a clear PsiGuard-only action at the registered comparison scale and is preserved as disagreement.

These findings do **not** mean that PsiGuard intervention is equivalent to Aperture `t_aw`, candidate state, formal `t*`, or failure.

## Source-topology confirmation

Before comparison, Bradley independently confirmed that the frozen T1–T275 source mapped one-to-one to his native record, including the unusual triple-sent prompt at `T209–T211`.

PsiGuard's four `no_reading` events:

`T21, T116, T209, T210`

exactly match Aperture's four preserved incomplete assistant events.

This is strong cross-system **source/topology correspondence**. It is not, by itself, validation of the stability measurements.

## What this repository establishes

This repository establishes the historical result of the first blind external Aperture × PsiGuard comparison:

1. the comparator was disclosed only after the Aperture result was frozen;
2. the external runtime identity was independently confirmed;
3. no Aperture result was recomputed or retuned after disclosure;
4. the comparison was performed by native `source_turn` join;
5. the systems show partial structural/temporal correspondence;
6. they also show real disagreement and different operational semantics;
7. the result is therefore evidence for **related sensitivity to trajectory structure**, not evidence that the systems are interchangeable.

## Recommended reading order

1. [`00_RESULTS_SUMMARY.md`](00_RESULTS_SUMMARY.md)
2. [`01_DISCLOSURE/BRADLEY_DISCLOSURE_RECORD.md`](01_DISCLOSURE/BRADLEY_DISCLOSURE_RECORD.md)
3. [`02_FROZEN_PARENT_REFERENCE/PARENT_PRE_DISCLOSURE_REFERENCE.md`](02_FROZEN_PARENT_REFERENCE/PARENT_PRE_DISCLOSURE_REFERENCE.md)
4. [`03_RESULTS/POST_UNBLINDING_RESULTS.md`](03_RESULTS/POST_UNBLINDING_RESULTS.md)
5. [`03_RESULTS/EVENT_BY_EVENT_COMPARISON.md`](03_RESULTS/EVENT_BY_EVENT_COMPARISON.md)
6. [`04_ANALYSIS/INTERPRETATION_AND_SIGNIFICANCE.md`](04_ANALYSIS/INTERPRETATION_AND_SIGNIFICANCE.md)
7. [`04_ANALYSIS/LIMITATIONS_AND_NEXT_TESTS.md`](04_ANALYSIS/LIMITATIONS_AND_NEXT_TESTS.md)

Machine-readable records are included beside the narrative documentation.

## Integrity

The authoritative pre-disclosure lock remains the lock published in the parent repository.

This follow-up repository does **not** rewrite that record.

See:

- `02_FROZEN_PARENT_REFERENCE/APERTURE_T1-T275_BLIND_RESULT_LOCK_v2.json`
- `MANIFEST_SHA256.txt`
- `REPOSITORY_STATUS.json`

## Citation and license

See `CITATION.cff` and `LICENSE.md`.

---

**SubstrateX® — Runtime Evidence Infrastructure**  
**Aperture™ — Runtime Evidence Observatory**  
**Intelligence in Motion™**
