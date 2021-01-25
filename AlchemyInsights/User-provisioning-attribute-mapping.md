---
title: Mapiranje atributa korisnika-dodjela resursa
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 01/22/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7851"
- "9004348"
ms.openlocfilehash: 8bbf554c533d960a304901d7cbb492b87e9bec71
ms.sourcegitcommit: 953a8567ebcd9835f8c5c49472b223107c92549b
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 01/22/2021
ms.locfileid: "49949665"
---
# <a name="user-provisioning-attribute-mapping"></a><span data-ttu-id="a10a1-102">Mapiranje atributa korisnika-dodjela resursa</span><span class="sxs-lookup"><span data-stu-id="a10a1-102">User-provisioning attribute mapping</span></span>

1. <span data-ttu-id="a10a1-103">Da biste otklonili poteškoće s poznatim problemima s preslikavanjem atributa, pogledajte [preslikavanje atributa](https://docs.microsoft.com/azure/active-directory/app-provisioning/known-issues#attribute-mappings).</span><span class="sxs-lookup"><span data-stu-id="a10a1-103">To troubleshoot known attribute-mapping issues, see [Attribute mappings](https://docs.microsoft.com/azure/active-directory/app-provisioning/known-issues#attribute-mappings).</span></span> 
2. <span data-ttu-id="a10a1-104">Microsoft Azure Active Directory (AD) nudi podršku za dodjelu resursa korisnicima u programu SaaS kao što su Salesforce, G suite i drugi.</span><span class="sxs-lookup"><span data-stu-id="a10a1-104">Microsoft Azure Active Directory (AD) provides support for user provisioning to third-party SaaS applications such as Salesforce, G Suite and others.</span></span> <span data-ttu-id="a10a1-105">Ako korisnicima omogućite dodjelu resursa za aplikaciju za SaaS, portal Azure upravlja vrijednostima atributa pomoću mapiranja atributa.</span><span class="sxs-lookup"><span data-stu-id="a10a1-105">If you enable user provisioning for a third-party SaaS application, the Azure portal controls its attribute values through attribute-mappings.</span></span> <span data-ttu-id="a10a1-106">Upute za prilagodbu zadanog mapiranja atributa potražite [u članku Prilagodba atributa korisničke dodjele resursa – mapiranja za aplikacije SaaS u servisu Azure Active Directory](https://docs.microsoft.com/azure/active-directory/app-provisioning/customize-application-attributes).</span><span class="sxs-lookup"><span data-stu-id="a10a1-106">To learn how to customize the default attribute-mappings, see [Customize user provisioning attribute-mappings for SaaS applications in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/app-provisioning/customize-application-attributes).</span></span>
    - <span data-ttu-id="a10a1-107">Da biste saznali više o dodjeli resursa korisnika u aplikaciji SaaS, pročitajte članak [što je automatska dodjela korisničkih aplikacija za SaaS u Azure ad?](https://docs.microsoft.com/azure/active-directory/app-provisioning/user-provisioning)</span><span class="sxs-lookup"><span data-stu-id="a10a1-107">To learn more about SaaS app user provisioning, see [What is automated SaaS app user provisioning in Azure AD?](https://docs.microsoft.com/azure/active-directory/app-provisioning/user-provisioning)</span></span> 
3. <span data-ttu-id="a10a1-108">Prilikom prilagodbe atributa – mapiranja za dodjelu resursa korisniku, možda ćete pronaći da se atribut koji želite mapirati ne prikazuje na popisu izvorišni atribut.</span><span class="sxs-lookup"><span data-stu-id="a10a1-108">When customizing attribute-mappings for user provisioning, you might find that the attribute you want to map doesn't appear in the Source attribute list.</span></span> <span data-ttu-id="a10a1-109">[Sinkroniziranje atributa iz lokalnog servisa Active Directory sa servisom Azure ad za dodjelu resursa u članak aplikacije](https://docs.microsoft.com/azure/active-directory/app-provisioning/user-provisioning-sync-attributes-for-mapping) prikazuje kako dodati atribut koji nema sinkroniziranjem s lokalnog oglasa na Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a10a1-109">The [Sync an attribute from your on-premises Active Directory to Azure AD for provisioning to an application](https://docs.microsoft.com/azure/active-directory/app-provisioning/user-provisioning-sync-attributes-for-mapping) article shows you how to add the missing attribute by synchronizing it from your on-premises AD to Azure AD.</span></span>
