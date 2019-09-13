---
id: "_lumin_.glyph.kerning.pair"
title: "lumin.glyph.kerning.Pair"
sidebar_label: "lumin.glyph.kerning.Pair"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [glyph](../modules/_lumin_.glyph.md) › [kerning](../modules/_lumin_.glyph.kerning.md) › [Pair](_lumin_.glyph.kerning.pair.md)

## Hierarchy

* **Pair**

## Index

### Constructors

* [constructor](_lumin_.glyph.kerning.pair.md#constructor)

### Properties

* [NONE](_lumin_.glyph.kerning.pair.md#none)
* [character](_lumin_.glyph.kerning.pair.md#character)
* [previous](_lumin_.glyph.kerning.pair.md#previous)

### Methods

* [equals](_lumin_.glyph.kerning.pair.md#equals)
* [toString](_lumin_.glyph.kerning.pair.md#tostring)
* [IsNone](_lumin_.glyph.kerning.pair.md#static-isnone)

## Constructors

###  constructor

\+ **new Pair**(`prev`: number, `code`: number): *[Pair](_lumin_.glyph.kerning.pair.md)*

**Parameters:**

Name | Type |
------ | ------ |
`prev` | number |
`code` | number |

**Returns:** *[Pair](_lumin_.glyph.kerning.pair.md)*

## Properties

###  NONE

• **NONE**: *[number, number]* =  [0,0]

___

###  character

• **character**: *number*

___

###  previous

• **previous**: *number*

## Methods

###  equals

▸ **equals**(`rhs`: [Pair](_lumin_.glyph.kerning.pair.md)): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`rhs` | [Pair](_lumin_.glyph.kerning.pair.md) |

**Returns:** *boolean*

___

###  toString

▸ **toString**(`assumeAscii`: boolean): *string*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`assumeAscii` | boolean | 0 |

**Returns:** *string*

___

### `Static` IsNone

▸ **IsNone**(`vector`: [number, number]): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`vector` | [number, number] |

**Returns:** *boolean*