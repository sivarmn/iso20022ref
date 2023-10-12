---
sidebar_position: 4
---

# Code Sets

Code sets are list of values used to restrict allowed values in a field.

## Internal

Internal codes are values that are specific and limited and are present within the message definition.

Examples: Settlement method, Settlement Priority

## External

The purpose and value of externalizing a code set is to allow for a more frequent update of the code set by for example adding new codes in the set without impacting the version of the messages and the development cycle of the messages.

Examples: Payment status, Transaction purpose, Rejected reason

[External Code Sets](https://www.iso20022.org/catalogue-messages/additional-content-messages/external-code-sets)

## Transaction Codes

The structure of the Bank Transaction Code component includes the following 3 levels:

![Transaction Codes Definition](./img/transaction-codes.png)

The transaction codes in the statements are external and should follow the transaction code sets and combinations.

### Examples

| Domain   | Domain Code | Family                          | Family Code | Sub Family | Sub Family Code |
| -------- | ----------- | ------------------------------- | ----------- | ---------- | --------------- |
| Payments | PMNT        | Received Credit Transfers       | RCDT        | Other      | OTHR            |
| Payments | PMNT        | Received Direct Debits          | RDDT        | Other      | OTHR            |
| Payments | PMNT        | Miscellaneous Credit Operations | MCOP        | Fees       | FEES            |
| Payments | PMNT        | Miscellaneous Credit Operations | MCOP        | Commission | COMM            |

[Complete Transaction Codes](https://www.iso20022.org/catalogue-messages/additional-content-messages/external-code-sets)
