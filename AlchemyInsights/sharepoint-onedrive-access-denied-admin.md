---
title: Otklanjanje poteškoća s zabranom pristupa porukama
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 22f5966fdae563c44affb7d0447787a4ee0aca93
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 09/15/2020
ms.locfileid: "47767649"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a><span data-ttu-id="21e8e-102">Otklanjanje poteškoća s zabranom pristupa porukama u centru za administratore sustava SharePoint/OneDrive</span><span class="sxs-lookup"><span data-stu-id="21e8e-102">Troubleshoot Access Denied messages in Sharepoint/OneDrive Admin Center</span></span>

<span data-ttu-id="21e8e-103">Ako prilikom pokušaja pregledavanja u centar za administratore sustava SharePoint/OneDrive primate poruku o uskraćenog pristupa, provjerite jeste li [korisniku dodijelili licencu](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users).</span><span class="sxs-lookup"><span data-stu-id="21e8e-103">If you are receiving an access denied message when attempting to browse to a Sharepoint/OneDrive Admin Center, please make sure that you [assign a license to the user](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users).</span></span> <span data-ttu-id="21e8e-104">Ako korisnik ima licencu, trebali biste se pobrinuti i da im je [dodijeljena administratorska uloga](hhttps://docs.microsoft.com/microsoft-365/admin/add-users/about-admin-roles) koja može pristupati centrima za administratore.</span><span class="sxs-lookup"><span data-stu-id="21e8e-104">If the user has a license, you should also make sure they are [assigned an administrator role](hhttps://docs.microsoft.com/microsoft-365/admin/add-users/about-admin-roles) that can access the admin centers.</span></span>

<span data-ttu-id="21e8e-105">Taj se problem može pojaviti i kada je korisnik izbrisan i ponovno stvoren pomoću istog glavnog naziva korisnika (UPN).</span><span class="sxs-lookup"><span data-stu-id="21e8e-105">This issue can also occur when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="21e8e-106">Novi se račun stvara pomoću različite vrijednosti za PUID (jedinstveni ID putovnice).</span><span class="sxs-lookup"><span data-stu-id="21e8e-106">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="21e8e-107">Kada korisnik pokuša pristupiti zbirci web-mjesta ili njihovom servisu OneDrive, korisnik ima pogrešan PUID.</span><span class="sxs-lookup"><span data-stu-id="21e8e-107">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="21e8e-108">Drugi scenarij obuhvaća sinkronizaciju direktorija s organizacijom Active Directory (OU).</span><span class="sxs-lookup"><span data-stu-id="21e8e-108">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="21e8e-109">Ako su se korisnici već prijavili u SharePoint, a zatim se premještaju u drugi OU i ponovno sinkroniziraju sa sustavom SharePoint, možda će doživjeti taj problem.</span><span class="sxs-lookup"><span data-stu-id="21e8e-109">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

<span data-ttu-id="21e8e-110">Da biste riješili taj problem, trebali biste vratiti originalni UPN pomoću koraka u članku, [vratiti korisnika u programu Microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).</span><span class="sxs-lookup"><span data-stu-id="21e8e-110">To resolve this issue, you should restore the original UPN with the steps in the article, [Restore a user in Microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).</span></span>

<span data-ttu-id="21e8e-111">Pažnja: Ako centar za administratore servisa OneDrive ili SharePoint nije dostupan većem broju korisnika koji su prethodno imali pristup, možda postoji privremeni problem s servisom.</span><span class="sxs-lookup"><span data-stu-id="21e8e-111">Note: If a OneDrive or SharePoint Admin center is not available to multiple users who previously had access, there may be a temporary service issue.</span></span>  <span data-ttu-id="21e8e-112">[Provjerite nadzornu ploču zdravstvenog stanja servisa](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="21e8e-112">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>


