---
external help file:
Module Name: Microsoft.Graph.CloudCommunications
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.cloudcommunications/invoke-mgcreateorgetcommunicationonlinemeeting
schema: 2.0.0
---

# Invoke-MgCreateOrGetCommunicationOnlineMeeting

## SYNOPSIS
Create new navigation property to onlineMeetings for communications

## SYNTAX

### CreateExpanded2 (Default)
```
Invoke-MgCreateOrGetCommunicationOnlineMeeting [-AccessLevel <String>] [-AdditionalProperties <Hashtable>]
 [-AllowAttendeeToEnableCamera] [-AllowAttendeeToEnableMic] [-AllowedPresenters <String>]
 [-AllowMeetingChat <String>] [-AllowTeamworkReactions] [-AlternativeRecordingInputFile <String>]
 [-AttendanceReports <IMicrosoftGraphMeetingAttendanceReport[]>] [-AttendeeReportInputFile <String>]
 [-AudioConferencing <IMicrosoftGraphAudioConferencing>]
 [-BroadcastSettings <IMicrosoftGraphBroadcastMeetingSettings1>] [-CanceledDateTime <DateTime>]
 [-Capabilities <String[]>] [-ChatInfo <IMicrosoftGraphChatInfo>] [-CreationDateTime <DateTime>]
 [-EndDateTime <DateTime>] [-EntryExitAnnouncement] [-ExpirationDateTime <DateTime>] [-ExternalId <String>]
 [-Id <String>] [-IsBroadcast] [-IsCancelled] [-IsEntryExitAnnounced]
 [-JoinInformation <IMicrosoftGraphItemBody>] [-JoinUrl <String>]
 [-LobbyBypassSettings <IMicrosoftGraphLobbyBypassSettings>]
 [-MeetingAttendanceReport <IMicrosoftGraphMeetingAttendanceReport>]
 [-Participants <IMicrosoftGraphMeetingParticipants1>] [-RecordAutomatically] [-RecordingInputFile <String>]
 [-Registration <IMicrosoftGraphMeetingRegistration>] [-StartDateTime <DateTime>] [-Subject <String>]
 [-Transcripts <IMicrosoftGraphCallTranscript[]>] [-VideoTeleconferenceId <String>] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### Create2
```
Invoke-MgCreateOrGetCommunicationOnlineMeeting -BodyParameter <IMicrosoftGraphOnlineMeeting1> [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to onlineMeetings for communications

## EXAMPLES

## PARAMETERS

### -AccessLevel
accessLevel

```yaml
Type: System.String
Parameter Sets: CreateExpanded2
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
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AllowAttendeeToEnableCamera
Indicates whether attendees can turn on their camera.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AllowAttendeeToEnableMic
Indicates whether attendees can turn on their microphone.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AllowedPresenters
onlineMeetingPresenters

```yaml
Type: System.String
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AllowMeetingChat
meetingChatMode

```yaml
Type: System.String
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AllowTeamworkReactions
Indicates if Teams reactions are enabled for the meeting.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AlternativeRecordingInputFile
Input File for AlternativeRecording (The content stream of the alternative recording of a Microsoft Teams live event.
Read-only.)

```yaml
Type: System.String
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AttendanceReports
The attendance reports of an online meeting.
Read-only.
To construct, please use Get-Help -Online and see NOTES section for ATTENDANCEREPORTS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMeetingAttendanceReport[]
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AttendeeReportInputFile
Input File for AttendeeReport (The content stream of the attendee report of a Teams live event.
Read-only.)

```yaml
Type: System.String
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AudioConferencing
audioConferencing
To construct, please use Get-Help -Online and see NOTES section for AUDIOCONFERENCING properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAudioConferencing
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
onlineMeeting
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphOnlineMeeting1
Parameter Sets: Create2
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -BroadcastSettings
broadcastMeetingSettings
To construct, please use Get-Help -Online and see NOTES section for BROADCASTSETTINGS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphBroadcastMeetingSettings1
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CanceledDateTime
.

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Capabilities
.

```yaml
Type: System.String[]
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ChatInfo
chatInfo
To construct, please use Get-Help -Online and see NOTES section for CHATINFO properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphChatInfo
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CreationDateTime
The meeting creation time in UTC.
Read-only.

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EndDateTime
The meeting end time in UTC.

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EntryExitAnnouncement
.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExpirationDateTime
.

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExternalId
The external ID.
A custom ID.
Optional.

```yaml
Type: System.String
Parameter Sets: CreateExpanded2
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
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsBroadcast
Indicates whether this is a Teams live event.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsCancelled
.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsEntryExitAnnounced
Indicates whether to announce when callers join or leave.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -JoinInformation
itemBody
To construct, please use Get-Help -Online and see NOTES section for JOININFORMATION properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphItemBody
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -JoinUrl
.

```yaml
Type: System.String
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LobbyBypassSettings
lobbyBypassSettings
To construct, please use Get-Help -Online and see NOTES section for LOBBYBYPASSSETTINGS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphLobbyBypassSettings
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MeetingAttendanceReport
meetingAttendanceReport
To construct, please use Get-Help -Online and see NOTES section for MEETINGATTENDANCEREPORT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMeetingAttendanceReport
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Participants
meetingParticipants
To construct, please use Get-Help -Online and see NOTES section for PARTICIPANTS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMeetingParticipants1
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RecordAutomatically
Indicates whether to record the meeting automatically.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RecordingInputFile
Input File for Recording (The content stream of the recording of a Teams live event.
Read-only.)

```yaml
Type: System.String
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Registration
meetingRegistration
To construct, please use Get-Help -Online and see NOTES section for REGISTRATION properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMeetingRegistration
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -StartDateTime
The meeting start time in UTC.

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Subject
The subject of the online meeting.

```yaml
Type: System.String
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Transcripts
.
To construct, please use Get-Help -Online and see NOTES section for TRANSCRIPTS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphCallTranscript[]
Parameter Sets: CreateExpanded2
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -VideoTeleconferenceId
The video teleconferencing ID.
Read-only.

```yaml
Type: System.String
Parameter Sets: CreateExpanded2
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphOnlineMeeting1

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphOnlineMeeting1

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


ATTENDANCEREPORTS <IMicrosoftGraphMeetingAttendanceReport[]>: The attendance reports of an online meeting. Read-only.
  - `[Id <String>]`: Read-only.
  - `[AttendanceRecords <IMicrosoftGraphAttendanceRecord[]>]`: List of attendance records of an attendance report. Read-only.
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
  - `[MeetingEndDateTime <DateTime?>]`: UTC time when the meeting ended. Read-only.
  - `[MeetingStartDateTime <DateTime?>]`: UTC time when the meeting started. Read-only.
  - `[TotalParticipantCount <Int32?>]`: Total number of participants. Read-only.

AUDIOCONFERENCING <IMicrosoftGraphAudioConferencing>: audioConferencing
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[ConferenceId <String>]`: The conference id of the online meeting.
  - `[DialinUrl <String>]`: A URL to the externally-accessible web page that contains dial-in information.
  - `[TollFreeNumber <String>]`: 
  - `[TollFreeNumbers <String[]>]`: List of toll-free numbers that are displayed in the meeting invite.
  - `[TollNumber <String>]`: 
  - `[TollNumbers <String[]>]`: List of toll numbers that are displayed in the meeting invite.

BODYPARAMETER <IMicrosoftGraphOnlineMeeting1>: onlineMeeting
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[AccessLevel <String>]`: accessLevel
  - `[AllowAttendeeToEnableCamera <Boolean?>]`: Indicates whether attendees can turn on their camera.
  - `[AllowAttendeeToEnableMic <Boolean?>]`: Indicates whether attendees can turn on their microphone.
  - `[AllowMeetingChat <String>]`: meetingChatMode
  - `[AllowTeamworkReactions <Boolean?>]`: Indicates if Teams reactions are enabled for the meeting.
  - `[AllowedPresenters <String>]`: onlineMeetingPresenters
  - `[AlternativeRecording <Byte[]>]`: The content stream of the alternative recording of a Microsoft Teams live event. Read-only.
  - `[AttendanceReports <IMicrosoftGraphMeetingAttendanceReport[]>]`: The attendance reports of an online meeting. Read-only.
    - `[Id <String>]`: Read-only.
    - `[AttendanceRecords <IMicrosoftGraphAttendanceRecord[]>]`: List of attendance records of an attendance report. Read-only.
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
    - `[MeetingEndDateTime <DateTime?>]`: UTC time when the meeting ended. Read-only.
    - `[MeetingStartDateTime <DateTime?>]`: UTC time when the meeting started. Read-only.
    - `[TotalParticipantCount <Int32?>]`: Total number of participants. Read-only.
  - `[AttendeeReport <Byte[]>]`: The content stream of the attendee report of a Teams live event. Read-only.
  - `[AudioConferencing <IMicrosoftGraphAudioConferencing>]`: audioConferencing
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[ConferenceId <String>]`: The conference id of the online meeting.
    - `[DialinUrl <String>]`: A URL to the externally-accessible web page that contains dial-in information.
    - `[TollFreeNumber <String>]`: 
    - `[TollFreeNumbers <String[]>]`: List of toll-free numbers that are displayed in the meeting invite.
    - `[TollNumber <String>]`: 
    - `[TollNumbers <String[]>]`: List of toll numbers that are displayed in the meeting invite.
  - `[BroadcastSettings <IMicrosoftGraphBroadcastMeetingSettings1>]`: broadcastMeetingSettings
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[AllowedAudience <String>]`: broadcastMeetingAudience
    - `[Captions <IMicrosoftGraphBroadcastMeetingCaptionSettings>]`: broadcastMeetingCaptionSettings
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[IsCaptionEnabled <Boolean?>]`: Indicates whether caption is enabled for this Teams live event.
      - `[SpokenLanguage <String>]`: The spoken language.
      - `[TranslationLanguages <String[]>]`: The translation languages (choose up to 6).
    - `[IsAttendeeReportEnabled <Boolean?>]`: Indicates whether attendee report is enabled for this Teams live event. Default value is false.
    - `[IsQuestionAndAnswerEnabled <Boolean?>]`: Indicates whether Q&A is enabled for this Teams live event. Default value is false.
    - `[IsRecordingEnabled <Boolean?>]`: Indicates whether recording is enabled for this Teams live event. Default value is false.
    - `[IsVideoOnDemandEnabled <Boolean?>]`: Indicates whether video on demand is enabled for this Teams live event. Default value is false.
  - `[CanceledDateTime <DateTime?>]`: 
  - `[Capabilities <String[]>]`: 
  - `[ChatInfo <IMicrosoftGraphChatInfo>]`: chatInfo
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[MessageId <String>]`: The unique identifier for a message in a Microsoft Teams channel.
    - `[ReplyChainMessageId <String>]`: The ID of the reply message.
    - `[ThreadId <String>]`: The unique identifier for a thread in Microsoft Teams.
  - `[CreationDateTime <DateTime?>]`: The meeting creation time in UTC. Read-only.
  - `[EndDateTime <DateTime?>]`: The meeting end time in UTC.
  - `[EntryExitAnnouncement <Boolean?>]`: 
  - `[ExpirationDateTime <DateTime?>]`: 
  - `[ExternalId <String>]`: The external ID. A custom ID. Optional.
  - `[IsBroadcast <Boolean?>]`: Indicates whether this is a Teams live event.
  - `[IsCancelled <Boolean?>]`: 
  - `[IsEntryExitAnnounced <Boolean?>]`: Indicates whether to announce when callers join or leave.
  - `[JoinInformation <IMicrosoftGraphItemBody>]`: itemBody
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Content <String>]`: The content of the item.
    - `[ContentType <String>]`: bodyType
  - `[JoinUrl <String>]`: 
  - `[LobbyBypassSettings <IMicrosoftGraphLobbyBypassSettings>]`: lobbyBypassSettings
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[IsDialInBypassEnabled <Boolean?>]`: Specifies whether or not to always let dial-in callers bypass the lobby. Optional.
    - `[Scope <String>]`: lobbyBypassScope
  - `[MeetingAttendanceReport <IMicrosoftGraphMeetingAttendanceReport>]`: meetingAttendanceReport
  - `[Participants <IMicrosoftGraphMeetingParticipants1>]`: meetingParticipants
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Attendees <IMicrosoftGraphMeetingParticipantInfo[]>]`: Information of the meeting attendees.
      - `[Identity <IMicrosoftGraphIdentitySet>]`: identitySet
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Application <IMicrosoftGraphIdentity>]`: identity
        - `[Device <IMicrosoftGraphIdentity>]`: identity
        - `[User <IMicrosoftGraphIdentity>]`: identity
      - `[Role <String>]`: onlineMeetingRole
      - `[Upn <String>]`: User principal name of the participant.
    - `[Contributors <IMicrosoftGraphMeetingParticipantInfo[]>]`: 
    - `[Organizer <IMicrosoftGraphMeetingParticipantInfo>]`: meetingParticipantInfo
    - `[Producers <IMicrosoftGraphMeetingParticipantInfo[]>]`: 
  - `[RecordAutomatically <Boolean?>]`: Indicates whether to record the meeting automatically.
  - `[Recording <Byte[]>]`: The content stream of the recording of a Teams live event. Read-only.
  - `[Registration <IMicrosoftGraphMeetingRegistration>]`: meetingRegistration
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[AllowedRegistrant <String>]`: meetingAudience
    - `[Registrants <IMicrosoftGraphMeetingRegistrantBase[]>]`: Registrants of the online meeting.
      - `[Id <String>]`: Read-only.
      - `[JoinWebUrl <String>]`: A unique web URL for the registrant to join the meeting. Read-only.
    - `[Id <String>]`: Read-only.
    - `[CustomQuestions <IMicrosoftGraphMeetingRegistrationQuestion[]>]`: Custom registration questions.
      - `[Id <String>]`: Read-only.
      - `[AnswerInputType <String>]`: answerInputType
      - `[AnswerOptions <String[]>]`: Answer options when answerInputType is radioButton.
      - `[DisplayName <String>]`: Display name of the custom registration question.
      - `[IsRequired <Boolean?>]`: Indicates whether the question is required. Default value is false.
    - `[Description <String>]`: The description of the meeting.
    - `[EndDateTime <DateTime?>]`: The meeting end time in UTC.
    - `[RegistrationPageViewCount <Int32?>]`: The number of times the registration page has been visited. Read-only.
    - `[RegistrationPageWebUrl <String>]`: The URL of the registration page. Read-only.
    - `[Speakers <IMicrosoftGraphMeetingSpeaker[]>]`: The meeting speaker's information.
      - `[Bio <String>]`: Bio of the speaker.
      - `[DisplayName <String>]`: Display name of the speaker.
    - `[StartDateTime <DateTime?>]`: The meeting start time in UTC.
    - `[Subject <String>]`: The subject of the meeting.
  - `[StartDateTime <DateTime?>]`: The meeting start time in UTC.
  - `[Subject <String>]`: The subject of the online meeting.
  - `[Transcripts <IMicrosoftGraphCallTranscript[]>]`: 
    - `[Id <String>]`: Read-only.
    - `[Content <Byte[]>]`: 
    - `[CreatedDateTime <DateTime?>]`: 
  - `[VideoTeleconferenceId <String>]`: The video teleconferencing ID. Read-only.

BROADCASTSETTINGS <IMicrosoftGraphBroadcastMeetingSettings1>: broadcastMeetingSettings
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[AllowedAudience <String>]`: broadcastMeetingAudience
  - `[Captions <IMicrosoftGraphBroadcastMeetingCaptionSettings>]`: broadcastMeetingCaptionSettings
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[IsCaptionEnabled <Boolean?>]`: Indicates whether caption is enabled for this Teams live event.
    - `[SpokenLanguage <String>]`: The spoken language.
    - `[TranslationLanguages <String[]>]`: The translation languages (choose up to 6).
  - `[IsAttendeeReportEnabled <Boolean?>]`: Indicates whether attendee report is enabled for this Teams live event. Default value is false.
  - `[IsQuestionAndAnswerEnabled <Boolean?>]`: Indicates whether Q&A is enabled for this Teams live event. Default value is false.
  - `[IsRecordingEnabled <Boolean?>]`: Indicates whether recording is enabled for this Teams live event. Default value is false.
  - `[IsVideoOnDemandEnabled <Boolean?>]`: Indicates whether video on demand is enabled for this Teams live event. Default value is false.

CHATINFO <IMicrosoftGraphChatInfo>: chatInfo
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[MessageId <String>]`: The unique identifier for a message in a Microsoft Teams channel.
  - `[ReplyChainMessageId <String>]`: The ID of the reply message.
  - `[ThreadId <String>]`: The unique identifier for a thread in Microsoft Teams.

JOININFORMATION <IMicrosoftGraphItemBody>: itemBody
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Content <String>]`: The content of the item.
  - `[ContentType <String>]`: bodyType

LOBBYBYPASSSETTINGS <IMicrosoftGraphLobbyBypassSettings>: lobbyBypassSettings
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[IsDialInBypassEnabled <Boolean?>]`: Specifies whether or not to always let dial-in callers bypass the lobby. Optional.
  - `[Scope <String>]`: lobbyBypassScope

MEETINGATTENDANCEREPORT <IMicrosoftGraphMeetingAttendanceReport>: meetingAttendanceReport
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[AttendanceRecords <IMicrosoftGraphAttendanceRecord[]>]`: List of attendance records of an attendance report. Read-only.
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
  - `[MeetingEndDateTime <DateTime?>]`: UTC time when the meeting ended. Read-only.
  - `[MeetingStartDateTime <DateTime?>]`: UTC time when the meeting started. Read-only.
  - `[TotalParticipantCount <Int32?>]`: Total number of participants. Read-only.

PARTICIPANTS <IMicrosoftGraphMeetingParticipants1>: meetingParticipants
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Attendees <IMicrosoftGraphMeetingParticipantInfo[]>]`: Information of the meeting attendees.
    - `[Identity <IMicrosoftGraphIdentitySet>]`: identitySet
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Application <IMicrosoftGraphIdentity>]`: identity
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[DisplayName <String>]`: The display name of the identity. This property is read-only.
        - `[Id <String>]`: The identifier of the identity. This property is read-only.
      - `[Device <IMicrosoftGraphIdentity>]`: identity
      - `[User <IMicrosoftGraphIdentity>]`: identity
    - `[Role <String>]`: onlineMeetingRole
    - `[Upn <String>]`: User principal name of the participant.
  - `[Contributors <IMicrosoftGraphMeetingParticipantInfo[]>]`: 
  - `[Organizer <IMicrosoftGraphMeetingParticipantInfo>]`: meetingParticipantInfo
  - `[Producers <IMicrosoftGraphMeetingParticipantInfo[]>]`: 

REGISTRATION <IMicrosoftGraphMeetingRegistration>: meetingRegistration
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[AllowedRegistrant <String>]`: meetingAudience
  - `[Registrants <IMicrosoftGraphMeetingRegistrantBase[]>]`: Registrants of the online meeting.
    - `[Id <String>]`: Read-only.
    - `[JoinWebUrl <String>]`: A unique web URL for the registrant to join the meeting. Read-only.
  - `[Id <String>]`: Read-only.
  - `[CustomQuestions <IMicrosoftGraphMeetingRegistrationQuestion[]>]`: Custom registration questions.
    - `[Id <String>]`: Read-only.
    - `[AnswerInputType <String>]`: answerInputType
    - `[AnswerOptions <String[]>]`: Answer options when answerInputType is radioButton.
    - `[DisplayName <String>]`: Display name of the custom registration question.
    - `[IsRequired <Boolean?>]`: Indicates whether the question is required. Default value is false.
  - `[Description <String>]`: The description of the meeting.
  - `[EndDateTime <DateTime?>]`: The meeting end time in UTC.
  - `[RegistrationPageViewCount <Int32?>]`: The number of times the registration page has been visited. Read-only.
  - `[RegistrationPageWebUrl <String>]`: The URL of the registration page. Read-only.
  - `[Speakers <IMicrosoftGraphMeetingSpeaker[]>]`: The meeting speaker's information.
    - `[Bio <String>]`: Bio of the speaker.
    - `[DisplayName <String>]`: Display name of the speaker.
  - `[StartDateTime <DateTime?>]`: The meeting start time in UTC.
  - `[Subject <String>]`: The subject of the meeting.

TRANSCRIPTS <IMicrosoftGraphCallTranscript[]>: .
  - `[Id <String>]`: Read-only.
  - `[Content <Byte[]>]`: 
  - `[CreatedDateTime <DateTime?>]`: 

## RELATED LINKS

