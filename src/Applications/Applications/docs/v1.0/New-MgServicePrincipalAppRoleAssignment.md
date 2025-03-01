---
external help file:
Module Name: Microsoft.Graph.Applications
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.applications/new-mgserviceprincipalapproleassignment
schema: 2.0.0
---

# New-MgServicePrincipalAppRoleAssignment

## SYNOPSIS
App role assignment for another app or service, granted to this service principal.
Supports $expand.

## SYNTAX

### CreateExpanded1 (Default)
```
New-MgServicePrincipalAppRoleAssignment -ServicePrincipalId <String> [-AdditionalProperties <Hashtable>]
 [-AppRoleId <String>] [-CreatedDateTime <DateTime>] [-DeletedDateTime <DateTime>] [-Id <String>]
 [-PrincipalDisplayName <String>] [-PrincipalId <String>] [-PrincipalType <String>]
 [-ResourceDisplayName <String>] [-ResourceId <String>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create1
```
New-MgServicePrincipalAppRoleAssignment -ServicePrincipalId <String>
 -BodyParameter <IMicrosoftGraphAppRoleAssignment> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentity1
```
New-MgServicePrincipalAppRoleAssignment -InputObject <IApplicationsIdentity>
 -BodyParameter <IMicrosoftGraphAppRoleAssignment> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentityExpanded1
```
New-MgServicePrincipalAppRoleAssignment -InputObject <IApplicationsIdentity>
 [-AdditionalProperties <Hashtable>] [-AppRoleId <String>] [-CreatedDateTime <DateTime>]
 [-DeletedDateTime <DateTime>] [-Id <String>] [-PrincipalDisplayName <String>] [-PrincipalId <String>]
 [-PrincipalType <String>] [-ResourceDisplayName <String>] [-ResourceId <String>] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

## DESCRIPTION
App role assignment for another app or service, granted to this service principal.
Supports $expand.

## EXAMPLES

### Example 1: {{ Add title here }}
```powershell
$appRoleAssignment = @{
  "principalId"= "0bdb123d-b8a7-4cc9-8cc2-bd17bad06f61"
  "resourceId"= "557aedfc-007c-4904-918a-7e6fed2e7403"
  "appRoleId"= "00000000-0000-0000-0000-000000000000"
  }

New-MgServicePrincipalAppRoleAssignment -ServicePrincipalId 0bdb123d-b8a7-4cc9-8cc2-bd17bad06f61 -BodyParameter $appRoleAssignment | Format-List

AppRoleId            : 00000000-0000-0000-0000-000000000000
CreatedDateTime      : 8/31/2021 2:01:28 PM
DeletedDateTime      :
Id                   : PRLbC6e4yUyMwr0XutBvYfZHkKGzlbxDr2I-QJWN9rs
PrincipalDisplayName : Example App
PrincipalId          : 0bdb123d-b8a7-4cc9-8cc2-bd17bad06f61
PrincipalType        : ServicePrincipal
ResourceDisplayName  : Office 365 Management APIs
ResourceId           : 557aedfc-007c-4904-918a-7e6fed2e7403
AdditionalProperties : {[@odata.context, https://graph.microsoft.com/v1.0/$metadata#servicePrincipals('0bdb123d-b8a7-4cc9-8cc2-bd17
                       bad06f61')/appRoleAssignments/$entity], [@odata.id, https://graph.microsoft.com/v2/fb625e04-52aa-42da-b10d-1
                       4f1195d665f/directoryObjects/$/Microsoft.DirectoryServices.ServicePrincipal('0bdb123d-b8a7-4cc9-8cc2-bd17bad
                       06f61')/appRoleAssignments/PRLbC6e4yUyMwr0XutBvYfZHkKGzlbxDr2I-QJWN9rs]}
```

In this example, the first command defines the `$appRoleAssignment` variable that defines the following:

-`principalId`: The id of the client service principal to which you are assigning the app role.

-`resourceId`: The id of the resource `servicePrincipal` (the API) which has defined the app role (the application permission).

-`appRoleId`: The id of the appRole (defined on the resource service principal) to assign to the client service principal.


Learn more about the [AppRoleAssignment resource](/graph/api/resources/approleassignment?view=graph-rest-1.0).

The second command adds the role to the specified service principal.

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: System.Collections.Hashtable
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppRoleId
The identifier (id) for the app role which is assigned to the principal.
This app role must be exposed in the appRoles property on the resource application's service principal (resourceId).
If the resource application has not declared any app roles, a default app role ID of 00000000-0000-0000-0000-000000000000 can be specified to signal that the principal is assigned to the resource app without any specific app roles.
Required on create.

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

### -BodyParameter
appRoleAssignment
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAppRoleAssignment
Parameter Sets: Create1, CreateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CreatedDateTime
The time when the app role assignment was created.The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
Read-only.

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeletedDateTime
.

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
Read-only.

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

### -InputObject
Identity Parameter
To construct, please use Get-Help -Online and see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IApplicationsIdentity
Parameter Sets: CreateViaIdentity1, CreateViaIdentityExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -PrincipalDisplayName
The display name of the user, group, or service principal that was granted the app role assignment.
Read-only.
Supports $filter (eq and startswith).

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

### -PrincipalId
The unique identifier (id) for the user, group or service principal being granted the app role.
Required on create.

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

### -PrincipalType
The type of the assigned principal.
This can either be User, Group or ServicePrincipal.
Read-only.

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

### -ResourceDisplayName
The display name of the resource app's service principal to which the assignment is made.

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

### -ResourceId
The unique identifier (id) for the resource service principal for which the assignment is made.
Required on create.
Supports $filter (eq only).

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

### -ServicePrincipalId
key: id of servicePrincipal

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

### Microsoft.Graph.PowerShell.Models.IApplicationsIdentity

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAppRoleAssignment

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAppRoleAssignment

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphAppRoleAssignment>: appRoleAssignment
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[DeletedDateTime <DateTime?>]`: 
  - `[Id <String>]`: Read-only.
  - `[AppRoleId <String>]`: The identifier (id) for the app role which is assigned to the principal. This app role must be exposed in the appRoles property on the resource application's service principal (resourceId). If the resource application has not declared any app roles, a default app role ID of 00000000-0000-0000-0000-000000000000 can be specified to signal that the principal is assigned to the resource app without any specific app roles. Required on create.
  - `[CreatedDateTime <DateTime?>]`: The time when the app role assignment was created.The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z. Read-only.
  - `[PrincipalDisplayName <String>]`: The display name of the user, group, or service principal that was granted the app role assignment. Read-only. Supports $filter (eq and startswith).
  - `[PrincipalId <String>]`: The unique identifier (id) for the user, group or service principal being granted the app role. Required on create.
  - `[PrincipalType <String>]`: The type of the assigned principal. This can either be User, Group or ServicePrincipal. Read-only.
  - `[ResourceDisplayName <String>]`: The display name of the resource app's service principal to which the assignment is made.
  - `[ResourceId <String>]`: The unique identifier (id) for the resource service principal for which the assignment is made. Required on create. Supports $filter (eq only).

INPUTOBJECT <IApplicationsIdentity>: Identity Parameter
  - `[AppRoleAssignmentId <String>]`: key: id of appRoleAssignment
  - `[ApplicationId <String>]`: key: id of application
  - `[ApplicationTemplateId <String>]`: key: id of applicationTemplate
  - `[ConnectorGroupId <String>]`: key: id of connectorGroup
  - `[ConnectorId <String>]`: key: id of connector
  - `[DelegatedPermissionClassificationId <String>]`: key: id of delegatedPermissionClassification
  - `[DirectoryDefinitionId <String>]`: key: id of directoryDefinition
  - `[EndpointId <String>]`: key: id of endpoint
  - `[ExtensionPropertyId <String>]`: key: id of extensionProperty
  - `[FederatedIdentityCredentialId <String>]`: key: id of federatedIdentityCredential
  - `[GroupId <String>]`: key: id of group
  - `[LicenseDetailsId <String>]`: key: id of licenseDetails
  - `[OnPremisesAgentGroupId <String>]`: key: id of onPremisesAgentGroup
  - `[OnPremisesAgentGroupId1 <String>]`: key: id of onPremisesAgentGroup
  - `[OnPremisesAgentId <String>]`: key: id of onPremisesAgent
  - `[OnPremisesAgentId1 <String>]`: key: id of onPremisesAgent
  - `[OnPremisesPublishingProfileId <String>]`: key: id of onPremisesPublishingProfile
  - `[PublishedResourceId <String>]`: key: id of publishedResource
  - `[PublishedResourceId1 <String>]`: key: id of publishedResource
  - `[ServicePrincipalId <String>]`: key: id of servicePrincipal
  - `[SynchronizationJobId <String>]`: key: id of synchronizationJob
  - `[SynchronizationTemplateId <String>]`: key: id of synchronizationTemplate
  - `[UserId <String>]`: key: id of user

## RELATED LINKS

