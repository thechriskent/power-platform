---
title: Elevation control reference | Creator Kit
description: Learn about the details and properties of the Elevation control in the Creator Kit.
author: denisem-msft
manager: devkeydet
ms.component: pa-maker
ms.topic: conceptual
ms.date: 05/16/2022
ms.subservice: guidance
ms.author: demora
ms.reviewer: tapanm
search.audienceType: 
  - maker
search.app: 
  - D365CE
  - PowerApps
  - Powerplatform
contributors:
  - tapanm-msft
  - slaouist
---

# :::no-loc text="Elevation"::: control

[This article is pre-release documentation and is subject to change.]

A control used to construct cards and flyout menus.

:::image type="content" source="media/elevation.png" alt-text="Elevation control.":::

## Description

Fluent UI `Elevation` support with mouse hover events.

> [!NOTE]
> Component source code and more information in the [GitHub code components repository](https://github.com/microsoft/powercat-code-components/tree/main/Elevation).

## Limitations

This code component can only be used in canvas apps and custom pages.

## Key properties

| Property | Description |
| -------- | ----------- |
| `Fill color` | The background color of the `Elevation` control. |
| `Depth` | The depth of the shadow. |

## Additional properties

| Property | Description |
| -------- | ----------- |
| `Hover fill color` | The background color of the `Elevation` control that appears on hover. |
| `Hover depth` | The depth of the shadow that appears on hover. |
| `Padding` | The distance between the `Elevation` card and the edge of the control (in each direction: left, right, top, and bottom). |
| `Dark overlay padding` | When enabled, displays a dark overlay effect in the padded area. |

## Best practices

Go to [Fluent UI Elevation control best practices](https://developer.microsoft.com/fluentui#/styles/web/elevation).

[!INCLUDE[footer-include](../../includes/footer-banner.md)]