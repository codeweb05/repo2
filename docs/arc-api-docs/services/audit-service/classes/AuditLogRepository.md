[@sourceloop/audit-service](../README.md) / [Exports](../modules.md) / AuditLogRepository

# Class: AuditLogRepository

## Hierarchy

- `DefaultCrudRepository`<[`AuditLog`](AuditLog.md), typeof [`id`](AuditLog.md#id)\>

  ↳ **`AuditLogRepository`**

## Table of contents

### Constructors

- [constructor](AuditLogRepository.md#constructor)

## Constructors

### constructor

• **new AuditLogRepository**(`dataSource`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `dataSource` | `DataSource` |

#### Overrides

DefaultCrudRepository&lt;
  AuditLog,
  typeof AuditLog.prototype.id
\&gt;.constructor

#### Defined in

[services/audit-service/src/repositories/audit-log.repository.ts:15](https://github.com/codeweb05/repo1/blob/a4cf318/services/audit-service/src/repositories/audit-log.repository.ts#L15)
