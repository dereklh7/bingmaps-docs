---
title: "Venue rectangle JSON class | Microsoft Docs"
ms.custom: ""
ms.date: "05/26/2020"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 8F3DD6AD-9E0E-4F1C-BB76-5D6553A06756
caps.latest.revision: 3
author: "dbuerer"
ms.author: ""
manager: ""
ms.service: "bing-maps"
---
# Venue rectangle JSON class

Encapsulates an oriented rectangle.

## Properties

| Property | Type           | Req? | Description |
|----------|----------------|------|-------------|
| angle    | number         |      | Angle in degrees that the rectangle is rotated counter-clockwise. |
| xy       | number[]       |  ✔   | An X and Y coordinate that, once transform is applied, defines a center of the rectangle. |
| width    | number         |  ✔   | The width of the box in Web Mercator degrees. |
| height   | number         |  ✔   | The height of the box in Web Mercator degrees. |

## Example

```json
{
  "angle": -10,
  "xy": [20, 30],
  "width": 5.01E-05,
  "height": 2.1E-05
}
```