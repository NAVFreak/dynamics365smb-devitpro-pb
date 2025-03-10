---
title: "XmlDocumentType.GetName(var Text) Method"
description: "Gets the name for this Document Type Definition (DTD)."
ms.author: solsen
ms.date: 08/26/2024
ms.topic: reference
author: SusanneWindfeldPedersen
ms.reviewer: solsen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# XmlDocumentType.GetName(var Text) Method
> **Version**: _Available or changed with runtime version 1.0._

Gets the name for this Document Type Definition (DTD).


## Syntax
```AL
[Ok := ]  XmlDocumentType.GetName(var Result: Text)
```
## Parameters
*XmlDocumentType*  
&emsp;Type: [XmlDocumentType](xmldocumenttype-data-type.md)  
An instance of the [XmlDocumentType](xmldocumenttype-data-type.md) data type.  

*Result*  
&emsp;Type: [Text](../text/text-data-type.md)  
A string that contains the name for this Document Type Definition (DTD).  


## Return Value
*[Optional] Ok*  
&emsp;Type: [Boolean](../boolean/boolean-data-type.md)  
**true** if the operation was successful; otherwise **false**.   If you omit this optional return value and the operation does not execute successfully, a runtime error will occur.  


[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## Related information
[XmlDocumentType Data Type](xmldocumenttype-data-type.md)  
[Get Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)