---
title: Zamijeni vaš Classic korijensko web-mjesto s Moderna web-mjesta
ms.author: efrene
author: efrene
ms.date: 8/6/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000687"
- "2579"
ms.openlocfilehash: ffb1466fe436d6cab7ae5fdd60c671f5dd2654dd
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36501071"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a><span data-ttu-id="75923-102">Zamijeni vaš Classic korijensko web-mjesto s Moderna web-mjesta</span><span class="sxs-lookup"><span data-stu-id="75923-102">Swap your Classic root site with a Modern site</span></span>

<span data-ttu-id="75923-103">Ako je vaše okruženje postavljena prije Travanj 2019 korijensko web-mjesto možete promijeniti Moderna web-mjesta pomoću Microsoft PowerShell:</span><span class="sxs-lookup"><span data-stu-id="75923-103">If your environment was set up before April 2019, you can change your root site to a modern site by using Microsoft PowerShell:</span></span>

- <span data-ttu-id="75923-104">Ako imate različite web-mjesta koje želite koristiti kao korijen web-mjesta, s njim možete zamijeniti (Zamijeni) korijenskog web-mjesta.</span><span class="sxs-lookup"><span data-stu-id="75923-104">If you have a different site that you want to use as your root site, you can replace (swap) the root site with it.</span></span> 
    - <span data-ttu-id="75923-105">Koristite [Pozovite SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) Zamijeni mjesto web-mjesta s drugog web-mjesta vrijeme arhiviranja izvornog web-mjesta.</span><span class="sxs-lookup"><span data-stu-id="75923-105">Use [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) to swap the location of a site with another site while archiving the original site.</span></span> <span data-ttu-id="75923-106">Dostupno za timskog web-mjesta (nije povezano s grupom) i komunikacije web-mjesta.</span><span class="sxs-lookup"><span data-stu-id="75923-106">Available for both Team Site (not connected to a group) and Communication Site.</span></span> 

- <span data-ttu-id="75923-107">Dodatne mogućnosti će biti uvedene uskoro koji će vam omogućiti zadržati pomoću sadržaja na web-mjestu, ali pretvaranje postojećeg web-mjesta komunikacije web-mjesta.</span><span class="sxs-lookup"><span data-stu-id="75923-107">Additional capabilities will be introduced soon that will allow you to keep using the content on the site, but convert the existing site to a communication site.</span></span> 
>[!Important]
><span data-ttu-id="75923-108">Ove mogućnosti će biti poslednjeg postupno.</span><span class="sxs-lookup"><span data-stu-id="75923-108">These capabilities will be rolled out gradually.</span></span> <span data-ttu-id="75923-109">Nastavite provjerite Office 365 poruku centar za ažuriranja.</span><span class="sxs-lookup"><span data-stu-id="75923-109">Continue to check the Office 365 Message Center for updates.</span></span> 

## <a name="known-issues-with-swapping-sites"></a><span data-ttu-id="75923-110">Poznati problemi s zamjene web-mjesta</span><span class="sxs-lookup"><span data-stu-id="75923-110">Known issues with swapping sites</span></span>

- <span data-ttu-id="75923-111">Ciljno mjesto može vratiti "nije pronađen" Pogreška (HTTP 404) za kratkog vremenskog razdoblja.</span><span class="sxs-lookup"><span data-stu-id="75923-111">The target site may return a "not found" (HTTP 404) error for a short period of time.</span></span>
- <span data-ttu-id="75923-112">Sadržaj će morati biti ponovno pretražiti da radi indeksiranja da biste ažurirali indeks pretraživanja.</span><span class="sxs-lookup"><span data-stu-id="75923-112">Content will need to be recrawled to update the search index.</span></span> <span data-ttu-id="75923-113">Postoji bez ručnog korak potreban - to će učiniti automatski.</span><span class="sxs-lookup"><span data-stu-id="75923-113">There is no manual step required - this will be done automatically.</span></span>
- <span data-ttu-id="75923-114">Ništa zavise "statički" veze (poput datoteka sinkronizacije datoteka i OneNote) morat ćete ručno ispraviti.</span><span class="sxs-lookup"><span data-stu-id="75923-114">Anything dependent on "static" links (such as File Sync and OneNote files) will need to be manually corrected.</span></span>
- <span data-ttu-id="75923-115">Izvorišnog web-mjesta je organizacijske vijesti, ažurirajte URL.</span><span class="sxs-lookup"><span data-stu-id="75923-115">If the source site was an organizational news site, update the URL.</span></span><span data-ttu-id="75923-116">Nabavite popis svih web-mjesta organizacijske vijesti.</span><span class="sxs-lookup"><span data-stu-id="75923-116"> Get a list of all organizational news sites.</span></span>
- <span data-ttu-id="75923-117">Web-mjesta Project Server možda morati provjeriti da biste bili sigurni da su i dalje povezani ispravno.</span><span class="sxs-lookup"><span data-stu-id="75923-117">Project Server sites may need to be validated to ensure that they are still associated correctly.</span></span>




