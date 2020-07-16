---
title: O identitetu na servisa Yammer
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/15/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6039"
- "9003111"
ms.openlocfilehash: 2c4c2c836d18d2ab45e2368e778c793277b18aa0
ms.sourcegitcommit: b677b85395b7244b2bf2b753468b696b4cf27c8d
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 07/16/2020
ms.locfileid: "45148179"
---
# <a name="about-identity-in-yammer"></a><span data-ttu-id="805b7-102">O identitetu na servisa Yammer</span><span class="sxs-lookup"><span data-stu-id="805b7-102">About identity in Yammer</span></span>

<span data-ttu-id="805b7-103">Preporučuje se da sve mreže poduzmu sljedeće korake kako bi izbjegle probleme povezane s identitetom:</span><span class="sxs-lookup"><span data-stu-id="805b7-103">It is recommended that all networks take the following steps to avoid identity-related issues:</span></span>

1. <span data-ttu-id="805b7-104">Nametni identitet sustava Office 365 nakon dodjele računa sustava Microsoft 365 za korisnike u azure AD da biste bili sigurni da se svi korisnici prijavljuju pomoću primarnog računa za Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="805b7-104">Enforce Office 365 identity after provisioning Microsoft 365 accounts for users in Azure AD to ensure that all users sign in by using their primary Microsoft 365 account.</span></span> <span data-ttu-id="805b7-105">Dodatne informacije potražite u članku [Nametanje identiteta sustava Office 365 za korisnike servisa Yammer](https://docs.microsoft.com/yammer/configure-your-yammer-network/enforce-office-365-identity).</span><span class="sxs-lookup"><span data-stu-id="805b7-105">For more info, see [Enforce Office 365 identity for Yammer users](https://docs.microsoft.com/yammer/configure-your-yammer-network/enforce-office-365-identity).</span></span>
2. <span data-ttu-id="805b7-106">Konsolidirajte više mreža servisa Yammer.</span><span class="sxs-lookup"><span data-stu-id="805b7-106">Consolidate multiple Yammer networks.</span></span> <span data-ttu-id="805b7-107">Naslijeđene konfiguracije servisa Yammer omogućuju povezivanje više mreža servisa Yammer s jednim klijentom.</span><span class="sxs-lookup"><span data-stu-id="805b7-107">Legacy Yammer configurations permit multiple Yammer networks to be connected to one tenant.</span></span> <span data-ttu-id="805b7-108">Dodatne informacije potražite u [odjeljku Migracija mreže – konsolidacija više mreža servisa Yammer](https://docs.microsoft.com/yammer/configure-your-yammer-network/consolidate-multiple-yammer-networks).</span><span class="sxs-lookup"><span data-stu-id="805b7-108">For more info, see [Network migration - Consolidate multiple Yammer networks](https://docs.microsoft.com/yammer/configure-your-yammer-network/consolidate-multiple-yammer-networks).</span></span>
3. <span data-ttu-id="805b7-109">Po želji, nametni licenciranje za Yammer da blokira korisnike sa servisa Yammer ako nemaju licencu.</span><span class="sxs-lookup"><span data-stu-id="805b7-109">Optionally, enforce licensing for Yammer to block users from Yammer if they don't have a license.</span></span> <span data-ttu-id="805b7-110">Dodatne informacije [potražite u odjeljku Upravljanje korisničkim licencama servisa Yammer u sustavu Office 365](https://docs.microsoft.com/yammer/manage-yammer-users/manage-yammer-licenses-in-office-365).</span><span class="sxs-lookup"><span data-stu-id="805b7-110">For more info, see [Manage Yammer user licenses in Office 365](https://docs.microsoft.com/yammer/manage-yammer-users/manage-yammer-licenses-in-office-365).</span></span>
4. <span data-ttu-id="805b7-111">Konačno, pregledajte popis korisnika za starije mreže servisa Yammer i obustavite naslijeđenu korisnike.</span><span class="sxs-lookup"><span data-stu-id="805b7-111">Finally, audit the user list for older Yammer networks and suspend legacy users.</span></span> <span data-ttu-id="805b7-112">Preporučuje se da obustavite (deaktivirati) korisnike umjesto da ih izbrišete jer je brisanje nepovratno.</span><span class="sxs-lookup"><span data-stu-id="805b7-112">It is recommended that you suspend (deactivate) users instead of deleting them, because deletion is irreversible.</span></span> <span data-ttu-id="805b7-113">Dodatne informacije potražite [u odjeljku Nadzor korisnika servisa Yammer u mrežama povezanima sa sustavom Office 365](https://docs.microsoft.com/yammer/manage-yammer-users/audit-users-connected-to-office-365) i [Uklanjanje korisnika](https://docs.microsoft.com/yammer/manage-yammer-users/add-block-or-remove-users#remove-users).</span><span class="sxs-lookup"><span data-stu-id="805b7-113">For more info, see [Audit Yammer users in networks connected to Office 365](https://docs.microsoft.com/yammer/manage-yammer-users/audit-users-connected-to-office-365) and [Remove users](https://docs.microsoft.com/yammer/manage-yammer-users/add-block-or-remove-users#remove-users).</span></span>

<span data-ttu-id="805b7-114">Konfiguriranjem servisa Yammer pomoću ovih koraka bit ćete spremni konfigurirati mrežu servisa Yammer za izvorni način rada za Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="805b7-114">By configuring Yammer using these steps, you'll also be ready to configure your Yammer network for Native Mode for Microsoft 365.</span></span> <span data-ttu-id="805b7-115">Dodatne informacije [potražite u odjeljku Konfiguriranje mreže servisa Yammer za izvorni način rada za Microsoft 365](https://docs.microsoft.com/yammer/configure-your-yammer-network/native-mode).</span><span class="sxs-lookup"><span data-stu-id="805b7-115">For more info, see [Configure your Yammer network for Native Mode for Microsoft 365](https://docs.microsoft.com/yammer/configure-your-yammer-network/native-mode).</span></span>