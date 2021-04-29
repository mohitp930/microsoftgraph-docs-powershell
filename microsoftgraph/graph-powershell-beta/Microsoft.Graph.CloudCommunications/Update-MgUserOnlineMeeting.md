---
external help file: Microsoft.Graph.CloudCommunications-help.xml
Module Name: Microsoft.Graph.CloudCommunications
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.cloudcommunications/update-mguseronlinemeeting
schema: 2.0.0
---

# Update-MgUserOnlineMeeting

## SYNOPSIS
Update the navigation property onlineMeetings in users

## SYNTAX

### UpdateExpanded1 (Default)
```
Update-MgUserOnlineMeeting -OnlineMeetingId <String> -UserId <String> [-AccessLevel <String>]
 [-AdditionalProperties <Hashtable>] [-AllowedPresenters <String>] [-AlternativeRecordingInputFile <String>]
 [-AttendeeReportInputFile <String>] [-AudioConferencing <IMicrosoftGraphAudioConferencing>]
 [-BroadcastSettings <IMicrosoftGraphBroadcastMeetingSettings>] [-CanceledDateTime <DateTime>]
 [-Capabilities <String[]>] [-ChatInfo <IMicrosoftGraphChatInfo>] [-CreationDateTime <DateTime>]
 [-EndDateTime <DateTime>] [-EntryExitAnnouncement] [-ExpirationDateTime <DateTime>] [-ExternalId <String>]
 [-Id <String>] [-IsBroadcast] [-IsCancelled] [-IsEntryExitAnnounced]
 [-JoinInformation <IMicrosoftGraphItemBody>] [-JoinUrl <String>]
 [-LobbyBypassSettings <IMicrosoftGraphLobbyBypassSettings>]
 [-MeetingAttendanceReport <IMicrosoftGraphMeetingAttendanceReport>]
 [-Participants <IMicrosoftGraphMeetingParticipants1>] [-RecordingInputFile <String>]
 [-StartDateTime <DateTime>] [-Subject <String>] [-VideoTeleconferenceId <String>] [-PassThru] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### Update1
```
Update-MgUserOnlineMeeting -OnlineMeetingId <String> -UserId <String>
 -BodyParameter <IMicrosoftGraphOnlineMeeting1> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded1
```
Update-MgUserOnlineMeeting -InputObject <ICloudCommunicationsIdentity> [-AccessLevel <String>]
 [-AdditionalProperties <Hashtable>] [-AllowedPresenters <String>] [-AlternativeRecordingInputFile <String>]
 [-AttendeeReportInputFile <String>] [-AudioConferencing <IMicrosoftGraphAudioConferencing>]
 [-BroadcastSettings <IMicrosoftGraphBroadcastMeetingSettings>] [-CanceledDateTime <DateTime>]
 [-Capabilities <String[]>] [-ChatInfo <IMicrosoftGraphChatInfo>] [-CreationDateTime <DateTime>]
 [-EndDateTime <DateTime>] [-EntryExitAnnouncement] [-ExpirationDateTime <DateTime>] [-ExternalId <String>]
 [-Id <String>] [-IsBroadcast] [-IsCancelled] [-IsEntryExitAnnounced]
 [-JoinInformation <IMicrosoftGraphItemBody>] [-JoinUrl <String>]
 [-LobbyBypassSettings <IMicrosoftGraphLobbyBypassSettings>]
 [-MeetingAttendanceReport <IMicrosoftGraphMeetingAttendanceReport>]
 [-Participants <IMicrosoftGraphMeetingParticipants1>] [-RecordingInputFile <String>]
 [-StartDateTime <DateTime>] [-Subject <String>] [-VideoTeleconferenceId <String>] [-PassThru] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity1
```
Update-MgUserOnlineMeeting -InputObject <ICloudCommunicationsIdentity>
 -BodyParameter <IMicrosoftGraphOnlineMeeting1> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property onlineMeetings in users

## EXAMPLES

## PARAMETERS

### -AccessLevel
accessLevel

```yaml
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Type: Hashtable
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AlternativeRecordingInputFile
Input File for AlternativeRecording (The content stream of the alternative recording of a live event.
Read-only.)

```yaml
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AttendeeReportInputFile
Input File for AttendeeReport (The content stream of the attendee report of a live event.
Read-only.)

```yaml
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AudioConferencing
audioConferencing
To construct, see NOTES section for AUDIOCONFERENCING properties and create a hash table.

```yaml
Type: IMicrosoftGraphAudioConferencing
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
onlineMeeting
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphOnlineMeeting1
Parameter Sets: Update1, UpdateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -BroadcastSettings
broadcastMeetingSettings
To construct, see NOTES section for BROADCASTSETTINGS properties and create a hash table.

```yaml
Type: IMicrosoftGraphBroadcastMeetingSettings
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Type: DateTime
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Capabilities
The list of meeting capabilities.
Possible values are: questionAndAnswer,unknownFutureValue.

```yaml
Type: String[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ChatInfo
chatInfo
To construct, see NOTES section for CHATINFO properties and create a hash table.

```yaml
Type: IMicrosoftGraphChatInfo
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Type: DateTime
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Type: DateTime
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Type: SwitchParameter
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Type: DateTime
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Type: String
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
Type: String
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
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: ICloudCommunicationsIdentity
Parameter Sets: UpdateViaIdentityExpanded1, UpdateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -IsBroadcast
Indicates if this is a live event.

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Type: SwitchParameter
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsEntryExitAnnounced
Whether or not to announce when callers join or leave.

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -JoinInformation
itemBody
To construct, see NOTES section for JOININFORMATION properties and create a hash table.

```yaml
Type: IMicrosoftGraphItemBody
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LobbyBypassSettings
lobbyBypassSettings
To construct, see NOTES section for LOBBYBYPASSSETTINGS properties and create a hash table.

```yaml
Type: IMicrosoftGraphLobbyBypassSettings
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MeetingAttendanceReport
meetingAttendanceReport
To construct, see NOTES section for MEETINGATTENDANCEREPORT properties and create a hash table.

```yaml
Type: IMicrosoftGraphMeetingAttendanceReport
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OnlineMeetingId
key: id of onlineMeeting

```yaml
Type: String
Parameter Sets: UpdateExpanded1, Update1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Participants
meetingParticipants
To construct, see NOTES section for PARTICIPANTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphMeetingParticipants1
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PassThru
Returns true when the command succeeds

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RecordingInputFile
Input File for Recording (The content stream of the recording of a live event.
Read-only.)

```yaml
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Type: DateTime
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Type: String
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
Type: String
Parameter Sets: UpdateExpanded1, Update1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -VideoTeleconferenceId
The video teleconferencing ID.
Read-only.

```yaml
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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

### Microsoft.Graph.PowerShell.Models.ICloudCommunicationsIdentity

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphOnlineMeeting1

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


AUDIOCONFERENCING <IMicrosoftGraphAudioConferencing>: audioConferencing
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[ConferenceId <String>]`: The conference id of the online meeting.
  - `[DialinUrl <String>]`: A URL to the externally-accessible web page that contains dial-in information.
  - `[TollFreeNumber <String>]`: The toll-free number that connects to the Audio Conference Provider.
  - `[TollNumber <String>]`: The toll number that connects to the Audio Conference Provider.

BODYPARAMETER <IMicrosoftGraphOnlineMeeting1>: onlineMeeting
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[AccessLevel <String>]`: accessLevel
  - `[AllowedPresenters <String>]`: onlineMeetingPresenters
  - `[AlternativeRecording <Byte[]>]`: The content stream of the alternative recording of a live event. Read-only.
  - `[AttendeeReport <Byte[]>]`: The content stream of the attendee report of a live event. Read-only.
  - `[AudioConferencing <IMicrosoftGraphAudioConferencing>]`: audioConferencing
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[ConferenceId <String>]`: The conference id of the online meeting.
    - `[DialinUrl <String>]`: A URL to the externally-accessible web page that contains dial-in information.
    - `[TollFreeNumber <String>]`: The toll-free number that connects to the Audio Conference Provider.
    - `[TollNumber <String>]`: The toll number that connects to the Audio Conference Provider.
  - `[BroadcastSettings <IMicrosoftGraphBroadcastMeetingSettings>]`: broadcastMeetingSettings
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[AllowedAudience <String>]`: broadcastMeetingAudience
    - `[IsAttendeeReportEnabled <Boolean?>]`: Indicates whether attendee report is enabled for this live event. Default value is false.
    - `[IsQuestionAndAnswerEnabled <Boolean?>]`: Indicates whether Q&A is enabled for this live event. Default value is false.
    - `[IsRecordingEnabled <Boolean?>]`: Indicates whether recording is enabled for this live event. Default value is false.
    - `[IsVideoOnDemandEnabled <Boolean?>]`: Indicates whether video on demand is enabled for this live event. Default value is false.
  - `[CanceledDateTime <DateTime?>]`: 
  - `[Capabilities <String[]>]`: The list of meeting capabilities. Possible values are: questionAndAnswer,unknownFutureValue.
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
  - `[IsBroadcast <Boolean?>]`: Indicates if this is a live event.
  - `[IsCancelled <Boolean?>]`: 
  - `[IsEntryExitAnnounced <Boolean?>]`: Whether or not to announce when callers join or leave.
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
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[AttendanceRecords <IMicrosoftGraphAttendanceRecord[]>]`: 
      - `[AttendanceIntervals <IMicrosoftGraphAttendanceInterval[]>]`: 
        - `[DurationInSeconds <Int32?>]`: 
        - `[JoinDateTime <DateTime?>]`: 
        - `[LeaveDateTime <DateTime?>]`: 
      - `[EmailAddress <String>]`: 
      - `[Identity <IMicrosoftGraphIdentity>]`: identity
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
        - `[Id <String>]`: Unique identifier for the identity.
      - `[Role <String>]`: 
      - `[TotalAttendanceInSeconds <Int32?>]`: 
  - `[Participants <IMicrosoftGraphMeetingParticipants1>]`: meetingParticipants
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Attendees <IMicrosoftGraphMeetingParticipantInfo1[]>]`: 
      - `[Identity <IMicrosoftGraphIdentitySet>]`: identitySet
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Application <IMicrosoftGraphIdentity>]`: identity
        - `[Device <IMicrosoftGraphIdentity>]`: identity
        - `[User <IMicrosoftGraphIdentity>]`: identity
      - `[Role <String>]`: 
      - `[Upn <String>]`: User principal name of the participant.
    - `[Contributors <IMicrosoftGraphMeetingParticipantInfo1[]>]`: For broadcast meeting only.
    - `[Organizer <IMicrosoftGraphMeetingParticipantInfo1>]`: meetingParticipantInfo
    - `[Producers <IMicrosoftGraphMeetingParticipantInfo1[]>]`: For broadcast meeting only.
  - `[Recording <Byte[]>]`: The content stream of the recording of a live event. Read-only.
  - `[StartDateTime <DateTime?>]`: The meeting start time in UTC.
  - `[Subject <String>]`: The subject of the online meeting.
  - `[VideoTeleconferenceId <String>]`: The video teleconferencing ID. Read-only.

BROADCASTSETTINGS <IMicrosoftGraphBroadcastMeetingSettings>: broadcastMeetingSettings
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[AllowedAudience <String>]`: broadcastMeetingAudience
  - `[IsAttendeeReportEnabled <Boolean?>]`: Indicates whether attendee report is enabled for this live event. Default value is false.
  - `[IsQuestionAndAnswerEnabled <Boolean?>]`: Indicates whether Q&A is enabled for this live event. Default value is false.
  - `[IsRecordingEnabled <Boolean?>]`: Indicates whether recording is enabled for this live event. Default value is false.
  - `[IsVideoOnDemandEnabled <Boolean?>]`: Indicates whether video on demand is enabled for this live event. Default value is false.

CHATINFO <IMicrosoftGraphChatInfo>: chatInfo
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[MessageId <String>]`: The unique identifier for a message in a Microsoft Teams channel.
  - `[ReplyChainMessageId <String>]`: The ID of the reply message.
  - `[ThreadId <String>]`: The unique identifier for a thread in Microsoft Teams.

INPUTOBJECT <ICloudCommunicationsIdentity>: Identity Parameter
  - `[AudioRoutingGroupId <String>]`: key: id of audioRoutingGroup
  - `[CallId <String>]`: key: id of call
  - `[CallRecordId <String>]`: key: id of callRecord
  - `[CommsOperationId <String>]`: key: id of commsOperation
  - `[OnlineMeetingId <String>]`: key: id of onlineMeeting
  - `[ParticipantId <String>]`: key: id of participant
  - `[PresenceId <String>]`: key: id of presence
  - `[SessionId <String>]`: key: id of session
  - `[UserId <String>]`: key: id of user

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
  - `[AttendanceRecords <IMicrosoftGraphAttendanceRecord[]>]`: 
    - `[AttendanceIntervals <IMicrosoftGraphAttendanceInterval[]>]`: 
      - `[DurationInSeconds <Int32?>]`: 
      - `[JoinDateTime <DateTime?>]`: 
      - `[LeaveDateTime <DateTime?>]`: 
    - `[EmailAddress <String>]`: 
    - `[Identity <IMicrosoftGraphIdentity>]`: identity
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
      - `[Id <String>]`: Unique identifier for the identity.
    - `[Role <String>]`: 
    - `[TotalAttendanceInSeconds <Int32?>]`: 

PARTICIPANTS <IMicrosoftGraphMeetingParticipants1>: meetingParticipants
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Attendees <IMicrosoftGraphMeetingParticipantInfo1[]>]`: 
    - `[Identity <IMicrosoftGraphIdentitySet>]`: identitySet
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Application <IMicrosoftGraphIdentity>]`: identity
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
        - `[Id <String>]`: Unique identifier for the identity.
      - `[Device <IMicrosoftGraphIdentity>]`: identity
      - `[User <IMicrosoftGraphIdentity>]`: identity
    - `[Role <String>]`: 
    - `[Upn <String>]`: User principal name of the participant.
  - `[Contributors <IMicrosoftGraphMeetingParticipantInfo1[]>]`: For broadcast meeting only.
  - `[Organizer <IMicrosoftGraphMeetingParticipantInfo1>]`: meetingParticipantInfo
  - `[Producers <IMicrosoftGraphMeetingParticipantInfo1[]>]`: For broadcast meeting only.

## RELATED LINKS

## RELATED LINKS