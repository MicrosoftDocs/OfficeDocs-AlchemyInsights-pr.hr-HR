---
title: Certifikat APNS za postavljanje aplikacije Intune za iOS
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000654"
- "3543"
ms.openlocfilehash: 66590b8a063e74e80bbe3e1e497c596d63a54ece
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51824031"
---
# <a name="intune-ios-set-up-apns-certificate"></a><span data-ttu-id="55bfe-102">Certifikat APNS za postavljanje aplikacije Intune za iOS</span><span class="sxs-lookup"><span data-stu-id="55bfe-102">Intune iOS set up APNS certificate</span></span>

<span data-ttu-id="55bfe-103">Certifikat Apple MDM Push (poznat i pod nazivom certifikat Appleova servisa za automatske obavijesti (APNS)) nije konfiguriran na vašoj pretplati.</span><span class="sxs-lookup"><span data-stu-id="55bfe-103">An Apple MDM Push certificate (also known as an Apple Push Notification Service (APNS) certificate) has not been configured on your subscription.</span></span>

<span data-ttu-id="55bfe-104">Bez konfiguriranog certifikata Apple MDM Push, nije moguće registrirati uređaje sa sustavom iOS i MacOS niti upravljati njima.</span><span class="sxs-lookup"><span data-stu-id="55bfe-104">Without an Apple MDM Push certificate configured, you'll be unable to enroll and manage iOS and MacOS devices.</span></span> <span data-ttu-id="55bfe-105">Kada dodate certifikat u aplikaciju Intune, korisnici će moći instalirati aplikaciju Company Portal i registrirati svoje uređaje sa sustavom iOS.</span><span class="sxs-lookup"><span data-stu-id="55bfe-105">After you add the certificate to Intune, your users can install the Company Portal app to enroll their iOS devices.</span></span>

<span data-ttu-id="55bfe-106">Detaljne upute za dodavanje certifikata APNS klijentu aplikacije Intune potražite u sadržaju na sljedećoj vezi:</span><span class="sxs-lookup"><span data-stu-id="55bfe-106">For a step-by-step guide to adding an APNS certificate to your Intune tenant, please review the content on the following link:</span></span>

- [<span data-ttu-id="55bfe-107">Preuzimanje certifikata Apple MDM Push</span><span class="sxs-lookup"><span data-stu-id="55bfe-107">Get an Apple MDM Push certificate</span></span>](https://docs.microsoft.com/mem/intune/enrollment/apple-mdm-push-certificate-get)

<span data-ttu-id="55bfe-108">Informacije o otklanjanju poteškoća s certifikatom Appleova servisa za automatske obavijesti (APNs) potražite u objavi na blogu: [Intune i certifikat APNs: najčešća pitanja i česti problemi](https://techcommunity.microsoft.com/t5/Intune-Customer-Success/Intune-and-the-APNs-certificate-FAQ-and-common-issues/ba-p/280121)</span><span class="sxs-lookup"><span data-stu-id="55bfe-108">If you are having issues with the Apple Push Notification certificate (APNs) refer to this blog post: [Intune and the APNs certificate: FAQ and common issues](https://techcommunity.microsoft.com/t5/Intune-Customer-Success/Intune-and-the-APNs-certificate-FAQ-and-common-issues/ba-p/280121)</span></span>
