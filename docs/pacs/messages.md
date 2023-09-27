---
sidebar_position: 1
---

# pacs messages

Payments clearing and settlement messages

| Message  | Definition                                                              |
| -------- | ----------------------------------------------------------------------- |
| pacs.008 | Financial Institution To Financial Institution Customer Credit Transfer |
| pacs.009 | Financial Institution Credit Transfer                                   |
| pacs.002 | Financial Institution To Financial Institution Payment Status Report    |
| pacs.004 | Payment Return                                                          |

## pacs.008

An Financial Institution To Financial Institution Customer Credit Transfer message is the inter-bank movement of an amount from a party bank account (the debtor account) to a beneficiary party (the creditor). Financial Institution To Financial Institution Customer Credit Transfer messages result in one or more cash transfers between debtors and creditors through correspondent banks or infrastructures. They may be exchanged as single or grouped instructions following certain common characteristics and, for convenience or efficiency reasons, exchanged in a batch mode. The processing of credit transfers may differ from country to country and system to system.

## pacs.009

A Financial Institution Credit Transfer message is the inter-bank movement of an amount from a party bank account (the debtor) to a beneficiary party (the creditor) where all parties are financial institutions. Financial Institution Credit Transfer messages result in cash transfers between debtors and creditors through correspondent banks or infrastructures. They may be exchanged as single instructions or grouped following certain common characteristics and, for convenience or efficiency reasons, exchanged in a batch mode. The processing of credit transfers may differ from country to country and system to system.

pacss.009 has two variants.

- Core - Used in FI to FI funds transfer
- Cover - Used as a cover message for pacs.008 settlement

## pacs.002

Status report of the payment instruction sent earlier. This could be positive status or negative status.

## pacs.004

The Payment Return message is sent by an instructed agent to the previous party in the payment chain when a payment cannot be executed due to an administrative reason (for example non existing/closed account) or banking reason (for example insufficient funds).
