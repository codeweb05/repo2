[@sourceloop/bpmn-service](../README.md) / [Exports](../modules.md) / WorkerRegisterFn

# Interface: WorkerRegisterFn<T, R\>

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | `AnyObject` |
| `R` | `AnyObject` |

## Callable

### WorkerRegisterFn

▸ **WorkerRegisterFn**(`bpmnName`, `topicName`, `commandCtor`): `Promise`<`void`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `bpmnName` | `string` |
| `topicName` | `string` |
| `commandCtor` | [`BPMTask`](../classes/BPMTask.md)<`T`, `R`\> |

#### Returns

`Promise`<`void`\>

#### Defined in

[services/bpmn-service/src/types/types.ts:46](https://github.com/codeweb05/repo1/blob/ea19add/services/bpmn-service/src/types/types.ts#L46)
