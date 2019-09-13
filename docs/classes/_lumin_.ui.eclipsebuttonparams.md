---
id: "_lumin_.ui.eclipsebuttonparams"
title: "lumin.ui.EclipseButtonParams"
sidebar_label: "lumin.ui.EclipseButtonParams"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [ui](../modules/_lumin_.ui.md) › [EclipseButtonParams](_lumin_.ui.eclipsebuttonparams.md)

## Hierarchy

* **EclipseButtonParams**

## Index

### Constructors

* [constructor](_lumin_.ui.eclipsebuttonparams.md#constructor)

### Properties

* [absoluteIconPath](_lumin_.ui.eclipsebuttonparams.md#absoluteiconpath)
* [height](_lumin_.ui.eclipsebuttonparams.md#height)
* [iconPath](_lumin_.ui.eclipsebuttonparams.md#iconpath)
* [iconScale](_lumin_.ui.eclipsebuttonparams.md#iconscale)
* [iconType](_lumin_.ui.eclipsebuttonparams.md#icontype)
* [l10nKey](_lumin_.ui.eclipsebuttonparams.md#l10nkey)
* [l10nParams](_lumin_.ui.eclipsebuttonparams.md#l10nparams)
* [labelDisplayMode](_lumin_.ui.eclipsebuttonparams.md#labeldisplaymode)
* [labelSide](_lumin_.ui.eclipsebuttonparams.md#labelside)
* [labelText](_lumin_.ui.eclipsebuttonparams.md#labeltext)
* [outlineButton](_lumin_.ui.eclipsebuttonparams.md#outlinebutton)
* [type](_lumin_.ui.eclipsebuttonparams.md#type)
* [width](_lumin_.ui.eclipsebuttonparams.md#width)

## Constructors

###  constructor

\+ **new EclipseButtonParams**(`a_type`: [EclipseButtonType](../enums/_lumin_.ui.eclipsebuttontype.md)): *[EclipseButtonParams](_lumin_.ui.eclipsebuttonparams.md)*

**Parameters:**

Name | Type |
------ | ------ |
`a_type` | [EclipseButtonType](../enums/_lumin_.ui.eclipsebuttontype.md) |

**Returns:** *[EclipseButtonParams](_lumin_.ui.eclipsebuttonparams.md)*

\+ **new EclipseButtonParams**(`a_type`: [EclipseButtonType](../enums/_lumin_.ui.eclipsebuttontype.md), `a_pathOrText`: string, `a_height`: number): *[EclipseButtonParams](_lumin_.ui.eclipsebuttonparams.md)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_type` | [EclipseButtonType](../enums/_lumin_.ui.eclipsebuttontype.md) | - |
`a_pathOrText` | string | - |
`a_height` | number | 0 |

**Returns:** *[EclipseButtonParams](_lumin_.ui.eclipsebuttonparams.md)*

\+ **new EclipseButtonParams**(`a_type`: [EclipseButtonType](../enums/_lumin_.ui.eclipsebuttontype.md), `a_iconPath`: string, `a_labelText`: string, `a_height`: number): *[EclipseButtonParams](_lumin_.ui.eclipsebuttonparams.md)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_type` | [EclipseButtonType](../enums/_lumin_.ui.eclipsebuttontype.md) | - |
`a_iconPath` | string | - |
`a_labelText` | string | - |
`a_height` | number | 0 |

**Returns:** *[EclipseButtonParams](_lumin_.ui.eclipsebuttonparams.md)*

\+ **new EclipseButtonParams**(`a_type`: [EclipseButtonType](../enums/_lumin_.ui.eclipsebuttontype.md), `a_iconPath`: string, `a_labelText`: string, `a_labelSide`: [Side](../enums/_lumin_.ui.side.md), `a_height`: number): *[EclipseButtonParams](_lumin_.ui.eclipsebuttonparams.md)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_type` | [EclipseButtonType](../enums/_lumin_.ui.eclipsebuttontype.md) | - |
`a_iconPath` | string | - |
`a_labelText` | string | - |
`a_labelSide` | [Side](../enums/_lumin_.ui.side.md) | - |
`a_height` | number | 0 |

**Returns:** *[EclipseButtonParams](_lumin_.ui.eclipsebuttonparams.md)*

\+ **new EclipseButtonParams**(`a_type`: [EclipseButtonType](../enums/_lumin_.ui.eclipsebuttontype.md), `a_iconPath`: string, `a_labelText`: string, `a_labelSide`: [Side](../enums/_lumin_.ui.side.md), `a_height`: number, `iconType`: [SystemIcon](../enums/_lumin_.ui.systemicon.md)): *[EclipseButtonParams](_lumin_.ui.eclipsebuttonparams.md)*

**Parameters:**

Name | Type |
------ | ------ |
`a_type` | [EclipseButtonType](../enums/_lumin_.ui.eclipsebuttontype.md) |
`a_iconPath` | string |
`a_labelText` | string |
`a_labelSide` | [Side](../enums/_lumin_.ui.side.md) |
`a_height` | number |
`iconType` | [SystemIcon](../enums/_lumin_.ui.systemicon.md) |

**Returns:** *[EclipseButtonParams](_lumin_.ui.eclipsebuttonparams.md)*

\+ **new EclipseButtonParams**(`a_type`: [EclipseButtonType](../enums/_lumin_.ui.eclipsebuttontype.md), `a_iconType`: [SystemIcon](../enums/_lumin_.ui.systemicon.md), `a_labelText`: string, `a_labelSide`: [Side](../enums/_lumin_.ui.side.md), `a_height`: number): *[EclipseButtonParams](_lumin_.ui.eclipsebuttonparams.md)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_type` | [EclipseButtonType](../enums/_lumin_.ui.eclipsebuttontype.md) | - |
`a_iconType` | [SystemIcon](../enums/_lumin_.ui.systemicon.md) | - |
`a_labelText` | string | - |
`a_labelSide` | [Side](../enums/_lumin_.ui.side.md) | - |
`a_height` | number | 0 |

**Returns:** *[EclipseButtonParams](_lumin_.ui.eclipsebuttonparams.md)*

\+ **new EclipseButtonParams**(`a_type`: [EclipseButtonType](../enums/_lumin_.ui.eclipsebuttontype.md), `a_iconType`: [SystemIcon](../enums/_lumin_.ui.systemicon.md), `a_height`: number): *[EclipseButtonParams](_lumin_.ui.eclipsebuttonparams.md)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_type` | [EclipseButtonType](../enums/_lumin_.ui.eclipsebuttontype.md) | - |
`a_iconType` | [SystemIcon](../enums/_lumin_.ui.systemicon.md) | - |
`a_height` | number | 0 |

**Returns:** *[EclipseButtonParams](_lumin_.ui.eclipsebuttonparams.md)*

## Properties

###  absoluteIconPath

• **absoluteIconPath**: *boolean*

___

###  height

• **height**: *number*

___

###  iconPath

• **iconPath**: *string*

___

###  iconScale

• **iconScale**: *number*

___

###  iconType

• **iconType**: *[SystemIcon](../enums/_lumin_.ui.systemicon.md)*

___

###  l10nKey

• **l10nKey**: *string*

___

###  l10nParams

• **l10nParams**: *Object*

___

###  labelDisplayMode

• **labelDisplayMode**: *[LabelDisplayMode](../enums/_lumin_.ui.labeldisplaymode.md)*

___

###  labelSide

• **labelSide**: *[Side](../enums/_lumin_.ui.side.md)*

___

###  labelText

• **labelText**: *string*

___

###  outlineButton

• **outlineButton**: *boolean*

___

###  type

• **type**: *[EclipseButtonType](../enums/_lumin_.ui.eclipsebuttontype.md)*

___

###  width

• **width**: *number*