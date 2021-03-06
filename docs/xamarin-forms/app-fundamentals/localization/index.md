---
title: Xamarin.Forms 本地化
description: 内置的 .NET 本地化框架可与 Xamarin.Forms 结合使用，从而生成跨平台的多语言应用程序。 文本和图像均可本地化，且应用程序支持从右到左的流方向。
ms.prod: xamarin
ms.assetid: 97BF843B-BDAA-4CEA-8189-6DB54B291D7F
ms.technology: xamarin-forms
author: davidbritch
ms.author: dabritch
ms.date: 11/07/2018
ms.openlocfilehash: 71033e935a2d3a4be88dbcc5d975938771484640
ms.sourcegitcommit: b60a37587aad8a0bfa8a522d88d22fa672002443
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/08/2018
ms.locfileid: "51285568"
---
# <a name="xamarinforms-localization"></a>Xamarin.Forms 本地化

内置的 .NET 本地化框架可与 Xamarin.Forms 结合使用，从而生成跨平台的多语言应用程序。

## <a name="string-and-image-localizationtextmd"></a>[字符串和映像本地化](text.md)

内置的 .NET 应用程序本地化机制使用 [RESX 文件](https://docs.microsoft.com/dotnet/framework/resources/creating-resource-files-for-desktop-apps#resources-in-resx-files)以及 `System.Resources` 和 `System.Globalization` 命名空间中的类。 包含已翻译字符串的 RESX 文件嵌入在 Xamarin.Forms 程序集中，该程序集中还包括编译器生成的类（可提供对翻译的强类型访问）。 然后可在代码中检索翻译文本。

## <a name="right-to-left-localizationright-to-leftmd"></a>[从右到左本地化](right-to-left.md)

流方向是指页面 UI 元素的浏览方向。 从右到左本地化为 Xamarin.Forms 应用程序添加了对从右到左流方向的支持。
