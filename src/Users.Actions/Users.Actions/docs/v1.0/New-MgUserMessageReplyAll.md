---
external help file:
Module Name: Microsoft.Graph.Users.Actions
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.users.actions/new-mgusermessagereplyall
schema: 2.0.0
---

# New-MgUserMessageReplyAll

## SYNOPSIS
Invoke action createReplyAll

## SYNTAX

### CreateExpanded1 (Default)
```
New-MgUserMessageReplyAll -MessageId <String> -UserId <String> [-AdditionalProperties <Hashtable>]
 [-Comment <String>] [-Message <IMicrosoftGraphMessage1>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create1
```
New-MgUserMessageReplyAll -MessageId <String> -UserId <String>
 -BodyParameter <IPaths140I0IcUsersUserIdMessagesMessageIdMicrosoftGraphCreatereplyallPostRequestbodyContentApplicationJsonSchema1>
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentity1
```
New-MgUserMessageReplyAll -InputObject <IUsersActionsIdentity>
 -BodyParameter <IPaths140I0IcUsersUserIdMessagesMessageIdMicrosoftGraphCreatereplyallPostRequestbodyContentApplicationJsonSchema1>
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentityExpanded1
```
New-MgUserMessageReplyAll -InputObject <IUsersActionsIdentity> [-AdditionalProperties <Hashtable>]
 [-Comment <String>] [-Message <IMicrosoftGraphMessage1>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Invoke action createReplyAll

## EXAMPLES

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

### -BodyParameter
.
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IPaths140I0IcUsersUserIdMessagesMessageIdMicrosoftGraphCreatereplyallPostRequestbodyContentApplicationJsonSchema1
Parameter Sets: Create1, CreateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Comment
.

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
Type: Microsoft.Graph.PowerShell.Models.IUsersActionsIdentity
Parameter Sets: CreateViaIdentity1, CreateViaIdentityExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Message
message
To construct, please use Get-Help -Online and see NOTES section for MESSAGE properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMessage1
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MessageId
key: id of message

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

### -UserId
key: id of user

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

### Microsoft.Graph.PowerShell.Models.IPaths140I0IcUsersUserIdMessagesMessageIdMicrosoftGraphCreatereplyallPostRequestbodyContentApplicationJsonSchema1

### Microsoft.Graph.PowerShell.Models.IUsersActionsIdentity

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMessage1

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IPaths140I0IcUsersUserIdMessagesMessageIdMicrosoftGraphCreatereplyallPostRequestbodyContentApplicationJsonSchema1>: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Comment <String>]`: 
  - `[Message <IMicrosoftGraphMessage1>]`: message
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Categories <String[]>]`: The categories associated with the item
    - `[ChangeKey <String>]`: Identifies the version of the item. Every time the item is changed, changeKey changes as well. This allows Exchange to apply changes to the correct version of the object. Read-only.
    - `[CreatedDateTime <DateTime?>]`: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
    - `[LastModifiedDateTime <DateTime?>]`: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
    - `[Id <String>]`: Read-only.
    - `[Attachments <IMicrosoftGraphAttachment[]>]`: The fileAttachment and itemAttachment attachments for the message.
      - `[Id <String>]`: Read-only.
      - `[ContentType <String>]`: The MIME type.
      - `[IsInline <Boolean?>]`: true if the attachment is an inline attachment; otherwise, false.
      - `[LastModifiedDateTime <DateTime?>]`: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[Name <String>]`: The display name of the attachment. This does not need to be the actual file name.
      - `[Size <Int32?>]`: The length of the attachment in bytes.
    - `[BccRecipients <IMicrosoftGraphRecipient[]>]`: The Bcc: recipients for the message.
      - `[EmailAddress <IMicrosoftGraphEmailAddress>]`: emailAddress
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Address <String>]`: The email address of an entity instance.
        - `[Name <String>]`: The display name of an entity instance.
    - `[Body <IMicrosoftGraphItemBody>]`: itemBody
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Content <String>]`: The content of the item.
      - `[ContentType <String>]`: bodyType
    - `[BodyPreview <String>]`: The first 255 characters of the message body. It is in text format. If the message contains instances of mention, this property would contain a concatenation of these mentions as well.
    - `[CcRecipients <IMicrosoftGraphRecipient[]>]`: The Cc: recipients for the message.
    - `[ConversationId <String>]`: The ID of the conversation the email belongs to.
    - `[ConversationIndex <Byte[]>]`: Indicates the position of the message within the conversation.
    - `[Extensions <IMicrosoftGraphExtension[]>]`: The collection of open extensions defined for the message. Nullable.
      - `[Id <String>]`: Read-only.
    - `[Flag <IMicrosoftGraphFollowupFlag>]`: followupFlag
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[CompletedDateTime <IMicrosoftGraphDateTimeZone>]`: dateTimeTimeZone
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[DateTime <String>]`: A single point of time in a combined date and time representation ({date}T{time}). For example, '2019-04-16T09:00:00'.
        - `[TimeZone <String>]`: Represents a time zone, for example, 'Pacific Standard Time'. See below for possible values.
      - `[DueDateTime <IMicrosoftGraphDateTimeZone>]`: dateTimeTimeZone
      - `[FlagStatus <String>]`: followupFlagStatus
      - `[StartDateTime <IMicrosoftGraphDateTimeZone>]`: dateTimeTimeZone
    - `[From <IMicrosoftGraphRecipient>]`: recipient
    - `[HasAttachments <Boolean?>]`: Indicates whether the message has attachments. This property doesn't include inline attachments, so if a message contains only inline attachments, this property is false. To verify the existence of inline attachments, parse the body property to look for a src attribute, such as <IMG src='cid:image001.jpg@01D26CD8.6C05F070'>.
    - `[Importance <String>]`: importance
    - `[InferenceClassification <String>]`: inferenceClassificationType
    - `[InternetMessageHeaders <IMicrosoftGraphInternetMessageHeader[]>]`: 
      - `[Name <String>]`: Represents the key in a key-value pair.
      - `[Value <String>]`: The value in a key-value pair.
    - `[InternetMessageId <String>]`: 
    - `[IsDeliveryReceiptRequested <Boolean?>]`: 
    - `[IsDraft <Boolean?>]`: 
    - `[IsRead <Boolean?>]`: 
    - `[IsReadReceiptRequested <Boolean?>]`: 
    - `[MultiValueExtendedProperties <IMicrosoftGraphMultiValueLegacyExtendedProperty[]>]`: The collection of multi-value extended properties defined for the message. Nullable.
      - `[Id <String>]`: Read-only.
      - `[Value <String[]>]`: A collection of property values.
    - `[ParentFolderId <String>]`: 
    - `[ReceivedDateTime <DateTime?>]`: 
    - `[ReplyTo <IMicrosoftGraphRecipient[]>]`: 
    - `[Sender <IMicrosoftGraphRecipient>]`: recipient
    - `[SentDateTime <DateTime?>]`: 
    - `[SingleValueExtendedProperties <IMicrosoftGraphSingleValueLegacyExtendedProperty[]>]`: The collection of single-value extended properties defined for the message. Nullable.
      - `[Id <String>]`: Read-only.
      - `[Value <String>]`: A property value.
    - `[Subject <String>]`: 
    - `[ToRecipients <IMicrosoftGraphRecipient[]>]`: 
    - `[UniqueBody <IMicrosoftGraphItemBody>]`: itemBody
    - `[WebLink <String>]`: 

INPUTOBJECT <IUsersActionsIdentity>: Identity Parameter
  - `[AccessReviewInstanceDecisionItemId <String>]`: key: id of accessReviewInstanceDecisionItem
  - `[AccessReviewInstanceId <String>]`: key: id of accessReviewInstance
  - `[AppLogCollectionRequestId <String>]`: key: id of appLogCollectionRequest
  - `[AuthenticationMethodId <String>]`: key: id of authenticationMethod
  - `[BaseTaskId <String>]`: key: id of baseTask
  - `[BaseTaskListId <String>]`: key: id of baseTaskList
  - `[CalendarId <String>]`: key: id of calendar
  - `[DeviceEnrollmentConfigurationId <String>]`: key: id of deviceEnrollmentConfiguration
  - `[DeviceLogCollectionResponseId <String>]`: key: id of deviceLogCollectionResponse
  - `[EventId <String>]`: key: id of event
  - `[EventId1 <String>]`: key: id of event
  - `[MailFolderId <String>]`: key: id of mailFolder
  - `[MailFolderId1 <String>]`: key: id of mailFolder
  - `[ManagedDeviceId <String>]`: key: id of managedDevice
  - `[MessageId <String>]`: key: id of message
  - `[MobileAppTroubleshootingEventId <String>]`: key: id of mobileAppTroubleshootingEvent
  - `[NotebookId <String>]`: key: id of notebook
  - `[OnenotePageId <String>]`: key: id of onenotePage
  - `[OnenoteSectionId <String>]`: key: id of onenoteSection
  - `[OutlookTaskFolderId <String>]`: key: id of outlookTaskFolder
  - `[OutlookTaskGroupId <String>]`: key: id of outlookTaskGroup
  - `[OutlookTaskId <String>]`: key: id of outlookTask
  - `[SharedInsightId <String>]`: key: id of sharedInsight
  - `[TrendingId <String>]`: key: id of trending
  - `[UsedInsightId <String>]`: key: id of usedInsight
  - `[UserId <String>]`: key: id of user

MESSAGE <IMicrosoftGraphMessage1>: message
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Categories <String[]>]`: The categories associated with the item
  - `[ChangeKey <String>]`: Identifies the version of the item. Every time the item is changed, changeKey changes as well. This allows Exchange to apply changes to the correct version of the object. Read-only.
  - `[CreatedDateTime <DateTime?>]`: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
  - `[LastModifiedDateTime <DateTime?>]`: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
  - `[Id <String>]`: Read-only.
  - `[Attachments <IMicrosoftGraphAttachment[]>]`: The fileAttachment and itemAttachment attachments for the message.
    - `[Id <String>]`: Read-only.
    - `[ContentType <String>]`: The MIME type.
    - `[IsInline <Boolean?>]`: true if the attachment is an inline attachment; otherwise, false.
    - `[LastModifiedDateTime <DateTime?>]`: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
    - `[Name <String>]`: The display name of the attachment. This does not need to be the actual file name.
    - `[Size <Int32?>]`: The length of the attachment in bytes.
  - `[BccRecipients <IMicrosoftGraphRecipient[]>]`: The Bcc: recipients for the message.
    - `[EmailAddress <IMicrosoftGraphEmailAddress>]`: emailAddress
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Address <String>]`: The email address of an entity instance.
      - `[Name <String>]`: The display name of an entity instance.
  - `[Body <IMicrosoftGraphItemBody>]`: itemBody
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Content <String>]`: The content of the item.
    - `[ContentType <String>]`: bodyType
  - `[BodyPreview <String>]`: The first 255 characters of the message body. It is in text format. If the message contains instances of mention, this property would contain a concatenation of these mentions as well.
  - `[CcRecipients <IMicrosoftGraphRecipient[]>]`: The Cc: recipients for the message.
  - `[ConversationId <String>]`: The ID of the conversation the email belongs to.
  - `[ConversationIndex <Byte[]>]`: Indicates the position of the message within the conversation.
  - `[Extensions <IMicrosoftGraphExtension[]>]`: The collection of open extensions defined for the message. Nullable.
    - `[Id <String>]`: Read-only.
  - `[Flag <IMicrosoftGraphFollowupFlag>]`: followupFlag
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[CompletedDateTime <IMicrosoftGraphDateTimeZone>]`: dateTimeTimeZone
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[DateTime <String>]`: A single point of time in a combined date and time representation ({date}T{time}). For example, '2019-04-16T09:00:00'.
      - `[TimeZone <String>]`: Represents a time zone, for example, 'Pacific Standard Time'. See below for possible values.
    - `[DueDateTime <IMicrosoftGraphDateTimeZone>]`: dateTimeTimeZone
    - `[FlagStatus <String>]`: followupFlagStatus
    - `[StartDateTime <IMicrosoftGraphDateTimeZone>]`: dateTimeTimeZone
  - `[From <IMicrosoftGraphRecipient>]`: recipient
  - `[HasAttachments <Boolean?>]`: Indicates whether the message has attachments. This property doesn't include inline attachments, so if a message contains only inline attachments, this property is false. To verify the existence of inline attachments, parse the body property to look for a src attribute, such as <IMG src='cid:image001.jpg@01D26CD8.6C05F070'>.
  - `[Importance <String>]`: importance
  - `[InferenceClassification <String>]`: inferenceClassificationType
  - `[InternetMessageHeaders <IMicrosoftGraphInternetMessageHeader[]>]`: 
    - `[Name <String>]`: Represents the key in a key-value pair.
    - `[Value <String>]`: The value in a key-value pair.
  - `[InternetMessageId <String>]`: 
  - `[IsDeliveryReceiptRequested <Boolean?>]`: 
  - `[IsDraft <Boolean?>]`: 
  - `[IsRead <Boolean?>]`: 
  - `[IsReadReceiptRequested <Boolean?>]`: 
  - `[MultiValueExtendedProperties <IMicrosoftGraphMultiValueLegacyExtendedProperty[]>]`: The collection of multi-value extended properties defined for the message. Nullable.
    - `[Id <String>]`: Read-only.
    - `[Value <String[]>]`: A collection of property values.
  - `[ParentFolderId <String>]`: 
  - `[ReceivedDateTime <DateTime?>]`: 
  - `[ReplyTo <IMicrosoftGraphRecipient[]>]`: 
  - `[Sender <IMicrosoftGraphRecipient>]`: recipient
  - `[SentDateTime <DateTime?>]`: 
  - `[SingleValueExtendedProperties <IMicrosoftGraphSingleValueLegacyExtendedProperty[]>]`: The collection of single-value extended properties defined for the message. Nullable.
    - `[Id <String>]`: Read-only.
    - `[Value <String>]`: A property value.
  - `[Subject <String>]`: 
  - `[ToRecipients <IMicrosoftGraphRecipient[]>]`: 
  - `[UniqueBody <IMicrosoftGraphItemBody>]`: itemBody
  - `[WebLink <String>]`: 

## RELATED LINKS

