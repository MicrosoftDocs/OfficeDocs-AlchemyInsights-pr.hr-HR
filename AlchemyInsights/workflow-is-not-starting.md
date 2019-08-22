---
title: Tijek rada se pokreće
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 8/2/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: a3bac74c19a77b7703f948c1d8b6bcd182e9b075
ms.sourcegitcommit: 631e527967f4d641bc9227642ffe38967ae87a00
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 08/09/2019
ms.locfileid: "36270772"
---
# <a name="workflow-is-not-starting"></a><span data-ttu-id="1e6b9-102">Tijek rada se pokreće</span><span class="sxs-lookup"><span data-stu-id="1e6b9-102">Workflow is not starting</span></span>

- <span data-ttu-id="1e6b9-103">SharePoint 2010 i SharePoint 2013 tijekovi rada su početni.</span><span class="sxs-lookup"><span data-stu-id="1e6b9-103">SharePoint 2010 and SharePoint 2013 workflows are not starting.</span></span>

    - <span data-ttu-id="1e6b9-104">Ako vaš tijek rada se pokreće, možda postoji problem privremeni servis gdje korisnici primijetiti povremena kašnjenja s tijeku rada.</span><span class="sxs-lookup"><span data-stu-id="1e6b9-104">If your workflow is not starting, there may be a temporary service issue where users may experience intermittent delays with workflow progress.</span></span> <span data-ttu-id="1e6b9-105">Provjerite [Nadzorne ploče servis stanja sustava](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) da biste vidjeli ako vaša organizacija utjecati.</span><span class="sxs-lookup"><span data-stu-id="1e6b9-105">Check the [Service Health Dashboard](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>

    - <span data-ttu-id="1e6b9-106">Ako više od 24 sata prošlo Budući vidjeli taj problem, prijaviti ulaznica za podršku.</span><span class="sxs-lookup"><span data-stu-id="1e6b9-106">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="1e6b9-107">U mnogim slučajevima smo već radite rješenje.</span><span class="sxs-lookup"><span data-stu-id="1e6b9-107">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="1e6b9-108">Molimo pošaljite nam najmanje 24 sata dovršiti rješenje.</span><span class="sxs-lookup"><span data-stu-id="1e6b9-108">Please give us at least 24 hours to complete a solution.</span></span>

- <span data-ttu-id="1e6b9-109">Tijekovi rada SharePoint 2010 odgođeno na početak.</span><span class="sxs-lookup"><span data-stu-id="1e6b9-109">SharePoint 2010 workflows delayed on start.</span></span>

    - <span data-ttu-id="1e6b9-110">To se događa ako se tijek rada pokrene u veliki serije.</span><span class="sxs-lookup"><span data-stu-id="1e6b9-110">This occurs if the workflow is triggered in large batches.</span></span> <span data-ttu-id="1e6b9-111">(na primjer, kada nekoliko stavke dodaju odjednom).</span><span class="sxs-lookup"><span data-stu-id="1e6b9-111">(for example, when several items are added at once).</span></span>

    - <span data-ttu-id="1e6b9-112">Tijekovi rada su dizajnirani za pokretanje u stvarnom vremenu, pa je kašnjenje ponašanje po dizajna.</span><span class="sxs-lookup"><span data-stu-id="1e6b9-112">Workflows are not designed to run real-time, so a delay is by-design behavior.</span></span>

   -  <span data-ttu-id="1e6b9-113">Ako je tijek rada složene Extensible objekt Markup Language (XMOL), kompiliranja može biti sporo.</span><span class="sxs-lookup"><span data-stu-id="1e6b9-113">If the Workflow is complex Extensible Object Markup Language (XMOL), compilation can be slow.</span></span> <span data-ttu-id="1e6b9-114">Provjerite [u ovom](https://support.microsoft.com/en-us/kb/3043697) članku.</span><span class="sxs-lookup"><span data-stu-id="1e6b9-114">Check [this](https://support.microsoft.com/en-us/kb/3043697) article.</span></span>

    - <span data-ttu-id="1e6b9-115">Trebali biste pojednostavili tijek rada ili redizajnirati ga pomoću vrsta platforme Microsoft SharePoint 2013 tijeka rada.</span><span class="sxs-lookup"><span data-stu-id="1e6b9-115">You should simplify the workflow or redesign it using the Microsoft SharePoint 2013 Workflow platform type.</span></span>

    - <span data-ttu-id="1e6b9-116">Ako povijest tijeka rada postala velik, možda želite Pročisti stavke ili stvoriti novi popis povijesti.</span><span class="sxs-lookup"><span data-stu-id="1e6b9-116">If your workflow history has grown large, you may want to purge the items or create a new history list.</span></span>

        <span data-ttu-id="1e6b9-117">Dodatne informacije: [Čišćenje povijesti tijeka rada](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span><span class="sxs-lookup"><span data-stu-id="1e6b9-117">More Information : [Purge Workflow History](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span></span>


## <a name="related-topics"></a><span data-ttu-id="1e6b9-118">Povezane teme</span><span class="sxs-lookup"><span data-stu-id="1e6b9-118">Related topics</span></span>
<span data-ttu-id="1e6b9-119">Želite li pokušajte Microsoft Flow u SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="1e6b9-119">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="1e6b9-120">Stvaranje toka</span><span class="sxs-lookup"><span data-stu-id="1e6b9-120">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="1e6b9-121">SharePoint i tijek</span><span class="sxs-lookup"><span data-stu-id="1e6b9-121">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 

