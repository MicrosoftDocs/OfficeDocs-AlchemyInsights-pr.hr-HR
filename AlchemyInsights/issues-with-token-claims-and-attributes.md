---
title: Problemi s tvrdnjama i atributima tokena
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
- "9004347"
- "7761"
ms.openlocfilehash: 4c12f768ab4bf4547f48abc19736743fa555c477
ms.sourcegitcommit: c1c6047ec467853dc823a17b02c461a6a476406d
ms.translationtype: MT
ms.contentlocale: hr-HR
ms.lasthandoff: 01/27/2021
ms.locfileid: "50035832"
---
# <a name="issues-with-token-claims-and-attributes"></a><span data-ttu-id="d6cbf-102">Problemi s tvrdnjama i atributima tokena</span><span class="sxs-lookup"><span data-stu-id="d6cbf-102">Issues with Token Claims and Attributes</span></span>

<span data-ttu-id="d6cbf-103">**Ažuriranje, konfiguriranje i uklanjanje potraživanja od tokena**</span><span class="sxs-lookup"><span data-stu-id="d6cbf-103">**Update, configure or remove token claims**</span></span>

1. <span data-ttu-id="d6cbf-104">Pomoću servisa Azure Active Directory (Azure AD) možete [prilagoditi vrstu potraživanja za zahtjev za ulogu](https://docs.microsoft.com/azure/active-directory/develop/active-directory-enterprise-app-role-management) u toknu odaziva koji ste primili nakon autorizacija aplikacije.</span><span class="sxs-lookup"><span data-stu-id="d6cbf-104">By using Azure Active Directory (Azure AD), you can [customize the claim type for the role claim](https://docs.microsoft.com/azure/active-directory/develop/active-directory-enterprise-app-role-management) in the response token that you receive after you authorize an app.</span></span>
2. <span data-ttu-id="d6cbf-105">Programeri aplikacija mogu koristiti neobavezne tvrdnje u svojim aplikacijama za Azure AD da bi naveli koje tvrdnje žele u tokene poslane u njihovu aplikaciju.</span><span class="sxs-lookup"><span data-stu-id="d6cbf-105">Application developers can use optional claims in their Azure AD applications to specify which claims they want in tokens sent to their application.</span></span> <span data-ttu-id="d6cbf-106">Dodatne informacije potražite u članku [pružanje neobaveznih zahtjeva za aplikaciju](https://docs.microsoft.com/azure/active-directory/develop/active-directory-optional-claims).</span><span class="sxs-lookup"><span data-stu-id="d6cbf-106">For more information, see [Provide optional claims to your app](https://docs.microsoft.com/azure/active-directory/develop/active-directory-optional-claims).</span></span>
3. <span data-ttu-id="d6cbf-107">[Konfigurirajte grupne potraživanja za aplikacije pomoću servisa Azure Active Directory](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-fed-group-claims).</span><span class="sxs-lookup"><span data-stu-id="d6cbf-107">[Configure group claims for applications with Azure Active Directory](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-fed-group-claims).</span></span>
4. <span data-ttu-id="d6cbf-108">Ako koristite neprekinutu jedinstvenu prijavu u aplikaciji, pročitajte članak [Prilagodba potraživanja izdanih u programu SAML token za Enterprise Applications](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-claims-customization).</span><span class="sxs-lookup"><span data-stu-id="d6cbf-108">If using Seamless Single Sign-on in your application, see [customize claims issued in the SAML token for enterprise applications](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-claims-customization).</span></span>

<span data-ttu-id="d6cbf-109">**Mapiranje atributa potraživanja**</span><span class="sxs-lookup"><span data-stu-id="d6cbf-109">**Claims Attribute Mapping**</span></span>

1. <span data-ttu-id="d6cbf-110">Da biste konfigurirali pravilnik o preslikavanju potraživanja pomoću komponente PowerShell, pročitajte članak [Prilagodba potraživanja koje emitiraju tokeni za određenu aplikaciju u klijentu (pretpregled)](https://docs.microsoft.com/azure/active-directory/develop/active-directory-claims-mapping).</span><span class="sxs-lookup"><span data-stu-id="d6cbf-110">To configure claims mapping policy using PowerShell, see [Customize claims emitted in tokens for a specific app in a tenant (Preview)](https://docs.microsoft.com/azure/active-directory/develop/active-directory-claims-mapping).</span></span>
2. <span data-ttu-id="d6cbf-111">Atributi proširenja sheme direktorija nude način spremanja dodatnih podataka u servisu Azure Active Directory na korisničke objekte i druge objekte direktorija, kao što su grupe, detalji o klijentu, ravnatelji servisa.</span><span class="sxs-lookup"><span data-stu-id="d6cbf-111">Directory schema extension attributes provide a way to store additional data in Azure Active Directory on user objects and other directory objects such as groups, tenant details, service principals.</span></span> <span data-ttu-id="d6cbf-112">Samo atributi proširenja na korisničke objekte mogu se koristiti za emitiranje potraživanja u aplikacije.</span><span class="sxs-lookup"><span data-stu-id="d6cbf-112">Only extension attributes on user objects can be used for emitting claims to applications.</span></span> <span data-ttu-id="d6cbf-113">[Pomoću atributa proširenja sheme direktorija u tvrdnjama](https://docs.microsoft.com/azure/active-directory/develop/active-directory-schema-extensions) opisan je način korištenja atributa proširenja sheme direktorija za slanje korisničkih podataka u aplikacije u tvrdnjama tokena.</span><span class="sxs-lookup"><span data-stu-id="d6cbf-113">[Using directory schema extension attributes in claims](https://docs.microsoft.com/azure/active-directory/develop/active-directory-schema-extensions) describes how to use directory schema extension attributes for sending user data to applications in token claims.</span></span>

<span data-ttu-id="d6cbf-114">Dodatne informacije o tvrdnjama tokena potražite u članku:</span><span class="sxs-lookup"><span data-stu-id="d6cbf-114">For more information on token claims, see:</span></span>

- [<span data-ttu-id="d6cbf-115">Potraživanja u programu Access tokens</span><span class="sxs-lookup"><span data-stu-id="d6cbf-115">Claims in access tokens</span></span>](https://docs.microsoft.com/azure/active-directory/develop/access-tokens#claims-in-access-tokens)
- [<span data-ttu-id="d6cbf-116">Potraživanja u id_token</span><span class="sxs-lookup"><span data-stu-id="d6cbf-116">Claims in an id_token</span></span>](https://docs.microsoft.com/azure/active-directory/develop/id-tokens#claims-in-an-id_token)
- <span data-ttu-id="d6cbf-117">[Tvrdi](https://docs.microsoft.com/azure/active-directory-b2c/tokens-overview#claims) da možete očekivati u ID tokena i pristupne tokeni koje je izdala Azure ad B2C</span><span class="sxs-lookup"><span data-stu-id="d6cbf-117">[Claims](https://docs.microsoft.com/azure/active-directory-b2c/tokens-overview#claims) that you can expect in ID tokens and access tokens issued by Azure AD B2C</span></span>
- [<span data-ttu-id="d6cbf-118">Referenca za SAML token</span><span class="sxs-lookup"><span data-stu-id="d6cbf-118">SAML token claims reference</span></span>](https://docs.microsoft.com/azure/active-directory/develop/reference-saml-tokens)
