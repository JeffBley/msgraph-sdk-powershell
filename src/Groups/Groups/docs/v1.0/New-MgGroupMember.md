---
external help file:
Module Name: Microsoft.Graph.Groups
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.groups/new-mggroupmember
schema: 2.0.0
---

# New-MgGroupMember

## SYNOPSIS
Add a member to an Office 365 group or security group through the members navigation property.

## SYNTAX

### CreateExpanded1 (Default)
```
New-MgGroupMember -GroupId <String> [-DirectoryObjectId <String>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create1
```
New-MgGroupMember -GroupId <String> -BodyParameter <IMicrosoftGraphDirectoryObject> [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### CreateViaIdentity1
```
New-MgGroupMember -InputObject <IGroupsIdentity> -BodyParameter <IMicrosoftGraphDirectoryObject> [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentityExpanded1
```
New-MgGroupMember -InputObject <IGroupsIdentity> [-DirectoryObjectId <String>] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

## DESCRIPTION
Add a member to an Office 365 group or security group through the members navigation property.

## EXAMPLES

### Example 1: Add a member to a group.
```powershell
New-MgGroupMember -GroupId '872648e7-b23a-4328-bd46-f1bd431c2354' -DirectoryObjectId '8a7c50d3-fcbd-4727-a889-8ab232dfea01'
```

This example adds a member specified by the DirectoryObjectId to the specified group.

## PARAMETERS

### -BodyParameter
HELP MESSAGE MISSING
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDirectoryObject
Parameter Sets: Create1, CreateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DirectoryObjectId
HELP MESSAGE MISSING

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GroupId
key: group-id of group

```yaml
Type: System.String
Parameter Sets: Create1, CreateExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, please use Get-Help -Online and see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IGroupsIdentity
Parameter Sets: CreateViaIdentity1, CreateViaIdentityExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
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

### Microsoft.Graph.PowerShell.Models.IGroupsIdentity

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDirectoryObject

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDirectoryObject

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphDirectoryObject>: HELP MESSAGE MISSING
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[DeletedDateTime <DateTime?>]`: 

INPUTOBJECT <IGroupsIdentity>: Identity Parameter
  - `[AttachmentId <String>]`: key: id of attachment
  - `[ConversationId <String>]`: key: id of conversation
  - `[ConversationThreadId <String>]`: key: id of conversationThread
  - `[DirectorySettingId <String>]`: key: id of directorySetting
  - `[EndpointId <String>]`: key: id of endpoint
  - `[EventId <String>]`: key: id of event
  - `[ExtensionId <String>]`: key: id of extension
  - `[GroupId <String>]`: key: id of group
  - `[GroupLifecyclePolicyId <String>]`: key: id of groupLifecyclePolicy
  - `[IncludePersonalNotebooks <Boolean?>]`: Usage: includePersonalNotebooks={includePersonalNotebooks}
  - `[MentionId <String>]`: key: id of mention
  - `[MultiValueLegacyExtendedPropertyId <String>]`: key: id of multiValueLegacyExtendedProperty
  - `[NotebookId <String>]`: key: id of notebook
  - `[OnenotePageId <String>]`: key: id of onenotePage
  - `[OnenoteSectionId <String>]`: key: id of onenoteSection
  - `[PostId <String>]`: key: id of post
  - `[ProfilePhotoId <String>]`: key: id of profilePhoto
  - `[ResourceSpecificPermissionGrantId <String>]`: key: id of resourceSpecificPermissionGrant
  - `[SingleValueLegacyExtendedPropertyId <String>]`: key: id of singleValueLegacyExtendedProperty
  - `[User <String>]`: Usage: User={User}
  - `[UserId <String>]`: key: id of user

## RELATED LINKS

