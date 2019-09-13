---
id: "_lumin_.multipack.descriptor"
title: "lumin.multipack.Descriptor"
sidebar_label: "lumin.multipack.Descriptor"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [multipack](../modules/_lumin_.multipack.md) › [Descriptor](_lumin_.multipack.descriptor.md)

## Hierarchy

* **Descriptor**

## Index

### Constructors

* [constructor](_lumin_.multipack.descriptor.md#constructor)

### Methods

* [empty](_lumin_.multipack.descriptor.md#empty)
* [getLocation](_lumin_.multipack.descriptor.md#getlocation)
* [getParams](_lumin_.multipack.descriptor.md#getparams)
* [getSheetCount](_lumin_.multipack.descriptor.md#getsheetcount)
* [getSheets](_lumin_.multipack.descriptor.md#getsheets)
* [getSubTextureCount](_lumin_.multipack.descriptor.md#getsubtexturecount)
* [getSubTextures](_lumin_.multipack.descriptor.md#getsubtextures)
* [Assemble](_lumin_.multipack.descriptor.md#static-assemble)

## Constructors

###  constructor

\+ **new Descriptor**(): *[Descriptor](_lumin_.multipack.descriptor.md)*

**Returns:** *[Descriptor](_lumin_.multipack.descriptor.md)*

\+ **new Descriptor**(`location`: string, `sheets`: Array‹[SheetFiles](_lumin_.multipack.sheetfiles.md)›, `subTextures`: Array‹[SubTexture](_lumin_.multipack.subtexture.md)›, `params`: [Params](_lumin_.multipack.params.md)): *[Descriptor](_lumin_.multipack.descriptor.md)*

**Parameters:**

Name | Type |
------ | ------ |
`location` | string |
`sheets` | Array‹[SheetFiles](_lumin_.multipack.sheetfiles.md)› |
`subTextures` | Array‹[SubTexture](_lumin_.multipack.subtexture.md)› |
`params` | [Params](_lumin_.multipack.params.md) |

**Returns:** *[Descriptor](_lumin_.multipack.descriptor.md)*

## Methods

###  empty

▸ **empty**(): *boolean*

**Returns:** *boolean*

___

###  getLocation

▸ **getLocation**(): *string*

**Returns:** *string*

___

###  getParams

▸ **getParams**(): *[Params](_lumin_.multipack.params.md)*

**Returns:** *[Params](_lumin_.multipack.params.md)*

___

###  getSheetCount

▸ **getSheetCount**(): *number*

**Returns:** *number*

___

###  getSheets

▸ **getSheets**(): *Array‹[SheetFiles](_lumin_.multipack.sheetfiles.md)›*

**Returns:** *Array‹[SheetFiles](_lumin_.multipack.sheetfiles.md)›*

___

###  getSubTextureCount

▸ **getSubTextureCount**(): *number*

**Returns:** *number*

___

###  getSubTextures

▸ **getSubTextures**(): *Array‹[SubTexture](_lumin_.multipack.subtexture.md)›*

**Returns:** *Array‹[SubTexture](_lumin_.multipack.subtexture.md)›*

___

### `Static` Assemble

▸ **Assemble**(`directory`: string, `params`: [Params](_lumin_.multipack.params.md)): *[Descriptor](_lumin_.multipack.descriptor.md)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`directory` | string | - |
`params` | [Params](_lumin_.multipack.params.md) | 0 |

**Returns:** *[Descriptor](_lumin_.multipack.descriptor.md)*

▸ **Assemble**(`vMetaDataNames`: Array‹string›, `params`: [Params](_lumin_.multipack.params.md)): *[Descriptor](_lumin_.multipack.descriptor.md)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`vMetaDataNames` | Array‹string› | - |
`params` | [Params](_lumin_.multipack.params.md) | 0 |

**Returns:** *[Descriptor](_lumin_.multipack.descriptor.md)*