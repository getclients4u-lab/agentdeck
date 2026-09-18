# AgentDeck™ — The AgentDeck™ Launch System

**Build date:** 2026-09-18 · **Builder:** Archie (nightly digital-business builder) · **Budget:** $0 (all free tiers)

## The Niche (why now)
**AI agents for small business / solopreneurs** is the single hottest niche of September 2026. The trend signal was loud across every source:
- **Tech YouTube:** freeCodeCamp "OpenAI Codex Crash Course – Build & Deploy Apps with Autonomous AI"; Two Minute Papers "GPT-6 Astra Changes Everything", "The New DeepSeek Is Huge. And Somehow Tiny.", "Claude Is Now Leaving Invisible Fingerprints In Its Text"; Web Dev Simplified "How To Build A Production Ready RAG AI"; Chrome DevTools "Third-party tools for Chrome DevTools for Agents".
- **Mainstream news (last 7 days):** Inc. "This Startup Is Now Offering an AI Receptionist for Just $29 a Month" (ElevenLabs); Mastercard "Is Giving AI Agents Virtual Cards to Handle Your Shopping"; TechTarget "Splunk .conf26: Context, control for Cisco's AI agents at scale"; Capitol Hill hearings on mandatory AI safety protocols.
- **The gap:** awareness of agents is exploding; the *deployment know-how* is not. Agencies charge **$1,500–$5,000** to build one agent that costs ~$10/mo to run. That information asymmetry is the info-product opportunity.

## The Business
- **Brand:** AgentDeck™ (deck motif: a stacked, playable system you deal out)
- **Product:** The AgentDeck™ Launch System — 8-part digital PDF system
- **Mechanism:** 4-Layer Model — **JOB** (one agent, one job) → **BRAIN** (prompt contract + grounding pack) → **TRIGGER** (schedule/webhook/email/chat + heartbeat) → **GUARDRAILS** (spend caps, kill switch, risk ladder)
- **Promise:** deploy your own 24/7 AI agent in one weekend, no code
- **Price:** $19 founder (anchor $97)
- **Audience:** solopreneurs, small-business owners, freelancers, no-code operators (24–55)

## Deliverables (8 PDFs in the pack)
1. The AgentDeck System — core guide (4-layer model + 7-day build)
2. The Job Scorecard — pick the ONE job (5-axis worksheet)
3. The Grounding Pack — the 6 files every agent needs
4. The Prompt Contract — template + 20-attack adversarial test sheet
5. The Trigger Map — cron/webhook/email/chat + dead-man's-switch heartbeat
6. Guardrails & Safeguards — spend caps, kill switch, risk ladder
7. The Receipt Tracker — run log, scorecard, 10-run trust gate
8. The AgentDeck Playbook — templates, starter code, 30-day roadmap, first client

## Files
- `index.html` — long-form conversion landing page (3-part hero, 4-layer mechanism, proof band, deliverables table, agency-vs-deck comparison, 4-step how-it-works, testimonials, 11-objection FAQ, value-stack offer box w/ guarantee)
- `thank-you.html` — post-purchase page
- `download.html` — member area (code-gated, 8 PDF rows)
- `admin.html` — admin dashboard (orders, users, add/revoke, product review)
- `api/` — serverless backend: `hub.js` (verify/admin/download), `webhook.js` (Stripe + email), thin routers `verify.js`, `admin.js`, `download.js`
- `emails/launch-emails.md` — 3-email launch sequence (teaser / launch / follow-up)
- `vsl/vsl-script.md` — 5-min VSL script + 56-slide storyboard (targets the autonomous-AI YouTube wave)
- `assets/logo.svg` — brand logo

## Live URL
**→ https://agentdeck.vercel.app/** (HTTP 200 verified)
- thank-you: https://agentdeck.vercel.app/thank-you.html
- repo: github.com/getclients4u-lab/agentdeck
- private data repo: github.com/getclients4u-lab/agentdeck-data (buyers.json, users.json, product/*.pdf)

## Stripe (TEST MODE)
- Payment link: _(filled at deploy)_
- Webhook: https://agentdeck.vercel.app/api/webhook (checkout.session.completed + async_payment_succeeded)

## Notes
- Educational system for building/deploying AI agents. You are responsible for any agent you deploy and for complying with applicable laws and platform policies. No income guaranteed.
- VSL video: script + storyboard produced (renders when ELEVENLABS_API_KEY is added to env).
