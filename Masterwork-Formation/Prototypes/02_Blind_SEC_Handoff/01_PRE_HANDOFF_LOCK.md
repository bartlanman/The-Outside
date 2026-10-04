# Prototype 02 — Blind SEC Documentary Handoff
## Pre-Handoff Lock

**Lock status:** BEFORE FILING-BODY REVEAL  
**Date locked:** 2026-10-04

## Purpose

Run the Irreducible Handoff against an independently custodied, low-risk public documentary source whose index is visible before the underlying filing body is opened.

External custodian:
U.S. Securities and Exchange Commission EDGAR.

## Source selected

Trimble Inc.
Form 8-K
Filed: October 2, 2026
SEC accession: 0000864749-26-000111.

Known before reveal from the SEC filing index only:

- Item 1.01 — Entry into a Material Definitive Agreement;
- Item 2.03 — Creation of a Direct Financial Obligation or Off-Balance Sheet Obligation;
- Item 9.01 — Financial Statements and Exhibits;
- Exhibit 10.1 filename indicates a term loan credit agreement;
- filer: Trimble Inc.

The main 8-K filing body has **not** been opened before this lock.

## MODEL — pre-contact representation

From the index alone, the model predicts:

### High confidence
1. Trimble entered into a new term-loan or credit facility.
2. The new agreement created a material borrowing obligation.
3. The 8-K will identify the lenders / administrative agent and the effective or closing date.
4. The filing will state principal amount or borrowing capacity.
5. The filing will describe maturity and interest-rate mechanics.
6. Exhibit 10.1 will contain substantially fuller contractual detail than the 8-K summary.

### Medium confidence
7. Proceeds may refinance or replace existing debt, support a corporate transaction, or provide general corporate liquidity.
8. The agreement likely contains customary covenants, representations, events of default, and prepayment provisions.
9. The facility may be secured or guaranteed by subsidiaries, though the index alone does not establish this.
10. The filing may identify an acquisition, refinancing, or balance-sheet event that explains why the financing was entered into now.

### Low confidence / speculative
11. The term loan may be several hundred million dollars or more given Trimble's scale, but the index supplies no amount.
12. The maturity may be roughly three to five years.
13. Pricing may use SOFR plus a margin tied to ratings or leverage.

## MODEL compression

MATERIAL AGREEMENT
-> TERM LOAN
-> NEW DEBT OBLIGATION
-> FINANCING PURPOSE
-> CONTRACTUAL TERMS / COVENANTS.

## What would materially change the model?

The filing would materially change the representation if:

- the agreement is not primarily new-money borrowing;
- the loan is substantially smaller or larger than expected;
- the purpose is a specific transaction not inferable from the index;
- the facility has an unusual structure;
- the debt replaces, amends, or restructures something in a way the index obscures;
- unusual guarantees, collateral, covenants, or repayment mechanics matter;
- the main economic significance is not the borrowing itself.

## Handoff rule

After this file is committed:

1. open the main 8-K body;
2. read only what the independently filed document states;
3. compare the source against each prediction;
4. preserve:
   - CONFIRMED;
   - PARTIALLY CONFIRMED;
   - CONTRADICTED;
   - NOT ADDRESSED;
5. identify what the index-model could not see;
6. preserve this pre-handoff file unchanged;
7. deposit a separate return document.

## Prototype success

Success does not require the model to be wrong.

Success requires the independently filed source to change the warranted account in some consequential way beyond what the index-model alone supports.
