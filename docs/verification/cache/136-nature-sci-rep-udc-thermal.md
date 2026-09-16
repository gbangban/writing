<!-- source: 136
     url: https://www.nature.com/articles/s41598-022-21293-2
     fetched_at: 2026-09-16T00:00:00Z
     http_status: 200
     title: Heat Wave Resilient Systems Architecture for Underwater Data Centers (Periola, Alonge & Ogudo, Scientific Reports 12, 2022)
     authoritative: yes
-->
# Heat Wave Resilient Systems Architecture for Underwater Data Centers

A. A. Periola, A. A. Alonge, K. A. Ogudo. *Scientific Reports* 12, 17254 (2022), published 2022-10-13. Open access. URL: https://www.nature.com/articles/s41598-022-21293-2

## What it is
A peer-reviewed systems-architecture paper on underwater data centers (UDCs) operating under **marine heat waves**. It models the thermal/cooling constraint: marine heat waves "limit the amount of ocean water available for UDC cooling," and proposes a reservoir-based mechanism (reservoir-as-a-service) to extend UDC operational duration.

## Key findings (thermal/ecological)
- UDCs are attractive for low cooling cost, but **marine heat waves reduce available cold water** for cooling.
- The mesopelagic zone (suitable UDC depth) has a rapidly changing temperature; warm-water exit temperatures "pose a threat to marine life" (citing prior work on warm-water cooling being unsuitable for UDCs).
- Proposed reservoir mechanism improves UDC operational duration by ~5.5–12.3% (heat waves spanning 10 epochs) and ~5.2–11.5% (15 epochs).
- This is a **modeling/simulation** study, not a field measurement of ecological impact.

## Relevance to the draft
Cited in the draft's "Known unknowns: underwater data centers" section to support the point that UDC warm-water discharge is a genuine thermal/ecological concern that the engineering literature takes seriously (heat-wave resilience is an active research topic). It backs the **concern** side of the section (warm discharge can threaten marine life), while the **no-large-impact** side is backed by [134] (HiCloud Hainan <1°C) and [135] (Highlander 2020 test, max 2°C outlet rise). Consistent with the author's "anecdotally reported" hedge: no independent peer-reviewed study of ecosystem distortion was found.

## Assessment
- `authoritative: yes` — peer-reviewed, open-access, Nature Scientific Reports.
- Caveat: modeling/simulation study, not a field measurement of actual ecological impact.
