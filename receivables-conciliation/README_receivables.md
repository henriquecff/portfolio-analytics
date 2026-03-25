# 💳 Receivables Conciliation

> Financial dashboard designed to reconcile receivables across multiple payment sources — POS, payment links, bank transfers and financial instruments.

👉 View project: https://seuusuario.github.io/receivables-conciliation/

---

## Context

Payment intermediaries must ensure that every processed transaction is properly reconciled across sales, settlements and pending balances.

Without a unified view, financial and operational teams rely on manual spreadsheets — leading to inefficiencies, lack of traceability and increased financial risk.

---

## Solution

This project provides an end-to-end conciliation layer, enabling:

- Consolidated visibility per client  
- Transaction-level traceability  
- Operational support for financial validation  
- Faster identification of inconsistencies  

---

## Dashboard Preview

![Receivables Conciliation Overview](assets/01-overview.png)

---

## Core Modules

**Client Extract (Core View)**  
- Consolidated financial view per client  
- Identification of pending vs settled balances  
- Breakdown by credit types (Transactional, Titles, Split)  
- Operational filtering by client status  

**Sales Transactions (Granular Layer)**  
- Drill-down to transaction and installment level  
- Gross vs net values  
- Payment method and document traceability  

**PIX Receipt Export**  
- Extraction of PIX receipts directly from the dashboard  
- Reduces dependency on external systems  
- Supports operational and customer service teams  

---

## KPIs
| Metric | Description |
|---|---|
| Settlements | Total amount settled within the period |
| Pending Balance | Amount not yet reconciled |
| Current Agenda | Receivables expected for the current day |
| Future Agenda | Scheduled receivables |

---

## Impact
- More than R$ 560M reconciled  
- Reduced manual conciliation workload  
- Increased operational efficiency and traceability  
- Faster response time for financial validation  

---

## Stack
- Power BI  
- SQL  
- DAX  

---

## Repository Structure
