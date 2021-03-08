---
title: Uređaj writeback
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003257"
- "8279"
ms.openlocfilehash: f1a8dba19d220e1154549507801c813f56fe5cdd
ms.sourcegitcommit: 0470a728d184ceb89d1419f7ed57166e07bb778b
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 02/15/2021
ms.locfileid: "50256702"
---
# <a name="device-writeback"></a><span data-ttu-id="66595-102">Uređaj writeback</span><span class="sxs-lookup"><span data-stu-id="66595-102">Device Writeback</span></span>

<span data-ttu-id="66595-103">Writeback uređaja koristi se u sljedećim scenarijima:</span><span class="sxs-lookup"><span data-stu-id="66595-103">Device Writeback is used in the following scenarios:</span></span>

- <span data-ttu-id="66595-104">Omogućavanje [servisa Windows Hello za tvrtke pomoću hibridnog certificiranja pouzdanih certifikata](https://docs.microsoft.com/windows/security/identity-protection/hello-for-business/hello-hybrid-cert-trust-prereqs#device-registration)</span><span class="sxs-lookup"><span data-stu-id="66595-104">Enable [Windows Hello for Business using hybrid certificate trust deployment](https://docs.microsoft.com/windows/security/identity-protection/hello-for-business/hello-hybrid-cert-trust-prereqs#device-registration)</span></span>
- <span data-ttu-id="66595-105">Omogućivanje uvjetnog pristupa na temelju uređaja na ADMINISTRATARE (2012 R2 ili novije) zaštićene aplikacije (Trust strana)</span><span class="sxs-lookup"><span data-stu-id="66595-105">Enable Conditional Access based on devices to ADFS (2012 R2 or higher) protected applications (relying party trusts)</span></span>

    > [!NOTE]
    > <span data-ttu-id="66595-106">Za writeback uređaja potrebna je pretplata na Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="66595-106">A subscription to Azure AD Premium is required for device writeback.</span></span>

<span data-ttu-id="66595-107">Time se omogućuje dodatna sigurnost i garancija da se pristup aplikacijama dodjeljuje samo pouzdanim uređajima.</span><span class="sxs-lookup"><span data-stu-id="66595-107">This provides additional security and assurance that access to applications is granted only to trusted devices.</span></span> <span data-ttu-id="66595-108">Dodatne informacije o uvjetnom pristupu potražite u članku [Upravljanje rizikom uz uvjetni pristup](https://docs.microsoft.com/azure/active-directory/conditional-access/overview) i [Postavljanje lokalnog uvjetnog pristupa pomoću servisa Azure Active Directory registracija uređaja](https://docs.microsoft.com/azure/active-directory/devices/overview).</span><span class="sxs-lookup"><span data-stu-id="66595-108">For more information on Conditional Access, see [Managing Risk with Conditional Access](https://docs.microsoft.com/azure/active-directory/conditional-access/overview) and [Setting up On-premises Conditional Access using Azure Active Directory Device Registration](https://docs.microsoft.com/azure/active-directory/devices/overview).</span></span>

<span data-ttu-id="66595-109">Dodatne informacije o omogućivanju uređaja writeback za uređaje potražite u članku [Omogućivanje programa writeback uređaja](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-device-writeback).</span><span class="sxs-lookup"><span data-stu-id="66595-109">For more information on Enabling Device Writeback for Devices, see [Enable Device Writeback](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-device-writeback).</span></span>