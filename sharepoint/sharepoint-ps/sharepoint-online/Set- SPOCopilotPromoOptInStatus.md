---
external help file: sharepointonline.xml
Module Name: Microsoft.Online.SharePoint.PowerShell
online version: https://learn.microsoft.com/powershell/module/sharepoint-online/Set-SPOCopilotPromoOptInStatus
applicable: SharePoint Online
title: Set-SPOCopilotPromoOptInStatus.md
schema: 
author: swathi.iruvanti
ms.author: siruvanti
ms.reviewer:
---
# Set-SPOCopilotPromoOptInStatus

## SYNOPSIS

Retrieves the IsCopilotPromoStatusEnabled ( "true/false" ) state of the Copilot promo opt-in bit and stores the information.

## SYNTAX
```powershell
Set-SPOCopilotPromoOptInStatus
```

### Parameters:

The values for this parameter are:

- True
  
- False

The following details are returned:

- Copilot promo status set successfully

- Error saving Copilot promo Status

## DESCRIPTION

The `Set-SPOCopilotPromoOptInStatus` cmdlet stores the opt-in state.

## EXAMPLES

### Example 1

```powershell
<data name="SPOCopilotPromoOptInStatusError" xml:space="preserve">
    <value>Error saving Copilot promo Status</value>
```

Example 1: Error message shown to user when commandlet fails to execute for Set-CopilotPromoOptInStatus

### Example 2

```powershell
<data name="SPOCopilotPromoOptInStatusSetSuccessfully" xml:space="preserve">
    <value>Copilot promo status set successfully</value>
```

Example 2: Success message shown to user when commandlet executes successfully for Set-CopilotPromoOptInStatus

## RELATED LINKS

Get-SPOCopilotPromoOptInStatus
