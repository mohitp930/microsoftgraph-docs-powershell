---
external help file: Microsoft.Graph.DeviceManagement-help.xml
Module Name: Microsoft.Graph.DeviceManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement/new-mgdevicemanagementdevicecompliancepolicysettingstatesummary
schema: 2.0.0
---

# New-MgDeviceManagementDeviceCompliancePolicySettingStateSummary

## SYNOPSIS
Create new navigation property to deviceCompliancePolicySettingStateSummaries for deviceManagement

## SYNTAX

### CreateExpanded (Default)
```
New-MgDeviceManagementDeviceCompliancePolicySettingStateSummary [-AdditionalProperties <Hashtable>]
 [-CompliantDeviceCount <Int32>] [-ConflictDeviceCount <Int32>]
 [-DeviceComplianceSettingStates <IMicrosoftGraphDeviceComplianceSettingState[]>] [-ErrorDeviceCount <Int32>]
 [-Id <String>] [-NonCompliantDeviceCount <Int32>] [-NotApplicableDeviceCount <Int32>] [-PlatformType <String>]
 [-RemediatedDeviceCount <Int32>] [-Setting <String>] [-SettingName <String>] [-UnknownDeviceCount <Int32>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgDeviceManagementDeviceCompliancePolicySettingStateSummary
 -BodyParameter <IMicrosoftGraphDeviceCompliancePolicySettingStateSummary> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to deviceCompliancePolicySettingStateSummaries for deviceManagement

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
Device Compilance Policy Setting State summary across the account.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceCompliancePolicySettingStateSummary
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CompliantDeviceCount
Number of compliant devices

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

### -ConflictDeviceCount
Number of conflict devices

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

### -DeviceComplianceSettingStates
Not yet documented
To construct, see NOTES section for DEVICECOMPLIANCESETTINGSTATES properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceComplianceSettingState[]
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ErrorDeviceCount
Number of error devices

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

### -NonCompliantDeviceCount
Number of NonCompliant devices

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

### -NotApplicableDeviceCount
Number of not applicable devices

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

### -PlatformType
.

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

### -RemediatedDeviceCount
Number of remediated devices

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

### -Setting
The setting class name and property name.

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

### -SettingName
Name of the setting.

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

### -UnknownDeviceCount
Number of unknown devices

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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDeviceCompliancePolicySettingStateSummary

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDeviceCompliancePolicySettingStateSummary

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphDeviceCompliancePolicySettingStateSummary>: Device Compilance Policy Setting State summary across the account.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[CompliantDeviceCount <Int32?>]`: Number of compliant devices
  - `[ConflictDeviceCount <Int32?>]`: Number of conflict devices
  - `[DeviceComplianceSettingStates <IMicrosoftGraphDeviceComplianceSettingState[]>]`: Not yet documented
    - `[Id <String>]`: Read-only.
    - `[ComplianceGracePeriodExpirationDateTime <DateTime?>]`: The DateTime when device compliance grace period expires
    - `[DeviceId <String>]`: The Device Id that is being reported
    - `[DeviceModel <String>]`: The device model that is being reported
    - `[DeviceName <String>]`: The Device Name that is being reported
    - `[PlatformType <String>]`: deviceType
    - `[Setting <String>]`: The setting class name and property name.
    - `[SettingName <String>]`: The Setting Name that is being reported
    - `[State <String>]`: complianceStatus
    - `[UserEmail <String>]`: The User email address that is being reported
    - `[UserId <String>]`: The user Id that is being reported
    - `[UserName <String>]`: The User Name that is being reported
    - `[UserPrincipalName <String>]`: The User PrincipalName that is being reported
  - `[ErrorDeviceCount <Int32?>]`: Number of error devices
  - `[NonCompliantDeviceCount <Int32?>]`: Number of NonCompliant devices
  - `[NotApplicableDeviceCount <Int32?>]`: Number of not applicable devices
  - `[PlatformType <String>]`: 
  - `[RemediatedDeviceCount <Int32?>]`: Number of remediated devices
  - `[Setting <String>]`: The setting class name and property name.
  - `[SettingName <String>]`: Name of the setting.
  - `[UnknownDeviceCount <Int32?>]`: Number of unknown devices

DEVICECOMPLIANCESETTINGSTATES <IMicrosoftGraphDeviceComplianceSettingState[]>: Not yet documented
  - `[Id <String>]`: Read-only.
  - `[ComplianceGracePeriodExpirationDateTime <DateTime?>]`: The DateTime when device compliance grace period expires
  - `[DeviceId <String>]`: The Device Id that is being reported
  - `[DeviceModel <String>]`: The device model that is being reported
  - `[DeviceName <String>]`: The Device Name that is being reported
  - `[PlatformType <String>]`: deviceType
  - `[Setting <String>]`: The setting class name and property name.
  - `[SettingName <String>]`: The Setting Name that is being reported
  - `[State <String>]`: complianceStatus
  - `[UserEmail <String>]`: The User email address that is being reported
  - `[UserId <String>]`: The user Id that is being reported
  - `[UserName <String>]`: The User Name that is being reported
  - `[UserPrincipalName <String>]`: The User PrincipalName that is being reported

## RELATED LINKS