---
title: Automatski Šifriraj određene poruke e-pošte u sustavu Office 365
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/24/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000078"
- "7342"
ms.openlocfilehash: e4b2f4ffcacf03e145b4c6d5ff6e73a75cb7c184
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 03/11/2021
ms.locfileid: "50743696"
---
# <a name="automatically-encrypt-certain-office-365-email-messages"></a><span data-ttu-id="45023-102">Automatski Šifriraj određene poruke e-pošte u sustavu Office 365</span><span class="sxs-lookup"><span data-stu-id="45023-102">Automatically encrypt certain Office 365 email messages</span></span>

<span data-ttu-id="45023-103">Možete automatski šifrirati poruke koje korisnici šalju određenim vanjskim osobama ili organizacijama.</span><span class="sxs-lookup"><span data-stu-id="45023-103">You can automatically encrypt messages that users send to certain external people or organizations.</span></span> <span data-ttu-id="45023-104">Da biste to učinili, slijedite sljedeće korake:</span><span class="sxs-lookup"><span data-stu-id="45023-104">To do this, perform the following steps:</span></span>

1. <span data-ttu-id="45023-105">U [centru za administratore sustava Exchange](https://outlook.office365.com/ecp/)odaberite **tijek pošte > pravila**.</span><span class="sxs-lookup"><span data-stu-id="45023-105">From the [Exchange admin center](https://outlook.office365.com/ecp/), choose **mail flow > rules**.</span></span> 
2. <span data-ttu-id="45023-106">Kliknite ikonu **Novo (+)** , a zatim kliknite **Primijeni šifriranje poruka i zaštita prava u sustavu Office 365 na poruke**.</span><span class="sxs-lookup"><span data-stu-id="45023-106">Click the **New (+)** icon, and then click **Apply Office 365 Message Encryption and rights protection to messages**.</span></span>
3. <span data-ttu-id="45023-107">U **naziv** unesite naziv pravila, primjerice *Šifriraj poruke poslane u DrToniRamos@gmail.com*.</span><span class="sxs-lookup"><span data-stu-id="45023-107">In **Name**, enter a name for the rule, such as *Encrypt messages sent to DrToniRamos@gmail.com*.</span></span>
4. <span data-ttu-id="45023-108">**Ako primijenite ovo pravilo**, odaberite **primatelja > je ta osoba**.</span><span class="sxs-lookup"><span data-stu-id="45023-108">In **Apply this rule if**, choose **The recipient > is this person**.</span></span> 
5. <span data-ttu-id="45023-109">U prozoru **Odabir članova** odaberite ime osobe na koju želite primijeniti pravilo šifriranja, a zatim kliknite **Dodaj**.</span><span class="sxs-lookup"><span data-stu-id="45023-109">In the **Select Members** window, select the name of the person you want the encryption rule to apply to, and then click **add**.</span></span> 
6. <span data-ttu-id="45023-110">Kada završite s dodavanjem korisnika, kliknite **u redu**.</span><span class="sxs-lookup"><span data-stu-id="45023-110">When you're done adding users, click **OK**.</span></span>
7. <span data-ttu-id="45023-111">Pokraj polja **učinite sljedeće** kliknite **Odaberi jednu**.</span><span class="sxs-lookup"><span data-stu-id="45023-111">Next to the **Do the following** field, click **Select one**.</span></span> 
8. <span data-ttu-id="45023-112">Na padajućem izborniku **predloška RMS** -a odaberite **Šifriraj**, a zatim kliknite **u redu**.</span><span class="sxs-lookup"><span data-stu-id="45023-112">In the **RMS template** drop-down menu, select **Encrypt**, and then click **OK**.</span></span> <span data-ttu-id="45023-113">(Ako ne vidite tu mogućnost, to znači da vaš plan ne obuhvaća automatsko šifriranje.</span><span class="sxs-lookup"><span data-stu-id="45023-113">(If you don't see this option, it means your plan doesn't include automatic encryption.</span></span> <span data-ttu-id="45023-114">No, možete ga dodati!)</span><span class="sxs-lookup"><span data-stu-id="45023-114">But you can add it!)</span></span>
9. <span data-ttu-id="45023-115">Odaberite bilo koji neobavezni odabir (s popisa neobaveznih odabira koje možete učiniti u ovom trenutku, od kojih se mnogi mogu vratiti uz zadanu postavku za jednostavnost).</span><span class="sxs-lookup"><span data-stu-id="45023-115">Choose any optional selection (from a list of optional selections that you can make at this point, many of which can be left with the default setting for simplicity).</span></span>
10. <span data-ttu-id="45023-116">Kliknite **Spremi**.</span><span class="sxs-lookup"><span data-stu-id="45023-116">Click **Save**.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="45023-117">Uvijek se možete vratiti i urediti to pravilo kasnije.</span><span class="sxs-lookup"><span data-stu-id="45023-117">You can always come back and edit this rule later.</span></span>

<span data-ttu-id="45023-118">Dodatne informacije o stvaranju pravila šifriranja potražite [u članku definiranje pravila tijeka pošte za šifriranje poruka e-pošte u sustavu Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).</span><span class="sxs-lookup"><span data-stu-id="45023-118">For more information about creating rules for encryption, see [Define mail flow rules to encrypt email messages in Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).</span></span>

