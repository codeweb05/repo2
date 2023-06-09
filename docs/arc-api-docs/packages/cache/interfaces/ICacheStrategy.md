[@sourceloop/cache](../README.md) / [Exports](../modules.md) / ICacheStrategy

# Interface: ICacheStrategy<M\>

Interface defining the component's options object

## Type parameters

| Name |
| :------ |
| `M` |

## Hierarchy

- [`CachePluginComponentOptions`](CachePluginComponentOptions.md)

  ↳ **`ICacheStrategy`**

## Implemented by

- [`RedisCacheStrategy`](../classes/RedisCacheStrategy.md)

## Table of contents

### Properties

- [cacheProvider](ICacheStrategy.md#cacheprovider)
- [getCacheDataSource](ICacheStrategy.md#getcachedatasource)
- [prefix](ICacheStrategy.md#prefix)

### Methods

- [clearCache](ICacheStrategy.md#clearcache)
- [saveInCache](ICacheStrategy.md#saveincache)
- [searchInCache](ICacheStrategy.md#searchincache)

## Properties

### cacheProvider

• **cacheProvider**: [`Redis`](../enums/CacheStrategyTypes.md#redis)

#### Inherited from

[CachePluginComponentOptions](CachePluginComponentOptions.md).[cacheProvider](CachePluginComponentOptions.md#cacheprovider)

#### Defined in

[types.ts:14](https://github.com/codeweb05/repo1/blob/a4cf318/packages/cache/src/types.ts#L14)

___

### getCacheDataSource

• **getCacheDataSource**: () => `Promise`<`DataSource`\>

#### Type declaration

▸ (): `Promise`<`DataSource`\>

##### Returns

`Promise`<`DataSource`\>

#### Defined in

[strategies/cache-strategy.ts:9](https://github.com/codeweb05/repo1/blob/a4cf318/packages/cache/src/strategies/cache-strategy.ts#L9)

___

### prefix

• **prefix**: `string`

#### Inherited from

[CachePluginComponentOptions](CachePluginComponentOptions.md).[prefix](CachePluginComponentOptions.md#prefix)

#### Defined in

[types.ts:15](https://github.com/codeweb05/repo1/blob/a4cf318/packages/cache/src/types.ts#L15)

## Methods

### clearCache

▸ **clearCache**(`cacheOptions`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `cacheOptions` | [`ICacheMixinOptions`](ICacheMixinOptions.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

[strategies/cache-strategy.ts:19](https://github.com/codeweb05/repo1/blob/a4cf318/packages/cache/src/strategies/cache-strategy.ts#L19)

___

### saveInCache

▸ **saveInCache**(`key`, `value`, `cacheOptions`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |
| `value` | ``null`` \| `M` \| `M`[] |
| `cacheOptions` | [`ICacheMixinOptions`](ICacheMixinOptions.md) |

#### Returns

`Promise`<`void`\>

#### Defined in

[strategies/cache-strategy.ts:14](https://github.com/codeweb05/repo1/blob/a4cf318/packages/cache/src/strategies/cache-strategy.ts#L14)

___

### searchInCache

▸ **searchInCache**(`key`, `cacheOptions`): `Promise`<`undefined` \| ``null`` \| `M` \| `M`[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |
| `cacheOptions` | [`ICacheMixinOptions`](ICacheMixinOptions.md) |

#### Returns

`Promise`<`undefined` \| ``null`` \| `M` \| `M`[]\>

#### Defined in

[strategies/cache-strategy.ts:10](https://github.com/codeweb05/repo1/blob/a4cf318/packages/cache/src/strategies/cache-strategy.ts#L10)
