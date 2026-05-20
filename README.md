# Cash Collection & Reconciliation — Feature Map

An interactive feature map for Avanti Finance's **Cash Collection & Reconciliation (CCM)** module.

🔗 **[View Live →](https://aman-avanti.github.io/ccm-features/)**

---

## What This Is

A single-page visual overview of the end-to-end cash journey — from borrower to lender — across 8 stages. It maps every shipped feature and every PRD in the pipeline, with live development status for each.

Built to help product, engineering, and operations teams get a shared view of where we are and what's left to close.

---

## How to Use

- **Hover** over any box to reveal PRD details — priority, size, and current development status
- **Box colour** indicates status at a glance (see legend below)
- **Always-visible priority tags** on red boxes flag items needing immediate attention

---

## Status Legend

| Colour | Meaning |
|--------|---------|
| 🟢 Green | Launched / In Production |
| 🟩 Light Green | Launched — modification or improvement pending |
| 🟡 Yellow | In QA / In Development / In Eng Queue |
| 🔴 Red | Pending Eng Review / PRD in Progress / In Design |
| 🔵 Blue dashed | Prioritised / New |

### Priority Tags

| Badge | Priority |
|-------|----------|
| `P0` | Critical |
| `P1` | High |
| `P2` | Medium |
| `P3` | Low |

### Status Badges (visible on hover)

| Badge | Status |
|-------|--------|
| `PER` | Pending Eng Review |
| `IEQ` | In Eng Queue |
| `Dev` | In Development |
| `ID` | In Design / PRD in Progress |

---

## Coverage

| Journey Stage | Features Mapped |
|---|---|
| Cash: Borrower → Agent | QR Code, UPI, Wallet Splits, Core CCM, BBPS, Rectification, Actionable Collections View |
| Instant Customer Credit | Platform credit, Backdated repayment, Concurrent Txn Resolution |
| Cash: Agent → Branch (L1) | Visibility, Transactions, Interwallet rectification, Branch CM Dashboard |
| Cash: Branch → Partner (L2) | Cash Position Table, Transactions, Interwallet rectification, Partner CM Dashboard |
| Cash to Lender | To-lender txn, Lending Org Dashboard, Negative balance, Ecollect filters |
| Dispute Management | LOA reversal, Dispute flow, Transaction verification, Notifications |
| Lender Bank Recon | Bank statement reconciliation |
| Analytics & Performance | Operational Collections View, Branch User Balances |

---

## Tech

Plain HTML, CSS, and vanilla JS — no frameworks, no build step. Open `index.html` directly in any browser or serve via GitHub Pages.

---

*Maintained by the Avanti Finance Product team.*
