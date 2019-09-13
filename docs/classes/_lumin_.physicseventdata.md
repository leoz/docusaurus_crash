---
id: "_lumin_.physicseventdata"
title: "lumin.PhysicsEventData"
sidebar_label: "lumin.PhysicsEventData"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [PhysicsEventData](_lumin_.physicseventdata.md)

## Hierarchy

* [ServerEvent](_lumin_.serverevent.md)

  ↳ **PhysicsEventData**

## Index

### Constructors

* [constructor](_lumin_.physicseventdata.md#constructor)

### Methods

* [getBody1CollisionMaterial](_lumin_.physicseventdata.md#getbody1collisionmaterial)
* [getBody2CollisionMaterial](_lumin_.physicseventdata.md#getbody2collisionmaterial)
* [getCollisionCount](_lumin_.physicseventdata.md#getcollisioncount)
* [getCollisionForces](_lumin_.physicseventdata.md#getcollisionforces)
* [getCollisionNormals](_lumin_.physicseventdata.md#getcollisionnormals)
* [getCollisionPoints](_lumin_.physicseventdata.md#getcollisionpoints)
* [getCollisionType](_lumin_.physicseventdata.md#getcollisiontype)
* [getPrismId](_lumin_.physicseventdata.md#getprismid)
* [getRigidBody1](_lumin_.physicseventdata.md#getrigidbody1)
* [getRigidBody2](_lumin_.physicseventdata.md#getrigidbody2)
* [isInputEventType](_lumin_.physicseventdata.md#isinputeventtype)
* [toString](_lumin_.physicseventdata.md#tostring)

## Constructors

###  constructor

\+ **new PhysicsEventData**(): *[PhysicsEventData](_lumin_.physicseventdata.md)*

*Overrides [ServerEvent](_lumin_.serverevent.md).[constructor](_lumin_.serverevent.md#constructor)*

**Returns:** *[PhysicsEventData](_lumin_.physicseventdata.md)*

## Methods

###  getBody1CollisionMaterial

▸ **getBody1CollisionMaterial**(`collision`: number): *[PhysicsMaterial](_lumin_.physicsmaterial.md)*

**Parameters:**

Name | Type |
------ | ------ |
`collision` | number |

**Returns:** *[PhysicsMaterial](_lumin_.physicsmaterial.md)*

___

###  getBody2CollisionMaterial

▸ **getBody2CollisionMaterial**(`collision`: number): *[PhysicsMaterial](_lumin_.physicsmaterial.md)*

**Parameters:**

Name | Type |
------ | ------ |
`collision` | number |

**Returns:** *[PhysicsMaterial](_lumin_.physicsmaterial.md)*

___

###  getCollisionCount

▸ **getCollisionCount**(): *number*

**Returns:** *number*

___

###  getCollisionForces

▸ **getCollisionForces**(): *Array‹[number, number, number]›*

**Returns:** *Array‹[number, number, number]›*

___

###  getCollisionNormals

▸ **getCollisionNormals**(): *Array‹[number, number, number]›*

**Returns:** *Array‹[number, number, number]›*

___

###  getCollisionPoints

▸ **getCollisionPoints**(): *Array‹[number, number, number]›*

**Returns:** *Array‹[number, number, number]›*

___

###  getCollisionType

▸ **getCollisionType**(): *[CollisionType](../enums/_lumin_.physics.collisiontype.md)*

**Returns:** *[CollisionType](../enums/_lumin_.physics.collisiontype.md)*

___

###  getPrismId

▸ **getPrismId**(): *BigInt*

*Inherited from [ServerEvent](_lumin_.serverevent.md).[getPrismId](_lumin_.serverevent.md#getprismid)*

**Returns:** *BigInt*

___

###  getRigidBody1

▸ **getRigidBody1**(): *BigInt*

**Returns:** *BigInt*

___

###  getRigidBody2

▸ **getRigidBody2**(): *BigInt*

**Returns:** *BigInt*

___

###  isInputEventType

▸ **isInputEventType**(): *boolean*

*Inherited from [ServerEvent](_lumin_.serverevent.md).[isInputEventType](_lumin_.serverevent.md#isinputeventtype)*

**Returns:** *boolean*

___

###  toString

▸ **toString**(): *string*

*Inherited from [ServerEvent](_lumin_.serverevent.md).[toString](_lumin_.serverevent.md#tostring)*

**Returns:** *string*