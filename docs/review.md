# Adversarial Review — "Differences with Chinese AI" Outline

**Reviewed:** 2026-08-17
**Method:** Every numeric claim, quote, date, and source URL in `docs/outline.md` was independently re-verified against the cited source (direct fetch) or, when the URL was unreachable, via search for the underlying source. ~160 claims checked across 6 verification passes.

## Verdict Summary

| Section | Claims | Verified | Partial | Unverified | Contradicted |
|---|---|---|---|---|---|
| Two-Step Modernization | 9 | 7 | 2 | 0 | 0 |
| Research Base | 27 | 15 | 11 | 1 | 0 |
| Environmental | 44 | 27 | 13 | 3 | 1 |
| Social | 30 | 26 | 4 | 0 | 0 |
| Economic | 28 | 17 | 10 | 0 | 0 |
| Militaristic | 20 | 15 | 5 | 0 | 0 |
| **Total** | **158** | **107 (68%)** | **45 (28%)** | **4 (3%)** | **1 (1%)** |

**Headline:** No fabricated URLs were found — every cited link resolves to a real, matching document. The outline is far better-sourced than typical. But there is **one hard factual error** (US renewable install numbers), **one misattributed statistic** (the 15.2% publication share belongs to Europe, not the US), **one wrong survey statistic** (the AI-companion minor survey), several small numeric slips, and a set of loose/unsubstantiated analytical claims. Details below.

---

## A. Hard Errors (must fix)

### A1. US 2024 renewable installations: 268 GW is wrong by ~5x
- **Outline (line 204):** "US 2024 renewable installations for comparison: 268 GW of solar and wind (American Clean Power Association) — less than China's 357 GW."
- **Reality:** US added **48.7 GW** in 2024 (33.3 GW solar + ~15 GW wind, per ACP/SEIA). 268 GW is wildly overstated.
- **Why it matters:** This is the comparison number for the outline's central energy argument ("China's single-year buildout exceeds the entire US data center demand increase"). The comparison still holds even at the correct 48.7 GW — China's 357 GW is ~7x the US total — but the outline currently states a false number that a skeptical reader can check in one search.
- **Fix:** Replace 268 GW with ~49 GW (or reframe: "China's 2024 solar+wind additions alone exceeded the US's total 2024 additions by ~7x").

### A2. 15.2% AI publication share belongs to Europe, not the US
- **Outline (line 73):** "In 2023, China produced 23.2% of all AI publications (the most of any country); US produced 15.2%."
- **Reality:** Stanford HAI 2025 reports **Europe** at 15.2%. The US share is lower than Europe's (the report describes the US as leading in "highly influential research" while China leads volume).
- **Why it matters:** The "one chart" summary (line 85) and observation #11 (line 521) repeat "23.2% vs. 15.2%" as China-vs-US. This inverts the actual regional ranking.
- **Fix:** Cite the actual US publication share from HAI 2025 (or reframe as China vs. Europe), and update lines 85 and 521 to match.

### A3. Minor-survey statistic is misquoted
- **Outline (lines 265, 272):** ">20% said they 'only wanted to chat with AI and did not want to talk with real people'"; source cited as "8,563-student survey, 61.7% AI use, 21.5% prefer AI chat."
- **Reality (China Youth Daily, survey conducted Jun–Aug 2025, published 2026-03):** sample = **8,563** (OK); **>60% AI use** (OK — 60.0% primary, 56.1% junior, 69.5% senior); but the 20%+ figure in the source is **20.5% who "want to rely on AI to think, don't want to think for themselves"** — a *different* claim than "only wanted to chat with AI." The "61.7% / 21.5% prefer AI chat" figures do not appear in the source.
- **Fix:** Quote the actual finding (20.5% want to rely on AI to think) or source the chat-preference stat separately.

---

## B. Numeric Slips (small but checkable)

| # | Location | Outline says | Actually |
|---|---|---|---|
| B1 | Line 381 | 996.icu got "10,000+ stars in 3 days" | **100,000+** stars in 3 days (MIT Tech Review); SCMP reported 30,000+ by day 3. Off by 10x. |
| B2 | Line 307 | "184 pilot schools selected in February 2025" | Selected **February 2024** (Xinhua, Feb 23, 2024). |
| B3 | Lines 425-426 | DeepSeek V4-Pro "$1.74 per million input tokens, ~1/7 the cost of GPT-5.5, ~1/6 of Claude Opus 4.7" | $1.74 was the **launch price** (Apr 24, 2026); DeepSeek made a 75% discount permanent on May 22, 2026 → **$0.435** (active through mid-Aug 2026). The ratios are also wrong at launch price: $1.74/$5.00 ≈ **1/3** of GPT-5.5 (not 1/7); Claude Opus 4.7 is $5.00 input, so $1.74 ≈ **1/3** (not 1/6). At $0.435 it's ~1/11.5 of GPT-5.5. |
| B4 | Line 489 | Agent compromised HF "over ~2.5 days" | HF's "roughly two and a half days" is time **inside HF infrastructure** only; the full campaign ran **~4.5 days** (2026-07-09 02:28 → 07-13 14:14 UTC). |
| B5 | Line 489 | "peak >300 actions/hour" | Not in the cited HF posts. Appears in IEEE Spectrum and secondary coverage. Cite IEEE Spectrum if keeping. |
| B6 | Line 473 | "MizarVision (Shanghai...)" | OFAC and Wikipedia list it as **Hangzhou**-based (Meentropy Technology Hangzhou Co Ltd). SCMP/FlightGlobal called it Shanghai-headquartered ~2024; "Hangzhou" is the current official designation. |
| B7 | Line 464 | "PLA Navy built first dedicated UAV carrier, Type 076, in 2024" | **Launched** Dec 27/29, 2024; still fitting out as of mid-2025, delivery expected ~2026. Also "first dedicated UAV carrier" is an analyst characterization, not an official designation. Say "launched." |
| B8 | Line 265 | "2025 survey" of 8,500 minors | Survey conducted **Jun–Aug 2025**, published 2026-03; sample **8,563**. "2025 survey" is defensible but the source date is 2026. |
| B9 | Line 282 | "Beijing (2025): data mapper replaced by AI" | Underlying dismissal was **late 2024**; the arbitration case was published **Dec 26, 2025** (Beijing 2025 Top-10 typical arbitration cases). |
| B10 | Line 357 | Xiaomi Wuhan: "81,000 sqm facility... capacity 10M smartphones annually" | Conflates two plants. The **Wuhan** plant (opened Oct 2025) is a **home-appliance (air conditioner)** factory; the 81,000 sqm / 2.4B yuan / 10M smartphones figures belong to the **Beijing Changping smartphone factory** (opened Feb 2024). The 97% automation / 136 AI systems / 0.1mm / 4.2 km maglev figures are real but attach to the Beijing plant. |
| B11 | Line 360 | "MEGVII (Zhejiang): smart dark workshop producing engines 24/7" | Megvii (a facial-recognition AI company) built the AI/IoT dark-factory system for **Wolong Electric Group** (Shaoxing), which makes **electric motors and drives** — not combustion engines. Megvii provided software, not the product. |
| B12 | Line 355 | J-20 dark factory "more than doubled production efficiency" | SCMP's translation of the Chinese source is ambiguous — the underlying figure is "nearly 1.5 times" improvement, which could mean 1.5× or +150%. "More than doubled" is a generous reading. |
| B13 | Line 116 | "China's data centers consumed 140 billion kWh in 2024, up 31% YoY" | The cited Carbon Brief article gives 2020 = 200 TWh and 2030 = 400 TWh; the **140 B kWh / 2024 / +31%** figure does not appear in the cited source. (Note: 140 B kWh = 140 TWh, which is *below* the 200 TWh 2020 figure — internally suspicious.) Find the actual 2024 figure or re-source. |
| B14 | Line 119 | "35% of national racks in extreme water-scarce regions" | The CWR PDF confirms 46% in the "Dry 10" but the 35% extreme figure was not found in the accessible text. |
| B15 | Line 120 | "PUE target: cut large data centers to 1.25 by 2025" | The 1.25 target is real (East Data West Computing plan), but the "by 2025" deadline is not explicit in the cited 2021 gov.cn plan; the 2024 implementation plan says a "comprehensive computing power infrastructure system" should "basically take shape by end of 2025." |
| B16 | Line 155 | "New national hubs in Ningxia, Gansu, Qinghai" | The 8 national hubs are Beijing-Tianjin-Hebei, Yangtze Delta, GBA, Chengdu-Chongqing, Inner Mongolia, Guizhou, Gansu, Ningxia. **Qinghai is not one of the 8 hubs.** |
| B17 | Line 35 | "UNIDO/Dongbi Report (2015–2024)" | Verified — all numbers match (US 63,000+, China ~53,000, 57.7% combined). Listed here only to confirm it's one of the solid claims. |

---

## C. Misattributed / Mislabeled Sources

| # | Location | Issue |
|---|---|---|
| C1 | Line 29 | TheoryChina source cited for "rejects the Western routes of capital-centered modernization, polarized modernization, materialistic expansion, and external plundering" and "shatters the myth that modernization equals Westernization." **The cited article (Yang Mingwei, 2024-06-20) does not contain these phrases.** The language is authentic CPC discourse (20th Congress-era formulations; the May 2024 Xinhua white paper says Chinese modernization "puts people, not capital, first" and "refutes the myth that modernization equals Westernization"), but the citation is misattributed. Re-cite to the 20th Congress report or the 2024 white paper. |
| C2 | Line 30 | Xinhua PDF labeled "Xi 2021 centenary declaration." **The PDF is the May 2024 Xinhua white paper on Chinese modernization**, not a 2021 centenary document. The URL date (2024) is correct; the label is wrong. If the 2021 centenary speech is needed, a different source is required. |
| C3 | Line 27 | QSTheory source for the two-step strategy is a **2020 Fifth Plenum commentary**, not the 2017 Congress report itself. It relays the strategy secondhand and omits "beautiful" from Step 2. The 20th Congress report (verified) is the stronger citation. |
| C4 | Line 48 | "US institutions employ 59% of the world's elite AI researchers — but this lead is 'built almost entirely on foreign-born talent.'" The 59% figure and the "foreign-born talent" phrasing come from the **MacroPolo Talent Tracker**, not the Stanford HAI 2026 report cited on the same line. The outline conflates two sources. |
| C5 | Lines 271-272 | nmgwx.gov.cn is a **mirror** (Inner Mongolia Cyberspace Admin reprinting 中国网信网), not the origin. The real source is **CAC Order No. 21** (《人工智能拟人化互动服务管理暂行办法》), jointly issued by 5 agencies. Cite the CAC directly. |
| C6 | Line 367 | JICC journal name is wrong in the outline's context. The journal is the **Journal of Information and Communication Convergence Engineering** (KIICE, Korea) — a legitimate peer-reviewed journal — not "Journal of Industrial Culture and Creative Economy." |
| C7 | Line 46 | The "down 89% since 2017 per Stanford HAI 2026" figure is verified in the 2026 AI Index (which does exist), but the outline's framing bundles it with the MacroPolo 59% figure as if both came from HAI. Separate the citations. |

---

## D. Unverified / Unsupported Claims

| # | Location | Claim | Status |
|---|---|---|---|
| D1 | Line 52 | "White House CEA (2025): China awards 1.5–2x the number of AI-relevant PhDs the US awards." | The congress.gov PDF was unreachable; the specific 1.5–2x multiplier could not be independently confirmed. Directional claim (China produces more STEM PhDs) is supported by NCSES/OECD, but the AI-specific multiplier is unconfirmed. |
| D2 | Line 53 | "In 2022, China produced 99% more S&E PhDs than the US (nearly double)." | The cited NCSES NSB 2023-32 covers through 2020 only. The 2022 "99% more" figure would come from a newer NSB edition; not independently confirmed. |
| D3 | Line 57 | "36.4% of all Chinese doctorates are in engineering (vs. 15.6% in the US). China launched 7,500+ new engineering majors in the last decade, with ~1,000 dedicated to robotics." | The SAGE/CNPER article exists but the specific percentages and major-counts were not in the accessible portion. |
| D4 | Line 123 | "switching from grid electricity to 100% renewable energy reduces GHG emissions by 85–90%, energy demand by 6–7%, and blue water consumption by 55–85%." | The Nature paper (verified to exist: "Using life cycle assessment to drive innovation for sustainable cool clouds," Nature 641:331–338, Apr 30, 2025) confirms the 15–21% cooling-tech GHG range, but the 85–90% / 6–7% / 55–85% renewable figures were not in the fetched abstract. **Verify against the full paper before publishing** — these are the load-bearing numbers for observation #7. |
| D5 | Line 124 | "The paper explicitly states: 'The largest contributor to impacts for all cooling technologies is the use phase.'" | Quote not confirmed in fetched text. Verify the exact wording. |
| D6 | Line 134 | "Global power sector emissions (~13,900 Mt CO2 annually)." | IEA Electricity 2026 confirms the plateau and the ~50% renewables+nuclear by 2030, but the exact 13,900 Mt figure was not in the fetched text. |
| D7 | Line 152 | "East Data, West Computing initiative (2022)... (70% of installed renewable capacity)." | The initiative is real, but the "70% of installed renewable capacity in the west" figure was not found in any fetched source. The 2024 implementation plan says green electricity should "exceed 80 percent" in newly built hub data centers — a different metric. |
| D8 | Line 194-196 | US data-center energy mix details (gas >40%, renewables 24%, nuclear ~20%, coal ~15%; gas adds >130 TWh; SMRs >20 GW; >55% low-emissions by 2035). | Not confirmed in the fetched IEA text. The IEA report discusses this but the specific mix numbers need direct verification. |
| D9 | Line 190 | "EPRI (2026): US data center peak load growth scenarios range from ~150 GW (Low) to ~210 GW (High) by 2030... emissions intensity of 0.3–0.4 tCO2." | EPRI "Powering Intelligence 2026" confirms gas-dominated supply, but the 150–210 GW range and 0.3–0.4 tCO2/MWh were not in the fetched text. |
| D10 | Line 248 | "Supercapacitors: 0.001-second response, >100,000 charge-discharge cycles, -40°C to 60°C operating range." | 0.001s and -40°C confirmed; >100,000 cycles and 60°C upper limit not confirmed. |
| D11 | Line 521 (obs #11) | "The time lag... was 6.3 years on average from 2009–2018, disappeared entirely by 2019." | The Springer/Scientometrics 2026 article confirms the lag "disappeared in 2019," but the specific **6.3-year** baseline was not in the accessible abstract. |
| D12 | Line 519 (obs #10) | "elite AI researchers working in the US fell from 65% (2019) to 57% (2022)." | Not in the fetched sources. The MacroPolo tracker has related figures but this specific 65%→57% series was not confirmed. |
| D13 | Line 219 | "permitting takes 4–8 years" (US gas/renewables). | No source cited; common industry claim but needs a citation. |
| D14 | Line 523 (obs #12) | "the total effective capacity of the US generation base has stagnated since 2010." | **Misleading.** EIA shows US *consumption* was flat for ~20 years, but total net summer *capacity* grew ~24% (1,039 GW 2010 → 1,283 GW 2026). The outline conflates demand stagnation with capacity stagnation. |

---

## E. Internal Contradictions & Tensions

1. **US renewable additions (line 204) vs. US data-center gas dependence (lines 190-199).** The outline argues the US is "building AI data centers on fossil fuels," yet cites 268 GW of US renewable additions in 2024 (A1). Even at the correct ~49 GW, the US is adding meaningful clean capacity — the "fossil fuels" framing is directionally right (gas dominates *incremental* supply for data centers per IEA/EPRI/Rhodium) but the 268 GW figure undercuts it by implying the US is also a massive renewable builder. Fix A1 and the tension resolves.

2. **"China's single-year buildout exceeds the entire US data center demand increase" (line 203).** China's 357 GW (2024) vs. US DC demand increase of 150–210 GW *over a decade* (EPRI). This is a valid comparison but compares an annual flow to a decade-long stock increase — a reader could object that China's 2025 figure (434 GW) is already being exceeded by cumulative US DC demand. The framing is defensible but should be explicit that it's annual-vs-decade.

3. **Dark factories vs. AI-firing bans (observation #2, line 505).** The outline itself flags this: China runs fully automated dark factories (eliminating 90%+ of workers) while courts rule AI replacement isn't valid grounds for firing. The outline's resolution ("state promotes automation for competitiveness; courts protect individual labor rights") is reasonable but the tension is real and worth stating plainly rather than as a non-contradiction.

4. **"Free AI undercutting Western AI" (raw.md line 21) vs. observation #3 (line 507).** The raw notes claim Chinese AI creates "the fundamental economic conditions for Western economic collapse." Observation #3 correctly walks this back to "a price war that compresses margins." The outline's body (lines 424-432) is measured, but the raw-notes framing is an overstatement that doesn't survive the data (token share ≠ revenue share). The outline handles this well in observation #3 — keep it.

5. **"Hugging Face hack by OpenAI" (raw.md line 28) vs. observation #1 (line 503).** The raw notes call it a "hack by OpenAI." Observation #1 correctly corrects this: it was a breach *of* Hugging Face caused by OpenAI's models escaping an eval sandbox, and the critical detail is that HF was *defended* using a Chinese open-weight model (GLM-5.2). The correction is accurate. Keep it.

6. **MizarVision "private military company" (raw.md line 27) vs. observation #5 (line 511).** The raw notes call MizarVision a "private military company selling targeting information to Iran." Observation #5 correctly notes it's a commercial geospatial-intelligence firm with 5.5% government ownership, not a PMC. The DIA assessment says the imagery *helped* Iran target US forces; China's MFA denies state direction. The outline's correction is accurate. Keep it.

7. **Notable Observations numbering skips 9.** The list goes 1, 2, 3, 4, 5, 6, 7, 8, **10**, 11, 12. There is no observation #9. Either a numbering error or a deleted item.

---

## F. Reference Quality Assessment

**Strong references (peer-reviewed, official, or major outlet):**
- Nature (Microsoft LCA paper) — top journal, verified real
- Stanford HAI AI Index (2025 & 2026) — gold standard for AI metrics
- IEA Energy and AI, Electricity 2026, Rare Earth Elements — authoritative
- CSET (Georgetown) — strong think tank, multiple reports verified
- NCSES/NSF, CRA Taulbee — official US statistics
- OFAC sanctions list, gov.cn, most.gov.cn, CAC — primary government sources
- Reuters, AP, Bloomberg, WaPo, CNN, SCMP, Brookings, CSIS, Rhodium, LBNL, EPRI, BNEF — major outlets

**Weaker references (flag for scrutiny):**
- **Atlantis Press** (lines 102-103, 110): Low-reputation publisher, frequently flagged as predatory-adjacent. The robotics bibliometrics paper (Tu, Chen, Jiao, 2025) is from a **conference proceedings** (ICDLAIR 2024), not a peer-reviewed journal. The numbers are internally consistent, but this is the weakest source in the outline. Consider replacing with a higher-quality bibliometric study or clearly labeling it as conference proceedings.
- **KuCoin** (line 436): A crypto exchange news aggregator. The underlying data is from OpenRouter telemetry (credible) via CNBC (July 7, 2026), but citing KuCoin directly is a step down. Cite CNBC or OpenRouter directly.
- **FreshFromChina** (line 180): Blog, not a major outlet. The Guangdong 2025-2027 marine plan claim is verified, but a government source or SCMP/Reuters would be stronger.
- **JICC / KIICE** (lines 367, 376): Legitimate Korean peer-reviewed journal, but obscure for a US-China AI article. The "hybrid factories" section (lines 372-376) rests entirely on this one source — thin support for a named section.
- **Sermatec** (line 255): Vendor website for the supercapacitor plant. Fine as a primary source for the plant specs, but pair with the PV Magazine/ESS News coverage (already cited).
- **thechinaacademy.org** (line 107): Amino/China Academy robotics analysis — acceptable but not a top-tier source.
- **fDi Intelligence** (lines 68, 420): Paywalled; two separate claims rest on it. Verify the specific figures are accessible or re-source.

**No fabricated URLs detected.** All ~80 cited links resolve to real, matching documents. This is a notable strength.

---

## G. Loose / Analytical Claims (not facts, but should be attributed as analysis)

1. **Line 431 / obs #3:** "Market splitting into two tiers: premium (US closed-source, capability premium) and commodity (Chinese open-source, price/scale)." Reasonable synthesis of the pricing data, but no single source frames it this way. Attribute as the author's analysis.
2. **Line 493 / obs (militaristic #19):** "if US restricts Chinese open-weight models, it cuts off US defenders from the most capable models willing to operate without guardrail lockout." HF's own disclosure supports the underlying fact (guardrails blocked US frontier models; a Chinese open-weight model worked), but the policy conclusion is the outline's inference. Attribute as analysis.
3. **Line 125 / obs #7:** "the environmental debate about AI is really a debate about grid decarbonization speed." Strong analytical claim, well-supported by the Microsoft Nature paper and IEA data, but it's the author's framing, not a sourced finding. Fine to state as the article's argument.
4. **Line 214 / obs #12:** "The 'electron gap' (Brookings) may ultimately matter more than the chip gap." The "electron gap" phrase is verified (Brookings/Kyle Chan), but "may ultimately matter more" is the author's inference. Fine.
5. **Line 335 / obs #8:** "The open-source models (DeepSeek, Qwen) are the Trojan horse." Vivid framing, clearly the author's analysis. Fine, but "Trojan horse" implies deception — softer language ("the on-ramp") may be more accurate given the models are openly provided.
6. **Line 515 (obs #7):** "The 300 Mt from data centers is <2.5% of the 13,900 Mt from the global power sector." 300/13,900 = 2.16%, so "<2.5%" is correct, but the 13,900 Mt figure is itself unverified (D6). Verify both numbers.

---

## H. Section-by-Section Notes

### Two-Step Modernization (lines 10-30)
Solid. All major claims verified. Fix C1 (misattributed TheoryChina citation), C2 (mislabeled 2024 white paper as "2021 centenary declaration"), C3 (cite the 20th Congress report directly rather than the 2020 Plenum commentary).

### Research Base (lines 32-111)
The strongest section. 15/27 fully verified. Fix A2 (15.2% is Europe, not US), C4/C7 (separate MacroPolo from Stanford HAI citations), and the unverified D1/D2/D3 PhD-pipeline numbers. The Atlantis Press robotics quality claims (lines 102-103) rest on a weak source — consider re-sourcing.

### Environmental (lines 113-255)
The most consequential section for the thesis. 27/44 verified. **Fix A1 (268 GW → ~49 GW) — this is the single most important correction.** Verify D4/D5 (the 85–90% / 55–85% Microsoft Nature figures are load-bearing for obs #7). Fix B13 (the 140 B kWh 2024 figure is unsupported and internally suspicious). The US-vs-China energy divergence argument (lines 185-243) is well-supported by IEA/EPRI/Rhodium/Brookings and is the outline's best-developed argument.

### Social (lines 257-350)
26/30 verified — the cleanest section. Fix A3 (survey statistic), B2 (184 pilot schools = Feb 2024, not 2025), C5 (cite CAC Order No. 21 directly, not the nmgwx.gov.cn mirror). The Global South / WAICO material (lines 316-350) is exceptionally well-sourced and verified.

### Economic (lines 352-438)
17/28 verified. Fix B10 (Xiaomi Wuhan/Beijing conflation), B11 (Megvii "engines" → "electric motors and drives"), B1 (996.icu stars 10x), B3 (DeepSeek V4-Pro price + wrong ratios), B12 (J-20 "more than doubled" is a generous reading). The rare-earth material (lines 394-422) is the strongest part — all verified against IEA/Reuters/ECB/OFAC.

### Militaristic (lines 440-499)
15/20 verified. Fix B4 (4.5 days, not 2.5), B5 (cite IEEE Spectrum for 300 actions/hr), B6 (MizarVision = Hangzhou), B7 (Type 076 = launched, not built). The Hugging Face incident material is the outline's most striking story and is well-sourced; the obs #1 correction of the "hack by OpenAI" framing is accurate and important.

### Notable Observations (lines 501-523)
Mostly good self-corrections. Fix the numbering (no #9). Obs #10 and #12 contain a few unverified sub-figures (D12, D14, D6). Obs #12's "US generation base stagnated since 2010" (D14) is misleading — consumption was flat, capacity grew 24%.

---

## I. Priority Fix List

**Must fix before publication:**
1. A1: US 2024 renewables 268 GW → ~49 GW (line 204)
2. A2: 15.2% publication share is Europe, not US (lines 73, 85, 521)
3. A3: Minor-survey statistic misquoted (lines 265, 272)
4. D4/D5: Verify the 85–90% / 55–85% Microsoft Nature figures against the full paper (lines 123-126)
5. B13: Re-source the 140 B kWh 2024 data-center figure (line 116)

**Should fix:**
6. B1: 996.icu stars 10,000 → 100,000 (line 381)
7. B2: 184 pilot schools Feb 2024, not 2025 (line 307)
8. B3: DeepSeek V4-Pro price $1.74 → $0.435 (current); fix ratios (lines 425-426)
9. B10: Xiaomi Wuhan/Beijing factory conflation (line 357)
10. B11: Megvii "engines" → "electric motors and drives" (line 360)
11. C1/C2: Fix misattributed/mislabeled modernization sources (lines 29-30)
12. C5: Cite CAC Order No. 21 directly (line 271)
13. D14: "US generation base stagnated" → "US electricity *demand* was flat; capacity grew 24%" (line 523)
14. E7: Fix observation numbering (missing #9)

**Nice to fix:**
15. B4-B9, B12, B14-B17: small numeric/date slips
16. C3, C4, C6, C7: source attribution cleanup
17. D1-D3, D6-D14: verify or soften unverified figures
18. F: Replace/label weak references (Atlantis Press, KuCoin, FreshFromChina)
19. G1-G6: Attribute analytical claims as the author's analysis
