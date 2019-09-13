---
id: "_lumin_.eyetrackingeventdata"
title: "lumin.EyeTrackingEventData"
sidebar_label: "lumin.EyeTrackingEventData"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [EyeTrackingEventData](_lumin_.eyetrackingeventdata.md)

## Hierarchy

* [ServerEvent](_lumin_.serverevent.md)

  ↳ **EyeTrackingEventData**

## Index

### Constructors

* [constructor](_lumin_.eyetrackingeventdata.md#constructor)

### Methods

* [getEyeTrackingFixationConfidence](_lumin_.eyetrackingeventdata.md#geteyetrackingfixationconfidence)
* [getEyeTrackingFixationPosition](_lumin_.eyetrackingeventdata.md#geteyetrackingfixationposition)
* [getEyeTrackingLeftEyeBlinkState](_lumin_.eyetrackingeventdata.md#geteyetrackinglefteyeblinkstate)
* [getEyeTrackingLeftEyeConfidence](_lumin_.eyetrackingeventdata.md#geteyetrackinglefteyeconfidence)
* [getEyeTrackingLeftEyePosition](_lumin_.eyetrackingeventdata.md#geteyetrackinglefteyeposition)
* [getEyeTrackingLeftEyeRotation](_lumin_.eyetrackingeventdata.md#geteyetrackinglefteyerotation)
* [getEyeTrackingRightEyeBlinkState](_lumin_.eyetrackingeventdata.md#geteyetrackingrighteyeblinkstate)
* [getEyeTrackingRightEyeConfidence](_lumin_.eyetrackingeventdata.md#geteyetrackingrighteyeconfidence)
* [getEyeTrackingRightEyePosition](_lumin_.eyetrackingeventdata.md#geteyetrackingrighteyeposition)
* [getEyeTrackingRightEyeRotation](_lumin_.eyetrackingeventdata.md#geteyetrackingrighteyerotation)
* [getPrismId](_lumin_.eyetrackingeventdata.md#getprismid)
* [hasFixationViolationOccured](_lumin_.eyetrackingeventdata.md#hasfixationviolationoccured)
* [isFixationDepthUnconfortable](_lumin_.eyetrackingeventdata.md#isfixationdepthunconfortable)
* [isInputEventType](_lumin_.eyetrackingeventdata.md#isinputeventtype)
* [remainingTimeAtUncomfortableDepth](_lumin_.eyetrackingeventdata.md#remainingtimeatuncomfortabledepth)
* [toString](_lumin_.eyetrackingeventdata.md#tostring)

## Constructors

###  constructor

\+ **new EyeTrackingEventData**(): *[EyeTrackingEventData](_lumin_.eyetrackingeventdata.md)*

*Overrides [ServerEvent](_lumin_.serverevent.md).[constructor](_lumin_.serverevent.md#constructor)*

**Returns:** *[EyeTrackingEventData](_lumin_.eyetrackingeventdata.md)*

## Methods

###  getEyeTrackingFixationConfidence

▸ **getEyeTrackingFixationConfidence**(): *number*

**Returns:** *number*

___

###  getEyeTrackingFixationPosition

▸ **getEyeTrackingFixationPosition**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getEyeTrackingLeftEyeBlinkState

▸ **getEyeTrackingLeftEyeBlinkState**(): *boolean*

**Returns:** *boolean*

___

###  getEyeTrackingLeftEyeConfidence

▸ **getEyeTrackingLeftEyeConfidence**(): *number*

**Returns:** *number*

___

###  getEyeTrackingLeftEyePosition

▸ **getEyeTrackingLeftEyePosition**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getEyeTrackingLeftEyeRotation

▸ **getEyeTrackingLeftEyeRotation**(): *[number, number, number, number]*

**Returns:** *[number, number, number, number]*

___

###  getEyeTrackingRightEyeBlinkState

▸ **getEyeTrackingRightEyeBlinkState**(): *boolean*

**Returns:** *boolean*

___

###  getEyeTrackingRightEyeConfidence

▸ **getEyeTrackingRightEyeConfidence**(): *number*

**Returns:** *number*

___

###  getEyeTrackingRightEyePosition

▸ **getEyeTrackingRightEyePosition**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getEyeTrackingRightEyeRotation

▸ **getEyeTrackingRightEyeRotation**(): *[number, number, number, number]*

**Returns:** *[number, number, number, number]*

___

###  getPrismId

▸ **getPrismId**(): *BigInt*

*Inherited from [ServerEvent](_lumin_.serverevent.md).[getPrismId](_lumin_.serverevent.md#getprismid)*

**Returns:** *BigInt*

___

###  hasFixationViolationOccured

▸ **hasFixationViolationOccured**(): *boolean*

**Returns:** *boolean*

___

###  isFixationDepthUnconfortable

▸ **isFixationDepthUnconfortable**(): *boolean*

**Returns:** *boolean*

___

###  isInputEventType

▸ **isInputEventType**(): *boolean*

*Inherited from [ServerEvent](_lumin_.serverevent.md).[isInputEventType](_lumin_.serverevent.md#isinputeventtype)*

**Returns:** *boolean*

___

###  remainingTimeAtUncomfortableDepth

▸ **remainingTimeAtUncomfortableDepth**(): *number*

**Returns:** *number*

___

###  toString

▸ **toString**(): *string*

*Inherited from [ServerEvent](_lumin_.serverevent.md).[toString](_lumin_.serverevent.md#tostring)*

**Returns:** *string*