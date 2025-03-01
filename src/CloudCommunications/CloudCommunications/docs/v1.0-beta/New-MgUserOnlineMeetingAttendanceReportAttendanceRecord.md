---
external help file:
Module Name: Microsoft.Graph.CloudCommunications
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.cloudcommunications/new-mguseronlinemeetingattendancereportattendancerecord
schema: 2.0.0
---

# New-MgUserOnlineMeetingAttendanceReportAttendanceRecord

## SYNOPSIS
List of attendance records of an attendance report.
Read-only.

## SYNTAX

### CreateExpanded1 (Default)
```
New-MgUserOnlineMeetingAttendanceReportAttendanceRecord -OnlineMeetingId <String> -UserId <String>
 [-AdditionalProperties <Hashtable>] [-AttendanceIntervals <IMicrosoftGraphAttendanceInterval[]>]
 [-EmailAddress <String>] [-Id <String>] [-Identity <IMicrosoftGraphIdentity>] [-Role <String>]
 [-TotalAttendanceInSeconds <Int32>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create
```
New-MgUserOnlineMeetingAttendanceReportAttendanceRecord -MeetingAttendanceReportId <String>
 -OnlineMeetingId <String> -UserId <String> -BodyParameter <IMicrosoftGraphAttendanceRecord> [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

### Create1
```
New-MgUserOnlineMeetingAttendanceReportAttendanceRecord -OnlineMeetingId <String> -UserId <String>
 -BodyParameter <IMicrosoftGraphAttendanceRecord> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateExpanded
```
New-MgUserOnlineMeetingAttendanceReportAttendanceRecord -MeetingAttendanceReportId <String>
 -OnlineMeetingId <String> -UserId <String> [-AdditionalProperties <Hashtable>]
 [-AttendanceIntervals <IMicrosoftGraphAttendanceInterval[]>] [-EmailAddress <String>] [-Id <String>]
 [-Identity <IMicrosoftGraphIdentity>] [-Role <String>] [-TotalAttendanceInSeconds <Int32>] [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentity
```
New-MgUserOnlineMeetingAttendanceReportAttendanceRecord -InputObject <ICloudCommunicationsIdentity>
 -BodyParameter <IMicrosoftGraphAttendanceRecord> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentity1
```
New-MgUserOnlineMeetingAttendanceReportAttendanceRecord -InputObject <ICloudCommunicationsIdentity>
 -BodyParameter <IMicrosoftGraphAttendanceRecord> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentityExpanded
```
New-MgUserOnlineMeetingAttendanceReportAttendanceRecord -InputObject <ICloudCommunicationsIdentity>
 [-AdditionalProperties <Hashtable>] [-AttendanceIntervals <IMicrosoftGraphAttendanceInterval[]>]
 [-EmailAddress <String>] [-Id <String>] [-Identity <IMicrosoftGraphIdentity>] [-Role <String>]
 [-TotalAttendanceInSeconds <Int32>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentityExpanded1
```
New-MgUserOnlineMeetingAttendanceReportAttendanceRecord -InputObject <ICloudCommunicationsIdentity>
 [-AdditionalProperties <Hashtable>] [-AttendanceIntervals <IMicrosoftGraphAttendanceInterval[]>]
 [-EmailAddress <String>] [-Id <String>] [-Identity <IMicrosoftGraphIdentity>] [-Role <String>]
 [-TotalAttendanceInSeconds <Int32>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
List of attendance records of an attendance report.
Read-only.

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: System.Collections.Hashtable
Parameter Sets: CreateExpanded, CreateExpanded1, CreateViaIdentityExpanded, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AttendanceIntervals
List of time periods between joining and leaving a meeting.
To construct, please use Get-Help -Online and see NOTES section for ATTENDANCEINTERVALS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAttendanceInterval[]
Parameter Sets: CreateExpanded, CreateExpanded1, CreateViaIdentityExpanded, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
attendanceRecord
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAttendanceRecord
Parameter Sets: Create, Create1, CreateViaIdentity, CreateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -EmailAddress
Email address of the user associated with this atttendance record.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateExpanded1, CreateViaIdentityExpanded, CreateViaIdentityExpanded1
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
Parameter Sets: CreateExpanded, CreateExpanded1, CreateViaIdentityExpanded, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Identity
identity
To construct, please use Get-Help -Online and see NOTES section for IDENTITY properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphIdentity
Parameter Sets: CreateExpanded, CreateExpanded1, CreateViaIdentityExpanded, CreateViaIdentityExpanded1
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
Type: Microsoft.Graph.PowerShell.Models.ICloudCommunicationsIdentity
Parameter Sets: CreateViaIdentity, CreateViaIdentity1, CreateViaIdentityExpanded, CreateViaIdentityExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -MeetingAttendanceReportId
key: id of meetingAttendanceReport

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

### -OnlineMeetingId
key: id of onlineMeeting

```yaml
Type: System.String
Parameter Sets: Create, Create1, CreateExpanded, CreateExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Role
Role of the attendee.
Possible values are: None, Attendee, Presenter, and Organizer.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateExpanded1, CreateViaIdentityExpanded, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TotalAttendanceInSeconds
Total duration of the attendances in seconds.

```yaml
Type: System.Int32
Parameter Sets: CreateExpanded, CreateExpanded1, CreateViaIdentityExpanded, CreateViaIdentityExpanded1
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
Parameter Sets: Create, Create1, CreateExpanded, CreateExpanded1
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

### Microsoft.Graph.PowerShell.Models.ICloudCommunicationsIdentity

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAttendanceRecord

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAttendanceRecord

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


ATTENDANCEINTERVALS <IMicrosoftGraphAttendanceInterval[]>: List of time periods between joining and leaving a meeting.
  - `[DurationInSeconds <Int32?>]`: Duration of the meeting interval in seconds; that is, the difference between joinDateTime and leaveDateTime.
  - `[JoinDateTime <DateTime?>]`: The time the attendee joined in UTC.
  - `[LeaveDateTime <DateTime?>]`: The time the attendee left in UTC.

BODYPARAMETER <IMicrosoftGraphAttendanceRecord>: attendanceRecord
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[AttendanceIntervals <IMicrosoftGraphAttendanceInterval[]>]`: List of time periods between joining and leaving a meeting.
    - `[DurationInSeconds <Int32?>]`: Duration of the meeting interval in seconds; that is, the difference between joinDateTime and leaveDateTime.
    - `[JoinDateTime <DateTime?>]`: The time the attendee joined in UTC.
    - `[LeaveDateTime <DateTime?>]`: The time the attendee left in UTC.
  - `[EmailAddress <String>]`: Email address of the user associated with this atttendance record.
  - `[Identity <IMicrosoftGraphIdentity>]`: identity
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DisplayName <String>]`: The display name of the identity. This property is read-only.
    - `[Id <String>]`: The identifier of the identity. This property is read-only.
  - `[Role <String>]`: Role of the attendee. Possible values are: None, Attendee, Presenter, and Organizer.
  - `[TotalAttendanceInSeconds <Int32?>]`: Total duration of the attendances in seconds.

IDENTITY <IMicrosoftGraphIdentity>: identity
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[DisplayName <String>]`: The display name of the identity. This property is read-only.
  - `[Id <String>]`: The identifier of the identity. This property is read-only.

INPUTOBJECT <ICloudCommunicationsIdentity>: Identity Parameter
  - `[AttendanceRecordId <String>]`: key: id of attendanceRecord
  - `[AudioRoutingGroupId <String>]`: key: id of audioRoutingGroup
  - `[CallId <String>]`: key: id of call
  - `[CallRecordId <String>]`: key: id of callRecord
  - `[CallTranscriptId <String>]`: key: id of callTranscript
  - `[CommsOperationId <String>]`: key: id of commsOperation
  - `[MeetingAttendanceReportId <String>]`: key: id of meetingAttendanceReport
  - `[MeetingRegistrationQuestionId <String>]`: key: id of meetingRegistrationQuestion
  - `[OnlineMeetingId <String>]`: key: id of onlineMeeting
  - `[ParticipantId <String>]`: key: id of participant
  - `[PresenceId <String>]`: key: id of presence
  - `[SessionId <String>]`: key: id of session
  - `[UserId <String>]`: key: id of user

## RELATED LINKS

