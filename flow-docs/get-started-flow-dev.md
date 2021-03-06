---
title: Tworzenie łączników niestandardowych i osadzanie przepływów | Microsoft Docs
description: Utwórz łącznik niestandardowy, udostępnij go, osadź w przepływie i skorzystaj z wielu innych możliwości
services: ''
suite: flow
documentationcenter: na
author: bbarath
manager: anneta
editor: ''
tags: ''
ms.service: flow
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 11/22/2017
ms.author: barathb
search.app:
- Flow
search.audienceType:
- flowmaker
- enduser
ms.openlocfilehash: 21f35216231193f40c1a723dda62bb3a2ad1be59
ms.sourcegitcommit: a20fbed9941f0cd8b69dc579277a30da9c8bb31b
ms.translationtype: HT
ms.contentlocale: pl-PL
ms.lasthandoff: 09/12/2018
ms.locfileid: "44689645"
---
# <a name="start-to-build-with-microsoft-flow"></a>Rozpocznij tworzenie z usługą Microsoft Flow

Oto kilka sposobów na rozszerzenie aplikacji przy użyciu usługi Microsoft Flow:

* Utworzenie łącznika niestandardowego i nawiązanie z nim połączenia.
* Udostępnianie łącznika niestandardowego wszystkim użytkownikom usługi Microsoft Flow.
* Osadzenie przepływu w aplikacji.
* Wyróżnienie wszystkich łączników niestandardowych, aby użytkownicy mogli korzystać z usługi Microsoft Flow w najwygodniejszy dla siebie sposób.

## <a name="prerequisites"></a>Wymagania wstępne

* Konto usługi [Microsoft Flow](https://flow.microsoft.com).

## <a name="create-a-custom-connector"></a>Tworzenie łącznika niestandardowego

Jeśli masz usługę internetową, z którą chcesz połączyć się z usługi Microsoft Flow, musisz najpierw utworzyć łącznik niestandardowy. Rejestrując łącznik niestandardowy, przekazujesz usłudze Microsoft Flow informacje o właściwościach usługi internetowej, w tym o wymaganym uwierzytelnianiu, obsługiwanych wyzwalaczach i akcjach oraz parametrach i danych wyjściowych dla każdej z tych akcji.

Postępuj zgodnie z tym samouczkiem, aby dowiedzieć się, jak [zarejestrować łączniki niestandardowe i używać ich](https://powerapps.microsoft.com/tutorials/register-custom-api/). Po zarejestrowaniu łącznika niestandardowego możesz udostępnić go w swojej organizacji do przetestowania.

## <a name="share-a-custom-connector-with-all-microsoft-flow-users"></a>Udostępnianie łącznika niestandardowego wszystkim użytkownikom usługi Microsoft Flow

Po pełnym przetestowaniu łącznika niestandardowego uruchom [proces przeglądu](https://flow.microsoft.com/blog/calling-all-saas-apps-now-you-can-build-your-own-connector-for-flow-and-logic-apps/), aby uzyskać zatwierdzenie od firmy Microsoft na potrzeby udostępniania go wszystkim innym użytkownikom usługi Microsoft Flow.

Oto co jest potrzebne do procesu przeglądu:

* Plik w standardzie OpenAPI reprezentujący interfejs API i wszelkie informacje uwierzytelniania.
* Ikona Twojego łącznika.
* Opis Twojego łącznika.
* Około 10 pomysłów na to, jak ten łącznik może przynieść korzyści innym użytkownikom dzięki szablonom.

Po przesłaniu tych informacji firma Microsoft rozpocznie ocenianie działania interfejsu API w usłudze Microsoft Flow i Microsoft PowerApps.

## <a name="embed-the-flow-experience-into-your-website-or-app"></a>Osadzanie przepływu w witrynie internetowej lub aplikacji

Możesz [osadzić](developer/embed-flow-dev.md) usługę Microsoft Flow w aplikacji, aby umożliwić głęboką, kontekstową integrację aplikacji i wszystkich innych usług obsługiwanych przez usługę Microsoft Flow. Na przykład możesz wykonywać następujące działania:

* Przeglądanie wszystkich szablonów związanych z usługą i umożliwienie użytkownikom wyboru szablonu.
* Zarządzanie przepływami, które użytkownicy powiązali z daną aplikacją.

## <a name="next-steps"></a>Następne kroki

Dowiedz się, jak [osadzić](developer/embed-flow-dev.md) usługę Microsoft Flow w aplikacji.
