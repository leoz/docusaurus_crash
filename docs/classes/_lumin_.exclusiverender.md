---
id: "_lumin_.exclusiverender"
title: "lumin.ExclusiveRender"
sidebar_label: "lumin.ExclusiveRender"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [ExclusiveRender](_lumin_.exclusiverender.md)

## Hierarchy

* **ExclusiveRender**

## Index

### Constructors

* [constructor](_lumin_.exclusiverender.md#constructor)

### Methods

* [beginFrame](_lumin_.exclusiverender.md#beginframe)
* [endFrame](_lumin_.exclusiverender.md#endframe)
* [setFrameTimingHint](_lumin_.exclusiverender.md#setframetiminghint)
* [signalRenderComplete](_lumin_.exclusiverender.md#signalrendercomplete)

## Constructors

###  constructor

\+ **new ExclusiveRender**(): *[ExclusiveRender](_lumin_.exclusiverender.md)*

**Returns:** *[ExclusiveRender](_lumin_.exclusiverender.md)*

## Methods

###  beginFrame

▸ **beginFrame**(`params`: ExclusiveRender.FrameParams, `outFrameHandle`: ExclusiveRender.FrameInfo): *number*

**Parameters:**

Name | Type |
------ | ------ |
`params` | ExclusiveRender.FrameParams |
`outFrameHandle` | ExclusiveRender.FrameInfo |

**Returns:** *number*

___

###  endFrame

▸ **endFrame**(`frame`: ExclusiveRender.FrameInfo, `signalComplete`: boolean): *number*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`frame` | ExclusiveRender.FrameInfo | - |
`signalComplete` | boolean | 0 |

**Returns:** *number*

___

###  setFrameTimingHint

▸ **setFrameTimingHint**(`timing`: ExclusiveRender.FrameTimingHint): *number*

**Parameters:**

Name | Type |
------ | ------ |
`timing` | ExclusiveRender.FrameTimingHint |

**Returns:** *number*

___

###  signalRenderComplete

▸ **signalRenderComplete**(`frame`: ExclusiveRender.FrameInfo, `camIdx`: number): *number*

**Parameters:**

Name | Type |
------ | ------ |
`frame` | ExclusiveRender.FrameInfo |
`camIdx` | number |

**Returns:** *number*