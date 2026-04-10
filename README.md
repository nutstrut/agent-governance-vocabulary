# Agent Governance Vocabulary

Canonical names for governance primitives across multi-issuer agent ecosystems.

**Precedent:** IANA JWT claim registry, JSON-LD `@context`. Each system keeps its internal code. This repo provides shared reference + per-system crosswalks.

## Status

v0.1 draft. Open for Working Group review. Co-authored:

- [@aeoess](https://github.com/aeoess) - APS
- [@QueBallSharken](https://github.com/QueBallSharken) - descriptor dimensions, BBIS-aligned distinctions
- [@douglasborthwick-crypto](https://github.com/douglasborthwick-crypto) - InsumerAPI / SkyeProfile, scope layering
- [@MoltyCel](https://github.com/MoltyCel) - MolTrust / AAE, typed schema discipline
- WG members invited

## Layered scope

Three layers, distinct altitudes, cross-reference via this repo:

1. `vocabulary.yaml` - canonical names for abstract governance primitives (signal types, descriptor dimensions, match semantics)
2. `MULTI-ATTESTATION-SPEC.md` (lives in [insumer-examples](https://github.com/douglasborthwick-crypto/insumer-examples)) - canonical envelope `type` field values for multi-issuer verification
3. `crosswalk/<system>.yaml` - per-system mappings between internal names and canonical names

Renaming live signed envelope `type` values is explicitly out of scope - canonical aligns with what is already in production.

## Crosswalks

Open a PR adding `crosswalk/<your-system>.yaml`. Use the match types from `vocabulary.yaml > crosswalk_match_types`. Partial match and non-equivalent-similar-label are encouraged - this layer exists to clarify differences, not hide them.

Committed contributors so far:

- `crosswalk/insumerapi.yaml` - @douglasborthwick-crypto
- `crosswalk/moltrust.yaml` - @MoltyCel
- `crosswalk/aps.yaml` - @aeoess (this week)

## License

Apache-2.0.
