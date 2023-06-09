[@sourceloop/authentication-service](../README.md) / [Exports](../modules.md) / Role

# Class: Role

## Hierarchy

- `UserModifiableEntity`

  ↳ **`Role`**

## Table of contents

### Constructors

- [constructor](Role.md#constructor)

### Properties

- [createdBy](Role.md#createdby)
- [createdOn](Role.md#createdon)
- [id](Role.md#id)
- [modifiedBy](Role.md#modifiedby)
- [modifiedOn](Role.md#modifiedon)
- [name](Role.md#name)
- [permissions](Role.md#permissions)
- [roleType](Role.md#roletype)

## Constructors

### constructor

• **new Role**(`data?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | `Partial`<[`Role`](Role.md)\> |

#### Overrides

UserModifiableEntity.constructor

#### Defined in

[services/authentication-service/src/models/role.model.ts:41](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/models/role.model.ts#L41)

## Properties

### createdBy

• `Optional` **createdBy**: `string`

#### Inherited from

UserModifiableEntity.createdBy

#### Defined in

packages/core/dist/models/user-modifiable-entity.model.d.ts:3

___

### createdOn

• `Optional` **createdOn**: `Date`

#### Inherited from

UserModifiableEntity.createdOn

#### Defined in

packages/core/dist/models/base-entity.model.d.ts:3

___

### id

• `Optional` **id**: `string`

#### Defined in

[services/authentication-service/src/models/role.model.ts:16](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/models/role.model.ts#L16)

___

### modifiedBy

• `Optional` **modifiedBy**: `string`

#### Inherited from

UserModifiableEntity.modifiedBy

#### Defined in

packages/core/dist/models/user-modifiable-entity.model.d.ts:4

___

### modifiedOn

• `Optional` **modifiedOn**: `Date`

#### Inherited from

UserModifiableEntity.modifiedOn

#### Defined in

packages/core/dist/models/base-entity.model.d.ts:4

___

### name

• **name**: `string`

#### Defined in

[services/authentication-service/src/models/role.model.ts:22](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/models/role.model.ts#L22)

___

### permissions

• **permissions**: `string`[]

#### Defined in

[services/authentication-service/src/models/role.model.ts:39](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/models/role.model.ts#L39)

___

### roleType

• **roleType**: `RoleTypes`

#### Defined in

[services/authentication-service/src/models/role.model.ts:33](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/models/role.model.ts#L33)
