---
sidebar_position: 2
---

# Settlement - Correspondents

Payment settlement where debtor and creditor agents are correspondents

## Payment Details

- DEF electronics had raised an invoice for 10 million USD needs to be paid to DEF Electronics account 23683707994214 with AAAA Bank, London (AAAAGB2L).
- ABC Corporation assigns reference ABC/4563/2023 to the payment.
- Payment transaction charges are shared between ABC Corporation and DEF Electronics.
- ABC Corporation, New York, holds an account 00125574998 with BBBB Bank, New York
- AAAA Bank, London holds a USD account with BBBB Bank, New York and are correspondents.

## Message Details

- On receipt of invoice, pain.001 will be sent by ABC Corporation, New York to its bank BBBB Bank, New York.
- BBBB Bank, New York debits the DEF Electronics account 00125574998 and credits the AAAA Bank, London account in its books.
- BBBB Bank, New York sends pacs.008 to AAAA Bank, London with settlement method as INGA.
- INGA settlement method is used because BBBB Bank, New York is the account servicer and AAAA Bank, London is the account owner.
- AAAA Bank, London debits its Nostro account and credits the DEF electronics account 23683707994214.
- SMS or Email notification could be sent by AAAA Bank, London to DEF Electronics based on their internal agreement.

![Message Flow](./img/settlement-correspondents.png)
