---
title: Sinkroniziranje grupe
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/15/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "8304"
- "9003234"
ms.openlocfilehash: 52c19b6dcc79968150a188b389c5481c122f7945
ms.sourcegitcommit: 6900c2b7208ca51a9873dfc2e00be6f66cb25e3c
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 02/15/2021
ms.locfileid: "50256667"
---
# <a name="group-sync"></a><span data-ttu-id="1d8d4-102">Sinkroniziranje grupe</span><span class="sxs-lookup"><span data-stu-id="1d8d4-102">Group sync</span></span>

<span data-ttu-id="1d8d4-103">U ovom se članku navode smjernice o sinkronizaciji grupe.</span><span class="sxs-lookup"><span data-stu-id="1d8d4-103">This article provides guidance on group synchronization.</span></span>

1. <span data-ttu-id="1d8d4-104">Ako globalni administrator ili vlasnik grupe ne može izmijeniti svojstva grupe ili dodavati članove ili dodijeliti vlasnike na portalu Azure, provjerite je li izvor autoriteta za grupu Azure Active Directory (Azure AD) za globalne administratore ili vlasnika grupe da biste izmijenili grupu.</span><span class="sxs-lookup"><span data-stu-id="1d8d4-104">If a global admin or group owner is not able to modify group properties or add members or assign owners in the Azure portal, ensure the source of the authority for the group is Azure Active Directory (Azure AD) for the global admin or group owner to modify the group.</span></span>
2. <span data-ttu-id="1d8d4-105">Prije nego što pokušate izbrisati sinkroniziranu grupu u servisu Azure AD, provjerite jeste li [izbrisali sve dodijeljene licence](https://docs.microsoft.com/azure/active-directory/enterprise-users/licensing-group-advanced) da biste izbjegli pogreške.</span><span class="sxs-lookup"><span data-stu-id="1d8d4-105">Before attempting to delete a synced group in Azure AD, ensure you have [deleted all assigned licenses](https://docs.microsoft.com/azure/active-directory/enterprise-users/licensing-group-advanced) to avoid errors.</span></span>

<span data-ttu-id="1d8d4-106">Da biste razumjeli kako sinkronizirati korisnike, grupe i kontakte, pročitajte članak [Azure ad Connect sync](https://docs.microsoft.com/azure/active-directory/hybrid/concept-azure-ad-connect-sync-user-and-contacts)i pratite [sinkronizaciju lokalne grupe na Azure pomoću servisa Azure ad Connect](https://docs.microsoft.com/azure/active-directory/hybrid/whatis-hybrid-identity?WT.mc_id=Portal-Microsoft_Azure_Support) da biste sinkronizirali grupe na perm-u pomoću servisa ad Connect.</span><span class="sxs-lookup"><span data-stu-id="1d8d4-106">For understanding how to sync users, groups and contacts, see [Azure AD Connect Sync](https://docs.microsoft.com/azure/active-directory/hybrid/concept-azure-ad-connect-sync-user-and-contacts), and follow [Syncing an on-premises group to Azure using Azure AD Connect](https://docs.microsoft.com/azure/active-directory/hybrid/whatis-hybrid-identity?WT.mc_id=Portal-Microsoft_Azure_Support) to sync on-perm groups using AD connect.</span></span>

<span data-ttu-id="1d8d4-107">Slijedite ovaj vodič za [Otklanjanje poteškoća s pogreškama tijekom sinkronizacije](https://docs.microsoft.com/azure/active-directory/hybrid/tshoot-connect-sync-errors) radi otklanjanja uobičajenih pogrešaka tijekom sinkronizacije.</span><span class="sxs-lookup"><span data-stu-id="1d8d4-107">Follow this guide [Troubleshooting Errors during synchronization](https://docs.microsoft.com/azure/active-directory/hybrid/tshoot-connect-sync-errors) to troubleshoot common errors during synchronization.</span></span>
