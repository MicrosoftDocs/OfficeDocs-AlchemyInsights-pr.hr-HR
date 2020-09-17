---
title: Pitanja o korištenju alata za implementaciju sustava Office (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: e9f7581fd21cf5ca2d712038c4b73b67d08f3a76
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 09/15/2020
ms.locfileid: "47774883"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>Pitanja o korištenju alata za implementaciju sustava Office (ODT)

Preuzmite alat za implementaciju sustava Office iz [Microsoftova centra za preuzimanje](https://go.microsoft.com/fwlink/p/?LinkID=626065).
  
Kada preuzmete datoteku, pokrenite samoizdvajanje izvršnu datoteku koja sadrži izvršne alate za implementaciju sustava Office (setup.exe) te oglednu konfiguracijsku datoteku (configuration.xml).
  
 **Da biste isključili ili uklonili aplikacije Microsoft 365 za Enterprise Products sa klijentskih računala, učinite sljedeće:**
  
Prilikom instalacije aplikacija Microsoft 365 za Enterprise možete isključiti specifične proizvode. Da biste to učinili, slijedite korake za instaliranje sustava Office s ODT-om, ali u konfiguracijskoj datoteci uvrstite element ExcludeApp. Ta konfiguracijska datoteka, primjerice, instalira sve aplikacije Microsoft 365 za tvrtke, osim programa Publisher:
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[Pregled alata za implementaciju sustava Office](https://docs.microsoft.com/deployoffice/overview-office-deployment-tool)
  

