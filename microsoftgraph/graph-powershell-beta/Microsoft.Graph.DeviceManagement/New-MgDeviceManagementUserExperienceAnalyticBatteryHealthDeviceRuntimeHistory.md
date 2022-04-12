---
external help file: Microsoft.Graph.DeviceManagement-help.xml
Module Name: Microsoft.Graph.DeviceManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement/new-mgdevicemanagementuserexperienceanalyticbatteryhealthdeviceruntimehistory
schema: 2.0.0
---

# New-MgDeviceManagementUserExperienceAnalyticBatteryHealthDeviceRuntimeHistory

## SYNOPSIS
User Experience Analytics Battery Health Device Runtime History

## SYNTAX

### CreateExpanded (Default)
```
New-MgDeviceManagementUserExperienceAnalyticBatteryHealthDeviceRuntimeHistory
 [-AdditionalProperties <Hashtable>] [-DeviceId <String>] [-EstimatedRuntimeInMinutes <Int32>] [-Id <String>]
 [-RuntimeDateTime <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgDeviceManagementUserExperienceAnalyticBatteryHealthDeviceRuntimeHistory
 -BodyParameter <IMicrosoftGraphUserExperienceAnalyticsBatteryHealthDeviceRuntimeHistory> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
User Experience Analytics Battery Health Device Runtime History

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

### -BodyParameter
The user experience analytics battery health runtime history entity contains the trend of runtime of a device over a period of 30 days
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphUserExperienceAnalyticsBatteryHealthDeviceRuntimeHistory
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DeviceId
The unique identifier of the device, Intune DeviceID or SCCM device id.

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

### -EstimatedRuntimeInMinutes
The estimated runtime of the device when the battery is fully charged.
Unit in minutes.
Valid values -2147483648 to 2147483647

```yaml
Type: Int32
Parameter Sets: CreateExpanded
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
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RuntimeDateTime
The datetime for the instance of runtime history.

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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserExperienceAnalyticsBatteryHealthDeviceRuntimeHistory
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserExperienceAnalyticsBatteryHealthDeviceRuntimeHistory
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphUserExperienceAnalyticsBatteryHealthDeviceRuntimeHistory>: The user experience analytics battery health runtime history entity contains the trend of runtime of a device over a period of 30 days
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[DeviceId <String>]`: The unique identifier of the device, Intune DeviceID or SCCM device id.
  - `[EstimatedRuntimeInMinutes <Int32?>]`: The estimated runtime of the device when the battery is fully charged. Unit in minutes. Valid values -2147483648 to 2147483647
  - `[RuntimeDateTime <String>]`: The datetime for the instance of runtime history.

## RELATED LINKS