---
id: "_lumin_.controltouchpadinputeventdata"
title: "lumin.ControlTouchPadInputEventData"
sidebar_label: "lumin.ControlTouchPadInputEventData"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [ControlTouchPadInputEventData](_lumin_.controltouchpadinputeventdata.md)

## Hierarchy

  ↳ [InputEventData](_lumin_.inputeventdata.md)

  ↳ **ControlTouchPadInputEventData**

## Index

### Constructors

* [constructor](_lumin_.controltouchpadinputeventdata.md#constructor)

### Methods

* [getDeviceId](_lumin_.controltouchpadinputeventdata.md#getdeviceid)
* [getEventSource](_lumin_.controltouchpadinputeventdata.md#geteventsource)
* [getEventType](_lumin_.controltouchpadinputeventdata.md#geteventtype)
* [getPrismId](_lumin_.controltouchpadinputeventdata.md#getprismid)
* [getTouch](_lumin_.controltouchpadinputeventdata.md#gettouch)
* [getTouchCount](_lumin_.controltouchpadinputeventdata.md#gettouchcount)
* [getTouchState](_lumin_.controltouchpadinputeventdata.md#gettouchstate)
* [isInputEventType](_lumin_.controltouchpadinputeventdata.md#isinputeventtype)
* [isMultiTouch](_lumin_.controltouchpadinputeventdata.md#ismultitouch)
* [toString](_lumin_.controltouchpadinputeventdata.md#tostring)

## Constructors

###  constructor

\+ **new ControlTouchPadInputEventData**(): *[ControlTouchPadInputEventData](_lumin_.controltouchpadinputeventdata.md)*

*Overrides [InputEventData](_lumin_.inputeventdata.md).[constructor](_lumin_.inputeventdata.md#constructor)*

**Returns:** *[ControlTouchPadInputEventData](_lumin_.controltouchpadinputeventdata.md)*

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