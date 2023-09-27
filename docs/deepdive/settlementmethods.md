---
sidebar_position: 3
---

# Settlement Methods

Methods used to settle the credit transfer instruction.

| Code | Name              | Definition                                                             |
| ---- | ----------------- | ---------------------------------------------------------------------- |
| INDA | Instructed Agent  | Settlement is done by the agent instructed to execute the payment      |
| INGA | Instructing Agent | Settlement is done by the agent instructing and forwarding the payment |
| COVE | Cover Method      | Settlement is done through a cover payment                             |
| CLRG | Clearing System   | Settlement is done through a payment clearing system                   |

## INDA

Instructed Agent will complete the settlement. The message is sent by the account owner and received by the account servicer.
The account owner will instruct the account servicer to debit the vostro/current account in its books once the message is received before sending the payment further. Payment can be returned or rejected.

## INGA

Instructing Agent will complete the settlement. The message is sent by the account servicer and received by the account owner.
The account servicer will credit the vostro/current account in its books before sending tha payment futher. Payment can only be returned.

## COVE

Settlement is dont through a cover payment. pacs.008 will be settled through a pacs.009 cover payment.

## CLRG

Settlement is dont through a payment clearing system/market infrastructure
