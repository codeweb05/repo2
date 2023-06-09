[@sourceloop/authentication-service](../README.md) / [Exports](../modules.md) / OtpGenerateProvider

# Class: OtpGenerateProvider

## Implements

- `Provider`<[`OtpGenerateFn`](../interfaces/OtpGenerateFn.md)\>

## Table of contents

### Constructors

- [constructor](OtpGenerateProvider.md#constructor)

### Properties

- [logger](OtpGenerateProvider.md#logger)

### Methods

- [value](OtpGenerateProvider.md#value)

## Constructors

### constructor

• **new OtpGenerateProvider**(`logger`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `logger` | `ILogger` |

#### Defined in

[services/authentication-service/src/providers/otp-generate.provider.ts:16](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/otp-generate.provider.ts#L16)

## Properties

### logger

• `Private` `Readonly` **logger**: `ILogger`

#### Defined in

[services/authentication-service/src/providers/otp-generate.provider.ts:16](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/otp-generate.provider.ts#L16)

## Methods

### value

▸ **value**(): [`OtpGenerateFn`](../interfaces/OtpGenerateFn.md)

#### Returns

[`OtpGenerateFn`](../interfaces/OtpGenerateFn.md)

#### Implementation of

Provider.value

#### Defined in

[services/authentication-service/src/providers/otp-generate.provider.ts:17](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/otp-generate.provider.ts#L17)
