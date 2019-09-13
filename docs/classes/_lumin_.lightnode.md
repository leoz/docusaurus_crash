---
id: "_lumin_.lightnode"
title: "lumin.LightNode"
sidebar_label: "lumin.LightNode"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [LightNode](_lumin_.lightnode.md)

## Hierarchy

  ↳ [TransformNode](_lumin_.transformnode.md)

  ↳ **LightNode**

## Index

### Methods

* [addChild](_lumin_.lightnode.md#addchild)
* [addMoveCallback](_lumin_.lightnode.md#addmovecallback)
* [addToLayer](_lumin_.lightnode.md#addtolayer)
* [delayMove](_lumin_.lightnode.md#delaymove)
* [findChild](_lumin_.lightnode.md#findchild)
* [findChildren](_lumin_.lightnode.md#findchildren)
* [findParent](_lumin_.lightnode.md#findparent)
* [getAABB](_lumin_.lightnode.md#getaabb)
* [getAnchorPosition](_lumin_.lightnode.md#getanchorposition)
* [getCastsShadows](_lumin_.lightnode.md#getcastsshadows)
* [getChild](_lumin_.lightnode.md#getchild)
* [getChildCount](_lumin_.lightnode.md#getchildcount)
* [getColor](_lumin_.lightnode.md#getcolor)
* [getCurrentPrismTransform](_lumin_.lightnode.md#getcurrentprismtransform)
* [getCurrentWorldTransform](_lumin_.lightnode.md#getcurrentworldtransform)
* [getCursorHoverState](_lumin_.lightnode.md#getcursorhoverstate)
* [getHeadPoseOffset](_lumin_.lightnode.md#getheadposeoffset)
* [getIntensity](_lumin_.lightnode.md#getintensity)
* [getLocalAABB](_lumin_.lightnode.md#getlocalaabb)
* [getLocalPosition](_lumin_.lightnode.md#getlocalposition)
* [getLocalRotation](_lumin_.lightnode.md#getlocalrotation)
* [getLocalScale](_lumin_.lightnode.md#getlocalscale)
* [getLocalTransform](_lumin_.lightnode.md#getlocaltransform)
* [getName](_lumin_.lightnode.md#getname)
* [getNodeId](_lumin_.lightnode.md#getnodeid)
* [getParent](_lumin_.lightnode.md#getparent)
* [getParentedBoneName](_lumin_.lightnode.md#getparentedbonename)
* [getPrismId](_lumin_.lightnode.md#getprismid)
* [getPrismPosition](_lumin_.lightnode.md#getprismposition)
* [getRange](_lumin_.lightnode.md#getrange)
* [getRigidBody](_lumin_.lightnode.md#getrigidbody)
* [getRoot](_lumin_.lightnode.md#getroot)
* [getSpotAngle](_lumin_.lightnode.md#getspotangle)
* [getType](_lumin_.lightnode.md#gettype)
* [getUseHeadPose](_lumin_.lightnode.md#getuseheadpose)
* [getWorldPosition](_lumin_.lightnode.md#getworldposition)
* [isInLayer](_lumin_.lightnode.md#isinlayer)
* [isInSubtree](_lumin_.lightnode.md#isinsubtree)
* [isSkipRaycast](_lumin_.lightnode.md#isskipraycast)
* [isTriggerable](_lumin_.lightnode.md#istriggerable)
* [isVisibilityInherited](_lumin_.lightnode.md#isvisibilityinherited)
* [isVisible](_lumin_.lightnode.md#isvisible)
* [isVisibleInPrism](_lumin_.lightnode.md#isvisibleinprism)
* [removeChild](_lumin_.lightnode.md#removechild)
* [removeFromLayer](_lumin_.lightnode.md#removefromlayer)
* [setAnchorPosition](_lumin_.lightnode.md#setanchorposition)
* [setColor](_lumin_.lightnode.md#setcolor)
* [setCursorHoverState](_lumin_.lightnode.md#setcursorhoverstate)
* [setIntensity](_lumin_.lightnode.md#setintensity)
* [setLocalPosition](_lumin_.lightnode.md#setlocalposition)
* [setLocalRotation](_lumin_.lightnode.md#setlocalrotation)
* [setLocalScale](_lumin_.lightnode.md#setlocalscale)
* [setLocalTransform](_lumin_.lightnode.md#setlocaltransform)
* [setName](_lumin_.lightnode.md#setname)
* [setParentedBoneName](_lumin_.lightnode.md#setparentedbonename)
* [setRange](_lumin_.lightnode.md#setrange)
* [setSkipRaycast](_lumin_.lightnode.md#setskipraycast)
* [setSpotAngle](_lumin_.lightnode.md#setspotangle)
* [setTriggerable](_lumin_.lightnode.md#settriggerable)
* [setType](_lumin_.lightnode.md#settype)
* [setUseHeadPose](_lumin_.lightnode.md#setuseheadpose)
* [setVisibilityInherited](_lumin_.lightnode.md#setvisibilityinherited)
* [setVisible](_lumin_.lightnode.md#setvisible)
* [stopTransformAnimations](_lumin_.lightnode.md#stoptransformanimations)
* [trySetCastsShadows](_lumin_.lightnode.md#trysetcastsshadows)
* [Delete](_lumin_.lightnode.md#static-delete)

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

*Inherited from [TransformNode](_lumin_.transformnode.md).[addMoveCallback](_lumin_.transformnode.md#addmovecallback)*

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

*Inherited from [TransformNode](_lumin_.transformnode.md).[delayMove](_lumin_.transformnode.md#delaymove)*

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

###  getCastsShadows

▸ **getCastsShadows**(): *boolean*

**Returns:** *boolean*

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

###  getColor

▸ **getColor**(): *[number, number, number]*

**Returns:** *[number, number, number]*

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

###  getHeadPoseOffset

▸ **getHeadPoseOffset**(): *[number, number, number, number]*

**Returns:** *[number, number, number, number]*

___

###  getIntensity

▸ **getIntensity**(): *number*

**Returns:** *number*

___

###  getLocalAABB

▸ **getLocalAABB**(): *[AABB](_lumin_.math.aabb.md)*

*Inherited from [Node](_lumin_.node.md).[getLocalAABB](_lumin_.node.md#getlocalaabb)*

**Returns:** *[AABB](_lumin_.math.aabb.md)*

___

###  getLocalPosition

▸ **getLocalPosition**(): *[number, number, number]*

*Inherited from [TransformNode](_lumin_.transformnode.md).[getLocalPosition](_lumin_.transformnode.md#getlocalposition)*

**Returns:** *[number, number, number]*

___

###  getLocalRotation

▸ **getLocalRotation**(): *[number, number, number, number]*

*Inherited from [TransformNode](_lumin_.transformnode.md).[getLocalRotation](_lumin_.transformnode.md#getlocalrotation)*

**Returns:** *[number, number, number, number]*

___

###  getLocalScale

▸ **getLocalScale**(): *[number, number, number]*

*Inherited from [TransformNode](_lumin_.transformnode.md).[getLocalScale](_lumin_.transformnode.md#getlocalscale)*

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

*Inherited from [TransformNode](_lumin_.transformnode.md).[getPrismPosition](_lumin_.transformnode.md#getprismposition)*

**Returns:** *[number, number, number]*

___

###  getRange

▸ **getRange**(): *number*

**Returns:** *number*

___

###  getRigidBody

▸ **getRigidBody**(): *[PhysicsRigidBody](_lumin_.physicsrigidbody.md)*

*Inherited from [TransformNode](_lumin_.transformnode.md).[getRigidBody](_lumin_.transformnode.md#getrigidbody)*

**Returns:** *[PhysicsRigidBody](_lumin_.physicsrigidbody.md)*

___

###  getRoot

▸ **getRoot**(): *[RootNode](_lumin_.rootnode.md)*

*Inherited from [Node](_lumin_.node.md).[getRoot](_lumin_.node.md#getroot)*

**Returns:** *[RootNode](_lumin_.rootnode.md)*

___

###  getSpotAngle

▸ **getSpotAngle**(): *number*

**Returns:** *number*

___

###  getType

▸ **getType**(): *[LightType](../enums/_lumin_.utils.lighttype.md)*

**Returns:** *[LightType](../enums/_lumin_.utils.lighttype.md)*

___

###  getUseHeadPose

▸ **getUseHeadPose**(): *boolean*

**Returns:** *boolean*

___

###  getWorldPosition

▸ **getWorldPosition**(): *[number, number, number]*

*Inherited from [TransformNode](_lumin_.transformnode.md).[getWorldPosition](_lumin_.transformnode.md#getworldposition)*

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

*Inherited from [TransformNode](_lumin_.transformnode.md).[setAnchorPosition](_lumin_.transformnode.md#setanchorposition)*

**Parameters:**

Name | Type |
------ | ------ |
`a_position` | [number, number, number] |

**Returns:** *void*

___

###  setColor

▸ **setColor**(`a_color`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_color` | [number, number, number] |

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

###  setIntensity

▸ **setIntensity**(`a_intensity`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_intensity` | number |

**Returns:** *void*

___

###  setLocalPosition

▸ **setLocalPosition**(`aPos`: [number, number, number]): *void*

*Inherited from [TransformNode](_lumin_.transformnode.md).[setLocalPosition](_lumin_.transformnode.md#setlocalposition)*

**Parameters:**

Name | Type |
------ | ------ |
`aPos` | [number, number, number] |

**Returns:** *void*

___

###  setLocalRotation

▸ **setLocalRotation**(`aRot`: [number, number, number, number]): *void*

*Inherited from [TransformNode](_lumin_.transformnode.md).[setLocalRotation](_lumin_.transformnode.md#setlocalrotation)*

**Parameters:**

Name | Type |
------ | ------ |
`aRot` | [number, number, number, number] |

**Returns:** *void*

___

###  setLocalScale

▸ **setLocalScale**(`aScale`: [number, number, number]): *void*

*Inherited from [TransformNode](_lumin_.transformnode.md).[setLocalScale](_lumin_.transformnode.md#setlocalscale)*

**Parameters:**

Name | Type |
------ | ------ |
`aScale` | [number, number, number] |

**Returns:** *void*

___

###  setLocalTransform

▸ **setLocalTransform**(`aTransform`: [number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]): *void*

*Inherited from [TransformNode](_lumin_.transformnode.md).[setLocalTransform](_lumin_.transformnode.md#setlocaltransform)*

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

###  setRange

▸ **setRange**(`a_range`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_range` | number |

**Returns:** *void*

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

###  setSpotAngle

▸ **setSpotAngle**(`a_spotAngle`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_spotAngle` | number |

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

###  setType

▸ **setType**(`a_type`: [LightType](../enums/_lumin_.utils.lighttype.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_type` | [LightType](../enums/_lumin_.utils.lighttype.md) |

**Returns:** *void*

___

###  setUseHeadPose

▸ **setUseHeadPose**(`a_on`: boolean, `a_offset`: [number, number, number, number]): *void*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_on` | boolean | - |
`a_offset` | [number, number, number, number] | 0 |

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

*Inherited from [TransformNode](_lumin_.transformnode.md).[stopTransformAnimations](_lumin_.transformnode.md#stoptransformanimations)*

**Returns:** *void*

___

###  trySetCastsShadows

▸ **trySetCastsShadows**(`a_castsShadows`: boolean): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`a_castsShadows` | boolean |

**Returns:** *boolean*

___

### `Static` Delete

▸ **Delete**(`node`: [Node](_lumin_.node.md)): *void*

*Inherited from [Node](_lumin_.node.md).[Delete](_lumin_.node.md#static-delete)*

**Parameters:**

Name | Type |
------ | ------ |
`node` | [Node](_lumin_.node.md) |

**Returns:** *void*