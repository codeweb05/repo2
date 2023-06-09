[@sourceloop/authentication-service](../README.md) / [Exports](../modules.md) / AzureAdPreVerifyFn

# Interface: AzureAdPreVerifyFn

## Callable

### AzureAdPreVerifyFn

▸ **AzureAdPreVerifyFn**(`accessToken`, `refreshToken`, `profile`, `user`): `Promise`<``null`` \| `IAuthUser`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `accessToken` | `string` |
| `refreshToken` | `string` |
| `profile` | `IProfile` |
| `user` | ``null`` \| `IAuthUser` |

#### Returns

`Promise`<``null`` \| `IAuthUser`\>

#### Defined in

[services/authentication-service/src/providers/types.ts:177](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/types.ts#L177)
