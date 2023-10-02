---
sidebar_position: 1.1
title: Kitchen Sink
---

# Kitchen sink of messages

## Payments

### Credit Transfer

- As a customer, to initiate a transfer you may send **pain.001** to your bank
- Your bank will then send **pacs.008** to the creditor bank or intermediary bank
- It could also send **pacs.009 cover** message to the reimbursement/correspondent bank
- **pain.002** will be used by your bank to inform you(customer) the status of the payment instruction
- **pacs.002** will be used to instruct the instructing agent about
  - the status of the transaction or
  - to reject the transaction
- **pacs.004** will be used to return the transaction
- **camt.054** will be used to inform the account owner of the debit/credit on the account
- **camt.052** can be used independently to provide the account report to the account owner
- **camt.052** can be used independently to provide the periodical statement to the account owner
- **pacs.009 core** is used to send the payment from one bank to another(not customer initiated)
