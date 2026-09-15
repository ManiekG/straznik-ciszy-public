# Market Analysis EN

> ⚠️ **PARTIALLY VERIFIED (2026-09-15)** — the unit-count market sizing below is built from cited GUS (Polish national statistics office) figures for the 2025/26 school year, retrieved and computed by Claude in this session. The EU extrapolation is an explicit, labeled rough estimate (population-based proxy), not sourced country-by-country data — treat it accordingly. **No revenue/PLN figures appear in this document by the founder's explicit instruction** (unit economics are tracked separately, under NDA, in the private repo) — do not attempt to back into a per-unit price from these numbers combined with any external revenue figure.

## Target segment

- **Primary:** Primary and secondary schools in Poland, plus pre-school (przedszkole) facilities — both included in the sizing below, since the product's stated goal is "eventually every classroom," not one unit per institution.
- **Secondary/expansion:** EU schools more broadly (EdTech/GovTech procurement channels).
- **Possible adjacent segments:** offices, libraries, healthcare waiting rooms — anywhere ambient noise monitoring has value. **Not sized here** — no reliable per-country data was available in this session; treat as a qualitative expansion direction only.

## Market sizing — Poland (sourced)

Two different unit definitions matter for this product, because the go-to-market goal is per-classroom, not per-institution:

| Layer | Count | Basis |
|---|---|---|
| Schools (primary + secondary, incl. special schools) | 23,100 | GUS, school year 2025/26 |
| Pre-school facilities (przedszkola) | 21,900 | GUS, school year 2025/26 |
| **Institutions, total** | **≈45,000** | sum of the above |
| Students (schools) | 5.3 million | GUS, school year 2025/26 |
| Children (pre-school) | 1.36 million | GUS, school year 2025/26 |
| Avg. class (oddział) size, primary schools | 18 students | GUS, school year 2024/25 |
| **Classrooms/groups, schools** (5.3M ÷ ~19, weighted avg incl. secondary) | **≈279,000** | derived |
| **Classrooms/groups, pre-schools** (1.36M ÷ ~21 children/group) | **≈65,000** | derived |
| **Classrooms/groups, total (TAM unit count)** | **≈344,000** | sum of the above |

**Takeaway:** sizing by institution count (45,000) understates the real per-unit opportunity by roughly 7-8x, since the product targets individual rooms, not one device per school.

## Market sizing — EU (rough extrapolation, not sourced per-country)

Poland is ≈36.5M people out of the EU's ≈448M (≈8.1% of EU population) — a population-based multiplier of **≈12.3x**.

| Layer | Poland | EU (population-proxy estimate) |
|---|---|---|
| Classrooms/groups (TAM unit count) | ≈344,000 | ≈4.2 million |

**This EU figure is explicitly a rough proxy, not real data** — it assumes EU countries have similar class-size and institution-density patterns to Poland, which is not verified. Before using this externally: replace with actual Eurostat school/classroom counts per target country, since school funding models and procurement channels vary significantly by member state (see "Regulatory / procurement" below).

## SAM / SOM (not sized in units here — needs go-to-market assumptions)

Converting the ≈344,000-unit Polish TAM into a realistic SAM (reachable via actual sales/procurement channels) and SOM (obtainable in a 3-5 year window by a small team) requires assumptions this document deliberately does not make: sales capacity, public-tender win rates, pilot-to-scale conversion. A range of illustrative penetration scenarios (e.g. 0.5%–3% of Polish TAM over 3-5 years) exists in the private repo's `investor/` folder together with unit economics — available under NDA, not reproduced here since it would let a reader back-calculate the per-unit price from the unit counts above.

## Rest of world

Not sized — would require market-by-market analysis of certification requirements, distribution, and local education budgets. Treat as a long-term qualitative direction, not a TAM component, until real research exists.

> A hard data block on noise/hearing/schools statistics (with source attributions that still need verification) is available in `DANE_RYNKOWE_HALAS_PL.md` — use it as a starting point, but verify every citation before including it here or in an investor deck. It is a separate, unverified data source from the GUS-sourced sizing above — do not conflate the two.

## Sources

- [GUS — "Polska szkoła w liczbach" (school year 2026/27 start, incl. 2025/26 final figures)](https://glos.pl/gus-polska-szkola-w-liczbach-najnowsze-dane-z-okazji-rozpoczecia-roku-szkolnego-2026-27)
- [GUS — average class size, school year 2024/25 (PAP Samorządowy)](https://samorzad.pap.pl/kategoria/edukacja/gus-60-proc-nauczycieli-podstawowek-nauczyciele-dyplomowani-srednia-wielkosc)
- [Eurostat population figures](https://ec.europa.eu/eurostat) — Poland (~36.5M) vs EU-27 (~448M) population ratio, used only for the rough EU multiplier above; not a per-country school-count source

## Competitive landscape

Not researched in this conversation. Before presenting this externally, identify:
- Direct competitors (other classroom noise-level indicator products, e.g. simple "noise light" devices sold internationally).
- Indirect competitors (general environmental IoT sensor platforms that could be adapted).
- Your differentiation (schools-specific workflow: secretariat panel, BASIC/PRO signage tiers, Polish-market fit, industrial design protection).

## Regulatory / procurement considerations

- Polish public schools typically procure through public tender processes (Prawo zamówień publicznych) above certain value thresholds — relevant to go-to-market planning.
- GDPR/RODO considerations are minimal for noise-level data itself (not personal data), but any integration with cameras, attendance, or student-linked data would change this.

---
*This is a starting structure, not researched market data. A real market analysis requires primary or secondary research this conversation does not have access to.*
