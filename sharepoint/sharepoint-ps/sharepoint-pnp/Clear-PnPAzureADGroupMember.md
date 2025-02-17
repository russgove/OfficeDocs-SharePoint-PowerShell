---
Module Name: PnP.PowerShell
schema: 2.0.0
applicable: SharePoint Online
online version: https://pnp.github.io/powershell/cmdlets/Clear-PnPAzureADGroupMember.html
external help file: PnP.PowerShell.dll-help.xml
title: Clear-PnPAzureADGroupMember
---
  
# Clear-PnPAzureADGroupMember

## SYNOPSIS

> [!TIP]
> We encourage you to make improvements to this documentation. Please navigate to https://github.com/pnp/powershell/blob/dev/documentation/Clear-PnPAzureADGroupMember.md to change this file.


**Required Permissions**

  * Microsoft Graph API : One of Directory.ReadWrite.All, Group.ReadWrite.All, GroupMember.ReadWrite.All

Removes all current members from a particular Azure Active Directory group. This can be a security, distribution or Microsoft 365 group.

## SYNTAX

```powershell
Clear-PnPAzureADGroupMember -Identity <AzureADGroupPipeBind> [<CommonParameters>]
```

## DESCRIPTION

## EXAMPLES

### EXAMPLE 1
```powershell
Clear-PnPAzureADGroupMember -Identity "Project Team"
```

Removes all the current members from the Azure Active Directory group named "Project Team"

## PARAMETERS

### -Identity
The Identity of the Azure Active Directory group to remove all members from

```yaml
Type: AzureADGroupPipeBind
Parameter Sets: (All)

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

## RELATED LINKS

[Microsoft 365 Patterns and Practices](https://aka.ms/m365pnp)[Documentation](/graph/api/group-delete-members)


