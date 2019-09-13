---
id: "_lumin_.transformnode"
title: "lumin.TransformNode"
sidebar_label: "lumin.TransformNode"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [TransformNode](_lumin_.transformnode.md)

## Hierarchy

* [Node](_lumin_.node.md)

  ↳ **TransformNode**

  ↳ [AudioNode](_lumin_.audionode.md)

  ↳ [LightNode](_lumin_.lightnode.md)

  ↳ [ModelAttachmentNode](_lumin_.modelattachmentnode.md)

  ↳ [RenderNode](_lumin_.rendernode.md)

  ↳ [RootNode](_lumin_.rootnode.md)

  ↳ [VolumeCubeNode](_lumin_.volumecubenode.md)

  ↳ [UiNode](_lumin_.ui.uinode.md)

## Index

### Methods

* [addChild](_lumin_.transformnode.md#addchild)
* [addMoveCallback](_lumin_.transformnode.md#addmovecallback)
* [addToLayer](_lumin_.transformnode.md#addtolayer)
* [delayMove](_lumin_.transformnode.md#delaymove)
* [findChild](_lumin_.transformnode.md#findchild)
* [findChildren](_lumin_.transformnode.md#findchildren)
* [findParent](_lumin_.transformnode.md#findparent)
* [getAABB](_lumin_.transformnode.md#getaabb)
* [getAnchorPosition](_lumin_.transformnode.md#getanchorposition)
* [getChild](_lumin_.transformnode.md#getchild)
* [getChildCount](_lumin_.transformnode.md#getchildcount)
* [getCurrentPrismTransform](_lumin_.transformnode.md#getcurrentprismtransform)
* [getCurrentWorldTransform](_lumin_.transformnode.md#getcurrentworldtransform)
* [getCursorHoverState](_lumin_.transformnode.md#getcursorhoverstate)
* [getLocalAABB](_lumin_.transformnode.md#getlocalaabb)
* [getLocalPosition](_lumin_.transformnode.md#getlocalposition)
* [getLocalRotation](_lumin_.transformnode.md#getlocalrotation)
* [getLocalScale](_lumin_.transformnode.md#getlocalscale)
* [getLocalTransform](_lumin_.transformnode.md#getlocaltransform)
* [getName](_lumin_.transformnode.md#getname)
* [getNodeId](_lumin_.transformnode.md#getnodeid)
* [getParent](_lumin_.transformnode.md#getparent)
* [getParentedBoneName](_lumin_.transformnode.md#getparentedbonename)
* [getPrismId](_lumin_.transformnode.md#getprismid)
* [getPrismPosition](_lumin_.transformnode.md#getprismposition)
* [getRigidBody](_lumin_.transformnode.md#getrigidbody)
* [getRoot](_lumin_.transformnode.md#getroot)
* [getWorldPosition](_lumin_.transformnode.md#getworldposition)
* [isInLayer](_lumin_.transformnode.md#isinlayer)
* [isInSubtree](_lumin_.transformnode.md#isinsubtree)
* [isSkipRaycast](_lumin_.transformnode.md#isskipraycast)
* [isTriggerable](_lumin_.transformnode.md#istriggerable)
* [isVisibilityInherited](_lumin_.transformnode.md#isvisibilityinherited)
* [isVisible](_lumin_.transformnode.md#isvisible)
* [isVisibleInPrism](_lumin_.transformnode.md#isvisibleinprism)
* [removeChild](_lumin_.transformnode.md#removechild)
* [removeFromLayer](_lumin_.transformnode.md#removefromlayer)
* [setAnchorPosition](_lumin_.transformnode.md#setanchorposition)
* [setCursorHoverState](_lumin_.transformnode.md#setcursorhoverstate)
* [setLocalPosition](_lumin_.transformnode.md#setlocalposition)
* [setLocalRotation](_lumin_.transformnode.md#setlocalrotation)
* [setLocalScale](_lumin_.transformnode.md#setlocalscale)
* [setLocalTransform](_lumin_.transformnode.md#setlocaltransform)
* [setName](_lumin_.transformnode.md#setname)
* [setParentedBoneName](_lumin_.transformnode.md#setparentedbonename)
* [setSkipRaycast](_lumin_.transformnode.md#setskipraycast)
* [setTriggerable](_lumin_.transformnode.md#settriggerable)
* [setVisibilityInherited](_lumin_.transformnode.md#setvisibilityinherited)
* [setVisible](_lumin_.transformnode.md#setvisible)
* [stopTransformAnimations](_lumin_.transformnode.md#stoptransformanimations)
* [Delete](_lumin_.transformnode.md#static-delete)

## Methods

###  addChild

▸ **addChild**(`a_pChild`: [Node](_lumin_.node.md)): *boolean*

*Inherited from [Node](_lumin_.node.md).[addChild](_lumin_.node.md#addchild)*

**Parameters:**

Name | Type |
------ | ------ |
`a_pChild` | [Node](_lumin_.node.md) |

**Returns:** *boolean*

___

###  addMoveCallback

▸ **addMoveCallback**(`track`: number): *void*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`track` | number | 0 |

**Returns:** *void*

___

###  addToLayer

▸ **addToLayer**(`a_layer`: BigInt): *void*

*Inherited from [Node](_lumin_.node.md).[addToLayer](_lumin_.node.md#addtolayer)*

**Parameters:**

Name | Type |
------ | ------ |
`a_layer` | BigInt |

**Returns:** *void*

___

###  delayMove

▸ **delayMove**(`durationSecs`: number, `track`: number): *void*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`durationSecs` | number | - |
`track` | number | 0 |

**Returns:** *void*

___

###  findChild

▸ **findChild**(`name`: string): *[Node](_lumin_.node.md)*

*Inherited from [Node](_lumin_.node.md).[findChild](_lumin_.node.md#findchild)*

**Parameters:**

Name | Type |
------ | ------ |
`name` | string |

**Returns:** *[Node](_lumin_.node.md)*

___

###  findChildren

▸ **findChildren**(`a_type`: number, `a_bExactType`: boolean, `a_bIncludeSelf`: boolean): *Array‹[Node](_lumin_.node.md)›*

*Inherited from [Node](_lumin_.node.md).[findChildren](_lumin_.node.md#findchildren)*

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

*Inherited from [Node](_lumin_.node.md).[findParent](_lumin_.node.md#findparent)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_type` | number | - |
`a_bExactType` | boolean | 0 |

**Returns:** *[Node](_lumin_.node.md)*

___

###  getAABB

▸ **getAABB**(): *[AABB](_lumin_.math.aabb.md)*

*Inherited from [Node](_lumin_.node.md).[getAABB](_lumin_.node.md#getaabb)*

**Returns:** *[AABB](_lumin_.math.aabb.md)*

___

###  getAnchorPosition

▸ **getAnchorPosition**(): *[number, number, number]*

*Inherited from [Node](_lumin_.node.md).[getAnchorPosition](_lumin_.node.md#getanchorposition)*

**Returns:** *[number, number, number]*

___

###  getChild

▸ **getChild**(`a_iIndex`: number): *[Node](_lumin_.node.md)*

*Inherited from [Node](_lumin_.node.md).[getChild](_lumin_.node.md#getchild)*

**Parameters:**

Name | Type |
------ | ------ |
`a_iIndex` | number |

**Returns:** *[Node](_lumin_.node.md)*

___

###  getChildCount

▸ **getChildCount**(): *number*

*Inherited from [Node](_lumin_.node.md).[getChildCount](_lumin_.node.md#getchildcount)*

**Returns:** *number*

___

###  getCurrentPrismTransform

▸ **getCurrentPrismTransform**(): *[number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]*

*Inherited from [Node](_lumin_.node.md).[getCurrentPrismTransform](_lumin_.node.md#getcurrentprismtransform)*

**Returns:** *[number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]*

___

###  getCurrentWorldTransform

▸ **getCurrentWorldTransform**(): *[number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]*

*Inherited from [Node](_lumin_.node.md).[getCurrentWorldTransform](_lumin_.node.md#getcurrentworldtransform)*

**Returns:** *[number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]*

___

###  getCursorHoverState

▸ **getCursorHoverState**(): *[CursorHoverState](../enums/_lumin_.cursorhoverstate.md)*

*Inherited from [Node](_lumin_.node.md).[getCursorHoverState](_lumin_.node.md#getcursorhoverstate)*

**Returns:** *[CursorHoverState](../enums/_lumin_.cursorhoverstate.md)*

___

###  getLocalAABB

▸ **getLocalAABB**(): *[AABB](_lumin_.math.aabb.md)*

*Inherited from [Node](_lumin_.node.md).[getLocalAABB](_lumin_.node.md#getlocalaabb)*

**Returns:** *[AABB](_lumin_.math.aabb.md)*

___

###  getLocalPosition

▸ **getLocalPosition**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getLocalRotation

▸ **getLocalRotation**(): *[number, number, number, number]*

**Returns:** *[number, number, number, number]*

___

###  getLocalScale

▸ **getLocalScale**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getLocalTransform

▸ **getLocalTransform**(): *[number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]*

*Inherited from [Node](_lumin_.node.md).[getLocalTransform](_lumin_.node.md#getlocaltransform)*

**Returns:** *[number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]*

___

###  getName

▸ **getName**(): *string*

*Inherited from [Node](_lumin_.node.md).[getName](_lumin_.node.md#getname)*

**Returns:** *string*

___

###  getNodeId

▸ **getNodeId**(): *BigInt*

*Inherited from [Node](_lumin_.node.md).[getNodeId](_lumin_.node.md#getnodeid)*

**Returns:** *BigInt*

___

###  getParent

▸ **getParent**(): *[Node](_lumin_.node.md)*

*Inherited from [Node](_lumin_.node.md).[getParent](_lumin_.node.md#getparent)*

**Returns:** *[Node](_lumin_.node.md)*

___

###  getParentedBoneName

▸ **getParentedBoneName**(): *string*

*Inherited from [Node](_lumin_.node.md).[getParentedBoneName](_lumin_.node.md#getparentedbonename)*

**Returns:** *string*

___

###  getPrismId

▸ **getPrismId**(): *BigInt*

*Inherited from [Node](_lumin_.node.md).[getPrismId](_lumin_.node.md#getprismid)*

**Returns:** *BigInt*

___

###  getPrismPosition

▸ **getPrismPosition**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getRigidBody

▸ **getRigidBody**(): *[PhysicsRigidBody](_lumin_.physicsrigidbody.md)*

**Returns:** *[PhysicsRigidBody](_lumin_.physicsrigidbody.md)*

___

###  getRoot

▸ **getRoot**(): *[RootNode](_lumin_.rootnode.md)*

*Inherited from [Node](_lumin_.node.md).[getRoot](_lumin_.node.md#getroot)*

**Returns:** *[RootNode](_lumin_.rootnode.md)*

___

###  getWorldPosition

▸ **getWorldPosition**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  isInLayer

▸ **isInLayer**(`a_layer`: BigInt): *boolean*

*Inherited from [Node](_lumin_.node.md).[isInLayer](_lumin_.node.md#isinlayer)*

**Parameters:**

Name | Type |
------ | ------ |
`a_layer` | BigInt |

**Returns:** *boolean*

___

###  isInSubtree

▸ **isInSubtree**(`pParent`: [Node](_lumin_.node.md)): *boolean*

*Inherited from [Node](_lumin_.node.md).[isInSubtree](_lumin_.node.md#isinsubtree)*

**Parameters:**

Name | Type |
------ | ------ |
`pParent` | [Node](_lumin_.node.md) |

**Returns:** *boolean*

___

###  isSkipRaycast

▸ **isSkipRaycast**(): *boolean*

*Inherited from [Node](_lumin_.node.md).[isSkipRaycast](_lumin_.node.md#isskipraycast)*

**Returns:** *boolean*

___

###  isTriggerable

▸ **isTriggerable**(): *boolean*

*Inherited from [Node](_lumin_.node.md).[isTriggerable](_lumin_.node.md#istriggerable)*

**Returns:** *boolean*

___

###  isVisibilityInherited

▸ **isVisibilityInherited**(): *boolean*

*Inherited from [Node](_lumin_.node.md).[isVisibilityInherited](_lumin_.node.md#isvisibilityinherited)*

**Returns:** *boolean*

___

###  isVisible

▸ **isVisible**(): *boolean*

*Inherited from [Node](_lumin_.node.md).[isVisible](_lumin_.node.md#isvisible)*

**Returns:** *boolean*

___

###  isVisibleInPrism

▸ **isVisibleInPrism**(): *boolean*

*Inherited from [Node](_lumin_.node.md).[isVisibleInPrism](_lumin_.node.md#isvisibleinprism)*

**Returns:** *boolean*

___

###  removeChild

▸ **removeChild**(`a_pChild`: [Node](_lumin_.node.md)): *void*

*Inherited from [Node](_lumin_.node.md).[removeChild](_lumin_.node.md#removechild)*

**Parameters:**

Name | Type |
------ | ------ |
`a_pChild` | [Node](_lumin_.node.md) |

**Returns:** *void*

___

###  removeFromLayer

▸ **removeFromLayer**(`a_layer`: BigInt): *void*

*Inherited from [Node](_lumin_.node.md).[removeFromLayer](_lumin_.node.md#removefromlayer)*

**Parameters:**

Name | Type |
------ | ------ |
`a_layer` | BigInt |

**Returns:** *void*

___

###  setAnchorPosition

▸ **setAnchorPosition**(`a_position`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_position` | [number, number, number] |

**Returns:** *void*

___

###  setCursorHoverState

▸ **setCursorHoverState**(`state`: [CursorHoverState](../enums/_lumin_.cursorhoverstate.md)): *void*

*Inherited from [Node](_lumin_.node.md).[setCursorHoverState](_lumin_.node.md#setcursorhoverstate)*

**Parameters:**

Name | Type |
------ | ------ |
`state` | [CursorHoverState](../enums/_lumin_.cursorhoverstate.md) |

**Returns:** *void*

___

###  setLocalPosition

▸ **setLocalPosition**(`aPos`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`aPos` | [number, number, number] |

**Returns:** *void*

___

###  setLocalRotation

▸ **setLocalRotation**(`aRot`: [number, number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`aRot` | [number, number, number, number] |

**Returns:** *void*

___

###  setLocalScale

▸ **setLocalScale**(`aScale`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`aScale` | [number, number, number] |

**Returns:** *void*

___

###  setLocalTransform

▸ **setLocalTransform**(`aTransform`: [number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`aTransform` | [number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number] |

**Returns:** *void*

___

###  setName

▸ **setName**(`a_name`: string): *boolean*

*Inherited from [Node](_lumin_.node.md).[setName](_lumin_.node.md#setname)*

**Parameters:**

Name | Type |
------ | ------ |
`a_name` | string |

**Returns:** *boolean*

___

###  setParentedBoneName

▸ **setParentedBoneName**(`a_boneName`: string): *boolean*

*Inherited from [Node](_lumin_.node.md).[setParentedBoneName](_lumin_.node.md#setparentedbonename)*

**Parameters:**

Name | Type |
------ | ------ |
`a_boneName` | string |

**Returns:** *boolean*

___

###  setSkipRaycast

▸ **setSkipRaycast**(`a_skipRaycast`: boolean, `a_propagateToChildren`: boolean): *void*

*Inherited from [Node](_lumin_.node.md).[setSkipRaycast](_lumin_.node.md#setskipraycast)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_skipRaycast` | boolean | - |
`a_propagateToChildren` | boolean | 0 |

**Returns:** *void*

___

###  setTriggerable

▸ **setTriggerable**(`a_triggerable`: boolean): *void*

*Inherited from [Node](_lumin_.node.md).[setTriggerable](_lumin_.node.md#settriggerable)*

**Parameters:**

Name | Type |
------ | ------ |
`a_triggerable` | boolean |

**Returns:** *void*

___

###  setVisibilityInherited

▸ **setVisibilityInherited**(`a_inherit`: boolean): *void*

*Inherited from [Node](_lumin_.node.md).[setVisibilityInherited](_lumin_.node.md#setvisibilityinherited)*

**Parameters:**

Name | Type |
------ | ------ |
`a_inherit` | boolean |

**Returns:** *void*

___

###  setVisible

▸ **setVisible**(`a_visible`: boolean, `a_propagateToChildren`: boolean): *void*

*Inherited from [Node](_lumin_.node.md).[setVisible](_lumin_.node.md#setvisible)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_visible` | boolean | - |
`a_propagateToChildren` | boolean | 0 |

**Returns:** *void*

___

###  stopTransformAnimations

▸ **stopTransformAnimations**(): *void*

**Returns:** *void*

___

### `Static` Delete

▸ **Delete**(`node`: [Node](_lumin_.node.md)): *void*

*Inherited from [Node](_lumin_.node.md).[Delete](_lumin_.node.md#static-delete)*

**Parameters:**

Name | Type |
------ | ------ |
`node` | [Node](_lumin_.node.md) |

**Returns:** *void*