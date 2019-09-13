---
id: "_lumin_.math.aabb"
title: "lumin.math.AABB"
sidebar_label: "lumin.math.AABB"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [math](../modules/_lumin_.math.md) › [AABB](_lumin_.math.aabb.md)

## Hierarchy

* **AABB**

## Index

### Constructors

* [constructor](_lumin_.math.aabb.md#constructor)

### Properties

* [EMPTY](_lumin_.math.aabb.md#empty)

### Methods

* [contains](_lumin_.math.aabb.md#contains)
* [extend](_lumin_.math.aabb.md#extend)
* [getCenter](_lumin_.math.aabb.md#getcenter)
* [getDepth](_lumin_.math.aabb.md#getdepth)
* [getExtents](_lumin_.math.aabb.md#getextents)
* [getHeight](_lumin_.math.aabb.md#getheight)
* [getMax](_lumin_.math.aabb.md#getmax)
* [getMin](_lumin_.math.aabb.md#getmin)
* [getWidth](_lumin_.math.aabb.md#getwidth)
* [intersect](_lumin_.math.aabb.md#intersect)
* [isEmpty](_lumin_.math.aabb.md#isempty)
* [isValid](_lumin_.math.aabb.md#isvalid)
* [isZeroSize](_lumin_.math.aabb.md#iszerosize)
* [isZeroVolume](_lumin_.math.aabb.md#iszerovolume)
* [setMax](_lumin_.math.aabb.md#setmax)
* [setMin](_lumin_.math.aabb.md#setmin)
* [toString](_lumin_.math.aabb.md#tostring)
* [transform](_lumin_.math.aabb.md#transform)
* [translate](_lumin_.math.aabb.md#translate)

## Constructors

###  constructor

\+ **new AABB**(): *[AABB](_lumin_.math.aabb.md)*

**Returns:** *[AABB](_lumin_.math.aabb.md)*

\+ **new AABB**(`min`: [number, number, number], `max`: [number, number, number]): *[AABB](_lumin_.math.aabb.md)*

**Parameters:**

Name | Type |
------ | ------ |
`min` | [number, number, number] |
`max` | [number, number, number] |

**Returns:** *[AABB](_lumin_.math.aabb.md)*

## Properties

###  EMPTY

• **EMPTY**: *[AABB](_lumin_.math.aabb.md)* =  AABB()

## Methods

###  contains

▸ **contains**(`point`: [number, number, number]): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`point` | [number, number, number] |

**Returns:** *boolean*

___

###  extend

▸ **extend**(`other`: [AABB](_lumin_.math.aabb.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`other` | [AABB](_lumin_.math.aabb.md) |

**Returns:** *void*

▸ **extend**(`point`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`point` | [number, number, number] |

**Returns:** *void*

___

###  getCenter

▸ **getCenter**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getDepth

▸ **getDepth**(): *number*

**Returns:** *number*

___

###  getExtents

▸ **getExtents**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getHeight

▸ **getHeight**(): *number*

**Returns:** *number*

___

###  getMax

▸ **getMax**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getMin

▸ **getMin**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getWidth

▸ **getWidth**(): *number*

**Returns:** *number*

___

###  intersect

▸ **intersect**(`rayOri`: [number, number, number], `rayDir`: [number, number, number]): *number*

**Parameters:**

Name | Type |
------ | ------ |
`rayOri` | [number, number, number] |
`rayDir` | [number, number, number] |

**Returns:** *number*

___

###  isEmpty

▸ **isEmpty**(): *boolean*

**Returns:** *boolean*

___

###  isValid

▸ **isValid**(): *boolean*

**Returns:** *boolean*

___

###  isZeroSize

▸ **isZeroSize**(): *boolean*

**Returns:** *boolean*

___

###  isZeroVolume

▸ **isZeroVolume**(): *boolean*

**Returns:** *boolean*

___

###  setMax

▸ **setMax**(`max`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`max` | [number, number, number] |

**Returns:** *void*

___

###  setMin

▸ **setMin**(`min`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`min` | [number, number, number] |

**Returns:** *void*

___

###  toString

▸ **toString**(): *string*

**Returns:** *string*

___

###  transform

▸ **transform**(`transform`: [number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`transform` | [number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number] |

**Returns:** *void*

___

###  translate

▸ **translate**(`offset`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`offset` | [number, number, number] |

**Returns:** *void*