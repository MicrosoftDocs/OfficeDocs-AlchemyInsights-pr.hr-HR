---
title: Upravljanje sinkroniziranim korisnikom
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000609"
- "2444"
ms.openlocfilehash: 53c188f6c6ab93bcc6f87d95717dc0d24d492bb7
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 09/15/2020
ms.locfileid: "47777669"
---
# <a name="unable-to-set-primary-email-address-change-user-attributes-or-removedelete-a-synchronized-user"></a><span data-ttu-id="01981-102">Nemogućnost postavljanja primarne adrese e-pošte, promjena korisničkih atributa ili uklanjanje/brisanje sinkroniziranog korisnika</span><span class="sxs-lookup"><span data-stu-id="01981-102">Unable to set primary email address, change user attributes, or remove/delete a synchronized user</span></span>

<span data-ttu-id="01981-103">Ako je za vašu okolinu omogućena sinkronizacija direktorija, neki korisnici ili atributi objekta ne mogu se promijeniti pomoću centra za administratore sustava Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="01981-103">If directory synchronization is enabled for your environment, some user or object attributes cannot be changed using the Microsoft 365 admin center.</span></span>

<span data-ttu-id="01981-104">Da biste u potpunosti upravljali sinkroniziranim korisnicima i svim njihovim atributima, koristite lokalne korisnike servisa Active Directory i konzolu za upravljanje grupama (Adsiedit. msc).</span><span class="sxs-lookup"><span data-stu-id="01981-104">To fully manage synchronized users and all their attributes, use your local active directory users and groups management console (adsiedit.msc).</span></span>  

<span data-ttu-id="01981-105">Alternativno, možete promijeniti pojedinačne korisnike ili atribute za sinkronizirane korisnike pomoću komponente PowerShell, kao što je prikazano u ovim uobičajenim primjerima:</span><span class="sxs-lookup"><span data-stu-id="01981-105">Alternatively, you can change individual users or attributes for synchronized users using powershell such as shown in these common examples:</span></span> 
- `Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com`

- `Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"`

- `Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com`
