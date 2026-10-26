# Hi there, we're Tallyhouse 👋

<p align="center">
  <img src="https://raw.githubusercontent.com/Tallyhouse/syncta_web_frontend/main/public/syncta-icon.png" width="96" alt="Syncta Brandmark" />
</p>

<p align="center">
  <strong>Engineering Autonomous Financial Infrastructure for Rwanda & African Digital Economies.</strong>
</p>

<p align="center">
  <a href="https://github.com/Tallyhouse/syncta_backend"><img src="https://img.shields.io/badge/Backend-FastAPI%20%7C%20Python%203.12-blue?style=flat-square" alt="Backend" /></a>
  <a href="https://github.com/Tallyhouse/syncta_web_frontend"><img src="https://img.shields.io/badge/Frontend-Next.js%2014%20%7C%20TypeScript-black?style=flat-square" alt="Frontend" /></a>
  <a href="https://etax.rra.gov.rw"><img src="https://img.shields.io/badge/Tax%20Compliance-RRA%20Law%20Nº%20027%2F2022-green?style=flat-square" alt="Tax Compliance" /></a>
  <a href="https://bnr.rw"><img src="https://img.shields.io/badge/Forex%20Sync-National%20Bank%20of%20Rwanda-gold?style=flat-square" alt="BNR" /></a>
</p>

---

## 🙋‍♀️ Who We Are

**Tallyhouse** builds modern, non-custodial financial operating systems that automate accounting, banking proof-of-income credentials, and statutory tax compliance for African enterprises, remote contractors, and certified accountants.

Our flagship product, **Syncta Financial OS**, turns paper ledgers, multi-currency client invoices, and mobile money collections into verifiable double-entry accounting records aligned with Rwandan law and central banking standards.

---

## ⚡ The Syncta Ecosystem

| Repository | Description | Key Technologies |
| :--- | :--- | :--- |
| [**`syncta_backend`**](https://github.com/Tallyhouse/syncta_backend) | Async ledger engine, BNR forex normalization, ReportLab cryptographic PDF certs, and RRA e-Tax compilers. | FastAPI, Python 3.12, SQLAlchemy, PostgreSQL, ReportLab, Groq AI |
| [**`syncta_web_frontend`**](https://github.com/Tallyhouse/syncta_web_frontend) | Interactive dashboard, monthly VAT & EBM mismatch auditor, invoice generator, and MoMo checkout UI. | Next.js 14, TypeScript, Vanilla CSS, Paypack SDK |

---

## 🎯 What Syncta Solves

* **⚖️ RRA Monthly VAT & EBM Auditing**: Real-time calculation of Output VAT (18%), Article 43 Zero-Rated Service Exports (0%), and deductible Input VAT. Automated detection of missing buyer TINs and unverified EBM receipts before submission on `etax.rra.gov.rw`.
* **📑 RRA E-Tax Declaration Packs**: 1-click export of official e-Tax schedules (Boxes 101, 102, 201, 301, 401, and Annexure 3 Withholding Tax schedules).
* **🏦 Bank-Grade Proof-of-Income**: Cryptographically signed A4 PDF credentials and embassy letters with dynamic QR codes for loan underwriting and visa adjudication.
* **📱 Cashless MoMo Invoicing**: Instant client invoicing with embedded dynamic QR codes and direct MTN Mobile Money / Airtel Money USSD push settlement via Paypack.
* **👁️ Multimodal AI Receipt Scanning**: Instant extraction of dates, amounts, TINs, and tax categories from physical paper slips and EBM receipts via vision AI.

---

## 🛠️ Tech Stack & Architecture

* **Backend Engine**: Asynchronous Python 3.12 with FastAPI & SQLAlchemy ORM.
* **Accounting Core**: Append-only, double-entry journal architecture ensuring `sum(debits) == sum(credits)`.
* **Central Banking Exchange**: Daily interbank rate reconciliation synchronized with the **National Bank of Rwanda (BNR)**.
* **Design & Frontend**: Next.js 14 App Router, TypeScript, and high-performance Vanilla CSS tailored for sub-second page loads.
* **Testing & Integrity**: 100% passing test suites with `pytest` and strict type safety with `tsc --noEmit`.

---

## 🤝 Getting Involved & Contributing

We welcome contributions from engineers, tax accountants, and fintech enthusiasts across East Africa and beyond:
1. Explore our [Backend Documentation](https://github.com/Tallyhouse/syncta_backend#readme) and [Frontend Setup](https://github.com/Tallyhouse/syncta_web_frontend#readme).
2. Read our statutory tax modeling guidelines (Rwanda Tax Law Nº 027/2022 & Law Nº 012/2019).
3. Submit issues, feature ideas, or pull requests!

---

<p align="center">
  <sub>Built with precision in Kigali, Rwanda 🇷🇼 · © 2026 Tallyhouse</sub>
</p>
