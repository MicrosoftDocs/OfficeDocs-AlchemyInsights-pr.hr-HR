---
title: Kašnjenja u obavještenjima sustava SharePoint i servisa OneDrive
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "2642"
ms.openlocfilehash: 27cc744bc57f1c18649e05c5b0df3b315c9c0201
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47727235"
---
# <a name="delays-in-receiving-sharepoint-and-onedrive-alerts"></a><span data-ttu-id="24d0e-102">Kašnjenja u obavještenjima sustava SharePoint i servisa OneDrive</span><span class="sxs-lookup"><span data-stu-id="24d0e-102">Delays in receiving SharePoint and OneDrive alerts</span></span>

- <span data-ttu-id="24d0e-103">Najprije provjerite mapu junk ili spam u poruci e-pošte.</span><span class="sxs-lookup"><span data-stu-id="24d0e-103">First check the Junk or Spam folder in your email.</span></span>
- <span data-ttu-id="24d0e-104">Ako **se sva upozorenja iz više datoteka ili biblioteka odgodite**, posjetite [nadzornu ploču zdravstvenog](https://portal.office.com/adminportal/home?ref=/servicehealth) sustava da biste provjerili bilo kakve savjete/incidente koji se mogu pojavljivati uz SharePoint ili Exchange.</span><span class="sxs-lookup"><span data-stu-id="24d0e-104">If **all alerts from multiple files or libraries are delayed**, visit the [Service Health dashboard](https://portal.office.com/adminportal/home?ref=/servicehealth) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="24d0e-105">Problem može biti uz mogućnost upozorenja u sustavu SharePoint ili kašnjenja u porukama e-pošte putem sustava Exchange.</span><span class="sxs-lookup"><span data-stu-id="24d0e-105">The issue might be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="24d0e-106">Obratite pozornost i na to je li poslana druga e-pošta – ako ne, problem je vjerojatno s odgodama sustava Exchange.</span><span class="sxs-lookup"><span data-stu-id="24d0e-106">Also note whether other email is being delivered—if not, the issue is likely with Exchange delays.</span></span>
- <span data-ttu-id="24d0e-107">Ako **se pojedinačna uzbuna iz određene datoteke ili biblioteke ne dostavi**, pokušajte je izbrisati i ponovno stvoriti.</span><span class="sxs-lookup"><span data-stu-id="24d0e-107">If **an individual alert from a specific file or library is not delivered**, attempt to delete and recreate it.</span></span> <span data-ttu-id="24d0e-108">Pogledajte odjeljak [Upravljanje, prikaz i brisanje upozorenja sustava SharePoint](https://support.microsoft.com/office/99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) da biste ponovno stvorili upozorenje.</span><span class="sxs-lookup"><span data-stu-id="24d0e-108">See [Manage, view, or delete SharePoint alerts](https://support.microsoft.com/office/99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) to recreate the alert.</span></span>

> [!NOTE]
> - <span data-ttu-id="24d0e-109">Upozorenja nije moguće poslati u grupu za raspodjelu.</span><span class="sxs-lookup"><span data-stu-id="24d0e-109">Alerts cannot be sent to a Distribution Group.</span></span> <span data-ttu-id="24d0e-110">Podržane su samo sigurnosne i O365 grupe.</span><span class="sxs-lookup"><span data-stu-id="24d0e-110">Only Security and O365 groups are supported.</span></span>
> - <span data-ttu-id="24d0e-111">Predloške e-pošte za upozorenje nije moguće prilagoditi.</span><span class="sxs-lookup"><span data-stu-id="24d0e-111">You cannot customize alert email templates.</span></span> <span data-ttu-id="24d0e-112">Da biste to postigli, morate koristiti Microsoft Flow ili tijek rada sustava SharePoint Designer.</span><span class="sxs-lookup"><span data-stu-id="24d0e-112">You must use Microsoft Flow or SharePoint Designer Workflow to achieve those.</span></span>
