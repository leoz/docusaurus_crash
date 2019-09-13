---
id: "_lumin_.physicsrigidbody"
title: "lumin.PhysicsRigidBody"
sidebar_label: "lumin.PhysicsRigidBody"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [PhysicsRigidBody](_lumin_.physicsrigidbody.md)

## Hierarchy

* **PhysicsRigidBody**

## Index

### Constructors

* [constructor](_lumin_.physicsrigidbody.md#constructor)

### Methods

* [addShape](_lumin_.physicsrigidbody.md#addshape)
* [applyForce](_lumin_.physicsrigidbody.md#applyforce)
* [applyForceAtPos](_lumin_.physicsrigidbody.md#applyforceatpos)
* [applyLocalForceAtPos](_lumin_.physicsrigidbody.md#applylocalforceatpos)
* [applyTorque](_lumin_.physicsrigidbody.md#applytorque)
* [clearColliderFlag](_lumin_.physicsrigidbody.md#clearcolliderflag)
* [clearCollidesWithFlag](_lumin_.physicsrigidbody.md#clearcollideswithflag)
* [clearForce](_lumin_.physicsrigidbody.md#clearforce)
* [clearTorque](_lumin_.physicsrigidbody.md#cleartorque)
* [getAngularDamping](_lumin_.physicsrigidbody.md#getangulardamping)
* [getAngularVelocity](_lumin_.physicsrigidbody.md#getangularvelocity)
* [getBodyType](_lumin_.physicsrigidbody.md#getbodytype)
* [getCenterOfMass](_lumin_.physicsrigidbody.md#getcenterofmass)
* [getColliderFlags](_lumin_.physicsrigidbody.md#getcolliderflags)
* [getCollidesWithFlags](_lumin_.physicsrigidbody.md#getcollideswithflags)
* [getInertiaTensor](_lumin_.physicsrigidbody.md#getinertiatensor)
* [getLinearDamping](_lumin_.physicsrigidbody.md#getlineardamping)
* [getLinearVelocity](_lumin_.physicsrigidbody.md#getlinearvelocity)
* [getMass](_lumin_.physicsrigidbody.md#getmass)
* [getMaxAngularVelocity](_lumin_.physicsrigidbody.md#getmaxangularvelocity)
* [getSleepThreshold](_lumin_.physicsrigidbody.md#getsleepthreshold)
* [isColliderFlagSet](_lumin_.physicsrigidbody.md#iscolliderflagset)
* [isCollidesWithFlagSet](_lumin_.physicsrigidbody.md#iscollideswithflagset)
* [lockAxes](_lumin_.physicsrigidbody.md#lockaxes)
* [node](_lumin_.physicsrigidbody.md#node)
* [removeShape](_lumin_.physicsrigidbody.md#removeshape)
* [setAngularDamping](_lumin_.physicsrigidbody.md#setangulardamping)
* [setAngularVelocity](_lumin_.physicsrigidbody.md#setangularvelocity)
* [setBodyType](_lumin_.physicsrigidbody.md#setbodytype)
* [setCenterOfMass](_lumin_.physicsrigidbody.md#setcenterofmass)
* [setColliderFlag](_lumin_.physicsrigidbody.md#setcolliderflag)
* [setColliderFlags](_lumin_.physicsrigidbody.md#setcolliderflags)
* [setCollidesWithFlag](_lumin_.physicsrigidbody.md#setcollideswithflag)
* [setCollidesWithFlags](_lumin_.physicsrigidbody.md#setcollideswithflags)
* [setEnableCCD](_lumin_.physicsrigidbody.md#setenableccd)
* [setIgnoreGravity](_lumin_.physicsrigidbody.md#setignoregravity)
* [setInertiaTensor](_lumin_.physicsrigidbody.md#setinertiatensor)
* [setLinearDamping](_lumin_.physicsrigidbody.md#setlineardamping)
* [setLinearVelocity](_lumin_.physicsrigidbody.md#setlinearvelocity)
* [setMass](_lumin_.physicsrigidbody.md#setmass)
* [setMaxAngularVelocity](_lumin_.physicsrigidbody.md#setmaxangularvelocity)
* [setSleepThreshold](_lumin_.physicsrigidbody.md#setsleepthreshold)

## Constructors

###  constructor

\+ **new PhysicsRigidBody**(): *[PhysicsRigidBody](_lumin_.physicsrigidbody.md)*

**Returns:** *[PhysicsRigidBody](_lumin_.physicsrigidbody.md)*

## Methods

###  addShape

▸ **addShape**(`shape`: [PhysicsShape](_lumin_.physicsshape.md), `position`: [number, number, number], `rotation`: [number, number, number, number]): *BigInt*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`shape` | [PhysicsShape](_lumin_.physicsshape.md) | - |
`position` | [number, number, number] | 0 |
`rotation` | [number, number, number, number] | 0 |

**Returns:** *BigInt*

___

###  applyForce

▸ **applyForce**(`type`: [ForceType](../enums/_lumin_.physics.forcetype.md), `force`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`type` | [ForceType](../enums/_lumin_.physics.forcetype.md) |
`force` | [number, number, number] |

**Returns:** *void*

___

###  applyForceAtPos

▸ **applyForceAtPos**(`type`: [ForceType](../enums/_lumin_.physics.forcetype.md), `force`: [number, number, number], `pos`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`type` | [ForceType](../enums/_lumin_.physics.forcetype.md) |
`force` | [number, number, number] |
`pos` | [number, number, number] |

**Returns:** *void*

___

###  applyLocalForceAtPos

▸ **applyLocalForceAtPos**(`type`: [ForceType](../enums/_lumin_.physics.forcetype.md), `force`: [number, number, number], `pos`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`type` | [ForceType](../enums/_lumin_.physics.forcetype.md) |
`force` | [number, number, number] |
`pos` | [number, number, number] |

**Returns:** *void*

___

###  applyTorque

▸ **applyTorque**(`type`: [ForceType](../enums/_lumin_.physics.forcetype.md), `force`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`type` | [ForceType](../enums/_lumin_.physics.forcetype.md) |
`force` | [number, number, number] |

**Returns:** *void*

___

###  clearColliderFlag

▸ **clearColliderFlag**(`flag`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`flag` | number |

**Returns:** *void*

___

###  clearCollidesWithFlag

▸ **clearCollidesWithFlag**(`flag`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`flag` | number |

**Returns:** *void*

___

###  clearForce

▸ **clearForce**(): *void*

**Returns:** *void*

___

###  clearTorque

▸ **clearTorque**(): *void*

**Returns:** *void*

___

###  getAngularDamping

▸ **getAngularDamping**(): *number*

**Returns:** *number*

___

###  getAngularVelocity

▸ **getAngularVelocity**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getBodyType

▸ **getBodyType**(): *[RigidBodyType](../enums/_lumin_.physics.rigidbodytype.md)*

**Returns:** *[RigidBodyType](../enums/_lumin_.physics.rigidbodytype.md)*

___

###  getCenterOfMass

▸ **getCenterOfMass**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getColliderFlags

▸ **getColliderFlags**(): *number*

**Returns:** *number*

___

###  getCollidesWithFlags

▸ **getCollidesWithFlags**(): *number*

**Returns:** *number*

___

###  getInertiaTensor

▸ **getInertiaTensor**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getLinearDamping

▸ **getLinearDamping**(): *number*

**Returns:** *number*

___

###  getLinearVelocity

▸ **getLinearVelocity**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getMass

▸ **getMass**(): *number*

**Returns:** *number*

___

###  getMaxAngularVelocity

▸ **getMaxAngularVelocity**(): *number*

**Returns:** *number*

___

###  getSleepThreshold

▸ **getSleepThreshold**(): *number*

**Returns:** *number*

___

###  isColliderFlagSet

▸ **isColliderFlagSet**(`flag`: number): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`flag` | number |

**Returns:** *boolean*

___

###  isCollidesWithFlagSet

▸ **isCollidesWithFlagSet**(`flag`: number): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`flag` | number |

**Returns:** *boolean*

___

###  lockAxes

▸ **lockAxes**(`linear`: [AxisLock](../enums/_lumin_.physics.axislock.md), `angular`: [AxisLock](../enums/_lumin_.physics.axislock.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`linear` | [AxisLock](../enums/_lumin_.physics.axislock.md) |
`angular` | [AxisLock](../enums/_lumin_.physics.axislock.md) |

**Returns:** *void*

___

###  node

▸ **node**(): *[Node](_lumin_.node.md)*

**Returns:** *[Node](_lumin_.node.md)*

___

###  removeShape

▸ **removeShape**(`id`: BigInt): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`id` | BigInt |

**Returns:** *boolean*

___

###  setAngularDamping

▸ **setAngularDamping**(`damping`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`damping` | number |

**Returns:** *void*

___

###  setAngularVelocity

▸ **setAngularVelocity**(`velocity`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`velocity` | [number, number, number] |

**Returns:** *void*

___

###  setBodyType

▸ **setBodyType**(`type`: [RigidBodyType](../enums/_lumin_.physics.rigidbodytype.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`type` | [RigidBodyType](../enums/_lumin_.physics.rigidbodytype.md) |

**Returns:** *void*

___

###  setCenterOfMass

▸ **setCenterOfMass**(`com`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`com` | [number, number, number] |

**Returns:** *void*

___

###  setColliderFlag

▸ **setColliderFlag**(`flag`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`flag` | number |

**Returns:** *void*

___

###  setColliderFlags

▸ **setColliderFlags**(`flags`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`flags` | number |

**Returns:** *void*

___

###  setCollidesWithFlag

▸ **setCollidesWithFlag**(`flag`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`flag` | number |

**Returns:** *void*

___

###  setCollidesWithFlags

▸ **setCollidesWithFlags**(`flags`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`flags` | number |

**Returns:** *void*

___

###  setEnableCCD

▸ **setEnableCCD**(`enable`: boolean): *void*

**Parameters:**

Name | Type |
------ | ------ |
`enable` | boolean |

**Returns:** *void*

___

###  setIgnoreGravity

▸ **setIgnoreGravity**(`ignore`: boolean): *void*

**Parameters:**

Name | Type |
------ | ------ |
`ignore` | boolean |

**Returns:** *void*

___

###  setInertiaTensor

▸ **setInertiaTensor**(`tensor`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`tensor` | [number, number, number] |

**Returns:** *void*

___

###  setLinearDamping

▸ **setLinearDamping**(`damping`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`damping` | number |

**Returns:** *void*

___

###  setLinearVelocity

▸ **setLinearVelocity**(`velocity`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`velocity` | [number, number, number] |

**Returns:** *void*

___

###  setMass

▸ **setMass**(`massKg`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`massKg` | number |

**Returns:** *void*

___

###  setMaxAngularVelocity

▸ **setMaxAngularVelocity**(`velocity`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`velocity` | number |

**Returns:** *void*

___

###  setSleepThreshold

▸ **setSleepThreshold**(`threshold`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`threshold` | number |

**Returns:** *void*