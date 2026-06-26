# Wylie Property Services — Project Reference

A working reference document capturing decisions, methodology, and reasoning behind the Wylie Property Services venture. Update this as new learning accumulates.

Live site: https://wyliepropertyservices.vercel.app/

---

## The Business

A commercial exterior maintenance company focused on recurring after-hours litter and debris cleanup contracts with property management firms in the GTA West corridor. Modeled loosely on Brian Winch's Cleanlots playbook (started 1981, US-based, sells a "Cleanlots" guidebook), adapted for the Ontario commercial property market in 2026.

**Owner-operator:** Brian Wylie (also operates BW Home Maintenance, a separate residential brand kept intentionally distinct from Wylie Property Services until the brand has traction).

**Service area:**
- Primary: Mississauga, Oakville, Burlington, Milton
- Secondary (select properties only): Ancaster, Brampton, Brantford, Etobicoke, Georgetown, Hamilton

**Service positioning:** After-hours service. Cleanup happens before tenants open and after they close so service never disrupts the property's business day. This is a deliberate differentiator from competitors who clean during business hours.

**Brand separation rationale:** BW Home Maintenance is B2C residential (homeowners buying pressure washing, etc.). Wylie Property Services is B2B commercial (property managers buying recurring contracts). Different audiences, different sales motions, different visual language. A future possibility is a parent site that routes visitors to residential vs commercial, but this is later, after Wylie has traction.

---

## Target Customer

**Decision-makers, in order of relevance:**

1. **Property Manager** — primary target. Manages a portfolio of 5-20 properties for one firm. Has signing authority for contracts up to $5,000-25,000/year. A litter cleanup contract at $1,000-1,300/month ($12-15K/year) fits within their signing authority at most mid-size firms.
2. **Facilities Manager / Operations Manager** — at larger firms, this role centralizes vendor contracts across the portfolio. Longer sales cycle but bigger volume per signature.
3. **Property Administrator / Assistant Property Manager** — gatekeeper, not decision-maker. Influences which proposals get prioritized. Treat with respect, ask for the property manager's name and email.
4. **Asset Manager** — wrong role. Works for the property owner on financial performance, not operations. If you reach one by mistake, ask for the Property Manager.

**Ideal firm profile:**
- Privately-held or family-owned (not REITs like RioCan, SmartCentres, First Capital, which have entrenched facility management vendors and slow procurement)
- Mid-size portfolio (5-50 properties) concentrated in the GTA West target geography
- Manages neighbourhood retail plazas, strip centres, mixed-use, light industrial, or multi-tenant office

---

## First Confirmed Lead

**The Laurier Group / Veritas Property Management**
- Private mid-size GTA commercial/industrial property management firm
- Head office likely Vaughan area (phone 905-738-2009, ext. 234 was identified)
- 13+ commercial properties across the GTA in their portfolio
- Two confirmed Oakville properties:
  - **2530 Sixth Line, Oakville** — 91,508 sqft parcel, 28,227 sqft building, ~58-60K sqft cleanable paved area. High litter generation (Circle K, two food tenants, bus stop, Holy Trinity HS within walking distance)
  - **1131 Nottinghill Gate, Oakville** — 93,438 sqft parcel, 28,612 sqft building, ~58-60K sqft cleanable paved area. Medium-high litter generation (kebab restaurant, pizza, transit stop adjacent)

These two are the planned first pitch with volume bundling.

---

## Pricing Methodology

### The core formula

**Monthly contract price = (Estimated minutes per visit / 60) × Target billed hourly rate × Visits per month × Litter intensity adjustment factor**

Where:
- Estimated minutes per visit comes from property assessment (see below)
- Target billed hourly rate is $100-120/hr CAD (this nets ~$65-78/hr after the ~35% unbilled overhead)
- Visits per month: 22 for 5-day/week, 26 for 6-day/week, 30 for 7-day/week
- Adjustment factor: 1.0 average, 1.2 high-generator properties, 0.85 low-generator

### Critical pricing discipline: billed vs net rate

A 35% overhead absorption is realistic for this kind of operation (drive time between properties, admin, prospecting, equipment, fuel, insurance, vehicle depreciation). So to net $75/hr, you must bill ~$115/hr. Pricing at $75/hr billed nets only $48/hr after overhead. **Always think in net terms, then back into the billed rate.**

### Drive time logic

Drive time is YOUR operational problem, not the customer's line item. Do NOT bill drive time explicitly. Absorb it through route density. One Oakville customer = 30 min drive overhead per visit. Five clustered Oakville customers = ~5-8 min between properties.

Route density math: 5 properties at $1,100/month each = $5,500/month for a 3-3.5 hour daily route = ~$71/hr net on a clustered route, with no drive time billed.

### Bundle/volume discount structure

Discounts should be framed as efficiency gains (route density), not arbitrary price cuts. Real operational savings from clustering one extra Oakville property: ~15-20 minutes drive time/day, ~$500/month in absorbed cost. So bundle discount should be 5-10% off combined, not 12-15%.

Example for Laurier:
- 2530 Sixth Line standalone (5x/week): $1,200/month
- 1131 Nottinghill standalone (5x/week): $1,100/month
- Combined standalone: $2,300/month
- Bundle offer (both at 5x/week): **$2,100/month** (saves them ~$200, 8.7% off)
- Bundle at 6x/week: $2,500/month

### Pitch tactic

Lead with standalone prices. Don't volunteer the discount. Let the property manager mention "what if we did both" or "any flexibility." Then bring out the bundle. Makes the discount feel like their idea, increases commitment.

---

## Property Assessment Methodology

The desktop pre-qualification process before any site walk:

1. **Google Maps satellite view** of the property
2. **Right-click → "Measure distance"** — trace the parcel perimeter to capture exact square footage. Subtract building footprint and landscape beds to get cleanable paved area
3. **Identify tenant mix** from the map labels and Street View
4. **Look for litter generators** within ~500m: schools, transit stops, fast food, convenience stores, gas stations, bars
5. **Apply Litter Generation Score** (weighted lookup, see below)
6. **Estimate per-visit time** using formula: ~8-12K sqft per minute walk time + stop-and-scoop time at high-accumulation zones + perimeter sweep + bag tie-off

### Litter Generation Score weights (provisional, calibrate against actual operating data)

- Tim Hortons within 200m: +5
- McDonald's/Wendy's/Burger King drive-thru: +5
- Gas station / convenience store: +3
- Vape shop: +3
- High school within 500m: +4
- LCBO/Beer Store: +2
- Transit stop on property: +2
- Bars / late-night food: +3

Total score modifies the base time estimate. Calibrate weights against real time-on-site data after the first 20 properties serviced.

### Time estimate cross-check (cars-as-ruler method)

Each parked car visible in satellite ≈ 15 sqm (160 sqft) of paved area including the space around it. Total parking spaces × 160 sqft + drive aisles (1.5-2x parking space area) + sidewalks ≈ paved area.

---

## Contract Caveats (Service Agreement Template)

Items to nail down before signing any contract:

1. **Disposal:** dumpster access vs haul-away. Price haul-away at ~$50-75/month per property if required. Always specify in writing which dumpster, since plaza dumpsters are usually CAM-charged and tenant-specific.

2. **Excessive litter events:** standard service covers routine. Dumped material, post-storm debris, vandalism, tenant move-outs get billed as incidents at $75-90/hr with prior written approval (photo evidence + estimate before doing the work).

3. **Sharps / biohazards:** start with Option A (declined, reported to property manager). Add Option B (premium sharps handling, ~$25-50/month) as a service upsell after 6 months.

4. **Weather:** snow days = modified visit (visible litter on plowed areas, full rate) or reduced winter retainer. Heavy rain = no adjustment.

5. **Frequency vs presence:** 5-day/week means 5 visits per 7-day period at contractor's scheduling discretion, not fixed Mon-Fri.

6. **Term:** 12-month initial, auto-renew with 60-90 days written notice to cancel. 30-day termination for cause. CPI escalator (greater of 3% or annual Ontario CPI change) on each anniversary.

7. **Insurance minimums:** $2M Commercial General Liability with property owner and management firm named as additional insureds. WSIB clearance certificate. Get this quoted before going to market.

8. **Found valuables:** report to property manager within 24 hours, deliver to management office or police. Never keep found items.

9. **Damage:** 24-hour incident reporting obligation. CGL covers, but property managers hate cover-ups.

10. **Scope creep from tenants:** contract specifies tenants can't expand scope. Small favours OK, anything larger goes through property manager in writing.

11. **Photo evidence:** scoped to incidents only (dumped material, vandalism, out-of-scope conditions). Not a routine visit deliverable. Justifies incident billing.

12. **Payment terms:** Net 30 standard. Don't accept Net 60 from a new client. 2%/month late fees written in.

---

## Sequencing Strategy

**Pre-revenue spend = zero on this category until verbal yes or signed contract.**

1. ~~Build pricing model~~ ✓ (in this doc)
2. ~~Build landing page~~ ✓ (live at https://wyliepropertyservices.vercel.app/)
3. ~~Wire Tally form~~ ✓
4. **Build prospecting list of property management firms** (separate thread)
5. **Develop proposal-generating system** (separate thread, leverages property assessment methodology)
6. **Cold outreach** (separate thread)
7. Site walks for the top 2-3 prospects (Laurier first)
8. Verbal yes triggers: incorporate Ontario corporation (~$300), bind insurance (~$800-1,500/year for $2M CGL), set up custom domain email (~$15-20/year)
9. Sign first contract
10. Refine pricing model and methodology against real operating data

---

## Brand & Site

**Domain:** wyliepropertyservices.vercel.app (free Vercel subdomain for now, custom .ca to come after revenue)

**Visual language:**
- Bone/charcoal palette with oxide rust accent (intentionally different from BW Home Maintenance to keep brands distinct)
- Instrument Serif (display) + Inter (body)
- Single-page site, deployed via GitHub → Vercel
- Tally form for inquiries (no backend needed)

**Tagline:** "Exterior maintenance you can count on, before your tenants are awake."

**Contact:**
- Phone: 226 268 2101
- Email: bri.mwylie@gmail.com (gmail flagged as credibility issue, upgrade to custom domain before first formal proposal)

---

## Open Questions / Decisions Pending

- Whether to incorporate Ontario corporation before pitching Laurier (cleaner B2B signal, $300, one day) or wait for verbal yes
- Whether to grab wylieproperty.ca domain before first proposal (~$15-20/year for credibility upgrade) — flagged but deferred
- Final Litter Generation Score calibration (current weights are provisional, needs first 20 properties of real operating data)
- Sharps/biohazard policy: starting with Option A (decline), planning Option B (premium service) as 6-month upsell

---

## Reference: Brian Winch / Cleanlots Model

Source: https://www.makingsenseofcents.com/2022/08/litter-cleanup-business

Winch's model:
- Started 1981
- Solo operator for decades
- Targets US$30-50/hour effective rate
- Quotes per-visit, not per-hour
- "Warm calling" approach: drive properties, identify ones with visible litter, approach the property manager with observation-based pitch (not a sales pitch)
- "Where there's litter, there's a potential client" — refined for our purposes to: "where there's litter AND the property is otherwise well-maintained, there's a great client" (the well-maintained property has an owner who pays for maintenance and has a gap in their service mix; the badly-maintained property has an owner who doesn't pay for maintenance and will ghost you)

His US$30-50/hour translates to roughly $45-75/hour CAD effective in our 2026 market for a solo operator. Premium positioning targets $65-78/hour net via $100-120/hour billed.
