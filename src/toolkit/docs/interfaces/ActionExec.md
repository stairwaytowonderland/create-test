[**create-test**](../README.md)

***

[create-test](../README.md) / ActionExec

# Interface: ActionExec

Defined in: [src/toolkit/action.ts:16](https://github.com/stairwaytowonderland/create-test/blob/b46546d95d3642e39fc686d8eb17bf9f255add49/src/toolkit/action.ts#L16)

Represents the configuration for a GitHub Action that includes a `run` method.

## Properties

### run

> **run**: () => `Promise`\<`unknown`\>

Defined in: [src/toolkit/action.ts:22](https://github.com/stairwaytowonderland/create-test/blob/b46546d95d3642e39fc686d8eb17bf9f255add49/src/toolkit/action.ts#L22)

Executes the main logic of the GitHub Action.

#### Returns

`Promise`\<`unknown`\>

A promise that resolves when the action has completed its run.
