---
title: Kernel-Mode Debugging in Visual Studio
description: To perform kernel-mode debugging in Microsoft Visual Studio
keywords: ["kernel-mode debugging visual studio"]
ms.date: 05/11/2018
---

# <span id="debugger.performing_kernel-mode_debugging_using_visual_studio"></span>Kernel-Mode Debugging in Visual Studio

> [!IMPORTANT]
> This feature is not available in Windows 10, version 1507 and later versions of the WDK.
>


To perform kernel-mode debugging in Microsoft Visual Studio:

1.  On the host computer, in Visual Studio, from the **Tools** Menu, choose **Attach to Process**.
2.  In the **Attach to Process** dialog box, set **Transport** to **Windows Kernel Mode Debugger**, and set **Qualifier** to the name of a previously configured target computer. For information about configuring a target computer, see [Setting Up Kernel-Mode Debugging in Visual Studio](setting-up-kernel-mode-debugging-in-visual-studio.md) or [Setting Up Kernel-Mode Debugging Manually](setting-up-kernel-mode-debugging-in-windbg--cdb--or-ntsd.md).
3.  Click **Attach.**

## <span id="related_topics"></span>Related topics


[Debugging Using Visual Studio](debugging-using-visual-studio.md)

 

 






