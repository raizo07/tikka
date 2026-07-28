[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / TxMemo

# Type Alias: TxMemo

> **TxMemo** = \{ `type`: `"text"`; `value`: `string`; \} \| \{ `type`: `"id"`; `value`: `string`; \} \| \{ `type`: `"hash"`; `value`: `Buffer`; \}

Defined in: [contract/lifecycle.ts:45](https://github.com/raizo07/tikka/blob/ecc00b1f098fb93cc62509c094951513b05fc8f9/sdk/src/contract/lifecycle.ts#L45)

Transaction memo — attach tracking data or external references.
Mirrors the three Stellar memo types the protocol supports.
