# Post-Disclosure Comparison Method

## 1. No recomputation

The Aperture result is frozen.

After PsiGuard disclosure:

- source was not re-ingested;
- telemetry was not recomputed;
- thresholds were not changed;
- markers were not moved;
- regimes were not rewritten;
- candidate states were not altered;
- formal `t*` states were not reissued;
- the terminal result was not changed.

## 2. Join key

The only comparison join key is native:

`source_turn`

No semantic remapping was used to move PsiGuard events onto more favorable Aperture coordinates.

## 3. Native comparator semantics

PsiGuard labels remain:

- `intervened`
- `uncertain`
- `no_reading`
- `holding`

No separate `wandering` class was manufactured.

## 4. Prospective comparison rule

Bradley defined intervention as a mid-answer action.

Therefore, a complete source turn T can contain output produced after PsiGuard has already intervened.

For strict advance-state interpretation, the preferred Aperture comparison point is:

`Aperture state at T−1 → PsiGuard intervention at T`

Exact-turn correspondences remain scientifically useful, but they are treated as synchronous relationships rather than automatically as advance prediction.

## 5. Warning is not counted as intervention convergence

Aperture's broad warning begins at T2 and persists through the trajectory.

Because it is nearly continuous, warning status alone is not a discriminative intervention match.

## 6. Temporary formal `t*`

A temporary formal `t*` issuance at a prospective evidence horizon is not retroactively promoted into a terminal confirmed Basin Exit.

The final T275 record has formal `t* = null`.

All temporary formal-boundary episodes are preserved as evidence-horizon-sensitive states.

## 7. Comparison interpretation

The experiment is designed to identify:

- prospective structural correspondence;
- temporal offset;
- synchronous correspondence;
- PsiGuard-only events;
- Aperture-only states;
- structural disagreement.

It is not designed to force detector equivalence.
