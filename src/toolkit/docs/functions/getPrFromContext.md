[**create-test**](../README.md)

***

[create-test](../README.md) / getPrFromContext

# Function: getPrFromContext()

> **getPrFromContext**(`context?`): \{\[`key`: `string`\]: `any`; `body?`: `string`; `html_url?`: `string`; `number`: `number`; \} \| `undefined`

Defined in: [src/toolkit/api.ts:124](https://github.com/stairwaytowonderland/create-test/blob/c1679f89e1cbbe5ee37cf6458e1b3966de8b32a9/src/toolkit/api.ts#L124)

Get the pull request object from the GitHub context payload.

## Parameters

### context?

[`GitHubContext`](../interfaces/GitHubContext.md) = `github.context`

The GitHub context object containing the payload for the current action.

## Returns

\{\[`key`: `string`\]: `any`; `body?`: `string`; `html_url?`: `string`; `number`: `number`; \} \| `undefined`

The pull request object from the GitHub context payload, or undefined if not present.
