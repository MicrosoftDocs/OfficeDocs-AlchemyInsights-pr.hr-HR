---
title: Omogući nadzor poštanskog sandučića
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: bd94ec10f9df2e72ec6e3d8552d2eb80212a9d78
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28279566"
---
# <a name="enable-mailbox-auditing"></a>Omogući nadzor poštanskog sandučića

Da biste omogućili nadzor poštanskog sandučića za jednog korisnika ili cijeloj organizaciji sljedeće Cmdletovi morate pokrenuti iz Remote Shell uštede energije:
  
 **Jedan korisnik**
  
Skup-poštanski sandučić - identitet "Dow Ane" - AuditEnabled $true
  
 **Organization**
  
Dohvati poštanski sandučić - ResultSize neograničen - filtriranje {RecipientTypeDetails - eq "UserMailbox"} | Skup poštanski sandučić - AuditEnabled $true
  
[Dodatne informacije](https://support.office.com/article/aaca8987-5b62-458b-9882-c28476a66918)
  

