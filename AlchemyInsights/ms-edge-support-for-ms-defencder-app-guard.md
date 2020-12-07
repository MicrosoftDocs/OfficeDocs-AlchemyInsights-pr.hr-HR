---
title: Podrška za Microsoft Edge radi zaštite aplikacija za Microsoft Defender
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 12/05/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004024"
- "7090"
ms.openlocfilehash: 65cbc867ea7d1c73ca2906f51f72aa3376f31b5d
ms.sourcegitcommit: 2e4a5153e530bf15744a52e982eeb0d99757e9d2
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 12/04/2020
ms.locfileid: "49583251"
---
# <a name="microsoft-edges-support-for-microsoft-defender-application-guard"></a><span data-ttu-id="1225f-102">Podrška za Microsoft Edge radi zaštite aplikacija za Microsoft Defender</span><span class="sxs-lookup"><span data-stu-id="1225f-102">Microsoft Edge's support for Microsoft Defender Application Guard</span></span>

<span data-ttu-id="1225f-103">Dizajniran za Windows 10 i Microsoft Edge, čuvar aplikacije koristi hardver-izolaciju pristup koji omogućuje korisniku navigaciju nepouzdano web-mjesto unutar izoliranog, Hyper-V – omogućenog spremnika, razdvojenog od glavnog operacijskog sustava.</span><span class="sxs-lookup"><span data-stu-id="1225f-103">Designed for Windows 10 and Microsoft Edge, Application Guard uses a hardware-isolation approach that lets a user navigate an untrusted site from inside an isolated, Hyper-V–enabled container, separated from the host operating system.</span></span>

<span data-ttu-id="1225f-104">Administrator tvrtke definira popis pouzdanih web-mjesta, resursa u oblaku i interne mreže.</span><span class="sxs-lookup"><span data-stu-id="1225f-104">An enterprise admin defines a list of trusted websites, cloud resources, and internal networks.</span></span> <span data-ttu-id="1225f-105">Kada korisnik posjeti web-mjesto koje se ne nalazi na popisu, Microsoft Edge otvorit će web-mjesto u spremniku.</span><span class="sxs-lookup"><span data-stu-id="1225f-105">When a user visits a site that's not on the list, Microsoft Edge will open the site in the container.</span></span> <span data-ttu-id="1225f-106">To znači da ako se prikaže zlonamjerno web-mjesto, glavno računalo ostat će zaštićeno, a napadač neće doći do podataka tvrtke.</span><span class="sxs-lookup"><span data-stu-id="1225f-106">This means that if the site turns out to be malicious, the host PC will remain protected and the attacker won't get to the enterprise data.</span></span>

<span data-ttu-id="1225f-107">Instalacija proširenja u spremniku podržana je kao Microsoft Edge verzija 81 i može se kontrolirati putem pravilnika.</span><span class="sxs-lookup"><span data-stu-id="1225f-107">Installation of extensions in the container is supported as of Microsoft Edge version 81, and it can be controlled via a policy.</span></span> <span data-ttu-id="1225f-108">Adresa updateURL koja se koristi u pravilima ExtensionInstallForcelist trebala bi biti dodana kao neutralni resurs u pravilima izolacije mreže koju koristi čuvar aplikacije.</span><span class="sxs-lookup"><span data-stu-id="1225f-108">The updateURL address that gets used in the ExtensionInstallForcelist policy should be added as a Neutral Resource in the Network Isolation policies used by Application Guard.</span></span>

<span data-ttu-id="1225f-109">Dodatne informacije potražite u [članku Podrška za Microsoft Edge za čuvara aplikacija za Microsoft Defender](https://go.microsoft.com/fwlink/?linkid=2134229).</span><span class="sxs-lookup"><span data-stu-id="1225f-109">For more info, see [Microsoft Edge support for Microsoft Defender Application Guard](https://go.microsoft.com/fwlink/?linkid=2134229).</span></span>
