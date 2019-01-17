---
title: Pretvaranje korisnički poštanski sandučić u zajednički poštanski sandučić?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ROBOTS: NOINDEX, NOFOLLOW
description: ''
ms.openlocfilehash: 22ad1b3fb818b40bcd77974031735f931e986968
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28280630"
---
<span data-ttu-id="6a91f-p101">Korisnički poštanski sandučić možete pretvoriti u zajednički poštanski sandučić samo ako korisnik ima Exchange licence. Nakon pretvaranja u poštanskom sandučiću, će nastaviti prikazivati na popisu aktivnih korisnika jer taj popis uključuje zajednički poštanski sandučići. Međutim, pretvorene poštanski sandučić također će prikazati u popisu zajednički poštanski sandučić.</span><span class="sxs-lookup"><span data-stu-id="6a91f-p101">You can only convert a user mailbox to a shared mailbox if the user has an Exchange license. After the mailbox is converted, it will continue to show up in the active users list because that list includes shared mailboxes. However, the converted mailbox will also show up in the shared mailbox list.</span></span> 
  
<span data-ttu-id="6a91f-p102">Ako pokušate pretvoriti poštanskog sandučića u Exchange administratorske konzole i pretvorba ne uspije, očistite predmemoriju preglednika i kolačiće i pokušajte ponovno. Ako ga i dalje ne radi, pokušajte pretvoriti u poštanski sandučić Exchange ljuske za upravljanje pokretanjem sljedeće naredbe:</span><span class="sxs-lookup"><span data-stu-id="6a91f-p102">If you try to convert a mailbox in the Exchange Admin Console and the conversion fails, clear your browser cache and cookies and try again. If it still isn't working, try converting the mailbox in the Exchange Management Shell by running the following command:</span></span>
  
```
Set-Mailbox -Type Shared
```

<span data-ttu-id="6a91f-107">Dodatne informacije o pretvorbi poštanski sandučić je dostupna u [pretvoriti korisnički poštanski sandučić zajednički poštanski sandučić](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).</span><span class="sxs-lookup"><span data-stu-id="6a91f-107">More mailbox conversion information is available in [Convert a user mailbox to a shared mailbox](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).</span></span>
  