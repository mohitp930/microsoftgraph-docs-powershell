---
external help file: Microsoft.Graph.Sites-help.xml
Module Name: Microsoft.Graph.Sites
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.sites/add-mgsitecontenttypecopyfromcontenttypehub
schema: 2.0.0
---

# Add-MgSiteContentTypeCopyFromContentTypeHub

## SYNOPSIS
Invoke action addCopyFromContentTypeHub

## SYNTAX

### AddExpanded1 (Default)
```
Add-MgSiteContentTypeCopyFromContentTypeHub -SiteId <String> [-AdditionalProperties <Hashtable>]
 [-ContentTypeId <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Add1
```
Add-MgSiteContentTypeCopyFromContentTypeHub -SiteId <String>
 -BodyParameter <IPathsRh5Nv3SitesSiteIdContenttypesMicrosoftGraphAddcopyfromcontenttypehubPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### AddViaIdentityExpanded1
```
Add-MgSiteContentTypeCopyFromContentTypeHub -InputObject <ISitesIdentity> [-AdditionalProperties <Hashtable>]
 [-ContentTypeId <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### AddViaIdentity1
```
Add-MgSiteContentTypeCopyFromContentTypeHub -InputObject <ISitesIdentity>
 -BodyParameter <IPathsRh5Nv3SitesSiteIdContenttypesMicrosoftGraphAddcopyfromcontenttypehubPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action addCopyFromContentTypeHub

## EXAMPLES

### Example 1: Synchronous pull
```powershell
Import-Module Microsoft.Graph.Sites

$params = @{
	ContentTypeId = "0x0101"
}

Add-MgSiteListContentTypeCopyFromContentTypeHub -SiteId $siteId -ListId $listId -BodyParameter $params
```

This example shows how to use the Add-MgSiteContentTypeCopyFromContentTypeHub Cmdlet.

To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).

### Example 2: Asynchronous pull
```powershell
Import-Module Microsoft.Graph.Sites

$params = @{
	ContentTypeId = "0x0101"
}

Add-MgSiteListContentTypeCopyFromContentTypeHub -SiteId $siteId -ListId $listId -BodyParameter $params
```

This example shows how to use the Add-MgSiteContentTypeCopyFromContentTypeHub Cmdlet.

To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: AddExpanded1, AddViaIdentityExpanded1
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
Type: IPathsRh5Nv3SitesSiteIdContenttypesMicrosoftGraphAddcopyfromcontenttypehubPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Add1, AddViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ContentTypeId
.

```yaml
Type: String
Parameter Sets: AddExpanded1, AddViaIdentityExpanded1
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
Type: ISitesIdentity
Parameter Sets: AddViaIdentityExpanded1, AddViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -SiteId
The unique identifier of site

```yaml
Type: String
Parameter Sets: AddExpanded1, Add1
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

### Microsoft.Graph.PowerShell.Models.IPathsRh5Nv3SitesSiteIdContenttypesMicrosoftGraphAddcopyfromcontenttypehubPostRequestbodyContentApplicationJsonSchema
### Microsoft.Graph.PowerShell.Models.ISitesIdentity
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphContentType
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER `<IPathsRh5Nv3SitesSiteIdContenttypesMicrosoftGraphAddcopyfromcontenttypehubPostRequestbodyContentApplicationJsonSchema>`: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[ContentTypeId <String>]`: 

INPUTOBJECT `<ISitesIdentity>`: Identity Parameter
  - `[BaseItemId <String>]`: The unique identifier of baseItem
  - `[BitlockerRecoveryKeyId <String>]`: The unique identifier of bitlockerRecoveryKey
  - `[ColumnDefinitionId <String>]`: The unique identifier of columnDefinition
  - `[ColumnLinkId <String>]`: The unique identifier of columnLink
  - `[ContentTypeId <String>]`: The unique identifier of contentType
  - `[ContentTypeId1 <String>]`: The unique identifier of contentType
  - `[DataLossPreventionPolicyId <String>]`: The unique identifier of dataLossPreventionPolicy
  - `[DocumentSetVersionId <String>]`: The unique identifier of documentSetVersion
  - `[DriveId <String>]`: The unique identifier of drive
  - `[EndDateTime <String>]`: Usage: endDateTime='{endDateTime}'
  - `[GroupId <String>]`: The unique identifier of group
  - `[GroupId1 <String>]`: The unique identifier of group
  - `[HorizontalSectionColumnId <String>]`: The unique identifier of horizontalSectionColumn
  - `[HorizontalSectionId <String>]`: The unique identifier of horizontalSection
  - `[IncludePersonalNotebooks <Boolean?>]`: Usage: includePersonalNotebooks={includePersonalNotebooks}
  - `[InformationProtectionLabelId <String>]`: The unique identifier of informationProtectionLabel
  - `[Interval <String>]`: Usage: interval='{interval}'
  - `[ItemActivityStatId <String>]`: The unique identifier of itemActivityStat
  - `[ListId <String>]`: The unique identifier of list
  - `[ListId1 <String>]`: Usage: listId='{listId}'
  - `[ListItemId <String>]`: The unique identifier of listItem
  - `[ListItemVersionId <String>]`: The unique identifier of listItemVersion
  - `[NotebookId <String>]`: The unique identifier of notebook
  - `[OnenotePageId <String>]`: The unique identifier of onenotePage
  - `[OnenoteSectionId <String>]`: The unique identifier of onenoteSection
  - `[Path <String>]`: Usage: path='{path}'
  - `[PermissionId <String>]`: The unique identifier of permission
  - `[RelationId <String>]`: The unique identifier of relation
  - `[RichLongRunningOperationId <String>]`: The unique identifier of richLongRunningOperation
  - `[SensitivityLabelId <String>]`: The unique identifier of sensitivityLabel
  - `[SensitivityLabelId1 <String>]`: The unique identifier of sensitivityLabel
  - `[SetId <String>]`: The unique identifier of set
  - `[SetId1 <String>]`: The unique identifier of set
  - `[SiteId <String>]`: The unique identifier of site
  - `[SiteId1 <String>]`: The unique identifier of site
  - `[SitePageId <String>]`: The unique identifier of sitePage
  - `[StartDateTime <String>]`: Usage: startDateTime='{startDateTime}'
  - `[StoreId <String>]`: The unique identifier of store
  - `[SubscriptionId <String>]`: The unique identifier of subscription
  - `[TermId <String>]`: The unique identifier of term
  - `[TermId1 <String>]`: The unique identifier of term
  - `[ThreatAssessmentRequestId <String>]`: The unique identifier of threatAssessmentRequest
  - `[ThreatAssessmentResultId <String>]`: The unique identifier of threatAssessmentResult
  - `[Token <String>]`: Usage: token='{token}'
  - `[UserId <String>]`: The unique identifier of user
  - `[WebPartId <String>]`: The unique identifier of webPart

## RELATED LINKS
