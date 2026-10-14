[**create-test**](../README.md)

***

[create-test](../README.md) / getIssueFromContext

# Function: getIssueFromContext()

> **getIssueFromContext**(`context?`): \{\[`key`: `string`\]: `any`; `body?`: `string`; `html_url?`: `string`; `number`: `number`; \} \| `undefined`

Defined in: [src/toolkit/api.ts:116](https://github.com/stairwaytowonderland/create-test/blob/b46546d95d3642e39fc686d8eb17bf9f255add49/src/toolkit/api.ts#L116)

Get the issue object from the GitHub context payload.

## Parameters

### context?

[`GitHubContext`](../interfaces/GitHubContext.md) = `github.context`

The GitHub context object containing the payload for the current action.

## Returns

\{\[`key`: `string`\]: `any`; `body?`: `string`; `html_url?`: `string`; `number`: `number`; \} \| `undefined`

The issue object from the GitHub context payload, or undefined if not present.
