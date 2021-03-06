---
title: Implementacija timova kao samostalnih ili s novim ili postojećim instalacijama sustava Office
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000660"
- "2509"
ms.openlocfilehash: c3ca4365abc41509ccf602c5b9046655706840fc
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 09/15/2020
ms.locfileid: "47806751"
---
# <a name="deploying-teams-as-standalone-or-with-new-or-existing-office-installations"></a>Implementacija timova kao samostalnih ili s novim ili postojećim instalacijama sustava Office

Microsoftovi timovi sada su uključeni kao dio ***novih instalacija*** aplikacija Microsoft 365 za Enterprise, Microsoft 365 Apps za tvrtke i Office za Mac. Dodatne informacije potražite u članku [kada će se Microsoftovi timovi početi uvrstiti u nove instalacije sustava Office?](https://docs.microsoft.com/deployoffice/teams-install#when-will-microsoft-teams-start-being-included-with-new-installations-of-microsoft-365-apps)

Uz to, počevši od verzije 1906 u trenutnim kanalima, timovi će biti ***dodani u postojeće instalacije*** Microsoft 365 aplikacija za Enterprise (i Microsoft 365 Apps za tvrtke) na uređajima sa sustavom Windows kada postojeću instalaciju ažurirate na najnoviju verziju. Dodatne informacije potražite u članku [što je s postojećim instalacijama sustava Office?](https://docs.microsoft.com/deployoffice/teams-install#what-about-existing-installations-of-microsoft-365-apps)

> [!NOTE]
> Ako ne želite čekati ovaj raspored rasporeda, možete implementirati timove kao samostalne korisnike tako da [slijedite ove upute](https://docs.microsoft.com/MicrosoftTeams/msi-deployment)   ili korisnici mogu instalirati timove za sebe  [https://teams.microsoft.com/downloads](https://teams.microsoft.com/downloads) .

Ako vaša tvrtka ili ustanova nije spremna implementirati timove, imamo korake koje možete poduzeti da biste ***isključili timove*** iz [novih](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-microsoft-365-apps) ili [postojećih](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams) instalacija sustava Office. Ako želite da se timovi instaliraju, ali ne želite da se timovi automatski započinju za korisnika nakon instalacije, pročitajte članak [Sprječavanje automatskog pokretanja Microsoftovih timova nakon instalacije](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation).

Da biste ***deinstalirali timove*** na uređaju sa sustavom Windows, pročitajte članak [Deinstalacija Microsoftovih timova](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81). Da biste očistili Microsoftove timove iz više odredišnih strojeva ili korisnika, pročitajte članak [čišćenje Microsoftovih timova](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).

Ako koristite dijeljena računala, udaljene radne površine (RDS-ove) ili infrastrukturu virtualne radne površine (VDI), pročitajte članak [zajednički računalo i VDI okruženja s Microsoftovim timovima](https://docs.microsoft.com/deployoffice/teams-install#shared-computer-and-vdi-environments-with-microsoft-teams).

Ako koristite Office za Mac, pročitajte odjeljak [instalacije Microsoftovih timova na Macu](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).

> [!NOTE]
> Kada se timovi instaliraju, [automatski se ažuriraju](https://docs.microsoft.com/deployoffice/teams-install#feature-and-quality-updates-for-microsoft-teams) približno svaka dva tjedna novim značajkama i kvalitetnim ažuriranjima. 