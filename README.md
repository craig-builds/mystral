# Mystral

**Accounting software for business owners, bookkeepers and accountants — in development.**

Mystral is an accounting application being designed to bring a business's everyday finance work into one coherent place: invoicing, bills and expenses, bank reconciliation, the general ledger and financial reports, with tools for the accountants and bookkeepers who look after several businesses.

> **Project status: early development.** Mystral is not released and there is nothing to download yet. Everything on this page describes what the project intends to build.

## The problem

Keeping a small or medium-sized business's books usually means stitching several things together: an invoicing tool, a spreadsheet of expenses, bank statements downloaded as files, a folder of receipts, and messages back and forth with an accountant. Records are captured twice, month-end depends on chasing documents, and it is hard for an owner to see where the business stands on a given day.

Accountants and bookkeepers feel the same friction multiplied across every client: different files, different habits, and little shared view of what has been processed, reviewed or is still missing.

## What Mystral is intended to do

Planned capabilities, all under design or development:

- **A dependable double-entry ledger** at the centre, so that every invoice, bill, payment and adjustment produces balanced, traceable accounting entries.
- **Sales and receivables:** customers, quotes, invoices, credit notes, payment allocation and debtor ageing.
- **Purchases and payables:** suppliers, bills, expenses, receipts and creditor ageing.
- **Banking:** statement import, transaction matching and bank reconciliation, with file import treated as a first-class path.
- **Reporting:** profit and loss, balance sheet, trial balance, general ledger and aged reports that trace back to the underlying transactions.
- **Tax configuration** designed first for South African VAT, with country-specific rules kept separate so that other markets can follow.
- **Practice workflows:** a way for accounting and bookkeeping professionals to work across the organisations they are authorised to manage.
- **Assistive automation:** document extraction and suggestions that help with capture and matching. Suggestions are always reviewed by a person; automation does not post accounting entries on its own.

## Who it is for

- **Business owners** who want to invoice, record expenses and understand their position without specialist help for routine work.
- **Bookkeepers** who process transactions and reconcile accounts and need efficient, reliable tools.
- **Accountants and accounting practices** who review, adjust and report across multiple client businesses.

The first market in view is South Africa.

## Vision

One application in which the important accounting and business-finance workflows fit together: records captured once, a ledger that can be trusted, and a clear trail from every report total back to the transaction and the document behind it.

## Where Mystral hopes to fit

Accounting software for smaller businesses is a well-established market, served by capable products such as Xero, Sage and QuickBooks. Mystral does not claim to match them today.

The project's aim is to offer a credible alternative over time, and it hopes to differentiate itself through:

- a South Africa-first design, with local requirements considered from the start;
- accounting integrity as the foundation — exact arithmetic, balanced entries, and corrections that preserve history;
- workflows that serve both the business and its accountant;
- automation that assists without taking control away from the people responsible for the books.

These are intentions for a product under development, not statements of achieved capability or market success.

## Status and roadmap

| Area | State |
|---|---|
| Requirements and data model | In progress |
| Application development | In progress — an internal Windows desktop build is in testing with demonstration data only |
| Public release | Not scheduled |

**Progress update (November 2026).** The internal build currently covers sign-in, demonstration organisations, the chart of accounts, accounting periods and locks, journals, trial balance, profit and loss, balance sheet and general ledger, customers and suppliers, invoices and bills (not yet VAT invoices), receipts and payments with allocation, debtor and creditor ageing, an audit trail and encrypted local backups. Work on banking has started with reading bank statement files (CSV and OFX), with exact amounts and duplicate detection that also catches repeated lines within a single file. Statement matching and bank reconciliation come next. None of this is released, and it has not yet been reviewed by accounting, tax or security professionals.

This repository will hold public documentation and selected application source code as development proceeds.

## Licence

No licence has been granted. All rights reserved unless and until a licence file is added to this repository.

## Contact

Contact details will be added when the project is ready for outside enquiries.
