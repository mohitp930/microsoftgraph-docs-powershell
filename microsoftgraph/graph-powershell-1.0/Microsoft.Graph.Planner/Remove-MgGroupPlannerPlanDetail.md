---
external help file: Microsoft.Graph.Planner-help.xml
Module Name: Microsoft.Graph.Planner
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.planner/remove-mggroupplannerplandetail
schema: 2.0.0
---

# Remove-MgGroupPlannerPlanDetail

## SYNOPSIS
Delete navigation property details for groups

## SYNTAX

### Delete1 (Default)
```
Remove-MgGroupPlannerPlanDetail -GroupId <String> -PlannerPlanId <String> [-IfMatch <String>] [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### DeleteViaIdentity1
```
Remove-MgGroupPlannerPlanDetail -InputObject <IPlannerIdentity> [-IfMatch <String>] [-PassThru] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Delete navigation property details for groups

## EXAMPLES

### Example 1: Code snippet
```powershell
Import-Module Microsoft.Graph.Planner

$params = @{
	SharedWith = @{
		"6463a5ce-2119-4198-9f2a-628761df4a62" = $true
		"D95e6152-f683-4d78-9ff5-67ad180fea4a" = $false
	}
	CategoryDescriptions = @{
		Category1 = "Indoors"
		Category3 = $null
	}
}

Update-MgPlannerPlanDetail -PlannerPlanId $plannerPlanId -BodyParameter $params
```

This example shows how to use the Remove-MgGroupPlannerPlanDetail Cmdlet.

To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).

## PARAMETERS

### -GroupId
The unique identifier of group

```yaml
Type: String
Parameter Sets: Delete1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IfMatch
ETag

```yaml
Type: String
Parameter Sets: (All)
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
Type: IPlannerIdentity
Parameter Sets: DeleteViaIdentity1
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
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PlannerPlanId
The unique identifier of plannerPlan

```yaml
Type: String
Parameter Sets: Delete1
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

### Microsoft.Graph.PowerShell.Models.IPlannerIdentity
## OUTPUTS

### System.Boolean
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


INPUTOBJECT `<IPlannerIdentity>`: Identity Parameter
  - `[GroupId <String>]`: The unique identifier of group
  - `[PlannerBucketId <String>]`: The unique identifier of plannerBucket
  - `[PlannerDeltaId <String>]`: The unique identifier of plannerDelta
  - `[PlannerPlanId <String>]`: The unique identifier of plannerPlan
  - `[PlannerRosterId <String>]`: The unique identifier of plannerRoster
  - `[PlannerRosterMemberId <String>]`: The unique identifier of plannerRosterMember
  - `[PlannerTaskId <String>]`: The unique identifier of plannerTask
  - `[UserId <String>]`: The unique identifier of user

## RELATED LINKS
