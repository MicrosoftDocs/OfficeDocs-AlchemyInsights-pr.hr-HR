---
title: Stvaranje web-mjesta sustava SharePoint
ms.author: pebaum
author: pebaum
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ms.collection: Adm_O365
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "5200004"
- "3911416"
- "1386"
- "2303"
ms.assetid: e62b9f80-b017-42dc-9464-f4e32c19d6c9
ms.openlocfilehash: 5ebaa342ca9864bc31a9ef26eebcf42d96523871
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 09/15/2020
ms.locfileid: "47806931"
---
# <a name="create-a-sharepoint-site"></a>Stvaranje web-mjesta sustava SharePoint

Stvaranje web-mjesta i upravljanje njima s [aktivnih web-mjesta](https://admin.microsoft.com/sharepoint?page=sitemanagement&modern=true) u centru za administratore sustava SharePoint Dodatne informacije potražite u članku [Upravljanje web-mjestima u novom centru za administratore sustava SharePoint](https://docs.microsoft.com/sharepoint/manage-site-creation). 

## <a name="tips"></a>Savjeti

- Ne **možete** stvoriti web-mjesto s istim URL-om postojećeg web-mjesta. Ako ste izbrisali web-mjesto i želite ponovno koristiti URL, moguće je da izbrisane web-mjesto i dalje postoji u odjeljku [Izbrisane web-mjesta](https://admin.microsoft.com/sharepoint?page=recyclebin&modern=true). Web-mjesto će se morati trajno izbrisati da bi se ponovno koristila URL. Da biste u potpunosti uklonili web-mjesto pomoću komponente PowerShell, pročitajte primjer sustava cmdlet [Remove-SPWeb](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) .
- Neki korisnici možda neće moći stvoriti web-mjesto. [Pročitajte članak upravljanje stvaranjem web-mjesta u sustavu SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).
- Moguće je da se web-mjesto zapelo pri **stvaranju** više od očekivanog. Ako je prošlo više od 24 sata otkad ste prvi put vidjeli taj problem, prijavite karticu za podršku. U mnogim slučajevima već radimo na rješenju. Dodajte nam najmanje 24 sata da biste dovršili rješenje.
