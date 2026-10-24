[**Toolkit**](../README.md)

***

[Toolkit](../README.md) / normalizeOptional

# Function: normalizeOptional()

> **normalizeOptional**(`value?`): `string` \| `undefined`

Defined in: [src/toolkit/utils.ts:14](https://github.com/stairwaytowonderland/create-test/blob/d4592b566e8eb5b8934094c52863cb3280562329/src/toolkit/utils.ts#L14)

Normalizes an optional string value.

Converts empty strings or undefined values to undefined.
This is useful for handling optional string values where empty strings should be treated as undefined.

## Parameters

### value?

`string`

The string value to normalize. If the value is an empty string or undefined, it will be converted to undefined.

## Returns

`string` \| `undefined`

The normalized string value or undefined.
