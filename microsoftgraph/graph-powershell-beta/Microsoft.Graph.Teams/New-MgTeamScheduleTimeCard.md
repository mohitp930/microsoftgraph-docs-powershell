---
external help file: Microsoft.Graph.Teams-help.xml
Module Name: Microsoft.Graph.Teams
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.teams/new-mgteamscheduletimecard
schema: 2.0.0
---

# New-MgTeamScheduleTimeCard

## SYNOPSIS
Create new navigation property to timeCards for teams

## SYNTAX

### CreateExpanded (Default)
```
New-MgTeamScheduleTimeCard -TeamId <String> [-AdditionalProperties <Hashtable>]
 [-Breaks <IMicrosoftGraphTimeCardBreak[]>] [-ClockInEvent <IMicrosoftGraphTimeCardEvent>]
 [-ClockOutEvent <IMicrosoftGraphTimeCardEvent>] [-ConfirmedBy <String>]
 [-CreatedBy <IMicrosoftGraphIdentitySet>] [-CreatedDateTime <DateTime>] [-Id <String>]
 [-LastModifiedBy <IMicrosoftGraphIdentitySet>] [-LastModifiedDateTime <DateTime>]
 [-Notes <IMicrosoftGraphItemBody>] [-OriginalEntry <IMicrosoftGraphTimeCardEntry>] [-State <String>]
 [-UserId <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgTeamScheduleTimeCard -TeamId <String> -BodyParameter <IMicrosoftGraphTimeCard> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### CreateViaIdentityExpanded
```
New-MgTeamScheduleTimeCard -InputObject <ITeamsIdentity> [-AdditionalProperties <Hashtable>]
 [-Breaks <IMicrosoftGraphTimeCardBreak[]>] [-ClockInEvent <IMicrosoftGraphTimeCardEvent>]
 [-ClockOutEvent <IMicrosoftGraphTimeCardEvent>] [-ConfirmedBy <String>]
 [-CreatedBy <IMicrosoftGraphIdentitySet>] [-CreatedDateTime <DateTime>] [-Id <String>]
 [-LastModifiedBy <IMicrosoftGraphIdentitySet>] [-LastModifiedDateTime <DateTime>]
 [-Notes <IMicrosoftGraphItemBody>] [-OriginalEntry <IMicrosoftGraphTimeCardEntry>] [-State <String>]
 [-UserId <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### CreateViaIdentity
```
New-MgTeamScheduleTimeCard -InputObject <ITeamsIdentity> -BodyParameter <IMicrosoftGraphTimeCard> [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to timeCards for teams

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
timeCard
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphTimeCard
Parameter Sets: Create, CreateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Breaks
.
To construct, see NOTES section for BREAKS properties and create a hash table.

```yaml
Type: IMicrosoftGraphTimeCardBreak[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ClockInEvent
timeCardEvent
To construct, see NOTES section for CLOCKINEVENT properties and create a hash table.

```yaml
Type: IMicrosoftGraphTimeCardEvent
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ClockOutEvent
timeCardEvent
To construct, see NOTES section for CLOCKOUTEVENT properties and create a hash table.

```yaml
Type: IMicrosoftGraphTimeCardEvent
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ConfirmedBy
confirmedBy

```yaml
Type: String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CreatedBy
identitySet
To construct, see NOTES section for CREATEDBY properties and create a hash table.

```yaml
Type: IMicrosoftGraphIdentitySet
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CreatedDateTime
The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z

```yaml
Type: DateTime
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
Type: String
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
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: ITeamsIdentity
Parameter Sets: CreateViaIdentityExpanded, CreateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -LastModifiedBy
identitySet
To construct, see NOTES section for LASTMODIFIEDBY properties and create a hash table.

```yaml
Type: IMicrosoftGraphIdentitySet
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LastModifiedDateTime
The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z

```yaml
Type: DateTime
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Notes
itemBody
To construct, see NOTES section for NOTES properties and create a hash table.

```yaml
Type: IMicrosoftGraphItemBody
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OriginalEntry
timeCardEntry
To construct, see NOTES section for ORIGINALENTRY properties and create a hash table.

```yaml
Type: IMicrosoftGraphTimeCardEntry
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -State
timeCardState

```yaml
Type: String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TeamId
key: id of team

```yaml
Type: String
Parameter Sets: CreateExpanded, Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserId
.

```yaml
Type: String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
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
Type: SwitchParameter
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
Type: SwitchParameter
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphTimeCard

### Microsoft.Graph.PowerShell.Models.ITeamsIdentity

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphTimeCard

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphTimeCard>: timeCard
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[CreatedBy <IMicrosoftGraphIdentitySet>]`: identitySet
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Application <IMicrosoftGraphIdentity>]`: identity
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
      - `[Id <String>]`: Unique identifier for the identity.
    - `[Device <IMicrosoftGraphIdentity>]`: identity
    - `[User <IMicrosoftGraphIdentity>]`: identity
  - `[CreatedDateTime <DateTime?>]`: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
  - `[LastModifiedBy <IMicrosoftGraphIdentitySet>]`: identitySet
  - `[LastModifiedDateTime <DateTime?>]`: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
  - `[Id <String>]`: Read-only.
  - `[Breaks <IMicrosoftGraphTimeCardBreak[]>]`: 
    - `[BreakId <String>]`: 
    - `[End <IMicrosoftGraphTimeCardEvent>]`: timeCardEvent
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[AtApprovedLocation <Boolean?>]`: 
      - `[DateTime <DateTime?>]`: 
      - `[Notes <IMicrosoftGraphItemBody>]`: itemBody
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Content <String>]`: The content of the item.
        - `[ContentType <String>]`: bodyType
    - `[Notes <IMicrosoftGraphItemBody>]`: itemBody
    - `[Start <IMicrosoftGraphTimeCardEvent>]`: timeCardEvent
  - `[ClockInEvent <IMicrosoftGraphTimeCardEvent>]`: timeCardEvent
  - `[ClockOutEvent <IMicrosoftGraphTimeCardEvent>]`: timeCardEvent
  - `[ConfirmedBy <String>]`: confirmedBy
  - `[Notes <IMicrosoftGraphItemBody>]`: itemBody
  - `[OriginalEntry <IMicrosoftGraphTimeCardEntry>]`: timeCardEntry
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Breaks <IMicrosoftGraphTimeCardBreak[]>]`: 
    - `[ClockInEvent <IMicrosoftGraphTimeCardEvent>]`: timeCardEvent
    - `[ClockOutEvent <IMicrosoftGraphTimeCardEvent>]`: timeCardEvent
  - `[State <String>]`: timeCardState
  - `[UserId <String>]`: 

BREAKS <IMicrosoftGraphTimeCardBreak[]>: .
  - `[BreakId <String>]`: 
  - `[End <IMicrosoftGraphTimeCardEvent>]`: timeCardEvent
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[AtApprovedLocation <Boolean?>]`: 
    - `[DateTime <DateTime?>]`: 
    - `[Notes <IMicrosoftGraphItemBody>]`: itemBody
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Content <String>]`: The content of the item.
      - `[ContentType <String>]`: bodyType
  - `[Notes <IMicrosoftGraphItemBody>]`: itemBody
  - `[Start <IMicrosoftGraphTimeCardEvent>]`: timeCardEvent

CLOCKINEVENT <IMicrosoftGraphTimeCardEvent>: timeCardEvent
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[AtApprovedLocation <Boolean?>]`: 
  - `[DateTime <DateTime?>]`: 
  - `[Notes <IMicrosoftGraphItemBody>]`: itemBody
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Content <String>]`: The content of the item.
    - `[ContentType <String>]`: bodyType

CLOCKOUTEVENT <IMicrosoftGraphTimeCardEvent>: timeCardEvent
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[AtApprovedLocation <Boolean?>]`: 
  - `[DateTime <DateTime?>]`: 
  - `[Notes <IMicrosoftGraphItemBody>]`: itemBody
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Content <String>]`: The content of the item.
    - `[ContentType <String>]`: bodyType

CREATEDBY <IMicrosoftGraphIdentitySet>: identitySet
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Application <IMicrosoftGraphIdentity>]`: identity
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
    - `[Id <String>]`: Unique identifier for the identity.
  - `[Device <IMicrosoftGraphIdentity>]`: identity
  - `[User <IMicrosoftGraphIdentity>]`: identity

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
  - `[TeamworkTagId <String>]`: key: id of teamworkTag
  - `[TeamworkTagMemberId <String>]`: key: id of teamworkTagMember
  - `[TimeCardId <String>]`: key: id of timeCard
  - `[TimeOffId <String>]`: key: id of timeOff
  - `[TimeOffReasonId <String>]`: key: id of timeOffReason
  - `[TimeOffRequestId <String>]`: key: id of timeOffRequest
  - `[UserId <String>]`: key: id of user
  - `[UserScopeTeamsAppInstallationId <String>]`: key: id of userScopeTeamsAppInstallation
  - `[WorkforceIntegrationId <String>]`: key: id of workforceIntegration

LASTMODIFIEDBY <IMicrosoftGraphIdentitySet>: identitySet
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Application <IMicrosoftGraphIdentity>]`: identity
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
    - `[Id <String>]`: Unique identifier for the identity.
  - `[Device <IMicrosoftGraphIdentity>]`: identity
  - `[User <IMicrosoftGraphIdentity>]`: identity

NOTES <IMicrosoftGraphItemBody>: itemBody
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Content <String>]`: The content of the item.
  - `[ContentType <String>]`: bodyType

ORIGINALENTRY <IMicrosoftGraphTimeCardEntry>: timeCardEntry
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Breaks <IMicrosoftGraphTimeCardBreak[]>]`: 
    - `[BreakId <String>]`: 
    - `[End <IMicrosoftGraphTimeCardEvent>]`: timeCardEvent
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[AtApprovedLocation <Boolean?>]`: 
      - `[DateTime <DateTime?>]`: 
      - `[Notes <IMicrosoftGraphItemBody>]`: itemBody
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Content <String>]`: The content of the item.
        - `[ContentType <String>]`: bodyType
    - `[Notes <IMicrosoftGraphItemBody>]`: itemBody
    - `[Start <IMicrosoftGraphTimeCardEvent>]`: timeCardEvent
  - `[ClockInEvent <IMicrosoftGraphTimeCardEvent>]`: timeCardEvent
  - `[ClockOutEvent <IMicrosoftGraphTimeCardEvent>]`: timeCardEvent

## RELATED LINKS