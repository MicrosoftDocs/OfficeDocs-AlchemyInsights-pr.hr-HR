---
title: Jedan korisnik dobiva pogrešku odbijen pristup prilikom dodavanja dodataka u programu Outlook
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/23/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5892"
- "6700008"
ms.openlocfilehash: 1f4672e306a282b3e1d20c75f4e361c02cdddaed
ms.sourcegitcommit: 07e56267dedfc4cec1143072c791670cbf81186b
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 07/24/2020
ms.locfileid: "45423363"
---
# <a name="one-user-gets-access-denied-error-while-adding-add-ins-in-outlook"></a><span data-ttu-id="06379-102">Jedan korisnik dobiva pogrešku odbijen pristup prilikom dodavanja dodataka u programu Outlook</span><span class="sxs-lookup"><span data-stu-id="06379-102">One user gets Access Denied error while adding add-ins in Outlook</span></span>

<span data-ttu-id="06379-103">Korisnički PowerShell Da biste pronašli dozvole:</span><span class="sxs-lookup"><span data-stu-id="06379-103">User PowerShell To find permissions:</span></span>

<span data-ttu-id="06379-104">Get-ManagementRoleAssignment -RoleAssignee [user@domain.com-Delegiranje](mailto:user@domain.com "mailto:user@domain.com") $false | Oblikovanje-tablica -Auto uloga,RoleAssigneeName,RoleAssigneeType</span><span class="sxs-lookup"><span data-stu-id="06379-104">Get-ManagementRoleAssignment -RoleAssignee [user@domain.com](mailto:user@domain.com "mailto:user@domain.com") -Delegating $false | Format-Table -Auto Role,RoleAssigneeName,RoleAssigneeType</span></span>