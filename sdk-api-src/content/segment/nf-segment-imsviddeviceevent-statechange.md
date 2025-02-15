---
UID: NF:segment.IMSVidDeviceEvent.StateChange
title: IMSVidDeviceEvent::StateChange (segment.h)
description: This topic applies to Windows XP or later.
old-location: mstv\imsviddeviceevent_statechange.htm
tech.root: mstv
ms.assetid: 0f7a5e37-5a0d-415e-aca0-df5f9448b017
ms.date: 12/05/2018
ms.keywords: IMSVidDeviceEvent interface [Microsoft TV Technologies],StateChange method, IMSVidDeviceEvent.StateChange, IMSVidDeviceEvent::StateChange, IMSVidDeviceEventStateChange, StateChange, StateChange method [Microsoft TV Technologies], StateChange method [Microsoft TV Technologies],IMSVidDeviceEvent interface, mstv.imsviddeviceevent_statechange, segment/IMSVidDeviceEvent::StateChange
f1_keywords:
- segment/IMSVidDeviceEvent.StateChange
dev_langs:
- c++
req.header: segment.h
req.include-header: Msvidctl.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Segment.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- segment.h
api_name:
- IMSVidDeviceEvent.StateChange
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IMSVidDeviceEvent::StateChange


## -description



This topic applies to Windows XP or later.
        



The <b>StateChange</b> method signals that the state of the device has changed.


## -parameters




### -param lpd [in]

Pointer to the device object that signaled the change.


### -param oldState [in]

Specifies the old state as an <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/msvidctl/ne-msvidctl-msvidctlstatelist">MSVidCtlStateList</a> value.


### -param newState [in]

Specifies the new state as an <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/msvidctl/ne-msvidctl-msvidctlstatelist">MSVidCtlStateList</a> value.


## -returns



If the method succeeds, it returns S_OK. If it fails, it returns an error code.




## -remarks



The dispatch identifier (dispid) of this method is <b>eventidStateChange</b>.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/segment/nn-segment-imsviddeviceevent">IMSVidDeviceEvent</a>
 

 

