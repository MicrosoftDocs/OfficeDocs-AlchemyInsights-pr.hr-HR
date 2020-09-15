---
title: Problemi s prijavom u aplikacije Microsoft 365
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2559"
ms.openlocfilehash: 57a4df23dc66eaf4c283dde741be6f415939633d
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47695171"
---
# <a name="fixing-the-microsoft-365-apps-your-computers-trusted-platform-module-is-not-functioning-properly-message"></a><span data-ttu-id="a0043-102">Ispravljanje aplikacija Microsoft 365 "Trusted Platform modul za vaše računalo ne funkcionira pravilno" poruka</span><span class="sxs-lookup"><span data-stu-id="a0043-102">Fixing the Microsoft 365 apps "Your computer's Trusted Platform module is not functioning properly" message</span></span>

<span data-ttu-id="a0043-103">Da biste ispravili tu pogrešku, pokušajte sljedeće:</span><span class="sxs-lookup"><span data-stu-id="a0043-103">To fix this error, try the following:</span></span>

- <span data-ttu-id="a0043-104">Instalirajte najnovija ažuriranja za [Windows](https://support.microsoft.com/help/4027667/windows-10-update) i [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span><span class="sxs-lookup"><span data-stu-id="a0043-104">Install the latest updates for [Windows](https://support.microsoft.com/help/4027667/windows-10-update) and [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span></span>
- <span data-ttu-id="a0043-105">[Poništite vjerodajnice sustava Office](https://docs.microsoft.com/eoffice/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomoću upravitelja vjerodajnica za Windows.</span><span class="sxs-lookup"><span data-stu-id="a0043-105">[Clear Office credentials](https://docs.microsoft.com/eoffice/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="a0043-106">**Upozorenje:** Putevi registra za Office 2016 promijenili su se u 16,0.</span><span class="sxs-lookup"><span data-stu-id="a0043-106">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="a0043-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="a0043-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>
- <span data-ttu-id="a0043-108">Isprobajte [postupak oporavka korisnika](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) da biste riješili pogreške pouzdanih Platform MODULE (TPM-a).</span><span class="sxs-lookup"><span data-stu-id="a0043-108">Try the [user recovery process](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) to fix Trusted Platform Module (TPM) failures.</span></span>
- <span data-ttu-id="a0043-109">Postavite EnableADAL = 0 pomoću sljedećih koraka:</span><span class="sxs-lookup"><span data-stu-id="a0043-109">Set the EnableADAL = 0 using the following steps:</span></span>  
    1. <span data-ttu-id="a0043-110">Desnom tipkom miša kliknite gumb Start sustava Windows, odaberite **Pokreni**, upišite **regedit**, a zatim odaberite **u redu**.</span><span class="sxs-lookup"><span data-stu-id="a0043-110">Right-click the Windows Start button, choose **Run**, type **regedit**, and then choose **OK**.</span></span>
    2. <span data-ttu-id="a0043-111">Odaberite **da** da bi uređivač registra omogućio promjene na uređaju.</span><span class="sxs-lookup"><span data-stu-id="a0043-111">Select **Yes** to allow Registry Editor to make changes to your device.</span></span>
    3. <span data-ttu-id="a0043-112">U uređivaču registra dodajte vrijednost DWORD za **Enableadal** s postavkom **0** u odjeljku HKEY_CURRENT_USER \Software\Microsoft\Office\16.0\Common\Identity.</span><span class="sxs-lookup"><span data-stu-id="a0043-112">In Registry Editor, add a DWORD value of **EnableADAL** with a setting of **0** under HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.</span></span>

<span data-ttu-id="a0043-113">Dodatne informacije potražite u članku [Problemi s povezivanjem u programu za prijavu nakon ažuriranja na Office 2016 međuverzija 16.0.7967 u sustavu Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span><span class="sxs-lookup"><span data-stu-id="a0043-113">For more information, see [Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span></span>