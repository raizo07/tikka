[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / withRetry

# Function: withRetry()

> **withRetry**\<`T`\>(`fn`, `opts?`): `Promise`\<`T`\>

Defined in: [utils/retry.ts:18](https://github.com/raizo07/tikka/blob/ecc00b1f098fb93cc62509c094951513b05fc8f9/sdk/src/utils/retry.ts#L18)

Executes an async function with exponential backoff and jitter.

Default options:
- maxAttempts: 3
- baseDelayMs: 500
- maxDelayMs: 8000
- retryOn: [503, 429, 'ECONNRESET']

## Type Parameters

### T

`T`

## Parameters

### fn

() => `Promise`\<`T`\>

### opts?

[`RetryOptions`](../interfaces/RetryOptions.md) = `{}`

## Returns

`Promise`\<`T`\>
