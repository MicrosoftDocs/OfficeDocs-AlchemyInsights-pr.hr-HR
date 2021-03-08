---
title: Konfiguracija servisa MIM sync
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/19/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "8472"
- "9004688"
ms.openlocfilehash: 48e9a0e8c26088b690092bfaedfba641841739f6
ms.sourcegitcommit: 379e132c4d21ecf703d5506484ec96a767fdda39
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 03/04/2021
ms.locfileid: "50480964"
---
# <a name="configure-mim-sync-service"></a><span data-ttu-id="d7c07-102">Konfiguracija servisa MIM sync</span><span class="sxs-lookup"><span data-stu-id="d7c07-102">Configure MIM Sync service</span></span>

<span data-ttu-id="d7c07-103">Servis za sinkronizaciju programa Microsoft Identity Manager (MIM) komponenta je MIM.</span><span class="sxs-lookup"><span data-stu-id="d7c07-103">Microsoft Identity Manager (MIM) Synchronization Service is a component of MIM.</span></span> <span data-ttu-id="d7c07-104">To je središnji lokalni servis koji pohranjuje i integrira informacije za tvrtke ili ustanove koje imaju više lokalnih direktorija i baza podataka.</span><span class="sxs-lookup"><span data-stu-id="d7c07-104">It is a centralized on-premises service that stores and integrates information for organizations that have multiple on-premises directories and databases.</span></span> <span data-ttu-id="d7c07-105">Problem možete riješiti i uz MIM sync ako je problem upućen nedavnim ažuriranjem na MIM ili je jedan od ostalih problema navedenih u odjeljku u nastavku.</span><span class="sxs-lookup"><span data-stu-id="d7c07-105">You may be able to resolve your problem with MIM Sync if the issue was addressed in a recent update to MIM or is one of the other issues mentioned in the below section.</span></span>

<span data-ttu-id="d7c07-106">**Preporučeni koraci**</span><span class="sxs-lookup"><span data-stu-id="d7c07-106">**Recommended steps**</span></span>

1. <span data-ttu-id="d7c07-107">Provjerite koristite li nedavno ažuriran broj MIM sinkronizacijom i provjerite je li na [bilješkama o objavama izdanja Mim sinkronizirajte](https://docs.microsoft.com/microsoft-identity-manager/reference/version-history) problem riješen u ažuriranju.</span><span class="sxs-lookup"><span data-stu-id="d7c07-107">Ensure that you are using a recent update of MIM Sync and check the [MIM Sync release notes](https://docs.microsoft.com/microsoft-identity-manager/reference/version-history) to determine if the issue has been resolved in an update.</span></span>
2. <span data-ttu-id="d7c07-108">Ako je problem s generičkim LDAP, Generic SQL, Lotus Domino ili Web Services Connector, provjerite koristite li nedavno ažuriranje [generičkih konektora](https://docs.microsoft.com/microsoft-identity-manager/reference/microsoft-identity-manager-2016-connector-version-history).</span><span class="sxs-lookup"><span data-stu-id="d7c07-108">If the problem is with the Generic LDAP, Generic SQL, Lotus Domino or Web Services connector, ensure that you are using a recent update of the [generic connectors](https://docs.microsoft.com/microsoft-identity-manager/reference/microsoft-identity-manager-2016-connector-version-history).</span></span>
3. <span data-ttu-id="d7c07-109">Ako se MIM sinkronizira s pogreškom, obratite se u tablici [kodova pogrešaka](https://docs.microsoft.com/microsoft-identity-manager/reference/maerrorcodes) radi utvrđivanja mogućih uzroka.</span><span class="sxs-lookup"><span data-stu-id="d7c07-109">If an MIM Sync-run stops with an error, consult the table of [run error codes](https://docs.microsoft.com/microsoft-identity-manager/reference/maerrorcodes) to determine the potential causes.</span></span>
4. <span data-ttu-id="d7c07-110">Ako se pokretanje prestane stvarati uz **iznimku Extension-DLL**, kliknite te riječi da biste otvorili prozor **Svojstva prostora konektora** , a zatim kliknite na gumb **Trace...** da biste vidjeli dodatne informacije o temeljnim uzroku, kao što je opisano u odjeljku [protezanje-DLL – iznimka](https://social.technet.microsoft.com/wiki/contents/articles/7515.fim-troubleshooting-extension-dll-exception.aspx).</span><span class="sxs-lookup"><span data-stu-id="d7c07-110">If the run stops with **extension-dll-exception**, then click on those words to open the **Connector Space Object properties** window, and click on **Stack Trace...** to see more information on the underlying cause, as described in [Extension-DLL-Exception](https://social.technet.microsoft.com/wiki/contents/articles/7515.fim-troubleshooting-extension-dll-exception.aspx).</span></span>
5. <span data-ttu-id="d7c07-111">Ako je u zapisniku događaja prilikom sinkronizacije lozinke servisa za obavješćivanje o promjeni lozinke (PCN-a) **došlo do pogreške 6025** , provjerite vodič za otklanjanje poteškoća s [prijavom na poruku o pogrešci 6025](https://social.technet.microsoft.com/wiki/contents/articles/4159.pcns-troubleshooting-event-id-6025.aspx).</span><span class="sxs-lookup"><span data-stu-id="d7c07-111">If the Password Change Notification Service (PCNS) component reports **error 6025** in the event log during password synchronization, check the guide for troubleshooting [PCNS reporting error 6025](https://social.technet.microsoft.com/wiki/contents/articles/4159.pcns-troubleshooting-event-id-6025.aspx).</span></span>
6. <span data-ttu-id="d7c07-112">Ako je potpuna sinkronizacija s agentom za upravljanje servisom FIM spor, provjerite postavku **automatskog rasta** za tempdb, kao što je opisano u odjeljku [Otklanjanje poteškoća s usporenim ili visećim punim sinkronizacijom](https://social.technet.microsoft.com/wiki/contents/articles/14713.troubleshooting-fim-performance-slow-or-hanging-full-synchronization.aspx).</span><span class="sxs-lookup"><span data-stu-id="d7c07-112">If full synchronization with the FIM Service Management Agent is slow, check the **auto grow** setting for TempDB, as described in [Troubleshooting slow or hanging full synchronization](https://social.technet.microsoft.com/wiki/contents/articles/14713.troubleshooting-fim-performance-slow-or-hanging-full-synchronization.aspx).</span></span>
7. <span data-ttu-id="d7c07-113">Ako naijete na pogrešku zaustavnog poslužitelja s neuspjelih-stvaranje-Via-web-servisima pomoću agenta za upravljanje servisom FIM, pročitajte članak [Podrška-informacije: nije uspjelo-stvaranje-Via-Web-Services](https://docs.microsoft.com/archive/blogs/iamsupport/support-info-fimma-failed-creation-via-web-services) za pregled uzroka.</span><span class="sxs-lookup"><span data-stu-id="d7c07-113">If you are encountering an error of stopped-server with failed-creation-via-web-services using the FIM Service Management Agent, see [Support-Info: failed-creation-via-web-services](https://docs.microsoft.com/archive/blogs/iamsupport/support-info-fimma-failed-creation-via-web-services) for an overview of causes.</span></span>
