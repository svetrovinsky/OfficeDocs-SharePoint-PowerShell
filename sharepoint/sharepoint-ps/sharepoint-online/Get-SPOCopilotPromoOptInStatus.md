---
external help file: sharepointonline.xml
Module Name: Microsoft.Online.SharePoint.PowerShell
online version: https://learn.microsoft.com/powershell/module/sharepoint-online/Get-SPOCopilotPromoOptInStatus
applicable: SharePoint Online
title: Get-SPOCopilotPromoOptInStatus.md
schema: 
author: swathi.iruvanti
ms.author: siruvanti
ms.reviewer:
---
# Get-SPOCopilotPromoOptInStatus

## SYNOPSIS

Returns the Opt-In Copilot promo status 

## SYNTAX
```powershell
Get-SPOCopilotPromoOptInStatus
```

### Parameters:

The values for this parameter are:

- True
  
- False

The following details are returned:

- Enabled

- Disabled


## DESCRIPTION

The `Get-SPOCopilotPromoOptInStatus` cmdlet retrieves and returns the opt-in Copilot promo status. 

## EXAMPLES

### Example 1

```powershell
<data name="CopilotPromoPacksOptInStatusEnabled" xml:space="preserve">
    <value>Copilot promo opt in status : Enabled</value>
```

Example 1: Success message shown to user when commandlet returns a positive flag from Tenant store

### Example 2

```powershell
 <data name="CopilotPromoPacksOptInStatusDisabled" xml:space="preserve">
    <value>Copilot promo packs opt in status : Disabled</value>
```

Example 2: Success message shown to user when commandlet returns a negative flag from Tenant store

## RELATED LINKS

Set-SPOCopilotPromoOptInStatus






