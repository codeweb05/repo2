[@sourceloop/cache](../README.md) / [Exports](../modules.md) / CacheManager

# Class: CacheManager

## Table of contents

### Constructors

- [constructor](CacheManager.md#constructor)

### Properties

- [options](CacheManager.md#options)

### Methods

- [CacheRepositoryMixin](CacheManager.md#cacherepositorymixin)

## Constructors

### constructor

• **new CacheManager**()

## Properties

### options

▪ `Static` **options**: [`CachePluginComponentOptions`](../interfaces/CachePluginComponentOptions.md) = `DEFAULT_CACHE_PLUGIN_OPTIONS`

#### Defined in

[mixins/cache.mixin.ts:27](https://github.com/codeweb05/repo1/blob/a4cf318/packages/cache/src/mixins/cache.mixin.ts#L27)

## Methods

### CacheRepositoryMixin

▸ `Static` **CacheRepositoryMixin**<`M`, `ID`, `Relations`, `R`\>(`baseClass`, `cacheOptions`): `R` & `Constructor`<[`ICacheMixin`](../interfaces/ICacheMixin.md)<`M`, `ID`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `M` | extends `Entity`<`M`\> |
| `ID` | `ID` |
| `Relations` | extends `object` |
| `R` | extends `MixinTarget`<`DefaultCrudRepository`<`M`, `ID`, `Relations`\>\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `baseClass` | `R` |
| `cacheOptions` | [`ICacheMixinOptions`](../interfaces/ICacheMixinOptions.md) & `Partial`<[`CachePluginComponentOptions`](../interfaces/CachePluginComponentOptions.md)\> |

#### Returns

`R` & `Constructor`<[`ICacheMixin`](../interfaces/ICacheMixin.md)<`M`, `ID`\>\>

#### Defined in

[mixins/cache.mixin.ts:30](https://github.com/codeweb05/repo1/blob/a4cf318/packages/cache/src/mixins/cache.mixin.ts#L30)
