---
UID: NE:fsrmenums._FsrmPropertyValueType
title: FsrmPropertyValueType (fsrmenums.h)
description: Enumerates the type of the value being assigned to an FSRM property in a property condition.
old-location: fsrm\fsrmpropertyvaluetype.htm
tech.root: fsrm
ms.assetid: 557183b3-aaeb-42d3-b7e0-72fc17f1205b
ms.date: 12/05/2018
ms.keywords: FsrmPropertyValueType, FsrmPropertyValueType enumeration [File Server Resource Manager], FsrmPropertyValueType_DateOffset, FsrmPropertyValueType_Literal, FsrmPropertyValueType_Undefined, fs.fsrmpropertyvaluetype, fsrm.fsrmpropertyvaluetype, fsrmenums/FsrmPropertyValueType, fsrmenums/FsrmPropertyValueType_DateOffset, fsrmenums/FsrmPropertyValueType_Literal, fsrmenums/FsrmPropertyValueType_Undefined
f1_keywords:
- fsrmenums/FsrmPropertyValueType
dev_langs:
- c++
req.header: fsrmenums.h
req.include-header: FsrmPipeline.h, FsrmQuota.h, FsrmReports.h, FsrmScreen.h
req.target-type: Windows
req.target-min-winverclnt: None supported
req.target-min-winversvr: Windows Server 2012
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: FsrmEnums.idl
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
- HeaderDef
api_location:
- FsrmEnums.h
api_name:
- FsrmPropertyValueType
targetos: Windows
req.typenames: FsrmPropertyValueType
req.redist: 
ms.custom: 19H1
---

# FsrmPropertyValueType enumeration


## -description


Enumerates the type of the value being assigned to an FSRM property in a property 
    condition.


## -enum-fields




### -field FsrmPropertyValueType_Undefined

The type assigned to the property value is not defined.


### -field FsrmPropertyValueType_Literal

The type assigned to the property value is one or more literal values.


### -field FsrmPropertyValueType_DateOffset

The type assigned to the property value is a date expression containing a date variable and an optional 
      date offset.


## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/fsrm/fsrm-enumerations">FSRM Enumerations</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/fsrmreports/nf-fsrmreports-ifsrmfileconditionproperty-get_valuetype">IFsrmFileConditionProperty.ValueType</a>
 

 

