---
title: 1336 Mapa RecoverableItems je puna
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1336"
- "3700003"
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: fb10b792981040bdcf4661b8aff30733c2438212
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43720244"
---
# <a name="the-recoverable-items-folder-is-full"></a><span data-ttu-id="45ebf-102">Mapa Oporavljene stavke puna je</span><span class="sxs-lookup"><span data-stu-id="45ebf-102">The Recoverable Items folder is full</span></span>

<span data-ttu-id="45ebf-103">Za poštanske sandučiće sustava Exchange Online zadano ograničenje pohrane za mapu Oporavljene stavke je 30 GB.</span><span class="sxs-lookup"><span data-stu-id="45ebf-103">For Exchange Online mailboxes, the default storage limit for the Recoverable Items folder is 30 GB.</span></span> <span data-ttu-id="45ebf-104">Ograničenje prostora za pohranu za mapu Oporavljene stavke automatski se povećava na 100 GB ako je poštanski sandučić smješten na čuvanje parnice, čuvanje elektroničkih dokumenata ili je dodijeljeno pravilima zadržavanja.</span><span class="sxs-lookup"><span data-stu-id="45ebf-104">The storage limit for the Recoverable Items folder is automatically increased to 100 GB if the mailbox is placed on Litigation Hold, eDiscovery hold, or is assigned to a retention policy.</span></span>

<span data-ttu-id="45ebf-105">Kada mapa Oporavljene stavke dosegne ograničenje pohrane, funkcija poštanskog sandučića utječe na sljedeće načine:</span><span class="sxs-lookup"><span data-stu-id="45ebf-105">When the Recoverable Items folder reaches the storage limit, mailbox functionality is affected in the following ways:</span></span>

- <span data-ttu-id="45ebf-106">Korisnik ne može izbrisati stavke iz poštanskog sandučića.</span><span class="sxs-lookup"><span data-stu-id="45ebf-106">The user can't delete items from the mailbox.</span></span>

- <span data-ttu-id="45ebf-107">Pomoćnik za upravljane mape ne može izbrisati stavke na temelju oznake zadržavanja ili postavki upravljanih mapa.</span><span class="sxs-lookup"><span data-stu-id="45ebf-107">The Managed Folder Assistant can't delete items based on retention tag or managed folder settings.</span></span>

- <span data-ttu-id="45ebf-108">Za poštanske sandučiće kojima je omogućen oporavak jedne stavke ili su stavljeni na čekanje, postupak zaštite stranice za kopiranje na pisati ne može održavati verzije stavki koje je korisnik uredio.</span><span class="sxs-lookup"><span data-stu-id="45ebf-108">For mailboxes that have Single Item Recovery enabled or are placed on hold, the copy-on-write page protection process can't maintain versions of items edited by the user.</span></span>

- <span data-ttu-id="45ebf-109">Za poštanske sandučiće kojima je omogućeno zapisivanje nadzora poštanskog sandučića, stavke zapisnika nadzora poštanskog sandučića ne mogu se spremiti u podmapu Nadzori u mapi Stavke koje se mogu oporaviti.</span><span class="sxs-lookup"><span data-stu-id="45ebf-109">For mailboxes that have mailbox audit logging enabled, no mailbox audit log entries can be saved in the Audits subfolder in the Recoverable Items folder.</span></span>

<span data-ttu-id="45ebf-110">Za poštanske sandučiće koji nisu na čekanju `Search-Mailbox -SearchDumpsterOnly -DeleteContent` administratori mogu koristiti naredbu u komponente Exchange Online PowerShell za brisanje stavki u mapi Stavke koje se mogu oporaviti.</span><span class="sxs-lookup"><span data-stu-id="45ebf-110">For mailboxes that aren't on hold, admins can use the `Search-Mailbox -SearchDumpsterOnly -DeleteContent` command in Exchange Online PowerShell to delete items in the Recoverable Items folder.</span></span> <span data-ttu-id="45ebf-111">Dodatne informacije potražite u sljedećim temama:</span><span class="sxs-lookup"><span data-stu-id="45ebf-111">For more information, see the following topics:</span></span>

- [<span data-ttu-id="45ebf-112">Traženje i brisanje poruka</span><span class="sxs-lookup"><span data-stu-id="45ebf-112">Search for and delete messages</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)

- [<span data-ttu-id="45ebf-113">Pretraživanje poštanskog sandučića</span><span class="sxs-lookup"><span data-stu-id="45ebf-113">Search-Mailbox</span></span>](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

<span data-ttu-id="45ebf-114">Za poštanske sandučiće koji su na čekanju administratori moraju ukloniti čekanje da bi mogli izbrisati stavke iz mape Stavke koje se mogu oporaviti.</span><span class="sxs-lookup"><span data-stu-id="45ebf-114">For mailboxes that are on hold, admins have to remove the hold before they can deleted items from the Recoverable Items folder.</span></span> <span data-ttu-id="45ebf-115">Dodatne informacije [potražite u odjeljku Brisanje stavki u mapi Stavke koje se mogu oporaviti u oblaku na čekanju](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="45ebf-115">For more information, see [Delete items in the Recoverable Items folder of cloud-based mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span></span>

<span data-ttu-id="45ebf-116">Da bi spriječili da mapa Oporavive stavke postane puna, administratori mogu povećati ograničenje pohrane mape Oporavljene stavke za poštanske sandučiće na čekanju i postaviti pravila zadržavanja poštanskog sandučića koja premješta stavke iz mape Stavke koje se mogu oporaviti u poštanski sandučić arhive korisnika.</span><span class="sxs-lookup"><span data-stu-id="45ebf-116">To help prevent the Recoverable Items folder from becoming full, admins can increase the storage limit of the Recoverable Items folder for mailboxes on hold and set up a mailbox retention policy that moves items from the Recoverable Items folder to the user's archive mailbox.</span></span> <span data-ttu-id="45ebf-117">Pogledajte [Povećanje kvote Oporavljenih stavki za poštanske sandučiće na čekanju](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="45ebf-117">See [Increase the Recoverable Items quota for mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span></span>
