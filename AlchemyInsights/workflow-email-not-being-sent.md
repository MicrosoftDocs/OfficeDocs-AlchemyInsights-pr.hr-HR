---
title: Tijek rada e-pošta se šalje
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 7/25/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 49c510668f4c73a71495b89ee9f810d4e7244da3
ms.sourcegitcommit: 631e527967f4d641bc9227642ffe38967ae87a00
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 08/09/2019
ms.locfileid: "36270664"
---
# <a name="workflow-email-is-not-being-sent"></a><span data-ttu-id="6b245-102">Tijek rada e-pošta se šalje</span><span class="sxs-lookup"><span data-stu-id="6b245-102">Workflow email is not being sent</span></span>

1. <span data-ttu-id="6b245-103">E-pošta s tijekovima rada se šalju sve korisnike ili samo određenim korisnicima ili vidjeti pogreške **poruku e-pošte nije moguće poslati. Provjerite je li e-pošta ima valjan primatelj**.</span><span class="sxs-lookup"><span data-stu-id="6b245-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

    <span data-ttu-id="6b245-104">Provjerite je li korisnik postoji u grupi dozvole **Sve osobe** (Popis korisničkih informacija) za tu zbirku web-mjesta.</span><span class="sxs-lookup"><span data-stu-id="6b245-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="6b245-105">Ogledni direktni URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx? MembershipGroupId = 0</span><span class="sxs-lookup"><span data-stu-id="6b245-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

    - <span data-ttu-id="6b245-106">Ako korisnik ne postoji, provjerite je li korisnik potpisano u stranicu.</span><span class="sxs-lookup"><span data-stu-id="6b245-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
    - <span data-ttu-id="6b245-107">Ako je vanjskog korisnika, provjerite njihove poziv je prihvaćen.</span><span class="sxs-lookup"><span data-stu-id="6b245-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
    - <span data-ttu-id="6b245-108">Ako korisnik ne postoji u grupi dozvole, provjerite je li adresa e-pošte točna.</span><span class="sxs-lookup"><span data-stu-id="6b245-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
    - <span data-ttu-id="6b245-109">Ako adresa e-pošte korisnicima ne Ovdje postavite, stvoriti primjerak upozorenja za tog korisnika koje navodi sinkronizaciju taj korisnički račun iz korisnički profili SharePoint zbirke web-mjesta.</span><span class="sxs-lookup"><span data-stu-id="6b245-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="6b245-110">E-pošta iz tijekova rada se šalju administratori zbirke web-mjesta, ali ne i drugim korisnicima i vidjeti pogrešku \*\*HTTP zabranjeno za <spam> <spam> \*\* <spam> <spam>.</span><span class="sxs-lookup"><span data-stu-id="6b245-110">Email from Workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <spam><spam>https://URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**<spam><spam>.</span></span>
 

    <span data-ttu-id="6b245-111">Pogledajte [Pristup odbijen kada grupira poslane e-pošte](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups).</span><span class="sxs-lookup"><span data-stu-id="6b245-111">See [Access Denied when sent email to groups](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups).</span></span>

    <span data-ttu-id="6b245-112">Također, provjerite je li značajka zbirke web-mjesta **način rada lockdown dozvole Ograničeni pristup korisnika** nije aktivan.</span><span class="sxs-lookup"><span data-stu-id="6b245-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>


## <a name="related-topics"></a><span data-ttu-id="6b245-113">Povezane teme</span><span class="sxs-lookup"><span data-stu-id="6b245-113">Related topics</span></span>
<span data-ttu-id="6b245-114">Želite li pokušajte Microsoft Flow u SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="6b245-114">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="6b245-115">Stvaranje toka</span><span class="sxs-lookup"><span data-stu-id="6b245-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="6b245-116">SharePoint i tijek</span><span class="sxs-lookup"><span data-stu-id="6b245-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 

