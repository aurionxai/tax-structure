# Tax Structure Plan — Multi-Partner Active Trading Operating Entity

> **Scope:** $50M+/year trading profits · US-citizen partners · domiciled in no-income-tax states (FL/TX/WY/NV/TN/SD/WA/AK/NH) · **greenfield (no entity yet — sole/individual accounts today)** · **100% single-name (ticker) options, high-frequency** — these are *securities*, NOT §1256, so the core book is ordinary-rate (~40.8%); **§475(f) is mandatory protection** and **PPLI is the primary rate lever**.
>
> **IMPORTANT — read first:** This is an *educational structuring design*, not legal or tax advice, and not a substitute for engagement. Tax *mitigation/avoidance* (using the Code as written) is legal; *evasion* is not — every element below is a mainstream, defensible planning tool, but each carries doctrine-level guardrails (economic substance §7701(o), investor-control doctrine, reasonable compensation, §817(h) diversification) that a licensed **tax attorney + CPA** must implement. Elections here have **hard, unforgiving deadlines**. Do not self-execute.

---

## Context

The partners run a high-frequency, real-time daily trading operation generating ~$50M/yr. This income is overwhelmingly **short-term / ordinary** — the worst possible character for tax purposes:
- Not eligible for long-term capital gains rates (held < 1 year).
- Not eligible for the §199A QBI deduction (trading is a specified service business *and* trading gains generally aren't QBI).
- Not subject to SE tax (a benefit) — but that also means there's no "earned income" base to fund retirement plans from the trading P&L directly.

Because the partners already live in zero-tax states, **state planning is effectively done**; the objective is to legally reduce/defer the **federal** bite (top 37% + 3.8% NIIT context) on ordinary trading income. The single largest legitimate lever at this scale is **character conversion and tax-free inside buildup**, not deductions.

**NIIT exemption under TTS (contested — high-dollar if confirmed):** The 3.8% NIIT (§1411) may not apply to TTS traders' trading income. The argument: TTS trading income arises from an active §162 trade or business, which is excluded from the §1411 net investment income base. The IRS has not definitively ruled; this position is contested but widely taken by trader-tax practitioners. If confirmed: **baseline drops from 40.8% → 37% — saving $1.9M/yr firmwide at $50M**. The CPA must model both scenarios, take a documented position with supporting authority, and re-run the effective-rate model accordingly. Do not assume it applies without counsel sign-off.

---

## Recommended Architecture (layered)

### Layer 1 — Core operating stack (foundation)

**Entity A — Trading vehicle: LP or LLC taxed as a partnership (Form 1065).**
- Holds capital, executes all trades, claims **Trader Tax Status (TTS)** (facts-and-circumstances: substantial, frequent, regular, continuous; multiple active partners strengthens the "business" narrative).
- **Greenfield advantage:** because nothing is formed yet, we form clean entities and capture the **§475(f) election within the 75-day internal-resolution window** (dated internal resolution, no IRS filing) — no transition mess, no pre-existing wash-sale baggage, free choice of WY/DE/NV domicile. (An *existing* entity would instead face the brutal **March 15** deadline.)

**Single-name HFT options election strategy:**
- **Ticker-symbol options are *securities*, not §1256** — no 60/40 treatment available on the core book. It is taxed at ordinary rates (~40.8% top, incl. NIIT).
- **§475(f) MTM is therefore MANDATORY, not optional** — high-frequency single-name options without 475 is a wash-sale catastrophe: thousands of overlapping trades in substantially-identical strikes/expiries defer losses and generate **phantom taxable income** that can exceed economic profit. 475 makes everything clean MTM ordinary, with **uncapped ordinary losses**. This is large-dollar *protection*, but not a rate reduction.
- **§1256 routing survives only as an upside option:** if any sub-strategy's edge ports to broad-based index paper (SPX/XSP/NDX — these ARE §1256, while SPY/QQQ/single-names are not), each 10% of P&L moved saves ~10.2 rate points (~$510K/yr per 10% at $50M). But **never trade alpha for tax** — if the edge is ticker-specific, it doesn't port, and forcing it costs more than it saves.
- **Consequence for the rest of the plan:** with the core P&L locked at ordinary rates, **PPLI (Layer 3) and substance-based deduction generators (Layer 5) are the primary rate levers**, and OZ rollovers are unavailable (475 gains are ordinary, not capital).

**Entity B — Solo S-corp per partner (each partner owns and operates independently).**
- Each partner forms their **own S-corp** — sole owner, sole operator, full solopreneur treatment. No shared entity for management; each S-corp is independent.
- Each S-corp charges the Trading LP its own management fee → earned income base for retirement plans, health insurance, and deductions.
- Each partner is fully responsible for their own S-corp's payroll, filings, retirement plans, and compliance — independent of other partners.
- **W-2 requirement:** MUST pay a reasonable W-2 salary before distributions (*Watson v. Commissioner*). Typical defensible range: **$150–200K minimum** (enough to support the retirement contribution math; higher if role warrants). Everything above salary = distributions, no payroll tax.
- **The Trading LP K-1 is separate:** the bulk of the $50M flows as K-1 — NO W-2, NO SE tax. W-2 rule only touches the management fee slice inside the S-corp.
- **The Trading LP needs zero employees.** TTS qualification is about trading activity, not headcount.
- **Documentation critical for solo setup:** the S-corp must have genuine, documented services provided to the Trading LP — research, risk management, administrative oversight. Solo setup with thin documentation is the most common solo-trader audit trigger.

### Layer 2 — Solo S-corp retirement stack (the solopreneur advantage)

Because each S-corp has a single participant, the cash-balance plan is sized purely around that partner's age — no dilution across multiple participants. This is the solopreneur retirement edge.

**Per-partner annual shelter (age-dependent):**

| Age | Cash-balance/DB | 401(k) elective | Mega backdoor Roth | Backdoor Roth IRA | Total shelter |
|-----|----------------|-----------------|-------------------|-------------------|---------------|
| 40  | ~$100K         | $23,500         | ~$48,500          | $7,000            | ~$179K        |
| 50  | ~$175K         | $31,000         | ~$49,000          | $8,000            | ~$263K        |
| 55  | ~$220K         | $31,000         | ~$49,000          | $8,000            | ~$308K        |
| 60+ | ~$280K+        | $34,750         | ~$45,250          | $8,000            | ~$368K+       |

*2026 §415 limits: $72,000 (under 50) / $80,000 (50+). Mega backdoor = §415 limit minus elective deferrals. Age 60–63 enhanced catch-up (SECURE 2.0) = $11,250 → reduces after-tax room slightly vs. 50–59.*

**Key rules:**
- **Cash-balance/DB:** pre-tax deferral, NOT Roth. Grows tax-deferred, taxed on withdrawal. Contributions are % of W-2 comp — the $150–200K+ salary must be set high enough to support the math.
- **Mega backdoor Roth:** after-tax 401(k) contributions up to the §415 DC limit (**$72K under 50 / $80K age 50+ in 2026**), immediately converted to Roth. After-tax room = §415 limit minus elective deferrals: **~$48,500 (under 50) / ~$49,000 (50–59) / ~$45,250 (60–63)**. Less if S-corp pays employer match/profit-sharing into the plan.
- **Backdoor Roth IRA:** $7K–$8K/yr (age 50+) — contribute to traditional IRA, immediately convert. Separate from the 401(k) stack.
- **What $165K+ actually means:** total retirement deferral space (cash-balance + 401(k)) can exceed $165K, but **only the ~$46–54K after-tax/Roth portion goes into Roth**. The rest is pre-tax. Both are worth doing — different tools.
- Health insurance premiums deductible through the S-corp.

### Layer 3 — The centerpiece: tax-free inside buildup via insurance wrapper

This is what actually moves the needle on a high-churn ordinary-income strategy:

- **Private Placement Life Insurance (PPLI)** wrapping an **Insurance-Dedicated Fund (IDF)** that runs the trading strategy.
  - Growth inside the policy compounds **tax-free**; policy **loans** are accessed tax-free; **death benefit** passes income-tax-free.
  - Converts the most tax-inefficient income (short-term trading gains) into tax-free buildup — the institutional answer to exactly this fact pattern.
  - **Hard requirements / guardrails:** partners must be **accredited investors / qualified purchasers**; **§817(h) diversification** rules; and the **investor-control doctrine** (the insured cannot direct the underlying trades — an independent IDF manager must run it). Insurability and underwriting required.
- **Private Placement Variable Annuity (PPVA)** as the alternative where insurability is poor — gives tax **deferral** (distributions are ordinary, no death-benefit step-up). PPLI is superior where partners are insurable.
- **Practical reality:** the partners' *own* high-frequency book and the *IDF* must be kept genuinely separate (investor-control). The PPLI typically holds a meaningful sleeve of capital, not necessarily 100% of the active book.

### Layer 4 — Charitable, estate & wealth transfer (the largest single-number lever, realized at death)

#### 4A — Annual gift exclusion (free, no structure, start immediately)
- Each partner can gift **$19,000/person/year** (2026 limit; $38,000/year with spouse gift-splitting) to any family member, with zero gift tax owed and no gift tax return required.
- Example: 4 kids per partner, both spouses giving = **$152,000–304,000/yr transferred silently per partner** with no planning lag.
- This requires no entities, no elections, no attorney action — write the checks and keep records. Start on day one.

#### 4B — 529 superfunding + SECURE 2.0 529→Roth rollover
- **5-year front-load:** contribute up to **$90,000/beneficiary** in a single year by electing to treat it as 5 years of annual exclusion gifts ($18K × 5 = $90K; $180K with spouse). No gift tax; no gift tax return required beyond the 709 election.
- **SECURE 2.0 529→Roth rollover:** after a 529 has been open for 15+ years, roll up to **$35,000 lifetime** into the beneficiary's Roth IRA (counts toward that year's Roth IRA contribution limit). Stacks on top of the kids' Roth IRA strategy — if education funds are unused, they do not go to waste.
- Start early; the 15-year holding period clock starts on account opening date, not contribution date.

#### 4C — Charitable vehicles
- **Charitable Remainder Trust (CRT):** contribute appreciated positions, receive a partial charitable deduction, defer/spread gain recognition, retain an income stream for a term of years.
- **Donor-Advised Fund (DAF)** for immediate large deductions with deferred grant decisions; **Private Foundation** for family philanthropy infrastructure.
- **Grantor CLAT:** large upfront charitable deduction against current ordinary income; remainder passes to family at low gift cost.

#### 4D — Advanced estate transfer (lock in $15M exemption — time-sensitive)
The OBBBA set the estate and gift tax exemption at **$15M/person** ($30M/couple). This level is not permanent and may revert to ~$7M in future legislation. **The window to lock in transfers at $15M is now.**

- **GRAT (Grantor Retained Annuity Trust):** transfer asset appreciation out of the estate at low/zero gift cost; remainder passes estate-tax-free. Best when hurdle rate (§7520 rate) is low and asset growth is high.
- **SLAT (Spousal Lifetime Access Trust):** irrevocable trust for spouse → removes assets from the grantor's estate while spouse can still benefit as a beneficiary. Locks in today's $15M exemption immediately. Structure two reciprocal SLATs with **different trustees, different assets, and time staggering** to avoid the reciprocal trust doctrine.
- **IDGT (Intentionally Defective Grantor Trust):** sell Trading LP interests to the trust in exchange for a promissory note at the §7520 rate. Future appreciation leaves the estate at the time of the sale; the grantor continues paying income tax on trust income (which is itself an additional tax-free gift to the trust). Superior to GRATs when asset growth is high/uncertain and no fixed term is needed.
- **Valuation discounts on LP/LLC interest gifts or sales:** when gifting or selling a minority interest in the Trading LP to a trust, a qualified appraiser establishes a **20–40% valuation discount** for lack of marketability and lack of control. A $15M gift exemption at a 35% discount effectively transfers **$23M of economic value** tax-free. Requires a timely qualified appraisal filed with the gift tax return.

#### 4E — Dynasty trust domicile: South Dakota (not Wyoming or Delaware)
For **dynasty trusts**, the domicile must be **South Dakota**, not WY/DE/NV:
- **No Rule Against Perpetuities** — South Dakota trusts run in perpetuity; Wyoming caps at 1,000 years.
- **Strongest spendthrift and asset protection provisions** in the US — creditor protection is near-absolute.
- **No state income tax on undistributed trust income** — zero SD state tax on accumulated trust earnings.
- **Quiet trust permitted** — beneficiaries need not be notified of the trust's existence.
- Requires a **South Dakota corporate trustee** (or co-trustee with a SD nexus); the family can retain investment direction authority as a non-fiduciary "trust protector" or investment advisor to the trust without triggering grantor trust status.
- Dynasty trust **owns the PPLI policies** — the death benefit passes outside the taxable estate and accumulates perpetually.

### Layer 5 — Supplemental offsets, credits & 2025-law upgrades (additive to Layers 1–4)

**Deduction generators (real economic substance required):**
- **Oil & gas working interests** — IDCs ~60–85% deductible year one; **§469(c)(3) working-interest exception** makes losses non-passive (offsets trading income directly); percentage depletion on production.
- **Real estate + cost seg + 100% bonus depreciation** (OBBBA made permanent, property acquired after 1/19/25). Traders can't realistically get REPS (trading hours swamp the personal-services test) — use the **STR exception** (avg stay ≤7 days + material participation) to make losses non-passive without REPS.
- **R&D credit (§41)** on proprietary algo/infra development — legitimately claimable by an HFT firm; OBBBA restored **immediate domestic R&D expensing** (no §174 amortization drag).
- **§6418 transferable energy credits** — buy at ~88–94¢/$; honest flag: passive-activity credit rules largely limit individuals to offsetting passive income → poor fit for partners directly; better inside a C-corp. Completeness item only.

**Character & timing (post-OBBBA updates):**
- **OZ 2.0** — OZs now **permanent**; rolling 5-yr deferral + 10% basis step-up (30% rural) for post-2026 investments; 10-yr tax-free appreciation retained. **With a 100% single-name §475 book, trading gains are ordinary → NOT OZ-eligible.** Only relevant if a §1256 index sleeve develops or for capital gains arising outside the trading book.
- **Municipal bond ladder** on idle treasury/margin cash — tax-exempt float.
- **Mega-backdoor Roth** in the S-corp 401(k) — after-tax contributions up to the §415 total limit (**$72K under 50 / $80K age 50+, 2026**), immediately converted to Roth; **~$48,500–$49,000 Roth space per partner per year** beyond the elective deferral. Grows and exits tax-free.
- **Roth conversions** in low-income years (drawdown, loss years, early retirement).
- **Custodial / kids' Roth IRAs** — employ minor children legitimately through Company B (real work, reasonable pay); pay up to the standard deduction (~$15K, zero income tax owed); the **parent can write the $7K check** into the custodial Roth on the child's behalf — the IRS doesn't care who funds it, only that the child has sufficient W-2 earned income to cover the contribution (limit = lesser of $7K or child's earned income). Zero W-2 = zero Roth, regardless of parent deposit. Requires genuine documented work and arm's-length compensation. 50–60 year tax-free compounding horizon.

**Income-shifting & charitable add-ons:**
- **Grantor CLAT** — large upfront charitable deduction vs. current ordinary income; remainder to family at low gift cost.
- **Gift LP interests** to trusts/adult family — shifts future K-1 income to lower brackets; multiplies estate exemption (**$15M/person from 2026**, OBBBA).
- **Family-office / Lender Mgmt structure** — mostly redundant given TTS, relevant only if a passive sleeve develops.

**Excluded by client constraint:** expatriation/renunciation, PR Act 60, **and USVI EDC** (same bona-fide-residency requirement).
**Additional listed-transaction traps to avoid:** syndicated conservation easements, Maltese pensions, monetized installment sales.

### Layer 6 — Asset protection (critical at this scale; frequently omitted)

At $50M+/yr income, the partnership becomes a target for creditor claims, judgments, and litigation. Asset protection must be built into the entity architecture from the start — retrofitting after a claim arises is too late.

**Wyoming LLC (entity-level protection for the Trading LP):**
- Wyoming has the strongest **charging order protection** in the US: a creditor who obtains a judgment against a partner can only receive a "charging order" (right to receive distributions if and when declared) — they cannot force a sale, liquidate the entity, or step into a partner's management rights. This makes a partner's interest in the LP nearly untouchable.
- Domiciling the Trading LP in Wyoming is therefore the correct choice; the entity operates federally but the protection comes from the state of formation.
- Nevada and South Dakota offer similar protections as backup alternatives.

**Domestic Asset Protection Trust (DAPT):**
- Available in Nevada, South Dakota, Delaware, and ~20 other states.
- A self-settled trust where the grantor is also a potential beneficiary — yet assets are protected from future creditors.
- **South Dakota DAPT** is the strongest: 2-year statute of limitations for fraudulent conveyance claims (vs. 4+ years elsewhere), full trust flexibility, self-settled explicitly permitted.
- **Must be established before any creditor claim arises** (fraudulent conveyance law voids transfers made to defeat known creditors). Establish on formation.
- Coordinate the DAPT with the dynasty trust; a combined SD DAPT/dynasty trust accomplishes asset protection, multigenerational wealth transfer, and estate tax mitigation in one instrument.

**Disability insurance — own-occupation (biggest overlooked risk):**
- The partners' most valuable income-producing asset is their ability to trade. Without it, K-1 income disappears. **No other element of this structure replaces operating income** — PPLI policy loans exist only if the PPLI has been funded over years.
- **Own-occupation disability insurance** (individual, not group): pays if the partner cannot perform the specific occupation (trading); cannot be canceled as long as premiums are paid; replaces income regardless of other earnings.
- **Business Overhead Expense (BOE) insurance**: covers the firm's fixed costs (data feeds, infrastructure, seat leases) during a partner's disability.
- Both are deductible through the S-corp when structured correctly.
- **Timing:** PPLI underwriting requires a medical exam. Schedule disability underwriting simultaneously — same medical workup, two policies, one appointment. Getting disability coverage before any health issue is detected is the single most time-sensitive non-tax action on this list.

### Explicitly NOT recommended (common traps at this profile)
- **C-corp "blocker" to defer at 21%** — for a trading entity this triggers **Personal Holding Company tax (§541)** and **Accumulated Earnings tax (§531)** on undistributed passive/trading income; double taxation on exit. Avoid as the trading vehicle.
- **Modeling a 20% QBI/§199A deduction** — not available for trading income.
- **Opportunity Zones** — driven by eligible *capital* gains; a full §475 ordinary election largely eliminates the qualifying gain. Only relevant for a non-475 / §1256 capital-gain sleeve.

---

## Compliance guardrails to build in from day one (the part that keeps it defensible)
- **Economic substance / business purpose** (§7701(o)) for every entity — real fees, real services, real separateness.
- **Investor-control doctrine** strictly observed for any PPLI/IDF — independent manager, no partner direction of insurance-dedicated trades.
- **Reasonable compensation** on the management-company S-corp.
- **§817(h) diversification** maintained inside the IDF.
- **Domicile hygiene:** confirm true domicile in the zero-tax state and **avoid creating nexus/sourcing** in a high-tax state by physically trading from there; domicile the entities in WY/DE/NV.
- **Contemporaneous documentation** of TTS qualification (trade logs, hours, frequency).
- **Pro-rata rule check before any backdoor Roth:** If any partner has existing traditional IRA balances with pre-tax contributions, the backdoor Roth conversion is taxed pro-rata across ALL IRA balances (the "cream in the coffee" rule). The CPA must identify and eliminate pre-tax IRA balances — roll them to the 401(k) plan or execute a strategic conversion in a loss year — before starting the annual backdoor Roth program. Zero tolerance for overlooking this.
- **PPLI lapse/loan management protocol:** Before the first policy loan is drawn, the IDF manager and insurance carrier must establish a written loan management policy: maximum loan-to-cash-value ratio (≤75–80%), annual review triggers, and paydown requirements. A lapse with loans outstanding produces a catastrophic single-year ordinary income event on all accrued gain. At $100M+/policy this is existential.

---

## Asset Location Strategy — What Goes Where

The structure creates multiple tax "buckets." Placing the right asset in the right bucket is as important as the structure itself. Attorney + CPA must review annually.

| Bucket | Best assets | Why |
|--------|-------------|-----|
| **PPLI / IDF** | HFT trading gains (highest-frequency, highest-rate) | 40.8% → 0% inside the policy; IDF runs the same strategy; compounds on the full dollar, not 59¢ |
| **Pre-tax 401(k) / cash-balance** | Stable return assets (bonds, structured notes, low-volatility) | Deduct at 40.8% now; withdraw in low-bracket years; no urgency to pay tax |
| **Roth / mega backdoor Roth** | Highest-return assets the brokerage can hold | Tax-free forever; no required minimum distributions; heirs inherit tax-free with no income tax |
| **Taxable (personal / trust)** | QSBS positions, muni bonds, appreciated long-term holds | QSBS: $10M/investment excluded after 5 yrs; munis: already tax-exempt; long-term holds get basis step-up at death |
| **South Dakota dynasty trust** | PPLI policies, LP interests, QSBS | Removes from taxable estate; perpetual compounding; PPLI death benefit is income-tax-free + estate-tax-free |

**Basis step-up hierarchy (critical for estate planning):**
- Taxable accounts: assets get a **step-up to fair market value at death** → heirs sell with zero capital gain. Hold appreciated long-term positions here.
- Traditional IRAs / 401(k)s: **NO step-up** — heirs pay ordinary income tax on every dollar withdrawn (income in respect of a decedent). Do not treat these as equivalent to taxable accounts for estate purposes.
- Roth IRAs: **no step-up needed** — already tax-free; heirs inherit and withdraw tax-free.
- PPLI death benefit (§101a): **income-tax-free entirely** — superior to the basis step-up because the full compounded cash value (decades of untaxed growth) transfers without any income tax event.
- **Implication:** Hold the most tax-efficient long-term positions in taxable for the basis step-up; hold HFT gains in PPLI; hold highest-return assets in Roth.

## Entity flow (simplified)

```
Trading LP/LLC (Form 1065)
│  └─ all trades, TTS, §475(f) election, zero employees
│
├─ K-1 (bulk of $50M) ──────────────────────────────────────────┐
│   NO W-2 required · NO SE tax · ordinary income               │
│                                                                │
└─ Management fee ──> [Partner A S-corp] [Partner B S-corp] ... │
                       W-2 ($150–400K)   W-2 ($150–400K)        │
                       + distributions   + distributions         │
                       + 401k/CB plan    + 401k/CB plan          │
                                                                 ▼
                                                   Partners receive K-1
                                                   → PPLI sleeve
                                                   → Dynasty trusts
                                                   → Retirement accounts
                                                   → Kids' Roth IRAs
```

---

## Open variables
**Resolved:**
- ✅ **Entity:** greenfield → clean formation, 75-day §475 window, WY/DE/NV domicile.
- ✅ **Asset class:** 100% single-name HFT options (securities, not §1256) → §475 mandatory, ordinary rates, PPLI + Layer 5 are the rate levers.
- ✅ **Employees:** Trading LP needs zero. W-2 only required inside each partner's management S-corp (reasonable comp $150–400K; K-1 from the LP has no W-2/SE requirement).
- ✅ **S-corp structure:** each partner can have their own S-corp for independent retirement/salary control, or share one.
- ✅ **Kids' Roth:** W-2 from S-corp employment unlocks it; parent can fund the $7K contribution; limit = lesser of $7K or child's earned income.
- ✅ **Capital source:** proprietary (own capital assumed).

**Still open:**
1. **§1256 portability** — can any sub-strategy move to SPX/XSP/NDX paper without alpha loss? Each 10% ≈ $510K/yr firmwide.
2. **Insurability** — PPLI vs. PPVA fallback. Drives Layer 3 sizing.
3. **Charitable intent** — genuine philanthropy or tax-only? Determines CRT/foundation scope.
4. **Partner count + ages** — drives cash-balance/DB plan sizing.

---

## Appendix — Vetting of the competing advisor memo (what to keep vs. drop)
| Memo item | Verdict | Reason |
|---|---|---|
| §475(f) MTM | ✅ Keep | Core; aligns with this plan. |
| §1256 60/40 | ✅ Keep | Core; the central lever for an options book. |
| **C-Corp shell / "blocker"** | ⚠️ Drop for trading vehicle | 21% is a mirage: **PHC tax §541 (+20%)** and **Accumulated Earnings Tax §531 (+20%)** on retained trading/passive income, plus double tax on exit. "Blocker" is the wrong concept for US-citizen owners (blockers stop UBTI/ECI flow-through to tax-exempt/foreign LPs, not rate-arbitrage for individuals). |
| **Offshore feeder funds** | 🚫 Drop | US persons taxed on worldwide income; **CFC/Subpart F + PFIC** deny offshore deferral to US owners. Feeders shelter foreign/tax-exempt LPs, not the partners. No legal benefit; scrutiny risk. |
| **Captive insurance (831(b))** | 🚫 Drop | **Listed transaction** (Notice 2016-66 + final regs), IRS "Dirty Dozen," repeated taxpayer losses (Avrahami, Reserve Mechanical, Syzygy). The memo's premium-deduction framing is the abusive pattern. |
| Cash-balance / DB plan | ✅ Keep | Via management S-corp; real but small vs. $50M. |
| **Opportunity Zones** | ⚠️ Situational + memo factually off | Needs **eligible capital gains** — §475 converts gains to ordinary, leaving nothing to roll. Memo's "defer up to 5 years" is wrong (fixed 12/31/2026 deferral date; 10%/15% step-ups expired; real benefit = tax-free appreciation after 10-yr hold). Only for a non-475 capital-gain sleeve. |
| **PPLI / IDF (omitted by memo)** | ➕ Add — centerpiece | The legitimate, mainstream tool the captive/offshore ideas only gesture at: tax-free inside buildup, tax-free policy loans, tax-free death benefit on high-churn ordinary income. |

---

## Implementation path (attorney + CPA + PPLI specialist execute; timeline matters)

**Immediate (before entity formation):**
- **Disability insurance:** Begin underwriting for own-occupation policies for each partner NOW — before PPLI underwriting, before any health events surface. Schedule medical exams to also serve PPLI underwriting. This is the most time-sensitive non-tax item.
- **Annual gift exclusion:** Begin $19K/person/yr gifts immediately — no entities required. No planning lag. Write the checks.

**Phase 1 — Entity formation (execute together, clock-sensitive):**
1. **Engage** trader-tax CPA + tax attorney + PPLI specialist / IDF manager.
2. **Form** Trading LP/LLC (**Wyoming** domicile for charging-order protection) + one S-corp per partner; draft partnership agreement with allocation provisions and management fee terms.
3. **File elections on the clock:**
   - §475(f) internal resolution within **75 days** of Trading LP formation (dated, signed, filed in entity records — no IRS filing needed at formation; existing entities face March 15 deadline)
   - S-corp elections (Form 2553) for each management S-corp
   - PTET elections where applicable
4. **Set reasonable W-2 salaries** in each management S-corp ($150–400K range); run payroll.

**Phase 2 — Retirement stack (before year-end):**
5. **Check existing traditional IRA balances** for each partner; eliminate pre-tax IRA balances (roll to 401(k) or strategic conversion) before initiating backdoor Roth. Pro-rata rule makes backdoor Roth partially taxable if pre-tax IRAs exist.
6. **Stand up** 401(k) + cash-balance/DB plans through each S-corp; execute mega-backdoor Roth conversions annually.
7. **Employ minor children** through S-corp if applicable; document duties, set arm's-length compensation, open custodial Roth IRAs.
8. **Open 529 plans** per beneficiary; superfund up to $90K/child ($180K with spouse) in year one. Starts 15-year Roth rollover clock.

**Phase 3 — Insurance wrapper (requires underwriting, takes 60–120 days):**
9. **Structure & underwrite** PPLI/IDF with an independent IDF manager (not the partners); fund the insurance sleeve. Establish written **PPLI loan management protocol** before taking any policy loans (max loan-to-cash-value ≤75–80%; annual review).

**Phase 4 — Estate & protection (attorney-led; do not defer):**
10. **Establish South Dakota dynasty trust(s)** with SD corporate trustee; trust owns PPLI policies (moves death benefit outside taxable estate).
11. **Execute SLAT and/or IDGT** to lock in $15M/person exemption — do not wait; exemption may sunset. Attorney coordinates valuation discounts on LP interest transfers and timely qualified appraisals.
12. **Establish South Dakota DAPT** for each partner before any creditor exposure materializes.
13. **Layer** charitable vehicles (CRT/DAF/CLAT) if philanthropically motivated.

**Ongoing (annual):**
14. **Document** TTS (trade logs, hours, frequency), management fees, and economic substance — contemporaneously, every year.
15. **§817(h) diversification testing, TTS substantiation, nexus/domicile confirmation** — attorney + CPA review annually.
16. **Asset location review** — confirm HFT gains routed to PPLI, stable assets in pre-tax, highest-return positions in Roth.

## Verification / testing (how you confirm it works)
- **Pre-mortem modeling:** have the CPA build a side-by-side effective-tax-rate model — *status quo* vs. *proposed* — across a representative trade mix, showing the marginal contribution of (a) 475/1256 split, (b) qualified plans, (c) PPLI inside buildup, (d) charitable.
- **Election proof:** retain dated §475 internal resolution and Form 2553 acceptance.
- **Doctrine stress-test:** independent counsel opinion on investor-control (PPLI), economic substance, and reasonable comp before funding.
- **Annual review:** §817(h) diversification testing, TTS substantiation, nexus/domicile confirmation.
