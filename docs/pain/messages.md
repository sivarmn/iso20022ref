---
sidebar_position: 1
title: pain messages
---

# Messages

Payment initiation messages

| Message  | Definition                          |
| -------- | ----------------------------------- |
| pain.001 | Customer Credit Transfer Initiation |
| pain.002 | Customer Payment Status Report      |
| pain.007 | Customer Payment Reversal           |
| pain.008 | Customer Direct Debit Initiation    |

:::info

pain messages are used in the customer to bank communication. These parties are free to use their own modalities for their business transactions.

Example - They could use internet banking and its own apis to request a funds transfer and need not use pain.001 format.

:::

## pain.001

The Customer Credit Transfer Initiation message is sent from the initiating party to the debtor agent.

## pain.002

Depending on the service level agreed between the debtor agent and the initiating party, the debtor agent may send a Customer Payment Status Report message to inform the initiating party of the status of the initiation.

## pain.007

:::note
Work in progress
:::

## pain.008

:::note
Work in progress
:::
