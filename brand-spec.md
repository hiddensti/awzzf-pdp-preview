# Atomic Wheels · AWZZF PDP — Brand Spec

> Captured 2026-04-29. Asset completeness: **HIGH** — real logo, real product renders, real palette extracted from production CSS, real font, real PDP copy from current live page.
> Source domain: `atomic-wheels.com` (NOT `atomicwheels.com` — that's a parked domain).

---

## 🎯 Core Assets

### Logo
- **File:** `assets/atomic-wheels-brand/logo_300x.webp` (actually PNG, 300×87, RGBA, transparent bg)
- **Composition:** red curving "smile" arc above wordmark `ATOMIC WHEELS`
- **Usage:** header (lockup), footer (smaller). Works on white. For dark bg → request reversed version (not yet pulled).
- **Don't:** stretch, recolor the arc, add stroke.

### Product renders (real AWZZF, not placeholders)
- `assets/atomic-wheels-brand/awzzf-photos/0504.jpg` — main 3/4 hero, polished/silver finish, white backdrop, 916×916 (best hero candidate, score 8.5/10 — clean, on-brand)
- `awzzf-photos/20240809181452.jpg` — likely alt angle / detail
- `awzzf-photos/2_b34fa3f0-b77c-4489-9e51-3294b9e09023.jpg` — alt
- `awzzf-photos/3f98400ea11cf8a7d6483163fb5faa32_2_12.jpg` — alt
- `awzzf-photos/901c891068e4189565a0f18c0fd150b7.jpg` — alt
- **Photography style:** studio 3/4 angle, white background, soft shadow under wheel, no environment. Match this for any new shots.

### Reference PDP photos (existing AWZZ for tone)
- `assets/atomic-wheels-brand/awzz-reference-1.jpg` (1600×1200, "stamp" watermark on real shot)

---

## 🎨 Brand System

### Palette (extracted from production CSS, top hex frequency)
| Token | Hex | Usage |
|---|---|---|
| **Primary / Brand Red** | `#ee3d48` | CTA buttons, hero accents, section heading underlines, footer titles |
| **Ink (charcoal)** | `#1c1c1c` | Body text, primary nav |
| **Ink alt** | `#18181a` / `#282a2c` / `#231f20` | secondary text, borders |
| **Mute** | `#6c757d` | sub-copy, captions |
| **Bg** | `#ffffff` | page background |
| **Bg alt** | `#fafafa` / `#f9fafb` | section dividers |
| **Border** | `#e9e9e9` / `#dfdfdf` | hairlines |
| **Announcement bar bg** | dark red (per current homepage screenshot, sampling needed if exact match required) |
| **Secondary bar bg** | navy (`#1d2c40`-ish, sampled visually from screenshot) |

> Note: WebFetch initially hallucinated brand color as `#FFD700` gold because it saw 💰 emoji in the announcement banner. Raw CSS confirms primary is **red `#ee3d48`** (35 occurrences). This is a fact-check win.

### Type
- **Family (display + body):** **Lato** — preloaded as `lato_n5.woff2` from `atomic-wheels.com/cdn/fonts/lato/`
- **Weights observed:** 400 (n4), 500 (n5), 700 (bold)
- **Stack to use:** `'Lato', -apple-system, BlinkMacSystemFont, sans-serif`
- **No serif anywhere** on production site — keep PDP all-Lato.

### Tone of voice
From real meta description on AWZZF page:
> "Shop the AWZZF Flow Form Wheels for Tesla Model 3/Y at Atomic Wheels. Designed for maximum performance and durability. Order now for a perfect fit and improved driving experience!"

- Direct US e-commerce voice. Imperative ("Shop", "Order now").
- Keywords AW uses: "performance", "durability", "perfect fit", "premium", "engineered", "lifetime structural warranty".
- Audience: car enthusiast, technical-but-accessible, no jargon flex.

### Trust badges (confirmed on AWZZ + site-wide)
- **Lifetime Structural Warranty**
- **50% off accidental damage replacement**
- Premium 6061-T6 forged aluminum (for AWZZ; AWZZF is flow-formed — copy must differ)
- Free US Shipping on Orders $100+
- 147 customer reviews (Judge.me widget)

### Header structure (production)
- Top announcement bar (red bg, white text): `💰 Tax Season Upgrade — 15% Off Wheels & Accessories + Free US Shipping on Orders $100+ | Excludes Tire Sets | Use Code TAX15`
- Secondary bar (navy bg): `Big Discounts • Exclusive Wheel and Tire Deals • Shop Now`
- Main nav: WHEELS / TIRE SETS / ACCESSORIES / WHEEL SERVICES / INTERIOR & EXTERIOR / PHOTO GALLERY / REVIEWS / Fitment Guides / CONTACT US / WHO WE ARE
- Right icons: Search / Login / Cart

### Footer structure
3 columns: Main Menu / Helpful Information / Contact Details. Social: Facebook, Instagram, YouTube. Copyright: `Copyright © 2026 Atomic Wheels`.

### Signature details to do at 120%
- Sticky pre-order CTA on mobile with countdown to "end of July" delivery
- Variant picker: color swatches as **filled circles** (not dropdowns), size as button group
- Spec table with `#18-8535` / `#19-9535` SKU codes treated as quasi-monospace tags (real AW does this)

### Don't / red lines
- No purple/violet anywhere — not in palette
- No emoji in body copy (only in promo announcement bar)
- No serif fonts
- No "AI-generated wheel render" — we have real renders, use them
- No fake reviews — use placeholder review cards labeled `<!-- placeholder, fill from Judge.me -->`

---

## 📦 AWZZF · Real Product Facts (live as of 2026-04-29)

**URL:** https://atomic-wheels.com/products/awzzf-flow-form-wheels-for-tesla-model-3-y

### Variants — **8 total** (2 sizes × 4 colors, NOT 6)
| Size | Width × Offset | SKU | Available colors |
|---|---|---|---|
| 18" | 8.5" +35 | `#18-8535` | Gloss Black · Satin Black · Satin Bronze · Satin Gunmetal |
| 19" | 9.5" +35 | `#19-9535` | Gloss Black · Satin Black · Satin Bronze · Satin Gunmetal |

> **Open question for user:** original brief said "3 colors per size". Live site has 4. Which is correct for the prototype — drop one (which?) or show all 4?

### Pricing (per wheel, USD)
- $346.50 (lowest)
- $369.00
- $385.00 (advertised in search dropdown — likely 18" baseline)
- $410.00 (highest)

> **Open question for user:** confirm price-per-variant mapping. Price shown in PDP per single wheel; sets of 4 = ~$1,386–$1,640.

### Pre-order mechanics (real, copy-pasted from page)
- **ETA:** "Estimated delivery time — end of July"
- **Early Bird offer:** "Enjoy an extra 10% off at checkout with our Early Bird Pre-Order. This discount stacks with any other active coupons."
- **Payment:** "Your remaining balance will be charged once the items arrive at our warehouse."
- **Alt scheme:** Partial payment option `$10 per wheel` deposit

### Companion PDPs (for "Related products" block)
- AWZZF for BMW F30/F10/E90 — $365
- AWZZF for BMW G20/G30 — $365
- AWZZ Forged for Tesla Model 3/Y — $615 (the premium upsell)

---

## 🚦 Open questions before v1 build

1. **3 vs 4 colors** — your brief said 3, live site has 4. Which is the ground truth?
2. **Hero copy direction** — current AW pages use a generic "Shop the AWZZF…" meta. Want me to write tighter PDP hero copy ("Forged-grade strength. Cast-grade price.") or stay close to the current AW house tone?
3. **Comparison block** — AWZZF vs AWZZ vs Cast: is positioning "85–90% of forged strength at ~60% price" official messaging, or is that my fabrication that needs to be replaced/removed?
4. **Pre-order incentive prominence** — make the Early Bird +10% the primary CTA hook (e.g. "Pre-order now, save 10%") or keep it as a secondary line?
5. **Reviews block** — the live AWZZF page presumably has 0 or few reviews. Should the prototype show real placeholder count or be hidden until reviews exist?

---

## ✅ Asset checklist (Core Asset Protocol Step 5 sign-off)

- [x] Logo downloaded, transparent PNG, header-ready
- [x] Product renders downloaded (5 real AWZZF photos)
- [x] Reference photography style captured (1 AWZZ shot)
- [x] Color palette extracted from real production CSS, 7 tokens defined
- [x] Font confirmed (Lato, woff2 from CDN)
- [x] Tone of voice samples extracted from live meta + AWZZ page
- [x] Header/footer/announcement-bar structure documented
- [x] Trust badges enumerated
- [x] Real PDP variants/pricing/ETA captured
- [ ] Reverse-color logo for dark sections (not yet needed — PDP body is white)

**Status:** ready for v1 build pending answers to 5 open questions above.
