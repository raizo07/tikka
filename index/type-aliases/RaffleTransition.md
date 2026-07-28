[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / RaffleTransition

# Type Alias: RaffleTransition

> **RaffleTransition** = `"open→drawing"` \| `"drawing→finalized"` \| `"open→cancelled"`

Defined in: [modules/raffle/raffle.types.ts:105](https://github.com/raizo07/tikka/blob/ecc00b1f098fb93cc62509c094951513b05fc8f9/sdk/src/modules/raffle/raffle.types.ts#L105)

Valid state transitions in the raffle contract state machine:

 Open ──► Drawing  (trigger_draw)
 Drawing ──► Finalized (receive_randomness → internal finalization)
 Open ──► Cancelled (cancel_raffle)

Any other transition is rejected by the contract and surfaced as
`RaffleStateError`.
