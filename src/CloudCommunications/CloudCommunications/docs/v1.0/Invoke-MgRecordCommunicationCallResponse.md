---
external help file:
Module Name: Microsoft.Graph.CloudCommunications
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.cloudcommunications/invoke-mgrecordcommunicationcallresponse
schema: 2.0.0
---

# Invoke-MgRecordCommunicationCallResponse

## SYNOPSIS
Invoke action recordResponse

## SYNTAX

### RecordExpanded (Default)
```
Invoke-MgRecordCommunicationCallResponse -CallId <String> [-AdditionalProperties <Hashtable>]
 [-BargeInAllowed] [-ClientContext <String>] [-InitialSilenceTimeoutInSeconds <Int32>]
 [-MaxRecordDurationInSeconds <Int32>] [-MaxSilenceTimeoutInSeconds <Int32>] [-PlayBeep]
 [-Prompts <IMicrosoftGraphPrompt[]>] [-StopTones <String[]>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Record
```
Invoke-MgRecordCommunicationCallResponse -CallId <String>
 -BodyParameter <IPaths14Wb7KqCommunicationsCallsCallIdMicrosoftGraphRecordresponsePostRequestbodyContentApplicationJsonSchema>
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### RecordViaIdentity
```
Invoke-MgRecordCommunicationCallResponse -InputObject <ICloudCommunicationsIdentity>
 -BodyParameter <IPaths14Wb7KqCommunicationsCallsCallIdMicrosoftGraphRecordresponsePostRequestbodyContentApplicationJsonSchema>
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### RecordViaIdentityExpanded
```
Invoke-MgRecordCommunicationCallResponse -InputObject <ICloudCommunicationsIdentity>
 [-AdditionalProperties <Hashtable>] [-BargeInAllowed] [-ClientContext <String>]
 [-InitialSilenceTimeoutInSeconds <Int32>] [-MaxRecordDurationInSeconds <Int32>]
 [-MaxSilenceTimeoutInSeconds <Int32>] [-PlayBeep] [-Prompts <IMicrosoftGraphPrompt[]>]
 [-StopTones <String[]>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Invoke action recordResponse

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: System.Collections.Hashtable
Parameter Sets: RecordExpanded, RecordViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BargeInAllowed
.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: RecordExpanded, RecordViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
.
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IPaths14Wb7KqCommunicationsCallsCallIdMicrosoftGraphRecordresponsePostRequestbodyContentApplicationJsonSchema
Parameter Sets: Record, RecordViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CallId
key: id of call

```yaml
Type: System.String
Parameter Sets: Record, RecordExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ClientContext
.

```yaml
Type: System.String
Parameter Sets: RecordExpanded, RecordViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InitialSilenceTimeoutInSeconds
.

```yaml
Type: System.Int32
Parameter Sets: RecordExpanded, RecordViaIdentityExpanded
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
Parameter Sets: RecordViaIdentity, RecordViaIdentityExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -MaxRecordDurationInSeconds
.

```yaml
Type: System.Int32
Parameter Sets: RecordExpanded, RecordViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MaxSilenceTimeoutInSeconds
.

```yaml
Type: System.Int32
Parameter Sets: RecordExpanded, RecordViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PlayBeep
.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: RecordExpanded, RecordViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Prompts
.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphPrompt[]
Parameter Sets: RecordExpanded, RecordViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -StopTones
.

```yaml
Type: System.String[]
Parameter Sets: RecordExpanded, RecordViaIdentityExpanded
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

### Microsoft.Graph.PowerShell.Models.ICloudCommunicationsIdentity

### Microsoft.Graph.PowerShell.Models.IPaths14Wb7KqCommunicationsCallsCallIdMicrosoftGraphRecordresponsePostRequestbodyContentApplicationJsonSchema

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphRecordOperation

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IPaths14Wb7KqCommunicationsCallsCallIdMicrosoftGraphRecordresponsePostRequestbodyContentApplicationJsonSchema>: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[BargeInAllowed <Boolean?>]`: 
  - `[ClientContext <String>]`: 
  - `[InitialSilenceTimeoutInSeconds <Int32?>]`: 
  - `[MaxRecordDurationInSeconds <Int32?>]`: 
  - `[MaxSilenceTimeoutInSeconds <Int32?>]`: 
  - `[PlayBeep <Boolean?>]`: 
  - `[Prompts <IMicrosoftGraphPrompt[]>]`: 
  - `[StopTones <String[]>]`: 

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

