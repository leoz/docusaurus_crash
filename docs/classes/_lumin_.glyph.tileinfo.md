---
id: "_lumin_.glyph.tileinfo"
title: "lumin.glyph.TileInfo"
sidebar_label: "lumin.glyph.TileInfo"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [glyph](../modules/_lumin_.glyph.md) › [TileInfo](_lumin_.glyph.tileinfo.md)

## Hierarchy

* **TileInfo**

## Index

### Constructors

* [constructor](_lumin_.glyph.tileinfo.md#constructor)

### Properties

* [NO_TILE](_lumin_.glyph.tileinfo.md#no_tile)
* [charCode](_lumin_.glyph.tileinfo.md#charcode)
* [layerIndex](_lumin_.glyph.tileinfo.md#layerindex)
* [metrics](_lumin_.glyph.tileinfo.md#metrics)
* [texMaxCoord](_lumin_.glyph.tileinfo.md#texmaxcoord)
* [texMinCoord](_lumin_.glyph.tileinfo.md#texmincoord)
* [textureId](_lumin_.glyph.tileinfo.md#textureid)
* [textureSize](_lumin_.glyph.tileinfo.md#texturesize)

## Constructors

###  constructor

\+ **new TileInfo**(`code`: number, `texId`: number, `layer`: number, `texMin`: [number, number], `texMax`: [number, number], `size`: [TextureSize](../enums/_lumin_.glyph.texturesize.md), `mt`: [Metrics](_lumin_.glyph.metrics.md)): *[TileInfo](_lumin_.glyph.tileinfo.md)*

**Parameters:**

Name | Type |
------ | ------ |
`code` | number |
`texId` | number |
`layer` | number |
`texMin` | [number, number] |
`texMax` | [number, number] |
`size` | [TextureSize](../enums/_lumin_.glyph.texturesize.md) |
`mt` | [Metrics](_lumin_.glyph.metrics.md) |

**Returns:** *[TileInfo](_lumin_.glyph.tileinfo.md)*

## Properties

###  NO_TILE

• **NO_TILE**: *[TileInfo](_lumin_.glyph.tileinfo.md)* =  TileInfo(NUL_CHAR,0,0,[],[],TextureSize.kNormal,Metrics())

___

###  charCode

• **charCode**: *number*

___

###  layerIndex

• **layerIndex**: *number*

___

###  metrics

• **metrics**: *[Metrics](_lumin_.glyph.metrics.md)*

___

###  texMaxCoord

• **texMaxCoord**: *[number, number]*

___

###  texMinCoord

• **texMinCoord**: *[number, number]*

___

###  textureId

• **textureId**: *number*

___

###  textureSize

• **textureSize**: *[TextureSize](../enums/_lumin_.glyph.texturesize.md)*