# event-management

# Event Photo Sharing Platform (QR + Face Match) — Product Plan

**Concept:** Photographer uploads event photos → guests scan a QR code, upload a selfie → AI face-match finds and delivers only their photos.

---

## 1. Market Landscape

### Existing Players (already proven category)
| Player | Region | Notes |
|---|---|---|
| FotoOwl | India | Closest match to this concept — bulk upload + selfie-based face match |
| Sortmyphotos, PixellotAI, ShareMyImage | India | Similar face-recognition event delivery |
| PhotoDay, SnapBar | US | Same concept for events/schools |
| Pixieset, ShootProof | Global | Gallery tools with some face-search add-ons |

**Conclusion:** This is not a blue-ocean idea — it's an already-validated, working business model. The opportunity lies in a differentiated angle, not the base concept.

### Technology Feasibility
- Face recognition: mature, off-the-shelf (AWS Rekognition, Azure Face API, or open-source InsightFace)
- QR generation + selfie upload flow: straightforward to build
- No major technical barrier to entry

---

## 2. Adoption Reality (Where the Real Gap Is)

| Segment | Current Status |
|---|---|
| Metro premium wedding photographers (Chennai, Bangalore, Mumbai) | Aware of & using such tools |
| Tier 2/3 city & local/freelance photographers | **90%+ still manual** — Google Drive links, WhatsApp bulk sharing |

**This is the real opportunity: category is standard, but adoption is not.** Most photographers outside metros either don't know these tools exist or assume they're too expensive to try.

### Known Pain Points in Existing Tools
- **Photographer side:** complex bulk upload, slow processing, high storage cost, expensive per-event pricing
- **Guest side:** face-match accuracy issues in group photos, forced app downloads instead of direct delivery
- **Trust/privacy:** guests uneasy about face data storage and who can access their photos

---

## 3. Target Segment & Differentiation

**Target:** Tier 2/3 city photographers and independent/freelance photographers (not big metro studios)

**Differentiation angle:**
- Affordable, flat pricing (not per-photo/per-event like incumbents)
- Tamil/regional language support
- Simple onboarding — photographer setup in ~10 minutes
- WhatsApp-first delivery for guests — no app download required
- Faster same-day delivery during the event itself

---

## 4. Pricing Model

### Why Pure Monthly Subscription Doesn't Work
Photography demand is **seasonal**, not steady:
- Wedding season (Oct–Feb, Apr–Jun): high volume
- Off-season (monsoon, inauspicious months): near-zero events

A flat "₹999/month forever" subscription leads to **churn during off-season** — photographers feel they're paying for nothing, cancel, and may not return when demand picks back up.

### Recommended: Hybrid Pricing Model

| Model | Structure | Best For |
|---|---|---|
| **Pay-Per-Event (default)** | ₹199–₹499 per event, based on guest count/photo volume | Low commitment, easy trial, matches irregular usage |
| **Season Pass** | e.g., ₹4,999 for 5 months (Oct–Feb) unlimited events | Heavy users during peak wedding season — framed as a "season pack," not a monthly subscription |
| **Credit System** | ₹999 = 5 event credits, valid 6 months | Middle ground — photographer feels invested without recurring pressure, no "waste" feeling |

**Recommendation:** Default to pay-per-event for easy adoption; upsell season pass/credits to high-frequency users (studios with multiple photographers).

### Unit Economics to Verify Before Locking Pricing
- Face recognition API cost (~$0.001/image on AWS Rekognition, or self-hosted server cost if using open-source models)
- Storage cost (photo files are large — cost scales fast with volume; avoid promising "unlimited storage" at low price points)
- Confirm: **price − (API cost + storage cost) = healthy margin**, before finalizing any tier

---

## 5. Verdict

| Question | Answer |
|---|---|
| Is this idea "possible"? | Yes — it's already a proven, working business model |
| Is it a "new" idea? | No — existing players are established; success depends on differentiation |
| Is there a real market gap? | Yes — Tier 2/3 photographer segment is underserved and largely still manual |
| Does flat monthly subscription work? | No — seasonal usage makes it churn-prone; use hybrid pay-per-event + season pass model instead |

**Bottom line:** Viable business, but position clearly as *"FotoOwl for Tier 2/3 photographers — affordable, WhatsApp-first, no app needed"* rather than a generic competitor in an already-crowded metro market.