# Executive Summary EN — Strażnik Ciszy (Investor Ready v5.2)

> ⚠️ **DRAFT** — written by Claude based on known project facts, not previously generated content. Review and correct every claim before sharing externally.

## The Problem

Noise levels in school classrooms and common areas are difficult to monitor objectively. Teachers and administrators typically rely on subjective judgment, with no continuous, data-backed way to track noise trends, flag problematic periods, or demonstrate improvement over time.

## The Solution

**Strażnik Ciszy** ("Guardian of Silence") is an IoT noise-monitoring device and platform purpose-built for schools:

- An ESP32-based sensor unit measures ambient noise continuously and publishes readings over MQTT.
- Data flows into a self-hosted pipeline (EMQX broker → InfluxDB → Grafana) for storage and visualization.
- A web-based **secretariat panel** gives school staff a simple dashboard view.
- **Signage displays** (BASIC / PRO tiers) give real-time visual feedback in the classroom (e.g. traffic-light style noise indicators).

## Market

Target customers are schools and pre-schools in Poland and, longer-term, the broader EU — an EdTech/GovTech segment where procurement is often public-sector driven. The product targets individual classrooms/rooms, not one unit per institution: **≈45,000 institutions, but ≈344,000 classrooms/groups** in Poland (GUS, 2025/26) — full methodology and sources in `MARKET_ANALYSIS_EN.md`.

## Business Model

**Hardware sale only** — a one-time transaction, **no subscription/SaaS component** (confirmed by the founder 2026-09-15; an earlier draft incorrectly assumed a recurring revenue stream). The dashboard/panel and analytics ship as part of the device, not as a separate product. *Pricing and unit economics are known to the founder — intentionally not disclosed in this document at his request; the full unit-economics model exists in the private repo under NDA.*

## Traction & IP

- **10 units sold to schools/pre-schools** — first real, paying customers in the target segment (confirmed by the founder, 2026-09-15).
- Domain `cotakglosno.pl` registered.
- **Utility model** (wzór użytkowy) filed with the Polish Patent Office (UPRP), doc. ID 1439233 — protects the technical/functional solution, closer to a patent than a design registration (an earlier version of this document incorrectly said "industrial design").
- Working hardware and firmware exist (ESP32 + MQTT), per the founder's own confirmation ("hardware and signaling already work").

## The Ask

Selling the entire project (source code, firmware, IP, platform, domain) for **PLN 4,000,000** — this is a full exit/sale offer, not an equity investment round. See `PITCH_DECK_PL.md`, slide 8, for details.

*Figure carried over from `../../straznik-ciszy-private/investor/VALUATION_EN.md`, flagged there as methodologically unverified — a serious buyer will likely ask for justification.*

---
*Contact: Mariusz Głowacki.*
