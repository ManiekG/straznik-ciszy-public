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

Target customers are primary and secondary schools in Poland and, longer-term, the broader EU — an EdTech/GovTech segment where procurement is often public-sector driven (see `MARKET_ANALYSIS_EN.md` for detail — currently a placeholder pending real market sizing).

## Business Model

Device sales (hardware) combined with a recurring SaaS component (dashboard, data retention, analytics) — see the original project notes' revenue model. *Actual pricing and unit economics still need to be filled in.*

## Traction & IP

- Domain `cotakglosno.pl` registered.
- Industrial design (wzór przemysłowy) filed with the Polish Patent Office (UPRP) — protects the device's appearance.
- Working hardware and firmware exist (ESP32 + MQTT), per the founder's own confirmation ("hardware and signaling already work").

## The Ask

*To be defined — amount raising, use of funds, and target milestones are not yet specified in the source material for this draft.*

---
*Contact: Mariusz Głowacki.*
