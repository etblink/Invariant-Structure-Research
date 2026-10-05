# Structural Crosswalk 0.1.1

**Status:** seed matrix / hypothesis inventory  
**Rule:** entries below identify candidate comparison targets, not validated bridges.

## Classification legend

- `EXACT` — explicit formal identity/correspondence within stated scope
- `FORMAL_ANALOGUE` — meaningful structural similarity without established common mechanism
- `POSSIBLE_BRIDGE` — warrants a targeted stronger test
- `SUPERFICIAL_SIMILARITY` — resemblance does not survive structural analysis
- `NOT_ESTABLISHED` — insufficient evidence

At version 0.1.1, most relationships remain `NOT_ESTABLISHED` because the project-specific formal objects have not yet been extracted side-by-side.

## Seed matrix

| Structural theme | NFC | PGH | FCP | Project Observatory | PCR | HiVenues | Evidence-Based Market Methods | Seed status |
|---|---|---|---|---|---|---|---|---|
| Symmetry / invariance | triality, structural persistence, crystallographic motifs | possible grammar invariants | invariants across framework comparison | possible state-normalization invariants | identity/state across successors | faithful views of canonical host state | robustness across instruments, periods, regimes, costs and benchmarks is explicitly tested; formal symmetry is not established | `POSSIBLE_BRIDGE` |
| Graphs / adjacency / networks | interaction / adjacency structures | relational grammar structures | framework/source relation graphs may occur | dependency/state relations | authority, succession, evidence relations | social, content, authority and deployment relations | not presently a central formal object | `NOT_ESTABLISHED` |
| Local ↔ global structure | fibers/spine and regime/global relationships | local rules vs generated/global structure | local framework claims vs cross-framework result | local artifacts vs project-state view | local agent context vs durable project state | host-local presentation vs wider Hive/network state | individual evidence items and subfamilies vs family-level/project-level synthesis and allocation relevance | `POSSIBLE_BRIDGE` |
| State transitions | regime evolution | grammatical generation / transition | stage/gate transitions | current/stale/superseded state | authorized project transitions | draft → approval → deploy → rollback | canonical research state and phase changes in `STATE.yaml`; research does not itself authorize capital deployment | `FORMAL_ANALOGUE` |
| Constraints / admissibility | admissible regimes/extensions | grammar rules | admission and acceptance standards | state-validity / freshness rules | authority/permissibility boundaries | validation/deployment constraints | retain/defer/reject/benchmark-only screening; preregistered experiment gates; cost/accessibility constraints | `FORMAL_ANALOGUE` |
| Canonical representation | candidate canonical physical descriptions | candidate grammar normal forms | normalized comparison basis | normalized project state | canonical identity/evidence records | canonical HostGraph/state | `STATE.yaml` is explicitly the sole canonical mutable project state | `POSSIBLE_BRIDGE` |
| Persistence under transformation | protected persistence | unknown / to extract | claim survival across comparison | state continuity across updates | project identity across successors | host identity across revisions/renderings | effect/strategy robustness under time, regime, benchmark, cost, and implementation changes | `POSSIBLE_BRIDGE` |
| Hierarchy / nesting | explicit nesting | grammar composition | framework/program/stage hierarchy | project/artifact hierarchy | project/phase/stage/evidence hierarchy | host/page/component and authority hierarchy | method families → subfamilies → evidence records / audits | `FORMAL_ANALOGUE` |
| Equivalence vs identity | alternate configurations/descriptions | alternate grammars | framework equivalence vs distinct claims | duplicate/stale/current artifact identity | semantic projection vs canonical state | multiple renderings vs one canonical state | classification by information source/economic mechanism rather than marketing label or implementation style | `POSSIBLE_BRIDGE` |
| Information preservation | structural/physical information questions | rule/state preservation questions | evidence preservation | project-state reconstruction | continuity/provenance | versioning, deployment, authority | evidence snapshots plus Git history preserve prior states while canonical current state remains singular | `POSSIBLE_BRIDGE` |
| Observer / representation relation | interpretation/model dependence may arise | grammar as description | framework-specific representation | observer view of project state | successor model vs project reality | UI/Studio representation vs underlying state | evidence, synthesis, and decision are explicitly separated; statistical significance, predictability, profitability and usefulness are distinct claims | `POSSIBLE_BRIDGE` |
| Boundary conditions | physical/regime boundaries | grammar scope | comparison/admission scope | repository/project boundaries | authority and scope boundaries | security, host and deployment boundaries | holdout/forward-test boundaries; benchmark/cost model; research-to-capital boundary | `FORMAL_ANALOGUE` |
| Reversibility / irreversibility | physical/dynamical question | to extract | adjudication/history may be irreversible operationally | supersession/history | authority/history/finality concepts | publish/deploy/rollback; chain finality where relevant | Git preserves prior states; deployment of capital requires a separate explicit decision | `NOT_ESTABLISHED` |
| Noise / incomplete observation | measurement/model uncertainty | to extract | incomplete/unequal evidence | stale/incomplete project state | partial context / uncertain reconstruction | network/user/state uncertainty | multiple testing, data snooping, look-ahead, survivorship, selection bias, estimation uncertainty, transaction costs | `POSSIBLE_BRIDGE` |
| Composition | subsystems / fibrational composition | grammar composition | framework/result composition | artifact/project composition | evidence/authority composition | pages/components/services | strategy families, subfamilies, signals, implementation layers and benchmark-relative evaluation | `POSSIBLE_BRIDGE` |

## Important limitation

The matrix above is **not evidence of a common mechanism**.

Its purpose is to identify where formal extraction should begin.

A row can contain the same English word while the underlying mathematics is unrelated.

## Candidate cross-domain patterns

### Pattern P1 — Local representation → transformation → invariant/global state

Candidate appearances:

- crystallographic coordinate/unit-cell descriptions under symmetry operations;
- physical descriptions under transformations;
- framework-specific claims under FCP normalization/comparison;
- successor-specific project representations under PCR reconstruction;
- heterogeneous project artifacts under Observatory normalization;
- host-specific views under HiVenues canonical state/rendering;
- market-method claims under benchmark, regime, cost, and implementation transformations in EBMM.

**Classification:** `POSSIBLE_BRIDGE`

**Reason not stronger:** the exact objects, maps, and invariants differ and have not yet been formally aligned.

### Pattern P2 — Many descriptions, fewer invariants

Candidate appearances:

- symmetry-equivalent physical/crystallographic descriptions;
- competing scientific frameworks with overlapping empirical content;
- multiple successor summaries of one project;
- multiple rendered views of one canonical host state;
- multiple market labels or implementations grouped by a smaller set of information sources/economic mechanisms.

**Classification:** `POSSIBLE_BRIDGE`

### Pattern P3 — Structured multiplicity constrained by invariant relations

This is the broadest candidate meta-pattern.

It may encompass:

- lattices;
- graphs;
- grammars;
- physical state spaces;
- authority systems;
- evolving project states;
- empirical method families constrained by evidence, benchmarks, costs, regimes, and decision boundaries.

**Classification:** `NOT_ESTABLISHED`

The breadth of the pattern makes false-positive matching especially likely.

## First extraction target

The first serious revision of this crosswalk should avoid adding more rows.

Instead, choose a small number of the strongest rows and extract:

1. the exact formal objects used by each relevant project;
2. the exact relation or transformation;
3. the candidate invariant;
4. the known domain and scope;
5. a falsification or disanalogy test;
6. the resulting bridge classification.

The goal is compression toward defensible structure, not accumulation of similarities.
