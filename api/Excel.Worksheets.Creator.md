---
title: Worksheets.Creator property (Excel)
keywords: vbaxl10.chm469074
f1_keywords:
- vbaxl10.chm469074
api_name:
- Excel.Worksheets.Creator
ms.assetid: 5f6d4cec-b867-1165-2deb-a793b78d32e3
ms.date: 05/18/2019
ms.localizationpriority: medium
---


# Worksheets.Creator property (Excel)

Returns a 32-bit integer that indicates the application in which this object was created. Read-only **Long**.


## Syntax

_expression_.**Creator**

_expression_ A variable that represents a **[Worksheets](Excel.Worksheets.md)** object.


## Remarks

If the object was created in Microsoft Excel, this property returns the string XCEL, which is equivalent to the hexadecimal number 5843454C. The **Creator** property is designed to be used in Microsoft Excel for the Macintosh, where each application has a four-character creator code. For example, Microsoft Excel has the creator code XCEL.




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]