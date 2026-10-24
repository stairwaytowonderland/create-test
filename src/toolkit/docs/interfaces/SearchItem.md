[**Toolkit**](../README.md)

***

[Toolkit](../README.md) / SearchItem

# Interface: SearchItem

Defined in: [src/toolkit/api.ts:134](https://github.com/stairwaytowonderland/create-test/blob/d4592b566e8eb5b8934094c52863cb3280562329/src/toolkit/api.ts#L134)

Represents a single search result item from the GitHub API.

## Properties

### node\_id

> **node\_id**: `string`

Defined in: [src/toolkit/api.ts:136](https://github.com/stairwaytowonderland/create-test/blob/d4592b566e8eb5b8934094c52863cb3280562329/src/toolkit/api.ts#L136)

The unique node ID of the search result item.

***

### number

> **number**: `number`

Defined in: [src/toolkit/api.ts:138](https://github.com/stairwaytowonderland/create-test/blob/d4592b566e8eb5b8934094c52863cb3280562329/src/toolkit/api.ts#L138)

The issue or pull request number.

***

### labels

> **labels**: `object`[]

Defined in: [src/toolkit/api.ts:140](https://github.com/stairwaytowonderland/create-test/blob/d4592b566e8eb5b8934094c52863cb3280562329/src/toolkit/api.ts#L140)

The labels associated with the issue or pull request.

#### name

> **name**: `string`

The name of the label.

***

### title

> **title**: `string`

Defined in: [src/toolkit/api.ts:145](https://github.com/stairwaytowonderland/create-test/blob/d4592b566e8eb5b8934094c52863cb3280562329/src/toolkit/api.ts#L145)

The title of the issue or pull request.

***

### html\_url

> **html\_url**: `string`

Defined in: [src/toolkit/api.ts:147](https://github.com/stairwaytowonderland/create-test/blob/d4592b566e8eb5b8934094c52863cb3280562329/src/toolkit/api.ts#L147)

The URL of the issue or pull request on GitHub.

***

### repository\_url

> **repository\_url**: `string`

Defined in: [src/toolkit/api.ts:149](https://github.com/stairwaytowonderland/create-test/blob/d4592b566e8eb5b8934094c52863cb3280562329/src/toolkit/api.ts#L149)

The URL of the repository containing the issue or pull request.

***

### created\_at

> **created\_at**: `Date`

Defined in: [src/toolkit/api.ts:151](https://github.com/stairwaytowonderland/create-test/blob/d4592b566e8eb5b8934094c52863cb3280562329/src/toolkit/api.ts#L151)

The date and time when the issue or pull request was created.
