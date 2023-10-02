---
sidebar_position: 1
title: camt messages
---

# Messages

Payments clearing and settlement messages

| Message  | Definition                                 |
| -------- | ------------------------------------------ |
| camt.052 | Bank To Customer Account Report            |
| camt.053 | Bank To Customer Account Statement         |
| camt.054 | Bank To Customer Debit Credit Notification |
| camt.060 | Account Reporting Request                  |

## camt.052

This message is sent by the account servicer to an account owner or to a party authorised by the account owner to receive the message. It can be used to inform the account owner, or authorised party, of the entries reported to the account, and/or to provide the owner with balance information on the account at a given point in time.

## camt.053

This message is sent by the account servicer to an account owner or to a party authorised by the account owner to receive the message. It is used to inform the account owner, or authorised party, of the entries booked to the account, and to provide the owner with balance information on the account at a given point in time.

## camt.054

This message is sent by the account servicer to an account owner or to a party authorised by the account owner to receive the message. It can be used to inform the account owner, or authorised party, of single or multiple debit and/or credit entries reported to the account.

## camt.060

The AccountReportingRequest message is sent by the account owner, either directly or through a forwarding agent, to one of its account servicing institutions. It is used to ask the account servicing institution to send a report on the account owner's account in a Bank To Customer Account Report (camt.052), a Bank To Customer Statement (camt.053) or a Bank To Customer Debit Credit Notification (camt.054).
