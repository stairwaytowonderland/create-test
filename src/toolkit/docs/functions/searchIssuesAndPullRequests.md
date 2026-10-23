[**create-test**](../README.md)

***

[create-test](../README.md) / searchIssuesAndPullRequests

# Function: searchIssuesAndPullRequests()

> **searchIssuesAndPullRequests**(`query`, `octokit`): `Promise`\<[`SearchItem`](../interfaces/SearchItem.md)[]\>

Defined in: [src/toolkit/api.ts:164](https://github.com/stairwaytowonderland/create-test/blob/418e563f4cc7e2c1fc2e1d1e5032474be00a6a48/src/toolkit/api.ts#L164)

Searches for issues and pull requests based on the provided query using the GitHub REST API.
Returns a list of search result items matching the query.

## Parameters

### query

`string`

The search query string used to find issues and pull requests.

### octokit

`Octokit` & `Api` & `object`

The Octokit client instance used to interact with the GitHub REST API.

## Returns

`Promise`\<[`SearchItem`](../interfaces/SearchItem.md)[]\>

A promise that resolves to an array of search result items matching the query.

## See

https://docs.github.com/en/rest/search/search?apiVersion=2026-03-10#search-issues-and-pull-requests
