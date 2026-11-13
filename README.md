# Awesome-Customer-Queue-Management-Ticketing

## Top Customer Queue Management & Ticketing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Virtual Queuing, Walk-In Ticketing & Real-Time Service Flow Control*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Queue Management & Ticketing**. These tools help service businesses—clinics, banks, retail stores, government offices—manage walk-in traffic, reduce perceived wait times, and route customers to the right service point without chaotic physical lines.

**Examples** include Qminder, Waitwhile, Qmatic, NEMO-Q, Wavetec, and open-source alternatives like WaitWise, SimplQ, and Kyros (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted queue management, open-source ticketing systems, and community-driven virtual queuing—ideal for organizations seeking data sovereignty and predictable costs over per-location or per-visit SaaS pricing. The open-source queue space is genuinely thin but functional: WaitWise offers correctness-first backend logic, SimplQ provides a mature web frontend, and Kyros delivers a modern retail-focused platform.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Qminder](https://www.qminder.com/)** | Queue management for service businesses with SMS notifications, chat, and API. Three subscription tiers based on team member count. **Starter ($4,668/year)** for 10 team members; **Business ($9,468/year)** adds SMS and API; **Premium ($12,588/year)** adds custom branding and SSO. Unlimited locations, visitors, and service lines on all plans [citation:3]. Software Advice lists monthly pricing from **$429/month** [citation:13]. | Starter: $4,668/year (10 members); Business: $9,468/year; Premium: $12,588/year [citation:3] | No free tier; demo via sales |
| **[Waitwhile](https://waitwhile.com/)** | Virtual queue and appointment platform for retail, healthcare, and events. **New pricing (effective June 2025): Starter $39/location/month (250 visits); Business $69/location/month (500 visits)**. SMS moved to pay-as-you-go; email and push notifications included. **Free tier: 50 visits/month** [citation:14]. Event-specific plans from **$1,600** for single events (1,000 registrations) [citation:4]. | Starter: $39/location/month; Business: $69/location/month [citation:14] | **Free**: 50 visits/month [citation:14] |
| **[Qmatic](https://www.qmatic.com/)** | Enterprise queue management with hardware kiosks and software suite. Pricing is hardware/software bundled and varies by reseller—third-party listings show kiosk systems from **$390–$1,500** depending on configuration and supplier [citation:5][citation:15]. | Quote-only (hardware + software bundle) | No free tier; demo via sales |
| **[NEMO-Q](https://nemo-q.com/)** | Queue management with digital signage and analytics. **Published U.S. pricing: $290/month** for 1 location, 10 workstations, unlimited users/visitors/queues, self-service or receptionist check-in, real-time reporting, and basic branding [citation:8]. | **$290/month** (1 location, 10 workstations) [citation:8] | No free tier listed |
| **[Wavetec](https://www.wavetec.com/)** | Queue management and customer flow analytics. Capterra lists starting price at **$69/month** (flat rate) [citation:10]. Full deployment pricing varies by hardware and location count. | **$69/month** (Capterra listing) [citation:10] | No free tier; demo via sales |
| **[Q-nomy](https://www.q-nomy.com/)** | Branch and store customer flow optimization with appointment scheduling, kiosks, and agent routing. **Quote-based pricing**; no free version per GoodFirms . | Quote-only (contact vendor)  | No free tier  |
| **[ACF Technologies](https://www.acftechnologies.com/)** | AI-powered customer experience with queue management, appointment scheduling, and video consultations. **Custom pricing** based on organization size and deployment (cloud or on-premise) [citation:7]. | Quote-only (custom) [citation:7] | No free tier; ROI calculator available |
| **[Skiplino](https://www.skiplino.com/)** | Virtual queue management app (limited public pricing information; app listed as free in Sensor Tower data) . | Free app (in-app purchases likely)  | Free app download  |
| **[VirtuaQ](https://www.virtuaq.com/)** | Virtual queuing solution (limited public pricing information available). | Contact vendor | Contact vendor |
| **[Zoho Queue](https://www.zoho.com/)** | Queue management within Zoho ecosystem (limited public information; primarily for Zoho users). | Contact Zoho | Contact vendor |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[WaitWise](https://github.com/ruatahmar/WaitWise)** | [![Stars](https://img.shields.io/github/stars/ruatahmar/WaitWise?style=social&color=white)](https://github.com/ruatahmar/WaitWise/stargazers) | **The most correctness-focused open-source queue backend.** Virtual queue management with strict state machine (`WAITING`, `SERVING`, `LATE`, `MISSED`, `CANCELLED`, `COMPLETED`), transactional operations, background workers for expiry/late transitions, WebSocket real-time updates, and Redis caching. Designed for concurrency safety—multiple users joining/leaving simultaneously cannot break the queue. Includes comprehensive documentation (SYSTEM.md, INVARIANTS.md, CONCURRENCY.md). Node.js/Prisma/PostgreSQL backend; separate frontend repo [citation:1]. |
| **[SimplQ](https://github.com/SimplQ)** | [![Stars](https://img.shields.io/github/stars/SimplQ/simplQ-frontend?style=social&color=white)](https://github.com/SimplQ/simplQ-frontend/stargazers) | **Mature open-source virtual queue frontend** (JavaScript, GPL-3.0). ~194 stars. "Modern and fully web based free queue management open source software." Backend in Java (GPL-3.0) with ~20 stars. Long-standing project (frontend updated July 2023; backend August 2024). Positioned as "virtualizing queues, a long overdue alternative to physical queues" [citation:11]. |
| **[Kyros](https://github.com/IronBraz/kyros)** | [![Stars](https://img.shields.io/github/stars/IronBraz/kyros?style=social&color=white)](https://github.com/IronBraz/kyros/stargazers) | **Modern retail-focused queue management platform** (React 19 PWA + serverless TypeScript on Vercel + Neon Postgres). **Source-available under PolyForm Noncommercial** (not fully open-source). QR/NFC ticketing—customers scan at entrance, get ticket on phone, watch live progress, receive notification when called. Live Control Room for FIFO management. AI concierge from store wiki with spend cap. Multi-tenant by design. PIN-based admin access (no accounts to provision). **Noncommercial license restricts commercial use** [citation:12]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Ticket Booking Scheduler](https://github.com/Presktok/ticket-booking-schedular)** | [![Stars](https://img.shields.io/github/stars/Presktok/ticket-booking-schedular?style=social&color=white)](https://github.com/Presktok/ticket-booking-schedular/stargazers) | Real-time ticket booking with **priority-based scheduling** (VIP, Normal, Lower queues). VIP processes can preempt others. Seat selection with conflict prevention, interactive payment terminal, and thread-safe operations (Python/Flask/SQLite). Positioned for ticket booking rather than walk-in queues, but priority queue logic is directly applicable [citation:2]. |

**Frameworks for building custom systems**: Combine **WaitWise** for correctness-first queue backend logic with state machine and concurrency safety, **SimplQ** for a mature web frontend, and **Kyros** as a reference architecture for QR/NFC ticketing and Control Room operations—all deployable via Docker or serverless without per-location SaaS fees. Note that **Kyros is source-available for noncommercial use only**; commercial deployments require licensing or alternative solutions.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Queue management platforms handle customer flow data and potentially PII (names, phone numbers for SMS notifications); enforce consent management and compliance with applicable privacy regulations.
- **Pricing transparency varies dramatically.** NEMO-Q publishes **$290/month** for a single location with 10 workstations [citation:8]. Qminder publishes annual plans from **$4,668/year** [citation:3]. Waitwhile publishes **$39–$69/location/month** for self-serve plans [citation:14]. Qmatic, Q-nomy, ACF Technologies, and VirtuaQ are quote-only. **Open-source queue management is genuinely thin but improving.** WaitWise offers production-grade backend logic but requires frontend assembly [citation:1]. SimplQ is mature but its last major frontend update was 2023 [citation:11]. Kyros is modern and feature-rich but **noncommercial-licensed** [citation:12]. Always validate concurrency handling under real load before deploying any open-source queue system.

---

**Made for operations managers, clinic administrators, retail store managers, and developers building walk-in service infrastructure.**  
Let's make customer queue management more open, orderly, and stress-free.
