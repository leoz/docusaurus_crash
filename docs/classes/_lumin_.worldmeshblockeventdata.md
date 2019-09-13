---
id: "_lumin_.worldmeshblockeventdata"
title: "lumin.WorldMeshBlockEventData"
sidebar_label: "lumin.WorldMeshBlockEventData"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [WorldMeshBlockEventData](_lumin_.worldmeshblockeventdata.md)

## Hierarchy

* [ServerEvent](_lumin_.serverevent.md)

  ↳ **WorldMeshBlockEventData**

## Index

### Constructors

* [constructor](_lumin_.worldmeshblockeventdata.md#constructor)

### Methods

* [getBlockId](_lumin_.worldmeshblockeventdata.md#getblockid)
* [getData](_lumin_.worldmeshblockeventdata.md#getdata)
* [getPrismId](_lumin_.worldmeshblockeventdata.md#getprismid)
* [getUpdateType](_lumin_.worldmeshblockeventdata.md#getupdatetype)
* [isInputEventType](_lumin_.worldmeshblockeventdata.md#isinputeventtype)
* [toString](_lumin_.worldmeshblockeventdata.md#tostring)

## Constructors

###  constructor

\+ **new WorldMeshBlockEventData**(): *[WorldMeshBlockEventData](_lumin_.worldmeshblockeventdata.md)*

*Overrides [ServerEvent](_lumin_.serverevent.md).[constructor](_lumin_.serverevent.md#constructor)*

**Returns:** *[WorldMeshBlockEventData](_lumin_.worldmeshblockeventdata.md)*

## Methods

###  getBlockId

▸ **getBlockId**(): *WorldMeshBlockData.Id*

**Returns:** *WorldMeshBlockData.Id*

___

###  getData

▸ **getData**(): *[WorldMeshBlockData](_lumin_.worldmeshblockdata.md)*

**Returns:** *[WorldMeshBlockData](_lumin_.worldmeshblockdata.md)*

___

###  getPrismId

▸ **getPrismId**(): *BigInt*

*Inherited from [ServerEvent](_lumin_.serverevent.md).[getPrismId](_lumin_.serverevent.md#getprismid)*

**Returns:** *BigInt*

___

###  getUpdateType

▸ **getUpdateType**(): *[MeshBlockUpdate](../enums/_lumin_.densemesh.meshblockupdate.md)*

**Returns:** *[MeshBlockUpdate](../enums/_lumin_.densemesh.meshblockupdate.md)*

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