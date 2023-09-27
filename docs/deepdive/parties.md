---
sidebar_position: 2
---

# Parties

Parties involved in payments clearing and settlement.

## Debtor

Party that owes an amount of money to the (ultimate) creditor. The debtor is also the debit account owner and whose account is debited.

## Creditor

Party to which an amount of money is due. The party whose account is credited.

## Ultimate Debtor

This is used when the debtor is different from the party who is the ultimate source of the payment. This is normally used when a subsidiary uses the account of head office to settle the payment.

## Ultimate Creditor

This is used when the creditor is different from the ultimate beneficiary of the payment. This is normally used when a subsidiary uses the account of head office to receive the payment.

## Debtor Agent

The bank/financial instituition where debtor holds the account.

## Creditor Agent

The bank/financial instituition where creditor holds the account.

## Initiating party

Party that initiates the payment. This is the party that instantiates the payment data using say an ERP system.
Example: The party who initiates the pain.001

## Forwarding party

Financial institution that receives the instruction from the initiating party and forwards it to the next agent in the payment chain for execution. Forwarding agents are used at times where you have an integration with a bank(coordinator) but the actual debtor agent(or where you hold the account) is another bank.

## Instructing Agent

Agent that instructs the next party in the payment chain to carry out the payment/instruction.

## Instructed Agent

Agent that executes the instruction upon the request of the previous party in the chain (either an agreement party, or a clearing agent).

## Intermediary Agents

Agent between the debtor's agent and the creditor's agent. There can be several intermediary agents specified for the execution of a payment.

## Reimbursing Agents

Reimbursement agents are used to refer to parties in the cover message. The reimbursement agents in pacs.008 will refer to the parties used in the pacs.009 cover messages.

## Previous Instructing Agents

Previous instructing agents in the payment chain.

## Other Roles

Some parties are referred by other names such as

### Account Owner

Party that legally owns the account.

### Account Servicer

Party that manages the account on behalf of the account owner, that manages the registration and booking of entries on the account, calculates balances on the account and provides information about the account.
