# Setup Wizard — Start Here

The first thing Muse Autopilot does is interview the owner about the business.
Seven short screens, about eighteen questions, most with defaults you can accept in one tap.
Nothing runs until the wizard finishes — the answers become the system's constitution:
they fill the knowledge base, set the money limits, and arm the approval gates.

**Flow:** answer → review one summary screen → confirm → Autopilot generates the
knowledge-base files and each executive's decision rights from your answers.

---

## Screen 0 — Bring Your Business With You  *(before any questions)*
The fastest setup is not typing — it is handing the system what already exists.
Everything given here is used to **pre-fill** the questionnaire; you confirm or edit instead of typing.

**Your website**
- **Business website URL** — the system reads it on the spot: business name, services/offers,
  service area, contact details, brand colours, and the tone of the copy.
  Screens 1, 3 and 4 arrive pre-filled from your own site. No website? Skip it, type instead.

**Uploads — any business data you have**
| Upload | What the system does with it |
|---|---|
| **Leads CSV** | Maps the columns (name, email, phone, company, source, status, notes — any order, extra columns kept), dedupes on email + phone, scores every lead, loads the CRM as `imported — uncontacted` |
| **Customers / clients CSV** | Loads the client book: who buys, how often, what they pay — feeds retention, reviews and referral plays |
| **Products / services / price list** (CSV, PDF, or a page of your site) | Builds the offer catalog and pricing file |
| **Past invoices or sales export** (CSV) | Seeds the finance picture: real revenue pattern, best sellers, late payers |
| **Documents** (proposals, contracts, menus, SOPs — PDF/Word/text) | Read into the knowledge base as source material for drafts and answers |
| **Logo & brand images** | Locked in as the visual identity; brand colour double-checked against the logo |
| **Reviews / testimonials file** | Stored as approved social proof the content engine may quote — verbatim only |

**Import rules (hard):**
- Importing is **not** permission to contact. Imported leads are never emailed, DM'd or called
  until the owner approves an outreach batch — same gate as everything else.
- Every import reports back: *rows in, duplicates removed, rows missing contact info, columns guessed.*
  Guessed columns are flagged for one-tap correction, never silently trusted.
- Uploads live in the business knowledge base only. They are never shared outside the business.

*Configures:* the pre-fill for Screens 1–4, `03_SALES` (lead book), `02_OFFERS/offer_catalog.md`,
`06_FINANCE` (revenue seed), `01_BRAND/logo_and_asset_rules.md`

## Screen 1 — The Business
1. **Business name?** *(text)*
2. **What do you sell, in one line?** *(text)*
3. **Who is it for — your ideal customer?** *(text)*
4. **Where do you sell — city/region, or online?** *(text)*

*Configures:* `00_COMMAND_CENTER/company_goals.md`, `02_OFFERS/ideal_customer_profiles.md`

## Screen 2 — The Money
5. **Monthly revenue goal?** *(number — the number the whole system optimizes toward)*
6. **Roughly where is revenue now?** *(pick: pre-revenue / under $5k / $5–25k / $25k+ a month)*
7. **Monthly spend the system may test with, inside the batch approvals?** *(number — your test budget cap)*

*Configures:* `06_FINANCE/margin_targets.md`, the Budget rule, CFO thresholds

## Screen 3 — The Offers
8. **Your core offers and price range?** *(text — one per line)*
9. **One thing you never promise or discount?** *(text — becomes a hard prohibited rule)*

*Configures:* `02_OFFERS/offer_catalog.md`, `02_OFFERS/pricing_and_packages.md`, `01_BRAND/prohibited_claims.md`

## Screen 4 — The Brand
10. **Voice — pick the closest three:** *(direct / bold / friendly / premium / funny / no-nonsense)*
11. **Brand colour?** *(hex or name — default: electric blue `#0066FF`)*

*Configures:* `01_BRAND/brand_voice.md`, `01_BRAND/visual_identity.md`

## Screen 5 — Decision Limits  *(the most important screen)*
12. **What may run without you?** *(checklist, defaults on: internal summaries, lead scoring, drafts, reports)*
13. **What must ALWAYS stop for you?** *(checklist, defaults on: spending, refunds, legal, deletions, new promises to clients)*
14. **Your two daily approval windows?** *(times — default 9:00 AM and 4:00 PM)*
15. **Confidence floor — below this, the system escalates instead of acting?** *(slider — default 75; 90+ acts, 75–89 batches)*

*Configures:* `00_COMMAND_CENTER/decision_rights.md` — every executive inherits these exact limits

## Screen 6 — Tools & Priorities
16. **Which tools do we connect first?** *(checklist: email, calendar, Drive, WhatsApp/Slack, CRM, Meta Ads, Instagram, Shopify, Stripe)*
17. **Top 3 priorities for the next 30 days?** *(text)*
18. **The #1 bottleneck right now?** *(pick: leads / sales / delivery / cash / time)*

*Configures:* `00_COMMAND_CENTER/current_priorities.md`, the connector rollout order, the CEO's first-week plan

---

## Summary screen (before anything is saved)
The wizard shows one page back: *here is your business, your money limits, your red lines,
your approval windows* — Edit any line, then **Confirm & Build**.
On confirm it writes the knowledge base, generates each executive's prompt from the
standard skeleton with your limits filled in, and schedules the first Daily Control Room.

**Skip rule:** any question can be skipped except Screen 5. A business can be vague;
its red lines cannot.
