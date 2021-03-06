---
title: Uvjetni pristup pomoću aplikacije Intune
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: 20ef8205431aad821419f2559be3402c8228d838
ms.sourcegitcommit: 0eb4f9bde53395b5fd4b5cd4ffc56ca96db91298
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 03/10/2021
ms.locfileid: "50704778"
---
# <a name="conditional-access-with-intune"></a>Uvjetni pristup pomoću aplikacije Intune

Korištenje  **uvjetnog pristupa**  pomoću aplikacije Intune zahtijeva tri koraka:

- Stvaranje  **pravilnika o usklađenosti**  ([Android](https://docs.microsoft.com/intune/compliance-policy-create-android),  [iOS](https://docs.microsoft.com/intune/compliance-policy-create-ios),  [Windows](https://docs.microsoft.com//intune/compliance-policy-create-windows)) za definiranje postavki koje je potrebno ispuniti prije nego što se uređaj smatra sukladnim. Na primjer, uređaj mora imati PIN od najmanje 6 znamenki prije nego što se smatra sukladnim.
- Stvorite **pravilnik o uvjetnom pristupu**  koji definira resurse zaštićene i koje uvjete morate ispuniti da biste pristupili tim resursima.  [Na primjer,](https://docs.microsoft.com/intune/tutorial-protect-email-on-unmanaged-devices#create-conditional-access-policies)  uređaj mora biti usklađen prije pristupanja korporativnom e-pošti.
- Provjerite jesu li **pravila usklađivanja**  i pravila  **uvjetnog pristupa**  usmjerena na željene grupe korisnika. To može zahtijevati stvaranje određenih grupa korisnika u servisu Azure Active Directory.

**Korisne veze:**

[Pregled usklađenosti uređaja](https://docs.microsoft.com/intune/device-compliance-get-started)

[Otklanjanje poteškoća sa com](https://docs.microsoft.com/intune/troubleshoot-conditional-access)

[Pravilnik o otklanjanju poteškoća](https://docs.microsoft.com/troubleshoot/mem/intune/troubleshoot-policies-in-microsoft-intune)

Da biste zaštitili e-poštu (Exchange Online) iz programa Access prema nesukladnim uređajima, moraju se pratiti oba dokumenta:

1. [Zaštita pristupa e-pošti s uređaja pomoću servisa EAS](https://docs.microsoft.com/intune/tutorial-protect-email-on-unmanaged-devices)
2. [Zaštita pristupa e-pošti s uređaja pomoću modernih klijenata za provjeru autentičnosti kao što je Outlook](https://docs.microsoft.com/intune/tutorial-protect-email-on-enrolled-devices)