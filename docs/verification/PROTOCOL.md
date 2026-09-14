# Verification Protocol (frozen)

## Verdicts
- verified: cited (or traced) authoritative source contains the exact figure/quote.
- verified-with-caveat: true, but the source forces a qualifier (date, range, scope).
- fix-required: source contradicts, or figure not in cited source and no authoritative re-source found.
- unverified: no authoritative source located after search (handwritten: must resolve; AI: downgrade or remove).
- analysis-ok: author's analysis; premises verified, framing is the author's.

## Origin
- hw: author's own (framing, thesis, asides, revisions, argument).
- ai: AI-generated research (figures, policies, tables, case details, stats).
- mixed: author framing wrapping an AI figure (verify figure as ai, framing as hw).
- analysis: opinion/framing (verify premises only).

## Authoritative source (any ONE of)
primary/official, peer-reviewed, top-tier outlet, recognized domain authority.
Blog/vendor/aggregator/mirror = NOT authoritative alone; must trace to an authoritative origin.

## Standard by origin
- hw load-bearing: must reach verified / verified-with-caveat / fix-required (no unverified).
- ai: must reach verified / verified-with-caveat / fix-required, AND if the cited source
  lacks the exact figure, a different authoritative source must be found and recorded.

## Fold-down (cache) rule
Every cited URL -> cache/NN-slug.md + NN-slug.json. On fetch failure: sidecar status=failed,
search for authoritative origin, cache that instead. Re-runs read the cache (no re-fetch).
