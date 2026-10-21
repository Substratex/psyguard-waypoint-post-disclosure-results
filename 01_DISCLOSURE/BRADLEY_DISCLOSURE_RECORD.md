# Bradley Carter — Comparator Disclosure Record

**Disclosure date:** 2026-10-20  
**Message time shown by LinkedIn:** 5:37 PM  
**Timezone:** not asserted by this repository  
**Comparator:** PsiGuard  
**Developer:** Bradley Carter

## Source confirmation

Before disclosing PsiGuard coordinates, Bradley reviewed the frozen Aperture package and confirmed that:

- Aperture T1–T275 maps one-to-one to his native Waypoint record;
- the triple-sent prompt at T209–T211 is present in both records;
- Aperture's four incomplete assistant events correspond to his four native `interrupted before completion` events at:
  - T21
  - T116
  - T209
  - T210

Bradley's conclusion was that the frozen Aperture source was his run.

## Native label semantics

Bradley supplied a two-column file containing `source_turn` and `label`.

The native PsiGuard labels are preserved without reinterpretation:

### `intervened`

PsiGuard stepped in mid-answer and steadied the model.

Count: **11**

### `uncertain`

PsiGuard observed the turn but did not have enough evidence to judge it.

Count: **6**

Native turns:

`T1, T2, T3, T4, T178, T179`

### `no_reading`

The answer was interrupted before completion.

Count: **4**

Native turns:

`T21, T116, T209, T210`

### `holding`

Every turn not listed in the disclosure file is native holding.

## Wandering terminology

PsiGuard does not maintain a separate native `wandering` state.

Bradley explicitly declined to invent one after the fact.

For PsiGuard, the intervention turns are the native operational events relevant to the earlier "wandering" request. `uncertain` is preserved as a separate native class and is not converted into wandering or holding.

## Disclosed coordinate artifact

File:

`psiguard_waypoint_T1-T275_coordinates.csv`

SHA-256:

`f9e40354af3dc63b6d7bc1103f0361ffffe4720defcb35e3bc46d1628961e6d4`

The raw disclosed file is preserved unchanged in this repository.
