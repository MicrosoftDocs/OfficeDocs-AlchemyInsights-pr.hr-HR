---
title: Prijavljivanje AAD Connect
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
- "9003245"
- "9326"
ms.openlocfilehash: 832c9dd587cb023b5b1d87e905acb123df34237f
ms.sourcegitcommit: c08bed4071baa3bb5879496df3ed44fb828c8367
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 03/19/2021
ms.locfileid: "51035088"
---
# <a name="notification-aad-connect"></a><span data-ttu-id="d1906-102">Prijavljivanje AAD Connect</span><span class="sxs-lookup"><span data-stu-id="d1906-102">Notification AAD Connect</span></span>

- <span data-ttu-id="d1906-103">Provjerite jeste li ovlašteni za izvršavanje operacije.</span><span class="sxs-lookup"><span data-stu-id="d1906-103">Ensure you are authorized to perform the operation.</span></span> <span data-ttu-id="d1906-104">Globalni administratori imaju pristup prema zadanim postavkama.</span><span class="sxs-lookup"><span data-stu-id="d1906-104">Global Admins have access by default.</span></span> <span data-ttu-id="d1906-105">Uz to, pomoću [kontrole pristupa temeljene na ulogama](https://docs.microsoft.com/azure/active-directory/connect-health/active-directory-aadconnect-health-operations) možete delegirati dozvolu za registraciju suradnika.</span><span class="sxs-lookup"><span data-stu-id="d1906-105">Additionally, you can use [Role Based Access Control](https://docs.microsoft.com/azure/active-directory/connect-health/active-directory-aadconnect-health-operations) to delegate registration permission to Contributor.</span></span>
- <span data-ttu-id="d1906-106">Provjerite jesu li obavezne krajnje točke omogućene i nije li blokirana zbog vatrozida.</span><span class="sxs-lookup"><span data-stu-id="d1906-106">Ensure the required endpoints are enabled, and not blocked due to firewall.</span></span> <span data-ttu-id="d1906-107">Pojedinosti potražite u članku [Preduvjeti](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-health-agent-install).</span><span class="sxs-lookup"><span data-stu-id="d1906-107">For details, see [requirements](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-health-agent-install).</span></span>
- <span data-ttu-id="d1906-108">Registracija može propasti zbog odlazne komunikacije koja je izložena SSL inspekciji putem mrežnog sloja.</span><span class="sxs-lookup"><span data-stu-id="d1906-108">Registration can fail due to outbound communication being subjected to SSL inspection by the network layer.</span></span>
- <span data-ttu-id="d1906-109">Provjerite jeste li potvrdili postavke obavijesti za Azure AD Connect zdravlje i pregledajte postavke.</span><span class="sxs-lookup"><span data-stu-id="d1906-109">Make sure you have verified the notification settings for Azure AD Connect Health and review your setting.</span></span> <span data-ttu-id="d1906-110">Da biste razumjeli kako konfigurirati postavke obavijesti za obavijesti o zdravlju u servisu Azure AD Connect, pogledajte ovaj [vodič](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-health-operations).</span><span class="sxs-lookup"><span data-stu-id="d1906-110">To understand how to configure the notification settings for Azure AD Connect Health notifications, see this [guide](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-health-operations).</span></span>
- <span data-ttu-id="d1906-111">Da biste saznali više o izvješću o sinkronizaciji programa AAD Connect i kako ga preuzeti, pročitajte članak [izvješće o sinkronizaciji razina objekta](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-health-sync).</span><span class="sxs-lookup"><span data-stu-id="d1906-111">To learn more about the AAD Connect Health sync report and how to download it, see [Object level synchronization report](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-health-sync).</span></span>

<span data-ttu-id="d1906-112">Da biste otklonili poteškoće s upozorenjima za AAD Connect, slijedite [upute za otklanjanje poteškoća za AAD povežite upozorenja o osvježenosti podataka](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-health-data-freshness) i najčešća pitanja, pročitajte članak [zajednički AAD Connect pitanja o zdravstvenoj instalaciji](https://docs.microsoft.com/azure/active-directory/hybrid/reference-connect-health-faq).</span><span class="sxs-lookup"><span data-stu-id="d1906-112">To troubleshoot AAD Connect Health Alerts follow [the troubleshooting guide for AAD Connect Health data freshness alerts](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-health-data-freshness) and for commonly asked questions, see [Common AAD Connect Health installation questions](https://docs.microsoft.com/azure/active-directory/hybrid/reference-connect-health-faq).</span></span>