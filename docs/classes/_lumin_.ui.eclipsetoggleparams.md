---
id: "_lumin_.ui.eclipsetoggleparams"
title: "lumin.ui.EclipseToggleParams"
sidebar_label: "lumin.ui.EclipseToggleParams"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [ui](../modules/_lumin_.ui.md) › [EclipseToggleParams](_lumin_.ui.eclipsetoggleparams.md)

## Hierarchy

* **EclipseToggleParams**

## Index

### Constructors

* [constructor](_lumin_.ui.eclipsetoggleparams.md#constructor)

### Properties

* [absoluteIconPath](_lumin_.ui.eclipsetoggleparams.md#absoluteiconpath)
* [height](_lumin_.ui.eclipsetoggleparams.md#height)
* [iconPath](_lumin_.ui.eclipsetoggleparams.md#iconpath)
* [iconScale](_lumin_.ui.eclipsetoggleparams.md#iconscale)
* [iconType](_lumin_.ui.eclipsetoggleparams.md#icontype)
* [iconTypeOffState](_lumin_.ui.eclipsetoggleparams.md#icontypeoffstate)
* [l10nKey](_lumin_.ui.eclipsetoggleparams.md#l10nkey)
* [l10nParams](_lumin_.ui.eclipsetoggleparams.md#l10nparams)
* [labelDisplayMode](_lumin_.ui.eclipsetoggleparams.md#labeldisplaymode)
* [labelSide](_lumin_.ui.eclipsetoggleparams.md#labelside)
* [labelText](_lumin_.ui.eclipsetoggleparams.md#labeltext)
* [showBackground](_lumin_.ui.eclipsetoggleparams.md#showbackground)
* [statusText1](_lumin_.ui.eclipsetoggleparams.md#statustext1)
* [statusText2](_lumin_.ui.eclipsetoggleparams.md#statustext2)
* [type](_lumin_.ui.eclipsetoggleparams.md#type)

## Constructors

###  constructor

\+ **new EclipseToggleParams**(`a_type`: [EclipseToggleType](../enums/_lumin_.ui.eclipsetoggletype.md), `a_iconPath`: string, `a_labelText`: string, `a_statusText1`: string, `a_statusText2`: string, `a_height`: number): *[EclipseToggleParams](_lumin_.ui.eclipsetoggleparams.md)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_type` | [EclipseToggleType](../enums/_lumin_.ui.eclipsetoggletype.md) | - |
`a_iconPath` | string | - |
`a_labelText` | string | 0 |
`a_statusText1` | string | 0 |
`a_statusText2` | string | 0 |
`a_height` | number | 0 |

**Returns:** *[EclipseToggleParams](_lumin_.ui.eclipsetoggleparams.md)*

\+ **new EclipseToggleParams**(`a_type`: [EclipseToggleType](../enums/_lumin_.ui.eclipsetoggletype.md), `a_iconPath`: string, `a_labelText`: string, `a_statusText1`: string, `a_statusText2`: string, `a_height`: number, `a_iconType`: [SystemIcon](../enums/_lumin_.ui.systemicon.md)): *[EclipseToggleParams](_lumin_.ui.eclipsetoggleparams.md)*

**Parameters:**

Name | Type |
------ | ------ |
`a_type` | [EclipseToggleType](../enums/_lumin_.ui.eclipsetoggletype.md) |
`a_iconPath` | string |
`a_labelText` | string |
`a_statusText1` | string |
`a_statusText2` | string |
`a_height` | number |
`a_iconType` | [SystemIcon](../enums/_lumin_.ui.systemicon.md) |

**Returns:** *[EclipseToggleParams](_lumin_.ui.eclipsetoggleparams.md)*

\+ **new EclipseToggleParams**(`a_type`: [EclipseToggleType](../enums/_lumin_.ui.eclipsetoggletype.md), `a_iconPath`: string, `a_labelText`: string, `a_statusText1`: string, `a_statusText2`: string, `a_height`: number, `a_iconType`: [SystemIcon](../enums/_lumin_.ui.systemicon.md), `a_iconTypeOffState`: [SystemIcon](../enums/_lumin_.ui.systemicon.md)): *[EclipseToggleParams](_lumin_.ui.eclipsetoggleparams.md)*

**Parameters:**

Name | Type |
------ | ------ |
`a_type` | [EclipseToggleType](../enums/_lumin_.ui.eclipsetoggletype.md) |
`a_iconPath` | string |
`a_labelText` | string |
`a_statusText1` | string |
`a_statusText2` | string |
`a_height` | number |
`a_iconType` | [SystemIcon](../enums/_lumin_.ui.systemicon.md) |
`a_iconTypeOffState` | [SystemIcon](../enums/_lumin_.ui.systemicon.md) |

**Returns:** *[EclipseToggleParams](_lumin_.ui.eclipsetoggleparams.md)*

\+ **new EclipseToggleParams**(`a_type`: [EclipseToggleType](../enums/_lumin_.ui.eclipsetoggletype.md), `a_iconType`: [SystemIcon](../enums/_lumin_.ui.systemicon.md), `a_labelText`: string, `a_statusText1`: string, `a_statusText2`: string, `a_height`: number): *[EclipseToggleParams](_lumin_.ui.eclipsetoggleparams.md)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_type` | [EclipseToggleType](../enums/_lumin_.ui.eclipsetoggletype.md) | - |
`a_iconType` | [SystemIcon](../enums/_lumin_.ui.systemicon.md) | - |
`a_labelText` | string | 0 |
`a_statusText1` | string | 0 |
`a_statusText2` | string | 0 |
`a_height` | number | 0 |

**Returns:** *[EclipseToggleParams](_lumin_.ui.eclipsetoggleparams.md)*

\+ **new EclipseToggleParams**(`a_type`: [EclipseToggleType](../enums/_lumin_.ui.eclipsetoggletype.md), `a_iconType`: [SystemIcon](../enums/_lumin_.ui.systemicon.md), `a_iconTypeOffState`: [SystemIcon](../enums/_lumin_.ui.systemicon.md), `a_labelText`: string, `a_statusText1`: string, `a_statusText2`: string, `a_height`: number): *[EclipseToggleParams](_lumin_.ui.eclipsetoggleparams.md)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_type` | [EclipseToggleType](../enums/_lumin_.ui.eclipsetoggletype.md) | - |
`a_iconType` | [SystemIcon](../enums/_lumin_.ui.systemicon.md) | - |
`a_iconTypeOffState` | [SystemIcon](../enums/_lumin_.ui.systemicon.md) | - |
`a_labelText` | string | 0 |
`a_statusText1` | string | 0 |
`a_statusText2` | string | 0 |
`a_height` | number | 0 |

**Returns:** *[EclipseToggleParams](_lumin_.ui.eclipsetoggleparams.md)*

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

###  iconTypeOffState

• **iconTypeOffState**: *[SystemIcon](../enums/_lumin_.ui.systemicon.md)*

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

###  showBackground

• **showBackground**: *boolean*

___

###  statusText1

• **statusText1**: *string*

___

###  statusText2

• **statusText2**: *string*

___

###  type

• **type**: *[EclipseToggleType](../enums/_lumin_.ui.eclipsetoggletype.md)*