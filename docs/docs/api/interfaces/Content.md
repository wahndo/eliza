# Interface: Content

Represents the content of a message, including its main text (`content`), any associated action (`action`), and the source of the content (`source`), if applicable.

## Extended by

- [`CreateAndBuyContent`](CreateAndBuyContent.md)

## Indexable

 \[`key`: `string`\]: `unknown`

## Properties

### action?

> `optional` **action**: `string`

#### Defined in

[core/src/core/types.ts:14](https://github.com/ai16z/eliza/blob/c537cb3e848b54fcb914d8ef84924fa5fdeaec66/core/src/core/types.ts#L14)

***

### attachments?

> `optional` **attachments**: [`Media`](../type-aliases/Media.md)[]

#### Defined in

[core/src/core/types.ts:18](https://github.com/ai16z/eliza/blob/c537cb3e848b54fcb914d8ef84924fa5fdeaec66/core/src/core/types.ts#L18)

***

### inReplyTo?

> `optional` **inReplyTo**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

#### Defined in

[core/src/core/types.ts:17](https://github.com/ai16z/eliza/blob/c537cb3e848b54fcb914d8ef84924fa5fdeaec66/core/src/core/types.ts#L17)

***

### source?

> `optional` **source**: `string`

#### Defined in

[core/src/core/types.ts:15](https://github.com/ai16z/eliza/blob/c537cb3e848b54fcb914d8ef84924fa5fdeaec66/core/src/core/types.ts#L15)

***

### text

> **text**: `string`

#### Defined in

[core/src/core/types.ts:13](https://github.com/ai16z/eliza/blob/c537cb3e848b54fcb914d8ef84924fa5fdeaec66/core/src/core/types.ts#L13)

***

### url?

> `optional` **url**: `string`

#### Defined in

[core/src/core/types.ts:16](https://github.com/ai16z/eliza/blob/c537cb3e848b54fcb914d8ef84924fa5fdeaec66/core/src/core/types.ts#L16)