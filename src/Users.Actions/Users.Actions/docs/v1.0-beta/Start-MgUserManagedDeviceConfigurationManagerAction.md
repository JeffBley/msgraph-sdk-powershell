---
external help file:
Module Name: Microsoft.Graph.Users.Actions
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.users.actions/start-mgusermanageddeviceconfigurationmanageraction
schema: 2.0.0
---

# Start-MgUserManagedDeviceConfigurationManagerAction

## SYNOPSIS
Trigger action on ConfigurationManager client

## SYNTAX

### TriggerExpanded (Default)
```
Start-MgUserManagedDeviceConfigurationManagerAction -ManagedDeviceId <String> -UserId <String>
 [-AdditionalProperties <Hashtable>] [-ConfigurationManagerAction <IMicrosoftGraphConfigurationManagerAction>]
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Trigger
```
Start-MgUserManagedDeviceConfigurationManagerAction -ManagedDeviceId <String> -UserId <String>
 -BodyParameter <IPathsA6Tcp7UsersUserIdManageddevicesManageddeviceIdMicrosoftGraphTriggerconfigurationmanageractionPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### TriggerViaIdentity
```
Start-MgUserManagedDeviceConfigurationManagerAction -InputObject <IUsersActionsIdentity>
 -BodyParameter <IPathsA6Tcp7UsersUserIdManageddevicesManageddeviceIdMicrosoftGraphTriggerconfigurationmanageractionPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### TriggerViaIdentityExpanded
```
Start-MgUserManagedDeviceConfigurationManagerAction -InputObject <IUsersActionsIdentity>
 [-AdditionalProperties <Hashtable>] [-ConfigurationManagerAction <IMicrosoftGraphConfigurationManagerAction>]
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Trigger action on ConfigurationManager client

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: System.Collections.Hashtable
Parameter Sets: TriggerExpanded, TriggerViaIdentityExpanded
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
Type: Microsoft.Graph.PowerShell.Models.IPathsA6Tcp7UsersUserIdManageddevicesManageddeviceIdMicrosoftGraphTriggerconfigurationmanageractionPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Trigger, TriggerViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ConfigurationManagerAction
Parameter for action triggerConfigurationManagerAction
To construct, please use Get-Help -Online and see NOTES section for CONFIGURATIONMANAGERACTION properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphConfigurationManagerAction
Parameter Sets: TriggerExpanded, TriggerViaIdentityExpanded
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
Parameter Sets: TriggerViaIdentity, TriggerViaIdentityExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ManagedDeviceId
key: id of managedDevice

```yaml
Type: System.String
Parameter Sets: Trigger, TriggerExpanded
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

### -UserId
key: id of user

```yaml
Type: System.String
Parameter Sets: Trigger, TriggerExpanded
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

### Microsoft.Graph.PowerShell.Models.IPathsA6Tcp7UsersUserIdManageddevicesManageddeviceIdMicrosoftGraphTriggerconfigurationmanageractionPostRequestbodyContentApplicationJsonSchema

### Microsoft.Graph.PowerShell.Models.IUsersActionsIdentity

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IPathsA6Tcp7UsersUserIdManageddevicesManageddeviceIdMicrosoftGraphTriggerconfigurationmanageractionPostRequestbodyContentApplicationJsonSchema>: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[ConfigurationManagerAction <IMicrosoftGraphConfigurationManagerAction>]`: Parameter for action triggerConfigurationManagerAction
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Action <String>]`: Action type on Configuration Manager client

CONFIGURATIONMANAGERACTION <IMicrosoftGraphConfigurationManagerAction>: Parameter for action triggerConfigurationManagerAction
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Action <String>]`: Action type on Configuration Manager client

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

## RELATED LINKS

