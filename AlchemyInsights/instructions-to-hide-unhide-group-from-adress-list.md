---
title: Upute za skrivanje/otkrivanje grupe s popisa adresa
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "3161"
ms.openlocfilehash: 4d55866700b9b8494f1f692cd3b865116b96a1bc
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51831870"
---
# <a name="hide-microsoft-365-group-from-address-list-gal"></a>Skrivanje grupe sustava Microsoft 365 s popisa adresa (GAL)

Da biste sakrili grupu sustava Microsoft 365 od popisa adresa (GAL) klijenata sustava Exchange (kao što su Outlook ili OWA), u exo ljusci koristite sljedeću naredbu:

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

Da biste sakrili grupu sustava Microsoft 365 od vidljivosti klijentima sustava Exchange, u exo ljusci koristite sljedeću naredbu:

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`

