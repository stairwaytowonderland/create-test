[**Toolkit**](../README.md)

***

[Toolkit](../README.md) / GitHubContext

# Interface: GitHubContext

Defined in: node\_modules/@actions/github/lib/context.d.ts:2

Represents the GitHub context object provided by the `@actions/github` library.

## Properties

### payload

> **payload**: `WebhookPayload`

Defined in: node\_modules/@actions/github/lib/context.d.ts:6

Webhook payload object that triggered the workflow

***

### eventName

> **eventName**: `string`

Defined in: node\_modules/@actions/github/lib/context.d.ts:7

***

### sha

> **sha**: `string`

Defined in: node\_modules/@actions/github/lib/context.d.ts:8

***

### ref

> **ref**: `string`

Defined in: node\_modules/@actions/github/lib/context.d.ts:9

***

### workflow

> **workflow**: `string`

Defined in: node\_modules/@actions/github/lib/context.d.ts:10

***

### action

> **action**: `string`

Defined in: node\_modules/@actions/github/lib/context.d.ts:11

***

### actor

> **actor**: `string`

Defined in: node\_modules/@actions/github/lib/context.d.ts:12

***

### job

> **job**: `string`

Defined in: node\_modules/@actions/github/lib/context.d.ts:13

***

### runAttempt

> **runAttempt**: `number`

Defined in: node\_modules/@actions/github/lib/context.d.ts:14

***

### runNumber

> **runNumber**: `number`

Defined in: node\_modules/@actions/github/lib/context.d.ts:15

***

### runId

> **runId**: `number`

Defined in: node\_modules/@actions/github/lib/context.d.ts:16

***

### apiUrl

> **apiUrl**: `string`

Defined in: node\_modules/@actions/github/lib/context.d.ts:17

***

### serverUrl

> **serverUrl**: `string`

Defined in: node\_modules/@actions/github/lib/context.d.ts:18

***

### graphqlUrl

> **graphqlUrl**: `string`

Defined in: node\_modules/@actions/github/lib/context.d.ts:19

## Accessors

### issue

#### Get Signature

> **get** **issue**(): `object`

Defined in: node\_modules/@actions/github/lib/context.d.ts:24

##### Returns

`object`

###### owner

> **owner**: `string`

###### repo

> **repo**: `string`

###### number

> **number**: `number`

***

### repo

#### Get Signature

> **get** **repo**(): `object`

Defined in: node\_modules/@actions/github/lib/context.d.ts:29

##### Returns

`object`

###### owner

> **owner**: `string`

###### repo

> **repo**: `string`
