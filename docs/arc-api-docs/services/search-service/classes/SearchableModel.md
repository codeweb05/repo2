[@sourceloop/search-service](../README.md) / [Exports](../modules.md) / SearchableModel

# Class: SearchableModel<T, S\>

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `Model` |
| `S` | extends typeof `Model` = typeof `Model` |

## Table of contents

### Constructors

- [constructor](SearchableModel.md#constructor)

### Properties

- [columns](SearchableModel.md#columns)
- [identifier](SearchableModel.md#identifier)
- [model](SearchableModel.md#model)

## Constructors

### constructor

• **new SearchableModel**<`T`, `S`\>()

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `Model`<`T`\> |
| `S` | extends typeof `Model` = typeof `Model` |

## Properties

### columns

• **columns**: [`ColumnMap`](../modules.md#columnmap)<`T`\>

#### Defined in

[services/search-service/src/types.ts:54](https://github.com/codeweb05/repo1/blob/ea19add/services/search-service/src/types.ts#L54)

___

### identifier

• `Optional` **identifier**: `string`

#### Defined in

[services/search-service/src/types.ts:55](https://github.com/codeweb05/repo1/blob/ea19add/services/search-service/src/types.ts#L55)

___

### model

• **model**: `S`

#### Defined in

[services/search-service/src/types.ts:53](https://github.com/codeweb05/repo1/blob/ea19add/services/search-service/src/types.ts#L53)