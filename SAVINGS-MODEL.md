# Estimated Tax Savings Model

> Illustrative only — not advice. Assumes: $50M/yr profit, 4 partners equal split ($12.5M each), top bracket, no-tax-state residents, current law (OBBBA-era), **100% options book**. CPA must rerun against actual trade mix (see Verification section of PLAN.md).

## Baseline — no structure

Short-term option gains as individuals: **37% + 3.8% NIIT = 40.8%**, near-zero expense deductibility.

| | Firm | Per partner |
|---|---|---|
| Profit | $50.0M | $12.50M |
| Tax @ 40.8% | **$20.4M** | **$5.10M** |

## Scenario A — Full §1256 routing (entire book in broad-based index options: SPX/NDX/RUT/XSP)

All profit at the 60/40 blended rate (~30.6%: 60% × 23.8% LTCG+NIIT + 40% × 40.8%).

| Lever (permanent, year one) | Firm/yr | Per partner/yr |
|---|---|---|
| §1256 routing — 10.2 pts × $50M | **~$5.1M** | **~$1.28M** |
| TTS business-expense deductions (~$2M real costs) | ~$0.8M | ~$200K |
| R&D credit (§41) on algo/infra dev | ~$0.4M | ~$100K |
| **Total permanent, year one** | **~$6.3M** | **~$1.58M** |

| Deferrals & compounding | Per partner/yr |
|---|---|
| 401(k) + cash-balance (~$350K contribution) | ~$143K deferred + tax-free growth |
| PPLI — years 1–2 (funding) | ~$200–500K |
| PPLI — year 5+ (~$25M inside @ ~15% return) | **~$1.1M+/yr and growing** |
| OZ 2.0 — all gains now capital → fully rollover-eligible | optional deferral + 10-yr tax-free appreciation |

| Effective rate trajectory | Rate | Per-partner saved vs baseline |
|---|---|---|
| Baseline | 40.8% | — |
| Year 1 structured | **~28%** | ~$1.58M permanent + ~$143K deferred |
| Year 5+ (PPLI scaled) | **low-to-mid 20s%** | **~$2.5–2.7M/yr** |

§1256-only bonus: **3-year loss carryback** (§1212(c)) — a loss year claws back prior years' tax.

## Scenario B — Mixed book (single-name edge can't all be routed)

Single-name sleeve keeps §475 protection (no wash sales, uncapped ordinary losses) but no rate benefit.

| §1256 share of P&L | Firm permanent/yr | Per partner/yr |
|---|---|---|
| 50% routed | ~$3.7M | ~$930K |
| 75% routed | ~$5.0M | ~$1.25M |
| 100% routed (Scenario A) | ~$6.3M | ~$1.58M |

## Sensitivities

- **Routing**: each 10% of P&L moved from equity-option paper (SPY/QQQ/single-name) to index paper (SPX/NDX/XSP) ≈ **+$510K/yr firmwide, permanent, zero structural cost**. The traders' question: *can the strategy be expressed in the §1256 instrument without losing edge?*
- **Partner count**: per-partner figures scale linearly (2 partners → 2×, 8 → ½×).
- **PPLI**: funding pace × strategy return drives the long-run number more than anything else.

See [PLAN.md](PLAN.md) for structure detail; [SUMMARY-CAVEMAN.md](SUMMARY-CAVEMAN.md) for the simple version.
