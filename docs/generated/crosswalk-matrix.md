# Crosswalk Matrix

Auto-generated on 2026-05-02. 15 systems × 13 canonical signal types.

Cell legend:

- ✅ `exact` — same question, same surface shape
- 🟠 `structural` — same question, different surface
- 🟡 `partial` — overlapping but not identical scope
- 🔵 `non_equivalent_similar_label` — different question entirely
- ⚪ `no_mapping` — explicit gap with technical rationale
- · mapped but no `match` strength declared (legacy schema)
- — not addressed by this crosswalk

## Matrix

| System            | wallet_state | behavioral_trust | wallet_intelligence | reasoning_integrity | compliance_risk | governance_attestation | passport_grade | trust_verification | security_posture | job_performance | settlement_witness | peer_review | entity_continuity |
| ----------------- | ------------ | ---------------- | ------------------- | ------------------- | --------------- | ---------------------- | -------------- | ------------------ | ---------------- | --------------- | ------------------ | ----------- | ----------------- |
| Agent-Did         | ⚪            | ⚪                | ⚪                   | ⚪                   | ⚪               | ⚪                      | ⚪              | 🟡                 | ⚪                | ⚪               | ⚪                  | ⚪           | 🟡                |
| Agentlair         | ⚪            | ✅                | ⚪                   | ⚪                   | ⚪               | 🟡                     | ⚪              | 🟡                 | ⚪                | ⚪               | ⚪                  | ⚪           | ⚪                 |
| Agentnexus        | ·            | —                | —                   | —                   | —               | ·                      | —              | —                  | —                | —               | —                  | —           | —                 |
| APS               | ⚪            | 🟡               | ⚪                   | ⚪                   | ⚪               | ✅                      | ✅              | ✅                  | ⚪                | ⚪               | ⚪                  | ⚪           | 🟡                |
| ASQAV             | ·            | ·                | ·                   | ·                   | ·               | ·                      | ·              | ·                  | ·                | ·               | ·                  | —           | —                 |
| DCP-Ai            | ⚪            | ⚪                | ⚪                   | ⚪                   | ⚪               | ✅                      | 🔵             | ✅                  | ⚪                | ⚪               | ⚪                  | 🟡          | 🟡                |
| Fidelity-Spec     | ⚪            | 🟡               | ⚪                   | ⚪                   | ⚪               | 🟡                     | ⚪              | ⚪                  | ⚪                | ⚪               | ⚪                  | ⚪           | 🟡                |
| Insumerapi        | ✅            | ⚪                | ⚪                   | ⚪                   | ⚪               | —                      | ⚪              | ⚪                  | ⚪                | ⚪               | ⚪                  | —           | —                 |
| Moltrust          | ⚪            | ✅                | ⚪                   | ⚪                   | ⚪               | ⚪                      | ⚪              | ✅                  | ⚪                | ⚪               | ⚪                  | ⚪           | —                 |
| Nobulex           | ·            | ·                | ·                   | ·                   | ·               | ·                      | ·              | ·                  | ·                | ·               | ·                  | —           | —                 |
| Pathcourse-Health | ⚪            | ✅                | ⚪                   | ⚪                   | ⚪               | ⚪                      | ⚪              | 🟡                 | ⚪                | ⚪               | ⚪                  | ⚪           | —                 |
| PIC               | ⚪            | ⚪                | ⚪                   | ⚪                   | ⚪               | ⚪                      | ⚪              | ⚪                  | ⚪                | ⚪               | ⚪                  | ⚪           | ⚪                 |
| Signet            | ·            | ·                | ·                   | ·                   | ·               | ·                      | ·              | ·                  | ·                | ·               | ·                  | ·           | —                 |
| SINT              | 🟡           | 🟡               | ⚪                   | ⚪                   | ⚪               | ✅                      | 🟡             | 🟡                 | 🟡               | 🟡              | 🟡                 | ⚪           | 🟠                |
| Veritasacta       | ⚪            | ⚪                | ⚪                   | 🟡                  | ⚪               | —                      | ⚪              | ⚪                  | ⚪                | ⚪               | 🟠                 | —           | —                 |

## Coverage

- Systems represented: 15
- Canonical signal types: 13

### Per-signal coverage

| Signal type | Systems mapped | Coverage |
|---|---|---|
| `wallet_state` | 15 / 15 | 100% |
| `behavioral_trust` | 14 / 15 | 93% |
| `compliance_risk` | 14 / 15 | 93% |
| `job_performance` | 14 / 15 | 93% |
| `passport_grade` | 14 / 15 | 93% |
| `reasoning_integrity` | 14 / 15 | 93% |
| `security_posture` | 14 / 15 | 93% |
| `settlement_witness` | 14 / 15 | 93% |
| `trust_verification` | 14 / 15 | 93% |
| `wallet_intelligence` | 14 / 15 | 93% |
| `governance_attestation` | 13 / 15 | 87% |
| `peer_review` | 10 / 15 | 67% |
| `entity_continuity` | 7 / 15 | 47% |

### Top-3 most-mapped

- `wallet_state` — 15/15 (100%)
- `behavioral_trust` — 14/15 (93%)
- `compliance_risk` — 14/15 (93%)

### Top-3 least-mapped

- `entity_continuity` — 7/15 (47%)
- `peer_review` — 10/15 (67%)
- `governance_attestation` — 13/15 (87%)

---

Auto-generated by `scripts/generate-crosswalk-matrix.js`. Do not edit. Re-run after any crosswalk PR merges.

## Alternative-format crosswalks not represented in this matrix

- `crosswalk/a2a.yaml` — no signal_types block (alternative crosswalk format)
- `crosswalk/continuity-analyzer.yaml` — no signal_types block (alternative crosswalk format)
- `crosswalk/jep.yaml` — no signal_types block (alternative crosswalk format)
- `crosswalk/logpose.yaml` — no signal_types block (alternative crosswalk format)
- `crosswalk/rnwy.yaml` — no signal_types block (alternative crosswalk format)
- `crosswalk/sar.yaml` — no signal_types block (alternative crosswalk format)
- `crosswalk/satp/behavioral-trust.yaml` — no signal_types block (alternative crosswalk format)
- `crosswalk/soulboundrobots.yaml` — no signal_types block (alternative crosswalk format)
- `crosswalk/sovereign-atom.yaml` — no signal_types block (alternative crosswalk format)

## Reverse crosswalks (separate matrix)

- `crosswalk/rfc-category-taxonomy.yaml` — `crosswalk_type: rfc_category_reverse`

## Test fixtures (excluded)

- `crosswalk/_test-invalid.yaml` — deliberate negative-control fixture
