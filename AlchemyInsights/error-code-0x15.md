---
title: Kod pogreške 0x15
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Ako vam se prikaže pogreška prilikom aktivacije sustava Office 2013 u implementacijama servisa udaljene radne površine (RDS-a), razmotrite Omogućivanje ADALA uređivanjem registra.
ms.openlocfilehash: deb2ac4b0fb6a7b2e0045ff1b0ba95ad6e5e4a3a
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47709179"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a>Pogreška prilikom aktivacije sustava Office 2013 na servisima udaljene radne površine

Ako vam se prikaže pogreška prilikom aktivacije sustava Office 2013 u implementacijama servisa udaljene radne površine (RDS-a), razmotrite Omogućivanje ADALA uređivanjem registra.
  
|**Ključ registra**|**Upišite**|**Vrijednost**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER \Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |REG_DWORD  <br/> |1  <br/> |

Dodatne informacije potražite u članku [Omogućivanje moderne provjere autentičnosti za Office 2013 na uređajima sa sustavom Windows](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  ADAL je prema zadanim postavkama omogućen u aplikacijama Microsoft 365 za Enterprise i Office 2016. Servisi udaljene radne površine (RDS) prethodno su imenovani terminalskim servisima.
  