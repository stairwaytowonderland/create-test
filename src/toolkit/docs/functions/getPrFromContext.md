[**Toolkit**](../README.md)

***

[Toolkit](../README.md) / getPrFromContext

# Function: getPrFromContext()

> **getPrFromContext**(`context?`): \{\[`key`: `string`\]: `any`; `number`: `number`; `html_url?`: `string`; `body?`: `string`; \} \| `undefined`

Defined in: [src/toolkit/api.ts:124](https://github.com/stairwaytowonderland/create-test/blob/d4592b566e8eb5b8934094c52863cb3280562329/src/toolkit/api.ts#L124)

Get the pull request object from the GitHub context payload.

## Parameters

### context?

[`GitHubContext`](../interfaces/GitHubContext.md) = `github.context`

The GitHub context object containing the payload for the current action.

## Returns

\{\[`key`: `string`\]: `any`; `number`: `number`; `html_url?`: `string`; `body?`: `string`; \} \| `undefined`

The pull request object from the GitHub context payload, or undefined if not present.
