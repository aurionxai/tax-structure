# Estimated Tax Savings Model

> Illustrative only — not advice. Assumes: $50M/yr profit, 4 partners equal split ($12.5M each), top bracket, no-tax-state residents, current law (OBBBA-era), **100% single-name (ticker) options, high-frequency**. CPA must rerun against actual trade mix (see Verification section of PLAN.md).

## Key fact driving everything

**Ticker-symbol options are *securities*, not §1256 contracts.** No 60/40 rate. The core book is ordinary-rate (**37% + 3.8% NIIT = 40.8%**), and no legal structure changes that character. The plan's value is therefore: (1) §475 protection, (2) deduct everything real, (3) shield the compounding via PPLI, (4) offset with substance-based deductions.

## Baseline — no structure

| | Firm | Per partner |
|---|---|---|
| Profit | $50.0M | $12.50M |
| Tax @ 40.8% | **$20.4M** | **$5.10M** |

Plus an unpriced hazard: without §475, HFT in overlapping strikes/expiries triggers **wash-sale deferrals → phantom taxable income** that can exceed economic profit. The 475 election (Layer 1) eliminates this entirely — large-dollar protection, though not a rate cut.

## Structured — savings by bucket

**Permanent, year one:**

| Lever | Firm/yr | Per partner/yr |
|---|---|---|
| TTS business-expense deductions (~$2M real costs: data, infra, comp) | ~$0.8M | ~$200K |
| R&D credit (§41) — strong fit for HFT algo/infra dev + immediate §174A expensing | ~$0.4–0.6M | ~$100–150K |
| **Subtotal** | **~$1.2–1.4M** | **~$300–350K** |

**Deferrals:**

| Lever | Per partner/yr |
|---|---|
| 401(k) + cash-balance (~$350K contribution) | ~$143K deferred + tax-free growth |

**The compounding engine — PPLI (now THE rate lever):**

Growth shielded at the full 40.8% ordinary rate. Illustrative: ~$25M inside per partner @ ~15% return:

| Stage | Per partner/yr saved |
|---|---|
| Years 1–2 (funding) | ~$200–500K |
| Year 5+ steady state | **~$1.5M/yr and growing** |

**Optional substance-based offsets (Layer 5 — promoted in this scenario):**

| Lever | Value |
|---|---|
| Oil & gas working interests ($5M/yr firm placement) | ~$1.6M yr-1 deduction value (~$410K/partner) — real investment risk |
| Real estate + cost seg + STR exception | scales with placement |
| Grantor CLAT (if philanthropic) | large upfront ordinary-income deduction |

**Dead in this scenario:** §1256 60/40 on the core book; OZ rollovers (§475 gains are ordinary, not capital).

**Upside option:** if any sub-strategy ports to broad-based index paper (SPX/XSP/NDX) without losing edge, each 10% of P&L moved ≈ **+$510K/yr firmwide, permanent**. Never trade alpha for tax.

## Effective rate trajectory (4 partners)

| | Rate | Per-partner saved vs baseline |
|---|---|---|
| Baseline | 40.8% | — |
| Year 1 structured | **~38%** | ~$300–350K permanent + ~$143K deferred + wash-sale hazard eliminated |
| Year 5+ (PPLI scaled) | **~29–31%** | **~$1.8–2.0M/yr** |
| Year 5+ with deduction-generator program | **~26–28%** | **~$2.2–2.5M/yr** |

## Sensitivities

- **Partner count**: per-partner figures scale linearly (2 partners → 2×, 8 → ½×).
- **PPLI funding pace × strategy return** drives the long-run number more than anything else.
- **Index-paper portability**: the only remaining rate lever on the trading P&L itself.

See [PLAN.md](PLAN.md) for structure detail; [SUMMARY-CAVEMAN.md](SUMMARY-CAVEMAN.md) for the simple version.
