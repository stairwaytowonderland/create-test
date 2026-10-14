[**create-test**](../README.md)

***

[create-test](../README.md) / ActionExec

# Interface: ActionExec

Defined in: [src/toolkit/action.ts:16](https://github.com/stairwaytowonderland/create-test/blob/c1679f89e1cbbe5ee37cf6458e1b3966de8b32a9/src/toolkit/action.ts#L16)

Represents the configuration for a GitHub Action that includes a `run` method.

## Properties

### run

> **run**: () => `Promise`\<`unknown`\>

Defined in: [src/toolkit/action.ts:22](https://github.com/stairwaytowonderland/create-test/blob/c1679f89e1cbbe5ee37cf6458e1b3966de8b32a9/src/toolkit/action.ts#L22)

Executes the main logic of the GitHub Action.

#### Returns

`Promise`\<`unknown`\>

A promise that resolves when the action has completed its run.
