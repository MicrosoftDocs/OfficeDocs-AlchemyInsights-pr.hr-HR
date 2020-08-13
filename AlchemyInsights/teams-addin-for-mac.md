---
title: Dodatak za timove za Mac
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 08/10/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6173"
- "9003233"
ms.openlocfilehash: 74bd424f71a59b80a91b960b815363668bee7036
ms.sourcegitcommit: 1361b2b37fd0201502a1a3547084961de284a3fc
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 08/11/2020
ms.locfileid: "46629407"
---
# <a name="teams-add-in-for-mac"></a><span data-ttu-id="f64be-102">Dodatak za timove za Mac</span><span class="sxs-lookup"><span data-stu-id="f64be-102">Teams add-in for Mac</span></span>

<span data-ttu-id="f64be-103">Da biste otklonili poteškoće s dodacima za korisnike operacijskog sustava Mac koje nema, slijedite ove korake:</span><span class="sxs-lookup"><span data-stu-id="f64be-103">To troubleshoot a missing Teams add-in for Mac operating system users, follow these steps:</span></span>

<span data-ttu-id="f64be-104">**Prvi korak:** Ako imate hibridnu razmjenu lokalnih sustava (2016 CU3 ili noviji), upotrijebite alat za Test-HMA.ps1 da biste potvrdili da je hibridna moderna provjera autentičnosti ispravno konfigurirana.</span><span class="sxs-lookup"><span data-stu-id="f64be-104">**Step 1:** If you have Hybrid Exchange On-Premises (2016 CU3 or later required), use the Test-HMA.ps1 tool to confirm that Hybrid Modern Authentication is correctly configured.</span></span> <span data-ttu-id="f64be-105">Dodatne informacije potražite u članku [Provjera valjanosti hibridnih modernih postavki provjere autentičnosti za Outlook za iOS i Android](https://aka.ms/AA980zq).</span><span class="sxs-lookup"><span data-stu-id="f64be-105">For more info, see [Validating Hybrid Modern Authentication setup for Outlook for iOS and Android](https://aka.ms/AA980zq).</span></span>  

<span data-ttu-id="f64be-106">**Notes** Koristite oblik adrese UPN (na primjer, [username@contoso.com](mailto:username@contoso.com)), a ne domena\usernaziv.</span><span class="sxs-lookup"><span data-stu-id="f64be-106">**Note** Use the UPN address format (for example, [username@contoso.com](mailto:username@contoso.com)), not domain\username.</span></span> <span data-ttu-id="f64be-107">Učinite to čak i za korisnike s poštanskim sandučićima sustava Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f64be-107">Do this even for users with Exchange Online mailboxes.</span></span>

<span data-ttu-id="f64be-108">**Drugi korak:** Neka korisnik krene na račune **alata**  >  **Accounts**... u programu Outlook za Mac, a zatim pronađite i odaberite račun.</span><span class="sxs-lookup"><span data-stu-id="f64be-108">**Step 2:** Have the user go to **Tools** > **Accounts**... in Outlook for Mac, and find and select the account.</span></span> <span data-ttu-id="f64be-109">Potvrdite korisničko ime koje je navedeno u obliku UPN (primjerice, [username@contoso.com](mailto:username@contoso.com)).</span><span class="sxs-lookup"><span data-stu-id="f64be-109">Confirm the username listed is in UPN format (for example, [username@contoso.com](mailto:username@contoso.com)).</span></span>

<span data-ttu-id="f64be-110">Treći **korak:** Potvrdite da je korisnik licencirani Microsoft timovi.</span><span class="sxs-lookup"><span data-stu-id="f64be-110">**Step 3:** Confirm the user is a licensed Microsoft Teams user.</span></span> <span data-ttu-id="f64be-111">Korisnik mora koristiti pretplatu na Office 365 za Mac, verziju proizvoda 16,24 ili noviji.</span><span class="sxs-lookup"><span data-stu-id="f64be-111">The user must be using the Office 365 for Mac subscription, product version 16.24 or later.</span></span>