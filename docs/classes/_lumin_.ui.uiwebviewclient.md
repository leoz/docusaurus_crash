---
id: "_lumin_.ui.uiwebviewclient"
title: "lumin.ui.UiWebViewClient"
sidebar_label: "lumin.ui.UiWebViewClient"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [ui](../modules/_lumin_.ui.md) › [UiWebViewClient](_lumin_.ui.uiwebviewclient.md)

## Hierarchy

* **UiWebViewClient**

## Index

### Constructors

* [constructor](_lumin_.ui.uiwebviewclient.md#constructor)

### Methods

* [onBeforeResourceLoad](_lumin_.ui.uiwebviewclient.md#onbeforeresourceload)
* [onExternalProtocol](_lumin_.ui.uiwebviewclient.md#onexternalprotocol)
* [onLoadEnd](_lumin_.ui.uiwebviewclient.md#onloadend)
* [onLoadError](_lumin_.ui.uiwebviewclient.md#onloaderror)

## Constructors

###  constructor

\+ **new UiWebViewClient**(): *[UiWebViewClient](_lumin_.ui.uiwebviewclient.md)*

**Returns:** *[UiWebViewClient](_lumin_.ui.uiwebviewclient.md)*

## Methods

###  onBeforeResourceLoad

▸ **onBeforeResourceLoad**(`webview`: [UiWebView](_lumin_.ui.uiwebview.md), `resource_url`: string): *void*

**Parameters:**

Name | Type |
------ | ------ |
`webview` | [UiWebView](_lumin_.ui.uiwebview.md) |
`resource_url` | string |

**Returns:** *void*

___

###  onExternalProtocol

▸ **onExternalProtocol**(`webview`: [UiWebView](_lumin_.ui.uiwebview.md), `url`: string): *void*

**Parameters:**

Name | Type |
------ | ------ |
`webview` | [UiWebView](_lumin_.ui.uiwebview.md) |
`url` | string |

**Returns:** *void*

___

###  onLoadEnd

▸ **onLoadEnd**(`webview`: [UiWebView](_lumin_.ui.uiwebview.md), `is_main_frame`: boolean, `http_error_code`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`webview` | [UiWebView](_lumin_.ui.uiwebview.md) |
`is_main_frame` | boolean |
`http_error_code` | number |

**Returns:** *void*

___

###  onLoadError

▸ **onLoadError**(`webview`: [UiWebView](_lumin_.ui.uiwebview.md), `is_main_frame`: boolean, `error_code`: number, `error_str`: string, `failed_url`: string): *void*

**Parameters:**

Name | Type |
------ | ------ |
`webview` | [UiWebView](_lumin_.ui.uiwebview.md) |
`is_main_frame` | boolean |
`error_code` | number |
`error_str` | string |
`failed_url` | string |

**Returns:** *void*