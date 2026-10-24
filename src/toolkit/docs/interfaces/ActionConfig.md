[**Toolkit**](../README.md)

***

[Toolkit](../README.md) / ActionConfig

# Interface: ActionConfig

Defined in: [src/toolkit/action.ts:29](https://github.com/stairwaytowonderland/create-test/blob/d4592b566e8eb5b8934094c52863cb3280562329/src/toolkit/action.ts#L29)

Represents the base configuration for a GitHub Actions run.

## Properties

### dryRun

> **dryRun**: `boolean`

Defined in: [src/toolkit/action.ts:31](https://github.com/stairwaytowonderland/create-test/blob/d4592b566e8eb5b8934094c52863cb3280562329/src/toolkit/action.ts#L31)

Indicates if the action should run in dry-run mode.

***

### context

> **context**: [`GitHubContext`](GitHubContext.md)

Defined in: [src/toolkit/action.ts:34](https://github.com/stairwaytowonderland/create-test/blob/d4592b566e8eb5b8934094c52863cb3280562329/src/toolkit/action.ts#L34)

The GitHub context object.

***

### repo

> **repo**: [`SimpleRepository`](SimpleRepository.md)

Defined in: [src/toolkit/action.ts:37](https://github.com/stairwaytowonderland/create-test/blob/d4592b566e8eb5b8934094c52863cb3280562329/src/toolkit/action.ts#L37)

The repository associated with the GitHub Action.

***

### inputs?

> `optional` **inputs?**: `object`

Defined in: [src/toolkit/action.ts:40](https://github.com/stairwaytowonderland/create-test/blob/d4592b566e8eb5b8934094c52863cb3280562329/src/toolkit/action.ts#L40)

The action inputs provided to the GitHub Action.

#### Index Signature

\[`key`: `string`\]: `unknown`

The action input key-value pairs.

#### dryRun

> **dryRun**: `boolean`

Indicates if the action should run in dry-run mode.
