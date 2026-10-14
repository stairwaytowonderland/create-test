[**create-test**](../README.md)

***

[create-test](../README.md) / ActionConfig

# Interface: ActionConfig

Defined in: [src/toolkit/action.ts:28](https://github.com/stairwaytowonderland/create-test/blob/b46546d95d3642e39fc686d8eb17bf9f255add49/src/toolkit/action.ts#L28)

Represents the base configuration for a GitHub Actions run.

## Properties

### context

> **context**: [`GitHubContext`](GitHubContext.md)

Defined in: [src/toolkit/action.ts:33](https://github.com/stairwaytowonderland/create-test/blob/b46546d95d3642e39fc686d8eb17bf9f255add49/src/toolkit/action.ts#L33)

The GitHub context object.

***

### dryRun

> **dryRun**: `boolean`

Defined in: [src/toolkit/action.ts:30](https://github.com/stairwaytowonderland/create-test/blob/b46546d95d3642e39fc686d8eb17bf9f255add49/src/toolkit/action.ts#L30)

Indicates if the action should run in dry-run mode.

***

### inputs?

> `optional` **inputs?**: `object`

Defined in: [src/toolkit/action.ts:39](https://github.com/stairwaytowonderland/create-test/blob/b46546d95d3642e39fc686d8eb17bf9f255add49/src/toolkit/action.ts#L39)

The action inputs provided to the GitHub Action.

#### Index Signature

\[`key`: `string`\]: `unknown`

The action input key-value pairs.

#### dryRun

> **dryRun**: `boolean`

Indicates if the action should run in dry-run mode.

***

### repo

> **repo**: [`SimpleRepository`](SimpleRepository.md)

Defined in: [src/toolkit/action.ts:36](https://github.com/stairwaytowonderland/create-test/blob/b46546d95d3642e39fc686d8eb17bf9f255add49/src/toolkit/action.ts#L36)

The repository associated with the GitHub Action.
