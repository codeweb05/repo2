[@sourceloop/authentication-service](../README.md) / [Exports](../modules.md) / JWTAsymmetricVerifierProvider

# Class: JWTAsymmetricVerifierProvider<T\>

## Type parameters

| Name |
| :------ |
| `T` |

## Implements

- `Provider`<[`JWTVerifierFn`](../modules.md#jwtverifierfn)<`T`\>\>

## Table of contents

### Constructors

- [constructor](JWTAsymmetricVerifierProvider.md#constructor)

### Methods

- [value](JWTAsymmetricVerifierProvider.md#value)

## Constructors

### constructor

• **new JWTAsymmetricVerifierProvider**<`T`\>()

#### Type parameters

| Name |
| :------ |
| `T` |

## Methods

### value

▸ **value**(): [`JWTVerifierFn`](../modules.md#jwtverifierfn)<`T`\>

#### Returns

[`JWTVerifierFn`](../modules.md#jwtverifierfn)<`T`\>

#### Implementation of

Provider.value

#### Defined in

[services/authentication-service/src/providers/jwt-asymmetric-verifier.provider.ts:12](https://github.com/codeweb05/repo1/blob/ea19add/services/authentication-service/src/providers/jwt-asymmetric-verifier.provider.ts#L12)
