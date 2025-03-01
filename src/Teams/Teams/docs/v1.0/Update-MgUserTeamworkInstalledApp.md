---
external help file:
Module Name: Microsoft.Graph.Teams
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.teams/update-mguserteamworkinstalledapp
schema: 2.0.0
---

# Update-MgUserTeamworkInstalledApp

## SYNOPSIS
The apps installed in the personal scope of this user.

## SYNTAX

### UpdateExpanded1 (Default)
```
Update-MgUserTeamworkInstalledApp -UserId <String> -UserScopeTeamsAppInstallationId <String>
 [-AdditionalProperties <Hashtable>] [-Chat <IMicrosoftGraphChat1>] [-Id <String>]
 [-TeamsApp <IMicrosoftGraphTeamsApp1>] [-TeamsAppDefinition <IMicrosoftGraphTeamsAppDefinition1>] [-PassThru]
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Update1
```
Update-MgUserTeamworkInstalledApp -UserId <String> -UserScopeTeamsAppInstallationId <String>
 -BodyParameter <IMicrosoftGraphUserScopeTeamsAppInstallation1> [-PassThru] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### UpdateViaIdentity1
```
Update-MgUserTeamworkInstalledApp -InputObject <ITeamsIdentity>
 -BodyParameter <IMicrosoftGraphUserScopeTeamsAppInstallation1> [-PassThru] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### UpdateViaIdentityExpanded1
```
Update-MgUserTeamworkInstalledApp -InputObject <ITeamsIdentity> [-AdditionalProperties <Hashtable>]
 [-Chat <IMicrosoftGraphChat1>] [-Id <String>] [-TeamsApp <IMicrosoftGraphTeamsApp1>]
 [-TeamsAppDefinition <IMicrosoftGraphTeamsAppDefinition1>] [-PassThru] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

## DESCRIPTION
The apps installed in the personal scope of this user.

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: System.Collections.Hashtable
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
userScopeTeamsAppInstallation
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserScopeTeamsAppInstallation1
Parameter Sets: Update1, UpdateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Chat
chat
To construct, please use Get-Help -Online and see NOTES section for CHAT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphChat1
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Type: Microsoft.Graph.PowerShell.Models.ITeamsIdentity
Parameter Sets: UpdateViaIdentity1, UpdateViaIdentityExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
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

### -TeamsApp
teamsApp
To construct, please use Get-Help -Online and see NOTES section for TEAMSAPP properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphTeamsApp1
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TeamsAppDefinition
teamsAppDefinition
To construct, please use Get-Help -Online and see NOTES section for TEAMSAPPDEFINITION properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphTeamsAppDefinition1
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Parameter Sets: Update1, UpdateExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserScopeTeamsAppInstallationId
key: id of userScopeTeamsAppInstallation

```yaml
Type: System.String
Parameter Sets: Update1, UpdateExpanded1
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserScopeTeamsAppInstallation1

### Microsoft.Graph.PowerShell.Models.ITeamsIdentity

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphUserScopeTeamsAppInstallation1>: userScopeTeamsAppInstallation
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[TeamsApp <IMicrosoftGraphTeamsApp1>]`: teamsApp
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[AppDefinitions <IMicrosoftGraphTeamsAppDefinition1[]>]`: The details for each version of the app.
      - `[Id <String>]`: Read-only.
      - `[Bot <IMicrosoftGraphTeamworkBot>]`: teamworkBot
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
      - `[CreatedBy <IMicrosoftGraphIdentitySet>]`: identitySet
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Application <IMicrosoftGraphIdentity>]`: identity
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[DisplayName <String>]`: The display name of the identity. This property is read-only.
          - `[Id <String>]`: The identifier of the identity. This property is read-only.
        - `[Device <IMicrosoftGraphIdentity>]`: identity
        - `[User <IMicrosoftGraphIdentity>]`: identity
      - `[Description <String>]`: Verbose description of the application.
      - `[DisplayName <String>]`: The name of the app provided by the app developer.
      - `[LastModifiedDateTime <DateTime?>]`: 
      - `[PublishingState <String>]`: teamsAppPublishingState
      - `[ShortDescription <String>]`: Short description of the application.
      - `[TeamsAppId <String>]`: The ID from the Teams app manifest.
      - `[Version <String>]`: The version number of the application.
    - `[DisplayName <String>]`: The name of the catalog app provided by the app developer in the Microsoft Teams zip app package.
    - `[DistributionMethod <String>]`: teamsAppDistributionMethod
    - `[ExternalId <String>]`: The ID of the catalog provided by the app developer in the Microsoft Teams zip app package.
  - `[TeamsAppDefinition <IMicrosoftGraphTeamsAppDefinition1>]`: teamsAppDefinition
  - `[Id <String>]`: Read-only.
  - `[Chat <IMicrosoftGraphChat1>]`: chat
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[ChatType <String>]`: chatType
    - `[CreatedDateTime <DateTime?>]`: Date and time at which the chat was created. Read-only.
    - `[InstalledApps <IMicrosoftGraphTeamsAppInstallation1[]>]`: A collection of all the apps in the chat. Nullable.
      - `[Id <String>]`: Read-only.
      - `[TeamsApp <IMicrosoftGraphTeamsApp1>]`: teamsApp
      - `[TeamsAppDefinition <IMicrosoftGraphTeamsAppDefinition1>]`: teamsAppDefinition
    - `[LastUpdatedDateTime <DateTime?>]`: Date and time at which the chat was renamed or list of members were last changed. Read-only.
    - `[Members <IMicrosoftGraphConversationMember[]>]`: A collection of all the members in the chat. Nullable.
      - `[Id <String>]`: Read-only.
      - `[DisplayName <String>]`: The display name of the user.
      - `[Roles <String[]>]`: The roles for that user.
      - `[VisibleHistoryStartDateTime <DateTime?>]`: The timestamp denoting how far back a conversation's history is shared with the conversation member. This property is settable only for members of a chat.
    - `[Messages <IMicrosoftGraphChatMessage1[]>]`: A collection of all the messages in the chat. Nullable.
      - `[Id <String>]`: Read-only.
      - `[Attachments <IMicrosoftGraphChatMessageAttachment[]>]`: References to attached objects like files, tabs, meetings etc.
        - `[Content <String>]`: The content of the attachment. If the attachment is a rich card, set the property to the rich card object. This property and contentUrl are mutually exclusive.
        - `[ContentType <String>]`: The media type of the content attachment. It can have the following values: reference: Attachment is a link to another file. Populate the contentURL with the link to the object.Any contentTypes supported by the Bot Framework's Attachment objectapplication/vnd.microsoft.card.codesnippet: A code snippet. application/vnd.microsoft.card.announcement: An announcement header.
        - `[ContentUrl <String>]`: URL for the content of the attachment. Supported protocols: http, https, file and data.
        - `[Id <String>]`: Read-only. Unique id of the attachment.
        - `[Name <String>]`: Name of the attachment.
        - `[ThumbnailUrl <String>]`: URL to a thumbnail image that the channel can use if it supports using an alternative, smaller form of content or contentUrl. For example, if you set contentType to application/word and set contentUrl to the location of the Word document, you might include a thumbnail image that represents the document. The channel could display the thumbnail image instead of the document. When the user clicks the image, the channel would open the document.
      - `[Body <IMicrosoftGraphItemBody>]`: itemBody
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Content <String>]`: The content of the item.
        - `[ContentType <String>]`: bodyType
      - `[ChannelIdentity <IMicrosoftGraphChannelIdentity>]`: channelIdentity
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[ChannelId <String>]`: The identity of the channel in which the message was posted.
        - `[TeamId <String>]`: The identity of the team in which the message was posted.
      - `[ChatId <String>]`: If the message was sent in a chat, represents the identity of the chat.
      - `[CreatedDateTime <DateTime?>]`: Timestamp of when the chat message was created.
      - `[DeletedDateTime <DateTime?>]`: Read only. Timestamp at which the chat message was deleted, or null if not deleted.
      - `[Etag <String>]`: Read-only. Version number of the chat message.
      - `[EventDetail <IMicrosoftGraphEventMessageDetail>]`: eventMessageDetail
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[From <IMicrosoftGraphChatMessageFromIdentitySet>]`: chatMessageFromIdentitySet
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Application <IMicrosoftGraphIdentity>]`: identity
        - `[Device <IMicrosoftGraphIdentity>]`: identity
        - `[User <IMicrosoftGraphIdentity>]`: identity
      - `[HostedContents <IMicrosoftGraphChatMessageHostedContent[]>]`: Content in a message hosted by Microsoft Teams - for example, images or code snippets.
        - `[ContentBytes <Byte[]>]`: Write only. Bytes for the hosted content (such as images).
        - `[ContentType <String>]`: Write only. Content type, such as image/png, image/jpg.
        - `[Id <String>]`: Read-only.
      - `[Importance <String>]`: 
      - `[LastEditedDateTime <DateTime?>]`: Read only. Timestamp when edits to the chat message were made. Triggers an 'Edited' flag in the Teams UI. If no edits are made the value is null.
      - `[LastModifiedDateTime <DateTime?>]`: Read only. Timestamp when the chat message is created (initial setting) or modified, including when a reaction is added or removed.
      - `[Locale <String>]`: Locale of the chat message set by the client. Always set to en-us.
      - `[Mentions <IMicrosoftGraphChatMessageMention1[]>]`: List of entities mentioned in the chat message. Supported entities are: user, bot, team, channel, and tag.
        - `[Id <Int32?>]`: Index of an entity being mentioned in the specified chatMessage. Matches the {index} value in the corresponding <at id='{index}'> tag in the message body.
        - `[MentionText <String>]`: String used to represent the mention. For example, a user's display name, a team name.
        - `[Mentioned <IMicrosoftGraphChatMessageMentionedIdentitySet1>]`: chatMessageMentionedIdentitySet
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[Application <IMicrosoftGraphIdentity>]`: identity
          - `[Device <IMicrosoftGraphIdentity>]`: identity
          - `[User <IMicrosoftGraphIdentity>]`: identity
          - `[Conversation <IMicrosoftGraphTeamworkConversationIdentity>]`: teamworkConversationIdentity
            - `[(Any) <Object>]`: This indicates any property can be added to this object.
            - `[DisplayName <String>]`: The display name of the identity. This property is read-only.
            - `[Id <String>]`: The identifier of the identity. This property is read-only.
            - `[ConversationIdentityType <String>]`: teamworkConversationIdentityType
      - `[MessageType <String>]`: chatMessageType
      - `[PolicyViolation <IMicrosoftGraphChatMessagePolicyViolation>]`: chatMessagePolicyViolation
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[DlpAction <String>]`: chatMessagePolicyViolationDlpActionTypes
        - `[JustificationText <String>]`: Justification text provided by the sender of the message when overriding a policy violation.
        - `[PolicyTip <IMicrosoftGraphChatMessagePolicyViolationPolicyTip>]`: chatMessagePolicyViolationPolicyTip
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[ComplianceUrl <String>]`: The URL a user can visit to read about the data loss prevention policies for the organization. (ie, policies about what users shouldn't say in chats)
          - `[GeneralText <String>]`: Explanatory text shown to the sender of the message.
          - `[MatchedConditionDescriptions <String[]>]`: The list of improper data in the message that was detected by the data loss prevention app. Each DLP app defines its own conditions, examples include 'Credit Card Number' and 'Social Security Number'.
        - `[UserAction <String>]`: chatMessagePolicyViolationUserActionTypes
        - `[VerdictDetails <String>]`: chatMessagePolicyViolationVerdictDetailsTypes
      - `[Reactions <IMicrosoftGraphChatMessageReaction[]>]`: Reactions for this chat message (for example, Like).
        - `[CreatedDateTime <DateTime?>]`: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
        - `[ReactionType <String>]`: Supported values are like, angry, sad, laugh, heart, surprised.
        - `[User <IMicrosoftGraphChatMessageReactionIdentitySet>]`: chatMessageReactionIdentitySet
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[Application <IMicrosoftGraphIdentity>]`: identity
          - `[Device <IMicrosoftGraphIdentity>]`: identity
          - `[User <IMicrosoftGraphIdentity>]`: identity
      - `[Replies <IMicrosoftGraphChatMessage1[]>]`: Replies for a specified message.
      - `[ReplyToId <String>]`: Read-only. ID of the parent chat message or root chat message of the thread. (Only applies to chat messages in channels, not chats.)
      - `[Subject <String>]`: The subject of the chat message, in plaintext.
      - `[Summary <String>]`: Summary text of the chat message that could be used for push notifications and summary views or fall back views. Only applies to channel chat messages, not chat messages in a chat.
      - `[WebUrl <String>]`: Read-only. Link to the message in Microsoft Teams.
    - `[Tabs <IMicrosoftGraphTeamsTab1[]>]`: 
      - `[Id <String>]`: Read-only.
      - `[Configuration <IMicrosoftGraphTeamsTabConfiguration>]`: teamsTabConfiguration
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[ContentUrl <String>]`: Url used for rendering tab contents in Teams. Required.
        - `[EntityId <String>]`: Identifier for the entity hosted by the tab provider.
        - `[RemoveUrl <String>]`: Url called by Teams client when a Tab is removed using the Teams Client.
        - `[WebsiteUrl <String>]`: Url for showing tab contents outside of Teams.
      - `[DisplayName <String>]`: Name of the tab.
      - `[TeamsApp <IMicrosoftGraphTeamsApp1>]`: teamsApp
      - `[WebUrl <String>]`: Deep link URL of the tab instance. Read only.
    - `[Topic <String>]`: (Optional) Subject or topic for the chat. Only available for group chats.
    - `[WebUrl <String>]`: The URL for the chat in Microsoft Teams. The URL should be treated as an opaque blob, and not parsed. Read-only.

CHAT <IMicrosoftGraphChat1>: chat
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[ChatType <String>]`: chatType
  - `[CreatedDateTime <DateTime?>]`: Date and time at which the chat was created. Read-only.
  - `[InstalledApps <IMicrosoftGraphTeamsAppInstallation1[]>]`: A collection of all the apps in the chat. Nullable.
    - `[Id <String>]`: Read-only.
    - `[TeamsApp <IMicrosoftGraphTeamsApp1>]`: teamsApp
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[AppDefinitions <IMicrosoftGraphTeamsAppDefinition1[]>]`: The details for each version of the app.
        - `[Id <String>]`: Read-only.
        - `[Bot <IMicrosoftGraphTeamworkBot>]`: teamworkBot
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[Id <String>]`: Read-only.
        - `[CreatedBy <IMicrosoftGraphIdentitySet>]`: identitySet
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[Application <IMicrosoftGraphIdentity>]`: identity
            - `[(Any) <Object>]`: This indicates any property can be added to this object.
            - `[DisplayName <String>]`: The display name of the identity. This property is read-only.
            - `[Id <String>]`: The identifier of the identity. This property is read-only.
          - `[Device <IMicrosoftGraphIdentity>]`: identity
          - `[User <IMicrosoftGraphIdentity>]`: identity
        - `[Description <String>]`: Verbose description of the application.
        - `[DisplayName <String>]`: The name of the app provided by the app developer.
        - `[LastModifiedDateTime <DateTime?>]`: 
        - `[PublishingState <String>]`: teamsAppPublishingState
        - `[ShortDescription <String>]`: Short description of the application.
        - `[TeamsAppId <String>]`: The ID from the Teams app manifest.
        - `[Version <String>]`: The version number of the application.
      - `[DisplayName <String>]`: The name of the catalog app provided by the app developer in the Microsoft Teams zip app package.
      - `[DistributionMethod <String>]`: teamsAppDistributionMethod
      - `[ExternalId <String>]`: The ID of the catalog provided by the app developer in the Microsoft Teams zip app package.
    - `[TeamsAppDefinition <IMicrosoftGraphTeamsAppDefinition1>]`: teamsAppDefinition
  - `[LastUpdatedDateTime <DateTime?>]`: Date and time at which the chat was renamed or list of members were last changed. Read-only.
  - `[Members <IMicrosoftGraphConversationMember[]>]`: A collection of all the members in the chat. Nullable.
    - `[Id <String>]`: Read-only.
    - `[DisplayName <String>]`: The display name of the user.
    - `[Roles <String[]>]`: The roles for that user.
    - `[VisibleHistoryStartDateTime <DateTime?>]`: The timestamp denoting how far back a conversation's history is shared with the conversation member. This property is settable only for members of a chat.
  - `[Messages <IMicrosoftGraphChatMessage1[]>]`: A collection of all the messages in the chat. Nullable.
    - `[Id <String>]`: Read-only.
    - `[Attachments <IMicrosoftGraphChatMessageAttachment[]>]`: References to attached objects like files, tabs, meetings etc.
      - `[Content <String>]`: The content of the attachment. If the attachment is a rich card, set the property to the rich card object. This property and contentUrl are mutually exclusive.
      - `[ContentType <String>]`: The media type of the content attachment. It can have the following values: reference: Attachment is a link to another file. Populate the contentURL with the link to the object.Any contentTypes supported by the Bot Framework's Attachment objectapplication/vnd.microsoft.card.codesnippet: A code snippet. application/vnd.microsoft.card.announcement: An announcement header.
      - `[ContentUrl <String>]`: URL for the content of the attachment. Supported protocols: http, https, file and data.
      - `[Id <String>]`: Read-only. Unique id of the attachment.
      - `[Name <String>]`: Name of the attachment.
      - `[ThumbnailUrl <String>]`: URL to a thumbnail image that the channel can use if it supports using an alternative, smaller form of content or contentUrl. For example, if you set contentType to application/word and set contentUrl to the location of the Word document, you might include a thumbnail image that represents the document. The channel could display the thumbnail image instead of the document. When the user clicks the image, the channel would open the document.
    - `[Body <IMicrosoftGraphItemBody>]`: itemBody
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Content <String>]`: The content of the item.
      - `[ContentType <String>]`: bodyType
    - `[ChannelIdentity <IMicrosoftGraphChannelIdentity>]`: channelIdentity
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[ChannelId <String>]`: The identity of the channel in which the message was posted.
      - `[TeamId <String>]`: The identity of the team in which the message was posted.
    - `[ChatId <String>]`: If the message was sent in a chat, represents the identity of the chat.
    - `[CreatedDateTime <DateTime?>]`: Timestamp of when the chat message was created.
    - `[DeletedDateTime <DateTime?>]`: Read only. Timestamp at which the chat message was deleted, or null if not deleted.
    - `[Etag <String>]`: Read-only. Version number of the chat message.
    - `[EventDetail <IMicrosoftGraphEventMessageDetail>]`: eventMessageDetail
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[From <IMicrosoftGraphChatMessageFromIdentitySet>]`: chatMessageFromIdentitySet
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Application <IMicrosoftGraphIdentity>]`: identity
      - `[Device <IMicrosoftGraphIdentity>]`: identity
      - `[User <IMicrosoftGraphIdentity>]`: identity
    - `[HostedContents <IMicrosoftGraphChatMessageHostedContent[]>]`: Content in a message hosted by Microsoft Teams - for example, images or code snippets.
      - `[ContentBytes <Byte[]>]`: Write only. Bytes for the hosted content (such as images).
      - `[ContentType <String>]`: Write only. Content type, such as image/png, image/jpg.
      - `[Id <String>]`: Read-only.
    - `[Importance <String>]`: 
    - `[LastEditedDateTime <DateTime?>]`: Read only. Timestamp when edits to the chat message were made. Triggers an 'Edited' flag in the Teams UI. If no edits are made the value is null.
    - `[LastModifiedDateTime <DateTime?>]`: Read only. Timestamp when the chat message is created (initial setting) or modified, including when a reaction is added or removed.
    - `[Locale <String>]`: Locale of the chat message set by the client. Always set to en-us.
    - `[Mentions <IMicrosoftGraphChatMessageMention1[]>]`: List of entities mentioned in the chat message. Supported entities are: user, bot, team, channel, and tag.
      - `[Id <Int32?>]`: Index of an entity being mentioned in the specified chatMessage. Matches the {index} value in the corresponding <at id='{index}'> tag in the message body.
      - `[MentionText <String>]`: String used to represent the mention. For example, a user's display name, a team name.
      - `[Mentioned <IMicrosoftGraphChatMessageMentionedIdentitySet1>]`: chatMessageMentionedIdentitySet
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Application <IMicrosoftGraphIdentity>]`: identity
        - `[Device <IMicrosoftGraphIdentity>]`: identity
        - `[User <IMicrosoftGraphIdentity>]`: identity
        - `[Conversation <IMicrosoftGraphTeamworkConversationIdentity>]`: teamworkConversationIdentity
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[DisplayName <String>]`: The display name of the identity. This property is read-only.
          - `[Id <String>]`: The identifier of the identity. This property is read-only.
          - `[ConversationIdentityType <String>]`: teamworkConversationIdentityType
    - `[MessageType <String>]`: chatMessageType
    - `[PolicyViolation <IMicrosoftGraphChatMessagePolicyViolation>]`: chatMessagePolicyViolation
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[DlpAction <String>]`: chatMessagePolicyViolationDlpActionTypes
      - `[JustificationText <String>]`: Justification text provided by the sender of the message when overriding a policy violation.
      - `[PolicyTip <IMicrosoftGraphChatMessagePolicyViolationPolicyTip>]`: chatMessagePolicyViolationPolicyTip
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[ComplianceUrl <String>]`: The URL a user can visit to read about the data loss prevention policies for the organization. (ie, policies about what users shouldn't say in chats)
        - `[GeneralText <String>]`: Explanatory text shown to the sender of the message.
        - `[MatchedConditionDescriptions <String[]>]`: The list of improper data in the message that was detected by the data loss prevention app. Each DLP app defines its own conditions, examples include 'Credit Card Number' and 'Social Security Number'.
      - `[UserAction <String>]`: chatMessagePolicyViolationUserActionTypes
      - `[VerdictDetails <String>]`: chatMessagePolicyViolationVerdictDetailsTypes
    - `[Reactions <IMicrosoftGraphChatMessageReaction[]>]`: Reactions for this chat message (for example, Like).
      - `[CreatedDateTime <DateTime?>]`: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[ReactionType <String>]`: Supported values are like, angry, sad, laugh, heart, surprised.
      - `[User <IMicrosoftGraphChatMessageReactionIdentitySet>]`: chatMessageReactionIdentitySet
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Application <IMicrosoftGraphIdentity>]`: identity
        - `[Device <IMicrosoftGraphIdentity>]`: identity
        - `[User <IMicrosoftGraphIdentity>]`: identity
    - `[Replies <IMicrosoftGraphChatMessage1[]>]`: Replies for a specified message.
    - `[ReplyToId <String>]`: Read-only. ID of the parent chat message or root chat message of the thread. (Only applies to chat messages in channels, not chats.)
    - `[Subject <String>]`: The subject of the chat message, in plaintext.
    - `[Summary <String>]`: Summary text of the chat message that could be used for push notifications and summary views or fall back views. Only applies to channel chat messages, not chat messages in a chat.
    - `[WebUrl <String>]`: Read-only. Link to the message in Microsoft Teams.
  - `[Tabs <IMicrosoftGraphTeamsTab1[]>]`: 
    - `[Id <String>]`: Read-only.
    - `[Configuration <IMicrosoftGraphTeamsTabConfiguration>]`: teamsTabConfiguration
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[ContentUrl <String>]`: Url used for rendering tab contents in Teams. Required.
      - `[EntityId <String>]`: Identifier for the entity hosted by the tab provider.
      - `[RemoveUrl <String>]`: Url called by Teams client when a Tab is removed using the Teams Client.
      - `[WebsiteUrl <String>]`: Url for showing tab contents outside of Teams.
    - `[DisplayName <String>]`: Name of the tab.
    - `[TeamsApp <IMicrosoftGraphTeamsApp1>]`: teamsApp
    - `[WebUrl <String>]`: Deep link URL of the tab instance. Read only.
  - `[Topic <String>]`: (Optional) Subject or topic for the chat. Only available for group chats.
  - `[WebUrl <String>]`: The URL for the chat in Microsoft Teams. The URL should be treated as an opaque blob, and not parsed. Read-only.

INPUTOBJECT <ITeamsIdentity>: Identity Parameter
  - `[ChannelId <String>]`: key: id of channel
  - `[ChatId <String>]`: key: id of chat
  - `[ChatMessageHostedContentId <String>]`: key: id of chatMessageHostedContent
  - `[ChatMessageId <String>]`: key: id of chatMessage
  - `[ChatMessageId1 <String>]`: key: id of chatMessage
  - `[ConversationMemberId <String>]`: key: id of conversationMember
  - `[GroupId <String>]`: key: id of group
  - `[OfferShiftRequestId <String>]`: key: id of offerShiftRequest
  - `[OpenShiftChangeRequestId <String>]`: key: id of openShiftChangeRequest
  - `[OpenShiftId <String>]`: key: id of openShift
  - `[ResourceSpecificPermissionGrantId <String>]`: key: id of resourceSpecificPermissionGrant
  - `[SchedulingGroupId <String>]`: key: id of schedulingGroup
  - `[ShiftId <String>]`: key: id of shift
  - `[SwapShiftsChangeRequestId <String>]`: key: id of swapShiftsChangeRequest
  - `[TeamId <String>]`: key: id of team
  - `[TeamsAppDefinitionId <String>]`: key: id of teamsAppDefinition
  - `[TeamsAppId <String>]`: key: id of teamsApp
  - `[TeamsAppInstallationId <String>]`: key: id of teamsAppInstallation
  - `[TeamsAsyncOperationId <String>]`: key: id of teamsAsyncOperation
  - `[TeamsTabId <String>]`: key: id of teamsTab
  - `[TeamworkDeviceId <String>]`: key: id of teamworkDevice
  - `[TeamworkDeviceOperationId <String>]`: key: id of teamworkDeviceOperation
  - `[TeamworkTagId <String>]`: key: id of teamworkTag
  - `[TeamworkTagMemberId <String>]`: key: id of teamworkTagMember
  - `[TimeCardId <String>]`: key: id of timeCard
  - `[TimeOffId <String>]`: key: id of timeOff
  - `[TimeOffReasonId <String>]`: key: id of timeOffReason
  - `[TimeOffRequestId <String>]`: key: id of timeOffRequest
  - `[UserId <String>]`: key: id of user
  - `[UserScopeTeamsAppInstallationId <String>]`: key: id of userScopeTeamsAppInstallation
  - `[WorkforceIntegrationId <String>]`: key: id of workforceIntegration

TEAMSAPP <IMicrosoftGraphTeamsApp1>: teamsApp
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[AppDefinitions <IMicrosoftGraphTeamsAppDefinition1[]>]`: The details for each version of the app.
    - `[Id <String>]`: Read-only.
    - `[Bot <IMicrosoftGraphTeamworkBot>]`: teamworkBot
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
    - `[CreatedBy <IMicrosoftGraphIdentitySet>]`: identitySet
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Application <IMicrosoftGraphIdentity>]`: identity
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[DisplayName <String>]`: The display name of the identity. This property is read-only.
        - `[Id <String>]`: The identifier of the identity. This property is read-only.
      - `[Device <IMicrosoftGraphIdentity>]`: identity
      - `[User <IMicrosoftGraphIdentity>]`: identity
    - `[Description <String>]`: Verbose description of the application.
    - `[DisplayName <String>]`: The name of the app provided by the app developer.
    - `[LastModifiedDateTime <DateTime?>]`: 
    - `[PublishingState <String>]`: teamsAppPublishingState
    - `[ShortDescription <String>]`: Short description of the application.
    - `[TeamsAppId <String>]`: The ID from the Teams app manifest.
    - `[Version <String>]`: The version number of the application.
  - `[DisplayName <String>]`: The name of the catalog app provided by the app developer in the Microsoft Teams zip app package.
  - `[DistributionMethod <String>]`: teamsAppDistributionMethod
  - `[ExternalId <String>]`: The ID of the catalog provided by the app developer in the Microsoft Teams zip app package.

TEAMSAPPDEFINITION <IMicrosoftGraphTeamsAppDefinition1>: teamsAppDefinition
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[Bot <IMicrosoftGraphTeamworkBot>]`: teamworkBot
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
  - `[CreatedBy <IMicrosoftGraphIdentitySet>]`: identitySet
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Application <IMicrosoftGraphIdentity>]`: identity
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[DisplayName <String>]`: The display name of the identity. This property is read-only.
      - `[Id <String>]`: The identifier of the identity. This property is read-only.
    - `[Device <IMicrosoftGraphIdentity>]`: identity
    - `[User <IMicrosoftGraphIdentity>]`: identity
  - `[Description <String>]`: Verbose description of the application.
  - `[DisplayName <String>]`: The name of the app provided by the app developer.
  - `[LastModifiedDateTime <DateTime?>]`: 
  - `[PublishingState <String>]`: teamsAppPublishingState
  - `[ShortDescription <String>]`: Short description of the application.
  - `[TeamsAppId <String>]`: The ID from the Teams app manifest.
  - `[Version <String>]`: The version number of the application.

## RELATED LINKS

