---
external help file: Microsoft.Graph.DeviceManagement-help.xml
Module Name: Microsoft.Graph.DeviceManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement/new-mgdevicemanagementassignmentfilter
schema: 2.0.0
---

# New-MgDeviceManagementAssignmentFilter

## SYNOPSIS
Create new navigation property to assignmentFilters for deviceManagement

## SYNTAX

### CreateExpanded (Default)
```
New-MgDeviceManagementAssignmentFilter [-AdditionalProperties <Hashtable>]
 [-AssignmentFilterManagementType <AssignmentFilterManagementType>] [-CreatedDateTime <DateTime>]
 [-Description <String>] [-DisplayName <String>] [-Id <String>] [-LastModifiedDateTime <DateTime>]
 [-Payloads <IMicrosoftGraphPayloadByFilter[]>] [-Platform <DevicePlatformType>] [-RoleScopeTags <String[]>]
 [-Rule <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgDeviceManagementAssignmentFilter -BodyParameter <IMicrosoftGraphDeviceAndAppManagementAssignmentFilter>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to assignmentFilters for deviceManagement

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AssignmentFilterManagementType
Supported filter management types whether its devices or apps.

```yaml
Type: AssignmentFilterManagementType
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
A class containing the properties used for Assignment Filter.
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceAndAppManagementAssignmentFilter
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CreatedDateTime
The creation time of the assignment filter.
The value cannot be modified and is automatically populated during new assignment filter process.
The timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'.

```yaml
Type: DateTime
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
Optional description of the Assignment Filter.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
The name of the Assignment Filter.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
The unique idenfier for an entity.
Read-only.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LastModifiedDateTime
Last modified time of the Assignment Filter.
The timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'

```yaml
Type: DateTime
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Payloads
Indicates associated assignments for a specific filter.
To construct, please use Get-Help -Online and see NOTES section for PAYLOADS properties and create a hash table.

```yaml
Type: IMicrosoftGraphPayloadByFilter[]
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Platform
Supported platform types.

```yaml
Type: DevicePlatformType
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RoleScopeTags
Indicates role scope tags assigned for the assignment filter.

```yaml
Type: String[]
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Rule
Rule definition of the assignment filter.

```yaml
Type: String
Parameter Sets: CreateExpanded
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDeviceAndAppManagementAssignmentFilter
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDeviceAndAppManagementAssignmentFilter
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER `<IMicrosoftGraphDeviceAndAppManagementAssignmentFilter>`: A class containing the properties used for Assignment Filter.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: The unique idenfier for an entity. Read-only.
  - `[AssignmentFilterManagementType <AssignmentFilterManagementType?>]`: Supported filter management types whether its devices or apps.
  - `[CreatedDateTime <DateTime?>]`: The creation time of the assignment filter. The value cannot be modified and is automatically populated during new assignment filter process. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'.
  - `[Description <String>]`: Optional description of the Assignment Filter.
  - `[DisplayName <String>]`: The name of the Assignment Filter.
  - `[LastModifiedDateTime <DateTime?>]`: Last modified time of the Assignment Filter. The timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'
  - `[Payloads <IMicrosoftGraphPayloadByFilter[]>]`: Indicates associated assignments for a specific filter.
    - `[AssignmentFilterType <DeviceAndAppManagementAssignmentFilterType?>]`: Represents type of the assignment filter.
    - `[GroupId <String>]`: The Azure AD security group ID
    - `[PayloadId <String>]`: The policy identifier
    - `[PayloadType <AssociatedAssignmentPayloadType?>]`: This enum represents associated assignment payload type
  - `[Platform <DevicePlatformType?>]`: Supported platform types.
  - `[RoleScopeTags <String[]>]`: Indicates role scope tags assigned for the assignment filter.
  - `[Rule <String>]`: Rule definition of the assignment filter.

PAYLOADS <IMicrosoftGraphPayloadByFilter\[]>: Indicates associated assignments for a specific filter.
  - `[AssignmentFilterType <DeviceAndAppManagementAssignmentFilterType?>]`: Represents type of the assignment filter.
  - `[GroupId <String>]`: The Azure AD security group ID
  - `[PayloadId <String>]`: The policy identifier
  - `[PayloadType <AssociatedAssignmentPayloadType?>]`: This enum represents associated assignment payload type

## RELATED LINKS
