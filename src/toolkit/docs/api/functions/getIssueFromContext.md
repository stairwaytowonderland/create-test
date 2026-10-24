[**Toolkit**](../../README.md)

***

[Toolkit](../../README.md) / [api](../README.md) / getIssueFromContext

# Function: getIssueFromContext()

> **getIssueFromContext**(`context?`): \{\[`key`: `string`\]: `any`; `number`: `number`; `body?`: `string`; `html_url?`: `string`; \} \| `undefined`

Defined in: [src/toolkit/api.ts:116](https://github.com/stairwaytowonderland/create-test/blob/71b4398fc3059d98acaa5cf1a82ce20c1c5e2c0b/src/toolkit/api.ts#L116)

Get the issue object from the GitHub context payload.

## Parameters

### context?

[`GitHubContext`](../../action/interfaces/GitHubContext.md) = `github.context`

The GitHub context object containing the payload for the current action.

## Returns

\{\[`key`: `string`\]: `any`; `number`: `number`; `body?`: `string`; `html_url?`: `string`; \} \| `undefined`

The issue object from the GitHub context payload, or undefined if not present.
