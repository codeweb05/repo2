[@sourceloop/authentication-service](../README.md) / [Exports](../modules.md) / ApplePreVerifyFn

# Interface: ApplePreVerifyFn

## Callable

### ApplePreVerifyFn

▸ **ApplePreVerifyFn**(`accessToken`, `refreshToken`, `profile`, `user`): `Promise`<``null`` \| `IAuthUser`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `accessToken` | `string` |
| `refreshToken` | `string` |
| `profile` | `Profile` |
| `user` | ``null`` \| `IAuthUser` |

#### Returns

`Promise`<``null`` \| `IAuthUser`\>

#### Defined in

[services/authentication-service/src/providers/types.ts:73](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/types.ts#L73)
