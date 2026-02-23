# Full Financial Analysis — Swiss Physio Consumables Import

**Version:** 2.0 — MBA-grade  
**Date:** February 2026  
**Methodology:** Bottom-up cost build from factory gate to customer delivery. All figures in CHF unless stated. FX: USD/CHF 0.90.

---

## Executive Summary

The business is financially viable. At steady-state (60 accounts, ~40 orders/month), gross profit is ~CHF 2,300/month on revenue of ~CHF 3,800/month. Initial investment requirement is low (CHF 6,000–8,000 all-in). Break-even on startup costs is Month 3–4. Margins are genuinely strong (65–80% gross) because Swiss retail pricing is inflated by distributor chains, and direct import eliminates 2–3 layers of margin.

**The key risk isn't margin — it's volume.** The model works at 40+ orders/month. Getting there requires acquiring ~60 active accounts. That's the execution challenge.

---

## 1. Input Assumptions & Sources

### Factory Prices (USD, confirmed from Made-in-China.com, Alibaba, direct supplier pages)

| SKU | Price at 500 units | Price at 1,000 units | Price at 5,000 units | Source |
|---|---|---|---|---|
| Kinesiology tape 5cm×5m | $1.20/roll | $0.90/roll | $0.78/roll | Made-in-China.com (Feb 2026) |
| Kinesiology tape 5cm×32m | $4.00/roll | $3.20/roll | $2.50/roll | Aupcon.com, made-in-china.com |
| TENS electrode pads 4-pack 50×50mm | $1.80/pack | $1.40/pack | $0.95/pack | Quanding Medical, Alibaba |
| Ultrasound gel 1L | $3.50/unit | $2.80/unit | $2.00/unit | Made-in-China.com, Shanghai Shenfeng |
| Ultrasound gel 5L | $12.00/unit | $9.50/unit | $7.00/unit | Made-in-China.com |
| Resistance bands (set of 5) | $5.00/set | $4.00/set | $3.00/set | Alibaba general market |

**Working assumption:** First bulk order = 500 unit tier. Volume discount available once >1,000/SKU reached.

---

## 2. International Freight — China to Switzerland

### Key structural insight
Swiss customs duties on industrial goods = **0%** since January 1, 2024 (Switzerland abolished all remaining industrial tariffs — Bundesgesetz über die Abänderung des Zolltarifgesetzes, effective 01.01.2024). Only MWST applies at import.

### Freight rate data (2025, confirmed)

| Method | Rate | Door-to-door | Minimum | Best for |
|---|---|---|---|---|
| Economy air (forwarder, e.g., Flexport) | $3.50–5.00/kg | 7–14 days | $100–150/shipment | Bulk reorders ≥20kg |
| Standard air (DHL/FedEx commercial) | $8–12/kg | 5–8 days | Included | Mid-size orders |
| DHL Express | $20–30/kg | 3–5 days | Included | Samples / urgent |
| Sea freight LCL | $0.50–1.00/kg | 30–50 days | $200–400/CBM | Gel only — high weight/value ratio |

**Dimensional weight rule:** Air freight charges the greater of actual weight vs. volumetric weight (L×W×H cm ÷ 5,000 = volumetric kg).
- Kinesiology tape rolls: dense/small → actual weight dominates → good for air
- Ultrasound gel (5L): very dense (5+ kg/unit) → actual weight dominates → bad for air (expensive), good for sea

### Product-specific freight strategy

| Product | Recommended method | Reason |
|---|---|---|
| Kinesiology tape | Economy air / standard air | Light, high value density — air freight cost per unit is small |
| TENS pads | Economy air / standard air | Light, high value density |
| Resistance bands | Economy air | Light |
| Ultrasound gel 1L | Sea freight (group with gel 5L) | Water-based = heavy, low value/kg → air freight cost disproportionate |
| Ultrasound gel 5L | Sea freight mandatory | 6kg/unit × 15 units = 90kg; air freight would cost $450–900 for $142 of product |

**Two-channel freight approach:**
- Channel A (air): tape, pads, bands — 2–3 week order cycle
- Channel B (sea): gel — 6–8 week order cycle, hold 3 months' stock

---

## 3. Full Landed Cost Per Unit — Per SKU

### 3.1 Kinesiology Tape 5cm×5m

**Shipment basis:** 500-roll air shipment from Shenzhen  
**Shipment weight:** 500 rolls × 30g = 15kg net + packaging = ~20kg gross  
**Freight cost (economy air):** $4.50/kg × 20kg = $90. Plus Swiss customs clearance by DHL/forwarder included in economy rate. Basis: $90 total freight for 500 rolls.

| Cost component | Per roll | CHF | Notes |
|---|---|---|---|
| Factory price | $1.20 | CHF 1.08 | 500-unit tier |
| International freight | $90 / 500 rolls = $0.18 | CHF 0.16 | Economy air, 20kg shipment |
| Swiss customs clearance fee | CHF 80 / 500 = | CHF 0.16 | Customs agent fee, allocated per roll |
| Swiss customs duty | 0% | CHF 0.00 | Industrial tariff abolished Jan 2024 |
| Swiss import MWST (8.1% of CIF) | 8.1% × CHF 1.24 | CHF 0.10 | Paid at import, **reclaimed** — net CHF 0.00 |
| Private label sticker / insert | — | CHF 0.08 | Printed label roll, ~0.5g |
| Packaging (retail bag/header) | — | CHF 0.12 | Poly bag + cardboard header |
| Swiss domestic storage | — | CHF 0.02 | Home storage — negligible |
| **Total landed cost** | | **CHF 1.54** | |
| **Sell price ex-MWST** | | **CHF 5.90** | |
| **Gross profit per roll** | | **CHF 4.36** | |
| **Gross margin** | | **73.9%** | |

**AcuMax normal price:** CHF 9.90. **Our price is 40% cheaper.**  
**AcuMax sale price:** — Not consistently available.

---

### 3.2 Kinesiology Tape 5cm×32m (Bulk Practice Roll)

**Shipment basis:** 100-roll air shipment. Weight: 100 × 120g = 12kg + packaging = 15kg gross.

| Cost component | Per roll | CHF |
|---|---|---|
| Factory price | $4.00 | CHF 3.60 |
| International freight | $4.50 × 15kg / 100 = $0.68 | CHF 0.61 |
| Customs clearance fee | CHF 80 / 100 | CHF 0.80 |
| Customs duty | 0% | CHF 0.00 |
| Import MWST (reclaimed) | Net | CHF 0.00 |
| Packaging + label | — | CHF 0.25 |
| **Total landed** | | **CHF 5.26** |
| **Sell price ex-MWST** | | **CHF 18.90** |
| **Gross profit** | | **CHF 13.64** |
| **Gross margin** | | **72.2%** |

---

### 3.3 TENS Electrode Pads (4-pack, 50×50mm)

**Shipment basis:** 500-pack air shipment. Weight: 500 × 40g = 20kg + packaging = 25kg gross.

| Cost component | Per 4-pack | CHF |
|---|---|---|
| Factory price | $1.80 | CHF 1.62 |
| International freight | $4.50 × 25kg / 500 = $0.225 | CHF 0.20 |
| Customs clearance | CHF 80 / 500 | CHF 0.16 |
| Customs duty (HS 9018.90) | 0% | CHF 0.00 |
| Import MWST (reclaimed) | Net | CHF 0.00 |
| Packaging + CE importer label | — | CHF 0.20 |
| **Total landed** | | **CHF 2.18** |
| **Sell price ex-MWST** | | **CHF 5.90** |
| **Gross profit** | | **CHF 3.72** |
| **Gross margin** | | **63.1%** |

**Note on CE compliance cost:** We must be registered with Swissmedic as importer. Registration is free. CE certificate must be verified. Estimated one-time compliance setup time: 3–4 hours. No recurring cash cost. This is included in operating expenses below.

**AcuMax normal price: CHF 10.90.** We are **46% cheaper** at normal, **15% cheaper** vs. AcuMax sale price.

**Sensitivity: if we priced at CHF 7.90 (still 27% below AcuMax normal):**
- Gross profit: CHF 5.72 per pack
- Gross margin: 72.4%
- Still highly competitive; gives room to maneuver on B2B volume discounts

---

### 3.4 Ultrasound Gel 1L

**Freight model: SEA FREIGHT** (gel is water-based, ~1.1kg/L density = 1.1kg net per bottle)

**Shipment basis:** 100 × 1L bottles via sea freight LCL. Weight: 100 × 1.3kg gross = 130kg. Volume: 100 × 0.001m³ = 0.1 CBM.

Sea freight cost: $0.80/kg × 130kg = $104. But LCL minimum applies — add $200 for origin charges + consolidation. Total sea freight: $304. Per bottle: $3.04.

| Cost component | Per 1L bottle | CHF |
|---|---|---|
| Factory price | $2.80 | CHF 2.52 |
| Sea freight (incl. origin/consolidation) | $304 / 100 = $3.04 | CHF 2.74 |
| Swiss customs clearance | CHF 150 / 100 | CHF 1.50 |
| Customs duty | 0% | CHF 0.00 |
| Import MWST (reclaimed) | Net | CHF 0.00 |
| Packaging label | — | CHF 0.15 |
| **Total landed** | | **CHF 6.91** |
| **Sell price ex-MWST** | | **CHF 10.90** |
| **Gross profit** | | **CHF 3.99** |
| **Gross margin** | | **36.6%** |

⚠️ **Gel 1L is the weakest margin SKU.** The freight cost for heavy, water-based goods via sea LCL at small volumes is punishing. Minimum viable order = 200+ units before margins improve meaningfully.

At 200 units sea freight: $304 (fixed) + 200 × $0.80/kg × 1.3kg = $304 + $208 = $512. Per unit: $2.56 freight → CHF 2.30. Landed: CHF 5.97 → Margin = **45.2%**. Better but still thin.

At 500 units (full pallet, economy sea): $1/kg × 650kg = $650. Per unit: $1.30 → CHF 1.17. Landed: CHF 4.84 → Margin = **55.6%**. Viable.

**Recommendation: Don't sell 1L gel until order volume justifies 500-unit sea shipment, OR source gel locally (Swiss or German supplier) at a slight premium but no sea freight risk.**

---

### 3.5 Ultrasound Gel 5L

**Shipment basis:** 20 × 5L jugs via sea LCL. Gross weight: 20 × 6.5kg = 130kg. Volume: 20 × 0.008m³ = 0.16 CBM.

Sea freight: fixed origin + LCL charges = ~$300 minimum for this size. Per jug: $15.

| Cost component | Per 5L jug | CHF |
|---|---|---|
| Factory price | $9.50 | CHF 8.55 |
| Sea freight | $300 / 20 = $15 | CHF 13.50 |
| Customs clearance | CHF 150 / 20 | CHF 7.50 |
| Customs duty | 0% | CHF 0.00 |
| Import MWST (reclaimed) | Net | CHF 0.00 |
| Packaging label | — | CHF 0.20 |
| **Total landed (20-unit order)** | | **CHF 29.75** |
| **Sell price ex-MWST** | | **CHF 32.90** |
| **Gross profit** | | **CHF 3.15** |
| **Gross margin** | | **9.6%** |

⚠️ **Gel 5L at small volumes is nearly break-even on a unit economics basis.** Sea freight LCL minimum charges dominate when order size is small.

At 50-unit order: $300 + $0.80/kg × 50 × 6.5 = $300 + $260 = $560. Per jug: $11.20 → CHF 10.08 freight. Landed: CHF 19.83. Margin = **39.7%**.
At 100-unit order (full pallet): $0.80/kg × 650kg = $520. Per jug: $5.20 → CHF 4.68. Landed: CHF 14.73. Margin = **55.2%**.

**Gel viability threshold: minimum 50-unit sea shipment for 5L. Below this, economics don't work.**

**Alternative for gel (phase 1):** Source Dispogel or equivalent from a Swiss/German distributor at cost ≈ CHF 10–15/unit (confirmed from comparis.ch: multiple sellers from CHF 10). Re-sell at CHF 10.90 for 1L — thin margin, but no working capital risk, no sea freight. Use this for year 1 while building gel customer base, then switch to direct import at scale.

---

### 3.6 Resistance Bands (Set of 5)

**Shipment basis:** 200-set air shipment. Weight: 200 × 100g = 20kg + packaging = 25kg.

| Cost component | Per set | CHF |
|---|---|---|
| Factory price | $4.00 | CHF 3.60 |
| Air freight | $4.50 × 25kg / 200 = $0.56 | CHF 0.51 |
| Customs clearance | CHF 80 / 200 | CHF 0.40 |
| Customs duty | 0% | CHF 0.00 |
| Import MWST (reclaimed) | Net | CHF 0.00 |
| Packaging | — | CHF 0.20 |
| **Total landed** | | **CHF 4.71** |
| **Sell price ex-MWST** | | **CHF 11.90** |
| **Gross profit** | | **CHF 7.19** |
| **Gross margin** | | **60.4%** |

---

## 4. Domestic Costs (Swiss delivery to customers)

| Shipment size | Carrier | Cost | Notes |
|---|---|---|---|
| 0–2kg parcel | Swiss Post Priority | CHF 7.00 | Standard B2B delivery |
| 2–5kg parcel | Swiss Post Priority | CHF 9.50 | Typical medium order |
| 5–10kg parcel | Swiss Post Priority | CHF 12.00 | Large B2B order |
| 10–30kg parcel | Swiss Post Economy | CHF 18.00 | Bulk order |

**Delivery cost strategy:** Minimum order CHF 50. Free delivery above CHF 150 (vs. AcuMax's CHF 250 threshold — we win on convenience). Below CHF 150: flat CHF 6.90 shipping fee.

**Contribution from delivery on average CHF 95 order:**
- Orders CHF 50–150: CHF 6.90 collected. Actual cost CHF 7–9.50. Net: −CHF 0.60 to +CHF 0.10. Essentially neutral.
- Orders CHF 150+: CHF 0 collected. Cost CHF 9.50. Net: −CHF 9.50. This is a **marketing cost**, justified as acquisition/retention tool. Include in cost model.

---

## 5. MWST (Swiss VAT) — Full Treatment

### Import MWST
- 8.1% on CIF value (cost + freight + insurance) at Swiss border
- Paid to BAZG (customs) on delivery or monthly if registered
- **Fully reclaimable** as input tax in quarterly MWST filing
- Net cost to us: CHF 0.00 on imports

### MWST on sales
- We charge customers 8.1% on invoices (B2B physio practices are MWST-registered businesses → they reclaim it anyway)
- We collect CHF X, remit CHF X to ESTV quarterly
- Net cost to us: CHF 0.00

### What this means:
All prices in this model are **ex-MWST** (before tax). The CHF 5.90 tape sell price is ex-MWST. The customer pays CHF 5.90 × 1.081 = CHF 6.38 on the invoice. They reclaim CHF 0.48 from ESTV. We remit CHF 0.48 to ESTV. Revenue = CHF 5.90.

### MWST registration break-even:
Voluntary registration is worthwhile from Day 1. Year 1 import VAT reclaim on CHF 5,000 inventory = ~CHF 405. Registration admin: ~5 hours/quarter. Net benefit: strongly positive.

---

## 6. Operating Cost Structure

### Fixed monthly costs (Year 1)

| Cost | CHF/month | Notes |
|---|---|---|
| Shopify Basic | CHF 26 | $29/mo |
| Domain + email (G Suite) | CHF 12 | Prorated |
| Swiss Post parcel supplies (boxes, tape) | CHF 30 | ~30 parcels/month avg |
| Product liability insurance | CHF 33 | CHF 400/year |
| Accounting software (Bexio Basic) | CHF 12 | Swiss MWST-compliant |
| Phone/internet (allocated) | CHF 10 | Marginal |
| **Total fixed** | **CHF 123/month** | |

### Variable costs

| Cost | Rate | Applied to |
|---|---|---|
| Payment processing (Stripe CH) | 1.5% + CHF 0.25 | Per order |
| Free delivery cost | CHF 9.50 | Orders >CHF 150 |
| Returns handling | ~1% of revenue | Estimated |

**Blended payment processing cost:** On CHF 95 average order: 1.5% × CHF 95 + CHF 0.25 = CHF 1.68. Plus 8.1% MWST collected on processing fee = CHF 1.82 per order.

### One-time startup costs

| Cost | CHF | Notes |
|---|---|---|
| First sample order | CHF 170 | Airmail samples, AliExpress |
| Webshop setup (Shopify + theme) | CHF 450 | Basic setup, 10 hours own time |
| Private label design | CHF 200 | Logo + label design, Fiverr/Canva |
| Label printing (1,000 units) | CHF 80 | Local print shop |
| Initial marketing (targeted mailers to 100 physio practices) | CHF 200 | Printing + postage |
| Swissmedic registration | CHF 0 | Free |
| MWST registration | CHF 0 | Free |
| Legal pre-consultation (1h lawyer) | CHF 0–250 | Optional; probably skip at start |
| Buffer | CHF 200 | Misc setup |
| **Total one-time** | **CHF 1,300–1,550** | |

### First inventory investment

**Recommended Phase 1 inventory (air freight only — no gel initially):**

| SKU | Units | Factory (CHF) | Freight (CHF) | Landed total |
|---|---|---|---|---|
| Tape 5m | 500 rolls | CHF 540 | CHF 90 | CHF 630 |
| Tape 32m | 100 rolls | CHF 360 | CHF 54 | CHF 414 |
| TENS pads | 500 packs | CHF 810 | CHF 101 | CHF 911 |
| Resistance bands | 200 sets | CHF 720 | CHF 45 | CHF 765 |
| Customs clearance (2 shipments) | — | — | CHF 160 | CHF 160 |
| Import MWST (paid, reclaimed) | — | — | CHF 198 | (reclaimed) |
| **Inventory subtotal** | | | | **CHF 2,880** |

**Total initial outlay:** CHF 1,400 (setup) + CHF 2,880 (inventory) = **CHF 4,280**

*Gel added in Phase 2 (Month 3) when volume justifies 50-unit sea shipment.*

---

## 7. Per-Order Unit Economics

**Blended order model:** A typical physio practice monthly order contains:
- 10 rolls tape 5m × CHF 5.90 = CHF 59.00
- 5 packs TENS pads × CHF 5.90 = CHF 29.50
- 2 sets bands × CHF 11.90 = CHF 23.80
- **Order total: CHF 112.30 ex-MWST**
- **MWST collected (8.1%): CHF 9.10**
- **Invoice total: CHF 121.40**

| Component | Amount |
|---|---|
| Revenue (ex-MWST) | CHF 112.30 |
| COGS (blended landed cost) | CHF 33.20 |
| **Gross profit per order** | **CHF 79.10** |
| **Gross margin** | **70.4%** |
| Delivery cost (free above CHF 150 — N/A here, CHF 6.90 charged) | CHF 0 net (charged back) |
| Payment processing | CHF 1.82 |
| Packaging materials | CHF 0.80 |
| Your time (pack + ship, ~7 min) | CHF 0 cash (time cost only) |
| **Net contribution per order** | **CHF 76.48** |

At 40 orders/month (base scenario): **CHF 3,059 contribution/month** before fixed costs.
After fixed costs (CHF 123): **CHF 2,936/month net.**

---

## 8. 12-Month P&L Projection

*Assumptions: 10 new accounts per month. Average 3 orders/account/month in first 3 months, 5 orders/month by Month 6. CHF 112 average order.*

### Conservative (6 new accounts/month)

| Month | Active accounts | Orders/mo | Revenue | Gross Profit | Fixed | Delivery subsidy | Net |
|---|---|---|---|---|---|---|---|
| 1 | 6 | 12 | CHF 1,347 | CHF 948 | CHF 123 | −CHF 57 | CHF 768 |
| 2 | 12 | 26 | CHF 2,919 | CHF 2,055 | CHF 123 | −CHF 114 | CHF 1,818 |
| 3 | 18 | 42 | CHF 4,717 | CHF 3,321 | CHF 123 | −CHF 178 | CHF 3,020 |
| 4 | 24 | 58 | CHF 6,513 | CHF 4,585 | CHF 123 | −CHF 247 | CHF 4,215 |
| 5 | 30 | 72 | CHF 8,082 | CHF 5,690 | CHF 123 | −CHF 285 | CHF 5,282 |
| 6 | 36 | 88 | CHF 9,882 | CHF 6,961 | CHF 123 | −CHF 350 | CHF 6,488 |
| 7–12 | ~42–60 | ~100/mo | ~CHF 11,200 | ~CHF 7,886 | CHF 123 | ~−CHF 400 | ~CHF 7,363 |
| **Year 1 total** | | **~580** | **~CHF 65K** | **~CHF 46K** | CHF 1,476 | ~−CHF 2.5K | **~CHF 42K** |

### Base (10 new accounts/month)

| Month | Orders/mo | Revenue | Gross Profit | Net |
|---|---|---|---|---|
| 1 | 18 | CHF 2,021 | CHF 1,423 | CHF 1,243 |
| 2 | 38 | CHF 4,267 | CHF 3,004 | CHF 2,824 |
| 3 | 62 | CHF 6,963 | CHF 4,901 | CHF 4,721 |
| 4 | 88 | CHF 9,882 | CHF 6,961 | CHF 6,781 |
| 5 | 110 | CHF 12,353 | CHF 8,697 | CHF 8,517 |
| 6 | 120 | CHF 13,477 | CHF 9,490 | CHF 9,310 |
| 7–12 | 130/mo | CHF 14,600 | CHF 10,279 | CHF 10,099 |
| **Year 1 total** | **~870** | **~CHF 97K** | **~CHF 68K** | **~CHF 66K** |

---

## 9. Working Capital Analysis

**Cash conversion cycle:**
- Pay supplier: Day 0
- Goods arrive (air): Day 5–8
- Sell to customer: Day 8–90 (inventory turnover, ~30 days average holding)
- Customer pays (net-30 for Pro accounts): Day 38–120

**Working capital required at steady state (Base scenario, Month 6):**
- Inventory in transit and on hand: ~2 weeks of COGS = CHF 5,300 / 4 = CHF 1,325
- Accounts receivable (30-day terms, ~30% of monthly revenue): CHF 4,043
- **Total working capital: ~CHF 5,370**

Well within the CHF 10,000 budget. No financing needed.

**Cash flow pinch points:**
- Month 1: Pay for first inventory (CHF 2,880) + setup (CHF 1,400) before first revenue. Net cash out: CHF 4,280.
- Month 2: Need to reorder some SKUs before full revenue materializes.
- **Recommend: keep CHF 3,000 buffer above inventory cost at all times.**

---

## 10. Sensitivity Analysis

### A: What if AcuMax cuts prices to match us?

If AcuMax drops tape to CHF 5.90 (our price) permanently:
- Our only differentiator becomes B2B account management and delivery speed
- Margin unchanged (we still buy at cost)
- **Impact: lower customer acquisition, not margin. Model survives.**

### B: USD/CHF weakens by 10% (CHF 0.81 instead of 0.90)

| SKU | Normal landed | Landed at 0.81 | Sell price | Margin change |
|---|---|---|---|---|
| Tape 5m | CHF 1.54 | CHF 1.41 | CHF 5.90 | +2.3pp (improves!) |

CHF weakening = cheaper imports for us = BETTER margins. CHF is historically strong. Downside scenario = CHF strengthens (imports get pricier).

**CHF strengthens to 0.95:**
- Tape landed: CHF 1.60. Margin: 72.9% (−1pp). Negligible.
- TENS pads landed: CHF 2.22. Margin: 62.4% (−0.7pp). Negligible.
- **FX risk is very low for this business.**

### C: Freight rates spike 30% (geopolitical disruption)

Air freight goes from $4.50/kg to $5.85/kg:
- Tape landed: CHF 1.69 (was CHF 1.54). Margin: 71.4% (−2.5pp).
- TENS pads landed: CHF 2.26. Margin: 61.7% (−1.4pp).
- **Impact: minor. Freight is a small portion of landed cost for light goods.**

### D: Chinese supplier raises prices 20% (inflation / tariff)

- Tape factory goes from $1.20 to $1.44/roll
- Tape landed: CHF 1.75. Margin: 70.3% (−3.6pp).
- Can absorb without price increase. If persistent, raise sell price by 5% to CHF 6.20.

### E: Low volume (only 20 active accounts at Year 1 end)

- 20 accounts × 4 orders/month × CHF 112 = CHF 8,960/month revenue
- Monthly net contribution: ~CHF 6,200
- Fixed costs: CHF 123
- **Net: CHF 6,077/month — still profitable, just smaller**
- Break-even on startup costs (CHF 4,280): still Month 2 in this scenario

---

## 11. Is CHF 5.90 Tape Price Feasible?

**Yes, clearly.** Let's reconcile:

| | Per roll |
|---|---|
| Factory | CHF 1.08 |
| All landed costs | CHF 1.54 |
| Sell at | CHF 5.90 |
| Gross profit | CHF 4.36 |
| Gross margin | **73.9%** |
| Price vs. AcuMax | **−40%** |
| Price vs. Nasara retail (CHF 18+) | **−67%** |

The CHF 5.90 price is:
- **Profitable** at 73.9% gross margin
- **Competitive** at −40% below the main Swiss competitor
- **Not undercutting to the bone** — there's room to offer 10–15% B2B volume discounts and still be solidly in the black

**The TENS pad question (AcuMax sale price CHF 6.90 vs. our CHF 5.90):**

Our CHF 5.90 is CHF 1 below AcuMax's *promotional* price. This works as long as AcuMax doesn't run sales constantly. If they do, consider dropping to CHF 4.90 (margin drops to 55% — still fine) or holding at CHF 5.90 and emphasizing the account benefits (no minimum order, same-day dispatch, B2B invoice).

---

## 12. Summary: Is This Business Financially Viable?

| Question | Answer |
|---|---|
| Are our prices feasible? | ✅ Yes — strong margin at competitive prices |
| Can we undercut AcuMax by 30–40%? | ✅ Yes, comfortably |
| Is the gel economics OK? | ⚠️ Only at 50+ unit sea freight orders. Phase 2 only. |
| What's the minimum viable scale? | 20 active accounts = profitable |
| What's the startup cost? | CHF 4,000–5,000 realistic |
| When do we break even on startup? | Month 2–3 (base/optimistic), Month 3–4 (conservative) |
| What's the Year 1 net (base case)? | ~CHF 66,000 |
| FX risk? | Very low |
| Freight risk? | Low for light goods (tape, pads). High for gel at small volumes. |
| What could kill it? | Failing to acquire accounts. Not margin. |
