---
external help file: Microsoft.Graph.CloudCommunications-help.xml
Module Name: Microsoft.Graph.CloudCommunications
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.cloudcommunications/update-mguseronlinemeetingregistration
schema: 2.0.0
---

# Update-MgUserOnlineMeetingRegistration

## SYNOPSIS
The registration that has been enabled for an online meeting.
One online meeting can only have one registration enabled.

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgUserOnlineMeetingRegistration -OnlineMeetingId <String> -UserId <String>
 [-AdditionalProperties <Hashtable>] [-AllowedRegistrant <String>]
 [-CustomQuestions <IMicrosoftGraphMeetingRegistrationQuestion[]>] [-Description <String>]
 [-EndDateTime <DateTime>] [-Id <String>] [-Registrants <IMicrosoftGraphMeetingRegistrantBase[]>]
 [-RegistrationPageViewCount <Int32>] [-RegistrationPageWebUrl <String>]
 [-Speakers <IMicrosoftGraphMeetingSpeaker[]>] [-StartDateTime <DateTime>] [-Subject <String>] [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Update
```
Update-MgUserOnlineMeetingRegistration -OnlineMeetingId <String> -UserId <String>
 -BodyParameter <IMicrosoftGraphMeetingRegistration> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgUserOnlineMeetingRegistration -InputObject <ICloudCommunicationsIdentity>
 [-AdditionalProperties <Hashtable>] [-AllowedRegistrant <String>]
 [-CustomQuestions <IMicrosoftGraphMeetingRegistrationQuestion[]>] [-Description <String>]
 [-EndDateTime <DateTime>] [-Id <String>] [-Registrants <IMicrosoftGraphMeetingRegistrantBase[]>]
 [-RegistrationPageViewCount <Int32>] [-RegistrationPageWebUrl <String>]
 [-Speakers <IMicrosoftGraphMeetingSpeaker[]>] [-StartDateTime <DateTime>] [-Subject <String>] [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgUserOnlineMeetingRegistration -InputObject <ICloudCommunicationsIdentity>
 -BodyParameter <IMicrosoftGraphMeetingRegistration> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
The registration that has been enabled for an online meeting.
One online meeting can only have one registration enabled.

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AllowedRegistrant
meetingAudience

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
meetingRegistration
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphMeetingRegistration
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CustomQuestions
Custom registration questions.
To construct, please use Get-Help -Online and see NOTES section for CUSTOMQUESTIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphMeetingRegistrationQuestion[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
The description of the meeting.

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Type: ICloudCommunicationsIdentity
Parameter Sets: UpdateViaIdentityExpanded, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -OnlineMeetingId
key: id of onlineMeeting

```yaml
Type: String
Parameter Sets: UpdateExpanded, Update
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
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Registrants
Registrants of the online meeting.
To construct, please use Get-Help -Online and see NOTES section for REGISTRANTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphMeetingRegistrantBase[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RegistrationPageViewCount
The number of times the registration page has been visited.
Read-only.

```yaml
Type: Int32
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RegistrationPageWebUrl
The URL of the registration page.
Read-only.

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Speakers
The meeting speaker's information.
To construct, please use Get-Help -Online and see NOTES section for SPEAKERS properties and create a hash table.

```yaml
Type: IMicrosoftGraphMeetingSpeaker[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Subject
The subject of the meeting.

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Parameter Sets: UpdateExpanded, Update
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

### Microsoft.Graph.PowerShell.Models.ICloudCommunicationsIdentity
### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMeetingRegistration
## OUTPUTS

### System.Boolean
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphMeetingRegistration>: meetingRegistration
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

CUSTOMQUESTIONS <IMicrosoftGraphMeetingRegistrationQuestion[]>: Custom registration questions.
  - `[Id <String>]`: Read-only.
  - `[AnswerInputType <String>]`: answerInputType
  - `[AnswerOptions <String[]>]`: Answer options when answerInputType is radioButton.
  - `[DisplayName <String>]`: Display name of the custom registration question.
  - `[IsRequired <Boolean?>]`: Indicates whether the question is required. Default value is false.

INPUTOBJECT <ICloudCommunicationsIdentity>: Identity Parameter
  - `[AttendanceRecordId <String>]`: key: id of attendanceRecord
  - `[AudioRoutingGroupId <String>]`: key: id of audioRoutingGroup
  - `[CallId <String>]`: key: id of call
  - `[CallRecordId <String>]`: key: id of callRecord
  - `[CommsOperationId <String>]`: key: id of commsOperation
  - `[MeetingAttendanceReportId <String>]`: key: id of meetingAttendanceReport
  - `[MeetingRegistrationQuestionId <String>]`: key: id of meetingRegistrationQuestion
  - `[OnlineMeetingId <String>]`: key: id of onlineMeeting
  - `[ParticipantId <String>]`: key: id of participant
  - `[PresenceId <String>]`: key: id of presence
  - `[SessionId <String>]`: key: id of session
  - `[UserId <String>]`: key: id of user

REGISTRANTS <IMicrosoftGraphMeetingRegistrantBase[]>: Registrants of the online meeting.
  - `[Id <String>]`: Read-only.
  - `[JoinWebUrl <String>]`: A unique web URL for the registrant to join the meeting. Read-only.

SPEAKERS <IMicrosoftGraphMeetingSpeaker[]>: The meeting speaker's information.
  - `[Bio <String>]`: Bio of the speaker.
  - `[DisplayName <String>]`: Display name of the speaker.

## RELATED LINKS