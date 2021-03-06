[@redhat-cloud-services/approval-client](../README.md) › [Globals](../globals.md) › [Action](action.md)

# Interface: Action

**`export`** 

**`interface`** Action

## Hierarchy

* **Action**

## Index

### Properties

* [comments](action.md#optional-comments)
* [created_at](action.md#optional-created_at)
* [id](action.md#optional-id)
* [operation](action.md#optional-operation)
* [processed_by](action.md#optional-processed_by)
* [request_id](action.md#optional-request_id)

## Properties

### `Optional` comments

• **comments**? : *string | null*

*Defined in [packages/approval/api.ts:63](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L63)*

Comments for action

**`memberof`** Action

___

### `Optional` created_at

• **created_at**? : *string*

*Defined in [packages/approval/api.ts:39](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L39)*

Timestamp of creation

**`memberof`** Action

___

### `Optional` id

• **id**? : *string*

*Defined in [packages/approval/api.ts:33](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L33)*

**`memberof`** Action

___

### `Optional` operation

• **operation**? : *[ActionOperationEnum](../enums/actionoperationenum.md)*

*Defined in [packages/approval/api.ts:57](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L57)*

Types of action, may be one of the value (approve, cancel, deny, notify, memo, skip, or start). The request state will be updated according to the operation.

**`memberof`** Action

___

### `Optional` processed_by

• **processed_by**? : *string*

*Defined in [packages/approval/api.ts:51](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L51)*

The person who performs the action

**`memberof`** Action

___

### `Optional` request_id

• **request_id**? : *string*

*Defined in [packages/approval/api.ts:45](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/approval/api.ts#L45)*

Associated request id

**`memberof`** Action
