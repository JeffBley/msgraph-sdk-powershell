---
external help file:
Module Name: Microsoft.Graph.Reports
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.reports/get-mgreportmanageddeviceenrollmentabandonmentsummary
schema: 2.0.0
---

# Get-MgReportManagedDeviceEnrollmentAbandonmentSummary

## SYNOPSIS
Metadata for Enrollment abandonment summary report

## SYNTAX

### Managed (Default)
```
Get-MgReportManagedDeviceEnrollmentAbandonmentSummary -Filter <String> -Skip <Int32> -SkipToken <String>
 -Top <Int32> -OutFile <String> [-PassThru] [<CommonParameters>]
```

### ManagedViaIdentity
```
Get-MgReportManagedDeviceEnrollmentAbandonmentSummary -InputObject <IReportsIdentity> -OutFile <String>
 [-PassThru] [<CommonParameters>]
```

## DESCRIPTION
Metadata for Enrollment abandonment summary report

## EXAMPLES

## PARAMETERS

### -Filter
Usage: filter={filter}

```yaml
Type: System.String
Parameter Sets: Managed
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
Type: Microsoft.Graph.PowerShell.Models.IReportsIdentity
Parameter Sets: ManagedViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -OutFile
Path to write output file to

```yaml
Type: System.String
Parameter Sets: (All)
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

### -Skip
Usage: skip={skip}

```yaml
Type: System.Int32
Parameter Sets: Managed
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SkipToken
Usage: skipToken={skipToken}

```yaml
Type: System.String
Parameter Sets: Managed
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Top
Usage: top={top}

```yaml
Type: System.Int32
Parameter Sets: Managed
Aliases: Limit

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IReportsIdentity

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


INPUTOBJECT <IReportsIdentity>: Identity Parameter
  - `[ApplicationSignInDetailedSummaryId <String>]`: key: id of applicationSignInDetailedSummary
  - `[CredentialUserRegistrationDetailsId <String>]`: key: id of credentialUserRegistrationDetails
  - `[Date <DateTime?>]`: Usage: date={date}
  - `[DeviceManagementCachedReportConfigurationId <String>]`: key: id of deviceManagementCachedReportConfiguration
  - `[DeviceManagementExportJobId <String>]`: key: id of deviceManagementExportJob
  - `[DirectoryAuditId <String>]`: key: id of directoryAudit
  - `[EndDateTime <DateTime?>]`: Usage: endDateTime={endDateTime}
  - `[Filter <String>]`: Usage: filter={filter}
  - `[GroupId <String>]`: Usage: groupId={groupId}
  - `[IncludedUserRoles <String>]`: Usage: includedUserRoles={includedUserRoles}
  - `[IncludedUserTypes <String>]`: Usage: includedUserTypes={includedUserTypes}
  - `[Period <String>]`: Usage: period={period}
  - `[PrintUsageByPrinterId <String>]`: key: id of printUsageByPrinter
  - `[PrintUsageByUserId <String>]`: key: id of printUsageByUser
  - `[PrinterId <String>]`: Usage: printerId={printerId}
  - `[ProvisioningObjectSummaryId <String>]`: key: id of provisioningObjectSummary
  - `[RestrictedSignInId <String>]`: key: id of restrictedSignIn
  - `[SignInId <String>]`: key: id of signIn
  - `[Skip <Int32?>]`: Usage: skip={skip}
  - `[SkipToken <String>]`: Usage: skipToken={skipToken}
  - `[StartDateTime <DateTime?>]`: Usage: startDateTime={startDateTime}
  - `[Top <Int32?>]`: Usage: top={top}
  - `[UserCredentialUsageDetailsId <String>]`: key: id of userCredentialUsageDetails
  - `[UserId <String>]`: Usage: userId={userId}
  - `[UserRegistrationDetailsId <String>]`: key: id of userRegistrationDetails

## RELATED LINKS

