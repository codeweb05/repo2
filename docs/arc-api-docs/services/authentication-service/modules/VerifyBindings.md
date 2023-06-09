[@sourceloop/authentication-service](../README.md) / [Exports](../modules.md) / VerifyBindings

# Namespace: VerifyBindings

## Table of contents

### Variables

- [APPLE\_POST\_VERIFY\_PROVIDER](VerifyBindings.md#apple_post_verify_provider)
- [APPLE\_PRE\_VERIFY\_PROVIDER](VerifyBindings.md#apple_pre_verify_provider)
- [AZURE\_AD\_POST\_VERIFY\_PROVIDER](VerifyBindings.md#azure_ad_post_verify_provider)
- [AZURE\_AD\_PRE\_VERIFY\_PROVIDER](VerifyBindings.md#azure_ad_pre_verify_provider)
- [BEARER\_SIGNUP\_VERIFY\_PROVIDER](VerifyBindings.md#bearer_signup_verify_provider)
- [COGNITO\_POST\_VERIFY\_PROVIDER](VerifyBindings.md#cognito_post_verify_provider)
- [COGNITO\_PRE\_VERIFY\_PROVIDER](VerifyBindings.md#cognito_pre_verify_provider)
- [FACEBOOK\_POST\_VERIFY\_PROVIDER](VerifyBindings.md#facebook_post_verify_provider)
- [FACEBOOK\_PRE\_VERIFY\_PROVIDER](VerifyBindings.md#facebook_pre_verify_provider)
- [GOOGLE\_POST\_VERIFY\_PROVIDER](VerifyBindings.md#google_post_verify_provider)
- [GOOGLE\_PRE\_VERIFY\_PROVIDER](VerifyBindings.md#google_pre_verify_provider)
- [INSTAGRAM\_POST\_VERIFY\_PROVIDER](VerifyBindings.md#instagram_post_verify_provider)
- [INSTAGRAM\_PRE\_VERIFY\_PROVIDER](VerifyBindings.md#instagram_pre_verify_provider)
- [KEYCLOAK\_POST\_VERIFY\_PROVIDER](VerifyBindings.md#keycloak_post_verify_provider)
- [KEYCLOAK\_PRE\_VERIFY\_PROVIDER](VerifyBindings.md#keycloak_pre_verify_provider)
- [MFA\_PROVIDER](VerifyBindings.md#mfa_provider)
- [OTP\_GENERATE\_PROVIDER](VerifyBindings.md#otp_generate_provider)
- [OTP\_PROVIDER](VerifyBindings.md#otp_provider)
- [OTP\_SENDER\_PROVIDER](VerifyBindings.md#otp_sender_provider)
- [SAML\_POST\_VERIFY\_PROVIDER](VerifyBindings.md#saml_post_verify_provider)
- [SAML\_PRE\_VERIFY\_PROVIDER](VerifyBindings.md#saml_pre_verify_provider)

## Variables

### APPLE\_POST\_VERIFY\_PROVIDER

• `Const` **APPLE\_POST\_VERIFY\_PROVIDER**: `BindingKey`<[`ApplePostVerifyFn`](../interfaces/ApplePostVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:95](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L95)

___

### APPLE\_PRE\_VERIFY\_PROVIDER

• `Const` **APPLE\_PRE\_VERIFY\_PROVIDER**: `BindingKey`<[`ApplePreVerifyFn`](../interfaces/ApplePreVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:92](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L92)

___

### AZURE\_AD\_POST\_VERIFY\_PROVIDER

• `Const` **AZURE\_AD\_POST\_VERIFY\_PROVIDER**: `BindingKey`<[`AzureAdPostVerifyFn`](../interfaces/AzureAdPostVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:134](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L134)

___

### AZURE\_AD\_PRE\_VERIFY\_PROVIDER

• `Const` **AZURE\_AD\_PRE\_VERIFY\_PROVIDER**: `BindingKey`<[`AzureAdPreVerifyFn`](../interfaces/AzureAdPreVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:132](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L132)

___

### BEARER\_SIGNUP\_VERIFY\_PROVIDER

• `Const` **BEARER\_SIGNUP\_VERIFY\_PROVIDER**: `BindingKey`<`GenericAuthFn`<`any`\>\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:127](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L127)

___

### COGNITO\_POST\_VERIFY\_PROVIDER

• `Const` **COGNITO\_POST\_VERIFY\_PROVIDER**: `BindingKey`<[`CognitoPostVerifyFn`](../interfaces/CognitoPostVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:107](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L107)

___

### COGNITO\_PRE\_VERIFY\_PROVIDER

• `Const` **COGNITO\_PRE\_VERIFY\_PROVIDER**: `BindingKey`<[`CognitoPreVerifyFn`](../interfaces/CognitoPreVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:105](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L105)

___

### FACEBOOK\_POST\_VERIFY\_PROVIDER

• `Const` **FACEBOOK\_POST\_VERIFY\_PROVIDER**: `BindingKey`<[`FacebookPostVerifyFn`](../interfaces/FacebookPostVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:97](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L97)

___

### FACEBOOK\_PRE\_VERIFY\_PROVIDER

• `Const` **FACEBOOK\_PRE\_VERIFY\_PROVIDER**: `BindingKey`<[`FacebookPreVerifyFn`](../interfaces/FacebookPreVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:99](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L99)

___

### GOOGLE\_POST\_VERIFY\_PROVIDER

• `Const` **GOOGLE\_POST\_VERIFY\_PROVIDER**: `BindingKey`<[`GooglePostVerifyFn`](../interfaces/GooglePostVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:86](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L86)

___

### GOOGLE\_PRE\_VERIFY\_PROVIDER

• `Const` **GOOGLE\_PRE\_VERIFY\_PROVIDER**: `BindingKey`<[`GooglePreVerifyFn`](../interfaces/GooglePreVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:84](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L84)

___

### INSTAGRAM\_POST\_VERIFY\_PROVIDER

• `Const` **INSTAGRAM\_POST\_VERIFY\_PROVIDER**: `BindingKey`<[`InstagramPostVerifyFn`](../interfaces/InstagramPostVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:88](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L88)

___

### INSTAGRAM\_PRE\_VERIFY\_PROVIDER

• `Const` **INSTAGRAM\_PRE\_VERIFY\_PROVIDER**: `BindingKey`<[`InstagramPreVerifyFn`](../interfaces/InstagramPreVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:90](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L90)

___

### KEYCLOAK\_POST\_VERIFY\_PROVIDER

• `Const` **KEYCLOAK\_POST\_VERIFY\_PROVIDER**: `BindingKey`<[`KeyCloakPostVerifyFn`](../interfaces/KeyCloakPostVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:103](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L103)

___

### KEYCLOAK\_PRE\_VERIFY\_PROVIDER

• `Const` **KEYCLOAK\_PRE\_VERIFY\_PROVIDER**: `BindingKey`<[`KeyCloakPreVerifyFn`](../interfaces/KeyCloakPreVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:101](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L101)

___

### MFA\_PROVIDER

• `Const` **MFA\_PROVIDER**: `BindingKey`<[`MfaCheckFn`](../interfaces/MfaCheckFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:123](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L123)

___

### OTP\_GENERATE\_PROVIDER

• `Const` **OTP\_GENERATE\_PROVIDER**: `BindingKey`<[`OtpGenerateFn`](../interfaces/OtpGenerateFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:117](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L117)

___

### OTP\_PROVIDER

• `Const` **OTP\_PROVIDER**: `BindingKey`<[`OtpFn`](../interfaces/OtpFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:116](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L116)

___

### OTP\_SENDER\_PROVIDER

• `Const` **OTP\_SENDER\_PROVIDER**: `BindingKey`<[`OtpSenderFn`](../interfaces/OtpSenderFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:120](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L120)

___

### SAML\_POST\_VERIFY\_PROVIDER

• `Const` **SAML\_POST\_VERIFY\_PROVIDER**: `BindingKey`<[`SamlPostVerifyFn`](../interfaces/SamlPostVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:112](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L112)

___

### SAML\_PRE\_VERIFY\_PROVIDER

• `Const` **SAML\_PRE\_VERIFY\_PROVIDER**: `BindingKey`<[`SamlPreVerifyFn`](../interfaces/SamlPreVerifyFn.md)\>

#### Defined in

[services/authentication-service/src/providers/keys.ts:109](https://github.com/codeweb05/repo1/blob/a4cf318/services/authentication-service/src/providers/keys.ts#L109)
