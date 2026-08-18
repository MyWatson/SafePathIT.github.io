# SafePath IT — Service Menu (per-vertical draft)

> Draft v1 — Aug 18, 2026. Productized, fixed-scope, per the venture brief. Three tiers × two verticals. Prices are engagement prices, not hourly. Nothing under $1K, ever.

## The three tiers (vertical-agnostic frame)

| Tier | Price | Duration | What it is |
|---|---|---|---|
| **Assessment** | $2,500–5,000 | 2–3 weeks | The front door. Dig into systems, data, and process; deliver a prioritized, costed roadmap. |
| **Build** | $5,000–15,000 | 3–8 weeks | One fixed-scope system from the roadmap: dashboard, automation, or integration. |
| **Advisory retainer** | $2,000–4,000/mo | ongoing | Fractional technology leadership: vendor calls, hiring input, roadmap stewardship, "call before you sign anything." |

Rules that hold across both verticals:

- Every Build should trace back to an Assessment finding (or an equivalently concrete, pre-scoped ask). Assessment fee credits 50% toward a Build signed within 60 days — makes the front door easy to walk through without discounting the work.
- Fixed scope means a written one-pager per engagement: deliverables, what's out, acceptance criteria, price. Scope change = new one-pager.
- Agents do the monitoring and summarization on every engagement; Jungle reviews exceptions. Target: each active client costs minutes/day, not hours.

## Vertical A — Equipment dealers & ag-adjacent businesses

Credibility anchor: Jungle builds and runs AI-powered dealer platforms day to day (parts discovery, e-commerce, dealer data). Public materials keep this generic — the CROP platform is a separate business and stays unnamed on SafePath collateral (brief, conclusion 6); it can be demoed live in conversation where appropriate.

### Assessment ($3,500–5,000 for a dealership; $2,500 for smaller ag-adjacent)

**"Dealer Data & AI Readiness Assessment"**

- Inventory of the stack: DMS, parts systems, e-commerce presence, phones/comms, spreadsheets that secretly run the business
- Data dig: where parts, customer, service, and sales data lives; what's trapped; what's duplicated
- Web/discovery audit: how findable is the dealership's inventory and parts catalog to a customer searching online
- Process walkthrough with parts counter, service writer, and office manager — where the hours actually go
- **Deliverable:** written roadmap, 3–7 prioritized opportunities, each with a fixed-price Build quote attached

### Builds ($5,000–15,000)

- **Parts/inventory discovery layer** — web presence that makes the dealer's catalog findable and shoppable (scoped per-dealer)
- **Dealer ops dashboard** — absorption rate, parts turns, service backlog, aged inventory in one live view instead of month-end DMS reports
- **Quote/lead automation** — inbound web and phone leads routed, enriched, and answered with AI drafting + human approval
- **DMS/e-commerce integration** — connect the systems the vendors say don't talk to each other

### Retainer ($2,500–4,000/mo)

Fractional digital platform owner — the role Jungle plays in his dealership day job, sold in slices: vendor management (DMS, OEM portals), roadmap stewardship, one build-sprint's worth of small fixes per month.

## Vertical B — Construction & trades (Las Vegas)

Credibility anchor: owns and runs a concrete business. Speaks GC scheduling, sub coordination, and job costing as a peer, not a vendor.

### Assessment ($2,500–4,000 for subs/specialty trades; $3,500–5,000 for GCs/builders)

**"Job Profit & Process Assessment"**

- Follow the money on 3–5 recent jobs: estimate → actuals → what leaked (change orders, rework, idle days, unbilled extras)
- Inventory the paper: where bids, schedules, submittals, invoices, and punch lists actually live (usually: texts, a whiteboard, and someone's truck)
- Comms map: how the field talks to the office, and what gets lost in between
- Software reality check: what they're paying for (Procore/Buildertrend/QuickBooks/etc.) vs. what they actually use
- **Deliverable:** written roadmap, prioritized by dollars recovered per dollar spent, each item with a fixed-price Build quote attached

### Builds ($5,000–15,000)

- **Job costing dashboard** — live estimate-vs-actual per job, fed from QuickBooks + time tracking, readable from a phone
- **Bid/estimate automation** — takeoff-to-proposal pipeline with AI drafting and templated pricing, owner approves before send
- **Field-to-office capture** — photo/voice-note intake from crews → structured daily logs, change-order flags, and punch lists (Telegram/SMS-based; matches the intake prototype pattern)
- **Sub/schedule coordination** — automated lookaheads and confirmation chasing so the GC isn't the one making 40 calls

### Retainer ($2,000–3,500/mo)

Fractional tech partner for a GC or growing sub: keeps the systems from decaying, monthly numbers review, first call before buying any software or signing any SaaS contract.

## Cross-cutting line — Security (both verticals)

Credibility anchor: master's degree in cybersecurity + AI-assisted audit tooling + a career on the audited side of regulated environments — HIPAA/HITRUST (Athenahealth healthcare data), SOX (banking data centers), PCI (Las Vegas gaming, MGM via Xerox), enterprise ops at IBM and GE Aerospace. Sold inside the same tier structure; explicitly NOT ongoing monitoring/SOC work (violates the minutes-per-day constraint).

### Assessment ($2,500–5,000)

**"SMB Security Audit"** — scoped to what actually gets small businesses hurt:

- MFA and identity coverage (M365/Google Workspace, DMS, banking, OEM/vendor portals)
- Email posture: SPF/DKIM/DMARC, forwarding rules, compromised-mailbox indicators
- Backup reality check: does a restore actually work, and who has tested it
- Access sprawl: ex-employees, shared logins, admin rights nobody remembers granting
- Payment-fraud exposure: how a payment-change request gets verified (construction wire fraud / dealer ACH fraud lens)
- AI-assisted depth: log review, config review, policy gap analysis, optional phishing simulation
- **Deliverable:** findings ranked by real risk, each with a fixed-price remediation quote

Vertical flavoring: for dealers, add DMS/OEM portal credential hygiene and customer-data handling; for contractors, lead with wire fraud and pay-app phishing — it's the loss they've all heard about from a peer.

### Builds ($5,000–15,000)

- **Hardening sprint** — MFA rollout, email authentication, backup/DR with tested restores, offboarding process
- **Payment-change verification workflow** — the control that stops payment-diversion fraud, built into how the office already works

### Retainer

No standalone security retainer at launch. A quarterly re-audit cadence can ride inside the advisory retainer; every Build (any vertical) includes a security review in scope.

## Open questions on this draft

- Assessment price anchoring: flat price per vertical vs. sized by revenue band — pick after the first 2–3 sell.
- Whether the 50% assessment-credit rule holds for retainer conversions too.
- Vegas GC licensing implications for anything that touches scheduling/coordination deliverables (open item in the brief).
