---
title: Tajna klijenta za registraciju aplikacija ili problemi s certifikatom
ms.author: v-jmathew
author: v-jmathew
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004352"
- "9685"
ms.openlocfilehash: 990648d286ec801785201e6513b70534c3d80e3f
ms.sourcegitcommit: 1f43598a726cdb9904aa501eb8db87f143020d9e
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 03/23/2021
ms.locfileid: "51404296"
---
# <a name="app-registration-client-secret-or-certificate-issues"></a><span data-ttu-id="86c74-102">Tajna klijenta za registraciju aplikacija ili problemi s certifikatom</span><span class="sxs-lookup"><span data-stu-id="86c74-102">App Registration client secret or Certificate issues</span></span>

<span data-ttu-id="86c74-103">Klijentska tajna aplikacije istječe?</span><span class="sxs-lookup"><span data-stu-id="86c74-103">Application client secret expiring?</span></span>

<span data-ttu-id="86c74-104">Bez obzira na to kako je registrirana aplikacija stvorena, bez obzira na to je li putem standardnog postupka registracije na portalu za registraciju aplikacija ili ako je upravitelj servisa stvoren na vašem klijentu pomoću pristanka aplikacije, prije isteka trenutnog programa morat će se stvoriti nova tajna klijenta i ažurirati u povezanom kodu aplikacije.</span><span class="sxs-lookup"><span data-stu-id="86c74-104">Regardless of how the registered application was created, whether through the standard registration process in the Apps Registration portal or if the Service Principal was created in your tenant using application consent, a new Client Secret will need to be created prior to the expiration of the current one and updated in the related application code.</span></span> <span data-ttu-id="86c74-105">Razdoblje maksimalne valjanosti je 2 godine.</span><span class="sxs-lookup"><span data-stu-id="86c74-105">The maximum validity period is 2 years.</span></span> <span data-ttu-id="86c74-106">Kao podsjetnik tajna vrijednost mora se zabilježiti jer više neće biti vidljiva nakon napuštanja stranice za registracije aplikacije na portalu.</span><span class="sxs-lookup"><span data-stu-id="86c74-106">As a reminder the secret value must be recorded as it will no longer be visible after leaving the App registrations page in the portal.</span></span> <span data-ttu-id="86c74-107">Dodatne informacije potražite u članku [Brzi početak rada: Registracija aplikacije na microsoftovoj platformi za identitet](https://docs.microsoft.com/azure/active-directory/develop/quickstart-register-app) i najbolje prakse za [platformu Microsoftova identiteta](https://docs.microsoft.com/azure/active-directory/develop/identity-platform-integration-checklist#security).</span><span class="sxs-lookup"><span data-stu-id="86c74-107">For more information, see [Quickstart: Register an app in the Microsoft identity platform](https://docs.microsoft.com/azure/active-directory/develop/quickstart-register-app) and [Best practices for the Microsoft identity platform](https://docs.microsoft.com/azure/active-directory/develop/identity-platform-integration-checklist#security).</span></span>

<span data-ttu-id="86c74-108">Dodatne informacije potražite u članku [Stvaranje aplikacije Azure AD & glavnicu servisa na portalu – platformu Microsoftova identiteta](https://docs.microsoft.com/azure/active-directory/develop/howto-create-service-principal-portal).</span><span class="sxs-lookup"><span data-stu-id="86c74-108">To learn more, see [Create an Azure AD app & service principal in the portal - Microsoft identity platform](https://docs.microsoft.com/azure/active-directory/develop/howto-create-service-principal-portal).</span></span>