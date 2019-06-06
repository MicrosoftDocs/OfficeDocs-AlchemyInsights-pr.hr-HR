---
title: Upoznavanje s programom SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 7ae05f21-eb16-4d71-9e19-4f097eb100d2
ms.openlocfilehash: a44b2c7b26895e09c24df772f1ada9a2e3483747
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 06/05/2019
ms.locfileid: "34735975"
---
# <a name="workflows-in-sharepoint"></a><span data-ttu-id="0a2f4-102">Tijekovi rada u programu SharePoint</span><span class="sxs-lookup"><span data-stu-id="0a2f4-102">Workflows in SharePoint</span></span>

<span data-ttu-id="0a2f4-103">Ako tijekovi rada SharePoint su slanja poruke e-pošte, vaša organizacija možda naišao Exchange Online ograničenja pošiljatelja.</span><span class="sxs-lookup"><span data-stu-id="0a2f4-103">If SharePoint workflows are not sending emails, your organization may have encountered the Exchange Online sender limits.</span></span>

<span data-ttu-id="0a2f4-104">'Tijek rada je obustavljena' poruka o pogrešci može pojaviti ako imate jednu od sljedećih stavki:</span><span class="sxs-lookup"><span data-stu-id="0a2f4-104">'Workflow is Suspended' error message may occur if you have one of the following items:</span></span>

- <span data-ttu-id="0a2f4-105">Imate tijeka rada u SharePoint Online koji koriste SharePoint 2010 ili vrsta platformi SharePoint 2013 tijeka rada.</span><span class="sxs-lookup"><span data-stu-id="0a2f4-105">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span>

- <span data-ttu-id="0a2f4-106">Tijek rada konfiguriran za slanje poruka e-pošte prilagođenih više od 200 korisnicima na vrijeme, više od 10 000 primatelja po danu ili na više od 30 poruka u minuti.</span><span class="sxs-lookup"><span data-stu-id="0a2f4-106">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span>

<span data-ttu-id="0a2f4-107">Kad pokrenete tijek rada, poruka e-pošte nije poslana i Primijetit ćete poruku o pogrešci, interni Status je postavljen na Suspended ili nije moguće poslati primatelju prikazuje.</span><span class="sxs-lookup"><span data-stu-id="0a2f4-107">When you run the workflow, the email message isn't sent, and you notice the error message, Internal Status is set to Suspended or Unable to send to a recipient is displayed.</span></span>

<span data-ttu-id="0a2f4-108">Za dodatne informacije pogledajte sljedeći [članak](https://support.office.com/en-us/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US).</span><span class="sxs-lookup"><span data-stu-id="0a2f4-108">For more information, please refer to the following [article](https://support.office.com/en-us/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US).</span></span>

