---
title: "MSBuild Response Files | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "VB"
  - "CSharp"
  - "C++"
  - "jsharp"
helpviewer_keywords: 
  - "response files, MSBuild"
  - "MSBuild, response files"
  - "MSBuild, .rsp files"
  - ".rsp files"
ms.assetid: 9f53987b-20ee-470a-ab62-fce997bb5e15
caps.latest.revision: 6
author: mikejo5000
ms.author: mikejo
manager: "ghogen"
---
# MSBuild Response Files
[!INCLUDE[vs2017banner](../includes/vs2017banner.md)]

The latest version of this topic can be found at [MSBuild Response Files](https://docs.microsoft.com/visualstudio/msbuild/msbuild-response-files).  
  
  
Response (.rsp) files are text files that contain MSBuild.exe command line switches. Each switch can be on a separate line or all switches can be on one line. Comment lines are prefaced with a **#** symbol. The **@** switch is used to pass another response file to MSBuild.exe.  
  
 The auto-response file is a special .rsp file that MSBuild.exe automatically uses when building a project. This file, MSBuild.rsp, must be in the same directory as MSBuild.exe, otherwise it will not be found. You can edit this file to specify default command line switches to MSBuild.exe. For example, if you use the same logger every time you build a project, you can add the **/logger** switch to MSBuild.rsp, and MSBuild.exe will use the logger every time a project is built.  
  
## See Also  
 [MSBuild Reference](../msbuild/msbuild-reference.md)   
 [Command-Line Reference](../msbuild/msbuild-command-line-reference.md)



