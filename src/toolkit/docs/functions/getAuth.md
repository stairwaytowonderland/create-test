[**create-test**](../README.md)

***

[create-test](../README.md) / getAuth

# Function: getAuth()

> **getAuth**(`action`, `failOnError?`, `ghToken?`): `Promise`\<`Octokit` & `Api` & `object` \| `undefined`\>

Defined in: [src/toolkit/api.ts:77](https://github.com/stairwaytowonderland/create-test/blob/b46546d95d3642e39fc686d8eb17bf9f255add49/src/toolkit/api.ts#L77)

Retrieves an authenticated Octokit client using the provided GitHub token or the token from the action inputs.

If the environment is set to 'test', the function will skip live GitHub API authentication and return a mock Octokit client.

## Parameters

### action

[`ActionConfig`](../interfaces/ActionConfig.md)

The repository action containing repository and input details.

### failOnError?

`boolean` = `false`

Whether to throw an error if authentication fails. Defaults to false.

### ghToken?

`string`

Optional GitHub token to use for authentication. If not provided, it will be read from the action inputs.

## Returns

`Promise`\<`Octokit` & `Api` & `object` \| `undefined`\>

A promise that resolves to an authenticated Octokit client instance, or undefined if authentication fails.
