[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / parseSorobanContractErrorCode

# Function: parseSorobanContractErrorCode()

> **parseSorobanContractErrorCode**(`raw`): `number` \| `undefined`

Defined in: [utils/errors.ts:252](https://github.com/raizo07/tikka/blob/ecc00b1f098fb93cc62509c094951513b05fc8f9/sdk/src/utils/errors.ts#L252)

Extracts a numeric Soroban contract error code from a raw error string.
Recognizes the common formats surfaced by the Stellar RPC / SDK:
  - "Error(Contract, #35)"
  - "ScError::Contract(4)"
  - "contract error code 5"

## Parameters

### raw

`string` \| `null` \| `undefined`

## Returns

`number` \| `undefined`

the parsed code, or `undefined` if no recognizable pattern is found.
