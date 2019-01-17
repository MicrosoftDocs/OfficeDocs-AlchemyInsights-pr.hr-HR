---
title: Uvjetno Access s Intune
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: 59f1aefaeec3d655b2388b00e7d58a8c2338504b
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28279675"
---
# <a name="conditional-access-with-intune"></a><span data-ttu-id="1278b-102">Uvjetno Access s Intune</span><span class="sxs-lookup"><span data-stu-id="1278b-102">Conditional Access with Intune</span></span>

<span data-ttu-id="1278b-103">Pomoću **Uvjetnog Access** s Intune zahtijeva korake 3:</span><span class="sxs-lookup"><span data-stu-id="1278b-103">Using **Conditional Access** with Intune requires 3 steps:</span></span> 
  
- <span data-ttu-id="1278b-p101">Stvaranje **Pravila uvjetnog pristup** koji definira zaštićeni su resursima i što uvjete treba zadovoljiti pristup tih resursa. Ako, na primjer, uređaj mora biti usklađen prije pristupanja tvrtke e-pošte.</span><span class="sxs-lookup"><span data-stu-id="1278b-p101">Create a **Conditional Access Policy** that defines what resources are being protected, and what conditions need to be met to access those resources. For example, a device must be compliant before accessing corporate email.</span></span> 
    
- <span data-ttu-id="1278b-p102">Stvaranje **Pravila usklađenosti** definirati postavke koje treba zadovoljiti prije smatra se uređaj sa standardom. Ako, na primjer, uređaj mora imati pin barem 6 znamenke prije smatra se sa standardom.</span><span class="sxs-lookup"><span data-stu-id="1278b-p102">Create a **Compliance Policy** to define settings that must be met before the device is considered compliant. For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span> 
    
- <span data-ttu-id="1278b-p103">Osiguravanje **Pravila usklađenosti** i **Pravilima uvjetnog Access** ciljan za željeni grupe korisnika. To može zahtijevati stvaranje određene grupe korisnika Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="1278b-p103">Ensuring both **Compliance Policies** and **Conditional Access Policies** are targeted to the desired groups of users. This may require creating specific groups of users in Azure Active Directory.</span></span> 
    
<span data-ttu-id="1278b-110">Pročitajte više:</span><span class="sxs-lookup"><span data-stu-id="1278b-110">Read more:</span></span>
  
- [<span data-ttu-id="1278b-111">Uvjetno Access Najbolji postupci</span><span class="sxs-lookup"><span data-stu-id="1278b-111">Conditional Access best practices</span></span>](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/best-practices)
    
- [<span data-ttu-id="1278b-112">Uvod uvjetno Access</span><span class="sxs-lookup"><span data-stu-id="1278b-112">Getting started with Conditional Access </span></span>](https://docs.microsoft.com/en-us/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    
