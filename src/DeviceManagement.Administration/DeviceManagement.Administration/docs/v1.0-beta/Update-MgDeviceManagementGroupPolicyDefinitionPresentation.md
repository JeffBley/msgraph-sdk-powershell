---
external help file:
Module Name: Microsoft.Graph.DeviceManagement.Administration
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.administration/update-mgdevicemanagementgrouppolicydefinitionpresentation
schema: 2.0.0
---

# Update-MgDeviceManagementGroupPolicyDefinitionPresentation

## SYNOPSIS
The group policy presentations associated with the definition.

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgDeviceManagementGroupPolicyDefinitionPresentation -GroupPolicyDefinitionId <String>
 -GroupPolicyPresentationId <String> [-AdditionalProperties <Hashtable>]
 [-Definition <IMicrosoftGraphGroupPolicyDefinition>] [-Id <String>] [-Label <String>]
 [-LastModifiedDateTime <DateTime>] [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Update
```
Update-MgDeviceManagementGroupPolicyDefinitionPresentation -GroupPolicyDefinitionId <String>
 -GroupPolicyPresentationId <String> -BodyParameter <IMicrosoftGraphGroupPolicyPresentation> [-PassThru]
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgDeviceManagementGroupPolicyDefinitionPresentation
 -InputObject <IDeviceManagementAdministrationIdentity>
 -BodyParameter <IMicrosoftGraphGroupPolicyPresentation> [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgDeviceManagementGroupPolicyDefinitionPresentation
 -InputObject <IDeviceManagementAdministrationIdentity> [-AdditionalProperties <Hashtable>]
 [-Definition <IMicrosoftGraphGroupPolicyDefinition>] [-Id <String>] [-Label <String>]
 [-LastModifiedDateTime <DateTime>] [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
The group policy presentations associated with the definition.

## EXAMPLES

## PARAMETERS

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

### -BodyParameter
The base entity for the display presentation of any of the additional options in a group policy definition.
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphGroupPolicyPresentation
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Definition
The entity describes all of the information about a single group policy.
To construct, please use Get-Help -Online and see NOTES section for DEFINITION properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphGroupPolicyDefinition
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GroupPolicyDefinitionId
key: id of groupPolicyDefinition

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

### -GroupPolicyPresentationId
key: id of groupPolicyPresentation

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
Type: Microsoft.Graph.PowerShell.Models.IDeviceManagementAdministrationIdentity
Parameter Sets: UpdateViaIdentity, UpdateViaIdentityExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Label
Localized text label for any presentation entity.
The default value is empty.

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

### -LastModifiedDateTime
The date and time the entity was last modified.

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

### Microsoft.Graph.PowerShell.Models.IDeviceManagementAdministrationIdentity

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphGroupPolicyPresentation

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphGroupPolicyPresentation>: The base entity for the display presentation of any of the additional options in a group policy definition.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[Definition <IMicrosoftGraphGroupPolicyDefinition>]`: The entity describes all of the information about a single group policy.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[Category <IMicrosoftGraphGroupPolicyCategory>]`: The category entity stores the category of a group policy definition
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[Children <IMicrosoftGraphGroupPolicyCategory[]>]`: The children categories
      - `[DefinitionFile <IMicrosoftGraphGroupPolicyDefinitionFile>]`: The entity represents an ADMX (Administrative Template) XML file. The ADMX file contains a collection of group policy definitions and their locations by category path. The group policy definition file also contains the languages supported as determined by the language dependent ADML (Administrative Template) language files.
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
        - `[Definitions <IMicrosoftGraphGroupPolicyDefinition[]>]`: The group policy definitions associated with the file.
        - `[Description <String>]`: The localized description of the policy settings in the ADMX file. The default value is empty.
        - `[DisplayName <String>]`: The localized friendly name of the ADMX file.
        - `[LanguageCodes <String[]>]`: The supported language codes for the ADMX file.
        - `[LastModifiedDateTime <DateTime?>]`: The date and time the entity was last modified.
        - `[PolicyType <String>]`: Type of Group Policy File or Definition.
        - `[Revision <String>]`: The revision version associated with the file.
        - `[TargetNamespace <String>]`: Specifies the URI used to identify the namespace within the ADMX file.
        - `[TargetPrefix <String>]`: Specifies the logical name that refers to the namespace within the ADMX file.
      - `[Definitions <IMicrosoftGraphGroupPolicyDefinition[]>]`: The immediate GroupPolicyDefinition children of the category
      - `[DisplayName <String>]`: The string id of the category's display name
      - `[IsRoot <Boolean?>]`: Defines if the category is a root category
      - `[LastModifiedDateTime <DateTime?>]`: The date and time the entity was last modified.
      - `[Parent <IMicrosoftGraphGroupPolicyCategory>]`: The category entity stores the category of a group policy definition
    - `[CategoryPath <String>]`: The localized full category path for the policy.
    - `[ClassType <String>]`: Group Policy Definition Class Type.
    - `[DefinitionFile <IMicrosoftGraphGroupPolicyDefinitionFile>]`: The entity represents an ADMX (Administrative Template) XML file. The ADMX file contains a collection of group policy definitions and their locations by category path. The group policy definition file also contains the languages supported as determined by the language dependent ADML (Administrative Template) language files.
    - `[DisplayName <String>]`: The localized policy name.
    - `[ExplainText <String>]`: The localized explanation or help text associated with the policy. The default value is empty.
    - `[GroupPolicyCategoryId <String>]`: The category id of the parent category
    - `[HasRelatedDefinitions <Boolean?>]`: Signifies whether or not there are related definitions to this definition
    - `[LastModifiedDateTime <DateTime?>]`: The date and time the entity was last modified.
    - `[MinDeviceCspVersion <String>]`: Minimum required CSP version for device configuration in this definition
    - `[MinUserCspVersion <String>]`: Minimum required CSP version for user configuration in this definition
    - `[NextVersionDefinition <IMicrosoftGraphGroupPolicyDefinition>]`: The entity describes all of the information about a single group policy.
    - `[PolicyType <String>]`: Type of Group Policy File or Definition.
    - `[Presentations <IMicrosoftGraphGroupPolicyPresentation[]>]`: The group policy presentations associated with the definition.
    - `[PreviousVersionDefinition <IMicrosoftGraphGroupPolicyDefinition>]`: The entity describes all of the information about a single group policy.
    - `[SupportedOn <String>]`: Localized string used to specify what operating system or application version is affected by the policy.
    - `[Version <String>]`: Setting definition version
  - `[Label <String>]`: Localized text label for any presentation entity. The default value is empty.
  - `[LastModifiedDateTime <DateTime?>]`: The date and time the entity was last modified.

DEFINITION <IMicrosoftGraphGroupPolicyDefinition>: The entity describes all of the information about a single group policy.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[Category <IMicrosoftGraphGroupPolicyCategory>]`: The category entity stores the category of a group policy definition
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[Children <IMicrosoftGraphGroupPolicyCategory[]>]`: The children categories
    - `[DefinitionFile <IMicrosoftGraphGroupPolicyDefinitionFile>]`: The entity represents an ADMX (Administrative Template) XML file. The ADMX file contains a collection of group policy definitions and their locations by category path. The group policy definition file also contains the languages supported as determined by the language dependent ADML (Administrative Template) language files.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[Definitions <IMicrosoftGraphGroupPolicyDefinition[]>]`: The group policy definitions associated with the file.
      - `[Description <String>]`: The localized description of the policy settings in the ADMX file. The default value is empty.
      - `[DisplayName <String>]`: The localized friendly name of the ADMX file.
      - `[LanguageCodes <String[]>]`: The supported language codes for the ADMX file.
      - `[LastModifiedDateTime <DateTime?>]`: The date and time the entity was last modified.
      - `[PolicyType <String>]`: Type of Group Policy File or Definition.
      - `[Revision <String>]`: The revision version associated with the file.
      - `[TargetNamespace <String>]`: Specifies the URI used to identify the namespace within the ADMX file.
      - `[TargetPrefix <String>]`: Specifies the logical name that refers to the namespace within the ADMX file.
    - `[Definitions <IMicrosoftGraphGroupPolicyDefinition[]>]`: The immediate GroupPolicyDefinition children of the category
    - `[DisplayName <String>]`: The string id of the category's display name
    - `[IsRoot <Boolean?>]`: Defines if the category is a root category
    - `[LastModifiedDateTime <DateTime?>]`: The date and time the entity was last modified.
    - `[Parent <IMicrosoftGraphGroupPolicyCategory>]`: The category entity stores the category of a group policy definition
  - `[CategoryPath <String>]`: The localized full category path for the policy.
  - `[ClassType <String>]`: Group Policy Definition Class Type.
  - `[DefinitionFile <IMicrosoftGraphGroupPolicyDefinitionFile>]`: The entity represents an ADMX (Administrative Template) XML file. The ADMX file contains a collection of group policy definitions and their locations by category path. The group policy definition file also contains the languages supported as determined by the language dependent ADML (Administrative Template) language files.
  - `[DisplayName <String>]`: The localized policy name.
  - `[ExplainText <String>]`: The localized explanation or help text associated with the policy. The default value is empty.
  - `[GroupPolicyCategoryId <String>]`: The category id of the parent category
  - `[HasRelatedDefinitions <Boolean?>]`: Signifies whether or not there are related definitions to this definition
  - `[LastModifiedDateTime <DateTime?>]`: The date and time the entity was last modified.
  - `[MinDeviceCspVersion <String>]`: Minimum required CSP version for device configuration in this definition
  - `[MinUserCspVersion <String>]`: Minimum required CSP version for user configuration in this definition
  - `[NextVersionDefinition <IMicrosoftGraphGroupPolicyDefinition>]`: The entity describes all of the information about a single group policy.
  - `[PolicyType <String>]`: Type of Group Policy File or Definition.
  - `[Presentations <IMicrosoftGraphGroupPolicyPresentation[]>]`: The group policy presentations associated with the definition.
    - `[Id <String>]`: Read-only.
    - `[Definition <IMicrosoftGraphGroupPolicyDefinition>]`: The entity describes all of the information about a single group policy.
    - `[Label <String>]`: Localized text label for any presentation entity. The default value is empty.
    - `[LastModifiedDateTime <DateTime?>]`: The date and time the entity was last modified.
  - `[PreviousVersionDefinition <IMicrosoftGraphGroupPolicyDefinition>]`: The entity describes all of the information about a single group policy.
  - `[SupportedOn <String>]`: Localized string used to specify what operating system or application version is affected by the policy.
  - `[Version <String>]`: Setting definition version

INPUTOBJECT <IDeviceManagementAdministrationIdentity>: Identity Parameter
  - `[AuditEventId <String>]`: key: id of auditEvent
  - `[CartToClassAssociationId <String>]`: key: id of cartToClassAssociation
  - `[CloudPcAuditEventId <String>]`: key: id of cloudPcAuditEvent
  - `[CloudPcDeviceImageId <String>]`: key: id of cloudPcDeviceImage
  - `[CloudPcGalleryImageId <String>]`: key: id of cloudPcGalleryImage
  - `[CloudPcId <String>]`: key: id of cloudPC
  - `[CloudPcOnPremisesConnectionId <String>]`: key: id of cloudPcOnPremisesConnection
  - `[CloudPcProvisioningPolicyAssignmentId <String>]`: key: id of cloudPcProvisioningPolicyAssignment
  - `[CloudPcProvisioningPolicyId <String>]`: key: id of cloudPcProvisioningPolicy
  - `[CloudPcServicePlanId <String>]`: key: id of cloudPcServicePlan
  - `[CloudPcSnapshotId <String>]`: key: id of cloudPcSnapshot
  - `[CloudPcSupportedRegionId <String>]`: key: id of cloudPcSupportedRegion
  - `[CloudPcUserSettingAssignmentId <String>]`: key: id of cloudPcUserSettingAssignment
  - `[CloudPcUserSettingId <String>]`: key: id of cloudPcUserSetting
  - `[ComanagementEligibleDeviceId <String>]`: key: id of comanagementEligibleDevice
  - `[ComplianceManagementPartnerId <String>]`: key: id of complianceManagementPartner
  - `[DeviceAndAppManagementRoleAssignmentId <String>]`: key: id of deviceAndAppManagementRoleAssignment
  - `[DeviceManagementDomainJoinConnectorId <String>]`: key: id of deviceManagementDomainJoinConnector
  - `[DeviceManagementExchangeConnectorId <String>]`: key: id of deviceManagementExchangeConnector
  - `[DeviceManagementExchangeOnPremisesPolicyId <String>]`: key: id of deviceManagementExchangeOnPremisesPolicy
  - `[DeviceManagementPartnerId <String>]`: key: id of deviceManagementPartner
  - `[GroupPolicyCategoryId <String>]`: key: id of groupPolicyCategory
  - `[GroupPolicyDefinitionFileId <String>]`: key: id of groupPolicyDefinitionFile
  - `[GroupPolicyDefinitionId <String>]`: key: id of groupPolicyDefinition
  - `[GroupPolicyMigrationReportId <String>]`: key: id of groupPolicyMigrationReport
  - `[GroupPolicyObjectFileId <String>]`: key: id of groupPolicyObjectFile
  - `[GroupPolicyOperationId <String>]`: key: id of groupPolicyOperation
  - `[GroupPolicyPresentationId <String>]`: key: id of groupPolicyPresentation
  - `[GroupPolicySettingMappingId <String>]`: key: id of groupPolicySettingMapping
  - `[GroupPolicyUploadedDefinitionFileId <String>]`: key: id of groupPolicyUploadedDefinitionFile
  - `[IntuneBrandingProfileAssignmentId <String>]`: key: id of intuneBrandingProfileAssignment
  - `[IntuneBrandingProfileId <String>]`: key: id of intuneBrandingProfile
  - `[IosUpdateDeviceStatusId <String>]`: key: id of iosUpdateDeviceStatus
  - `[ManagedAllDeviceCertificateStateId <String>]`: key: id of managedAllDeviceCertificateState
  - `[MobileThreatDefenseConnectorId <String>]`: key: id of mobileThreatDefenseConnector
  - `[NdesConnectorId <String>]`: key: id of ndesConnector
  - `[RemoteAssistancePartnerId <String>]`: key: id of remoteAssistancePartner
  - `[ResourceOperationId <String>]`: key: id of resourceOperation
  - `[RestrictedAppsViolationId <String>]`: key: id of restrictedAppsViolation
  - `[RoleAssignmentId <String>]`: key: id of roleAssignment
  - `[RoleDefinitionId <String>]`: key: id of roleDefinition
  - `[RoleScopeTagAutoAssignmentId <String>]`: key: id of roleScopeTagAutoAssignment
  - `[RoleScopeTagId <String>]`: key: id of roleScopeTag
  - `[TelecomExpenseManagementPartnerId <String>]`: key: id of telecomExpenseManagementPartner
  - `[TermsAndConditionsAcceptanceStatusId <String>]`: key: id of termsAndConditionsAcceptanceStatus
  - `[TermsAndConditionsAssignmentId <String>]`: key: id of termsAndConditionsAssignment
  - `[TermsAndConditionsGroupAssignmentId <String>]`: key: id of termsAndConditionsGroupAssignment
  - `[TermsAndConditionsId <String>]`: key: id of termsAndConditions
  - `[UnsupportedGroupPolicyExtensionId <String>]`: key: id of unsupportedGroupPolicyExtension
  - `[UserPfxCertificateId <String>]`: key: id of userPFXCertificate

## RELATED LINKS

