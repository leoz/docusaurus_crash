---
id: "_lumin_.ui.keyboard"
title: "lumin.ui.Keyboard"
sidebar_label: "lumin.ui.Keyboard"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [ui](../modules/_lumin_.ui.md) › [Keyboard](_lumin_.ui.keyboard.md)

## Hierarchy

* **Keyboard**

## Index

### Constructors

* [constructor](_lumin_.ui.keyboard.md#constructor)

### Methods

* [hide](_lumin_.ui.keyboard.md#hide)
* [onVisibilityChangedSub](_lumin_.ui.keyboard.md#onvisibilitychangedsub)
* [onVisibilityChangedUnsub](_lumin_.ui.keyboard.md#onvisibilitychangedunsub)
* [show](_lumin_.ui.keyboard.md#show)
* [Get](_lumin_.ui.keyboard.md#static-get)

## Constructors

###  constructor

\+ **new Keyboard**(): *[Keyboard](_lumin_.ui.keyboard.md)*

**Returns:** *[Keyboard](_lumin_.ui.keyboard.md)*

## Methods

###  hide

▸ **hide**(): *void*

**Returns:** *void*

___

###  onVisibilityChangedSub

▸ **onVisibilityChangedSub**(`callback`: callable): *[CallbackID](_lumin_.utils.callbackid.md)*

**Parameters:**

Name | Type |
------ | ------ |
`callback` | callable |

**Returns:** *[CallbackID](_lumin_.utils.callbackid.md)*

___

###  onVisibilityChangedUnsub

▸ **onVisibilityChangedUnsub**(`callbackID`: [CallbackID](_lumin_.utils.callbackid.md)): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`callbackID` | [CallbackID](_lumin_.utils.callbackid.md) |

**Returns:** *boolean*

___

###  show

▸ **show**(`a_pClientVol`: [Prism](_lumin_.prism.md), `a_pLocaleCode`: [Code](../enums/_lumin_.ui.locale.code.md), `a_keyboardProperties`: [KeyboardProperties](_lumin_.ui.keyboardproperties.md), `a_eventHandler`: callable, `positionExtents`: [AABB](_lumin_.math.aabb.md)): *ui.Keyboard.ShowKeyboardReturnCode*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`a_pClientVol` | [Prism](_lumin_.prism.md) | - |
`a_pLocaleCode` | [Code](../enums/_lumin_.ui.locale.code.md) | - |
`a_keyboardProperties` | [KeyboardProperties](_lumin_.ui.keyboardproperties.md) | - |
`a_eventHandler` | callable | - |
`positionExtents` | [AABB](_lumin_.math.aabb.md) | 0 |

**Returns:** *ui.Keyboard.ShowKeyboardReturnCode*

___

### `Static` Get

▸ **Get**(): *[Keyboard](_lumin_.ui.keyboard.md)*

**Returns:** *[Keyboard](_lumin_.ui.keyboard.md)*