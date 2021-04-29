---
external help file: Microsoft.Graph.DeviceManagement.Administration-help.xml
Module Name: Microsoft.Graph.DeviceManagement.Administration
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.administration/new-mgdevicemanagementmobilethreatdefenseconnector
schema: 2.0.0
---

# New-MgDeviceManagementMobileThreatDefenseConnector

## SYNOPSIS
Create new navigation property to mobileThreatDefenseConnectors for deviceManagement

## SYNTAX

### CreateExpanded1 (Default)
```
New-MgDeviceManagementMobileThreatDefenseConnector [-AdditionalProperties <Hashtable>]
 [-AndroidDeviceBlockedOnMissingPartnerData] [-AndroidEnabled] [-Id <String>]
 [-IosDeviceBlockedOnMissingPartnerData] [-IosEnabled] [-LastHeartbeatDateTime <DateTime>]
 [-PartnerState <String>] [-PartnerUnresponsivenessThresholdInDays <Int32>]
 [-PartnerUnsupportedOSVersionBlocked] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create1
```
New-MgDeviceManagementMobileThreatDefenseConnector -BodyParameter <IMicrosoftGraphMobileThreatDefenseConnector>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to mobileThreatDefenseConnectors for deviceManagement

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AndroidDeviceBlockedOnMissingPartnerData
For Android, set whether Intune must receive data from the data sync partner prior to marking a device compliant

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AndroidEnabled
For Android, set whether data from the data sync partner should be used during compliance evaluations

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
Entity which represents a connection to Mobile threat defense partner.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphMobileThreatDefenseConnector
Parameter Sets: Create1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Id
Read-only.

```yaml
Type: String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IosDeviceBlockedOnMissingPartnerData
For IOS, set whether Intune must receive data from the data sync partner prior to marking a device compliant

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IosEnabled
For IOS, get or set whether data from the data sync partner should be used during compliance evaluations

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LastHeartbeatDateTime
DateTime of last Heartbeat recieved from the Data Sync Partner

```yaml
Type: DateTime
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PartnerState
mobileThreatPartnerTenantState

```yaml
Type: String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PartnerUnresponsivenessThresholdInDays
Get or Set days the per tenant tolerance to unresponsiveness for this partner integration

```yaml
Type: Int32
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PartnerUnsupportedOSVersionBlocked
Get or set whether to block devices on the enabled platforms that do not meet the minimum version requirements of the Data Sync Partner

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded1
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMobileThreatDefenseConnector

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMobileThreatDefenseConnector

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphMobileThreatDefenseConnector>: Entity which represents a connection to Mobile threat defense partner.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[AndroidDeviceBlockedOnMissingPartnerData <Boolean?>]`: For Android, set whether Intune must receive data from the data sync partner prior to marking a device compliant
  - `[AndroidEnabled <Boolean?>]`: For Android, set whether data from the data sync partner should be used during compliance evaluations
  - `[IosDeviceBlockedOnMissingPartnerData <Boolean?>]`: For IOS, set whether Intune must receive data from the data sync partner prior to marking a device compliant
  - `[IosEnabled <Boolean?>]`: For IOS, get or set whether data from the data sync partner should be used during compliance evaluations
  - `[LastHeartbeatDateTime <DateTime?>]`: DateTime of last Heartbeat recieved from the Data Sync Partner
  - `[PartnerState <String>]`: mobileThreatPartnerTenantState
  - `[PartnerUnresponsivenessThresholdInDays <Int32?>]`: Get or Set days the per tenant tolerance to unresponsiveness for this partner integration
  - `[PartnerUnsupportedOSVersionBlocked <Boolean?>]`: Get or set whether to block devices on the enabled platforms that do not meet the minimum version requirements of the Data Sync Partner

## RELATED LINKS