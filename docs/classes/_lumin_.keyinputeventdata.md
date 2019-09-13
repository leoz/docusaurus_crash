---
id: "_lumin_.keyinputeventdata"
title: "lumin.KeyInputEventData"
sidebar_label: "lumin.KeyInputEventData"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [KeyInputEventData](_lumin_.keyinputeventdata.md)

## Hierarchy

  ↳ [InputEventData](_lumin_.inputeventdata.md)

  ↳ **KeyInputEventData**

## Index

### Constructors

* [constructor](_lumin_.keyinputeventdata.md#constructor)

### Methods

* [getDeviceId](_lumin_.keyinputeventdata.md#getdeviceid)
* [getEventSource](_lumin_.keyinputeventdata.md#geteventsource)
* [getEventType](_lumin_.keyinputeventdata.md#geteventtype)
* [getPrismId](_lumin_.keyinputeventdata.md#getprismid)
* [isInputEventType](_lumin_.keyinputeventdata.md#isinputeventtype)
* [keyCode](_lumin_.keyinputeventdata.md#keycode)
* [keyVal](_lumin_.keyinputeventdata.md#keyval)
* [metaKeys](_lumin_.keyinputeventdata.md#metakeys)
* [toString](_lumin_.keyinputeventdata.md#tostring)

## Constructors

###  constructor

\+ **new KeyInputEventData**(): *[KeyInputEventData](_lumin_.keyinputeventdata.md)*

*Overrides [InputEventData](_lumin_.inputeventdata.md).[constructor](_lumin_.inputeventdata.md#constructor)*

**Returns:** *[KeyInputEventData](_lumin_.keyinputeventdata.md)*

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

###  isInputEventType

▸ **isInputEventType**(): *boolean*

*Inherited from [ServerEvent](_lumin_.serverevent.md).[isInputEventType](_lumin_.serverevent.md#isinputeventtype)*

**Returns:** *boolean*

___

###  keyCode

▸ **keyCode**(): *[KeyCodes](../enums/_lumin_.input.keycodes.md)*

**Returns:** *[KeyCodes](../enums/_lumin_.input.keycodes.md)*

___

###  keyVal

▸ **keyVal**(): *number*

**Returns:** *number*

___

###  metaKeys

▸ **metaKeys**(): *number*

**Returns:** *number*

___

###  toString

▸ **toString**(): *string*

*Inherited from [ServerEvent](_lumin_.serverevent.md).[toString](_lumin_.serverevent.md#tostring)*

**Returns:** *string*