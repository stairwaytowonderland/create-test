[**Toolkit**](../../README.md)

***

[Toolkit](../../README.md) / [action](../README.md) / SimpleRepository

# Interface: SimpleRepository

Defined in: [src/toolkit/action.ts:101](https://github.com/stairwaytowonderland/create-test/blob/71b4398fc3059d98acaa5cf1a82ce20c1c5e2c0b/src/toolkit/action.ts#L101)

Represents basic information about a GitHub repository.

Extends the Partial type to allow optional repository properties.

## See

 - https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype
 - https://www.typescriptlang.org/docs/handbook/release-notes/typescript-2-1.html#mapped-types

## Extends

- `Partial`\<[`GitHubContext`](GitHubContext.md)\[`"repo"`\]\>

## Properties

### fullName?

> `optional` **fullName?**: `string`

Defined in: [src/toolkit/action.ts:103](https://github.com/stairwaytowonderland/create-test/blob/71b4398fc3059d98acaa5cf1a82ce20c1c5e2c0b/src/toolkit/action.ts#L103)

The full repository name in the format "owner/repo".

***

### owner?

> `optional` **owner?**: `string`

Defined in: node\_modules/@actions/github/lib/context.d.ts:30

#### Inherited from

`Partial.owner`

***

### repo?

> `optional` **repo?**: `string`

Defined in: node\_modules/@actions/github/lib/context.d.ts:31

#### Inherited from

`Partial.repo`
