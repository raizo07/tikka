[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / RefundTicketResult

# Interface: RefundTicketResult

Defined in: [modules/ticket/ticket.types.ts:79](https://github.com/raizo07/tikka/blob/ecc00b1f098fb93cc62509c094951513b05fc8f9/sdk/src/modules/ticket/ticket.types.ts#L79)

Result of a ticket refund.
Provides transaction confirmation.

## Properties

### feePaid

> **feePaid**: `string`

Defined in: [modules/ticket/ticket.types.ts:85](https://github.com/raizo07/tikka/blob/ecc00b1f098fb93cc62509c094951513b05fc8f9/sdk/src/modules/ticket/ticket.types.ts#L85)

Transaction fee paid in stroops

***

### ledger

> **ledger**: `number`

Defined in: [modules/ticket/ticket.types.ts:83](https://github.com/raizo07/tikka/blob/ecc00b1f098fb93cc62509c094951513b05fc8f9/sdk/src/modules/ticket/ticket.types.ts#L83)

Ledger number where transaction was confirmed

***

### transactionHash

> **transactionHash**: `string`

Defined in: [modules/ticket/ticket.types.ts:81](https://github.com/raizo07/tikka/blob/ecc00b1f098fb93cc62509c094951513b05fc8f9/sdk/src/modules/ticket/ticket.types.ts#L81)

Transaction hash for confirmation
