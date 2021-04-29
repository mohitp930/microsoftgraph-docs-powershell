---
external help file: Microsoft.Graph.DeviceManagement.Administration-help.xml
Module Name: Microsoft.Graph.DeviceManagement.Administration
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.administration/update-mgdevicemanagementmobilethreatdefenseconnector
schema: 2.0.0
---

# Update-MgDeviceManagementMobileThreatDefenseConnector

## SYNOPSIS
Update the navigation property mobileThreatDefenseConnectors in deviceManagement

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgDeviceManagementMobileThreatDefenseConnector -MobileThreatDefenseConnectorId <String>
 [-AdditionalProperties <Hashtable>] [-AllowPartnerToCollectIosApplicationMetadata]
 [-AndroidDeviceBlockedOnMissingPartnerData] [-AndroidEnabled] [-AndroidMobileApplicationManagementEnabled]
 [-Id <String>] [-IosDeviceBlockedOnMissingPartnerData] [-IosEnabled] [-IosMobileApplicationManagementEnabled]
 [-LastHeartbeatDateTime <DateTime>] [-MacDeviceBlockedOnMissingPartnerData] [-MacEnabled]
 [-PartnerState <String>] [-PartnerUnresponsivenessThresholdInDays <Int32>]
 [-PartnerUnsupportedOSVersionBlocked] [-WindowsDeviceBlockedOnMissingPartnerData] [-WindowsEnabled]
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Update
```
Update-MgDeviceManagementMobileThreatDefenseConnector -MobileThreatDefenseConnectorId <String>
 -BodyParameter <IMicrosoftGraphMobileThreatDefenseConnector1> [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgDeviceManagementMobileThreatDefenseConnector -InputObject <IDeviceManagementAdministrationIdentity>
 [-AdditionalProperties <Hashtable>] [-AllowPartnerToCollectIosApplicationMetadata]
 [-AndroidDeviceBlockedOnMissingPartnerData] [-AndroidEnabled] [-AndroidMobileApplicationManagementEnabled]
 [-Id <String>] [-IosDeviceBlockedOnMissingPartnerData] [-IosEnabled] [-IosMobileApplicationManagementEnabled]
 [-LastHeartbeatDateTime <DateTime>] [-MacDeviceBlockedOnMissingPartnerData] [-MacEnabled]
 [-PartnerState <String>] [-PartnerUnresponsivenessThresholdInDays <Int32>]
 [-PartnerUnsupportedOSVersionBlocked] [-WindowsDeviceBlockedOnMissingPartnerData] [-WindowsEnabled]
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgDeviceManagementMobileThreatDefenseConnector -InputObject <IDeviceManagementAdministrationIdentity>
 -BodyParameter <IMicrosoftGraphMobileThreatDefenseConnector1> [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property mobileThreatDefenseConnectors in deviceManagement

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

### -AllowPartnerToCollectIosApplicationMetadata
For IOS devices, allows the admin to configure whether the data sync partner may also collect metadata about installed applications from Intune

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AndroidMobileApplicationManagementEnabled
For Android, set whether data from the data sync partner should be used during Mobile Application Management (MAM) evaluations.
Only one partner per platform may be enabled for Mobile Application Management (MAM) evaluation.

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Type: IMicrosoftGraphMobileThreatDefenseConnector1
Parameter Sets: Update, UpdateViaIdentity
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
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IDeviceManagementAdministrationIdentity
Parameter Sets: UpdateViaIdentityExpanded, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -IosDeviceBlockedOnMissingPartnerData
For IOS, set whether Intune must receive data from the data sync partner prior to marking a device compliant

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IosMobileApplicationManagementEnabled
For IOS, get or set whether data from the data sync partner should be used during Mobile Application Management (MAM) evaluations.
Only one partner per platform may be enabled for Mobile Application Management (MAM) evaluation.

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MacDeviceBlockedOnMissingPartnerData
For Mac, get or set whether Intune must receive data from the data sync partner prior to marking a device compliant

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MacEnabled
For Mac, get or set whether data from the data sync partner should be used during compliance evaluations

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MobileThreatDefenseConnectorId
key: id of mobileThreatDefenseConnector

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

### -PartnerState
mobileThreatPartnerTenantState

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

### -PartnerUnresponsivenessThresholdInDays
Get or Set days the per tenant tolerance to unresponsiveness for this partner integration

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

### -PartnerUnsupportedOSVersionBlocked
Get or set whether to block devices on the enabled platforms that do not meet the minimum version requirements of the Data Sync Partner

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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

### -WindowsDeviceBlockedOnMissingPartnerData
For Windows, set whether Intune must receive data from the data sync partner prior to marking a device compliant

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WindowsEnabled
For Windows, get or set whether data from the data sync partner should be used during compliance evaluations

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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

### Microsoft.Graph.PowerShell.Models.IDeviceManagementAdministrationIdentity

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMobileThreatDefenseConnector1

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphMobileThreatDefenseConnector1>: Entity which represents a connection to Mobile threat defense partner.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[AllowPartnerToCollectIosApplicationMetadata <Boolean?>]`: For IOS devices, allows the admin to configure whether the data sync partner may also collect metadata about installed applications from Intune
  - `[AndroidDeviceBlockedOnMissingPartnerData <Boolean?>]`: For Android, set whether Intune must receive data from the data sync partner prior to marking a device compliant
  - `[AndroidEnabled <Boolean?>]`: For Android, set whether data from the data sync partner should be used during compliance evaluations
  - `[AndroidMobileApplicationManagementEnabled <Boolean?>]`: For Android, set whether data from the data sync partner should be used during Mobile Application Management (MAM) evaluations. Only one partner per platform may be enabled for Mobile Application Management (MAM) evaluation.
  - `[IosDeviceBlockedOnMissingPartnerData <Boolean?>]`: For IOS, set whether Intune must receive data from the data sync partner prior to marking a device compliant
  - `[IosEnabled <Boolean?>]`: For IOS, get or set whether data from the data sync partner should be used during compliance evaluations
  - `[IosMobileApplicationManagementEnabled <Boolean?>]`: For IOS, get or set whether data from the data sync partner should be used during Mobile Application Management (MAM) evaluations. Only one partner per platform may be enabled for Mobile Application Management (MAM) evaluation.
  - `[LastHeartbeatDateTime <DateTime?>]`: DateTime of last Heartbeat recieved from the Data Sync Partner
  - `[MacDeviceBlockedOnMissingPartnerData <Boolean?>]`: For Mac, get or set whether Intune must receive data from the data sync partner prior to marking a device compliant
  - `[MacEnabled <Boolean?>]`: For Mac, get or set whether data from the data sync partner should be used during compliance evaluations
  - `[PartnerState <String>]`: mobileThreatPartnerTenantState
  - `[PartnerUnresponsivenessThresholdInDays <Int32?>]`: Get or Set days the per tenant tolerance to unresponsiveness for this partner integration
  - `[PartnerUnsupportedOSVersionBlocked <Boolean?>]`: Get or set whether to block devices on the enabled platforms that do not meet the minimum version requirements of the Data Sync Partner
  - `[WindowsDeviceBlockedOnMissingPartnerData <Boolean?>]`: For Windows, set whether Intune must receive data from the data sync partner prior to marking a device compliant
  - `[WindowsEnabled <Boolean?>]`: For Windows, get or set whether data from the data sync partner should be used during compliance evaluations

INPUTOBJECT <IDeviceManagementAdministrationIdentity>: Identity Parameter
  - `[AuditEventId <String>]`: key: id of auditEvent
  - `[CartToClassAssociationId <String>]`: key: id of cartToClassAssociation
  - `[ComanagementEligibleDeviceId <String>]`: key: id of comanagementEligibleDevice
  - `[ComplianceManagementPartnerId <String>]`: key: id of complianceManagementPartner
  - `[DeviceAndAppManagementRoleAssignmentId <String>]`: key: id of deviceAndAppManagementRoleAssignment
  - `[DeviceManagementDomainJoinConnectorId <String>]`: key: id of deviceManagementDomainJoinConnector
  - `[DeviceManagementExchangeConnectorId <String>]`: key: id of deviceManagementExchangeConnector
  - `[DeviceManagementExchangeOnPremisesPolicyId <String>]`: key: id of deviceManagementExchangeOnPremisesPolicy
  - `[DeviceManagementPartnerId <String>]`: key: id of deviceManagementPartner
  - `[GroupPolicyCategoryId <String>]`: key: id of groupPolicyCategory
  - `[GroupPolicyDefinitionFileId <String>]`: key: id of groupPolicyDefinitionFile
  - `[GroupPolicyDefinitionId <String>]`: key: id of groupPolicyDefinition
  - `[GroupPolicyMigrationReportId <String>]`: key: id of groupPolicyMigrationReport
  - `[GroupPolicyObjectFileId <String>]`: key: id of groupPolicyObjectFile
  - `[GroupPolicyOperationId <String>]`: key: id of groupPolicyOperation
  - `[GroupPolicyPresentationId <String>]`: key: id of groupPolicyPresentation
  - `[GroupPolicySettingMappingId <String>]`: key: id of groupPolicySettingMapping
  - `[GroupPolicyUploadedDefinitionFileId <String>]`: key: id of groupPolicyUploadedDefinitionFile
  - `[IntuneBrandingProfileAssignmentId <String>]`: key: id of intuneBrandingProfileAssignment
  - `[IntuneBrandingProfileId <String>]`: key: id of intuneBrandingProfile
  - `[IosUpdateDeviceStatusId <String>]`: key: id of iosUpdateDeviceStatus
  - `[ManagedAllDeviceCertificateStateId <String>]`: key: id of managedAllDeviceCertificateState
  - `[MobileThreatDefenseConnectorId <String>]`: key: id of mobileThreatDefenseConnector
  - `[NdesConnectorId <String>]`: key: id of ndesConnector
  - `[RemoteAssistancePartnerId <String>]`: key: id of remoteAssistancePartner
  - `[ResourceOperationId <String>]`: key: id of resourceOperation
  - `[RestrictedAppsViolationId <String>]`: key: id of restrictedAppsViolation
  - `[RoleAssignmentId <String>]`: key: id of roleAssignment
  - `[RoleDefinitionId <String>]`: key: id of roleDefinition
  - `[RoleScopeTagAutoAssignmentId <String>]`: key: id of roleScopeTagAutoAssignment
  - `[RoleScopeTagId <String>]`: key: id of roleScopeTag
  - `[TelecomExpenseManagementPartnerId <String>]`: key: id of telecomExpenseManagementPartner
  - `[TermsAndConditionsAcceptanceStatusId <String>]`: key: id of termsAndConditionsAcceptanceStatus
  - `[TermsAndConditionsAssignmentId <String>]`: key: id of termsAndConditionsAssignment
  - `[TermsAndConditionsGroupAssignmentId <String>]`: key: id of termsAndConditionsGroupAssignment
  - `[TermsAndConditionsId <String>]`: key: id of termsAndConditions
  - `[UnsupportedGroupPolicyExtensionId <String>]`: key: id of unsupportedGroupPolicyExtension
  - `[UserPfxCertificateId <String>]`: key: id of userPFXCertificate

## RELATED LINKS