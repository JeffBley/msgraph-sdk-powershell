---
external help file:
Module Name: Microsoft.Graph.Security
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.security/update-mgsecuritydomainsecurityprofile
schema: 2.0.0
---

# Update-MgSecurityDomainSecurityProfile

## SYNOPSIS
Update the navigation property domainSecurityProfiles in security

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgSecurityDomainSecurityProfile -DomainSecurityProfileId <String> [-ActivityGroupNames <String[]>]
 [-AdditionalProperties <Hashtable>] [-AzureSubscriptionId <String>] [-AzureTenantId <String>]
 [-CountHits <Int32>] [-CountInOrg <Int32>] [-DomainCategories <IMicrosoftGraphReputationCategory[]>]
 [-DomainRegisteredDateTime <DateTime>] [-FirstSeenDateTime <DateTime>] [-Id <String>]
 [-LastSeenDateTime <DateTime>] [-Name <String>] [-Registrant <IMicrosoftGraphDomainRegistrant>]
 [-RiskScore <String>] [-Tags <String[]>] [-VendorInformation <IMicrosoftGraphSecurityVendorInformation>]
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Update
```
Update-MgSecurityDomainSecurityProfile -DomainSecurityProfileId <String>
 -BodyParameter <IMicrosoftGraphDomainSecurityProfile> [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgSecurityDomainSecurityProfile -InputObject <ISecurityIdentity>
 -BodyParameter <IMicrosoftGraphDomainSecurityProfile> [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgSecurityDomainSecurityProfile -InputObject <ISecurityIdentity> [-ActivityGroupNames <String[]>]
 [-AdditionalProperties <Hashtable>] [-AzureSubscriptionId <String>] [-AzureTenantId <String>]
 [-CountHits <Int32>] [-CountInOrg <Int32>] [-DomainCategories <IMicrosoftGraphReputationCategory[]>]
 [-DomainRegisteredDateTime <DateTime>] [-FirstSeenDateTime <DateTime>] [-Id <String>]
 [-LastSeenDateTime <DateTime>] [-Name <String>] [-Registrant <IMicrosoftGraphDomainRegistrant>]
 [-RiskScore <String>] [-Tags <String[]>] [-VendorInformation <IMicrosoftGraphSecurityVendorInformation>]
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property domainSecurityProfiles in security

## EXAMPLES

## PARAMETERS

### -ActivityGroupNames
.

```yaml
Type: System.String[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AdditionalProperties
Additional Parameters

```yaml
Type: System.Collections.Hashtable
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AzureSubscriptionId
.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AzureTenantId
.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
domainSecurityProfile
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDomainSecurityProfile
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CountHits
.

```yaml
Type: System.Int32
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CountInOrg
.

```yaml
Type: System.Int32
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DomainCategories
.
To construct, please use Get-Help -Online and see NOTES section for DOMAINCATEGORIES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphReputationCategory[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DomainRegisteredDateTime
.

```yaml
Type: System.DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DomainSecurityProfileId
key: id of domainSecurityProfile

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

### -FirstSeenDateTime
.

```yaml
Type: System.DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Type: Microsoft.Graph.PowerShell.Models.ISecurityIdentity
Parameter Sets: UpdateViaIdentity, UpdateViaIdentityExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -LastSeenDateTime
.

```yaml
Type: System.DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
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

### -Registrant
domainRegistrant
To construct, please use Get-Help -Online and see NOTES section for REGISTRANT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDomainRegistrant
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RiskScore
.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Tags
.

```yaml
Type: System.String[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -VendorInformation
securityVendorInformation
To construct, please use Get-Help -Online and see NOTES section for VENDORINFORMATION properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSecurityVendorInformation
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDomainSecurityProfile

### Microsoft.Graph.PowerShell.Models.ISecurityIdentity

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphDomainSecurityProfile>: domainSecurityProfile
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[ActivityGroupNames <String[]>]`: 
  - `[AzureSubscriptionId <String>]`: 
  - `[AzureTenantId <String>]`: 
  - `[CountHits <Int32?>]`: 
  - `[CountInOrg <Int32?>]`: 
  - `[DomainCategories <IMicrosoftGraphReputationCategory[]>]`: 
    - `[Description <String>]`: 
    - `[Name <String>]`: 
    - `[Vendor <String>]`: 
  - `[DomainRegisteredDateTime <DateTime?>]`: 
  - `[FirstSeenDateTime <DateTime?>]`: 
  - `[LastSeenDateTime <DateTime?>]`: 
  - `[Name <String>]`: 
  - `[Registrant <IMicrosoftGraphDomainRegistrant>]`: domainRegistrant
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[CountryOrRegionCode <String>]`: 
    - `[Organization <String>]`: 
    - `[Url <String>]`: 
    - `[Vendor <String>]`: 
  - `[RiskScore <String>]`: 
  - `[Tags <String[]>]`: 
  - `[VendorInformation <IMicrosoftGraphSecurityVendorInformation>]`: securityVendorInformation
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Provider <String>]`: Specific provider (product/service - not vendor company); for example, WindowsDefenderATP.
    - `[ProviderVersion <String>]`: Version of the provider or subprovider, if it exists, that generated the alert. Required
    - `[SubProvider <String>]`: Specific subprovider (under aggregating provider); for example, WindowsDefenderATP.SmartScreen.
    - `[Vendor <String>]`: Name of the alert vendor (for example, Microsoft, Dell, FireEye). Required

DOMAINCATEGORIES <IMicrosoftGraphReputationCategory[]>: .
  - `[Description <String>]`: 
  - `[Name <String>]`: 
  - `[Vendor <String>]`: 

INPUTOBJECT <ISecurityIdentity>: Identity Parameter
  - `[AlertId <String>]`: key: id of alert
  - `[CloudAppSecurityProfileId <String>]`: key: id of cloudAppSecurityProfile
  - `[DomainSecurityProfileId <String>]`: key: id of domainSecurityProfile
  - `[FileSecurityProfileId <String>]`: key: id of fileSecurityProfile
  - `[HostSecurityProfileId <String>]`: key: id of hostSecurityProfile
  - `[IPSecurityProfileId <String>]`: key: id of ipSecurityProfile
  - `[IncidentId <String>]`: key: id of incident
  - `[ProviderTenantSettingId <String>]`: key: id of providerTenantSetting
  - `[SecureScoreControlProfileId <String>]`: key: id of secureScoreControlProfile
  - `[SecureScoreId <String>]`: key: id of secureScore
  - `[SecurityActionId <String>]`: key: id of securityAction
  - `[SimulationId <String>]`: key: id of simulation
  - `[TiIndicatorId <String>]`: key: id of tiIndicator
  - `[UserSecurityProfileId <String>]`: key: id of userSecurityProfile

REGISTRANT <IMicrosoftGraphDomainRegistrant>: domainRegistrant
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[CountryOrRegionCode <String>]`: 
  - `[Organization <String>]`: 
  - `[Url <String>]`: 
  - `[Vendor <String>]`: 

VENDORINFORMATION <IMicrosoftGraphSecurityVendorInformation>: securityVendorInformation
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Provider <String>]`: Specific provider (product/service - not vendor company); for example, WindowsDefenderATP.
  - `[ProviderVersion <String>]`: Version of the provider or subprovider, if it exists, that generated the alert. Required
  - `[SubProvider <String>]`: Specific subprovider (under aggregating provider); for example, WindowsDefenderATP.SmartScreen.
  - `[Vendor <String>]`: Name of the alert vendor (for example, Microsoft, Dell, FireEye). Required

## RELATED LINKS

