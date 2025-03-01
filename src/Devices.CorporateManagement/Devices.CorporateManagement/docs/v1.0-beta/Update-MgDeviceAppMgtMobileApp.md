---
external help file:
Module Name: Microsoft.Graph.Devices.CorporateManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devices.corporatemanagement/update-mgdeviceappmgtmobileapp
schema: 2.0.0
---

# Update-MgDeviceAppMgtMobileApp

## SYNOPSIS
The mobile apps.

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgDeviceAppMgtMobileApp -MobileAppId <String> [-AdditionalProperties <Hashtable>]
 [-Assignments <IMicrosoftGraphMobileAppAssignment[]>] [-Categories <IMicrosoftGraphMobileAppCategory[]>]
 [-CreatedDateTime <DateTime>] [-DependentAppCount <Int32>] [-Description <String>] [-Developer <String>]
 [-DeviceStatuses <IMicrosoftGraphMobileAppInstallStatus[]>] [-DisplayName <String>] [-Id <String>]
 [-InformationUrl <String>] [-InstallSummary <IMicrosoftGraphMobileAppInstallSummary>] [-IsAssigned]
 [-IsFeatured] [-LargeIcon <IMicrosoftGraphMimeContent>] [-LastModifiedDateTime <DateTime>] [-Notes <String>]
 [-Owner <String>] [-PrivacyInformationUrl <String>] [-Publisher <String>] [-PublishingState <String>]
 [-Relationships <IMicrosoftGraphMobileAppRelationship[]>] [-RoleScopeTagIds <String[]>]
 [-SupersededAppCount <Int32>] [-SupersedingAppCount <Int32>] [-UploadState <Int32>]
 [-UserStatuses <IMicrosoftGraphUserAppInstallStatus[]>] [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Update
```
Update-MgDeviceAppMgtMobileApp -MobileAppId <String> -BodyParameter <IMicrosoftGraphMobileApp> [-PassThru]
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgDeviceAppMgtMobileApp -InputObject <IDevicesCorporateManagementIdentity>
 -BodyParameter <IMicrosoftGraphMobileApp> [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgDeviceAppMgtMobileApp -InputObject <IDevicesCorporateManagementIdentity>
 [-AdditionalProperties <Hashtable>] [-Assignments <IMicrosoftGraphMobileAppAssignment[]>]
 [-Categories <IMicrosoftGraphMobileAppCategory[]>] [-CreatedDateTime <DateTime>] [-DependentAppCount <Int32>]
 [-Description <String>] [-Developer <String>] [-DeviceStatuses <IMicrosoftGraphMobileAppInstallStatus[]>]
 [-DisplayName <String>] [-Id <String>] [-InformationUrl <String>]
 [-InstallSummary <IMicrosoftGraphMobileAppInstallSummary>] [-IsAssigned] [-IsFeatured]
 [-LargeIcon <IMicrosoftGraphMimeContent>] [-LastModifiedDateTime <DateTime>] [-Notes <String>]
 [-Owner <String>] [-PrivacyInformationUrl <String>] [-Publisher <String>] [-PublishingState <String>]
 [-Relationships <IMicrosoftGraphMobileAppRelationship[]>] [-RoleScopeTagIds <String[]>]
 [-SupersededAppCount <Int32>] [-SupersedingAppCount <Int32>] [-UploadState <Int32>]
 [-UserStatuses <IMicrosoftGraphUserAppInstallStatus[]>] [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
The mobile apps.

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

### -Assignments
The list of group assignments for this mobile app.
To construct, please use Get-Help -Online and see NOTES section for ASSIGNMENTS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMobileAppAssignment[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
An abstract class containing the base properties for Intune mobile apps.
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMobileApp
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Categories
The list of categories for this app.
To construct, please use Get-Help -Online and see NOTES section for CATEGORIES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMobileAppCategory[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CreatedDateTime
The date and time the app was created.

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

### -DependentAppCount
The total number of dependencies the child app has.

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

### -Description
The description of the app.

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

### -Developer
The developer of the app.

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

### -DeviceStatuses
The list of installation states for this mobile app.
To construct, please use Get-Help -Online and see NOTES section for DEVICESTATUSES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMobileAppInstallStatus[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
The admin provided or imported title of the app.

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

### -InformationUrl
The more information Url.

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
Type: Microsoft.Graph.PowerShell.Models.IDevicesCorporateManagementIdentity
Parameter Sets: UpdateViaIdentity, UpdateViaIdentityExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -InstallSummary
Contains properties for the installation summary of a mobile app.
To construct, please use Get-Help -Online and see NOTES section for INSTALLSUMMARY properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMobileAppInstallSummary
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsAssigned
The value indicating whether the app is assigned to at least one group.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsFeatured
The value indicating whether the app is marked as featured by the admin.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LargeIcon
Contains properties for a generic mime content.
To construct, please use Get-Help -Online and see NOTES section for LARGEICON properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMimeContent
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LastModifiedDateTime
The date and time the app was last modified.

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

### -MobileAppId
key: id of mobileApp

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

### -Notes
Notes for the app.

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

### -Owner
The owner of the app.

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

### -PrivacyInformationUrl
The privacy statement Url.

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

### -Publisher
The publisher of the app.

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

### -PublishingState
Indicates the publishing state of an app.

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

### -Relationships
List of relationships for this mobile app.
To construct, please use Get-Help -Online and see NOTES section for RELATIONSHIPS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMobileAppRelationship[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RoleScopeTagIds
List of scope tag ids for this mobile app.

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

### -SupersededAppCount
The total number of apps this app is directly or indirectly superseded by.

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

### -SupersedingAppCount
The total number of apps this app directly or indirectly supersedes.

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

### -UploadState
The upload state.

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

### -UserStatuses
The list of installation states for this mobile app.
To construct, please use Get-Help -Online and see NOTES section for USERSTATUSES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserAppInstallStatus[]
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

### Microsoft.Graph.PowerShell.Models.IDevicesCorporateManagementIdentity

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMobileApp

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

### Update-MgDeviceAppManagementMobileApp

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


ASSIGNMENTS <IMicrosoftGraphMobileAppAssignment[]>: The list of group assignments for this mobile app.
  - `[Id <String>]`: Read-only.
  - `[Intent <String>]`: Possible values for the install intent chosen by the admin.
  - `[Settings <IMicrosoftGraphMobileAppAssignmentSettings>]`: Abstract class to contain properties used to assign a mobile app to a group.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Source <String>]`: Represents source of assignment.
  - `[SourceId <String>]`: The identifier of the source of the assignment.
  - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DeviceAndAppManagementAssignmentFilterId <String>]`: The Id of the filter for the target assignment.
    - `[DeviceAndAppManagementAssignmentFilterType <String>]`: Represents type of the assignment filter.

BODYPARAMETER <IMicrosoftGraphMobileApp>: An abstract class containing the base properties for Intune mobile apps.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[Assignments <IMicrosoftGraphMobileAppAssignment[]>]`: The list of group assignments for this mobile app.
    - `[Id <String>]`: Read-only.
    - `[Intent <String>]`: Possible values for the install intent chosen by the admin.
    - `[Settings <IMicrosoftGraphMobileAppAssignmentSettings>]`: Abstract class to contain properties used to assign a mobile app to a group.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Source <String>]`: Represents source of assignment.
    - `[SourceId <String>]`: The identifier of the source of the assignment.
    - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[DeviceAndAppManagementAssignmentFilterId <String>]`: The Id of the filter for the target assignment.
      - `[DeviceAndAppManagementAssignmentFilterType <String>]`: Represents type of the assignment filter.
  - `[Categories <IMicrosoftGraphMobileAppCategory[]>]`: The list of categories for this app.
    - `[Id <String>]`: Read-only.
    - `[DisplayName <String>]`: The name of the app category.
    - `[LastModifiedDateTime <DateTime?>]`: The date and time the mobileAppCategory was last modified.
  - `[CreatedDateTime <DateTime?>]`: The date and time the app was created.
  - `[DependentAppCount <Int32?>]`: The total number of dependencies the child app has.
  - `[Description <String>]`: The description of the app.
  - `[Developer <String>]`: The developer of the app.
  - `[DeviceStatuses <IMicrosoftGraphMobileAppInstallStatus[]>]`: The list of installation states for this mobile app.
    - `[Id <String>]`: Read-only.
    - `[App <IMicrosoftGraphMobileApp>]`: An abstract class containing the base properties for Intune mobile apps.
    - `[DeviceId <String>]`: Device ID
    - `[DeviceName <String>]`: Device name
    - `[DisplayVersion <String>]`: Human readable version of the application
    - `[ErrorCode <Int32?>]`: The error code for install or uninstall failures.
    - `[InstallState <String>]`: resultantAppState
    - `[InstallStateDetail <String>]`: Enum indicating additional details regarding why an application has a particular install state.
    - `[LastSyncDateTime <DateTime?>]`: Last sync date time
    - `[MobileAppInstallStatusValue <String>]`: resultantAppState
    - `[OSDescription <String>]`: OS Description
    - `[OSVersion <String>]`: OS Version
    - `[UserName <String>]`: Device User Name
    - `[UserPrincipalName <String>]`: User Principal Name
  - `[DisplayName <String>]`: The admin provided or imported title of the app.
  - `[InformationUrl <String>]`: The more information Url.
  - `[InstallSummary <IMicrosoftGraphMobileAppInstallSummary>]`: Contains properties for the installation summary of a mobile app.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[FailedDeviceCount <Int32?>]`: Number of Devices that have failed to install this app.
    - `[FailedUserCount <Int32?>]`: Number of Users that have 1 or more device that failed to install this app.
    - `[InstalledDeviceCount <Int32?>]`: Number of Devices that have successfully installed this app.
    - `[InstalledUserCount <Int32?>]`: Number of Users whose devices have all succeeded to install this app.
    - `[NotApplicableDeviceCount <Int32?>]`: Number of Devices that are not applicable for this app.
    - `[NotApplicableUserCount <Int32?>]`: Number of Users whose devices were all not applicable for this app.
    - `[NotInstalledDeviceCount <Int32?>]`: Number of Devices that does not have this app installed.
    - `[NotInstalledUserCount <Int32?>]`: Number of Users that have 1 or more devices that did not install this app.
    - `[PendingInstallDeviceCount <Int32?>]`: Number of Devices that have been notified to install this app.
    - `[PendingInstallUserCount <Int32?>]`: Number of Users that have 1 or more device that have been notified to install this app and have 0 devices with failures.
  - `[IsAssigned <Boolean?>]`: The value indicating whether the app is assigned to at least one group.
  - `[IsFeatured <Boolean?>]`: The value indicating whether the app is marked as featured by the admin.
  - `[LargeIcon <IMicrosoftGraphMimeContent>]`: Contains properties for a generic mime content.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Type <String>]`: Indicates the content mime type.
    - `[Value <Byte[]>]`: The byte array that contains the actual content.
  - `[LastModifiedDateTime <DateTime?>]`: The date and time the app was last modified.
  - `[Notes <String>]`: Notes for the app.
  - `[Owner <String>]`: The owner of the app.
  - `[PrivacyInformationUrl <String>]`: The privacy statement Url.
  - `[Publisher <String>]`: The publisher of the app.
  - `[PublishingState <String>]`: Indicates the publishing state of an app.
  - `[Relationships <IMicrosoftGraphMobileAppRelationship[]>]`: List of relationships for this mobile app.
    - `[Id <String>]`: Read-only.
    - `[TargetDisplayName <String>]`: The target mobile app's display name.
    - `[TargetDisplayVersion <String>]`: The target mobile app's display version.
    - `[TargetId <String>]`: The target mobile app's app id.
    - `[TargetPublisher <String>]`: The target mobile app's publisher.
    - `[TargetType <String>]`: Indicates whether the target of a relationship is the parent or the child in the relationship.
  - `[RoleScopeTagIds <String[]>]`: List of scope tag ids for this mobile app.
  - `[SupersededAppCount <Int32?>]`: The total number of apps this app is directly or indirectly superseded by.
  - `[SupersedingAppCount <Int32?>]`: The total number of apps this app directly or indirectly supersedes.
  - `[UploadState <Int32?>]`: The upload state.
  - `[UserStatuses <IMicrosoftGraphUserAppInstallStatus[]>]`: The list of installation states for this mobile app.
    - `[Id <String>]`: Read-only.
    - `[App <IMicrosoftGraphMobileApp>]`: An abstract class containing the base properties for Intune mobile apps.
    - `[DeviceStatuses <IMicrosoftGraphMobileAppInstallStatus[]>]`: The install state of the app on devices.
    - `[FailedDeviceCount <Int32?>]`: Failed Device Count.
    - `[InstalledDeviceCount <Int32?>]`: Installed Device Count.
    - `[NotInstalledDeviceCount <Int32?>]`: Not installed device count.
    - `[UserName <String>]`: User name.
    - `[UserPrincipalName <String>]`: User Principal Name.

CATEGORIES <IMicrosoftGraphMobileAppCategory[]>: The list of categories for this app.
  - `[Id <String>]`: Read-only.
  - `[DisplayName <String>]`: The name of the app category.
  - `[LastModifiedDateTime <DateTime?>]`: The date and time the mobileAppCategory was last modified.

DEVICESTATUSES <IMicrosoftGraphMobileAppInstallStatus[]>: The list of installation states for this mobile app.
  - `[Id <String>]`: Read-only.
  - `[App <IMicrosoftGraphMobileApp>]`: An abstract class containing the base properties for Intune mobile apps.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[Assignments <IMicrosoftGraphMobileAppAssignment[]>]`: The list of group assignments for this mobile app.
      - `[Id <String>]`: Read-only.
      - `[Intent <String>]`: Possible values for the install intent chosen by the admin.
      - `[Settings <IMicrosoftGraphMobileAppAssignmentSettings>]`: Abstract class to contain properties used to assign a mobile app to a group.
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Source <String>]`: Represents source of assignment.
      - `[SourceId <String>]`: The identifier of the source of the assignment.
      - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[DeviceAndAppManagementAssignmentFilterId <String>]`: The Id of the filter for the target assignment.
        - `[DeviceAndAppManagementAssignmentFilterType <String>]`: Represents type of the assignment filter.
    - `[Categories <IMicrosoftGraphMobileAppCategory[]>]`: The list of categories for this app.
      - `[Id <String>]`: Read-only.
      - `[DisplayName <String>]`: The name of the app category.
      - `[LastModifiedDateTime <DateTime?>]`: The date and time the mobileAppCategory was last modified.
    - `[CreatedDateTime <DateTime?>]`: The date and time the app was created.
    - `[DependentAppCount <Int32?>]`: The total number of dependencies the child app has.
    - `[Description <String>]`: The description of the app.
    - `[Developer <String>]`: The developer of the app.
    - `[DeviceStatuses <IMicrosoftGraphMobileAppInstallStatus[]>]`: The list of installation states for this mobile app.
    - `[DisplayName <String>]`: The admin provided or imported title of the app.
    - `[InformationUrl <String>]`: The more information Url.
    - `[InstallSummary <IMicrosoftGraphMobileAppInstallSummary>]`: Contains properties for the installation summary of a mobile app.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[FailedDeviceCount <Int32?>]`: Number of Devices that have failed to install this app.
      - `[FailedUserCount <Int32?>]`: Number of Users that have 1 or more device that failed to install this app.
      - `[InstalledDeviceCount <Int32?>]`: Number of Devices that have successfully installed this app.
      - `[InstalledUserCount <Int32?>]`: Number of Users whose devices have all succeeded to install this app.
      - `[NotApplicableDeviceCount <Int32?>]`: Number of Devices that are not applicable for this app.
      - `[NotApplicableUserCount <Int32?>]`: Number of Users whose devices were all not applicable for this app.
      - `[NotInstalledDeviceCount <Int32?>]`: Number of Devices that does not have this app installed.
      - `[NotInstalledUserCount <Int32?>]`: Number of Users that have 1 or more devices that did not install this app.
      - `[PendingInstallDeviceCount <Int32?>]`: Number of Devices that have been notified to install this app.
      - `[PendingInstallUserCount <Int32?>]`: Number of Users that have 1 or more device that have been notified to install this app and have 0 devices with failures.
    - `[IsAssigned <Boolean?>]`: The value indicating whether the app is assigned to at least one group.
    - `[IsFeatured <Boolean?>]`: The value indicating whether the app is marked as featured by the admin.
    - `[LargeIcon <IMicrosoftGraphMimeContent>]`: Contains properties for a generic mime content.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Type <String>]`: Indicates the content mime type.
      - `[Value <Byte[]>]`: The byte array that contains the actual content.
    - `[LastModifiedDateTime <DateTime?>]`: The date and time the app was last modified.
    - `[Notes <String>]`: Notes for the app.
    - `[Owner <String>]`: The owner of the app.
    - `[PrivacyInformationUrl <String>]`: The privacy statement Url.
    - `[Publisher <String>]`: The publisher of the app.
    - `[PublishingState <String>]`: Indicates the publishing state of an app.
    - `[Relationships <IMicrosoftGraphMobileAppRelationship[]>]`: List of relationships for this mobile app.
      - `[Id <String>]`: Read-only.
      - `[TargetDisplayName <String>]`: The target mobile app's display name.
      - `[TargetDisplayVersion <String>]`: The target mobile app's display version.
      - `[TargetId <String>]`: The target mobile app's app id.
      - `[TargetPublisher <String>]`: The target mobile app's publisher.
      - `[TargetType <String>]`: Indicates whether the target of a relationship is the parent or the child in the relationship.
    - `[RoleScopeTagIds <String[]>]`: List of scope tag ids for this mobile app.
    - `[SupersededAppCount <Int32?>]`: The total number of apps this app is directly or indirectly superseded by.
    - `[SupersedingAppCount <Int32?>]`: The total number of apps this app directly or indirectly supersedes.
    - `[UploadState <Int32?>]`: The upload state.
    - `[UserStatuses <IMicrosoftGraphUserAppInstallStatus[]>]`: The list of installation states for this mobile app.
      - `[Id <String>]`: Read-only.
      - `[App <IMicrosoftGraphMobileApp>]`: An abstract class containing the base properties for Intune mobile apps.
      - `[DeviceStatuses <IMicrosoftGraphMobileAppInstallStatus[]>]`: The install state of the app on devices.
      - `[FailedDeviceCount <Int32?>]`: Failed Device Count.
      - `[InstalledDeviceCount <Int32?>]`: Installed Device Count.
      - `[NotInstalledDeviceCount <Int32?>]`: Not installed device count.
      - `[UserName <String>]`: User name.
      - `[UserPrincipalName <String>]`: User Principal Name.
  - `[DeviceId <String>]`: Device ID
  - `[DeviceName <String>]`: Device name
  - `[DisplayVersion <String>]`: Human readable version of the application
  - `[ErrorCode <Int32?>]`: The error code for install or uninstall failures.
  - `[InstallState <String>]`: resultantAppState
  - `[InstallStateDetail <String>]`: Enum indicating additional details regarding why an application has a particular install state.
  - `[LastSyncDateTime <DateTime?>]`: Last sync date time
  - `[MobileAppInstallStatusValue <String>]`: resultantAppState
  - `[OSDescription <String>]`: OS Description
  - `[OSVersion <String>]`: OS Version
  - `[UserName <String>]`: Device User Name
  - `[UserPrincipalName <String>]`: User Principal Name

INPUTOBJECT <IDevicesCorporateManagementIdentity>: Identity Parameter
  - `[AndroidManagedAppProtectionId <String>]`: key: id of androidManagedAppProtection
  - `[AppLogCollectionRequestId <String>]`: key: id of appLogCollectionRequest
  - `[AssignmentFilterEvaluationStatusDetailsId <String>]`: key: id of assignmentFilterEvaluationStatusDetails
  - `[BundleId <String>]`: Usage: bundleId={bundleId}
  - `[Count <Int64?>]`: Usage: count={count}
  - `[DefaultManagedAppProtectionId <String>]`: key: id of defaultManagedAppProtection
  - `[DeviceAppManagementTaskId <String>]`: key: id of deviceAppManagementTask
  - `[DeviceCompliancePolicyStateId <String>]`: key: id of deviceCompliancePolicyState
  - `[DeviceConfigurationStateId <String>]`: key: id of deviceConfigurationState
  - `[DeviceEnrollmentConfigurationId <String>]`: key: id of deviceEnrollmentConfiguration
  - `[DeviceId <String>]`: Usage: deviceId={deviceId}
  - `[DeviceInstallStateId <String>]`: key: id of deviceInstallState
  - `[DeviceLogCollectionResponseId <String>]`: key: id of deviceLogCollectionResponse
  - `[DeviceManagementTroubleshootingEventId <String>]`: key: id of deviceManagementTroubleshootingEvent
  - `[EnrollmentConfigurationAssignmentId <String>]`: key: id of enrollmentConfigurationAssignment
  - `[EnterpriseCodeSigningCertificateId <String>]`: key: id of enterpriseCodeSigningCertificate
  - `[IosLobAppProvisioningConfigurationAssignmentId <String>]`: key: id of iosLobAppProvisioningConfigurationAssignment
  - `[IosLobAppProvisioningConfigurationId <String>]`: key: id of iosLobAppProvisioningConfiguration
  - `[IosManagedAppProtectionId <String>]`: key: id of iosManagedAppProtection
  - `[ManagedAppOperationId <String>]`: key: id of managedAppOperation
  - `[ManagedAppPolicyId <String>]`: key: id of managedAppPolicy
  - `[ManagedAppRegistrationId <String>]`: key: id of managedAppRegistration
  - `[ManagedAppStatusId <String>]`: key: id of managedAppStatus
  - `[ManagedDeviceId <String>]`: key: id of managedDevice
  - `[ManagedDeviceMobileAppConfigurationAssignmentId <String>]`: key: id of managedDeviceMobileAppConfigurationAssignment
  - `[ManagedDeviceMobileAppConfigurationDeviceStatusId <String>]`: key: id of managedDeviceMobileAppConfigurationDeviceStatus
  - `[ManagedDeviceMobileAppConfigurationId <String>]`: key: id of managedDeviceMobileAppConfiguration
  - `[ManagedDeviceMobileAppConfigurationStateId <String>]`: key: id of managedDeviceMobileAppConfigurationState
  - `[ManagedDeviceMobileAppConfigurationUserStatusId <String>]`: key: id of managedDeviceMobileAppConfigurationUserStatus
  - `[ManagedEBookAssignmentId <String>]`: key: id of managedEBookAssignment
  - `[ManagedEBookCategoryId <String>]`: key: id of managedEBookCategory
  - `[ManagedEBookId <String>]`: key: id of managedEBook
  - `[ManagedMobileAppId <String>]`: key: id of managedMobileApp
  - `[MdmWindowsInformationProtectionPolicyId <String>]`: key: id of mdmWindowsInformationProtectionPolicy
  - `[MobileAppAssignmentId <String>]`: key: id of mobileAppAssignment
  - `[MobileAppCategoryId <String>]`: key: id of mobileAppCategory
  - `[MobileAppId <String>]`: key: id of mobileApp
  - `[MobileAppInstallStatusId <String>]`: key: id of mobileAppInstallStatus
  - `[MobileAppIntentAndStateId <String>]`: key: id of mobileAppIntentAndState
  - `[MobileAppProvisioningConfigGroupAssignmentId <String>]`: key: id of mobileAppProvisioningConfigGroupAssignment
  - `[MobileAppRelationshipId <String>]`: key: id of mobileAppRelationship
  - `[MobileAppTroubleshootingEventId <String>]`: key: id of mobileAppTroubleshootingEvent
  - `[OfficeClientConfigurationAssignmentId <String>]`: key: id of officeClientConfigurationAssignment
  - `[OfficeClientConfigurationId <String>]`: key: id of officeClientConfiguration
  - `[PolicySetAssignmentId <String>]`: key: id of policySetAssignment
  - `[PolicySetId <String>]`: key: id of policySet
  - `[PolicySetItemId <String>]`: key: id of policySetItem
  - `[SecurityBaselineSettingStateId <String>]`: key: id of securityBaselineSettingState
  - `[SecurityBaselineStateId <String>]`: key: id of securityBaselineState
  - `[SideLoadingKeyId <String>]`: key: id of sideLoadingKey
  - `[Status <String>]`: Usage: status={status}
  - `[TargetedManagedAppConfigurationId <String>]`: key: id of targetedManagedAppConfiguration
  - `[TargetedManagedAppPolicyAssignmentId <String>]`: key: id of targetedManagedAppPolicyAssignment
  - `[UserAppInstallStatusId <String>]`: key: id of userAppInstallStatus
  - `[UserId <String>]`: key: id of user
  - `[UserInstallStateSummaryId <String>]`: key: id of userInstallStateSummary
  - `[UserPrincipalName <String>]`: Usage: userPrincipalName={userPrincipalName}
  - `[VppTokenId <String>]`: key: id of vppToken
  - `[WindowsDefenderApplicationControlSupplementalPolicyAssignmentId <String>]`: key: id of windowsDefenderApplicationControlSupplementalPolicyAssignment
  - `[WindowsDefenderApplicationControlSupplementalPolicyDeploymentStatusId <String>]`: key: id of windowsDefenderApplicationControlSupplementalPolicyDeploymentStatus
  - `[WindowsDefenderApplicationControlSupplementalPolicyId <String>]`: key: id of windowsDefenderApplicationControlSupplementalPolicy
  - `[WindowsDeviceMalwareStateId <String>]`: key: id of windowsDeviceMalwareState
  - `[WindowsInformationProtectionDeviceRegistrationId <String>]`: key: id of windowsInformationProtectionDeviceRegistration
  - `[WindowsInformationProtectionPolicyId <String>]`: key: id of windowsInformationProtectionPolicy
  - `[WindowsInformationProtectionWipeActionId <String>]`: key: id of windowsInformationProtectionWipeAction

INSTALLSUMMARY <IMicrosoftGraphMobileAppInstallSummary>: Contains properties for the installation summary of a mobile app.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[FailedDeviceCount <Int32?>]`: Number of Devices that have failed to install this app.
  - `[FailedUserCount <Int32?>]`: Number of Users that have 1 or more device that failed to install this app.
  - `[InstalledDeviceCount <Int32?>]`: Number of Devices that have successfully installed this app.
  - `[InstalledUserCount <Int32?>]`: Number of Users whose devices have all succeeded to install this app.
  - `[NotApplicableDeviceCount <Int32?>]`: Number of Devices that are not applicable for this app.
  - `[NotApplicableUserCount <Int32?>]`: Number of Users whose devices were all not applicable for this app.
  - `[NotInstalledDeviceCount <Int32?>]`: Number of Devices that does not have this app installed.
  - `[NotInstalledUserCount <Int32?>]`: Number of Users that have 1 or more devices that did not install this app.
  - `[PendingInstallDeviceCount <Int32?>]`: Number of Devices that have been notified to install this app.
  - `[PendingInstallUserCount <Int32?>]`: Number of Users that have 1 or more device that have been notified to install this app and have 0 devices with failures.

LARGEICON <IMicrosoftGraphMimeContent>: Contains properties for a generic mime content.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Type <String>]`: Indicates the content mime type.
  - `[Value <Byte[]>]`: The byte array that contains the actual content.

RELATIONSHIPS <IMicrosoftGraphMobileAppRelationship[]>: List of relationships for this mobile app.
  - `[Id <String>]`: Read-only.
  - `[TargetDisplayName <String>]`: The target mobile app's display name.
  - `[TargetDisplayVersion <String>]`: The target mobile app's display version.
  - `[TargetId <String>]`: The target mobile app's app id.
  - `[TargetPublisher <String>]`: The target mobile app's publisher.
  - `[TargetType <String>]`: Indicates whether the target of a relationship is the parent or the child in the relationship.

USERSTATUSES <IMicrosoftGraphUserAppInstallStatus[]>: The list of installation states for this mobile app.
  - `[Id <String>]`: Read-only.
  - `[App <IMicrosoftGraphMobileApp>]`: An abstract class containing the base properties for Intune mobile apps.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[Assignments <IMicrosoftGraphMobileAppAssignment[]>]`: The list of group assignments for this mobile app.
      - `[Id <String>]`: Read-only.
      - `[Intent <String>]`: Possible values for the install intent chosen by the admin.
      - `[Settings <IMicrosoftGraphMobileAppAssignmentSettings>]`: Abstract class to contain properties used to assign a mobile app to a group.
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Source <String>]`: Represents source of assignment.
      - `[SourceId <String>]`: The identifier of the source of the assignment.
      - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[DeviceAndAppManagementAssignmentFilterId <String>]`: The Id of the filter for the target assignment.
        - `[DeviceAndAppManagementAssignmentFilterType <String>]`: Represents type of the assignment filter.
    - `[Categories <IMicrosoftGraphMobileAppCategory[]>]`: The list of categories for this app.
      - `[Id <String>]`: Read-only.
      - `[DisplayName <String>]`: The name of the app category.
      - `[LastModifiedDateTime <DateTime?>]`: The date and time the mobileAppCategory was last modified.
    - `[CreatedDateTime <DateTime?>]`: The date and time the app was created.
    - `[DependentAppCount <Int32?>]`: The total number of dependencies the child app has.
    - `[Description <String>]`: The description of the app.
    - `[Developer <String>]`: The developer of the app.
    - `[DeviceStatuses <IMicrosoftGraphMobileAppInstallStatus[]>]`: The list of installation states for this mobile app.
      - `[Id <String>]`: Read-only.
      - `[App <IMicrosoftGraphMobileApp>]`: An abstract class containing the base properties for Intune mobile apps.
      - `[DeviceId <String>]`: Device ID
      - `[DeviceName <String>]`: Device name
      - `[DisplayVersion <String>]`: Human readable version of the application
      - `[ErrorCode <Int32?>]`: The error code for install or uninstall failures.
      - `[InstallState <String>]`: resultantAppState
      - `[InstallStateDetail <String>]`: Enum indicating additional details regarding why an application has a particular install state.
      - `[LastSyncDateTime <DateTime?>]`: Last sync date time
      - `[MobileAppInstallStatusValue <String>]`: resultantAppState
      - `[OSDescription <String>]`: OS Description
      - `[OSVersion <String>]`: OS Version
      - `[UserName <String>]`: Device User Name
      - `[UserPrincipalName <String>]`: User Principal Name
    - `[DisplayName <String>]`: The admin provided or imported title of the app.
    - `[InformationUrl <String>]`: The more information Url.
    - `[InstallSummary <IMicrosoftGraphMobileAppInstallSummary>]`: Contains properties for the installation summary of a mobile app.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[FailedDeviceCount <Int32?>]`: Number of Devices that have failed to install this app.
      - `[FailedUserCount <Int32?>]`: Number of Users that have 1 or more device that failed to install this app.
      - `[InstalledDeviceCount <Int32?>]`: Number of Devices that have successfully installed this app.
      - `[InstalledUserCount <Int32?>]`: Number of Users whose devices have all succeeded to install this app.
      - `[NotApplicableDeviceCount <Int32?>]`: Number of Devices that are not applicable for this app.
      - `[NotApplicableUserCount <Int32?>]`: Number of Users whose devices were all not applicable for this app.
      - `[NotInstalledDeviceCount <Int32?>]`: Number of Devices that does not have this app installed.
      - `[NotInstalledUserCount <Int32?>]`: Number of Users that have 1 or more devices that did not install this app.
      - `[PendingInstallDeviceCount <Int32?>]`: Number of Devices that have been notified to install this app.
      - `[PendingInstallUserCount <Int32?>]`: Number of Users that have 1 or more device that have been notified to install this app and have 0 devices with failures.
    - `[IsAssigned <Boolean?>]`: The value indicating whether the app is assigned to at least one group.
    - `[IsFeatured <Boolean?>]`: The value indicating whether the app is marked as featured by the admin.
    - `[LargeIcon <IMicrosoftGraphMimeContent>]`: Contains properties for a generic mime content.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Type <String>]`: Indicates the content mime type.
      - `[Value <Byte[]>]`: The byte array that contains the actual content.
    - `[LastModifiedDateTime <DateTime?>]`: The date and time the app was last modified.
    - `[Notes <String>]`: Notes for the app.
    - `[Owner <String>]`: The owner of the app.
    - `[PrivacyInformationUrl <String>]`: The privacy statement Url.
    - `[Publisher <String>]`: The publisher of the app.
    - `[PublishingState <String>]`: Indicates the publishing state of an app.
    - `[Relationships <IMicrosoftGraphMobileAppRelationship[]>]`: List of relationships for this mobile app.
      - `[Id <String>]`: Read-only.
      - `[TargetDisplayName <String>]`: The target mobile app's display name.
      - `[TargetDisplayVersion <String>]`: The target mobile app's display version.
      - `[TargetId <String>]`: The target mobile app's app id.
      - `[TargetPublisher <String>]`: The target mobile app's publisher.
      - `[TargetType <String>]`: Indicates whether the target of a relationship is the parent or the child in the relationship.
    - `[RoleScopeTagIds <String[]>]`: List of scope tag ids for this mobile app.
    - `[SupersededAppCount <Int32?>]`: The total number of apps this app is directly or indirectly superseded by.
    - `[SupersedingAppCount <Int32?>]`: The total number of apps this app directly or indirectly supersedes.
    - `[UploadState <Int32?>]`: The upload state.
    - `[UserStatuses <IMicrosoftGraphUserAppInstallStatus[]>]`: The list of installation states for this mobile app.
  - `[DeviceStatuses <IMicrosoftGraphMobileAppInstallStatus[]>]`: The install state of the app on devices.
  - `[FailedDeviceCount <Int32?>]`: Failed Device Count.
  - `[InstalledDeviceCount <Int32?>]`: Installed Device Count.
  - `[NotInstalledDeviceCount <Int32?>]`: Not installed device count.
  - `[UserName <String>]`: User name.
  - `[UserPrincipalName <String>]`: User Principal Name.

## RELATED LINKS

