[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / AssetDescriptor

# Interface: AssetDescriptor

Defined in: [modules/raffle/raffle.types.ts:8](https://github.com/raizo07/tikka/blob/ecc00b1f098fb93cc62509c094951513b05fc8f9/sdk/src/modules/raffle/raffle.types.ts#L8)

Structured asset descriptor for ticket pricing.
Use `{ code: 'XLM' }` for native lumens, or provide `issuer` for SEP-41 tokens.

## Properties

### code

> **code**: `string`

Defined in: [modules/raffle/raffle.types.ts:10](https://github.com/raizo07/tikka/blob/ecc00b1f098fb93cc62509c094951513b05fc8f9/sdk/src/modules/raffle/raffle.types.ts#L10)

Asset code, e.g. "XLM", "USDC", "yXLM"

***

### issuer?

> `optional` **issuer?**: `string`

Defined in: [modules/raffle/raffle.types.ts:12](https://github.com/raizo07/tikka/blob/ecc00b1f098fb93cc62509c094951513b05fc8f9/sdk/src/modules/raffle/raffle.types.ts#L12)

Issuer account for non-native assets. Omit for XLM.
