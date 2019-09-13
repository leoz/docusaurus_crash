---
id: "_lumin_.inputeventdata"
title: "lumin.InputEventData"
sidebar_label: "lumin.InputEventData"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [InputEventData](_lumin_.inputeventdata.md)

## Hierarchy

* [ServerEvent](_lumin_.serverevent.md)

  ↳ **InputEventData**

  ↳ [ControlPose3DofInputEventData](_lumin_.controlpose3dofinputeventdata.md)

  ↳ [ControlPose6DofInputEventData](_lumin_.controlpose6dofinputeventdata.md)

  ↳ [ControlTouchPadInputEventData](_lumin_.controltouchpadinputeventdata.md)

  ↳ [GestureInputEventData](_lumin_.gestureinputeventdata.md)

  ↳ [KeyInputEventData](_lumin_.keyinputeventdata.md)

## Index

### Constructors

* [constructor](_lumin_.inputeventdata.md#constructor)

### Methods

* [getDeviceId](_lumin_.inputeventdata.md#getdeviceid)
* [getEventSource](_lumin_.inputeventdata.md#geteventsource)
* [getEventType](_lumin_.inputeventdata.md#geteventtype)
* [getPrismId](_lumin_.inputeventdata.md#getprismid)
* [isInputEventType](_lumin_.inputeventdata.md#isinputeventtype)
* [toString](_lumin_.inputeventdata.md#tostring)

## Constructors

###  constructor

\+ **new InputEventData**(): *[InputEventData](_lumin_.inputeventdata.md)*

*Overrides [ServerEvent](_lumin_.serverevent.md).[constructor](_lumin_.serverevent.md#constructor)*

**Returns:** *[InputEventData](_lumin_.inputeventdata.md)*

## Methods

###  getDeviceId

▸ **getDeviceId**(): *number*

**Returns:** *number*

___

###  getEventSource

▸ **getEventSource**(): *[EventSource](../enums/_lumin_.input.eventsource.md)*

**Returns:** *[EventSource](../enums/_lumin_.input.eventsource.md)*

___

###  getEventType

▸ **getEventType**(): *[EventType](../enums/_lumin_.input.eventtype.md)*

**Returns:** *[EventType](../enums/_lumin_.input.eventtype.md)*

___

###  getPrismId

▸ **getPrismId**(): *BigInt*

*Inherited from [ServerEvent](_lumin_.serverevent.md).[getPrismId](_lumin_.serverevent.md#getprismid)*

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