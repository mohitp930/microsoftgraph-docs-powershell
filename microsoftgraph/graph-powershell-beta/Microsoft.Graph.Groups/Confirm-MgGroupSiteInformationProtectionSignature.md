---
external help file: Microsoft.Graph.Groups-help.xml
Module Name: Microsoft.Graph.Groups
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.groups/confirm-mggroupsiteinformationprotectionsignature
schema: 2.0.0
---

# Confirm-MgGroupSiteInformationProtectionSignature

## SYNOPSIS
Invoke action verifySignature

## SYNTAX

### VerifyExpanded (Default)
```
Confirm-MgGroupSiteInformationProtectionSignature -GroupId <String> -SiteId <String>
 [-AdditionalProperties <Hashtable>] [-DigestInputFile <String>] [-SignatureInputFile <String>]
 [-SigningKeyId <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Verify
```
Confirm-MgGroupSiteInformationProtectionSignature -GroupId <String> -SiteId <String>
 -BodyParameter <IPaths1Gvcs06GroupsGroupIdSitesSiteIdInformationprotectionMicrosoftGraphVerifysignaturePostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### VerifyViaIdentityExpanded
```
Confirm-MgGroupSiteInformationProtectionSignature -InputObject <IGroupsIdentity>
 [-AdditionalProperties <Hashtable>] [-DigestInputFile <String>] [-SignatureInputFile <String>]
 [-SigningKeyId <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### VerifyViaIdentity
```
Confirm-MgGroupSiteInformationProtectionSignature -InputObject <IGroupsIdentity>
 -BodyParameter <IPaths1Gvcs06GroupsGroupIdSitesSiteIdInformationprotectionMicrosoftGraphVerifysignaturePostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action verifySignature

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: VerifyExpanded, VerifyViaIdentityExpanded
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
Type: IPaths1Gvcs06GroupsGroupIdSitesSiteIdInformationprotectionMicrosoftGraphVerifysignaturePostRequestbodyContentApplicationJsonSchema
Parameter Sets: Verify, VerifyViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DigestInputFile
Input File for Digest (.)

```yaml
Type: String
Parameter Sets: VerifyExpanded, VerifyViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GroupId
The unique identifier of group

```yaml
Type: String
Parameter Sets: VerifyExpanded, Verify
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, please use Get-Help -Online and see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IGroupsIdentity
Parameter Sets: VerifyViaIdentityExpanded, VerifyViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -SignatureInputFile
Input File for Signature (.)

```yaml
Type: String
Parameter Sets: VerifyExpanded, VerifyViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SigningKeyId
.

```yaml
Type: String
Parameter Sets: VerifyExpanded, VerifyViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SiteId
The unique identifier of site

```yaml
Type: String
Parameter Sets: VerifyExpanded, Verify
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

### Microsoft.Graph.PowerShell.Models.IGroupsIdentity
### Microsoft.Graph.PowerShell.Models.IPaths1Gvcs06GroupsGroupIdSitesSiteIdInformationprotectionMicrosoftGraphVerifysignaturePostRequestbodyContentApplicationJsonSchema
## OUTPUTS

### System.Boolean
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER `<IPaths1Gvcs06GroupsGroupIdSitesSiteIdInformationprotectionMicrosoftGraphVerifysignaturePostRequestbodyContentApplicationJsonSchema>`: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Digest <Byte[]>]`: 
  - `[Signature <Byte[]>]`: 
  - `[SigningKeyId <String>]`: 

INPUTOBJECT `<IGroupsIdentity>`: Identity Parameter
  - `[AttachmentId <String>]`: The unique identifier of attachment
  - `[ContentTypeId <String>]`: The unique identifier of contentType
  - `[ConversationId <String>]`: The unique identifier of conversation
  - `[ConversationThreadId <String>]`: The unique identifier of conversationThread
  - `[DirectoryObjectId <String>]`: The unique identifier of directoryObject
  - `[DirectorySettingId <String>]`: The unique identifier of directorySetting
  - `[DocumentSetVersionId <String>]`: The unique identifier of documentSetVersion
  - `[DriveId <String>]`: The unique identifier of drive
  - `[DriveItemId <String>]`: The unique identifier of driveItem
  - `[DriveItemVersionId <String>]`: The unique identifier of driveItemVersion
  - `[EndDateTime <String>]`: Usage: endDateTime='{endDateTime}'
  - `[EndpointId <String>]`: The unique identifier of endpoint
  - `[EventId <String>]`: The unique identifier of event
  - `[ExtensionId <String>]`: The unique identifier of extension
  - `[GroupId <String>]`: The unique identifier of group
  - `[GroupLifecyclePolicyId <String>]`: The unique identifier of groupLifecyclePolicy
  - `[GroupSettingId <String>]`: The unique identifier of groupSetting
  - `[HorizontalSectionColumnId <String>]`: The unique identifier of horizontalSectionColumn
  - `[HorizontalSectionId <String>]`: The unique identifier of horizontalSection
  - `[IncludePersonalNotebooks <Boolean?>]`: Usage: includePersonalNotebooks={includePersonalNotebooks}
  - `[Interval <String>]`: Usage: interval='{interval}'
  - `[ListId <String>]`: The unique identifier of list
  - `[ListId1 <String>]`: Usage: listId='{listId}'
  - `[ListItemId <String>]`: The unique identifier of listItem
  - `[ListItemVersionId <String>]`: The unique identifier of listItemVersion
  - `[MentionId <String>]`: The unique identifier of mention
  - `[MultiValueLegacyExtendedPropertyId <String>]`: The unique identifier of multiValueLegacyExtendedProperty
  - `[NotebookId <String>]`: The unique identifier of notebook
  - `[OnenotePageId <String>]`: The unique identifier of onenotePage
  - `[OnenoteSectionId <String>]`: The unique identifier of onenoteSection
  - `[Path <String>]`: Usage: path='{path}'
  - `[PermissionId <String>]`: The unique identifier of permission
  - `[PlannerBucketId <String>]`: The unique identifier of plannerBucket
  - `[PlannerPlanId <String>]`: The unique identifier of plannerPlan
  - `[PostId <String>]`: The unique identifier of post
  - `[ProfilePhotoId <String>]`: The unique identifier of profilePhoto
  - `[Q <String>]`: Usage: q='{q}'
  - `[ResourceSpecificPermissionGrantId <String>]`: The unique identifier of resourceSpecificPermissionGrant
  - `[SensitivityLabelId <String>]`: The unique identifier of sensitivityLabel
  - `[SingleValueLegacyExtendedPropertyId <String>]`: The unique identifier of singleValueLegacyExtendedProperty
  - `[SiteId <String>]`: The unique identifier of site
  - `[SitePageId <String>]`: The unique identifier of sitePage
  - `[StartDateTime <String>]`: Usage: startDateTime='{startDateTime}'
  - `[SubscriptionId <String>]`: The unique identifier of subscription
  - `[Token <String>]`: Usage: token='{token}'
  - `[User <String>]`: Usage: User='{User}'
  - `[UserId <String>]`: The unique identifier of user
  - `[WebPartId <String>]`: The unique identifier of webPart

## RELATED LINKS
