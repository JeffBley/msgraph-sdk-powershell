---
external help file:
Module Name: Microsoft.Graph.Reports
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.reports/get-mgreportdailyprintusage
schema: 2.0.0
---

# Get-MgReportDailyPrintUsage

## SYNOPSIS
Get dailyPrintUsageByPrinter from reports

## SYNTAX

### List2 (Default)
```
Get-MgReportDailyPrintUsage [-ExpandProperty <String[]>] [-Filter <String>] [-Property <String[]>]
 [-Search <String>] [-Skip <Int32>] [-Sort <String[]>] [-Top <Int32>] [-All] [-CountVariable <String>]
 [-PageSize <Int32>] [<CommonParameters>]
```

### Get2
```
Get-MgReportDailyPrintUsage -PrintUsageByPrinterId <String> [-ExpandProperty <String[]>]
 [-Property <String[]>] [<CommonParameters>]
```

### Get3
```
Get-MgReportDailyPrintUsage -PrintUsageByUserId <String> [-ExpandProperty <String[]>] [-Property <String[]>]
 [<CommonParameters>]
```

### GetViaIdentity2
```
Get-MgReportDailyPrintUsage -InputObject <IReportsIdentity> [-ExpandProperty <String[]>]
 [-Property <String[]>] [<CommonParameters>]
```

### GetViaIdentity3
```
Get-MgReportDailyPrintUsage -InputObject <IReportsIdentity> [-ExpandProperty <String[]>]
 [-Property <String[]>] [<CommonParameters>]
```

### List3
```
Get-MgReportDailyPrintUsage [-ExpandProperty <String[]>] [-Filter <String>] [-Property <String[]>]
 [-Search <String>] [-Skip <Int32>] [-Sort <String[]>] [-Top <Int32>] [-All] [-CountVariable <String>]
 [-PageSize <Int32>] [<CommonParameters>]
```

## DESCRIPTION
Get dailyPrintUsageByPrinter from reports

## EXAMPLES

## PARAMETERS

### -All
List all pages.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: List2, List3
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CountVariable
Specifies a count of the total number of items in a collection.
By default, this variable will be set in the global scope.

```yaml
Type: System.String
Parameter Sets: List2, List3
Aliases: CV

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExpandProperty
Expand related entities

```yaml
Type: System.String[]
Parameter Sets: (All)
Aliases: Expand

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Filter
Filter items by property values

```yaml
Type: System.String
Parameter Sets: List2, List3
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
Type: Microsoft.Graph.PowerShell.Models.IReportsIdentity
Parameter Sets: GetViaIdentity2, GetViaIdentity3
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -PageSize
Sets the page size of results.

```yaml
Type: System.Int32
Parameter Sets: List2, List3
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PrintUsageByPrinterId
key: id of printUsageByPrinter

```yaml
Type: System.String
Parameter Sets: Get2
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PrintUsageByUserId
key: id of printUsageByUser

```yaml
Type: System.String
Parameter Sets: Get3
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Property
Select properties to be returned

```yaml
Type: System.String[]
Parameter Sets: (All)
Aliases: Select

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Search
Search items by search phrases

```yaml
Type: System.String
Parameter Sets: List2, List3
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Skip
Skip the first n items

```yaml
Type: System.Int32
Parameter Sets: List2, List3
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Sort
Order items by property values

```yaml
Type: System.String[]
Parameter Sets: List2, List3
Aliases: OrderBy

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Top
Show only the first n items

```yaml
Type: System.Int32
Parameter Sets: List2, List3
Aliases: Limit

Required: False
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphPrintUsageByPrinter1

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphPrintUsageByUser1

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

