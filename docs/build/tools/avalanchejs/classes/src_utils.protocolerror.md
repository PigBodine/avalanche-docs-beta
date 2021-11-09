[avalanche](../README.md) › [src/utils](../modules/src_utils.md) › [ProtocolError](src_utils.protocolerror.md)

# Class: ProtocolError

## Hierarchy

  ↳ [AvalancheError](src_utils.avalancheerror.md)

  ↳ **ProtocolError**

## Index

### Constructors

* [constructor](src_utils.protocolerror.md#constructor)

### Properties

* [errorCode](src_utils.protocolerror.md#errorcode)
* [message](src_utils.protocolerror.md#message)
* [name](src_utils.protocolerror.md#name)
* [stack](src_utils.protocolerror.md#optional-stack)

### Methods

* [getCode](src_utils.protocolerror.md#getcode)

## Constructors

###  constructor

\+ **new ProtocolError**(`m`: string): *[ProtocolError](src_utils.protocolerror.md)*

*Overrides [AvalancheError](src_utils.avalancheerror.md).[constructor](src_utils.avalancheerror.md#constructor)*

*Defined in [src/utils/errors.ts:344](https://github.com/ava-labs/avalanchejs/blob/82de5d8/src/utils/errors.ts#L344)*

**Parameters:**

Name | Type |
------ | ------ |
`m` | string |

**Returns:** *[ProtocolError](src_utils.protocolerror.md)*

## Properties

###  errorCode

• **errorCode**: *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[errorCode](src_utils.avalancheerror.md#errorcode)*

*Defined in [src/utils/errors.ts:45](https://github.com/ava-labs/avalanchejs/blob/82de5d8/src/utils/errors.ts#L45)*

___

###  message

• **message**: *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[message](src_utils.avalancheerror.md#message)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:974

___

###  name

• **name**: *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[name](src_utils.avalancheerror.md#name)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:973

___

### `Optional` stack

• **stack**? : *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[stack](src_utils.avalancheerror.md#optional-stack)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:975

## Methods

###  getCode

▸ **getCode**(): *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[getCode](src_utils.avalancheerror.md#getcode)*

*Defined in [src/utils/errors.ts:52](https://github.com/ava-labs/avalanchejs/blob/82de5d8/src/utils/errors.ts#L52)*

**Returns:** *string*
