---
external help file: Microsoft.Graph.Compliance-help.xml
Module Name: Microsoft.Graph.Compliance
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.compliance/export-mgcomplianceediscoverycasereviewset
schema: 2.0.0
---

# Export-MgComplianceEdiscoveryCaseReviewSet

## SYNOPSIS
Invoke action export

## SYNTAX

### ExportExpanded (Default)
```
Export-MgComplianceEdiscoveryCaseReviewSet -CaseId <String> -ReviewSetId <String>
 [-AdditionalProperties <Hashtable>] [-AzureBlobContainer <String>] [-AzureBlobToken <String>]
 [-Description <String>] [-ExportOptions <String>] [-ExportStructure <String>] [-OutputName <String>]
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Export
```
Export-MgComplianceEdiscoveryCaseReviewSet -CaseId <String> -ReviewSetId <String>
 -BodyParameter <IPaths2D0MecComplianceEdiscoveryCasesCaseIdReviewsetsReviewsetIdMicrosoftGraphEdiscoveryExportPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ExportViaIdentityExpanded
```
Export-MgComplianceEdiscoveryCaseReviewSet -InputObject <IComplianceIdentity>
 [-AdditionalProperties <Hashtable>] [-AzureBlobContainer <String>] [-AzureBlobToken <String>]
 [-Description <String>] [-ExportOptions <String>] [-ExportStructure <String>] [-OutputName <String>]
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ExportViaIdentity
```
Export-MgComplianceEdiscoveryCaseReviewSet -InputObject <IComplianceIdentity>
 -BodyParameter <IPaths2D0MecComplianceEdiscoveryCasesCaseIdReviewsetsReviewsetIdMicrosoftGraphEdiscoveryExportPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action export

## EXAMPLES

### Example 1: Using the Export-MgComplianceEdiscoveryCaseReviewSet Cmdlet
```powershell
Import-Module Microsoft.Graph.Compliance
$params = @{
	OutputName = "2020-12-06 Contoso investigation export"
	Description = "Export for the Contoso investigation"
	ExportOptions = "originalFiles,fileInfo,tags"
	ExportStructure = "directory"
}
Export-MgComplianceEdiscoveryCaseReviewSet -CaseId $caseId -ReviewSetId $reviewSetId -BodyParameter $params
```

This example shows how to use the Export-MgComplianceEdiscoveryCaseReviewSet Cmdlet.
To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: ExportExpanded, ExportViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AzureBlobContainer
.

```yaml
Type: String
Parameter Sets: ExportExpanded, ExportViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AzureBlobToken
.

```yaml
Type: String
Parameter Sets: ExportExpanded, ExportViaIdentityExpanded
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
Type: IPaths2D0MecComplianceEdiscoveryCasesCaseIdReviewsetsReviewsetIdMicrosoftGraphEdiscoveryExportPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Export, ExportViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CaseId
The unique identifier of case

```yaml
Type: String
Parameter Sets: ExportExpanded, Export
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
.

```yaml
Type: String
Parameter Sets: ExportExpanded, ExportViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExportOptions
exportOptions

```yaml
Type: String
Parameter Sets: ExportExpanded, ExportViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExportStructure
exportFileStructure

```yaml
Type: String
Parameter Sets: ExportExpanded, ExportViaIdentityExpanded
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
Type: IComplianceIdentity
Parameter Sets: ExportViaIdentityExpanded, ExportViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -OutputName
.

```yaml
Type: String
Parameter Sets: ExportExpanded, ExportViaIdentityExpanded
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

### -ReviewSetId
The unique identifier of reviewSet

```yaml
Type: String
Parameter Sets: ExportExpanded, Export
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

### Microsoft.Graph.PowerShell.Models.IComplianceIdentity
### Microsoft.Graph.PowerShell.Models.IPaths2D0MecComplianceEdiscoveryCasesCaseIdReviewsetsReviewsetIdMicrosoftGraphEdiscoveryExportPostRequestbodyContentApplicationJsonSchema
## OUTPUTS

### System.Boolean
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER `<IPaths2D0MecComplianceEdiscoveryCasesCaseIdReviewsetsReviewsetIdMicrosoftGraphEdiscoveryExportPostRequestbodyContentApplicationJsonSchema>`: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[AzureBlobContainer <String>]`: 
  - `[AzureBlobToken <String>]`: 
  - `[Description <String>]`: 
  - `[ExportOptions <String>]`: exportOptions
  - `[ExportStructure <String>]`: exportFileStructure
  - `[OutputName <String>]`: 

INPUTOBJECT `<IComplianceIdentity>`: Identity Parameter
  - `[CaseId <String>]`: The unique identifier of case
  - `[CaseOperationId <String>]`: The unique identifier of caseOperation
  - `[CustodianId <String>]`: The unique identifier of custodian
  - `[DataSourceId <String>]`: The unique identifier of dataSource
  - `[LegalHoldId <String>]`: The unique identifier of legalHold
  - `[NoncustodialDataSourceId <String>]`: The unique identifier of noncustodialDataSource
  - `[ReviewSetId <String>]`: The unique identifier of reviewSet
  - `[ReviewSetQueryId <String>]`: The unique identifier of reviewSetQuery
  - `[SiteSourceId <String>]`: The unique identifier of siteSource
  - `[SourceCollectionId <String>]`: The unique identifier of sourceCollection
  - `[TagId <String>]`: The unique identifier of tag
  - `[TagId1 <String>]`: The unique identifier of tag
  - `[UnifiedGroupSourceId <String>]`: The unique identifier of unifiedGroupSource
  - `[UserSourceId <String>]`: The unique identifier of userSource

## RELATED LINKS
