---
title: Operations for your Azure Rights Management tenant key
ms.custom: na
ms.reviewer: na
ms.service: rights-management
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 1284d0ee-0a72-45ba-a64c-3dcb25846c3d
author: Cabailey
---
# Operations for your Azure Rights Management tenant key
Depending on your tenant key topology (Microsoft-managed or customer-managed), you have different levels of control and responsibility for your Microsoft Azure Rights Management (Azure RMS) tenant key after it is implemented.

When you manage your own tenant key, this is often referred to as bring your own key (BYOK). For more information about this scenario and how to choose between the two tenant key topologies, see [Planning and Implementing Your Azure Rights Management Tenant Key](planning-and-implementing-your-azure-rights-management-tenant-key.md).

The following table identifies which operations you can do, depending on the topology that you’ve chosen for your Azure RMS tenant key.

|Lifecycle operation|Microsoft-managed (default)|Customer-managed (BYOK)|
|-----------------------|-------------------------------|---------------------------|
|Revoke your tenant key|No (automatic)|No (automatic)|
|Re-key your tenant key|Yes|Yes|
|Backup and recover your tenant key|No|Yes|
|Export your tenant key|Yes|No|
|Respond to a breach|Yes|Yes|

After you have identified which topology you have implemented, select one of the following  for more information about these operations for your Azure RMS tenant key.

> [!div class="op_single_selector"]
- [Microsoft-managed tenant key](operations-for-your-azure-rights-management-tenant-key-microsoft-managed.md)
- [Customer-managed tenant key](operations-for-your-azure-rights-management-tenant-key-customer-managed.md)


## See Also
[Using Azure Rights Management](using-azure-rights-management.md)
