---
title: Sample NDIS Miniport Drivers
description: Sample NDIS Miniport Drivers
keywords:
- miniport drivers WDK networking , samples
- NDIS miniport drivers WDK networking , samples
- sample drivers WDK NDIS
ms.date: 03/02/2023
---

# Sample NDIS Miniport Drivers





The [Network driver samples](https://go.microsoft.com/fwlink/p/?LinkId=616034) in the [Windows driver samples](https://go.microsoft.com/fwlink/p/?LinkId=616507 ) repository on GitHub includes sample code for miniport drivers that manage several types of network cards. You can modify these sample drivers to your needs. The sample drivers contain functions that can be adapted to a new but similar driver. There are always hardware-dependent functions that you must write. However, many functions are fairly standard. For example, functions that communicate with the NDIS Library instead of a network interface card are typically standard. For these driver functions, the code in a sample driver might be usable with little or no modification.

 

 





