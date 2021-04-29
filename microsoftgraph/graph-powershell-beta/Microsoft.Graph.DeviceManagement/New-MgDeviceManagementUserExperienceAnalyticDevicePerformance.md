---
external help file: Microsoft.Graph.DeviceManagement-help.xml
Module Name: Microsoft.Graph.DeviceManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement/new-mgdevicemanagementuserexperienceanalyticdeviceperformance
schema: 2.0.0
---

# New-MgDeviceManagementUserExperienceAnalyticDevicePerformance

## SYNOPSIS
Create new navigation property to userExperienceAnalyticsDevicePerformance for deviceManagement

## SYNTAX

### CreateExpanded (Default)
```
New-MgDeviceManagementUserExperienceAnalyticDevicePerformance [-AdditionalProperties <Hashtable>]
 [-AverageBlueScreens <Double>] [-AverageRestarts <Double>] [-BlueScreenCount <Int32>] [-BootScore <Int32>]
 [-CoreBootTimeInMS <Int32>] [-CoreLoginTimeInMS <Int32>] [-DeviceCount <Int64>] [-DeviceName <String>]
 [-DiskType <String>] [-GroupPolicyBootTimeInMS <Int32>] [-GroupPolicyLoginTimeInMS <Int32>]
 [-HealthStatus <String>] [-Id <String>] [-LoginScore <Int32>] [-Manufacturer <String>] [-Model <String>]
 [-OperatingSystemVersion <String>] [-ResponsiveDesktopTimeInMS <Int32>] [-RestartCount <Int32>] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgDeviceManagementUserExperienceAnalyticDevicePerformance
 -BodyParameter <IMicrosoftGraphUserExperienceAnalyticsDevicePerformance> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to userExperienceAnalyticsDevicePerformance for deviceManagement

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

### -AverageBlueScreens
Average (mean) number of Blue Screens per device in the last 14 days.
Valid values 0 to 9999999

```yaml
Type: Double
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AverageRestarts
Average (mean) number of Restarts per device in the last 14 days.
Valid values 0 to 9999999

```yaml
Type: Double
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BlueScreenCount
Number of Blue Screens in the last 14 days.
Valid values 0 to 9999999

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

### -BodyParameter
The user experience analytics device performance entity contains device boot performance details.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphUserExperienceAnalyticsDevicePerformance
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -BootScore
The user experience analytics device boot score.

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

### -CoreBootTimeInMS
The user experience analytics device core boot time in milliseconds.

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

### -CoreLoginTimeInMS
The user experience analytics device core login time in milliseconds.

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

### -DeviceCount
User experience analytics summarized device count.

```yaml
Type: Int64
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceName
The user experience analytics device name.

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

### -DiskType
diskType

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

### -GroupPolicyBootTimeInMS
The user experience analytics device group policy boot time in milliseconds.

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

### -GroupPolicyLoginTimeInMS
The user experience analytics device group policy login time in milliseconds.

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

### -HealthStatus
userExperienceAnalyticsHealthState

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

### -LoginScore
The user experience analytics device login score.

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

### -Manufacturer
The user experience analytics device manufacturer.

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

### -Model
The user experience analytics device model.

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

### -OperatingSystemVersion
The user experience analytics device Operating System version.

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

### -ResponsiveDesktopTimeInMS
The user experience analytics responsive desktop time in milliseconds.

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

### -RestartCount
Number of Restarts in the last 14 days.
Valid values 0 to 9999999

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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserExperienceAnalyticsDevicePerformance

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserExperienceAnalyticsDevicePerformance

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphUserExperienceAnalyticsDevicePerformance>: The user experience analytics device performance entity contains device boot performance details.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[AverageBlueScreens <Double?>]`: Average (mean) number of Blue Screens per device in the last 14 days. Valid values 0 to 9999999
  - `[AverageRestarts <Double?>]`: Average (mean) number of Restarts per device in the last 14 days. Valid values 0 to 9999999
  - `[BlueScreenCount <Int32?>]`: Number of Blue Screens in the last 14 days. Valid values 0 to 9999999
  - `[BootScore <Int32?>]`: The user experience analytics device boot score.
  - `[CoreBootTimeInMS <Int32?>]`: The user experience analytics device core boot time in milliseconds.
  - `[CoreLoginTimeInMS <Int32?>]`: The user experience analytics device core login time in milliseconds.
  - `[DeviceCount <Int64?>]`: User experience analytics summarized device count.
  - `[DeviceName <String>]`: The user experience analytics device name.
  - `[DiskType <String>]`: diskType
  - `[GroupPolicyBootTimeInMS <Int32?>]`: The user experience analytics device group policy boot time in milliseconds.
  - `[GroupPolicyLoginTimeInMS <Int32?>]`: The user experience analytics device group policy login time in milliseconds.
  - `[HealthStatus <String>]`: userExperienceAnalyticsHealthState
  - `[LoginScore <Int32?>]`: The user experience analytics device login score.
  - `[Manufacturer <String>]`: The user experience analytics device manufacturer.
  - `[Model <String>]`: The user experience analytics device model.
  - `[OperatingSystemVersion <String>]`: The user experience analytics device Operating System version.
  - `[ResponsiveDesktopTimeInMS <Int32?>]`: The user experience analytics responsive desktop time in milliseconds.
  - `[RestartCount <Int32?>]`: Number of Restarts in the last 14 days. Valid values 0 to 9999999

## RELATED LINKS