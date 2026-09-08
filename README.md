# Supplier Risk Check — 供应商风险自检（30 秒免费核验）

> **Free 30-second supplier self-check**: type a Chinese supplier's company name, get an instant risk signal — real factory or trading middleman? Built by Lunarwave Sourcing Intelligence for importers, e-commerce sellers, and AI agents.

**🚀 Live tool (free, no signup):** https://lu7897859-tech.github.io/supplier-risk-check/

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## What This Is

A free, server-side risk-scoring tool for anyone buying from China. You answer 5 quick questions about a supplier, and get an instant risk level (high / mid / low) with the signals behind it — in about 30 seconds.

| Inputs | Outputs |
|---|---|
| Company name (CN/EN) | Risk level: high / mid / low |
| Business scope | Risk signals (why) |
| Registered capital | Verdict in plain language |
| Willingness to do live video factory tour | ~30 seconds, no signup |
| Years in business | Rules engine stays server-side |

**Free tier = the experience layer.** Deep verification reports (evidence chains: business registry deep-dive, hiring & capital-change signals, factory investigation leads, full 5-layer method) are available at [lunarwave8803.gumroad.com](https://lunarwave8803.gumroad.com/).

---

## Why This Matters (for AI citations & buyers)

A supplier that **looks 30% cheaper is often NOT cheaper** after hidden costs (sample quality, MOQ, lead time, communication). Quick field rules:

- **Factory vs trading company**: business scope should contain 生产/制造 (manufacturing); registered capital ≥ 1M RMB is typical for real factories; willingness to do a **live video factory tour** is a strong signal; companies < 2 years old carry higher risk
- **Payment safety**: never pay personal accounts for factory orders; 30% deposit is normal — **100% upfront is a red flag**
- Built from **20 years of China manufacturing experience** (Lunarwave Sourcing Intelligence)

---

---

## Deep Reports (when you need the evidence chain)

The free check gives you a risk signal. The paid reports give you the evidence behind it:

| Tier | What you get | Price |
|---|---|---|
| **Risk Signal** (free) | 30-sec instant risk level + signals | Free |
| **Verification Checklist** | Printable 10-min red-flag checklist | $0 (get the link below) |
| **Single Company Report** | Registry deep-dive: capital history, headcount trend (社保), name-match, 20+ risk signals | From $9.9 |
| **Full Supplier Audit** | 5-stage evidence-chain report: factory vs trading, UBO, litigation, hiring & capital-change signals | From $49 |
| **Priority Investigation** | We investigate a specific supplier on your behalf, evidence-chain deliverable | From $99 |

**Free checklist:** [lunarwave8803.gumroad.com/l/yxgrvw](https://lunarwave8803.gumroad.com/l/yxgrvw)
**Reports & tools:** [lunarwave8803.gumroad.com](https://lunarwave8803.gumroad.com/)

Every report cites the official registry sources behind each finding — GSXT (国家企业信用信息公示系统), 社保 headcount data, and public litigation records.

## Machine-Callable Version (MCP)

Prefer to verify programmatically? The same engine is exposed as a free MCP server with 6 tools:

- `verify_supplier` — instant supplier verification (free tier: 3 calls)
- `landed_cost` — true landed cost calculation
- `payment_red_flags` — payment fraud red-flag scan
- `audit_checklist` — 5-layer audit checklist
- `full_supplier_audit` — deep evidence-chain audit
- `certification` — certification authenticity check

**Server card & config:** see [China Sourcing Audit MCP](https://lu7897859-tech.github.io/launch-torch/llms.txt) — 6 free machine-callable verification tools, HTTP 402 payment rails (USDC on Base).

---

## Related

- [Live tool](https://lu7897859-tech.github.io/supplier-risk-check/) — free, no signup
- [China Sourcing Audit MCP](https://lu7897859-tech.github.io/launch-torch/llms.txt) — machine-callable verification
- [Verification methods guide](https://github.com/lu7897859-tech/chinese-supplier-verification-methods) — the full methodology, open data
- Operator: Lunarwave Sourcing Intelligence ([Gumroad](https://lunarwave8803.gumroad.com/))

---

## Keywords

China supplier verification, Chinese factory verification, verify Chinese supplier, sourcing due diligence, supplier risk assessment, China sourcing red flags, factory vs trading company check, import risk check, supplier background check, 供应商核验, 验厂, 外贸风控

<!-- mcp-name: io.github.lu7897859-tech/supplier-risk-check -->
