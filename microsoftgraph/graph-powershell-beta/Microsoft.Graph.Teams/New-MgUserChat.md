---
external help file: Microsoft.Graph.Teams-help.xml
Module Name: Microsoft.Graph.Teams
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.teams/new-mguserchat
schema: 2.0.0
---

# New-MgUserChat

## SYNOPSIS
Create new navigation property to chats for users

## SYNTAX

### CreateExpanded (Default)
```
New-MgUserChat -UserId <String> [-AdditionalProperties <Hashtable>] [-ChatType <String>]
 [-CreatedDateTime <DateTime>] [-Id <String>] [-InstalledApps <IMicrosoftGraphTeamsAppInstallation[]>]
 [-LastUpdatedDateTime <DateTime>] [-Members <IMicrosoftGraphConversationMember[]>]
 [-Messages <IMicrosoftGraphChatMessage[]>]
 [-PermissionGrants <IMicrosoftGraphResourceSpecificPermissionGrant[]>] [-Tabs <IMicrosoftGraphTeamsTab[]>]
 [-Topic <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgUserChat -UserId <String> -BodyParameter <IMicrosoftGraphChat> [-WhatIf] [-Confirm] [<CommonParameters>]
```

### CreateViaIdentityExpanded
```
New-MgUserChat -InputObject <ITeamsIdentity> [-AdditionalProperties <Hashtable>] [-ChatType <String>]
 [-CreatedDateTime <DateTime>] [-Id <String>] [-InstalledApps <IMicrosoftGraphTeamsAppInstallation[]>]
 [-LastUpdatedDateTime <DateTime>] [-Members <IMicrosoftGraphConversationMember[]>]
 [-Messages <IMicrosoftGraphChatMessage[]>]
 [-PermissionGrants <IMicrosoftGraphResourceSpecificPermissionGrant[]>] [-Tabs <IMicrosoftGraphTeamsTab[]>]
 [-Topic <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### CreateViaIdentity
```
New-MgUserChat -InputObject <ITeamsIdentity> -BodyParameter <IMicrosoftGraphChat> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to chats for users

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
chat
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphChat
Parameter Sets: Create, CreateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ChatType
chatType

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

### -CreatedDateTime
Date and time at which the chat was created.
Read-only.

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

### -InstalledApps
A collection of all the apps in the chat.
Nullable.
To construct, see NOTES section for INSTALLEDAPPS properties and create a hash table.

```yaml
Type: IMicrosoftGraphTeamsAppInstallation[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LastUpdatedDateTime
Date and time at which the chat was renamed or list of members were last changed.
Read-only.

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

### -Members
A collection of all the members in the chat.
Nullable.
To construct, see NOTES section for MEMBERS properties and create a hash table.

```yaml
Type: IMicrosoftGraphConversationMember[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Messages
A collection of all the messages in the chat.
Nullable.
To construct, see NOTES section for MESSAGES properties and create a hash table.

```yaml
Type: IMicrosoftGraphChatMessage[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PermissionGrants
A collection of permissions granted to apps for the chat.
To construct, see NOTES section for PERMISSIONGRANTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphResourceSpecificPermissionGrant[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Tabs
.
To construct, see NOTES section for TABS properties and create a hash table.

```yaml
Type: IMicrosoftGraphTeamsTab[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Topic
(Optional) Subject or topic for the chat.
Only available for group chats.

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

### -UserId
key: id of user

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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphChat

### Microsoft.Graph.PowerShell.Models.ITeamsIdentity

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphChat

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphChat>: chat
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[ChatType <String>]`: chatType
  - `[CreatedDateTime <DateTime?>]`: Date and time at which the chat was created. Read-only.
  - `[InstalledApps <IMicrosoftGraphTeamsAppInstallation[]>]`: A collection of all the apps in the chat. Nullable.
    - `[Id <String>]`: Read-only.
    - `[TeamsApp <IMicrosoftGraphTeamsApp>]`: teamsApp
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[AppDefinitions <IMicrosoftGraphTeamsAppDefinition[]>]`: The details for each version of the app.
        - `[Id <String>]`: Read-only.
        - `[AllowedInstallationScopes <String>]`: teamsAppInstallationScopes
        - `[AzureAdAppId <String>]`: The WebApplicationInfo.id from the Teams App manifest.
        - `[Bot <IMicrosoftGraphTeamworkBot>]`: teamworkBot
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[Id <String>]`: Read-only.
        - `[CreatedBy <IMicrosoftGraphIdentitySet>]`: identitySet
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[Application <IMicrosoftGraphIdentity>]`: identity
            - `[(Any) <Object>]`: This indicates any property can be added to this object.
            - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
            - `[Id <String>]`: Unique identifier for the identity.
          - `[Device <IMicrosoftGraphIdentity>]`: identity
          - `[User <IMicrosoftGraphIdentity>]`: identity
        - `[Description <String>]`: Verbose description of the application.
        - `[DisplayName <String>]`: The name of the app provided by the app developer.
        - `[LastModifiedDateTime <DateTime?>]`: 
        - `[PublishingState <String>]`: teamsAppPublishingState
        - `[Shortdescription <String>]`: 
        - `[TeamsAppId <String>]`: The id from the Teams App manifest.
        - `[Version <String>]`: The version number of the application.
      - `[DisplayName <String>]`: The name of the catalog app provided by the app developer in the Microsoft Teams zip app package.
      - `[DistributionMethod <String>]`: teamsAppDistributionMethod
      - `[ExternalId <String>]`: The ID of the catalog provided by the app developer in the Microsoft Teams zip app package.
    - `[TeamsAppDefinition <IMicrosoftGraphTeamsAppDefinition>]`: teamsAppDefinition
  - `[LastUpdatedDateTime <DateTime?>]`: Date and time at which the chat was renamed or list of members were last changed. Read-only.
  - `[Members <IMicrosoftGraphConversationMember[]>]`: A collection of all the members in the chat. Nullable.
    - `[Id <String>]`: Read-only.
    - `[DisplayName <String>]`: The display name of the user.
    - `[Roles <String[]>]`: The roles for that user.
    - `[VisibleHistoryStartDateTime <DateTime?>]`: The timestamp denoting how far back a conversation's history is shared with the conversation member. This property is settable only for members of a chat.
  - `[Messages <IMicrosoftGraphChatMessage[]>]`: A collection of all the messages in the chat. Nullable.
    - `[Id <String>]`: Read-only.
    - `[Attachments <IMicrosoftGraphChatMessageAttachment[]>]`: Attached files. Attachments are currently read-only - sending attachments is not supported.
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
    - `[From <IMicrosoftGraphIdentitySet>]`: identitySet
    - `[HostedContents <IMicrosoftGraphChatMessageHostedContent[]>]`: Content in a message hosted by Microsoft Teams e.g. images, code snippets etc.
      - `[ContentBytes <Byte[]>]`: Write only. Bytes for the hosted content (such as images).
      - `[ContentType <String>]`: Write only. Content type, such as image/png, image/jpg.
      - `[Id <String>]`: Read-only.
    - `[Importance <String>]`: 
    - `[LastEditedDateTime <DateTime?>]`: Read only. Timestamp when edits to the chat message were made. Triggers an 'Edited' flag in the Teams UI. If no edits are made the value is null.
    - `[LastModifiedDateTime <DateTime?>]`: Read only. Timestamp when the chat message is created (initial setting) or modified, including when a reaction is added or removed.
    - `[Locale <String>]`: Locale of the chat message set by the client. Always set to en-us.
    - `[Mentions <IMicrosoftGraphChatMessageMention[]>]`: List of entities mentioned in the chat message. Currently supports user, bot, team, channel.
      - `[Id <Int32?>]`: Index of an entity being mentioned in the specified chatMessage. Matches the {index} value in the corresponding <at id='{index}'> tag in the message body.
      - `[MentionText <String>]`: String used to represent the mention. For example, a user's display name, a team name.
      - `[Mentioned <IMicrosoftGraphIdentitySet>]`: identitySet
    - `[MessageType <String>]`: 
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
      - `[User <IMicrosoftGraphIdentitySet>]`: identitySet
    - `[Replies <IMicrosoftGraphChatMessage[]>]`: Replies for a specified message.
    - `[ReplyToId <String>]`: Read-only. ID of the parent chat message or root chat message of the thread. (Only applies to chat messages in channels, not chats.)
    - `[Subject <String>]`: The subject of the chat message, in plaintext.
    - `[Summary <String>]`: Summary text of the chat message that could be used for push notifications and summary views or fall back views. Only applies to channel chat messages, not chat messages in a chat.
    - `[WebUrl <String>]`: Read-only. Link to the message in Microsoft Teams.
  - `[PermissionGrants <IMicrosoftGraphResourceSpecificPermissionGrant[]>]`: A collection of permissions granted to apps for the chat.
    - `[DeletedDateTime <DateTime?>]`: 
    - `[Id <String>]`: Read-only.
    - `[ClientAppId <String>]`: ID of the service principal of the Azure AD app that has been granted access. Read-only.
    - `[ClientId <String>]`: ID of the Azure AD app that has been granted access. Read-only.
    - `[Permission <String>]`: The name of the permission. Read-only.
    - `[PermissionType <String>]`: The type of permission. Possible values are: Application,Delegated. Read-only.
    - `[ResourceAppId <String>]`: ID of the Azure AD app that is hosting the resource. Read-only.
  - `[Tabs <IMicrosoftGraphTeamsTab[]>]`: 
    - `[Id <String>]`: Read-only.
    - `[Configuration <IMicrosoftGraphTeamsTabConfiguration>]`: teamsTabConfiguration
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[ContentUrl <String>]`: Url used for rendering tab contents in Teams. Required.
      - `[EntityId <String>]`: Identifier for the entity hosted by the tab provider.
      - `[RemoveUrl <String>]`: Url called by Teams client when a Tab is removed using the Teams Client.
      - `[WebsiteUrl <String>]`: Url for showing tab contents outside of Teams.
    - `[DisplayName <String>]`: Name of the tab.
    - `[MessageId <String>]`: 
    - `[SortOrderIndex <String>]`: Index of the order used for sorting tabs.
    - `[TeamsApp <IMicrosoftGraphTeamsApp>]`: teamsApp
    - `[TeamsAppId <String>]`: 
    - `[WebUrl <String>]`: Deep link URL of the tab instance. Read only.
  - `[Topic <String>]`: (Optional) Subject or topic for the chat. Only available for group chats.

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

INSTALLEDAPPS <IMicrosoftGraphTeamsAppInstallation[]>: A collection of all the apps in the chat. Nullable.
  - `[Id <String>]`: Read-only.
  - `[TeamsApp <IMicrosoftGraphTeamsApp>]`: teamsApp
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[AppDefinitions <IMicrosoftGraphTeamsAppDefinition[]>]`: The details for each version of the app.
      - `[Id <String>]`: Read-only.
      - `[AllowedInstallationScopes <String>]`: teamsAppInstallationScopes
      - `[AzureAdAppId <String>]`: The WebApplicationInfo.id from the Teams App manifest.
      - `[Bot <IMicrosoftGraphTeamworkBot>]`: teamworkBot
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
      - `[CreatedBy <IMicrosoftGraphIdentitySet>]`: identitySet
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Application <IMicrosoftGraphIdentity>]`: identity
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
          - `[Id <String>]`: Unique identifier for the identity.
        - `[Device <IMicrosoftGraphIdentity>]`: identity
        - `[User <IMicrosoftGraphIdentity>]`: identity
      - `[Description <String>]`: Verbose description of the application.
      - `[DisplayName <String>]`: The name of the app provided by the app developer.
      - `[LastModifiedDateTime <DateTime?>]`: 
      - `[PublishingState <String>]`: teamsAppPublishingState
      - `[Shortdescription <String>]`: 
      - `[TeamsAppId <String>]`: The id from the Teams App manifest.
      - `[Version <String>]`: The version number of the application.
    - `[DisplayName <String>]`: The name of the catalog app provided by the app developer in the Microsoft Teams zip app package.
    - `[DistributionMethod <String>]`: teamsAppDistributionMethod
    - `[ExternalId <String>]`: The ID of the catalog provided by the app developer in the Microsoft Teams zip app package.
  - `[TeamsAppDefinition <IMicrosoftGraphTeamsAppDefinition>]`: teamsAppDefinition

MEMBERS <IMicrosoftGraphConversationMember[]>: A collection of all the members in the chat. Nullable.
  - `[Id <String>]`: Read-only.
  - `[DisplayName <String>]`: The display name of the user.
  - `[Roles <String[]>]`: The roles for that user.
  - `[VisibleHistoryStartDateTime <DateTime?>]`: The timestamp denoting how far back a conversation's history is shared with the conversation member. This property is settable only for members of a chat.

MESSAGES <IMicrosoftGraphChatMessage[]>: A collection of all the messages in the chat. Nullable.
  - `[Id <String>]`: Read-only.
  - `[Attachments <IMicrosoftGraphChatMessageAttachment[]>]`: Attached files. Attachments are currently read-only - sending attachments is not supported.
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
  - `[From <IMicrosoftGraphIdentitySet>]`: identitySet
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Application <IMicrosoftGraphIdentity>]`: identity
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
      - `[Id <String>]`: Unique identifier for the identity.
    - `[Device <IMicrosoftGraphIdentity>]`: identity
    - `[User <IMicrosoftGraphIdentity>]`: identity
  - `[HostedContents <IMicrosoftGraphChatMessageHostedContent[]>]`: Content in a message hosted by Microsoft Teams e.g. images, code snippets etc.
    - `[ContentBytes <Byte[]>]`: Write only. Bytes for the hosted content (such as images).
    - `[ContentType <String>]`: Write only. Content type, such as image/png, image/jpg.
    - `[Id <String>]`: Read-only.
  - `[Importance <String>]`: 
  - `[LastEditedDateTime <DateTime?>]`: Read only. Timestamp when edits to the chat message were made. Triggers an 'Edited' flag in the Teams UI. If no edits are made the value is null.
  - `[LastModifiedDateTime <DateTime?>]`: Read only. Timestamp when the chat message is created (initial setting) or modified, including when a reaction is added or removed.
  - `[Locale <String>]`: Locale of the chat message set by the client. Always set to en-us.
  - `[Mentions <IMicrosoftGraphChatMessageMention[]>]`: List of entities mentioned in the chat message. Currently supports user, bot, team, channel.
    - `[Id <Int32?>]`: Index of an entity being mentioned in the specified chatMessage. Matches the {index} value in the corresponding <at id='{index}'> tag in the message body.
    - `[MentionText <String>]`: String used to represent the mention. For example, a user's display name, a team name.
    - `[Mentioned <IMicrosoftGraphIdentitySet>]`: identitySet
  - `[MessageType <String>]`: 
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
    - `[User <IMicrosoftGraphIdentitySet>]`: identitySet
  - `[Replies <IMicrosoftGraphChatMessage[]>]`: Replies for a specified message.
  - `[ReplyToId <String>]`: Read-only. ID of the parent chat message or root chat message of the thread. (Only applies to chat messages in channels, not chats.)
  - `[Subject <String>]`: The subject of the chat message, in plaintext.
  - `[Summary <String>]`: Summary text of the chat message that could be used for push notifications and summary views or fall back views. Only applies to channel chat messages, not chat messages in a chat.
  - `[WebUrl <String>]`: Read-only. Link to the message in Microsoft Teams.

PERMISSIONGRANTS <IMicrosoftGraphResourceSpecificPermissionGrant[]>: A collection of permissions granted to apps for the chat.
  - `[DeletedDateTime <DateTime?>]`: 
  - `[Id <String>]`: Read-only.
  - `[ClientAppId <String>]`: ID of the service principal of the Azure AD app that has been granted access. Read-only.
  - `[ClientId <String>]`: ID of the Azure AD app that has been granted access. Read-only.
  - `[Permission <String>]`: The name of the permission. Read-only.
  - `[PermissionType <String>]`: The type of permission. Possible values are: Application,Delegated. Read-only.
  - `[ResourceAppId <String>]`: ID of the Azure AD app that is hosting the resource. Read-only.

TABS <IMicrosoftGraphTeamsTab[]>: .
  - `[Id <String>]`: Read-only.
  - `[Configuration <IMicrosoftGraphTeamsTabConfiguration>]`: teamsTabConfiguration
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[ContentUrl <String>]`: Url used for rendering tab contents in Teams. Required.
    - `[EntityId <String>]`: Identifier for the entity hosted by the tab provider.
    - `[RemoveUrl <String>]`: Url called by Teams client when a Tab is removed using the Teams Client.
    - `[WebsiteUrl <String>]`: Url for showing tab contents outside of Teams.
  - `[DisplayName <String>]`: Name of the tab.
  - `[MessageId <String>]`: 
  - `[SortOrderIndex <String>]`: Index of the order used for sorting tabs.
  - `[TeamsApp <IMicrosoftGraphTeamsApp>]`: teamsApp
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[AppDefinitions <IMicrosoftGraphTeamsAppDefinition[]>]`: The details for each version of the app.
      - `[Id <String>]`: Read-only.
      - `[AllowedInstallationScopes <String>]`: teamsAppInstallationScopes
      - `[AzureAdAppId <String>]`: The WebApplicationInfo.id from the Teams App manifest.
      - `[Bot <IMicrosoftGraphTeamworkBot>]`: teamworkBot
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
      - `[CreatedBy <IMicrosoftGraphIdentitySet>]`: identitySet
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Application <IMicrosoftGraphIdentity>]`: identity
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
          - `[Id <String>]`: Unique identifier for the identity.
        - `[Device <IMicrosoftGraphIdentity>]`: identity
        - `[User <IMicrosoftGraphIdentity>]`: identity
      - `[Description <String>]`: Verbose description of the application.
      - `[DisplayName <String>]`: The name of the app provided by the app developer.
      - `[LastModifiedDateTime <DateTime?>]`: 
      - `[PublishingState <String>]`: teamsAppPublishingState
      - `[Shortdescription <String>]`: 
      - `[TeamsAppId <String>]`: The id from the Teams App manifest.
      - `[Version <String>]`: The version number of the application.
    - `[DisplayName <String>]`: The name of the catalog app provided by the app developer in the Microsoft Teams zip app package.
    - `[DistributionMethod <String>]`: teamsAppDistributionMethod
    - `[ExternalId <String>]`: The ID of the catalog provided by the app developer in the Microsoft Teams zip app package.
  - `[TeamsAppId <String>]`: 
  - `[WebUrl <String>]`: Deep link URL of the tab instance. Read only.

## RELATED LINKS

## RELATED LINKS