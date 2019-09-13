---
id: "_lumin_.gestureinputeventdata"
title: "lumin.GestureInputEventData"
sidebar_label: "lumin.GestureInputEventData"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [GestureInputEventData](_lumin_.gestureinputeventdata.md)

## Hierarchy

  ↳ [InputEventData](_lumin_.inputeventdata.md)

  ↳ **GestureInputEventData**

## Index

### Constructors

* [constructor](_lumin_.gestureinputeventdata.md#constructor)

### Methods

* [getDeviceId](_lumin_.gestureinputeventdata.md#getdeviceid)
* [getEventSource](_lumin_.gestureinputeventdata.md#geteventsource)
* [getEventType](_lumin_.gestureinputeventdata.md#geteventtype)
* [getGesture](_lumin_.gestureinputeventdata.md#getgesture)
* [getGestureAngle](_lumin_.gestureinputeventdata.md#getgestureangle)
* [getGestureDirection](_lumin_.gestureinputeventdata.md#getgesturedirection)
* [getGestureDistance](_lumin_.gestureinputeventdata.md#getgesturedistance)
* [getGestureFingerGap](_lumin_.gestureinputeventdata.md#getgesturefingergap)
* [getGestureForceValue](_lumin_.gestureinputeventdata.md#getgestureforcevalue)
* [getGestureKeyPoseConfidence](_lumin_.gestureinputeventdata.md#getgesturekeyposeconfidence)
* [getGestureLocation](_lumin_.gestureinputeventdata.md#getgesturelocation)
* [getGestureRadius](_lumin_.gestureinputeventdata.md#getgestureradius)
* [getGestureSpeed](_lumin_.gestureinputeventdata.md#getgesturespeed)
* [getHandConfidence](_lumin_.gestureinputeventdata.md#gethandconfidence)
* [getHandGestureConfidence](_lumin_.gestureinputeventdata.md#gethandgestureconfidence)
* [getHandGestureIndex](_lumin_.gestureinputeventdata.md#gethandgestureindex)
* [getHandGestureKeyPointCount](_lumin_.gestureinputeventdata.md#gethandgesturekeypointcount)
* [getHandGestureKeyPoseConfidence](_lumin_.gestureinputeventdata.md#gethandgesturekeyposeconfidence)
* [getHandGestureKeypoint](_lumin_.gestureinputeventdata.md#gethandgesturekeypoint)
* [getHandGestureLocation](_lumin_.gestureinputeventdata.md#gethandgesturelocation)
* [getPrismId](_lumin_.gestureinputeventdata.md#getprismid)
* [getTouch](_lumin_.gestureinputeventdata.md#gettouch)
* [getTouchCount](_lumin_.gestureinputeventdata.md#gettouchcount)
* [getTouchState](_lumin_.gestureinputeventdata.md#gettouchstate)
* [isHandGestureKeypointRecognized](_lumin_.gestureinputeventdata.md#ishandgesturekeypointrecognized)
* [isInputEventType](_lumin_.gestureinputeventdata.md#isinputeventtype)
* [isMultiTouch](_lumin_.gestureinputeventdata.md#ismultitouch)
* [toString](_lumin_.gestureinputeventdata.md#tostring)

## Constructors

###  constructor

\+ **new GestureInputEventData**(): *[GestureInputEventData](_lumin_.gestureinputeventdata.md)*

*Overrides [InputEventData](_lumin_.inputeventdata.md).[constructor](_lumin_.inputeventdata.md#constructor)*

**Returns:** *[GestureInputEventData](_lumin_.gestureinputeventdata.md)*

## Methods

###  getDeviceId

▸ **getDeviceId**(): *number*

*Inherited from [InputEventData](_lumin_.inputeventdata.md).[getDeviceId](_lumin_.inputeventdata.md#getdeviceid)*

**Returns:** *number*

___

###  getEventSource

▸ **getEventSource**(): *[EventSource](../enums/_lumin_.input.eventsource.md)*

*Inherited from [InputEventData](_lumin_.inputeventdata.md).[getEventSource](_lumin_.inputeventdata.md#geteventsource)*

**Returns:** *[EventSource](../enums/_lumin_.input.eventsource.md)*

___

###  getEventType

▸ **getEventType**(): *[EventType](../enums/_lumin_.input.eventtype.md)*

*Inherited from [InputEventData](_lumin_.inputeventdata.md).[getEventType](_lumin_.inputeventdata.md#geteventtype)*

**Returns:** *[EventType](../enums/_lumin_.input.eventtype.md)*

___

###  getGesture

▸ **getGesture**(): *[GestureType](../enums/_lumin_.input.gesturetype.md)*

**Returns:** *[GestureType](../enums/_lumin_.input.gesturetype.md)*

___

###  getGestureAngle

▸ **getGestureAngle**(): *number*

**Returns:** *number*

___

###  getGestureDirection

▸ **getGestureDirection**(): *[GestureDirection](../enums/_lumin_.input.gesturedirection.md)*

**Returns:** *[GestureDirection](../enums/_lumin_.input.gesturedirection.md)*

___

###  getGestureDistance

▸ **getGestureDistance**(): *number*

**Returns:** *number*

___

###  getGestureFingerGap

▸ **getGestureFingerGap**(): *number*

**Returns:** *number*

___

###  getGestureForceValue

▸ **getGestureForceValue**(): *number*

**Returns:** *number*

___

###  getGestureKeyPoseConfidence

▸ **getGestureKeyPoseConfidence**(`gesture`: [GestureType](../enums/_lumin_.input.gesturetype.md)): *number*

**Parameters:**

Name | Type |
------ | ------ |
`gesture` | [GestureType](../enums/_lumin_.input.gesturetype.md) |

**Returns:** *number*

___

###  getGestureLocation

▸ **getGestureLocation**(): *[number, number]*

**Returns:** *[number, number]*

___

###  getGestureRadius

▸ **getGestureRadius**(): *number*

**Returns:** *number*

___

###  getGestureSpeed

▸ **getGestureSpeed**(): *number*

**Returns:** *number*

___

###  getHandConfidence

▸ **getHandConfidence**(): *number*

**Returns:** *number*

___

###  getHandGestureConfidence

▸ **getHandGestureConfidence**(): *number*

**Returns:** *number*

___

###  getHandGestureIndex

▸ **getHandGestureIndex**(): *number*

**Returns:** *number*

___

###  getHandGestureKeyPointCount

▸ **getHandGestureKeyPointCount**(): *number*

**Returns:** *number*

___

###  getHandGestureKeyPoseConfidence

▸ **getHandGestureKeyPoseConfidence**(`gesture`: [GestureType](../enums/_lumin_.input.gesturetype.md)): *number*

**Parameters:**

Name | Type |
------ | ------ |
`gesture` | [GestureType](../enums/_lumin_.input.gesturetype.md) |

**Returns:** *number*

___

###  getHandGestureKeypoint

▸ **getHandGestureKeypoint**(`keypointName`: [HandGestureKeypointName](../enums/_lumin_.input.handgesturekeypointname.md)): *[number, number, number]*

**Parameters:**

Name | Type |
------ | ------ |
`keypointName` | [HandGestureKeypointName](../enums/_lumin_.input.handgesturekeypointname.md) |

**Returns:** *[number, number, number]*

___

###  getHandGestureLocation

▸ **getHandGestureLocation**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getPrismId

▸ **getPrismId**(): *BigInt*

*Inherited from [ServerEvent](_lumin_.serverevent.md).[getPrismId](_lumin_.serverevent.md#getprismid)*

**Returns:** *BigInt*

___

###  getTouch

▸ **getTouch**(`tidx`: number): *[number, number, number]*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`tidx` | number | 0 |

**Returns:** *[number, number, number]*

___

###  getTouchCount

▸ **getTouchCount**(): *number*

**Returns:** *number*

___

###  getTouchState

▸ **getTouchState**(): *boolean*

**Returns:** *boolean*

___

###  isHandGestureKeypointRecognized

▸ **isHandGestureKeypointRecognized**(`keypointName`: [HandGestureKeypointName](../enums/_lumin_.input.handgesturekeypointname.md)): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`keypointName` | [HandGestureKeypointName](../enums/_lumin_.input.handgesturekeypointname.md) |

**Returns:** *boolean*

___

###  isInputEventType

▸ **isInputEventType**(): *boolean*

*Inherited from [ServerEvent](_lumin_.serverevent.md).[isInputEventType](_lumin_.serverevent.md#isinputeventtype)*

**Returns:** *boolean*

___

###  isMultiTouch

▸ **isMultiTouch**(): *boolean*

**Returns:** *boolean*

___

###  toString

▸ **toString**(): *string*

*Inherited from [ServerEvent](_lumin_.serverevent.md).[toString](_lumin_.serverevent.md#tostring)*

**Returns:** *string*