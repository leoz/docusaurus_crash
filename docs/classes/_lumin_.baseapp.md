---
id: "_lumin_.baseapp"
title: "lumin.BaseApp"
sidebar_label: "lumin.BaseApp"
---

[magic-script-typings](../index.md) › [&quot;lumin&quot;](../modules/_lumin_.md) › [BaseApp](_lumin_.baseapp.md)

## Hierarchy

* **BaseApp**

  ↳ [ImmersiveApp](_lumin_.immersiveapp.md)

  ↳ [LandscapeApp](_lumin_.landscapeapp.md)

## Index

### Constructors

* [constructor](_lumin_.baseapp.md#constructor)

### Methods

* [checkPrivilege](_lumin_.baseapp.md#checkprivilege)
* [deInit](_lumin_.baseapp.md#deinit)
* [deletePrism](_lumin_.baseapp.md#deleteprism)
* [dismissAllNotifications](_lumin_.baseapp.md#dismissallnotifications)
* [dismissNotification](_lumin_.baseapp.md#dismissnotification)
* [eventListener](_lumin_.baseapp.md#eventlistener)
* [getComponentName](_lumin_.baseapp.md#getcomponentname)
* [getCurrentLocaleHelper](_lumin_.baseapp.md#getcurrentlocalehelper)
* [getFloorHeight](_lumin_.baseapp.md#getfloorheight)
* [getHeadposeConfidence](_lumin_.baseapp.md#getheadposeconfidence)
* [getHeadposeError](_lumin_.baseapp.md#getheadposeerror)
* [getHeadposeMode](_lumin_.baseapp.md#getheadposemode)
* [getHeadposeWorldForwardVector](_lumin_.baseapp.md#getheadposeworldforwardvector)
* [getHeadposeWorldPosition](_lumin_.baseapp.md#getheadposeworldposition)
* [getHeadposeWorldUpVector](_lumin_.baseapp.md#getheadposeworldupvector)
* [getLocaleCode](_lumin_.baseapp.md#getlocalecode)
* [getPackageName](_lumin_.baseapp.md#getpackagename)
* [getPackagePath](_lumin_.baseapp.md#getpackagepath)
* [getPreloadedResources](_lumin_.baseapp.md#getpreloadedresources)
* [getPrism](_lumin_.baseapp.md#getprism)
* [getPrismPosition](_lumin_.baseapp.md#getprismposition)
* [getPrismRotation](_lumin_.baseapp.md#getprismrotation)
* [getPrismTransform](_lumin_.baseapp.md#getprismtransform)
* [getTempPath](_lumin_.baseapp.md#gettemppath)
* [getVisibleName](_lumin_.baseapp.md#getvisiblename)
* [getWritablePath](_lumin_.baseapp.md#getwritablepath)
* [getWritablePathWhenUnlocked](_lumin_.baseapp.md#getwritablepathwhenunlocked)
* [isImageTrackingReady](_lumin_.baseapp.md#isimagetrackingready)
* [isShareableApp](_lumin_.baseapp.md#isshareableapp)
* [lockCurrentLocaleHelperToLocale](_lumin_.baseapp.md#lockcurrentlocalehelpertolocale)
* [onAppPause](_lumin_.baseapp.md#onapppause)
* [onAppResume](_lumin_.baseapp.md#onappresume)
* [onAppStart](_lumin_.baseapp.md#onappstart)
* [onAppUnloadResources](_lumin_.baseapp.md#onappunloadresources)
* [onDeviceActive](_lumin_.baseapp.md#ondeviceactive)
* [onDeviceReality](_lumin_.baseapp.md#ondevicereality)
* [onDeviceStandby](_lumin_.baseapp.md#ondevicestandby)
* [onSharingStart](_lumin_.baseapp.md#onsharingstart)
* [onSharingStop](_lumin_.baseapp.md#onsharingstop)
* [orientPrism](_lumin_.baseapp.md#orientprism)
* [orientPrismRelativeToCamera](_lumin_.baseapp.md#orientprismrelativetocamera)
* [positionPrism](_lumin_.baseapp.md#positionprism)
* [positionPrismRelativeToCamera](_lumin_.baseapp.md#positionprismrelativetocamera)
* [postNotification](_lumin_.baseapp.md#postnotification)
* [quit](_lumin_.baseapp.md#quit)
* [raycastNodes](_lumin_.baseapp.md#raycastnodes)
* [registerOnLocaleChangedCallback](_lumin_.baseapp.md#registeronlocalechangedcallback)
* [requestPrivilege](_lumin_.baseapp.md#requestprivilege)
* [requestPrivilegeBlocking](_lumin_.baseapp.md#requestprivilegeblocking)
* [requestWorldPlaneCast](_lumin_.baseapp.md#requestworldplanecast)
* [requestWorldRayCast](_lumin_.baseapp.md#requestworldraycast)
* [resizePrism](_lumin_.baseapp.md#resizeprism)
* [setEventSleepTime](_lumin_.baseapp.md#seteventsleeptime)
* [stopTrackImage](_lumin_.baseapp.md#stoptrackimage)
* [trackMovingImage](_lumin_.baseapp.md#trackmovingimage)
* [trackStaticImage](_lumin_.baseapp.md#trackstaticimage)
* [triggerControlBodyHaptics](_lumin_.baseapp.md#triggercontrolbodyhaptics)
* [triggerControlCustomHaptic](_lumin_.baseapp.md#triggercontrolcustomhaptic)
* [triggerControlCustomHaptics](_lumin_.baseapp.md#triggercontrolcustomhaptics)
* [triggerControlHaptic](_lumin_.baseapp.md#triggercontrolhaptic)
* [triggerControlLEDHaptics](_lumin_.baseapp.md#triggercontrolledhaptics)
* [unlockCurrentLocaleHelper](_lumin_.baseapp.md#unlockcurrentlocalehelper)
* [unregisterOnLocaleChangedCallback](_lumin_.baseapp.md#unregisteronlocalechangedcallback)
* [updateLoop](_lumin_.baseapp.md#updateloop)
* [waitForTermination](_lumin_.baseapp.md#waitfortermination)

## Constructors

###  constructor

\+ **new BaseApp**(): *[BaseApp](_lumin_.baseapp.md)*

**Returns:** *[BaseApp](_lumin_.baseapp.md)*

## Methods

###  checkPrivilege

▸ **checkPrivilege**(`privilegeId`: [PrivilegeId](../enums/_lumin_.privilegeid.md)): *[PrivilegeResult](../enums/_lumin_.privilegeresult.md)*

**Parameters:**

Name | Type |
------ | ------ |
`privilegeId` | [PrivilegeId](../enums/_lumin_.privilegeid.md) |

**Returns:** *[PrivilegeResult](../enums/_lumin_.privilegeresult.md)*

___

###  deInit

▸ **deInit**(): *number*

**Returns:** *number*

___

###  deletePrism

▸ **deletePrism**(`prism`: [Prism](_lumin_.prism.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`prism` | [Prism](_lumin_.prism.md) |

**Returns:** *void*

___

###  dismissAllNotifications

▸ **dismissAllNotifications**(): *void*

**Returns:** *void*

___

###  dismissNotification

▸ **dismissNotification**(`notification`: [Notification](_lumin_.notification.md)): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`notification` | [Notification](_lumin_.notification.md) |

**Returns:** *boolean*

___

###  eventListener

▸ **eventListener**(`a_pEvent`: [ServerEvent](_lumin_.serverevent.md)): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`a_pEvent` | [ServerEvent](_lumin_.serverevent.md) |

**Returns:** *boolean*

___

###  getComponentName

▸ **getComponentName**(): *string*

**Returns:** *string*

___

###  getCurrentLocaleHelper

▸ **getCurrentLocaleHelper**(): *[LocaleHelper](_lumin_.utils.localehelper.md)*

**Returns:** *[LocaleHelper](_lumin_.utils.localehelper.md)*

___

###  getFloorHeight

▸ **getFloorHeight**(): *number*

**Returns:** *number*

___

###  getHeadposeConfidence

▸ **getHeadposeConfidence**(): *number*

**Returns:** *number*

___

###  getHeadposeError

▸ **getHeadposeError**(): *[Error](../enums/_lumin_.headtracking.error.md)*

**Returns:** *[Error](../enums/_lumin_.headtracking.error.md)*

___

###  getHeadposeMode

▸ **getHeadposeMode**(): *[Mode](../enums/_lumin_.headtracking.mode.md)*

**Returns:** *[Mode](../enums/_lumin_.headtracking.mode.md)*

___

###  getHeadposeWorldForwardVector

▸ **getHeadposeWorldForwardVector**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getHeadposeWorldPosition

▸ **getHeadposeWorldPosition**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getHeadposeWorldUpVector

▸ **getHeadposeWorldUpVector**(): *[number, number, number]*

**Returns:** *[number, number, number]*

___

###  getLocaleCode

▸ **getLocaleCode**(): *string*

**Returns:** *string*

___

###  getPackageName

▸ **getPackageName**(): *string*

**Returns:** *string*

___

###  getPackagePath

▸ **getPackagePath**(): *string*

**Returns:** *string*

___

###  getPreloadedResources

▸ **getPreloadedResources**(): *[Preloaded](_lumin_.resources.preloaded.md)*

**Returns:** *[Preloaded](_lumin_.resources.preloaded.md)*

___

###  getPrism

▸ **getPrism**(`prismId`: BigInt): *[Prism](_lumin_.prism.md)*

**Parameters:**

Name | Type |
------ | ------ |
`prismId` | BigInt |

**Returns:** *[Prism](_lumin_.prism.md)*

___

###  getPrismPosition

▸ **getPrismPosition**(`a_prism`: [Prism](_lumin_.prism.md)): *[number, number, number]*

**Parameters:**

Name | Type |
------ | ------ |
`a_prism` | [Prism](_lumin_.prism.md) |

**Returns:** *[number, number, number]*

___

###  getPrismRotation

▸ **getPrismRotation**(`a_prism`: [Prism](_lumin_.prism.md)): *[number, number, number, number]*

**Parameters:**

Name | Type |
------ | ------ |
`a_prism` | [Prism](_lumin_.prism.md) |

**Returns:** *[number, number, number, number]*

___

###  getPrismTransform

▸ **getPrismTransform**(`a_prism`: [Prism](_lumin_.prism.md)): *[number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]*

**Parameters:**

Name | Type |
------ | ------ |
`a_prism` | [Prism](_lumin_.prism.md) |

**Returns:** *[number, number, number, number, number, number, number, number, number, number, number, number, number, number, number, number]*

___

###  getTempPath

▸ **getTempPath**(): *string*

**Returns:** *string*

___

###  getVisibleName

▸ **getVisibleName**(): *string*

**Returns:** *string*

___

###  getWritablePath

▸ **getWritablePath**(): *string*

**Returns:** *string*

___

###  getWritablePathWhenUnlocked

▸ **getWritablePathWhenUnlocked**(): *string*

**Returns:** *string*

___

###  isImageTrackingReady

▸ **isImageTrackingReady**(): *boolean*

**Returns:** *boolean*

___

###  isShareableApp

▸ **isShareableApp**(): *boolean*

**Returns:** *boolean*

___

###  lockCurrentLocaleHelperToLocale

▸ **lockCurrentLocaleHelperToLocale**(`localeCode`: string): *void*

**Parameters:**

Name | Type |
------ | ------ |
`localeCode` | string |

**Returns:** *void*

___

###  onAppPause

▸ **onAppPause**(): *void*

**Returns:** *void*

___

###  onAppResume

▸ **onAppResume**(): *void*

**Returns:** *void*

___

###  onAppStart

▸ **onAppStart**(`initArg`: [InitArg](_lumin_.initarg.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`initArg` | [InitArg](_lumin_.initarg.md) |

**Returns:** *void*

___

###  onAppUnloadResources

▸ **onAppUnloadResources**(): *void*

**Returns:** *void*

___

###  onDeviceActive

▸ **onDeviceActive**(): *void*

**Returns:** *void*

___

###  onDeviceReality

▸ **onDeviceReality**(): *void*

**Returns:** *void*

___

###  onDeviceStandby

▸ **onDeviceStandby**(): *void*

**Returns:** *void*

___

###  onSharingStart

▸ **onSharingStart**(`sessionId`: BigInt, `sceneGraphIDs`: Array‹BigInt›): *void*

**Parameters:**

Name | Type |
------ | ------ |
`sessionId` | BigInt |
`sceneGraphIDs` | Array‹BigInt› |

**Returns:** *void*

___

###  onSharingStop

▸ **onSharingStop**(`sessionId`: BigInt): *void*

**Parameters:**

Name | Type |
------ | ------ |
`sessionId` | BigInt |

**Returns:** *void*

___

###  orientPrism

▸ **orientPrism**(`a_prism`: [Prism](_lumin_.prism.md), `a_orientation`: [number, number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_prism` | [Prism](_lumin_.prism.md) |
`a_orientation` | [number, number, number, number] |

**Returns:** *void*

___

###  orientPrismRelativeToCamera

▸ **orientPrismRelativeToCamera**(`a_prism`: [Prism](_lumin_.prism.md), `a_orientation`: [number, number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_prism` | [Prism](_lumin_.prism.md) |
`a_orientation` | [number, number, number, number] |

**Returns:** *void*

___

###  positionPrism

▸ **positionPrism**(`a_prism`: [Prism](_lumin_.prism.md), `a_position`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_prism` | [Prism](_lumin_.prism.md) |
`a_position` | [number, number, number] |

**Returns:** *void*

___

###  positionPrismRelativeToCamera

▸ **positionPrismRelativeToCamera**(`a_prism`: [Prism](_lumin_.prism.md), `a_position`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_prism` | [Prism](_lumin_.prism.md) |
`a_position` | [number, number, number] |

**Returns:** *void*

___

###  postNotification

▸ **postNotification**(`notification`: [Notification](_lumin_.notification.md)): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`notification` | [Notification](_lumin_.notification.md) |

**Returns:** *boolean*

___

###  quit

▸ **quit**(): *void*

**Returns:** *void*

___

###  raycastNodes

▸ **raycastNodes**(`a_prism`: [Prism](_lumin_.prism.md), `a_rayStart`: [number, number, number], `a_rayEnd`: [number, number, number]): *[RayCastResultLight](_lumin_.raycastresultlight.md)*

**Parameters:**

Name | Type |
------ | ------ |
`a_prism` | [Prism](_lumin_.prism.md) |
`a_rayStart` | [number, number, number] |
`a_rayEnd` | [number, number, number] |

**Returns:** *[RayCastResultLight](_lumin_.raycastresultlight.md)*

___

###  registerOnLocaleChangedCallback

▸ **registerOnLocaleChangedCallback**(`callbackFunction`: callable): *[CallbackID](_lumin_.utils.callbackid.md)*

**Parameters:**

Name | Type |
------ | ------ |
`callbackFunction` | callable |

**Returns:** *[CallbackID](_lumin_.utils.callbackid.md)*

___

###  requestPrivilege

▸ **requestPrivilege**(`privilegeId`: [PrivilegeId](../enums/_lumin_.privilegeid.md)): *void*

**Parameters:**

Name | Type |
------ | ------ |
`privilegeId` | [PrivilegeId](../enums/_lumin_.privilegeid.md) |

**Returns:** *void*

___

###  requestPrivilegeBlocking

▸ **requestPrivilegeBlocking**(`privilegeId`: [PrivilegeId](../enums/_lumin_.privilegeid.md)): *[PrivilegeResult](../enums/_lumin_.privilegeresult.md)*

**Parameters:**

Name | Type |
------ | ------ |
`privilegeId` | [PrivilegeId](../enums/_lumin_.privilegeid.md) |

**Returns:** *[PrivilegeResult](../enums/_lumin_.privilegeresult.md)*

___

###  requestWorldPlaneCast

▸ **requestWorldPlaneCast**(`center`: [number, number, number], `maxDistance`: number, `maxPlaneCount`: number, `flags`: [PlanecastFlags](../enums/_lumin_.planecastflags.md), `userValue`: BigInt): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`center` | [number, number, number] |
`maxDistance` | number |
`maxPlaneCount` | number |
`flags` | [PlanecastFlags](../enums/_lumin_.planecastflags.md) |
`userValue` | BigInt |

**Returns:** *boolean*

___

###  requestWorldRayCast

▸ **requestWorldRayCast**(`rayStart`: [number, number, number], `rayDir`: [number, number, number], `userValue`: BigInt, `confidenceThreshold`: number): *boolean*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`rayStart` | [number, number, number] | - |
`rayDir` | [number, number, number] | - |
`userValue` | BigInt | - |
`confidenceThreshold` | number | 0 |

**Returns:** *boolean*

▸ **requestWorldRayCast**(`rayStart`: [number, number, number], `rayDir`: [number, number, number], `width`: number, `height`: number, `horizFovDeg`: number, `userValue`: BigInt, `confidenceThreshold`: number): *boolean*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`rayStart` | [number, number, number] | - |
`rayDir` | [number, number, number] | - |
`width` | number | - |
`height` | number | - |
`horizFovDeg` | number | - |
`userValue` | BigInt | - |
`confidenceThreshold` | number | 0 |

**Returns:** *boolean*

___

###  resizePrism

▸ **resizePrism**(`a_prism`: [Prism](_lumin_.prism.md), `a_size`: [number, number, number]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_prism` | [Prism](_lumin_.prism.md) |
`a_size` | [number, number, number] |

**Returns:** *void*

___

###  setEventSleepTime

▸ **setEventSleepTime**(`a_fSleepTime`: number): *void*

**Parameters:**

Name | Type |
------ | ------ |
`a_fSleepTime` | number |

**Returns:** *void*

___

###  stopTrackImage

▸ **stopTrackImage**(`imageName`: string): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`imageName` | string |

**Returns:** *boolean*

___

###  trackMovingImage

▸ **trackMovingImage**(`imageName`: string, `dimensions`: [number, number], `file`: string, `prism`: [Prism](_lumin_.prism.md)): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`imageName` | string |
`dimensions` | [number, number] |
`file` | string |
`prism` | [Prism](_lumin_.prism.md) |

**Returns:** *boolean*

___

###  trackStaticImage

▸ **trackStaticImage**(`imageName`: string, `dimensions`: [number, number], `file`: string, `prism`: [Prism](_lumin_.prism.md)): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`imageName` | string |
`dimensions` | [number, number] |
`file` | string |
`prism` | [Prism](_lumin_.prism.md) |

**Returns:** *boolean*

___

###  triggerControlBodyHaptics

▸ **triggerControlBodyHaptics**(`pattern`: [VibePattern](../enums/_lumin_.haptics.vibepattern.md), `duration`: number, `intensity`: [VibeIntensity](../enums/_lumin_.haptics.vibeintensity.md), `controlID`: number, `deviceID`: number): *void*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`pattern` | [VibePattern](../enums/_lumin_.haptics.vibepattern.md) | - |
`duration` | number | 0 |
`intensity` | [VibeIntensity](../enums/_lumin_.haptics.vibeintensity.md) | 0 |
`controlID` | number | 0 |
`deviceID` | number | 0 |

**Returns:** *void*

___

###  triggerControlCustomHaptic

▸ **triggerControlCustomHaptic**(`haptic`: [HapticInfo](_lumin_.hapticinfo.md), `controlID`: number, `deviceID`: number): *void*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`haptic` | [HapticInfo](_lumin_.hapticinfo.md) | - |
`controlID` | number | 0 |
`deviceID` | number | 0 |

**Returns:** *void*

___

###  triggerControlCustomHaptics

▸ **triggerControlCustomHaptics**(`haptics`: Array‹[HapticInfo](_lumin_.hapticinfo.md)›, `controlID`: number, `deviceID`: number): *void*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`haptics` | Array‹[HapticInfo](_lumin_.hapticinfo.md)› | - |
`controlID` | number | 0 |
`deviceID` | number | 0 |

**Returns:** *void*

___

###  triggerControlHaptic

▸ **triggerControlHaptic**(`haptic`: [VibePattern](../enums/_lumin_.haptics.vibepattern.md), `controlID`: number, `deviceID`: number): *void*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`haptic` | [VibePattern](../enums/_lumin_.haptics.vibepattern.md) | - |
`controlID` | number | 0 |
`deviceID` | number | 0 |

**Returns:** *void*

▸ **triggerControlHaptic**(`haptic`: [LedPattern](../enums/_lumin_.haptics.ledpattern.md), `controlID`: number, `deviceID`: number): *void*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`haptic` | [LedPattern](../enums/_lumin_.haptics.ledpattern.md) | - |
`controlID` | number | 0 |
`deviceID` | number | 0 |

**Returns:** *void*

___

###  triggerControlLEDHaptics

▸ **triggerControlLEDHaptics**(`pattern`: [LedPattern](../enums/_lumin_.haptics.ledpattern.md), `duration`: number, `intensity`: [VibeIntensity](../enums/_lumin_.haptics.vibeintensity.md), `controlID`: number, `deviceID`: number): *void*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`pattern` | [LedPattern](../enums/_lumin_.haptics.ledpattern.md) | - |
`duration` | number | 0 |
`intensity` | [VibeIntensity](../enums/_lumin_.haptics.vibeintensity.md) | 0 |
`controlID` | number | 0 |
`deviceID` | number | 0 |

**Returns:** *void*

___

###  unlockCurrentLocaleHelper

▸ **unlockCurrentLocaleHelper**(): *void*

**Returns:** *void*

___

###  unregisterOnLocaleChangedCallback

▸ **unregisterOnLocaleChangedCallback**(`callbackID`: [CallbackID](_lumin_.utils.callbackid.md)): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`callbackID` | [CallbackID](_lumin_.utils.callbackid.md) |

**Returns:** *boolean*

___

###  updateLoop

▸ **updateLoop**(`a_fDelta`: number): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`a_fDelta` | number |

**Returns:** *boolean*

___

###  waitForTermination

▸ **waitForTermination**(): *void*

**Returns:** *void*