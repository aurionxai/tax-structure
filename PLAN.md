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

**Entity B — Management company: S-corp.**
- Charges the Trading LP an **administrative/management fee** → this *is* earned income, which creates the base to fund retirement plans and deduct health insurance.
- Reasonable-comp split (W-2 salary vs. distributions) managed for payroll efficiency.

### Layer 2 — Qualified deferral (good, but small relative to $50M)

Funded through Entity B's earned income:
- **Solo/employer 401(k)** per active partner.
- **Cash-balance / defined-benefit plan** layered on top — at these income levels can shelter **~$200K–$300K+ per partner per year** depending on age. Meaningful absolute dollars, but a rounding error against $50M — necessary, not sufficient.

### Layer 3 — The centerpiece: tax-free inside buildup via insurance wrapper

This is what actually moves the needle on a high-churn ordinary-income strategy:

- **Private Placement Life Insurance (PPLI)** wrapping an **Insurance-Dedicated Fund (IDF)** that runs the trading strategy.
  - Growth inside the policy compounds **tax-free**; policy **loans** are accessed tax-free; **death benefit** passes income-tax-free.
  - Converts the most tax-inefficient income (short-term trading gains) into tax-free buildup — the institutional answer to exactly this fact pattern.
  - **Hard requirements / guardrails:** partners must be **accredited investors / qualified purchasers**; **§817(h) diversification** rules; and the **investor-control doctrine** (the insured cannot direct the underlying trades — an independent IDF manager must run it). Insurability and underwriting required.
- **Private Placement Variable Annuity (PPVA)** as the alternative where insurability is poor — gives tax **deferral** (distributions are ordinary, no death-benefit step-up). PPLI is superior where partners are insurable.
- **Practical reality:** the partners' *own* high-frequency book and the *IDF* must be kept genuinely separate (investor-control). The PPLI typically holds a meaningful sleeve of capital, not necessarily 100% of the active book.

### Layer 4 — Charitable + estate (shelter that also transfers wealth)

- **Charitable Remainder Trust (CRT):** contribute appreciated positions, get a deduction, defer/spread gain, retain an income stream — useful for diversifying concentrated winners.
- **Donor-Advised Fund (DAF)** and/or **Private Foundation** for ongoing giving and current-year deduction smoothing.
- **Estate/wealth transfer:** at $50M/yr, dynasty/irrevocable trusts (ideally **owning the PPLI policies**, pushing death benefit *outside* the taxable estate), GRATs for transferring strategy upside at low gift cost.

### Layer 5 — Supplemental offsets, credits & 2025-law upgrades (additive to Layers 1–4)

**Deduction generators (real economic substance required):**
- **Oil & gas working interests** — IDCs ~60–85% deductible year one; **§469(c)(3) working-interest exception** makes losses non-passive (offsets trading income directly); percentage depletion on production.
- **Real estate + cost seg + 100% bonus depreciation** (OBBBA made permanent, property acquired after 1/19/25). Traders can't realistically get REPS (trading hours swamp the personal-services test) — use the **STR exception** (avg stay ≤7 days + material participation) to make losses non-passive without REPS.
- **R&D credit (§41)** on proprietary algo/infra development — legitimately claimable by an HFT firm; OBBBA restored **immediate domestic R&D expensing** (no §174 amortization drag).
- **§6418 transferable energy credits** — buy at ~88–94¢/$; honest flag: passive-activity credit rules largely limit individuals to offsetting passive income → poor fit for partners directly; better inside a C-corp. Completeness item only.

**Character & timing (post-OBBBA updates):**
- **OZ 2.0** — OZs now **permanent**; rolling 5-yr deferral + 10% basis step-up (30% rural) for post-2026 investments; 10-yr tax-free appreciation retained. **With a 100% single-name §475 book, trading gains are ordinary → NOT OZ-eligible.** Only relevant if a §1256 index sleeve develops or for capital gains arising outside the trading book.
- **Municipal bond ladder** on idle treasury/margin cash — tax-exempt float.
- **Mega-backdoor Roth** in the S-corp 401(k) — after-tax contributions up to the §415 total limit (~$70K/2026), immediately converted to Roth; ~$46K extra Roth space per partner per year beyond the elective deferral. Grows and exits tax-free. Small vs. $50M but free to execute.
- **Roth conversions** in low-income years (drawdown, loss years, early retirement).
- **Custodial / kids' Roth IRAs** — employ minor children legitimately through Company B (real work, reasonable pay); pay up to the standard deduction (~$15K, zero income tax owed); the **parent can write the $7K check** into the custodial Roth on the child's behalf — the IRS doesn't care who funds it, only that the child has sufficient W-2 earned income to cover the contribution (limit = lesser of $7K or child's earned income). Zero W-2 = zero Roth, regardless of parent deposit. Requires genuine documented work and arm's-length compensation. 50–60 year tax-free compounding horizon.

**Income-shifting & charitable add-ons:**
- **Grantor CLAT** — large upfront charitable deduction vs. current ordinary income; remainder to family at low gift cost.
- **Gift LP interests** to trusts/adult family — shifts future K-1 income to lower brackets; multiplies estate exemption (**$15M/person from 2026**, OBBBA).
- **Family-office / Lender Mgmt structure** — mostly redundant given TTS, relevant only if a passive sleeve develops.

**Excluded by client constraint:** expatriation/renunciation, PR Act 60, **and USVI EDC** (same bona-fide-residency requirement).
**Additional listed-transaction traps to avoid:** syndicated conservation easements, Maltese pensions, monetized installment sales.

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

---

## Open variables
**Resolved:**
- ✅ **Entity classification:** greenfield (nothing formed) → clean formation + 75-day §475 window.
- ✅ **Asset class:** **100% single-name (ticker) options, high-frequency** → securities book, §475(f) mandatory, ordinary rates on core P&L; PPLI + Layer 5 are the rate levers. §1256 routing only if a sub-strategy's edge ports to index paper without alpha loss.

**Still to confirm (to finalize):**
1. **Portability check** — can ANY sub-strategy express in broad-based index paper (SPX/XSP/NDX) without losing edge? Each 10% of P&L ported ≈ ~$510K/yr permanent savings firmwide.
2. **Own capital vs. outside money** — *Assumed proprietary (own capital).* If outside investors are involved, this becomes a **fund** (GP/LP, carried interest under §1061 3-year rule, RIA registration, fund admin) — a materially different build.
3. **Insurability** — are key partners insurable enough for **PPLI**, or is **PPVA** the fallback? Drives Layer 3.
4. **Charitable intent** — philanthropy genuinely desired, or is Layer 4 purely a tax tool? Determines CRT/foundation scope.
5. **Number of partners + ages** — drives cash-balance/DB plan sizing and special partnership allocations.

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

## "Implementation" / execution path (for the human professionals, not self-serve)
1. **Engage** a trader-tax CPA + tax attorney + (for Layer 3) a PPLI specialist / IDF manager.
2. **Form** Trading LP/LLC and Management S-corp; draft operating/partnership agreements with allocation provisions.
3. **File elections on the clock:** §475(f) (internal resolution within 75 days of new-entity formation), S-corp election (Form 2553) for the management company, PTET/entity domicile filings.
4. **Stand up** retirement plans (401(k) + cash-balance) through the management company.
5. **Structure & underwrite** PPLI/IDF (or PPVA) with an independent manager; fund the insurance sleeve.
6. **Layer** charitable/estate vehicles (CRT/DAF/foundation, dynasty trust owning policies).
7. **Document** TTS, fees, and economic substance contemporaneously.

## Verification / testing (how you confirm it works)
- **Pre-mortem modeling:** have the CPA build a side-by-side effective-tax-rate model — *status quo* vs. *proposed* — across a representative trade mix, showing the marginal contribution of (a) 475/1256 split, (b) qualified plans, (c) PPLI inside buildup, (d) charitable.
- **Election proof:** retain dated §475 internal resolution and Form 2553 acceptance.
- **Doctrine stress-test:** independent counsel opinion on investor-control (PPLI), economic substance, and reasonable comp before funding.
- **Annual review:** §817(h) diversification testing, TTS substantiation, nexus/domicile confirmation.
