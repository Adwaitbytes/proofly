# Proofly, Verify Once. Prove Everywhere.

**Agentic, privacy-first compliance infrastructure for cross-border finance.**

Proofly replaces repeated KYC paperwork with reusable cryptographic proof. A user
verifies their identity and financial credentials **once**, then an AI compliance
agent answers every institution's request with a **zero-knowledge proof**, proving
a single fact (KYC complete, accredited investor, sanctions clear, net worth above a
threshold) without ever revealing the underlying documents. The same agent then
monitors transactions continuously and pauses fraud or sanctions risk **before**
settlement.

Built for the **GIFT IFIH Young Builders' Program**, *Agentic AI in Financial Services*.

## The problem

Cross-border finance re-verifies facts that were already proven elsewhere. Every new
bank, fund, or payment provider demands the same documents, costs weeks of delay,
duplicates compliance spend, and scatters sensitive personal data across every
counterparty, against the data-minimisation principle of India's DPDP Act. Fraud and
sanctions breaches are usually caught only after money has moved.

## The solution

| | Today | With Proofly |
|---|---|---|
| Onboarding | Weeks, repeated at each institution | Minutes, verify once |
| Data shared | Raw documents, everywhere | Zero, only a true/false proof |
| Compliance | One-time, at onboarding | Continuous, agent-monitored |
| Risk | Caught after settlement | Paused before settlement |

## How it works

1. **Verify once**, identity and financials checked a single time; documents stay in a user-controlled vault.
2. **Seal into a passport**, credentials bound by a deterministic hash; unlinkable across institutions.
3. **Prove on demand**, the agent returns a zero-knowledge proof of the requested fact only.
4. **Monitor continuously**, every transaction scored in real time, risk paused with a verifiable audit trail.

**Tech enablers:** zero-knowledge proofs · AI compliance agent · cryptographic identity
binding · user-controlled credentials · real-time risk analysis · verifiable audit trail.

## Prototype

`index.html` is a self-contained interactive prototype (no build step, no dependencies).
Open it directly, or serve the folder with any static host.

The proof engine builds on [StellaRay](https://stellaray.fun), a live zero-knowledge
login layer with an eligibility-proof framework, and the compliance agent on Prophit,
an autonomous system with code-enforced risk guards and an auditable action log.

---

© 2026 Adwait Keshari · Prototype with sample data. No real documents are collected or stored.
