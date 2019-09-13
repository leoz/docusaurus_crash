---
id: "_lumin_.inputdeviceevent"
title: "lumin.InputDeviceEvent"
sidebar_label: "lumin.InputDeviceEvent"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [InputDeviceEvent](_lumin_.inputdeviceevent.md)

## Hierarchy

* [ServerEvent](_lumin_.serverevent.md)

  ↳ **InputDeviceEvent**

## Index

### Constructors

* [constructor](_lumin_.inputdeviceevent.md#constructor)

### Methods

* [getDeviceId](_lumin_.inputdeviceevent.md#getdeviceid)
* [getEventType](_lumin_.inputdeviceevent.md#geteventtype)
* [getPrismId](_lumin_.inputdeviceevent.md#getprismid)
* [getSource](_lumin_.inputdeviceevent.md#getsource)
* [isConnected](_lumin_.inputdeviceevent.md#isconnected)
* [isInputEventType](_lumin_.inputdeviceevent.md#isinputeventtype)
* [toString](_lumin_.inputdeviceevent.md#tostring)

## Constructors

###  constructor

\+ **new InputDeviceEvent**(): *[InputDeviceEvent](_lumin_.inputdeviceevent.md)*

*Overrides [ServerEvent](_lumin_.serverevent.md).[constructor](_lumin_.serverevent.md#constructor)*

**Returns:** *[InputDeviceEvent](_lumin_.inputdeviceevent.md)*

## Methods

###  getDeviceId

▸ **getDeviceId**(): *number*

**Returns:** *number*

___

###  getEventType

▸ **getEventType**(): *[DeviceEventType](../enums/_lumin_.input.deviceeventtype.md)*

**Returns:** *[DeviceEventType](../enums/_lumin_.input.deviceeventtype.md)*

___

###  getPrismId

▸ **getPrismId**(): *BigInt*

*Inherited from [ServerEvent](_lumin_.serverevent.md).[getPrismId](_lumin_.serverevent.md#getprismid)*

**Returns:** *BigInt*

___

###  getSource

▸ **getSource**(): *[EventSource](../enums/_lumin_.input.eventsource.md)*

**Returns:** *[EventSource](../enums/_lumin_.input.eventsource.md)*

___

###  isConnected

▸ **isConnected**(): *boolean*

**Returns:** *boolean*

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