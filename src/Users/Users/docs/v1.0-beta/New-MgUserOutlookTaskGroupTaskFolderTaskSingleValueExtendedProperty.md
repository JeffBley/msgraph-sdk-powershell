---
external help file:
Module Name: Microsoft.Graph.Users
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.users/new-mguseroutlooktaskgrouptaskfoldertasksinglevalueextendedproperty
schema: 2.0.0
---

# New-MgUserOutlookTaskGroupTaskFolderTaskSingleValueExtendedProperty

## SYNOPSIS
The collection of single-value extended properties defined for the task.
Read-only.
Nullable.

## SYNTAX

### CreateExpanded (Default)
```
New-MgUserOutlookTaskGroupTaskFolderTaskSingleValueExtendedProperty -OutlookTaskFolderId <String>
 -OutlookTaskGroupId <String> -OutlookTaskId <String> -UserId <String> [-AdditionalProperties <Hashtable>]
 [-Id <String>] [-Value <String>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create
```
New-MgUserOutlookTaskGroupTaskFolderTaskSingleValueExtendedProperty -OutlookTaskFolderId <String>
 -OutlookTaskGroupId <String> -OutlookTaskId <String> -UserId <String>
 -BodyParameter <IMicrosoftGraphSingleValueLegacyExtendedProperty> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentity
```
New-MgUserOutlookTaskGroupTaskFolderTaskSingleValueExtendedProperty -InputObject <IUsersIdentity>
 -BodyParameter <IMicrosoftGraphSingleValueLegacyExtendedProperty> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentityExpanded
```
New-MgUserOutlookTaskGroupTaskFolderTaskSingleValueExtendedProperty -InputObject <IUsersIdentity>
 [-AdditionalProperties <Hashtable>] [-Id <String>] [-Value <String>] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

## DESCRIPTION
The collection of single-value extended properties defined for the task.
Read-only.
Nullable.

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: System.Collections.Hashtable
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
singleValueLegacyExtendedProperty
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSingleValueLegacyExtendedProperty
Parameter Sets: Create, CreateViaIdentity
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
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
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
Type: Microsoft.Graph.PowerShell.Models.IUsersIdentity
Parameter Sets: CreateViaIdentity, CreateViaIdentityExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -OutlookTaskFolderId
key: id of outlookTaskFolder

```yaml
Type: System.String
Parameter Sets: Create, CreateExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OutlookTaskGroupId
key: id of outlookTaskGroup

```yaml
Type: System.String
Parameter Sets: Create, CreateExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OutlookTaskId
key: id of outlookTask

```yaml
Type: System.String
Parameter Sets: Create, CreateExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserId
key: id of user

```yaml
Type: System.String
Parameter Sets: Create, CreateExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Value
A property value.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSingleValueLegacyExtendedProperty

### Microsoft.Graph.PowerShell.Models.IUsersIdentity

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSingleValueLegacyExtendedProperty

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphSingleValueLegacyExtendedProperty>: singleValueLegacyExtendedProperty
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[Value <String>]`: A property value.

INPUTOBJECT <IUsersIdentity>: Identity Parameter
  - `[AttachmentId <String>]`: key: id of attachment
  - `[ExtensionId <String>]`: key: id of extension
  - `[LicenseDetailsId <String>]`: key: id of licenseDetails
  - `[LinkedResourceId <String>]`: key: id of linkedResource
  - `[MultiValueLegacyExtendedPropertyId <String>]`: key: id of multiValueLegacyExtendedProperty
  - `[NotificationId <String>]`: key: id of notification
  - `[OutlookCategoryId <String>]`: key: id of outlookCategory
  - `[OutlookTaskFolderId <String>]`: key: id of outlookTaskFolder
  - `[OutlookTaskGroupId <String>]`: key: id of outlookTaskGroup
  - `[OutlookTaskId <String>]`: key: id of outlookTask
  - `[ProfilePhotoId <String>]`: key: id of profilePhoto
  - `[SingleValueLegacyExtendedPropertyId <String>]`: key: id of singleValueLegacyExtendedProperty
  - `[TodoTaskId <String>]`: key: id of todoTask
  - `[TodoTaskListId <String>]`: key: id of todoTaskList
  - `[UserId <String>]`: key: id of user

## RELATED LINKS

