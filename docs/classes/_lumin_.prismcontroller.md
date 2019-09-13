---
id: "_lumin_.prismcontroller"
title: "lumin.PrismController"
sidebar_label: "lumin.PrismController"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [PrismController](_lumin_.prismcontroller.md)

## Hierarchy

* **PrismController**

## Index

### Constructors

* [constructor](_lumin_.prismcontroller.md#constructor)

### Methods

* [addChildController](_lumin_.prismcontroller.md#addchildcontroller)
* [deleteSceneGraph](_lumin_.prismcontroller.md#deletescenegraph)
* [getEventSleepTime](_lumin_.prismcontroller.md#geteventsleeptime)
* [getName](_lumin_.prismcontroller.md#getname)
* [getPrism](_lumin_.prismcontroller.md#getprism)
* [getRoot](_lumin_.prismcontroller.md#getroot)
* [isPrismDeletePending](_lumin_.prismcontroller.md#isprismdeletepending)
* [onAttachPrism](_lumin_.prismcontroller.md#onattachprism)
* [onDetachPrism](_lumin_.prismcontroller.md#ondetachprism)
* [onEvent](_lumin_.prismcontroller.md#onevent)
* [onPreAttachPrism](_lumin_.prismcontroller.md#onpreattachprism)
* [onUpdate](_lumin_.prismcontroller.md#onupdate)
* [removeChildController](_lumin_.prismcontroller.md#removechildcontroller)
* [setEventSleepTime](_lumin_.prismcontroller.md#seteventsleeptime)
* [setRetainSceneGraph](_lumin_.prismcontroller.md#setretainscenegraph)

## Constructors

###  constructor

\+ **new PrismController**(`a_name`: string): *[PrismController](_lumin_.prismcontroller.md)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_name` | string | 0 |

**Returns:** *[PrismController](_lumin_.prismcontroller.md)*

## Methods

###  addChildController

▸ **addChildController**(`controller`: [PrismController](_lumin_.prismcontroller.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`controller` | [PrismController](_lumin_.prismcontroller.md) |

**Returns:** *void*

___

###  deleteSceneGraph

▸ **deleteSceneGraph**(): *void*

**Returns:** *void*

___

###  getEventSleepTime

▸ **getEventSleepTime**(): *number*

**Returns:** *number*

___

###  getName

▸ **getName**(): *string*

**Returns:** *string*

___

###  getPrism

▸ **getPrism**(): *[Prism](_lumin_.prism.md)*

**Returns:** *[Prism](_lumin_.prism.md)*

___

###  getRoot

▸ **getRoot**(): *[TransformNode](_lumin_.transformnode.md)*

**Returns:** *[TransformNode](_lumin_.transformnode.md)*

___

###  isPrismDeletePending

▸ **isPrismDeletePending**(): *boolean*

**Returns:** *boolean*

___

###  onAttachPrism

▸ **onAttachPrism**(`prism`: [Prism](_lumin_.prism.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`prism` | [Prism](_lumin_.prism.md) |

**Returns:** *void*

___

###  onDetachPrism

▸ **onDetachPrism**(`prism`: [Prism](_lumin_.prism.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`prism` | [Prism](_lumin_.prism.md) |

**Returns:** *void*

___

###  onEvent

▸ **onEvent**(`a_pEvent`: [ServerEvent](_lumin_.serverevent.md)): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`a_pEvent` | [ServerEvent](_lumin_.serverevent.md) |

**Returns:** *boolean*

___

###  onPreAttachPrism

▸ **onPreAttachPrism**(`prism`: [Prism](_lumin_.prism.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`prism` | [Prism](_lumin_.prism.md) |

**Returns:** *void*

___

###  onUpdate

▸ **onUpdate**(`a_fDelta`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_fDelta` | number |

**Returns:** *void*

___

###  removeChildController

▸ **removeChildController**(`controller`: [PrismController](_lumin_.prismcontroller.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`controller` | [PrismController](_lumin_.prismcontroller.md) |

**Returns:** *void*

___

###  setEventSleepTime

▸ **setEventSleepTime**(`a_fSleepTime`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_fSleepTime` | number |

**Returns:** *void*

___

###  setRetainSceneGraph

▸ **setRetainSceneGraph**(`retainSceneGraph`: boolean): *void*

**Parameters:**

Name | Type |
------ | ------ |
`retainSceneGraph` | boolean |

**Returns:** *void*