---
id: "_lumin_.node"
title: "lumin.Node"
sidebar_label: "lumin.Node"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [Node](_lumin_.node.md)

## Hierarchy

* **Node**

  ↳ [TransformNode](_lumin_.transformnode.md)

## Index

### Methods

* [addChild](_lumin_.node.md#addchild)
* [addToLayer](_lumin_.node.md#addtolayer)
* [findChild](_lumin_.node.md#findchild)
* [findChildren](_lumin_.node.md#findchildren)
* [findParent](_lumin_.node.md#findparent)
* [getAABB](_lumin_.node.md#getaabb)
* [getAnchorPosition](_lumin_.node.md#getanchorposition)
* [getChild](_lumin_.node.md#getchild)
* [getChildCount](_lumin_.node.md#getchildcount)
* [getCurrentPrismTransform](_lumin_.node.md#getcurrentprismtransform)
* [getCurrentWorldTransform](_lumin_.node.md#getcurrentworldtransform)
* [getCursorHoverState](_lumin_.node.md#getcursorhoverstate)
* [getLocalAABB](_lumin_.node.md#getlocalaabb)
* [getLocalTransform](_lumin_.node.md#getlocaltransform)
* [getName](_lumin_.node.md#getname)
* [getNodeId](_lumin_.node.md#getnodeid)
* [getParent](_lumin_.node.md#getparent)
* [getParentedBoneName](_lumin_.node.md#getparentedbonename)
* [getPrismId](_lumin_.node.md#getprismid)
* [getRoot](_lumin_.node.md#getroot)
* [isInLayer](_lumin_.node.md#isinlayer)
* [isInSubtree](_lumin_.node.md#isinsubtree)
* [isSkipRaycast](_lumin_.node.md#isskipraycast)
* [isTriggerable](_lumin_.node.md#istriggerable)
* [isVisibilityInherited](_lumin_.node.md#isvisibilityinherited)
* [isVisible](_lumin_.node.md#isvisible)
* [isVisibleInPrism](_lumin_.node.md#isvisibleinprism)
* [removeChild](_lumin_.node.md#removechild)
* [removeFromLayer](_lumin_.node.md#removefromlayer)
* [setCursorHoverState](_lumin_.node.md#setcursorhoverstate)
* [setName](_lumin_.node.md#setname)
* [setParentedBoneName](_lumin_.node.md#setparentedbonename)
* [setSkipRaycast](_lumin_.node.md#setskipraycast)
* [setTriggerable](_lumin_.node.md#settriggerable)
* [setVisibilityInherited](_lumin_.node.md#setvisibilityinherited)
* [setVisible](_lumin_.node.md#setvisible)
* [Delete](_lumin_.node.md#static-delete)

## Methods

###  addChild

▸ **addChild**(`a_pChild`: [Node](_lumin_.node.md)): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`a_pChild` | [Node](_lumin_.node.md) |

**Returns:** *boolean*

___

###  addToLayer

▸ **addToLayer**(`a_layer`: BigInt): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_layer` | BigInt |

**Returns:** *void*

___

###  findChild

▸ **findChild**(`name`: string): *[Node](_lumin_.node.md)*

**Parameters:**

Name | Type |
------ | ------ |
`name` | string |

**Returns:** *[Node](_lumin_.node.md)*

___

###  findChildren

▸ **findChildren**(`a_type`: number, `a_bExactType`: boolean, `a_bIncludeSelf`: boolean): *Array‹[Node](_lumin_.node.md)›*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_type` | number | - |
`a_bExactType` | boolean | 0 |
`a_bIncludeSelf` | boolean | 0 |

**Returns:** *Array‹[Node](_lumin_.node.md)›*

___

###  findParent

▸ **findParent**(`a_type`: number, `a_bExactType`: boolean): *[Node](_lumin_.node.md)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_type` | number | - |
`a_bExactType` | boolean | 0 |

**Returns:** *[Node](_lumin_.node.md)*

___

###  getAABB

▸ **getAABB**(): *[AABB](_lumin_.math.aabb.md)*

**Returns:** *[AABB](_lumin_.math.aabb.md)*

___

###  getAnchorPosition

▸ **getAnchorPosition**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getChild

▸ **getChild**(`a_iIndex`: number): *[Node](_lumin_.node.md)*

**Parameters:**

Name | Type |
------ | ------ |
`a_iIndex` | number |

**Returns:** *[Node](_lumin_.node.md)*

___

###  getChildCount

▸ **getChildCount**(): *number*

**Returns:** *number*

___

###  getCurrentPrismTransform

▸ **getCurrentPrismTransform**(): *[number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]*

**Returns:** *[number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]*

___

###  getCurrentWorldTransform

▸ **getCurrentWorldTransform**(): *[number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]*

**Returns:** *[number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]*

___

###  getCursorHoverState

▸ **getCursorHoverState**(): *[CursorHoverState](../enums/_lumin_.cursorhoverstate.md)*

**Returns:** *[CursorHoverState](../enums/_lumin_.cursorhoverstate.md)*

___

###  getLocalAABB

▸ **getLocalAABB**(): *[AABB](_lumin_.math.aabb.md)*

**Returns:** *[AABB](_lumin_.math.aabb.md)*

___

###  getLocalTransform

▸ **getLocalTransform**(): *[number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]*

**Returns:** *[number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]*

___

###  getName

▸ **getName**(): *string*

**Returns:** *string*

___

###  getNodeId

▸ **getNodeId**(): *BigInt*

**Returns:** *BigInt*

___

###  getParent

▸ **getParent**(): *[Node](_lumin_.node.md)*

**Returns:** *[Node](_lumin_.node.md)*

___

###  getParentedBoneName

▸ **getParentedBoneName**(): *string*

**Returns:** *string*

___

###  getPrismId

▸ **getPrismId**(): *BigInt*

**Returns:** *BigInt*

___

###  getRoot

▸ **getRoot**(): *[RootNode](_lumin_.rootnode.md)*

**Returns:** *[RootNode](_lumin_.rootnode.md)*

___

###  isInLayer

▸ **isInLayer**(`a_layer`: BigInt): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`a_layer` | BigInt |

**Returns:** *boolean*

___

###  isInSubtree

▸ **isInSubtree**(`pParent`: [Node](_lumin_.node.md)): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`pParent` | [Node](_lumin_.node.md) |

**Returns:** *boolean*

___

###  isSkipRaycast

▸ **isSkipRaycast**(): *boolean*

**Returns:** *boolean*

___

###  isTriggerable

▸ **isTriggerable**(): *boolean*

**Returns:** *boolean*

___

###  isVisibilityInherited

▸ **isVisibilityInherited**(): *boolean*

**Returns:** *boolean*

___

###  isVisible

▸ **isVisible**(): *boolean*

**Returns:** *boolean*

___

###  isVisibleInPrism

▸ **isVisibleInPrism**(): *boolean*

**Returns:** *boolean*

___

###  removeChild

▸ **removeChild**(`a_pChild`: [Node](_lumin_.node.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_pChild` | [Node](_lumin_.node.md) |

**Returns:** *void*

___

###  removeFromLayer

▸ **removeFromLayer**(`a_layer`: BigInt): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_layer` | BigInt |

**Returns:** *void*

___

###  setCursorHoverState

▸ **setCursorHoverState**(`state`: [CursorHoverState](../enums/_lumin_.cursorhoverstate.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`state` | [CursorHoverState](../enums/_lumin_.cursorhoverstate.md) |

**Returns:** *void*

___

###  setName

▸ **setName**(`a_name`: string): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`a_name` | string |

**Returns:** *boolean*

___

###  setParentedBoneName

▸ **setParentedBoneName**(`a_boneName`: string): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`a_boneName` | string |

**Returns:** *boolean*

___

###  setSkipRaycast

▸ **setSkipRaycast**(`a_skipRaycast`: boolean, `a_propagateToChildren`: boolean): *void*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_skipRaycast` | boolean | - |
`a_propagateToChildren` | boolean | 0 |

**Returns:** *void*

___

###  setTriggerable

▸ **setTriggerable**(`a_triggerable`: boolean): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_triggerable` | boolean |

**Returns:** *void*

___

###  setVisibilityInherited

▸ **setVisibilityInherited**(`a_inherit`: boolean): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_inherit` | boolean |

**Returns:** *void*

___

###  setVisible

▸ **setVisible**(`a_visible`: boolean, `a_propagateToChildren`: boolean): *void*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_visible` | boolean | - |
`a_propagateToChildren` | boolean | 0 |

**Returns:** *void*

___

### `Static` Delete

▸ **Delete**(`node`: [Node](_lumin_.node.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`node` | [Node](_lumin_.node.md) |

**Returns:** *void*