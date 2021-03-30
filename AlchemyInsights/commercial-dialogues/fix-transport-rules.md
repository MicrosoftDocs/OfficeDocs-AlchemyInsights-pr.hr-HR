---
title: Rješavanje pravila prijenosa
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: 635009ed4b78d2b05b0eef1f3298765b10f86ede
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 03/11/2021
ms.locfileid: "50743863"
---
# <a name="fix-transport-rules"></a><span data-ttu-id="e17d0-102">Rješavanje pravila prijenosa</span><span class="sxs-lookup"><span data-stu-id="e17d0-102">Fix transport rules</span></span>

<span data-ttu-id="e17d0-103">Prilagođeno pravilo tijeka e-pošte utjecalo je na ovu poruku.</span><span class="sxs-lookup"><span data-stu-id="e17d0-103">A custom mail flow rule affected this message.</span></span> <span data-ttu-id="e17d0-104">Da biste pregledali točno pravilo, učinite sljedeće:</span><span class="sxs-lookup"><span data-stu-id="e17d0-104">To review the exact rule, do the following:</span></span>

1. <span data-ttu-id="e17d0-105">U rezultatima slanja u odjeljku **Dodatne informacije** obratite pozornost na **GUID** ili **naziv pravilnika**.</span><span class="sxs-lookup"><span data-stu-id="e17d0-105">In the submission results, under **Additional information**, note the **GUID** or the **Policy Name**.</span></span>
2. <span data-ttu-id="e17d0-106">Pokreni ljusku za upravljanje sustavom Exchange.</span><span class="sxs-lookup"><span data-stu-id="e17d0-106">Launch Exchange Management Shell.</span></span> <span data-ttu-id="e17d0-107">Dodatne informacije potražite u članku [Otvaranje ljuske za upravljanje sustavom Exchange](https://go.microsoft.com/fwlink/?linkid=2101432).</span><span class="sxs-lookup"><span data-stu-id="e17d0-107">For more information, see [Open the Exchange Management Shell](https://go.microsoft.com/fwlink/?linkid=2101432).</span></span>
3. <span data-ttu-id="e17d0-108">Pokretanje ove naredbe (pomoću GUID-a iz slanja):  **Nabavite-TransportRule-Identity "GUID" | FL \* Opis**\*</span><span class="sxs-lookup"><span data-stu-id="e17d0-108">Run this command (using the GUID from your submission):  **Get-TransportRule -identity "GUID" | fl \* Description**\*</span></span>
4. <span data-ttu-id="e17d0-109">Pregledajte Opis da biste vidjeli konfigurirane uvjete koji su utjecali na poruku.</span><span class="sxs-lookup"><span data-stu-id="e17d0-109">Review the description to see the configured conditions that affected the message.</span></span>

<span data-ttu-id="e17d0-110">Dodatne informacije potražite u članku [transport-Teleporttrule](https://go.microsoft.com/fwlink/?linkid=2101523).</span><span class="sxs-lookup"><span data-stu-id="e17d0-110">To learn more, see [Get-TransportRule](https://go.microsoft.com/fwlink/?linkid=2101523).</span></span>