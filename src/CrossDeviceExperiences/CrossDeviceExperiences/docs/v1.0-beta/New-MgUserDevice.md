---
external help file:
Module Name: Microsoft.Graph.CrossDeviceExperiences
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.crossdeviceexperiences/new-mguserdevice
schema: 2.0.0
---

# New-MgUserDevice

## SYNOPSIS
Create new navigation property to devices for users

## SYNTAX

### CreateExpanded (Default)
```
New-MgUserDevice -UserId <String> [-AccountEnabled] [-AdditionalProperties <Hashtable>]
 [-AlternativeSecurityIds <IMicrosoftGraphAlternativeSecurityId[]>]
 [-ApproximateLastSignInDateTime <DateTime>] [-Commands <IMicrosoftGraphCommand[]>]
 [-ComplianceExpirationDateTime <DateTime>] [-DeletedDateTime <DateTime>] [-DeviceCategory <String>]
 [-DeviceId <String>] [-DeviceMetadata <String>] [-DeviceOwnership <String>] [-DeviceVersion <Int32>]
 [-DisplayName <String>] [-DomainName <String>] [-EnrollmentProfileName <String>] [-EnrollmentType <String>]
 [-ExtensionAttributes <IMicrosoftGraphOnPremisesExtensionAttributes>]
 [-Extensions <IMicrosoftGraphExtension[]>] [-Hostnames <String[]>] [-Id <String>] [-IsCompliant] [-IsManaged]
 [-IsRooted] [-Kind <String>] [-ManagementType <String>] [-Manufacturer <String>] [-MdmAppId <String>]
 [-MemberOf <IMicrosoftGraphDirectoryObject[]>] [-Model <String>] [-Name <String>]
 [-OnPremisesLastSyncDateTime <DateTime>] [-OnPremisesSyncEnabled] [-OperatingSystem <String>]
 [-OperatingSystemVersion <String>] [-PhysicalIds <String[]>] [-Platform <String>] [-ProfileType <String>]
 [-RegisteredOwners <IMicrosoftGraphDirectoryObject[]>] [-RegisteredUsers <IMicrosoftGraphDirectoryObject[]>]
 [-RegistrationDateTime <DateTime>] [-Status <String>] [-SystemLabels <String[]>]
 [-TransitiveMemberOf <IMicrosoftGraphDirectoryObject[]>] [-TrustType <String>]
 [-UsageRights <IMicrosoftGraphUsageRight[]>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create
```
New-MgUserDevice -UserId <String> -BodyParameter <IMicrosoftGraphDevice> [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### CreateViaIdentity
```
New-MgUserDevice -InputObject <ICrossDeviceExperiencesIdentity> -BodyParameter <IMicrosoftGraphDevice>
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentityExpanded
```
New-MgUserDevice -InputObject <ICrossDeviceExperiencesIdentity> [-AccountEnabled]
 [-AdditionalProperties <Hashtable>] [-AlternativeSecurityIds <IMicrosoftGraphAlternativeSecurityId[]>]
 [-ApproximateLastSignInDateTime <DateTime>] [-Commands <IMicrosoftGraphCommand[]>]
 [-ComplianceExpirationDateTime <DateTime>] [-DeletedDateTime <DateTime>] [-DeviceCategory <String>]
 [-DeviceId <String>] [-DeviceMetadata <String>] [-DeviceOwnership <String>] [-DeviceVersion <Int32>]
 [-DisplayName <String>] [-DomainName <String>] [-EnrollmentProfileName <String>] [-EnrollmentType <String>]
 [-ExtensionAttributes <IMicrosoftGraphOnPremisesExtensionAttributes>]
 [-Extensions <IMicrosoftGraphExtension[]>] [-Hostnames <String[]>] [-Id <String>] [-IsCompliant] [-IsManaged]
 [-IsRooted] [-Kind <String>] [-ManagementType <String>] [-Manufacturer <String>] [-MdmAppId <String>]
 [-MemberOf <IMicrosoftGraphDirectoryObject[]>] [-Model <String>] [-Name <String>]
 [-OnPremisesLastSyncDateTime <DateTime>] [-OnPremisesSyncEnabled] [-OperatingSystem <String>]
 [-OperatingSystemVersion <String>] [-PhysicalIds <String[]>] [-Platform <String>] [-ProfileType <String>]
 [-RegisteredOwners <IMicrosoftGraphDirectoryObject[]>] [-RegisteredUsers <IMicrosoftGraphDirectoryObject[]>]
 [-RegistrationDateTime <DateTime>] [-Status <String>] [-SystemLabels <String[]>]
 [-TransitiveMemberOf <IMicrosoftGraphDirectoryObject[]>] [-TrustType <String>]
 [-UsageRights <IMicrosoftGraphUsageRight[]>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to devices for users

## EXAMPLES

## PARAMETERS

### -AccountEnabled
true if the account is enabled; otherwise, false.
Default is true.
Supports $filter (eq, ne, not, in).
Only callers in Global Administrator and Cloud Device Administrator roles can set this property.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
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
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AlternativeSecurityIds
For internal use only.
Not nullable.
Supports $filter (eq, not, ge, le).
To construct, please use Get-Help -Online and see NOTES section for ALTERNATIVESECURITYIDS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAlternativeSecurityId[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ApproximateLastSignInDateTime
The timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
Read-only.
Supports $filter (eq, ne, not, ge, le, and eq on null values) and $orderBy.

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
device
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDevice
Parameter Sets: Create, CreateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Commands
Set of commands sent to this device.
To construct, please use Get-Help -Online and see NOTES section for COMMANDS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphCommand[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ComplianceExpirationDateTime
The timestamp when the device is no longer deemed compliant.
The timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
Read-only.

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
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
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceCategory
User-defined property set by Intune to automatically add devices to groups and simplify managing devices.

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

### -DeviceId
Identifier set by Azure Device Registration Service at the time of registration.
Supports $filter (eq, ne, not, startsWith).

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

### -DeviceMetadata
For internal use only.
Set to null.

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

### -DeviceOwnership
Ownership of the device.
This property is set by Intune.
Possible values are: unknown, company, personal.

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

### -DeviceVersion
For internal use only.

```yaml
Type: System.Int32
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
The display name for the device.
Required.
Supports $filter (eq, ne, not, ge, le, in, startsWith, and eq on null values), $search, and $orderBy.

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

### -DomainName
The on-premises domain name of Hybrid Azure AD joined devices.
This property is set by Intune.

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

### -EnrollmentProfileName
Enrollment profile applied to the device.
For example, Apple Device Enrollment Profile, Device enrollment - Corporate device identifiers, or Windows Autopilot profile name.
This property is set by Intune.

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

### -EnrollmentType
Enrollment type of the device.
This property is set by Intune.
Possible values are: unknown, userEnrollment, deviceEnrollmentManager, appleBulkWithUser, appleBulkWithoutUser, windowsAzureADJoin, windowsBulkUserless, windowsAutoEnrollment, windowsBulkAzureDomainJoin, windowsCoManagement.

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

### -ExtensionAttributes
onPremisesExtensionAttributes
To construct, please use Get-Help -Online and see NOTES section for EXTENSIONATTRIBUTES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphOnPremisesExtensionAttributes
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Extensions
The collection of open extensions defined for the device.
Read-only.
Nullable.
To construct, please use Get-Help -Online and see NOTES section for EXTENSIONS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphExtension[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Hostnames
List of hostNames for the device.

```yaml
Type: System.String[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
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
Type: Microsoft.Graph.PowerShell.Models.ICrossDeviceExperiencesIdentity
Parameter Sets: CreateViaIdentity, CreateViaIdentityExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -IsCompliant
true if the device complies with Mobile Device Management (MDM) policies; otherwise, false.
Read-only.
This can only be updated by Intune for any device OS type or by an approved MDM app for Windows OS devices.
Supports $filter (eq, ne, not).

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsManaged
true if the device is managed by a Mobile Device Management (MDM) app; otherwise, false.
This can only be updated by Intune for any device OS type or by an approved MDM app for Windows OS devices.
Supports $filter (eq, ne, not).

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsRooted
true if device is rooted; false if device is jail-broken.
This can only be updated by Intune.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Kind
Form factor of device.
Only returned if user signs in with a Microsoft account as part of Project Rome.

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

### -ManagementType
Management channel of the device.
This property is set by Intune.
Possible values are: eas, mdm, easMdm, intuneClient, easIntuneClient, configurationManagerClient, configurationManagerClientMdm, configurationManagerClientMdmEas, unknown, jamf, googleCloudDevicePolicyController.

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

### -Manufacturer
Manufacturer of the device.
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

### -MdmAppId
Application identifier used to register device into MDM.
Read-only.
Supports $filter (eq, ne, not, startsWith).

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

### -MemberOf
Groups that this device is a member of.
Read-only.
Nullable.
Supports $expand.
To construct, please use Get-Help -Online and see NOTES section for MEMBEROF properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDirectoryObject[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Model
Model of the device.
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

### -Name
Friendly name of a device.
Only returned if user signs in with a Microsoft account as part of Project Rome.

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

### -OnPremisesLastSyncDateTime
The last time at which the object was synced with the on-premises directory.
The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z Read-only.
Supports $filter (eq, ne, not, ge, le, in).

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OnPremisesSyncEnabled
true if this object is synced from an on-premises directory; false if this object was originally synced from an on-premises directory but is no longer synced; null if this object has never been synced from an on-premises directory (default).
Read-only.
Supports $filter (eq, ne, not, in, and eq on null values).

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OperatingSystem
The type of operating system on the device.
Required.
Supports $filter (eq, ne, not, ge, le, startsWith, and eq on null values).

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

### -OperatingSystemVersion
Operating system version of the device.
Required.
Supports $filter (eq, ne, not, ge, le, startsWith, and eq on null values).

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

### -PhysicalIds
For internal use only.
Not nullable.
Supports $filter (eq, not, ge, le, startsWith).

```yaml
Type: System.String[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Platform
Platform of device.
Only returned if user signs in with a Microsoft account as part of Project Rome.
Only returned if user signs in with a Microsoft account as part of Project Rome.

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

### -ProfileType
The profile type of the device.
Possible values: RegisteredDevice (default), SecureVM, Printer, Shared, IoT.

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

### -RegisteredOwners
The user that cloud joined the device or registered their personal device.
The registered owner is set at the time of registration.
Currently, there can be only one owner.
Read-only.
Nullable.
Supports $expand.
To construct, please use Get-Help -Online and see NOTES section for REGISTEREDOWNERS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDirectoryObject[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RegisteredUsers
Collection of registered users of the device.
For cloud joined devices and registered personal devices, registered users are set to the same value as registered owners at the time of registration.
Read-only.
Nullable.
Supports $expand.
To construct, please use Get-Help -Online and see NOTES section for REGISTEREDUSERS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDirectoryObject[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RegistrationDateTime
Date and time of when the device was registered.
The timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
Read-only.

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Status
Device is online or offline.
Only returned if user signs in with a Microsoft account as part of Project Rome.

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

### -SystemLabels
List of labels applied to the device by the system.

```yaml
Type: System.String[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TransitiveMemberOf
Groups that this device is a member of.
This operation is transitive.
Supports $expand.
To construct, please use Get-Help -Online and see NOTES section for TRANSITIVEMEMBEROF properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDirectoryObject[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TrustType
Type of trust for the joined device.
Read-only.
Possible values: Workplace (indicates bring your own personal devices), AzureAd (Cloud only joined devices), ServerAd (on-premises domain joined devices joined to Azure AD).
For more details, see Introduction to device management in Azure Active Directory

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

### -UsageRights
Represents the usage rights a device has been granted.
To construct, please use Get-Help -Online and see NOTES section for USAGERIGHTS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUsageRight[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
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

### Microsoft.Graph.PowerShell.Models.ICrossDeviceExperiencesIdentity

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDevice

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDevice

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


ALTERNATIVESECURITYIDS <IMicrosoftGraphAlternativeSecurityId[]>: For internal use only. Not nullable. Supports $filter (eq, not, ge, le).
  - `[IdentityProvider <String>]`: For internal use only
  - `[Key <Byte[]>]`: For internal use only
  - `[Type <Int32?>]`: For internal use only

BODYPARAMETER <IMicrosoftGraphDevice>: device
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[DeletedDateTime <DateTime?>]`: 
  - `[Id <String>]`: Read-only.
  - `[AccountEnabled <Boolean?>]`: true if the account is enabled; otherwise, false. Default is true.  Supports $filter (eq, ne, not, in). Only callers in Global Administrator and Cloud Device Administrator roles can set this property.
  - `[AlternativeSecurityIds <IMicrosoftGraphAlternativeSecurityId[]>]`: For internal use only. Not nullable. Supports $filter (eq, not, ge, le).
    - `[IdentityProvider <String>]`: For internal use only
    - `[Key <Byte[]>]`: For internal use only
    - `[Type <Int32?>]`: For internal use only
  - `[ApproximateLastSignInDateTime <DateTime?>]`: The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z. Read-only. Supports $filter (eq, ne, not, ge, le, and eq on null values) and $orderBy.
  - `[Commands <IMicrosoftGraphCommand[]>]`: Set of commands sent to this device.
    - `[Id <String>]`: Read-only.
    - `[AppServiceName <String>]`: 
    - `[Error <String>]`: 
    - `[PackageFamilyName <String>]`: 
    - `[Payload <IMicrosoftGraphPayloadRequest>]`: payloadRequest
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[PermissionTicket <String>]`: 
    - `[PostBackUri <String>]`: 
    - `[Responsepayload <IMicrosoftGraphPayloadResponse>]`: payloadResponse
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
    - `[Status <String>]`: 
    - `[Type <String>]`: 
  - `[ComplianceExpirationDateTime <DateTime?>]`: The timestamp when the device is no longer deemed compliant. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z. Read-only.
  - `[DeviceCategory <String>]`: User-defined property set by Intune to automatically add devices to groups and simplify managing devices.
  - `[DeviceId <String>]`: Identifier set by Azure Device Registration Service at the time of registration. Supports $filter (eq, ne, not, startsWith).
  - `[DeviceMetadata <String>]`: For internal use only. Set to null.
  - `[DeviceOwnership <String>]`: Ownership of the device. This property is set by Intune. Possible values are: unknown, company, personal.
  - `[DeviceVersion <Int32?>]`: For internal use only.
  - `[DisplayName <String>]`: The display name for the device. Required. Supports $filter (eq, ne, not, ge, le, in, startsWith, and eq on null values), $search, and $orderBy.
  - `[DomainName <String>]`: The on-premises domain name of Hybrid Azure AD joined devices. This property is set by Intune.
  - `[EnrollmentProfileName <String>]`: Enrollment profile applied to the device. For example, Apple Device Enrollment Profile, Device enrollment - Corporate device identifiers, or Windows Autopilot profile name. This property is set by Intune.
  - `[EnrollmentType <String>]`: Enrollment type of the device. This property is set by Intune. Possible values are: unknown, userEnrollment, deviceEnrollmentManager, appleBulkWithUser, appleBulkWithoutUser, windowsAzureADJoin, windowsBulkUserless, windowsAutoEnrollment, windowsBulkAzureDomainJoin, windowsCoManagement.
  - `[ExtensionAttributes <IMicrosoftGraphOnPremisesExtensionAttributes>]`: onPremisesExtensionAttributes
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[ExtensionAttribute1 <String>]`: First customizable extension attribute.
    - `[ExtensionAttribute10 <String>]`: Tenth customizable extension attribute.
    - `[ExtensionAttribute11 <String>]`: Eleventh customizable extension attribute.
    - `[ExtensionAttribute12 <String>]`: Twelfth customizable extension attribute.
    - `[ExtensionAttribute13 <String>]`: Thirteenth customizable extension attribute.
    - `[ExtensionAttribute14 <String>]`: Fourteenth customizable extension attribute.
    - `[ExtensionAttribute15 <String>]`: Fifteenth customizable extension attribute.
    - `[ExtensionAttribute2 <String>]`: Second customizable extension attribute.
    - `[ExtensionAttribute3 <String>]`: Third customizable extension attribute.
    - `[ExtensionAttribute4 <String>]`: Fourth customizable extension attribute.
    - `[ExtensionAttribute5 <String>]`: Fifth customizable extension attribute.
    - `[ExtensionAttribute6 <String>]`: Sixth customizable extension attribute.
    - `[ExtensionAttribute7 <String>]`: Seventh customizable extension attribute.
    - `[ExtensionAttribute8 <String>]`: Eighth customizable extension attribute.
    - `[ExtensionAttribute9 <String>]`: Ninth customizable extension attribute.
  - `[Extensions <IMicrosoftGraphExtension[]>]`: The collection of open extensions defined for the device. Read-only. Nullable.
    - `[Id <String>]`: Read-only.
  - `[Hostnames <String[]>]`: List of hostNames for the device.
  - `[IsCompliant <Boolean?>]`: true if the device complies with Mobile Device Management (MDM) policies; otherwise, false. Read-only. This can only be updated by Intune for any device OS type or by an approved MDM app for Windows OS devices. Supports $filter (eq, ne, not).
  - `[IsManaged <Boolean?>]`: true if the device is managed by a Mobile Device Management (MDM) app; otherwise, false. This can only be updated by Intune for any device OS type or by an approved MDM app for Windows OS devices. Supports $filter (eq, ne, not).
  - `[IsRooted <Boolean?>]`: true if device is rooted; false if device is jail-broken. This can only be updated by Intune.
  - `[Kind <String>]`: Form factor of device. Only returned if user signs in with a Microsoft account as part of Project Rome.
  - `[ManagementType <String>]`: Management channel of the device.  This property is set by Intune. Possible values are: eas, mdm, easMdm, intuneClient, easIntuneClient, configurationManagerClient, configurationManagerClientMdm, configurationManagerClientMdmEas, unknown, jamf, googleCloudDevicePolicyController.
  - `[Manufacturer <String>]`: Manufacturer of the device. Read-only.
  - `[MdmAppId <String>]`: Application identifier used to register device into MDM. Read-only. Supports $filter (eq, ne, not, startsWith).
  - `[MemberOf <IMicrosoftGraphDirectoryObject[]>]`: Groups that this device is a member of. Read-only. Nullable. Supports $expand.
    - `[Id <String>]`: Read-only.
    - `[DeletedDateTime <DateTime?>]`: 
  - `[Model <String>]`: Model of the device. Read-only.
  - `[Name <String>]`: Friendly name of a device. Only returned if user signs in with a Microsoft account as part of Project Rome.
  - `[OnPremisesLastSyncDateTime <DateTime?>]`: The last time at which the object was synced with the on-premises directory. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z Read-only. Supports $filter (eq, ne, not, ge, le, in).
  - `[OnPremisesSyncEnabled <Boolean?>]`: true if this object is synced from an on-premises directory; false if this object was originally synced from an on-premises directory but is no longer synced; null if this object has never been synced from an on-premises directory (default). Read-only. Supports $filter (eq, ne, not, in, and eq on null values).
  - `[OperatingSystem <String>]`: The type of operating system on the device. Required. Supports $filter (eq, ne, not, ge, le, startsWith, and eq on null values).
  - `[OperatingSystemVersion <String>]`: Operating system version of the device. Required. Supports $filter (eq, ne, not, ge, le, startsWith, and eq on null values).
  - `[PhysicalIds <String[]>]`: For internal use only. Not nullable. Supports $filter (eq, not, ge, le, startsWith).
  - `[Platform <String>]`: Platform of device. Only returned if user signs in with a Microsoft account as part of Project Rome. Only returned if user signs in with a Microsoft account as part of Project Rome.
  - `[ProfileType <String>]`: The profile type of the device. Possible values: RegisteredDevice (default), SecureVM, Printer, Shared, IoT.
  - `[RegisteredOwners <IMicrosoftGraphDirectoryObject[]>]`: The user that cloud joined the device or registered their personal device. The registered owner is set at the time of registration. Currently, there can be only one owner. Read-only. Nullable. Supports $expand.
  - `[RegisteredUsers <IMicrosoftGraphDirectoryObject[]>]`: Collection of registered users of the device. For cloud joined devices and registered personal devices, registered users are set to the same value as registered owners at the time of registration. Read-only. Nullable. Supports $expand.
  - `[RegistrationDateTime <DateTime?>]`: Date and time of when the device was registered. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z. Read-only.
  - `[Status <String>]`: Device is online or offline. Only returned if user signs in with a Microsoft account as part of Project Rome.
  - `[SystemLabels <String[]>]`: List of labels applied to the device by the system.
  - `[TransitiveMemberOf <IMicrosoftGraphDirectoryObject[]>]`: Groups that this device is a member of. This operation is transitive. Supports $expand.
  - `[TrustType <String>]`: Type of trust for the joined device. Read-only. Possible values: Workplace (indicates bring your own personal devices), AzureAd (Cloud only joined devices), ServerAd (on-premises domain joined devices joined to Azure AD). For more details, see Introduction to device management in Azure Active Directory
  - `[UsageRights <IMicrosoftGraphUsageRight[]>]`: Represents the usage rights a device has been granted.
    - `[Id <String>]`: Read-only.
    - `[CatalogId <String>]`: Product id corresponding to the usage right.
    - `[ServiceIdentifier <String>]`: Identifier of the service corresponding to the usage right.
    - `[State <String>]`: usageRightState

COMMANDS <IMicrosoftGraphCommand[]>: Set of commands sent to this device.
  - `[Id <String>]`: Read-only.
  - `[AppServiceName <String>]`: 
  - `[Error <String>]`: 
  - `[PackageFamilyName <String>]`: 
  - `[Payload <IMicrosoftGraphPayloadRequest>]`: payloadRequest
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[PermissionTicket <String>]`: 
  - `[PostBackUri <String>]`: 
  - `[Responsepayload <IMicrosoftGraphPayloadResponse>]`: payloadResponse
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
  - `[Status <String>]`: 
  - `[Type <String>]`: 

EXTENSIONATTRIBUTES <IMicrosoftGraphOnPremisesExtensionAttributes>: onPremisesExtensionAttributes
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[ExtensionAttribute1 <String>]`: First customizable extension attribute.
  - `[ExtensionAttribute10 <String>]`: Tenth customizable extension attribute.
  - `[ExtensionAttribute11 <String>]`: Eleventh customizable extension attribute.
  - `[ExtensionAttribute12 <String>]`: Twelfth customizable extension attribute.
  - `[ExtensionAttribute13 <String>]`: Thirteenth customizable extension attribute.
  - `[ExtensionAttribute14 <String>]`: Fourteenth customizable extension attribute.
  - `[ExtensionAttribute15 <String>]`: Fifteenth customizable extension attribute.
  - `[ExtensionAttribute2 <String>]`: Second customizable extension attribute.
  - `[ExtensionAttribute3 <String>]`: Third customizable extension attribute.
  - `[ExtensionAttribute4 <String>]`: Fourth customizable extension attribute.
  - `[ExtensionAttribute5 <String>]`: Fifth customizable extension attribute.
  - `[ExtensionAttribute6 <String>]`: Sixth customizable extension attribute.
  - `[ExtensionAttribute7 <String>]`: Seventh customizable extension attribute.
  - `[ExtensionAttribute8 <String>]`: Eighth customizable extension attribute.
  - `[ExtensionAttribute9 <String>]`: Ninth customizable extension attribute.

EXTENSIONS <IMicrosoftGraphExtension[]>: The collection of open extensions defined for the device. Read-only. Nullable.
  - `[Id <String>]`: Read-only.

INPUTOBJECT <ICrossDeviceExperiencesIdentity>: Identity Parameter
  - `[ActivityHistoryItemId <String>]`: key: id of activityHistoryItem
  - `[DeviceId <String>]`: key: id of device
  - `[UserActivityId <String>]`: key: id of userActivity
  - `[UserId <String>]`: key: id of user

MEMBEROF <IMicrosoftGraphDirectoryObject[]>: Groups that this device is a member of. Read-only. Nullable. Supports $expand.
  - `[Id <String>]`: Read-only.
  - `[DeletedDateTime <DateTime?>]`: 

REGISTEREDOWNERS <IMicrosoftGraphDirectoryObject[]>: The user that cloud joined the device or registered their personal device. The registered owner is set at the time of registration. Currently, there can be only one owner. Read-only. Nullable. Supports $expand.
  - `[Id <String>]`: Read-only.
  - `[DeletedDateTime <DateTime?>]`: 

REGISTEREDUSERS <IMicrosoftGraphDirectoryObject[]>: Collection of registered users of the device. For cloud joined devices and registered personal devices, registered users are set to the same value as registered owners at the time of registration. Read-only. Nullable. Supports $expand.
  - `[Id <String>]`: Read-only.
  - `[DeletedDateTime <DateTime?>]`: 

TRANSITIVEMEMBEROF <IMicrosoftGraphDirectoryObject[]>: Groups that this device is a member of. This operation is transitive. Supports $expand.
  - `[Id <String>]`: Read-only.
  - `[DeletedDateTime <DateTime?>]`: 

USAGERIGHTS <IMicrosoftGraphUsageRight[]>: Represents the usage rights a device has been granted.
  - `[Id <String>]`: Read-only.
  - `[CatalogId <String>]`: Product id corresponding to the usage right.
  - `[ServiceIdentifier <String>]`: Identifier of the service corresponding to the usage right.
  - `[State <String>]`: usageRightState

## RELATED LINKS

