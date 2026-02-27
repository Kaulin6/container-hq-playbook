# Container HQ Cold Email Playbook — Visual Explainer Page

## Purpose
A single HTML page that walks through the Container HQ cold email marketing plan.
Audience: Kaulin explaining the strategy to partners/advisors. Needs to look sharp and be shareable.

## Content Sections (in order)

### 1. Hero
- Headline: "The Container HQ Growth Playbook"
- Sub: "Cold email infrastructure that generates qualified operator leads for $437/month"
- Visual: animated number counter showing the cost breakdown

### 2. The Opportunity
- Container HQ sells 8x20 portable steel storage containers to self-storage operators
- Operators use them to expand facilities without permits or construction
- $80–$150/unit/month revenue from day one
- Already have a scraped list of self-storage facilities across US, Canada, Europe

### 3. The Stack (~$437/mo)
Visual cost breakdown cards:
- 20 Domains @ Porkbun: $40/mo
- 60 Inboxes @ Google Workspace: $360/mo  
- Instantly.ai (warmup + sending): $37/mo
- Total: $437/mo vs $8,000/mo agency cost
- Savings: $7,563/mo

### 4. The 20 Domains (confirmed available)
Show all 20 domains in a grid — two categories:
Brand variations: containerhq.co, containerhq.io, containerhq.net, getcontainerhq.com, trycontainerhq.com
Outcome-focused: expandmystorage.com, addstorageunits.com, selfstorageexpansion.com, storagefacilitygrowth.com, scaleyourstorage.com, storageunitexpansion.com, storagecontainerpro.com, containerstoragepro.com, containerexpansion.com, portablecontainerstorage.com, storageoperatortools.com, containerunitstorage.com, storagebuildfast.com, storageunitsfast.com, quickstoragescale.com

### 5. The Timeline (4 weeks)
Visual timeline:
- Week 1: Buy domains + set up Workspace + Instantly. Configure DNS, create 60 inboxes, start warmup.
- Week 2-3: Warmup running. Write copy, segment list, build sequences.
- Week 3: Start sending at low volume (20-30/day)
- Week 4+: Scale to 200/day, measure, optimize

### 6. The 3 Email Angles
Cards for each:
A) Capacity Hook — "Quick question about [Facility Name]" — short, curiosity-driven
B) Revenue Math — "$80-150/unit/month without construction" — ROI-focused
C) Proof of Work — Personalized Loom video showing their facility layout — highest reply rate

Rules: Plain text only. Under 100 words. One CTA. Never negotiate price first.

### 7. The 30-Day Targets
Metric cards:
- 2,000 emails sent
- 3-5% reply rate = 60-100 replies
- 20-30% positive = 12-30 interested operators
- Target: 5-10 discovery calls booked

### 8. What Kaulin Does vs What the Agent Does
Two-column layout:
Kaulin (1 hour total):
- Buy 20 domains on Porkbun (~30 min)
- Set up Google Workspace account (~15 min)
- Sign up for Instantly.ai (~10 min)

Agent handles everything else:
- All DNS records (DKIM, SPF, DMARC)
- All 60 inbox creation
- Warmup configuration
- Email copy writing (15 templates)
- List segmentation
- Sequence logic + A/B testing

### 9. The Longer Game (Month 2+)
- Programmatic SEO: 7,500 city/state landing pages
- Self-Storage Operator Weekly newsletter
- AI voice agent for inbound calls
- Competitor monitoring cron
- Site selection heatmap

## Design Direction
- AESTHETIC: Industrial editorial — like a premium trade publication meets a war room briefing
- PALETTE: Deep charcoal (#1a1a1a) background, warm white (#f5f0e8) text, electric orange (#ff4d00) accent, steel blue (#4a9eff) secondary
- TYPOGRAPHY: "Bebas Neue" for massive display numbers + headers (free Google Font), "DM Serif Display" for section titles, "DM Mono" for domain names and code/numbers
- LAYOUT: Full-width sections, each with distinct treatment. Numbers are BIG. Data is visual.
- ANIMATIONS: Subtle — counters count up on scroll, timeline dots pulse, cost cards flip in
- VIBE: Confident. This is a war room plan, not a pitch deck. No fluff, all signal.
- NOT: Purple gradients, Space Grotesk, generic SaaS look, corporate blue

## Technical Requirements
- Pure HTML/CSS/JS — no framework, no build step
- Must work as a GitHub Pages static site
- All fonts from Google Fonts (no local files)
- Responsive (readable on mobile)
- Fast — no external dependencies beyond fonts

## Output
Single file: index.html
