---
UID: NF:shobjidl_core.IFolderFilter.GetEnumFlags
title: IFolderFilter::GetEnumFlags (shobjidl_core.h)
description: Allows a client to specify which classes of objects in a Shell folder should be enumerated. When used with SHBrowseForFolder, specifies the class or classes of items that should be shown in the dialog box tree view and which class or classes should not.
old-location: shell\IFolderFilter_GetEnumFlags.htm
tech.root: shell
ms.assetid: b02b103c-b82e-455b-9498-dfc387806c36
ms.date: 12/05/2018
ms.keywords: GetEnumFlags, GetEnumFlags method [Windows Shell], GetEnumFlags method [Windows Shell],IFolderFilter interface, IFolderFilter interface [Windows Shell],GetEnumFlags method, IFolderFilter.GetEnumFlags, IFolderFilter::GetEnumFlags, _shell_IFolderFilter_GetEnumFlags, shell.IFolderFilter_GetEnumFlags, shobjidl_core/IFolderFilter::GetEnumFlags
f1_keywords:
- shobjidl_core/IFolderFilter.GetEnumFlags
dev_langs:
- c++
req.header: shobjidl_core.h
req.include-header: Shobjidl.h
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Shobjidl.idl
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
- shobjidl_core.h
api_name:
- IFolderFilter.GetEnumFlags
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IFolderFilter::GetEnumFlags


## -description


Allows a client to specify which classes of objects in a Shell folder should be enumerated. When used with <a href="https://docs.microsoft.com/windows/desktop/api/shlobj_core/nf-shlobj_core-shbrowseforfoldera">SHBrowseForFolder</a>, specifies the class or classes of items that should be shown in the dialog box tree view and which class or classes should not.


## -parameters




### -param psf [in]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nn-shobjidl_core-ishellfolder">IShellFolder</a>*</b>

A pointer to the folder's <a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nn-shobjidl_core-ishellfolder">IShellFolder</a> interface.


### -param pidlFolder [in]

Type: <b>PCIDLIST_ABSOLUTE </b>

The PIDL of the folder.


### -param phwnd [in]

Type: <b>HWND*</b>

A pointer to the host's window handle.


### -param pgrfFlags [out]

Type: <b>DWORD*</b>

One or more <a href="https://docs.microsoft.com/windows/win32/api/shobjidl_core/ne-shobjidl_core-_shcontf">SHCONTF</a> values that specify the classes of object to enumerate.


## -returns



Type: <b>HRESULT</b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nn-shobjidl_core-ifolderfilter">IFolderFilter</a>
 

 

