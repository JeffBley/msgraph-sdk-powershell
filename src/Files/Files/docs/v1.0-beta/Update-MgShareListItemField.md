---
external help file:
Module Name: Microsoft.Graph.Files
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.files/update-mgsharelistitemfield
schema: 2.0.0
---

# Update-MgShareListItemField

## SYNOPSIS
The values of the columns set on this list item.

## SYNTAX

### UpdateExpanded1 (Default)
```
Update-MgShareListItemField -SharedDriveItemId <String> [-AdditionalProperties <Hashtable>] [-Id <String>]
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Update
```
Update-MgShareListItemField -ListItemId <String> -SharedDriveItemId <String> -BodyParameter <Hashtable>
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Update1
```
Update-MgShareListItemField -SharedDriveItemId <String> -BodyParameter <Hashtable> [-PassThru] [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

### UpdateExpanded
```
Update-MgShareListItemField -ListItemId <String> -SharedDriveItemId <String>
 [-AdditionalProperties <Hashtable>] [-Id <String>] [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgShareListItemField -InputObject <IFilesIdentity> -BodyParameter <Hashtable> [-PassThru] [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentity1
```
Update-MgShareListItemField -InputObject <IFilesIdentity> -BodyParameter <Hashtable> [-PassThru] [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgShareListItemField -InputObject <IFilesIdentity> [-AdditionalProperties <Hashtable>] [-Id <String>]
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentityExpanded1
```
Update-MgShareListItemField -InputObject <IFilesIdentity> [-AdditionalProperties <Hashtable>] [-Id <String>]
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
The values of the columns set on this list item.

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: System.Collections.Hashtable
Parameter Sets: UpdateExpanded, UpdateExpanded1, UpdateViaIdentityExpanded, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
fieldValueSet

```yaml
Type: System.Collections.Hashtable
Parameter Sets: Update, Update1, UpdateViaIdentity, UpdateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Id
Read-only.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded, UpdateExpanded1, UpdateViaIdentityExpanded, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, please use Get-Help -Online and see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IFilesIdentity
Parameter Sets: UpdateViaIdentity, UpdateViaIdentity1, UpdateViaIdentityExpanded, UpdateViaIdentityExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ListItemId
key: id of listItem

```yaml
Type: System.String
Parameter Sets: Update, UpdateExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PassThru
Returns true when the command succeeds

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SharedDriveItemId
key: id of sharedDriveItem

```yaml
Type: System.String
Parameter Sets: Update, Update1, UpdateExpanded, UpdateExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IFilesIdentity

### System.Collections.Hashtable

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


INPUTOBJECT <IFilesIdentity>: Identity Parameter
  - `[ColumnDefinitionId <String>]`: key: id of columnDefinition
  - `[ColumnLinkId <String>]`: key: id of columnLink
  - `[ContentTypeId <String>]`: key: id of contentType
  - `[DriveId <String>]`: key: id of drive
  - `[DriveItemId <String>]`: key: id of driveItem
  - `[EndDateTime <String>]`: Usage: endDateTime={endDateTime}
  - `[GroupId <String>]`: key: id of group
  - `[Interval <String>]`: Usage: interval={interval}
  - `[ListItemId <String>]`: key: id of listItem
  - `[ListItemVersionId <String>]`: key: id of listItemVersion
  - `[Q <String>]`: Usage: q={q}
  - `[RichLongRunningOperationId <String>]`: key: id of richLongRunningOperation
  - `[SharedDriveItemId <String>]`: key: id of sharedDriveItem
  - `[StartDateTime <String>]`: Usage: startDateTime={startDateTime}
  - `[SubscriptionId <String>]`: key: id of subscription
  - `[UserId <String>]`: key: id of user

## RELATED LINKS

