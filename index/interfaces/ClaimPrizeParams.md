[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / ClaimPrizeParams

# Interface: ClaimPrizeParams

Defined in: [modules/ticket/ticket.types.ts:91](https://github.com/raizo07/tikka/blob/ecc00b1f098fb93cc62509c094951513b05fc8f9/sdk/src/modules/ticket/ticket.types.ts#L91)

Parameters for claiming a finalized raffle prize.

## Properties

### memo?

> `optional` **memo?**: [`TxMemo`](../type-aliases/TxMemo.md)

Defined in: [modules/ticket/ticket.types.ts:95](https://github.com/raizo07/tikka/blob/ecc00b1f098fb93cc62509c094951513b05fc8f9/sdk/src/modules/ticket/ticket.types.ts#L95)

Optional transaction memo for tracking or external integrations.

***

### raffleId

> **raffleId**: `number`

Defined in: [modules/ticket/ticket.types.ts:93](https://github.com/raizo07/tikka/blob/ecc00b1f098fb93cc62509c094951513b05fc8f9/sdk/src/modules/ticket/ticket.types.ts#L93)

Raffle ID (must be positive integer)
