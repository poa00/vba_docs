---
title: Workbook.ChangeLink method (Excel)
keywords: vbaxl10.chm199083
f1_keywords:
- vbaxl10.chm199083
api_name:
- Excel.Workbook.ChangeLink
ms.assetid: 9b2c0b82-73ff-3bdb-63df-82c0708cb703
ms.date: 05/29/2019
ms.localizationpriority: medium
---


# Workbook.ChangeLink method (Excel)

Changes a link from one document to another.


## Syntax

_expression_.**ChangeLink** (_Name_, _NewName_, _Type_)

_expression_ A variable that represents a **[Workbook](Excel.Workbook.md)** object.


## Parameters

|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
| _Name_|Required| **String**|The name of the Microsoft Excel or DDE/OLE link to be changed, as it was returned from the **[LinkSources](Excel.Workbook.LinkSources.md)** method.|
| _NewName_|Required| **String**|The new name of the link.|
| _Type_|Optional| **[XlLinkType](Excel.XlLinkType.md)**|The link type.|

## Example

This example changes a Microsoft Excel link. This example assumes that at least one formula exists in the active workbook that links to another Excel source.

```vb
ActiveWorkbook.ChangeLink "c:\excel\book1.xls", _ 
 "c:\excel\book2.xls", xlExcelLinks
```



[!include[Support and feedback](~/includes/feedback-boilerplate.md)]
