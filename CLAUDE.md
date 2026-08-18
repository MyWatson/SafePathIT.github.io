# SafePath IT — Venture & Repo Brief

> Working brief for the SafePath IT consulting venture. Originated in a claude.ai strategy session (Aug 18, 2026), carried into this repo the same day. Treat decisions below as working conclusions — don't re-litigate them without new information, but push back where reasoning is thin. Open items are genuinely open.

## Who

Clinton "Jungle" Stechyshyn. 26–27 years in IT (development, infrastructure, PM/program management, data). Holds a **master's degree in cybersecurity** (added to the brief Aug 18, 2026 — wasn't in the original session). Currently Digital Platform Owner at Clinton Tractor & Implement Co. (New Holland dealership, Clinton NY), where he built CROP — an AI-powered parts e-commerce/discovery platform (crop.clintontractor.net, 635K+ discovered pages, GCP/Vercel/MongoDB/Elasticsearch stack). Also owns an epoxy & decorative concrete business with construction-trade relationships (Las Vegas). Has access to an offshore (Ukrainian) dev bench for scaling past solo capacity. Daily practitioner of AI-accelerated delivery — this is the core differentiator.

## The venture

**Name: SafePath IT** (decided Aug 18, 2026 — carries over from this repo's original MSP concept; resolves the former "name/brand" open item. Domain status still needs verification.)

Solo consulting practice (LLC or S-corp — entity choice unresolved, needs accountant input) offering technology/business strategy, development, infrastructure, PM/program management, process improvement, and data analysis/dashboards for small-to-mid businesses. Second income stream; no urgency to replace primary income. Low volume works: 1–2 engagements/month at start is success, with room to compound.

## Working conclusions (agreed)

1. **Two entry wedges, not generic IT consulting:**
   - **Ag/dealer vertical** — "AI and data systems for equipment dealers and ag-adjacent businesses." CROP is a live, demonstrable proof point; dealers network with each other.
   - **Vegas construction vertical** — leverages the concrete business: real contractor relationships, trade fluency (GC scheduling, sub coordination, job costing). Positioning: "guy who runs a concrete business AND builds AI systems" = peer credibility, not a cold-call tech vendor.
2. **Pricing: productized, fixed-scope. No sub-$1K engagements** (attract worst clients, can't absorb scope drift).
   - Assessment: $2,500–5,000 (data/process/stack dig + prioritized roadmap) — the front door
   - Build: $5,000–15,000 (dashboard, automation, integration) — where AI leverage creates margin
   - Retainer/fractional: $2–4K/month advisory
3. **Platform = proof + capacity multiplier, NOT the acquisition engine.** A prototype already exists (built in one day): website + chat flow + automations + Telegram notifications to phone. Prospects experiencing the intake flow are experiencing the product. Early funnel = concrete-business network, builder relationships, direct outreach. SEO is a long game, not the year-one plan.
4. **Agentic architecture for capacity:** agents handle monitoring, summarization, cross-project status synthesis; Jungle is the expert gate on everything outbound. Design constraint: each added client should cost **minutes/day of review, not hours**. Summaries surface exceptions and decisions, not raw activity.
5. **Sequencing:** entity formation → one-page site + scheduling link → first 2 clients from existing network → then invest in platform depth.
6. **Security is a cross-cutting service line, not a third vertical** (added Aug 18, 2026). Jungle's M.S. in cybersecurity + AI-assisted auditing = productized SMB security audits ($2,500–5K, assessment tier), hardening builds, and a security review baked into every build. It sells into both wedges (dealers: customer/financial data, OEM portal credentials; construction: payment-diversion/wire fraud is endemic) and it's the reason the SafePath name works. Keep it as an offer inside the existing tier structure — don't let it balloon into 24/7 SOC/monitoring commitments that violate the minutes-per-day constraint.

## What survives from the original MSP concept (pre-Aug 2026 repo state)

The repo previously held a generic "Las Vegas MSP" landing page. Kept from it: the **SafePath IT** name and logo, the dark visual design system, and the tagline **"Focused scope. Expert execution."** Dropped: 24/7 helpdesk/MSP service catalog (incompatible with solo + minutes-per-day constraint), fabricated stats/phone/status widgets, and dead multi-page nav.

## Open items

- Entity type (LLC vs S-corp election) — needs accountant, not AI
- Coexistence with Clinton Tractor role: scope, hours, and telling John directly rather than him hearing sideways
- safepathit.com (or alternative) domain ownership/registration; real contact email + scheduling link for the site
- Offshore bench engagement model (when does a project justify pulling in the bench, margin structure)
- Vegas market entry mechanics (licensing implications, whether concrete business network transfers to consulting intros)
- Wire the one-day intake prototype (site + chat + Telegram routing) into this site

## This repo

GitHub Pages site (static, no build step). `index.html` is the one-page venture site: two-vertical positioning, productized service menu with public pricing, CROP as proof. `docs/service-menu.md` is the per-vertical service menu draft (scopes/deliverables per wedge). Keep the site one page until the sequencing step calls for platform depth. No fabricated claims: every number on the page must be real (CROP stats, years of experience) — placeholder contact points are marked with HTML comments until the domain/email question is settled.

## Constraints & preferences

- Jungle's attention is the scarce resource — optimize every design for minimal review overhead
- He builds fast (Hono/TypeScript, Next.js/Vercel, MongoDB, Telegram bots are his comfort stack — mirror CROP's stack unless there's a reason not to)
- Don't re-litigate the wedge/pricing/platform conclusions above without new information; do push back where the reasoning is thin
