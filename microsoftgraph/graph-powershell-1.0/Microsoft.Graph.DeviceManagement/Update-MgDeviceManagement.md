---
external help file: Microsoft.Graph.DeviceManagement-help.xml
Module Name: Microsoft.Graph.DeviceManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement/update-mgdevicemanagement
schema: 2.0.0
---

# Update-MgDeviceManagement

## SYNOPSIS
Update deviceManagement

## SYNTAX

### UpdateExpanded1 (Default)
```
Update-MgDeviceManagement [-AdditionalProperties <Hashtable>]
 [-ApplePushNotificationCertificate <IMicrosoftGraphApplePushNotificationCertificate1>]
 [-ComplianceManagementPartners <IMicrosoftGraphComplianceManagementPartner1[]>]
 [-ConditionalAccessSettings <IMicrosoftGraphOnPremisesConditionalAccessSettings>]
 [-DetectedApps <IMicrosoftGraphDetectedApp1[]>] [-DeviceCategories <IMicrosoftGraphDeviceCategory2[]>]
 [-DeviceCompliancePolicies <IMicrosoftGraphDeviceCompliancePolicy1[]>]
 [-DeviceCompliancePolicyDeviceStateSummary <IMicrosoftGraphDeviceCompliancePolicyDeviceStateSummary>]
 [-DeviceCompliancePolicySettingStateSummaries <IMicrosoftGraphDeviceCompliancePolicySettingStateSummary1[]>]
 [-DeviceConfigurationDeviceStateSummaries <IMicrosoftGraphDeviceConfigurationDeviceStateSummary>]
 [-DeviceConfigurations <IMicrosoftGraphDeviceConfiguration1[]>]
 [-DeviceEnrollmentConfigurations <IMicrosoftGraphDeviceEnrollmentConfiguration1[]>]
 [-DeviceManagementPartners <IMicrosoftGraphDeviceManagementPartner1[]>]
 [-ExchangeConnectors <IMicrosoftGraphDeviceManagementExchangeConnector[]>] [-Id <String>]
 [-IntuneAccountId <String>] [-IntuneBrand <IMicrosoftGraphIntuneBrand1>]
 [-IosUpdateStatuses <IMicrosoftGraphIosUpdateDeviceStatus1[]>]
 [-ManagedDeviceOverview <IMicrosoftGraphManagedDeviceOverview1>]
 [-ManagedDevices <IMicrosoftGraphManagedDevice1[]>]
 [-MobileThreatDefenseConnectors <IMicrosoftGraphMobileThreatDefenseConnector1[]>]
 [-NotificationMessageTemplates <IMicrosoftGraphNotificationMessageTemplate1[]>]
 [-RemoteAssistancePartners <IMicrosoftGraphRemoteAssistancePartner1[]>]
 [-ResourceOperations <IMicrosoftGraphResourceOperation1[]>]
 [-RoleAssignments <IMicrosoftGraphDeviceAndAppManagementRoleAssignment1[]>]
 [-RoleDefinitions <IMicrosoftGraphRoleDefinition1[]>] [-Settings <IMicrosoftGraphDeviceManagementSettings1>]
 [-SoftwareUpdateStatusSummary <IMicrosoftGraphSoftwareUpdateStatusSummary>] [-SubscriptionState <String>]
 [-TelecomExpenseManagementPartners <IMicrosoftGraphTelecomExpenseManagementPartner[]>]
 [-TermsAndConditions <IMicrosoftGraphTermsAndConditions1[]>]
 [-TroubleshootingEvents <IMicrosoftGraphDeviceManagementTroubleshootingEvent1[]>]
 [-WindowsInformationProtectionAppLearningSummaries <IMicrosoftGraphWindowsInformationProtectionAppLearningSummary[]>]
 [-WindowsInformationProtectionNetworkLearningSummaries <IMicrosoftGraphWindowsInformationProtectionNetworkLearningSummary[]>]
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Update1
```
Update-MgDeviceManagement -BodyParameter <IMicrosoftGraphDeviceManagement1> [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
Update deviceManagement

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ApplePushNotificationCertificate
Apple push notification certificate.
To construct, see NOTES section for APPLEPUSHNOTIFICATIONCERTIFICATE properties and create a hash table.

```yaml
Type: IMicrosoftGraphApplePushNotificationCertificate1
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
Singleton entity that acts as a container for all device management functionality.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceManagement1
Parameter Sets: Update1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ComplianceManagementPartners
The list of Compliance Management Partners configured by the tenant.
To construct, see NOTES section for COMPLIANCEMANAGEMENTPARTNERS properties and create a hash table.

```yaml
Type: IMicrosoftGraphComplianceManagementPartner1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ConditionalAccessSettings
Singleton entity which represents the Exchange OnPremises Conditional Access Settings for a tenant.
To construct, see NOTES section for CONDITIONALACCESSSETTINGS properties and create a hash table.

```yaml
Type: IMicrosoftGraphOnPremisesConditionalAccessSettings
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DetectedApps
The list of detected apps associated with a device.
To construct, see NOTES section for DETECTEDAPPS properties and create a hash table.

```yaml
Type: IMicrosoftGraphDetectedApp1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceCategories
The list of device categories with the tenant.
To construct, see NOTES section for DEVICECATEGORIES properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceCategory2[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceCompliancePolicies
The device compliance policies.
To construct, see NOTES section for DEVICECOMPLIANCEPOLICIES properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceCompliancePolicy1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceCompliancePolicyDeviceStateSummary
deviceCompliancePolicyDeviceStateSummary
To construct, see NOTES section for DEVICECOMPLIANCEPOLICYDEVICESTATESUMMARY properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceCompliancePolicyDeviceStateSummary
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceCompliancePolicySettingStateSummaries
The summary states of compliance policy settings for this account.
To construct, see NOTES section for DEVICECOMPLIANCEPOLICYSETTINGSTATESUMMARIES properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceCompliancePolicySettingStateSummary1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceConfigurationDeviceStateSummaries
deviceConfigurationDeviceStateSummary
To construct, see NOTES section for DEVICECONFIGURATIONDEVICESTATESUMMARIES properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceConfigurationDeviceStateSummary
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceConfigurations
The device configurations.
To construct, see NOTES section for DEVICECONFIGURATIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceConfiguration1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceEnrollmentConfigurations
The list of device enrollment configurations
To construct, see NOTES section for DEVICEENROLLMENTCONFIGURATIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceEnrollmentConfiguration1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceManagementPartners
The list of Device Management Partners configured by the tenant.
To construct, see NOTES section for DEVICEMANAGEMENTPARTNERS properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceManagementPartner1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExchangeConnectors
The list of Exchange Connectors configured by the tenant.
To construct, see NOTES section for EXCHANGECONNECTORS properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceManagementExchangeConnector[]
Parameter Sets: UpdateExpanded1
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
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IntuneAccountId
Intune Account ID for given tenant

```yaml
Type: String
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IntuneBrand
intuneBrand contains data which is used in customizing the appearance of the Company Portal applications as well as the end user web portal.
To construct, see NOTES section for INTUNEBRAND properties and create a hash table.

```yaml
Type: IMicrosoftGraphIntuneBrand1
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IosUpdateStatuses
The IOS software update installation statuses for this account.
To construct, see NOTES section for IOSUPDATESTATUSES properties and create a hash table.

```yaml
Type: IMicrosoftGraphIosUpdateDeviceStatus1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ManagedDeviceOverview
Summary data for managed devices
To construct, see NOTES section for MANAGEDDEVICEOVERVIEW properties and create a hash table.

```yaml
Type: IMicrosoftGraphManagedDeviceOverview1
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ManagedDevices
The list of managed devices.
To construct, see NOTES section for MANAGEDDEVICES properties and create a hash table.

```yaml
Type: IMicrosoftGraphManagedDevice1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MobileThreatDefenseConnectors
The list of Mobile threat Defense connectors configured by the tenant.
To construct, see NOTES section for MOBILETHREATDEFENSECONNECTORS properties and create a hash table.

```yaml
Type: IMicrosoftGraphMobileThreatDefenseConnector1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -NotificationMessageTemplates
The Notification Message Templates.
To construct, see NOTES section for NOTIFICATIONMESSAGETEMPLATES properties and create a hash table.

```yaml
Type: IMicrosoftGraphNotificationMessageTemplate1[]
Parameter Sets: UpdateExpanded1
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

### -RemoteAssistancePartners
The remote assist partners.
To construct, see NOTES section for REMOTEASSISTANCEPARTNERS properties and create a hash table.

```yaml
Type: IMicrosoftGraphRemoteAssistancePartner1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceOperations
The Resource Operations.
To construct, see NOTES section for RESOURCEOPERATIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphResourceOperation1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RoleAssignments
The Role Assignments.
To construct, see NOTES section for ROLEASSIGNMENTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceAndAppManagementRoleAssignment1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RoleDefinitions
The Role Definitions.
To construct, see NOTES section for ROLEDEFINITIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphRoleDefinition1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Settings
deviceManagementSettings
To construct, see NOTES section for SETTINGS properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceManagementSettings1
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SoftwareUpdateStatusSummary
softwareUpdateStatusSummary
To construct, see NOTES section for SOFTWAREUPDATESTATUSSUMMARY properties and create a hash table.

```yaml
Type: IMicrosoftGraphSoftwareUpdateStatusSummary
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SubscriptionState
deviceManagementSubscriptionState

```yaml
Type: String
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TelecomExpenseManagementPartners
The telecom expense management partners.
To construct, see NOTES section for TELECOMEXPENSEMANAGEMENTPARTNERS properties and create a hash table.

```yaml
Type: IMicrosoftGraphTelecomExpenseManagementPartner[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TermsAndConditions
The terms and conditions associated with device management of the company.
To construct, see NOTES section for TERMSANDCONDITIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphTermsAndConditions1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TroubleshootingEvents
The list of troubleshooting events for the tenant.
To construct, see NOTES section for TROUBLESHOOTINGEVENTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphDeviceManagementTroubleshootingEvent1[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WindowsInformationProtectionAppLearningSummaries
The windows information protection app learning summaries.
To construct, see NOTES section for WINDOWSINFORMATIONPROTECTIONAPPLEARNINGSUMMARIES properties and create a hash table.

```yaml
Type: IMicrosoftGraphWindowsInformationProtectionAppLearningSummary[]
Parameter Sets: UpdateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WindowsInformationProtectionNetworkLearningSummaries
The windows information protection network learning summaries.
To construct, see NOTES section for WINDOWSINFORMATIONPROTECTIONNETWORKLEARNINGSUMMARIES properties and create a hash table.

```yaml
Type: IMicrosoftGraphWindowsInformationProtectionNetworkLearningSummary[]
Parameter Sets: UpdateExpanded1
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDeviceManagement1

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


APPLEPUSHNOTIFICATIONCERTIFICATE <IMicrosoftGraphApplePushNotificationCertificate1>: Apple push notification certificate.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[AppleIdentifier <String>]`: Apple Id of the account used to create the MDM push certificate.
  - `[Certificate <String>]`: Not yet documented
  - `[ExpirationDateTime <DateTime?>]`: The expiration date and time for Apple push notification certificate.
  - `[LastModifiedDateTime <DateTime?>]`: Last modified date and time for Apple push notification certificate.
  - `[TopicIdentifier <String>]`: Topic Id.

BODYPARAMETER <IMicrosoftGraphDeviceManagement1>: Singleton entity that acts as a container for all device management functionality.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[ApplePushNotificationCertificate <IMicrosoftGraphApplePushNotificationCertificate1>]`: Apple push notification certificate.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[AppleIdentifier <String>]`: Apple Id of the account used to create the MDM push certificate.
    - `[Certificate <String>]`: Not yet documented
    - `[ExpirationDateTime <DateTime?>]`: The expiration date and time for Apple push notification certificate.
    - `[LastModifiedDateTime <DateTime?>]`: Last modified date and time for Apple push notification certificate.
    - `[TopicIdentifier <String>]`: Topic Id.
  - `[ComplianceManagementPartners <IMicrosoftGraphComplianceManagementPartner1[]>]`: The list of Compliance Management Partners configured by the tenant.
    - `[Id <String>]`: Read-only.
    - `[AndroidEnrollmentAssignments <IMicrosoftGraphComplianceManagementPartnerAssignment[]>]`: User groups which enroll Android devices through partner.
      - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[AndroidOnboarded <Boolean?>]`: Partner onboarded for Android devices.
    - `[DisplayName <String>]`: Partner display name
    - `[IosEnrollmentAssignments <IMicrosoftGraphComplianceManagementPartnerAssignment[]>]`: User groups which enroll ios devices through partner.
    - `[IosOnboarded <Boolean?>]`: Partner onboarded for ios devices.
    - `[LastHeartbeatDateTime <DateTime?>]`: Timestamp of last heartbeat after admin onboarded to the compliance management partner
    - `[MacOSEnrollmentAssignments <IMicrosoftGraphComplianceManagementPartnerAssignment[]>]`: User groups which enroll Mac devices through partner.
    - `[MacOSOnboarded <Boolean?>]`: Partner onboarded for Mac devices.
    - `[PartnerState <String>]`: deviceManagementPartnerTenantState
  - `[ConditionalAccessSettings <IMicrosoftGraphOnPremisesConditionalAccessSettings>]`: Singleton entity which represents the Exchange OnPremises Conditional Access Settings for a tenant.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[Enabled <Boolean?>]`: Indicates if on premises conditional access is enabled for this organization
    - `[ExcludedGroups <String[]>]`: User groups that will be exempt by on premises conditional access. All users in these groups will be exempt from the conditional access policy.
    - `[IncludedGroups <String[]>]`: User groups that will be targeted by on premises conditional access. All users in these groups will be required to have mobile device managed and compliant for mail access.
    - `[OverrideDefaultRule <Boolean?>]`: Override the default access rule when allowing a device to ensure access is granted.
  - `[DetectedApps <IMicrosoftGraphDetectedApp1[]>]`: The list of detected apps associated with a device.
    - `[Id <String>]`: Read-only.
    - `[DeviceCount <Int32?>]`: The number of devices that have installed this application
    - `[DisplayName <String>]`: Name of the discovered application. Read-only
    - `[ManagedDevices <IMicrosoftGraphManagedDevice1[]>]`: The devices that have the discovered application installed
      - `[Id <String>]`: Read-only.
      - `[ActivationLockBypassCode <String>]`: Code that allows the Activation Lock on a device to be bypassed. This property is read-only.
      - `[AndroidSecurityPatchLevel <String>]`: Android security patch level. This property is read-only.
      - `[AzureAdDeviceId <String>]`: The unique identifier for the Azure Active Directory device. Read only. This property is read-only.
      - `[AzureAdRegistered <Boolean?>]`: Whether the device is Azure Active Directory registered. This property is read-only.
      - `[ComplianceGracePeriodExpirationDateTime <DateTime?>]`: The DateTime when device compliance grace period expires. This property is read-only.
      - `[ComplianceState <String>]`: complianceState
      - `[ConfigurationManagerClientEnabledFeatures <IMicrosoftGraphConfigurationManagerClientEnabledFeatures1>]`: configuration Manager client enabled features
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[CompliancePolicy <Boolean?>]`: Whether compliance policy is managed by Intune
        - `[DeviceConfiguration <Boolean?>]`: Whether device configuration is managed by Intune
        - `[Inventory <Boolean?>]`: Whether inventory is managed by Intune
        - `[ModernApps <Boolean?>]`: Whether modern application is managed by Intune
        - `[ResourceAccess <Boolean?>]`: Whether resource access is managed by Intune
        - `[WindowsUpdateForBusiness <Boolean?>]`: Whether Windows Update for Business is managed by Intune
      - `[DeviceActionResults <IMicrosoftGraphDeviceActionResult[]>]`: List of ComplexType deviceActionResult objects. This property is read-only.
        - `[ActionName <String>]`: Action name
        - `[ActionState <String>]`: actionState
        - `[LastUpdatedDateTime <DateTime?>]`: Time the action state was last updated
        - `[StartDateTime <DateTime?>]`: Time the action was initiated
      - `[DeviceCategory <IMicrosoftGraphDeviceCategory2>]`: Device categories provides a way to organize your devices. Using device categories, company administrators can define their own categories that make sense to their company. These categories can then be applied to a device in the Intune Azure console or selected by a user during device enrollment. You can filter reports and create dynamic Azure Active Directory device groups based on device categories.
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
        - `[Description <String>]`: Optional description for the device category.
        - `[DisplayName <String>]`: Display name for the device category.
      - `[DeviceCategoryDisplayName <String>]`: Device category display name. This property is read-only.
      - `[DeviceCompliancePolicyStates <IMicrosoftGraphDeviceCompliancePolicyState1[]>]`: Device compliance policy states for this device.
        - `[Id <String>]`: Read-only.
        - `[DisplayName <String>]`: The name of the policy for this policyBase
        - `[PlatformType <String>]`: 
        - `[SettingCount <Int32?>]`: Count of how many setting a policy holds
        - `[SettingStates <IMicrosoftGraphDeviceCompliancePolicySettingState[]>]`: 
          - `[CurrentValue <String>]`: Current value of setting on device
          - `[ErrorCode <Int64?>]`: Error code for the setting
          - `[ErrorDescription <String>]`: Error description
          - `[InstanceDisplayName <String>]`: Name of setting instance that is being reported.
          - `[Setting <String>]`: The setting that is being reported
          - `[SettingName <String>]`: Localized/user friendly setting name that is being reported
          - `[Sources <IMicrosoftGraphSettingSource[]>]`: Contributing policies
            - `[DisplayName <String>]`: Not yet documented
            - `[Id <String>]`: Not yet documented
          - `[State <String>]`: complianceStatus
          - `[UserEmail <String>]`: UserEmail
          - `[UserId <String>]`: UserId
          - `[UserName <String>]`: UserName
          - `[UserPrincipalName <String>]`: UserPrincipalName.
        - `[State <String>]`: complianceStatus
        - `[Version <Int32?>]`: The version of the policy
      - `[DeviceConfigurationStates <IMicrosoftGraphDeviceConfigurationState1[]>]`: Device configuration states for this device.
        - `[Id <String>]`: Read-only.
        - `[DisplayName <String>]`: The name of the policy for this policyBase
        - `[PlatformType <String>]`: 
        - `[SettingCount <Int32?>]`: Count of how many setting a policy holds
        - `[SettingStates <IMicrosoftGraphDeviceConfigurationSettingState[]>]`: 
          - `[CurrentValue <String>]`: Current value of setting on device
          - `[ErrorCode <Int64?>]`: Error code for the setting
          - `[ErrorDescription <String>]`: Error description
          - `[InstanceDisplayName <String>]`: Name of setting instance that is being reported.
          - `[Setting <String>]`: The setting that is being reported
          - `[SettingName <String>]`: Localized/user friendly setting name that is being reported
          - `[Sources <IMicrosoftGraphSettingSource[]>]`: Contributing policies
          - `[State <String>]`: complianceStatus
          - `[UserEmail <String>]`: UserEmail
          - `[UserId <String>]`: UserId
          - `[UserName <String>]`: UserName
          - `[UserPrincipalName <String>]`: UserPrincipalName.
        - `[State <String>]`: complianceStatus
        - `[Version <Int32?>]`: The version of the policy
      - `[DeviceEnrollmentType <String>]`: 
      - `[DeviceHealthAttestationState <IMicrosoftGraphDeviceHealthAttestationState>]`: deviceHealthAttestationState
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[AttestationIdentityKey <String>]`: TWhen an Attestation Identity Key (AIK) is present on a device, it indicates that the device has an endorsement key (EK) certificate.
        - `[BitLockerStatus <String>]`: On or Off of BitLocker Drive Encryption
        - `[BootAppSecurityVersion <String>]`: The security version number of the Boot Application
        - `[BootDebugging <String>]`: When bootDebugging is enabled, the device is used in development and testing
        - `[BootManagerSecurityVersion <String>]`: The security version number of the Boot Application
        - `[BootManagerVersion <String>]`: The version of the Boot Manager
        - `[BootRevisionListInfo <String>]`: The Boot Revision List that was loaded during initial boot on the attested device
        - `[CodeIntegrity <String>]`: When code integrity is enabled, code execution is restricted to integrity verified code
        - `[CodeIntegrityCheckVersion <String>]`: The version of the Boot Manager
        - `[CodeIntegrityPolicy <String>]`: The Code Integrity policy that is controlling the security of the boot environment
        - `[ContentNamespaceUrl <String>]`: The DHA report version. (Namespace version)
        - `[ContentVersion <String>]`: The HealthAttestation state schema version
        - `[DataExcutionPolicy <String>]`: DEP Policy defines a set of hardware and software technologies that perform additional checks on memory
        - `[DeviceHealthAttestationStatus <String>]`: The DHA report version. (Namespace version)
        - `[EarlyLaunchAntiMalwareDriverProtection <String>]`: ELAM provides protection for the computers in your network when they start up
        - `[HealthAttestationSupportedStatus <String>]`: This attribute indicates if DHA is supported for the device
        - `[HealthStatusMismatchInfo <String>]`: This attribute appears if DHA-Service detects an integrity issue
        - `[IssuedDateTime <DateTime?>]`: The DateTime when device was evaluated or issued to MDM
        - `[LastUpdateDateTime <String>]`: The Timestamp of the last update.
        - `[OperatingSystemKernelDebugging <String>]`: When operatingSystemKernelDebugging is enabled, the device is used in development and testing
        - `[OperatingSystemRevListInfo <String>]`: The Operating System Revision List that was loaded during initial boot on the attested device
        - `[Pcr0 <String>]`: The measurement that is captured in PCR[0]
        - `[PcrHashAlgorithm <String>]`: Informational attribute that identifies the HASH algorithm that was used by TPM
        - `[ResetCount <Int64?>]`: The number of times a PC device has hibernated or resumed
        - `[RestartCount <Int64?>]`: The number of times a PC device has rebooted
        - `[SafeMode <String>]`: Safe mode is a troubleshooting option for Windows that starts your computer in a limited state
        - `[SecureBoot <String>]`: When Secure Boot is enabled, the core components must have the correct cryptographic signatures
        - `[SecureBootConfigurationPolicyFingerPrint <String>]`: Fingerprint of the Custom Secure Boot Configuration Policy
        - `[TestSigning <String>]`: When test signing is allowed, the device does not enforce signature validation during boot
        - `[TpmVersion <String>]`: The security version number of the Boot Application
        - `[VirtualSecureMode <String>]`: VSM is a container that protects high value assets from a compromised kernel
        - `[WindowsPe <String>]`: Operating system running with limited services that is used to prepare a computer for Windows
      - `[DeviceName <String>]`: Name of the device. This property is read-only.
      - `[DeviceRegistrationState <String>]`: deviceRegistrationState
      - `[EasActivated <Boolean?>]`: Whether the device is Exchange ActiveSync activated. This property is read-only.
      - `[EasActivationDateTime <DateTime?>]`: Exchange ActivationSync activation time of the device. This property is read-only.
      - `[EasDeviceId <String>]`: Exchange ActiveSync Id of the device. This property is read-only.
      - `[EmailAddress <String>]`: Email(s) for the user associated with the device. This property is read-only.
      - `[EnrolledDateTime <DateTime?>]`: Enrollment time of the device. This property is read-only.
      - `[ExchangeAccessState <String>]`: deviceManagementExchangeAccessState
      - `[ExchangeAccessStateReason <String>]`: deviceManagementExchangeAccessStateReason
      - `[ExchangeLastSuccessfulSyncDateTime <DateTime?>]`: Last time the device contacted Exchange. This property is read-only.
      - `[FreeStorageSpaceInBytes <Int64?>]`: Free Storage in Bytes. This property is read-only.
      - `[Imei <String>]`: IMEI. This property is read-only.
      - `[IsEncrypted <Boolean?>]`: Device encryption status. This property is read-only.
      - `[IsSupervised <Boolean?>]`: Device supervised status. This property is read-only.
      - `[JailBroken <String>]`: whether the device is jail broken or rooted. This property is read-only.
      - `[LastSyncDateTime <DateTime?>]`: The date and time that the device last completed a successful sync with Intune. This property is read-only.
      - `[ManagedDeviceName <String>]`: Automatically generated name to identify a device. Can be overwritten to a user friendly name.
      - `[ManagedDeviceOwnerType <String>]`: managedDeviceOwnerType
      - `[ManagementAgent <String>]`: 
      - `[Manufacturer <String>]`: Manufacturer of the device. This property is read-only.
      - `[Meid <String>]`: MEID. This property is read-only.
      - `[Model <String>]`: Model of the device. This property is read-only.
      - `[OSVersion <String>]`: Operating system version of the device. This property is read-only.
      - `[OperatingSystem <String>]`: Operating system of the device. Windows, iOS, etc. This property is read-only.
      - `[PartnerReportedThreatState <String>]`: managedDevicePartnerReportedHealthState
      - `[PhoneNumber <String>]`: Phone number of the device. This property is read-only.
      - `[RemoteAssistanceSessionErrorDetails <String>]`: An error string that identifies issues when creating Remote Assistance session objects. This property is read-only.
      - `[RemoteAssistanceSessionUrl <String>]`: Url that allows a Remote Assistance session to be established with the device. This property is read-only.
      - `[SerialNumber <String>]`: SerialNumber. This property is read-only.
      - `[SubscriberCarrier <String>]`: Subscriber Carrier. This property is read-only.
      - `[TotalStorageSpaceInBytes <Int64?>]`: Total Storage in Bytes. This property is read-only.
      - `[UserDisplayName <String>]`: User display name. This property is read-only.
      - `[UserId <String>]`: Unique Identifier for the user associated with the device. This property is read-only.
      - `[UserPrincipalName <String>]`: Device user principal name. This property is read-only.
      - `[WiFiMacAddress <String>]`: Wi-Fi MAC. This property is read-only.
    - `[SizeInByte <Int64?>]`: Discovered application size in bytes. Read-only
    - `[Version <String>]`: Version of the discovered application. Read-only
  - `[DeviceCategories <IMicrosoftGraphDeviceCategory2[]>]`: The list of device categories with the tenant.
  - `[DeviceCompliancePolicies <IMicrosoftGraphDeviceCompliancePolicy1[]>]`: The device compliance policies.
    - `[Id <String>]`: Read-only.
    - `[Assignments <IMicrosoftGraphDeviceCompliancePolicyAssignment1[]>]`: The collection of assignments for this compliance policy.
      - `[Id <String>]`: Read-only.
      - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
    - `[CreatedDateTime <DateTime?>]`: DateTime the object was created.
    - `[Description <String>]`: Admin provided description of the Device Configuration.
    - `[DeviceSettingStateSummaries <IMicrosoftGraphSettingStateDeviceSummary[]>]`: Compliance Setting State Device Summary
      - `[Id <String>]`: Read-only.
      - `[CompliantDeviceCount <Int32?>]`: Device Compliant count for the setting
      - `[ConflictDeviceCount <Int32?>]`: Device conflict error count for the setting
      - `[ErrorDeviceCount <Int32?>]`: Device error count for the setting
      - `[InstancePath <String>]`: Name of the InstancePath for the setting
      - `[NonCompliantDeviceCount <Int32?>]`: Device NonCompliant count for the setting
      - `[NotApplicableDeviceCount <Int32?>]`: Device Not Applicable count for the setting
      - `[RemediatedDeviceCount <Int32?>]`: Device Compliant count for the setting
      - `[SettingName <String>]`: Name of the setting
      - `[UnknownDeviceCount <Int32?>]`: Device Unkown count for the setting
    - `[DeviceStatusOverview <IMicrosoftGraphDeviceComplianceDeviceOverview1>]`: deviceComplianceDeviceOverview
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[ConfigurationVersion <Int32?>]`: Version of the policy for that overview
      - `[ErrorCount <Int32?>]`: Number of error devices
      - `[FailedCount <Int32?>]`: Number of failed devices
      - `[LastUpdateDateTime <DateTime?>]`: Last update time
      - `[NotApplicableCount <Int32?>]`: Number of not applicable devices
      - `[PendingCount <Int32?>]`: Number of pending devices
      - `[SuccessCount <Int32?>]`: Number of succeeded devices
    - `[DeviceStatuses <IMicrosoftGraphDeviceComplianceDeviceStatus1[]>]`: List of DeviceComplianceDeviceStatus.
      - `[Id <String>]`: Read-only.
      - `[ComplianceGracePeriodExpirationDateTime <DateTime?>]`: The DateTime when device compliance grace period expires
      - `[DeviceDisplayName <String>]`: Device name of the DevicePolicyStatus.
      - `[DeviceModel <String>]`: The device model that is being reported
      - `[LastReportedDateTime <DateTime?>]`: Last modified date time of the policy report.
      - `[Status <String>]`: complianceStatus
      - `[UserName <String>]`: The User Name that is being reported
      - `[UserPrincipalName <String>]`: UserPrincipalName.
    - `[DisplayName <String>]`: Admin provided name of the device configuration.
    - `[LastModifiedDateTime <DateTime?>]`: DateTime the object was last modified.
    - `[ScheduledActionsForRule <IMicrosoftGraphDeviceComplianceScheduledActionForRule1[]>]`: The list of scheduled action for this rule
      - `[Id <String>]`: Read-only.
      - `[RuleName <String>]`: Name of the rule which this scheduled action applies to.
      - `[ScheduledActionConfigurations <IMicrosoftGraphDeviceComplianceActionItem1[]>]`: The list of scheduled action configurations for this compliance policy.
        - `[Id <String>]`: Read-only.
        - `[ActionType <String>]`: 
        - `[GracePeriodHours <Int32?>]`: Number of hours to wait till the action will be enforced. Valid values 0 to 8760
        - `[NotificationMessageCcList <String[]>]`: A list of group IDs to speicify who to CC this notification message to.
        - `[NotificationTemplateId <String>]`: What notification Message template to use
    - `[UserStatusOverview <IMicrosoftGraphDeviceComplianceUserOverview1>]`: deviceComplianceUserOverview
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[ConfigurationVersion <Int32?>]`: Version of the policy for that overview
      - `[ErrorCount <Int32?>]`: Number of error Users
      - `[FailedCount <Int32?>]`: Number of failed Users
      - `[LastUpdateDateTime <DateTime?>]`: Last update time
      - `[NotApplicableCount <Int32?>]`: Number of not applicable users
      - `[PendingCount <Int32?>]`: Number of pending Users
      - `[SuccessCount <Int32?>]`: Number of succeeded Users
    - `[UserStatuses <IMicrosoftGraphDeviceComplianceUserStatus[]>]`: List of DeviceComplianceUserStatus.
      - `[Id <String>]`: Read-only.
      - `[DevicesCount <Int32?>]`: Devices count for that user.
      - `[LastReportedDateTime <DateTime?>]`: Last modified date time of the policy report.
      - `[Status <String>]`: complianceStatus
      - `[UserDisplayName <String>]`: User name of the DevicePolicyStatus.
      - `[UserPrincipalName <String>]`: UserPrincipalName.
    - `[Version <Int32?>]`: Version of the device configuration.
  - `[DeviceCompliancePolicyDeviceStateSummary <IMicrosoftGraphDeviceCompliancePolicyDeviceStateSummary>]`: deviceCompliancePolicyDeviceStateSummary
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[CompliantDeviceCount <Int32?>]`: Number of compliant devices
    - `[ConfigManagerCount <Int32?>]`: Number of devices that have compliance managed by System Center Configuration Manager
    - `[ConflictDeviceCount <Int32?>]`: Number of conflict devices
    - `[ErrorDeviceCount <Int32?>]`: Number of error devices
    - `[InGracePeriodCount <Int32?>]`: Number of devices that are in grace period
    - `[NonCompliantDeviceCount <Int32?>]`: Number of NonCompliant devices
    - `[NotApplicableDeviceCount <Int32?>]`: Number of not applicable devices
    - `[RemediatedDeviceCount <Int32?>]`: Number of remediated devices
    - `[UnknownDeviceCount <Int32?>]`: Number of unknown devices
  - `[DeviceCompliancePolicySettingStateSummaries <IMicrosoftGraphDeviceCompliancePolicySettingStateSummary1[]>]`: The summary states of compliance policy settings for this account.
    - `[Id <String>]`: Read-only.
    - `[CompliantDeviceCount <Int32?>]`: Number of compliant devices
    - `[ConflictDeviceCount <Int32?>]`: Number of conflict devices
    - `[DeviceComplianceSettingStates <IMicrosoftGraphDeviceComplianceSettingState1[]>]`: Not yet documented
      - `[Id <String>]`: Read-only.
      - `[ComplianceGracePeriodExpirationDateTime <DateTime?>]`: The DateTime when device compliance grace period expires
      - `[DeviceId <String>]`: The Device Id that is being reported
      - `[DeviceModel <String>]`: The device model that is being reported
      - `[DeviceName <String>]`: The Device Name that is being reported
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
  - `[DeviceConfigurationDeviceStateSummaries <IMicrosoftGraphDeviceConfigurationDeviceStateSummary>]`: deviceConfigurationDeviceStateSummary
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[CompliantDeviceCount <Int32?>]`: Number of compliant devices
    - `[ConflictDeviceCount <Int32?>]`: Number of conflict devices
    - `[ErrorDeviceCount <Int32?>]`: Number of error devices
    - `[NonCompliantDeviceCount <Int32?>]`: Number of NonCompliant devices
    - `[NotApplicableDeviceCount <Int32?>]`: Number of not applicable devices
    - `[RemediatedDeviceCount <Int32?>]`: Number of remediated devices
    - `[UnknownDeviceCount <Int32?>]`: Number of unknown devices
  - `[DeviceConfigurations <IMicrosoftGraphDeviceConfiguration1[]>]`: The device configurations.
    - `[Id <String>]`: Read-only.
    - `[Assignments <IMicrosoftGraphDeviceConfigurationAssignment1[]>]`: The list of assignments for the device configuration profile.
      - `[Id <String>]`: Read-only.
      - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
    - `[CreatedDateTime <DateTime?>]`: DateTime the object was created.
    - `[Description <String>]`: Admin provided description of the Device Configuration.
    - `[DeviceSettingStateSummaries <IMicrosoftGraphSettingStateDeviceSummary[]>]`: Device Configuration Setting State Device Summary
    - `[DeviceStatusOverview <IMicrosoftGraphDeviceConfigurationDeviceOverview1>]`: deviceConfigurationDeviceOverview
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[ConfigurationVersion <Int32?>]`: Version of the policy for that overview
      - `[ErrorCount <Int32?>]`: Number of error devices
      - `[FailedCount <Int32?>]`: Number of failed devices
      - `[LastUpdateDateTime <DateTime?>]`: Last update time
      - `[NotApplicableCount <Int32?>]`: Number of not applicable devices
      - `[PendingCount <Int32?>]`: Number of pending devices
      - `[SuccessCount <Int32?>]`: Number of succeeded devices
    - `[DeviceStatuses <IMicrosoftGraphDeviceConfigurationDeviceStatus1[]>]`: Device configuration installation status by device.
      - `[Id <String>]`: Read-only.
      - `[ComplianceGracePeriodExpirationDateTime <DateTime?>]`: The DateTime when device compliance grace period expires
      - `[DeviceDisplayName <String>]`: Device name of the DevicePolicyStatus.
      - `[DeviceModel <String>]`: The device model that is being reported
      - `[LastReportedDateTime <DateTime?>]`: Last modified date time of the policy report.
      - `[Status <String>]`: complianceStatus
      - `[UserName <String>]`: The User Name that is being reported
      - `[UserPrincipalName <String>]`: UserPrincipalName.
    - `[DisplayName <String>]`: Admin provided name of the device configuration.
    - `[LastModifiedDateTime <DateTime?>]`: DateTime the object was last modified.
    - `[UserStatusOverview <IMicrosoftGraphDeviceConfigurationUserOverview1>]`: deviceConfigurationUserOverview
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[ConfigurationVersion <Int32?>]`: Version of the policy for that overview
      - `[ErrorCount <Int32?>]`: Number of error Users
      - `[FailedCount <Int32?>]`: Number of failed Users
      - `[LastUpdateDateTime <DateTime?>]`: Last update time
      - `[NotApplicableCount <Int32?>]`: Number of not applicable users
      - `[PendingCount <Int32?>]`: Number of pending Users
      - `[SuccessCount <Int32?>]`: Number of succeeded Users
    - `[UserStatuses <IMicrosoftGraphDeviceConfigurationUserStatus[]>]`: Device configuration installation status by user.
      - `[Id <String>]`: Read-only.
      - `[DevicesCount <Int32?>]`: Devices count for that user.
      - `[LastReportedDateTime <DateTime?>]`: Last modified date time of the policy report.
      - `[Status <String>]`: complianceStatus
      - `[UserDisplayName <String>]`: User name of the DevicePolicyStatus.
      - `[UserPrincipalName <String>]`: UserPrincipalName.
    - `[Version <Int32?>]`: Version of the device configuration.
  - `[DeviceEnrollmentConfigurations <IMicrosoftGraphDeviceEnrollmentConfiguration1[]>]`: The list of device enrollment configurations
    - `[Id <String>]`: Read-only.
    - `[Assignments <IMicrosoftGraphEnrollmentConfigurationAssignment[]>]`: The list of group assignments for the device configuration profile
      - `[Id <String>]`: Read-only.
      - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
    - `[CreatedDateTime <DateTime?>]`: Created date time in UTC of the device enrollment configuration
    - `[Description <String>]`: The description of the device enrollment configuration
    - `[DisplayName <String>]`: The display name of the device enrollment configuration
    - `[LastModifiedDateTime <DateTime?>]`: Last modified date time in UTC of the device enrollment configuration
    - `[Priority <Int32?>]`: Priority is used when a user exists in multiple groups that are assigned enrollment configuration. Users are subject only to the configuration with the lowest priority value.
    - `[Version <Int32?>]`: The version of the device enrollment configuration
  - `[DeviceManagementPartners <IMicrosoftGraphDeviceManagementPartner1[]>]`: The list of Device Management Partners configured by the tenant.
    - `[Id <String>]`: Read-only.
    - `[DisplayName <String>]`: Partner display name
    - `[IsConfigured <Boolean?>]`: Whether device management partner is configured or not
    - `[LastHeartbeatDateTime <DateTime?>]`: Timestamp of last heartbeat after admin enabled option Connect to Device management Partner
    - `[PartnerAppType <String>]`: deviceManagementPartnerAppType
    - `[PartnerState <String>]`: deviceManagementPartnerTenantState
    - `[SingleTenantAppId <String>]`: Partner Single tenant App id
    - `[WhenPartnerDevicesWillBeMarkedAsNonCompliantDateTime <DateTime?>]`: DateTime in UTC when PartnerDevices will be marked as NonCompliant
    - `[WhenPartnerDevicesWillBeRemovedDateTime <DateTime?>]`: DateTime in UTC when PartnerDevices will be removed
  - `[ExchangeConnectors <IMicrosoftGraphDeviceManagementExchangeConnector[]>]`: The list of Exchange Connectors configured by the tenant.
    - `[Id <String>]`: Read-only.
    - `[ConnectorServerName <String>]`: The name of the server hosting the Exchange Connector.
    - `[ExchangeAlias <String>]`: An alias assigned to the Exchange server
    - `[ExchangeConnectorType <String>]`: deviceManagementExchangeConnectorType
    - `[ExchangeOrganization <String>]`: Exchange Organization to the Exchange server
    - `[LastSyncDateTime <DateTime?>]`: Last sync time for the Exchange Connector
    - `[PrimarySmtpAddress <String>]`: Email address used to configure the Service To Service Exchange Connector.
    - `[ServerName <String>]`: The name of the Exchange server.
    - `[Status <String>]`: deviceManagementExchangeConnectorStatus
    - `[Version <String>]`: The version of the ExchangeConnectorAgent
  - `[IntuneAccountId <String>]`: Intune Account ID for given tenant
  - `[IntuneBrand <IMicrosoftGraphIntuneBrand1>]`: intuneBrand contains data which is used in customizing the appearance of the Company Portal applications as well as the end user web portal.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[ContactItEmailAddress <String>]`: Email address of the person/organization responsible for IT support.
    - `[ContactItName <String>]`: Name of the person/organization responsible for IT support.
    - `[ContactItNotes <String>]`: Text comments regarding the person/organization responsible for IT support.
    - `[ContactItPhoneNumber <String>]`: Phone number of the person/organization responsible for IT support.
    - `[DarkBackgroundLogo <IMicrosoftGraphMimeContent>]`: Contains properties for a generic mime content.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Type <String>]`: Indicates the content mime type.
      - `[Value <Byte[]>]`: The byte array that contains the actual content.
    - `[DisplayName <String>]`: Company/organization name that is displayed to end users.
    - `[LightBackgroundLogo <IMicrosoftGraphMimeContent>]`: Contains properties for a generic mime content.
    - `[OnlineSupportSiteName <String>]`: Display name of the company/organization's IT helpdesk site.
    - `[OnlineSupportSiteUrl <String>]`: URL to the company/organization's IT helpdesk site.
    - `[PrivacyUrl <String>]`: URL to the company/organization's privacy policy.
    - `[ShowDisplayNameNextToLogo <Boolean?>]`: Boolean that represents whether the administrator-supplied display name will be shown next to the logo image.
    - `[ShowLogo <Boolean?>]`: Boolean that represents whether the administrator-supplied logo images are shown or not shown.
    - `[ShowNameNextToLogo <Boolean?>]`: Boolean that represents whether the administrator-supplied display name will be shown next to the logo image.
    - `[ThemeColor <IMicrosoftGraphRgbColor>]`: Color in RGB.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[B <Int32?>]`: Blue value
      - `[G <Int32?>]`: Green value
      - `[R <Int32?>]`: Red value
  - `[IosUpdateStatuses <IMicrosoftGraphIosUpdateDeviceStatus1[]>]`: The IOS software update installation statuses for this account.
    - `[Id <String>]`: Read-only.
    - `[ComplianceGracePeriodExpirationDateTime <DateTime?>]`: The DateTime when device compliance grace period expires
    - `[DeviceDisplayName <String>]`: Device name of the DevicePolicyStatus.
    - `[DeviceId <String>]`: The device id that is being reported.
    - `[DeviceModel <String>]`: The device model that is being reported
    - `[InstallStatus <String>]`: 
    - `[LastReportedDateTime <DateTime?>]`: Last modified date time of the policy report.
    - `[OSVersion <String>]`: The device version that is being reported.
    - `[Status <String>]`: complianceStatus
    - `[UserId <String>]`: The User id that is being reported.
    - `[UserName <String>]`: The User Name that is being reported
    - `[UserPrincipalName <String>]`: UserPrincipalName.
  - `[ManagedDeviceOverview <IMicrosoftGraphManagedDeviceOverview1>]`: Summary data for managed devices
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[DeviceExchangeAccessStateSummary <IMicrosoftGraphDeviceExchangeAccessStateSummary>]`: Device Exchange Access State summary
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[AllowedDeviceCount <Int32?>]`: Total count of devices with Exchange Access State: Allowed.
      - `[BlockedDeviceCount <Int32?>]`: Total count of devices with Exchange Access State: Blocked.
      - `[QuarantinedDeviceCount <Int32?>]`: Total count of devices with Exchange Access State: Quarantined.
      - `[UnavailableDeviceCount <Int32?>]`: Total count of devices for which no Exchange Access State could be found.
      - `[UnknownDeviceCount <Int32?>]`: Total count of devices with Exchange Access State: Unknown.
    - `[DeviceOperatingSystemSummary <IMicrosoftGraphDeviceOperatingSystemSummary>]`: Device operating system summary.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[AndroidCount <Int32?>]`: Number of android device count.
      - `[IosCount <Int32?>]`: Number of iOS device count.
      - `[MacOSCount <Int32?>]`: Number of Mac OS X device count.
      - `[UnknownCount <Int32?>]`: Number of unknown device count.
      - `[WindowsCount <Int32?>]`: Number of Windows device count.
      - `[WindowsMobileCount <Int32?>]`: Number of Windows mobile device count.
    - `[DualEnrolledDeviceCount <Int32?>]`: The number of devices enrolled in both MDM and EAS
    - `[EnrolledDeviceCount <Int32?>]`: Total enrolled device count. Does not include PC devices managed via Intune PC Agent
    - `[MdmEnrolledCount <Int32?>]`: The number of devices enrolled in MDM
  - `[ManagedDevices <IMicrosoftGraphManagedDevice1[]>]`: The list of managed devices.
  - `[MobileThreatDefenseConnectors <IMicrosoftGraphMobileThreatDefenseConnector1[]>]`: The list of Mobile threat Defense connectors configured by the tenant.
    - `[Id <String>]`: Read-only.
    - `[AndroidDeviceBlockedOnMissingPartnerData <Boolean?>]`: For Android, set whether Intune must receive data from the data sync partner prior to marking a device compliant
    - `[AndroidEnabled <Boolean?>]`: For Android, set whether data from the data sync partner should be used during compliance evaluations
    - `[IosDeviceBlockedOnMissingPartnerData <Boolean?>]`: For IOS, set whether Intune must receive data from the data sync partner prior to marking a device compliant
    - `[IosEnabled <Boolean?>]`: For IOS, get or set whether data from the data sync partner should be used during compliance evaluations
    - `[LastHeartbeatDateTime <DateTime?>]`: DateTime of last Heartbeat recieved from the Data Sync Partner
    - `[PartnerState <String>]`: mobileThreatPartnerTenantState
    - `[PartnerUnresponsivenessThresholdInDays <Int32?>]`: Get or Set days the per tenant tolerance to unresponsiveness for this partner integration
    - `[PartnerUnsupportedOSVersionBlocked <Boolean?>]`: Get or set whether to block devices on the enabled platforms that do not meet the minimum version requirements of the Data Sync Partner
  - `[NotificationMessageTemplates <IMicrosoftGraphNotificationMessageTemplate1[]>]`: The Notification Message Templates.
    - `[Id <String>]`: Read-only.
    - `[BrandingOptions <String>]`: 
    - `[DefaultLocale <String>]`: The default locale to fallback onto when the requested locale is not available.
    - `[DisplayName <String>]`: Display name for the Notification Message Template.
    - `[LastModifiedDateTime <DateTime?>]`: DateTime the object was last modified.
    - `[LocalizedNotificationMessages <IMicrosoftGraphLocalizedNotificationMessage[]>]`: The list of localized messages for this Notification Message Template.
      - `[Id <String>]`: Read-only.
      - `[IsDefault <Boolean?>]`: Flag to indicate whether or not this is the default locale for language fallback. This flag can only be set. To unset, set this property to true on another Localized Notification Message.
      - `[LastModifiedDateTime <DateTime?>]`: DateTime the object was last modified.
      - `[Locale <String>]`: The Locale for which this message is destined.
      - `[MessageTemplate <String>]`: The Message Template content.
      - `[Subject <String>]`: The Message Template Subject.
  - `[RemoteAssistancePartners <IMicrosoftGraphRemoteAssistancePartner1[]>]`: The remote assist partners.
    - `[Id <String>]`: Read-only.
    - `[DisplayName <String>]`: Display name of the partner.
    - `[LastConnectionDateTime <DateTime?>]`: Timestamp of the last request sent to Intune by the TEM partner.
    - `[OnboardingStatus <String>]`: remoteAssistanceOnboardingStatus
    - `[OnboardingUrl <String>]`: URL of the partner's onboarding portal, where an administrator can configure their Remote Assistance service.
  - `[ResourceOperations <IMicrosoftGraphResourceOperation1[]>]`: The Resource Operations.
    - `[Id <String>]`: Read-only.
    - `[ActionName <String>]`: Type of action this operation is going to perform. The actionName should be concise and limited to as few words as possible.
    - `[Description <String>]`: Description of the resource operation. The description is used in mouse-over text for the operation when shown in the Azure Portal.
    - `[ResourceName <String>]`: Name of the Resource this operation is performed on.
  - `[RoleAssignments <IMicrosoftGraphDeviceAndAppManagementRoleAssignment1[]>]`: The Role Assignments.
    - `[Description <String>]`: Description of the Role Assignment.
    - `[DisplayName <String>]`: The display or friendly name of the role Assignment.
    - `[ResourceScopes <String[]>]`: List of ids of role scope member security groups.  These are IDs from Azure Active Directory.
    - `[RoleDefinition <IMicrosoftGraphRoleDefinition1>]`: The Role Definition resource. The role definition is the foundation of role based access in Intune. The role combines an Intune resource such as a Mobile App and associated role permissions such as Create or Read for the resource. There are two types of roles, built-in and custom. Built-in roles cannot be modified. Both built-in roles and custom roles must have assignments to be enforced. Create custom roles if you want to define a role that allows any of the available resources and role permissions to be combined into a single role.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[Description <String>]`: Description of the Role definition.
      - `[DisplayName <String>]`: Display Name of the Role definition.
      - `[IsBuiltIn <Boolean?>]`: Type of Role. Set to True if it is built-in, or set to False if it is a custom role definition.
      - `[RoleAssignments <IMicrosoftGraphRoleAssignment[]>]`: List of Role assignments for this role definition.
        - `[Id <String>]`: Read-only.
        - `[Description <String>]`: Description of the Role Assignment.
        - `[DisplayName <String>]`: The display or friendly name of the role Assignment.
        - `[ResourceScopes <String[]>]`: List of ids of role scope member security groups.  These are IDs from Azure Active Directory.
        - `[RoleDefinition <IMicrosoftGraphRoleDefinition1>]`: The Role Definition resource. The role definition is the foundation of role based access in Intune. The role combines an Intune resource such as a Mobile App and associated role permissions such as Create or Read for the resource. There are two types of roles, built-in and custom. Built-in roles cannot be modified. Both built-in roles and custom roles must have assignments to be enforced. Create custom roles if you want to define a role that allows any of the available resources and role permissions to be combined into a single role.
      - `[RolePermissions <IMicrosoftGraphRolePermission[]>]`: List of Role Permissions this role is allowed to perform. These must match the actionName that is defined as part of the rolePermission.
        - `[ResourceActions <IMicrosoftGraphResourceAction[]>]`: Resource Actions each containing a set of allowed and not allowed permissions.
          - `[AllowedResourceActions <String[]>]`: Allowed Actions
          - `[NotAllowedResourceActions <String[]>]`: Not Allowed Actions.
    - `[Id <String>]`: Read-only.
    - `[Members <String[]>]`: The list of ids of role member security groups. These are IDs from Azure Active Directory.
  - `[RoleDefinitions <IMicrosoftGraphRoleDefinition1[]>]`: The Role Definitions.
  - `[Settings <IMicrosoftGraphDeviceManagementSettings1>]`: deviceManagementSettings
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DeviceComplianceCheckinThresholdDays <Int32?>]`: The number of days a device is allowed to go without checking in to remain compliant.
    - `[IsScheduledActionEnabled <Boolean?>]`: Is feature enabled or not for scheduled action for rule.
    - `[SecureByDefault <Boolean?>]`: Device should be noncompliant when there is no compliance policy targeted when this is true
  - `[SoftwareUpdateStatusSummary <IMicrosoftGraphSoftwareUpdateStatusSummary>]`: softwareUpdateStatusSummary
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[CompliantDeviceCount <Int32?>]`: Number of compliant devices.
    - `[CompliantUserCount <Int32?>]`: Number of compliant users.
    - `[ConflictDeviceCount <Int32?>]`: Number of conflict devices.
    - `[ConflictUserCount <Int32?>]`: Number of conflict users.
    - `[DisplayName <String>]`: The name of the policy.
    - `[ErrorDeviceCount <Int32?>]`: Number of devices had error.
    - `[ErrorUserCount <Int32?>]`: Number of users had error.
    - `[NonCompliantDeviceCount <Int32?>]`: Number of non compliant devices.
    - `[NonCompliantUserCount <Int32?>]`: Number of non compliant users.
    - `[NotApplicableDeviceCount <Int32?>]`: Number of not applicable devices.
    - `[NotApplicableUserCount <Int32?>]`: Number of not applicable users.
    - `[RemediatedDeviceCount <Int32?>]`: Number of remediated devices.
    - `[RemediatedUserCount <Int32?>]`: Number of remediated users.
    - `[UnknownDeviceCount <Int32?>]`: Number of unknown devices.
    - `[UnknownUserCount <Int32?>]`: Number of unknown users.
  - `[SubscriptionState <String>]`: deviceManagementSubscriptionState
  - `[TelecomExpenseManagementPartners <IMicrosoftGraphTelecomExpenseManagementPartner[]>]`: The telecom expense management partners.
    - `[Id <String>]`: Read-only.
    - `[AppAuthorized <Boolean?>]`: Whether the partner's AAD app has been authorized to access Intune.
    - `[DisplayName <String>]`: Display name of the TEM partner.
    - `[Enabled <Boolean?>]`: Whether Intune's connection to the TEM service is currently enabled or disabled.
    - `[LastConnectionDateTime <DateTime?>]`: Timestamp of the last request sent to Intune by the TEM partner.
    - `[Url <String>]`: URL of the TEM partner's administrative control panel, where an administrator can configure their TEM service.
  - `[TermsAndConditions <IMicrosoftGraphTermsAndConditions1[]>]`: The terms and conditions associated with device management of the company.
    - `[Id <String>]`: Read-only.
    - `[AcceptanceStatement <String>]`: Administrator-supplied explanation of the terms and conditions, typically describing what it means to accept the terms and conditions set out in the T&C policy. This is shown to the user on prompts to accept the T&C policy.
    - `[AcceptanceStatuses <IMicrosoftGraphTermsAndConditionsAcceptanceStatus[]>]`: The list of acceptance statuses for this T&C policy.
      - `[Id <String>]`: Read-only.
      - `[AcceptedDateTime <DateTime?>]`: DateTime when the terms were last accepted by the user.
      - `[AcceptedVersion <Int32?>]`: Most recent version number of the T&C accepted by the user.
      - `[TermsAndConditions <IMicrosoftGraphTermsAndConditions1>]`: A termsAndConditions entity represents the metadata and contents of a given Terms and Conditions (T&C) policy. T&C policies' contents are presented to users upon their first attempt to enroll into Intune and subsequently upon edits where an administrator has required re-acceptance. They enable administrators to communicate the provisions to which a user must agree in order to have devices enrolled into Intune.
      - `[UserDisplayName <String>]`: Display name of the user whose acceptance the entity represents.
      - `[UserPrincipalName <String>]`: The userPrincipalName of the User that accepted the term.
    - `[Assignments <IMicrosoftGraphTermsAndConditionsAssignment[]>]`: The list of assignments for this T&C policy.
      - `[Id <String>]`: Read-only.
      - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
    - `[BodyText <String>]`: Administrator-supplied body text of the terms and conditions, typically the terms themselves. This is shown to the user on prompts to accept the T&C policy.
    - `[CreatedDateTime <DateTime?>]`: DateTime the object was created.
    - `[Description <String>]`: Administrator-supplied description of the T&C policy.
    - `[DisplayName <String>]`: Administrator-supplied name for the T&C policy.
    - `[LastModifiedDateTime <DateTime?>]`: DateTime the object was last modified.
    - `[Title <String>]`: Administrator-supplied title of the terms and conditions. This is shown to the user on prompts to accept the T&C policy.
    - `[Version <Int32?>]`: Integer indicating the current version of the terms. Incremented when an administrator makes a change to the terms and wishes to require users to re-accept the modified T&C policy.
  - `[TroubleshootingEvents <IMicrosoftGraphDeviceManagementTroubleshootingEvent1[]>]`: The list of troubleshooting events for the tenant.
    - `[Id <String>]`: Read-only.
    - `[CorrelationId <String>]`: Id used for tracing the failure in the service.
    - `[EventDateTime <DateTime?>]`: Time when the event occurred .
  - `[WindowsInformationProtectionAppLearningSummaries <IMicrosoftGraphWindowsInformationProtectionAppLearningSummary[]>]`: The windows information protection app learning summaries.
    - `[Id <String>]`: Read-only.
    - `[ApplicationName <String>]`: Application Name
    - `[ApplicationType <String>]`: applicationType
    - `[DeviceCount <Int32?>]`: Device Count
  - `[WindowsInformationProtectionNetworkLearningSummaries <IMicrosoftGraphWindowsInformationProtectionNetworkLearningSummary[]>]`: The windows information protection network learning summaries.
    - `[Id <String>]`: Read-only.
    - `[DeviceCount <Int32?>]`: Device Count
    - `[Url <String>]`: Website url

COMPLIANCEMANAGEMENTPARTNERS <IMicrosoftGraphComplianceManagementPartner1[]>: The list of Compliance Management Partners configured by the tenant.
  - `[Id <String>]`: Read-only.
  - `[AndroidEnrollmentAssignments <IMicrosoftGraphComplianceManagementPartnerAssignment[]>]`: User groups which enroll Android devices through partner.
    - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[AndroidOnboarded <Boolean?>]`: Partner onboarded for Android devices.
  - `[DisplayName <String>]`: Partner display name
  - `[IosEnrollmentAssignments <IMicrosoftGraphComplianceManagementPartnerAssignment[]>]`: User groups which enroll ios devices through partner.
  - `[IosOnboarded <Boolean?>]`: Partner onboarded for ios devices.
  - `[LastHeartbeatDateTime <DateTime?>]`: Timestamp of last heartbeat after admin onboarded to the compliance management partner
  - `[MacOSEnrollmentAssignments <IMicrosoftGraphComplianceManagementPartnerAssignment[]>]`: User groups which enroll Mac devices through partner.
  - `[MacOSOnboarded <Boolean?>]`: Partner onboarded for Mac devices.
  - `[PartnerState <String>]`: deviceManagementPartnerTenantState

CONDITIONALACCESSSETTINGS <IMicrosoftGraphOnPremisesConditionalAccessSettings>: Singleton entity which represents the Exchange OnPremises Conditional Access Settings for a tenant.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[Enabled <Boolean?>]`: Indicates if on premises conditional access is enabled for this organization
  - `[ExcludedGroups <String[]>]`: User groups that will be exempt by on premises conditional access. All users in these groups will be exempt from the conditional access policy.
  - `[IncludedGroups <String[]>]`: User groups that will be targeted by on premises conditional access. All users in these groups will be required to have mobile device managed and compliant for mail access.
  - `[OverrideDefaultRule <Boolean?>]`: Override the default access rule when allowing a device to ensure access is granted.

DETECTEDAPPS <IMicrosoftGraphDetectedApp1[]>: The list of detected apps associated with a device.
  - `[Id <String>]`: Read-only.
  - `[DeviceCount <Int32?>]`: The number of devices that have installed this application
  - `[DisplayName <String>]`: Name of the discovered application. Read-only
  - `[ManagedDevices <IMicrosoftGraphManagedDevice1[]>]`: The devices that have the discovered application installed
    - `[Id <String>]`: Read-only.
    - `[ActivationLockBypassCode <String>]`: Code that allows the Activation Lock on a device to be bypassed. This property is read-only.
    - `[AndroidSecurityPatchLevel <String>]`: Android security patch level. This property is read-only.
    - `[AzureAdDeviceId <String>]`: The unique identifier for the Azure Active Directory device. Read only. This property is read-only.
    - `[AzureAdRegistered <Boolean?>]`: Whether the device is Azure Active Directory registered. This property is read-only.
    - `[ComplianceGracePeriodExpirationDateTime <DateTime?>]`: The DateTime when device compliance grace period expires. This property is read-only.
    - `[ComplianceState <String>]`: complianceState
    - `[ConfigurationManagerClientEnabledFeatures <IMicrosoftGraphConfigurationManagerClientEnabledFeatures1>]`: configuration Manager client enabled features
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[CompliancePolicy <Boolean?>]`: Whether compliance policy is managed by Intune
      - `[DeviceConfiguration <Boolean?>]`: Whether device configuration is managed by Intune
      - `[Inventory <Boolean?>]`: Whether inventory is managed by Intune
      - `[ModernApps <Boolean?>]`: Whether modern application is managed by Intune
      - `[ResourceAccess <Boolean?>]`: Whether resource access is managed by Intune
      - `[WindowsUpdateForBusiness <Boolean?>]`: Whether Windows Update for Business is managed by Intune
    - `[DeviceActionResults <IMicrosoftGraphDeviceActionResult[]>]`: List of ComplexType deviceActionResult objects. This property is read-only.
      - `[ActionName <String>]`: Action name
      - `[ActionState <String>]`: actionState
      - `[LastUpdatedDateTime <DateTime?>]`: Time the action state was last updated
      - `[StartDateTime <DateTime?>]`: Time the action was initiated
    - `[DeviceCategory <IMicrosoftGraphDeviceCategory2>]`: Device categories provides a way to organize your devices. Using device categories, company administrators can define their own categories that make sense to their company. These categories can then be applied to a device in the Intune Azure console or selected by a user during device enrollment. You can filter reports and create dynamic Azure Active Directory device groups based on device categories.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[Description <String>]`: Optional description for the device category.
      - `[DisplayName <String>]`: Display name for the device category.
    - `[DeviceCategoryDisplayName <String>]`: Device category display name. This property is read-only.
    - `[DeviceCompliancePolicyStates <IMicrosoftGraphDeviceCompliancePolicyState1[]>]`: Device compliance policy states for this device.
      - `[Id <String>]`: Read-only.
      - `[DisplayName <String>]`: The name of the policy for this policyBase
      - `[PlatformType <String>]`: 
      - `[SettingCount <Int32?>]`: Count of how many setting a policy holds
      - `[SettingStates <IMicrosoftGraphDeviceCompliancePolicySettingState[]>]`: 
        - `[CurrentValue <String>]`: Current value of setting on device
        - `[ErrorCode <Int64?>]`: Error code for the setting
        - `[ErrorDescription <String>]`: Error description
        - `[InstanceDisplayName <String>]`: Name of setting instance that is being reported.
        - `[Setting <String>]`: The setting that is being reported
        - `[SettingName <String>]`: Localized/user friendly setting name that is being reported
        - `[Sources <IMicrosoftGraphSettingSource[]>]`: Contributing policies
          - `[DisplayName <String>]`: Not yet documented
          - `[Id <String>]`: Not yet documented
        - `[State <String>]`: complianceStatus
        - `[UserEmail <String>]`: UserEmail
        - `[UserId <String>]`: UserId
        - `[UserName <String>]`: UserName
        - `[UserPrincipalName <String>]`: UserPrincipalName.
      - `[State <String>]`: complianceStatus
      - `[Version <Int32?>]`: The version of the policy
    - `[DeviceConfigurationStates <IMicrosoftGraphDeviceConfigurationState1[]>]`: Device configuration states for this device.
      - `[Id <String>]`: Read-only.
      - `[DisplayName <String>]`: The name of the policy for this policyBase
      - `[PlatformType <String>]`: 
      - `[SettingCount <Int32?>]`: Count of how many setting a policy holds
      - `[SettingStates <IMicrosoftGraphDeviceConfigurationSettingState[]>]`: 
        - `[CurrentValue <String>]`: Current value of setting on device
        - `[ErrorCode <Int64?>]`: Error code for the setting
        - `[ErrorDescription <String>]`: Error description
        - `[InstanceDisplayName <String>]`: Name of setting instance that is being reported.
        - `[Setting <String>]`: The setting that is being reported
        - `[SettingName <String>]`: Localized/user friendly setting name that is being reported
        - `[Sources <IMicrosoftGraphSettingSource[]>]`: Contributing policies
        - `[State <String>]`: complianceStatus
        - `[UserEmail <String>]`: UserEmail
        - `[UserId <String>]`: UserId
        - `[UserName <String>]`: UserName
        - `[UserPrincipalName <String>]`: UserPrincipalName.
      - `[State <String>]`: complianceStatus
      - `[Version <Int32?>]`: The version of the policy
    - `[DeviceEnrollmentType <String>]`: 
    - `[DeviceHealthAttestationState <IMicrosoftGraphDeviceHealthAttestationState>]`: deviceHealthAttestationState
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[AttestationIdentityKey <String>]`: TWhen an Attestation Identity Key (AIK) is present on a device, it indicates that the device has an endorsement key (EK) certificate.
      - `[BitLockerStatus <String>]`: On or Off of BitLocker Drive Encryption
      - `[BootAppSecurityVersion <String>]`: The security version number of the Boot Application
      - `[BootDebugging <String>]`: When bootDebugging is enabled, the device is used in development and testing
      - `[BootManagerSecurityVersion <String>]`: The security version number of the Boot Application
      - `[BootManagerVersion <String>]`: The version of the Boot Manager
      - `[BootRevisionListInfo <String>]`: The Boot Revision List that was loaded during initial boot on the attested device
      - `[CodeIntegrity <String>]`: When code integrity is enabled, code execution is restricted to integrity verified code
      - `[CodeIntegrityCheckVersion <String>]`: The version of the Boot Manager
      - `[CodeIntegrityPolicy <String>]`: The Code Integrity policy that is controlling the security of the boot environment
      - `[ContentNamespaceUrl <String>]`: The DHA report version. (Namespace version)
      - `[ContentVersion <String>]`: The HealthAttestation state schema version
      - `[DataExcutionPolicy <String>]`: DEP Policy defines a set of hardware and software technologies that perform additional checks on memory
      - `[DeviceHealthAttestationStatus <String>]`: The DHA report version. (Namespace version)
      - `[EarlyLaunchAntiMalwareDriverProtection <String>]`: ELAM provides protection for the computers in your network when they start up
      - `[HealthAttestationSupportedStatus <String>]`: This attribute indicates if DHA is supported for the device
      - `[HealthStatusMismatchInfo <String>]`: This attribute appears if DHA-Service detects an integrity issue
      - `[IssuedDateTime <DateTime?>]`: The DateTime when device was evaluated or issued to MDM
      - `[LastUpdateDateTime <String>]`: The Timestamp of the last update.
      - `[OperatingSystemKernelDebugging <String>]`: When operatingSystemKernelDebugging is enabled, the device is used in development and testing
      - `[OperatingSystemRevListInfo <String>]`: The Operating System Revision List that was loaded during initial boot on the attested device
      - `[Pcr0 <String>]`: The measurement that is captured in PCR[0]
      - `[PcrHashAlgorithm <String>]`: Informational attribute that identifies the HASH algorithm that was used by TPM
      - `[ResetCount <Int64?>]`: The number of times a PC device has hibernated or resumed
      - `[RestartCount <Int64?>]`: The number of times a PC device has rebooted
      - `[SafeMode <String>]`: Safe mode is a troubleshooting option for Windows that starts your computer in a limited state
      - `[SecureBoot <String>]`: When Secure Boot is enabled, the core components must have the correct cryptographic signatures
      - `[SecureBootConfigurationPolicyFingerPrint <String>]`: Fingerprint of the Custom Secure Boot Configuration Policy
      - `[TestSigning <String>]`: When test signing is allowed, the device does not enforce signature validation during boot
      - `[TpmVersion <String>]`: The security version number of the Boot Application
      - `[VirtualSecureMode <String>]`: VSM is a container that protects high value assets from a compromised kernel
      - `[WindowsPe <String>]`: Operating system running with limited services that is used to prepare a computer for Windows
    - `[DeviceName <String>]`: Name of the device. This property is read-only.
    - `[DeviceRegistrationState <String>]`: deviceRegistrationState
    - `[EasActivated <Boolean?>]`: Whether the device is Exchange ActiveSync activated. This property is read-only.
    - `[EasActivationDateTime <DateTime?>]`: Exchange ActivationSync activation time of the device. This property is read-only.
    - `[EasDeviceId <String>]`: Exchange ActiveSync Id of the device. This property is read-only.
    - `[EmailAddress <String>]`: Email(s) for the user associated with the device. This property is read-only.
    - `[EnrolledDateTime <DateTime?>]`: Enrollment time of the device. This property is read-only.
    - `[ExchangeAccessState <String>]`: deviceManagementExchangeAccessState
    - `[ExchangeAccessStateReason <String>]`: deviceManagementExchangeAccessStateReason
    - `[ExchangeLastSuccessfulSyncDateTime <DateTime?>]`: Last time the device contacted Exchange. This property is read-only.
    - `[FreeStorageSpaceInBytes <Int64?>]`: Free Storage in Bytes. This property is read-only.
    - `[Imei <String>]`: IMEI. This property is read-only.
    - `[IsEncrypted <Boolean?>]`: Device encryption status. This property is read-only.
    - `[IsSupervised <Boolean?>]`: Device supervised status. This property is read-only.
    - `[JailBroken <String>]`: whether the device is jail broken or rooted. This property is read-only.
    - `[LastSyncDateTime <DateTime?>]`: The date and time that the device last completed a successful sync with Intune. This property is read-only.
    - `[ManagedDeviceName <String>]`: Automatically generated name to identify a device. Can be overwritten to a user friendly name.
    - `[ManagedDeviceOwnerType <String>]`: managedDeviceOwnerType
    - `[ManagementAgent <String>]`: 
    - `[Manufacturer <String>]`: Manufacturer of the device. This property is read-only.
    - `[Meid <String>]`: MEID. This property is read-only.
    - `[Model <String>]`: Model of the device. This property is read-only.
    - `[OSVersion <String>]`: Operating system version of the device. This property is read-only.
    - `[OperatingSystem <String>]`: Operating system of the device. Windows, iOS, etc. This property is read-only.
    - `[PartnerReportedThreatState <String>]`: managedDevicePartnerReportedHealthState
    - `[PhoneNumber <String>]`: Phone number of the device. This property is read-only.
    - `[RemoteAssistanceSessionErrorDetails <String>]`: An error string that identifies issues when creating Remote Assistance session objects. This property is read-only.
    - `[RemoteAssistanceSessionUrl <String>]`: Url that allows a Remote Assistance session to be established with the device. This property is read-only.
    - `[SerialNumber <String>]`: SerialNumber. This property is read-only.
    - `[SubscriberCarrier <String>]`: Subscriber Carrier. This property is read-only.
    - `[TotalStorageSpaceInBytes <Int64?>]`: Total Storage in Bytes. This property is read-only.
    - `[UserDisplayName <String>]`: User display name. This property is read-only.
    - `[UserId <String>]`: Unique Identifier for the user associated with the device. This property is read-only.
    - `[UserPrincipalName <String>]`: Device user principal name. This property is read-only.
    - `[WiFiMacAddress <String>]`: Wi-Fi MAC. This property is read-only.
  - `[SizeInByte <Int64?>]`: Discovered application size in bytes. Read-only
  - `[Version <String>]`: Version of the discovered application. Read-only

DEVICECATEGORIES <IMicrosoftGraphDeviceCategory2[]>: The list of device categories with the tenant.
  - `[Id <String>]`: Read-only.
  - `[Description <String>]`: Optional description for the device category.
  - `[DisplayName <String>]`: Display name for the device category.

DEVICECOMPLIANCEPOLICIES <IMicrosoftGraphDeviceCompliancePolicy1[]>: The device compliance policies.
  - `[Id <String>]`: Read-only.
  - `[Assignments <IMicrosoftGraphDeviceCompliancePolicyAssignment1[]>]`: The collection of assignments for this compliance policy.
    - `[Id <String>]`: Read-only.
    - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[CreatedDateTime <DateTime?>]`: DateTime the object was created.
  - `[Description <String>]`: Admin provided description of the Device Configuration.
  - `[DeviceSettingStateSummaries <IMicrosoftGraphSettingStateDeviceSummary[]>]`: Compliance Setting State Device Summary
    - `[Id <String>]`: Read-only.
    - `[CompliantDeviceCount <Int32?>]`: Device Compliant count for the setting
    - `[ConflictDeviceCount <Int32?>]`: Device conflict error count for the setting
    - `[ErrorDeviceCount <Int32?>]`: Device error count for the setting
    - `[InstancePath <String>]`: Name of the InstancePath for the setting
    - `[NonCompliantDeviceCount <Int32?>]`: Device NonCompliant count for the setting
    - `[NotApplicableDeviceCount <Int32?>]`: Device Not Applicable count for the setting
    - `[RemediatedDeviceCount <Int32?>]`: Device Compliant count for the setting
    - `[SettingName <String>]`: Name of the setting
    - `[UnknownDeviceCount <Int32?>]`: Device Unkown count for the setting
  - `[DeviceStatusOverview <IMicrosoftGraphDeviceComplianceDeviceOverview1>]`: deviceComplianceDeviceOverview
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[ConfigurationVersion <Int32?>]`: Version of the policy for that overview
    - `[ErrorCount <Int32?>]`: Number of error devices
    - `[FailedCount <Int32?>]`: Number of failed devices
    - `[LastUpdateDateTime <DateTime?>]`: Last update time
    - `[NotApplicableCount <Int32?>]`: Number of not applicable devices
    - `[PendingCount <Int32?>]`: Number of pending devices
    - `[SuccessCount <Int32?>]`: Number of succeeded devices
  - `[DeviceStatuses <IMicrosoftGraphDeviceComplianceDeviceStatus1[]>]`: List of DeviceComplianceDeviceStatus.
    - `[Id <String>]`: Read-only.
    - `[ComplianceGracePeriodExpirationDateTime <DateTime?>]`: The DateTime when device compliance grace period expires
    - `[DeviceDisplayName <String>]`: Device name of the DevicePolicyStatus.
    - `[DeviceModel <String>]`: The device model that is being reported
    - `[LastReportedDateTime <DateTime?>]`: Last modified date time of the policy report.
    - `[Status <String>]`: complianceStatus
    - `[UserName <String>]`: The User Name that is being reported
    - `[UserPrincipalName <String>]`: UserPrincipalName.
  - `[DisplayName <String>]`: Admin provided name of the device configuration.
  - `[LastModifiedDateTime <DateTime?>]`: DateTime the object was last modified.
  - `[ScheduledActionsForRule <IMicrosoftGraphDeviceComplianceScheduledActionForRule1[]>]`: The list of scheduled action for this rule
    - `[Id <String>]`: Read-only.
    - `[RuleName <String>]`: Name of the rule which this scheduled action applies to.
    - `[ScheduledActionConfigurations <IMicrosoftGraphDeviceComplianceActionItem1[]>]`: The list of scheduled action configurations for this compliance policy.
      - `[Id <String>]`: Read-only.
      - `[ActionType <String>]`: 
      - `[GracePeriodHours <Int32?>]`: Number of hours to wait till the action will be enforced. Valid values 0 to 8760
      - `[NotificationMessageCcList <String[]>]`: A list of group IDs to speicify who to CC this notification message to.
      - `[NotificationTemplateId <String>]`: What notification Message template to use
  - `[UserStatusOverview <IMicrosoftGraphDeviceComplianceUserOverview1>]`: deviceComplianceUserOverview
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[ConfigurationVersion <Int32?>]`: Version of the policy for that overview
    - `[ErrorCount <Int32?>]`: Number of error Users
    - `[FailedCount <Int32?>]`: Number of failed Users
    - `[LastUpdateDateTime <DateTime?>]`: Last update time
    - `[NotApplicableCount <Int32?>]`: Number of not applicable users
    - `[PendingCount <Int32?>]`: Number of pending Users
    - `[SuccessCount <Int32?>]`: Number of succeeded Users
  - `[UserStatuses <IMicrosoftGraphDeviceComplianceUserStatus[]>]`: List of DeviceComplianceUserStatus.
    - `[Id <String>]`: Read-only.
    - `[DevicesCount <Int32?>]`: Devices count for that user.
    - `[LastReportedDateTime <DateTime?>]`: Last modified date time of the policy report.
    - `[Status <String>]`: complianceStatus
    - `[UserDisplayName <String>]`: User name of the DevicePolicyStatus.
    - `[UserPrincipalName <String>]`: UserPrincipalName.
  - `[Version <Int32?>]`: Version of the device configuration.

DEVICECOMPLIANCEPOLICYDEVICESTATESUMMARY <IMicrosoftGraphDeviceCompliancePolicyDeviceStateSummary>: deviceCompliancePolicyDeviceStateSummary
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[CompliantDeviceCount <Int32?>]`: Number of compliant devices
  - `[ConfigManagerCount <Int32?>]`: Number of devices that have compliance managed by System Center Configuration Manager
  - `[ConflictDeviceCount <Int32?>]`: Number of conflict devices
  - `[ErrorDeviceCount <Int32?>]`: Number of error devices
  - `[InGracePeriodCount <Int32?>]`: Number of devices that are in grace period
  - `[NonCompliantDeviceCount <Int32?>]`: Number of NonCompliant devices
  - `[NotApplicableDeviceCount <Int32?>]`: Number of not applicable devices
  - `[RemediatedDeviceCount <Int32?>]`: Number of remediated devices
  - `[UnknownDeviceCount <Int32?>]`: Number of unknown devices

DEVICECOMPLIANCEPOLICYSETTINGSTATESUMMARIES <IMicrosoftGraphDeviceCompliancePolicySettingStateSummary1[]>: The summary states of compliance policy settings for this account.
  - `[Id <String>]`: Read-only.
  - `[CompliantDeviceCount <Int32?>]`: Number of compliant devices
  - `[ConflictDeviceCount <Int32?>]`: Number of conflict devices
  - `[DeviceComplianceSettingStates <IMicrosoftGraphDeviceComplianceSettingState1[]>]`: Not yet documented
    - `[Id <String>]`: Read-only.
    - `[ComplianceGracePeriodExpirationDateTime <DateTime?>]`: The DateTime when device compliance grace period expires
    - `[DeviceId <String>]`: The Device Id that is being reported
    - `[DeviceModel <String>]`: The device model that is being reported
    - `[DeviceName <String>]`: The Device Name that is being reported
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

DEVICECONFIGURATIONDEVICESTATESUMMARIES <IMicrosoftGraphDeviceConfigurationDeviceStateSummary>: deviceConfigurationDeviceStateSummary
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[CompliantDeviceCount <Int32?>]`: Number of compliant devices
  - `[ConflictDeviceCount <Int32?>]`: Number of conflict devices
  - `[ErrorDeviceCount <Int32?>]`: Number of error devices
  - `[NonCompliantDeviceCount <Int32?>]`: Number of NonCompliant devices
  - `[NotApplicableDeviceCount <Int32?>]`: Number of not applicable devices
  - `[RemediatedDeviceCount <Int32?>]`: Number of remediated devices
  - `[UnknownDeviceCount <Int32?>]`: Number of unknown devices

DEVICECONFIGURATIONS <IMicrosoftGraphDeviceConfiguration1[]>: The device configurations.
  - `[Id <String>]`: Read-only.
  - `[Assignments <IMicrosoftGraphDeviceConfigurationAssignment1[]>]`: The list of assignments for the device configuration profile.
    - `[Id <String>]`: Read-only.
    - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[CreatedDateTime <DateTime?>]`: DateTime the object was created.
  - `[Description <String>]`: Admin provided description of the Device Configuration.
  - `[DeviceSettingStateSummaries <IMicrosoftGraphSettingStateDeviceSummary[]>]`: Device Configuration Setting State Device Summary
    - `[Id <String>]`: Read-only.
    - `[CompliantDeviceCount <Int32?>]`: Device Compliant count for the setting
    - `[ConflictDeviceCount <Int32?>]`: Device conflict error count for the setting
    - `[ErrorDeviceCount <Int32?>]`: Device error count for the setting
    - `[InstancePath <String>]`: Name of the InstancePath for the setting
    - `[NonCompliantDeviceCount <Int32?>]`: Device NonCompliant count for the setting
    - `[NotApplicableDeviceCount <Int32?>]`: Device Not Applicable count for the setting
    - `[RemediatedDeviceCount <Int32?>]`: Device Compliant count for the setting
    - `[SettingName <String>]`: Name of the setting
    - `[UnknownDeviceCount <Int32?>]`: Device Unkown count for the setting
  - `[DeviceStatusOverview <IMicrosoftGraphDeviceConfigurationDeviceOverview1>]`: deviceConfigurationDeviceOverview
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[ConfigurationVersion <Int32?>]`: Version of the policy for that overview
    - `[ErrorCount <Int32?>]`: Number of error devices
    - `[FailedCount <Int32?>]`: Number of failed devices
    - `[LastUpdateDateTime <DateTime?>]`: Last update time
    - `[NotApplicableCount <Int32?>]`: Number of not applicable devices
    - `[PendingCount <Int32?>]`: Number of pending devices
    - `[SuccessCount <Int32?>]`: Number of succeeded devices
  - `[DeviceStatuses <IMicrosoftGraphDeviceConfigurationDeviceStatus1[]>]`: Device configuration installation status by device.
    - `[Id <String>]`: Read-only.
    - `[ComplianceGracePeriodExpirationDateTime <DateTime?>]`: The DateTime when device compliance grace period expires
    - `[DeviceDisplayName <String>]`: Device name of the DevicePolicyStatus.
    - `[DeviceModel <String>]`: The device model that is being reported
    - `[LastReportedDateTime <DateTime?>]`: Last modified date time of the policy report.
    - `[Status <String>]`: complianceStatus
    - `[UserName <String>]`: The User Name that is being reported
    - `[UserPrincipalName <String>]`: UserPrincipalName.
  - `[DisplayName <String>]`: Admin provided name of the device configuration.
  - `[LastModifiedDateTime <DateTime?>]`: DateTime the object was last modified.
  - `[UserStatusOverview <IMicrosoftGraphDeviceConfigurationUserOverview1>]`: deviceConfigurationUserOverview
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[ConfigurationVersion <Int32?>]`: Version of the policy for that overview
    - `[ErrorCount <Int32?>]`: Number of error Users
    - `[FailedCount <Int32?>]`: Number of failed Users
    - `[LastUpdateDateTime <DateTime?>]`: Last update time
    - `[NotApplicableCount <Int32?>]`: Number of not applicable users
    - `[PendingCount <Int32?>]`: Number of pending Users
    - `[SuccessCount <Int32?>]`: Number of succeeded Users
  - `[UserStatuses <IMicrosoftGraphDeviceConfigurationUserStatus[]>]`: Device configuration installation status by user.
    - `[Id <String>]`: Read-only.
    - `[DevicesCount <Int32?>]`: Devices count for that user.
    - `[LastReportedDateTime <DateTime?>]`: Last modified date time of the policy report.
    - `[Status <String>]`: complianceStatus
    - `[UserDisplayName <String>]`: User name of the DevicePolicyStatus.
    - `[UserPrincipalName <String>]`: UserPrincipalName.
  - `[Version <Int32?>]`: Version of the device configuration.

DEVICEENROLLMENTCONFIGURATIONS <IMicrosoftGraphDeviceEnrollmentConfiguration1[]>: The list of device enrollment configurations
  - `[Id <String>]`: Read-only.
  - `[Assignments <IMicrosoftGraphEnrollmentConfigurationAssignment[]>]`: The list of group assignments for the device configuration profile
    - `[Id <String>]`: Read-only.
    - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[CreatedDateTime <DateTime?>]`: Created date time in UTC of the device enrollment configuration
  - `[Description <String>]`: The description of the device enrollment configuration
  - `[DisplayName <String>]`: The display name of the device enrollment configuration
  - `[LastModifiedDateTime <DateTime?>]`: Last modified date time in UTC of the device enrollment configuration
  - `[Priority <Int32?>]`: Priority is used when a user exists in multiple groups that are assigned enrollment configuration. Users are subject only to the configuration with the lowest priority value.
  - `[Version <Int32?>]`: The version of the device enrollment configuration

DEVICEMANAGEMENTPARTNERS <IMicrosoftGraphDeviceManagementPartner1[]>: The list of Device Management Partners configured by the tenant.
  - `[Id <String>]`: Read-only.
  - `[DisplayName <String>]`: Partner display name
  - `[IsConfigured <Boolean?>]`: Whether device management partner is configured or not
  - `[LastHeartbeatDateTime <DateTime?>]`: Timestamp of last heartbeat after admin enabled option Connect to Device management Partner
  - `[PartnerAppType <String>]`: deviceManagementPartnerAppType
  - `[PartnerState <String>]`: deviceManagementPartnerTenantState
  - `[SingleTenantAppId <String>]`: Partner Single tenant App id
  - `[WhenPartnerDevicesWillBeMarkedAsNonCompliantDateTime <DateTime?>]`: DateTime in UTC when PartnerDevices will be marked as NonCompliant
  - `[WhenPartnerDevicesWillBeRemovedDateTime <DateTime?>]`: DateTime in UTC when PartnerDevices will be removed

EXCHANGECONNECTORS <IMicrosoftGraphDeviceManagementExchangeConnector[]>: The list of Exchange Connectors configured by the tenant.
  - `[Id <String>]`: Read-only.
  - `[ConnectorServerName <String>]`: The name of the server hosting the Exchange Connector.
  - `[ExchangeAlias <String>]`: An alias assigned to the Exchange server
  - `[ExchangeConnectorType <String>]`: deviceManagementExchangeConnectorType
  - `[ExchangeOrganization <String>]`: Exchange Organization to the Exchange server
  - `[LastSyncDateTime <DateTime?>]`: Last sync time for the Exchange Connector
  - `[PrimarySmtpAddress <String>]`: Email address used to configure the Service To Service Exchange Connector.
  - `[ServerName <String>]`: The name of the Exchange server.
  - `[Status <String>]`: deviceManagementExchangeConnectorStatus
  - `[Version <String>]`: The version of the ExchangeConnectorAgent

INTUNEBRAND <IMicrosoftGraphIntuneBrand1>: intuneBrand contains data which is used in customizing the appearance of the Company Portal applications as well as the end user web portal.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[ContactItEmailAddress <String>]`: Email address of the person/organization responsible for IT support.
  - `[ContactItName <String>]`: Name of the person/organization responsible for IT support.
  - `[ContactItNotes <String>]`: Text comments regarding the person/organization responsible for IT support.
  - `[ContactItPhoneNumber <String>]`: Phone number of the person/organization responsible for IT support.
  - `[DarkBackgroundLogo <IMicrosoftGraphMimeContent>]`: Contains properties for a generic mime content.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Type <String>]`: Indicates the content mime type.
    - `[Value <Byte[]>]`: The byte array that contains the actual content.
  - `[DisplayName <String>]`: Company/organization name that is displayed to end users.
  - `[LightBackgroundLogo <IMicrosoftGraphMimeContent>]`: Contains properties for a generic mime content.
  - `[OnlineSupportSiteName <String>]`: Display name of the company/organization's IT helpdesk site.
  - `[OnlineSupportSiteUrl <String>]`: URL to the company/organization's IT helpdesk site.
  - `[PrivacyUrl <String>]`: URL to the company/organization's privacy policy.
  - `[ShowDisplayNameNextToLogo <Boolean?>]`: Boolean that represents whether the administrator-supplied display name will be shown next to the logo image.
  - `[ShowLogo <Boolean?>]`: Boolean that represents whether the administrator-supplied logo images are shown or not shown.
  - `[ShowNameNextToLogo <Boolean?>]`: Boolean that represents whether the administrator-supplied display name will be shown next to the logo image.
  - `[ThemeColor <IMicrosoftGraphRgbColor>]`: Color in RGB.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[B <Int32?>]`: Blue value
    - `[G <Int32?>]`: Green value
    - `[R <Int32?>]`: Red value

IOSUPDATESTATUSES <IMicrosoftGraphIosUpdateDeviceStatus1[]>: The IOS software update installation statuses for this account.
  - `[Id <String>]`: Read-only.
  - `[ComplianceGracePeriodExpirationDateTime <DateTime?>]`: The DateTime when device compliance grace period expires
  - `[DeviceDisplayName <String>]`: Device name of the DevicePolicyStatus.
  - `[DeviceId <String>]`: The device id that is being reported.
  - `[DeviceModel <String>]`: The device model that is being reported
  - `[InstallStatus <String>]`: 
  - `[LastReportedDateTime <DateTime?>]`: Last modified date time of the policy report.
  - `[OSVersion <String>]`: The device version that is being reported.
  - `[Status <String>]`: complianceStatus
  - `[UserId <String>]`: The User id that is being reported.
  - `[UserName <String>]`: The User Name that is being reported
  - `[UserPrincipalName <String>]`: UserPrincipalName.

MANAGEDDEVICEOVERVIEW <IMicrosoftGraphManagedDeviceOverview1>: Summary data for managed devices
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[DeviceExchangeAccessStateSummary <IMicrosoftGraphDeviceExchangeAccessStateSummary>]`: Device Exchange Access State summary
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[AllowedDeviceCount <Int32?>]`: Total count of devices with Exchange Access State: Allowed.
    - `[BlockedDeviceCount <Int32?>]`: Total count of devices with Exchange Access State: Blocked.
    - `[QuarantinedDeviceCount <Int32?>]`: Total count of devices with Exchange Access State: Quarantined.
    - `[UnavailableDeviceCount <Int32?>]`: Total count of devices for which no Exchange Access State could be found.
    - `[UnknownDeviceCount <Int32?>]`: Total count of devices with Exchange Access State: Unknown.
  - `[DeviceOperatingSystemSummary <IMicrosoftGraphDeviceOperatingSystemSummary>]`: Device operating system summary.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[AndroidCount <Int32?>]`: Number of android device count.
    - `[IosCount <Int32?>]`: Number of iOS device count.
    - `[MacOSCount <Int32?>]`: Number of Mac OS X device count.
    - `[UnknownCount <Int32?>]`: Number of unknown device count.
    - `[WindowsCount <Int32?>]`: Number of Windows device count.
    - `[WindowsMobileCount <Int32?>]`: Number of Windows mobile device count.
  - `[DualEnrolledDeviceCount <Int32?>]`: The number of devices enrolled in both MDM and EAS
  - `[EnrolledDeviceCount <Int32?>]`: Total enrolled device count. Does not include PC devices managed via Intune PC Agent
  - `[MdmEnrolledCount <Int32?>]`: The number of devices enrolled in MDM

MANAGEDDEVICES <IMicrosoftGraphManagedDevice1[]>: The list of managed devices.
  - `[Id <String>]`: Read-only.
  - `[ActivationLockBypassCode <String>]`: Code that allows the Activation Lock on a device to be bypassed. This property is read-only.
  - `[AndroidSecurityPatchLevel <String>]`: Android security patch level. This property is read-only.
  - `[AzureAdDeviceId <String>]`: The unique identifier for the Azure Active Directory device. Read only. This property is read-only.
  - `[AzureAdRegistered <Boolean?>]`: Whether the device is Azure Active Directory registered. This property is read-only.
  - `[ComplianceGracePeriodExpirationDateTime <DateTime?>]`: The DateTime when device compliance grace period expires. This property is read-only.
  - `[ComplianceState <String>]`: complianceState
  - `[ConfigurationManagerClientEnabledFeatures <IMicrosoftGraphConfigurationManagerClientEnabledFeatures1>]`: configuration Manager client enabled features
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[CompliancePolicy <Boolean?>]`: Whether compliance policy is managed by Intune
    - `[DeviceConfiguration <Boolean?>]`: Whether device configuration is managed by Intune
    - `[Inventory <Boolean?>]`: Whether inventory is managed by Intune
    - `[ModernApps <Boolean?>]`: Whether modern application is managed by Intune
    - `[ResourceAccess <Boolean?>]`: Whether resource access is managed by Intune
    - `[WindowsUpdateForBusiness <Boolean?>]`: Whether Windows Update for Business is managed by Intune
  - `[DeviceActionResults <IMicrosoftGraphDeviceActionResult[]>]`: List of ComplexType deviceActionResult objects. This property is read-only.
    - `[ActionName <String>]`: Action name
    - `[ActionState <String>]`: actionState
    - `[LastUpdatedDateTime <DateTime?>]`: Time the action state was last updated
    - `[StartDateTime <DateTime?>]`: Time the action was initiated
  - `[DeviceCategory <IMicrosoftGraphDeviceCategory2>]`: Device categories provides a way to organize your devices. Using device categories, company administrators can define their own categories that make sense to their company. These categories can then be applied to a device in the Intune Azure console or selected by a user during device enrollment. You can filter reports and create dynamic Azure Active Directory device groups based on device categories.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[Description <String>]`: Optional description for the device category.
    - `[DisplayName <String>]`: Display name for the device category.
  - `[DeviceCategoryDisplayName <String>]`: Device category display name. This property is read-only.
  - `[DeviceCompliancePolicyStates <IMicrosoftGraphDeviceCompliancePolicyState1[]>]`: Device compliance policy states for this device.
    - `[Id <String>]`: Read-only.
    - `[DisplayName <String>]`: The name of the policy for this policyBase
    - `[PlatformType <String>]`: 
    - `[SettingCount <Int32?>]`: Count of how many setting a policy holds
    - `[SettingStates <IMicrosoftGraphDeviceCompliancePolicySettingState[]>]`: 
      - `[CurrentValue <String>]`: Current value of setting on device
      - `[ErrorCode <Int64?>]`: Error code for the setting
      - `[ErrorDescription <String>]`: Error description
      - `[InstanceDisplayName <String>]`: Name of setting instance that is being reported.
      - `[Setting <String>]`: The setting that is being reported
      - `[SettingName <String>]`: Localized/user friendly setting name that is being reported
      - `[Sources <IMicrosoftGraphSettingSource[]>]`: Contributing policies
        - `[DisplayName <String>]`: Not yet documented
        - `[Id <String>]`: Not yet documented
      - `[State <String>]`: complianceStatus
      - `[UserEmail <String>]`: UserEmail
      - `[UserId <String>]`: UserId
      - `[UserName <String>]`: UserName
      - `[UserPrincipalName <String>]`: UserPrincipalName.
    - `[State <String>]`: complianceStatus
    - `[Version <Int32?>]`: The version of the policy
  - `[DeviceConfigurationStates <IMicrosoftGraphDeviceConfigurationState1[]>]`: Device configuration states for this device.
    - `[Id <String>]`: Read-only.
    - `[DisplayName <String>]`: The name of the policy for this policyBase
    - `[PlatformType <String>]`: 
    - `[SettingCount <Int32?>]`: Count of how many setting a policy holds
    - `[SettingStates <IMicrosoftGraphDeviceConfigurationSettingState[]>]`: 
      - `[CurrentValue <String>]`: Current value of setting on device
      - `[ErrorCode <Int64?>]`: Error code for the setting
      - `[ErrorDescription <String>]`: Error description
      - `[InstanceDisplayName <String>]`: Name of setting instance that is being reported.
      - `[Setting <String>]`: The setting that is being reported
      - `[SettingName <String>]`: Localized/user friendly setting name that is being reported
      - `[Sources <IMicrosoftGraphSettingSource[]>]`: Contributing policies
      - `[State <String>]`: complianceStatus
      - `[UserEmail <String>]`: UserEmail
      - `[UserId <String>]`: UserId
      - `[UserName <String>]`: UserName
      - `[UserPrincipalName <String>]`: UserPrincipalName.
    - `[State <String>]`: complianceStatus
    - `[Version <Int32?>]`: The version of the policy
  - `[DeviceEnrollmentType <String>]`: 
  - `[DeviceHealthAttestationState <IMicrosoftGraphDeviceHealthAttestationState>]`: deviceHealthAttestationState
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[AttestationIdentityKey <String>]`: TWhen an Attestation Identity Key (AIK) is present on a device, it indicates that the device has an endorsement key (EK) certificate.
    - `[BitLockerStatus <String>]`: On or Off of BitLocker Drive Encryption
    - `[BootAppSecurityVersion <String>]`: The security version number of the Boot Application
    - `[BootDebugging <String>]`: When bootDebugging is enabled, the device is used in development and testing
    - `[BootManagerSecurityVersion <String>]`: The security version number of the Boot Application
    - `[BootManagerVersion <String>]`: The version of the Boot Manager
    - `[BootRevisionListInfo <String>]`: The Boot Revision List that was loaded during initial boot on the attested device
    - `[CodeIntegrity <String>]`: When code integrity is enabled, code execution is restricted to integrity verified code
    - `[CodeIntegrityCheckVersion <String>]`: The version of the Boot Manager
    - `[CodeIntegrityPolicy <String>]`: The Code Integrity policy that is controlling the security of the boot environment
    - `[ContentNamespaceUrl <String>]`: The DHA report version. (Namespace version)
    - `[ContentVersion <String>]`: The HealthAttestation state schema version
    - `[DataExcutionPolicy <String>]`: DEP Policy defines a set of hardware and software technologies that perform additional checks on memory
    - `[DeviceHealthAttestationStatus <String>]`: The DHA report version. (Namespace version)
    - `[EarlyLaunchAntiMalwareDriverProtection <String>]`: ELAM provides protection for the computers in your network when they start up
    - `[HealthAttestationSupportedStatus <String>]`: This attribute indicates if DHA is supported for the device
    - `[HealthStatusMismatchInfo <String>]`: This attribute appears if DHA-Service detects an integrity issue
    - `[IssuedDateTime <DateTime?>]`: The DateTime when device was evaluated or issued to MDM
    - `[LastUpdateDateTime <String>]`: The Timestamp of the last update.
    - `[OperatingSystemKernelDebugging <String>]`: When operatingSystemKernelDebugging is enabled, the device is used in development and testing
    - `[OperatingSystemRevListInfo <String>]`: The Operating System Revision List that was loaded during initial boot on the attested device
    - `[Pcr0 <String>]`: The measurement that is captured in PCR[0]
    - `[PcrHashAlgorithm <String>]`: Informational attribute that identifies the HASH algorithm that was used by TPM
    - `[ResetCount <Int64?>]`: The number of times a PC device has hibernated or resumed
    - `[RestartCount <Int64?>]`: The number of times a PC device has rebooted
    - `[SafeMode <String>]`: Safe mode is a troubleshooting option for Windows that starts your computer in a limited state
    - `[SecureBoot <String>]`: When Secure Boot is enabled, the core components must have the correct cryptographic signatures
    - `[SecureBootConfigurationPolicyFingerPrint <String>]`: Fingerprint of the Custom Secure Boot Configuration Policy
    - `[TestSigning <String>]`: When test signing is allowed, the device does not enforce signature validation during boot
    - `[TpmVersion <String>]`: The security version number of the Boot Application
    - `[VirtualSecureMode <String>]`: VSM is a container that protects high value assets from a compromised kernel
    - `[WindowsPe <String>]`: Operating system running with limited services that is used to prepare a computer for Windows
  - `[DeviceName <String>]`: Name of the device. This property is read-only.
  - `[DeviceRegistrationState <String>]`: deviceRegistrationState
  - `[EasActivated <Boolean?>]`: Whether the device is Exchange ActiveSync activated. This property is read-only.
  - `[EasActivationDateTime <DateTime?>]`: Exchange ActivationSync activation time of the device. This property is read-only.
  - `[EasDeviceId <String>]`: Exchange ActiveSync Id of the device. This property is read-only.
  - `[EmailAddress <String>]`: Email(s) for the user associated with the device. This property is read-only.
  - `[EnrolledDateTime <DateTime?>]`: Enrollment time of the device. This property is read-only.
  - `[ExchangeAccessState <String>]`: deviceManagementExchangeAccessState
  - `[ExchangeAccessStateReason <String>]`: deviceManagementExchangeAccessStateReason
  - `[ExchangeLastSuccessfulSyncDateTime <DateTime?>]`: Last time the device contacted Exchange. This property is read-only.
  - `[FreeStorageSpaceInBytes <Int64?>]`: Free Storage in Bytes. This property is read-only.
  - `[Imei <String>]`: IMEI. This property is read-only.
  - `[IsEncrypted <Boolean?>]`: Device encryption status. This property is read-only.
  - `[IsSupervised <Boolean?>]`: Device supervised status. This property is read-only.
  - `[JailBroken <String>]`: whether the device is jail broken or rooted. This property is read-only.
  - `[LastSyncDateTime <DateTime?>]`: The date and time that the device last completed a successful sync with Intune. This property is read-only.
  - `[ManagedDeviceName <String>]`: Automatically generated name to identify a device. Can be overwritten to a user friendly name.
  - `[ManagedDeviceOwnerType <String>]`: managedDeviceOwnerType
  - `[ManagementAgent <String>]`: 
  - `[Manufacturer <String>]`: Manufacturer of the device. This property is read-only.
  - `[Meid <String>]`: MEID. This property is read-only.
  - `[Model <String>]`: Model of the device. This property is read-only.
  - `[OSVersion <String>]`: Operating system version of the device. This property is read-only.
  - `[OperatingSystem <String>]`: Operating system of the device. Windows, iOS, etc. This property is read-only.
  - `[PartnerReportedThreatState <String>]`: managedDevicePartnerReportedHealthState
  - `[PhoneNumber <String>]`: Phone number of the device. This property is read-only.
  - `[RemoteAssistanceSessionErrorDetails <String>]`: An error string that identifies issues when creating Remote Assistance session objects. This property is read-only.
  - `[RemoteAssistanceSessionUrl <String>]`: Url that allows a Remote Assistance session to be established with the device. This property is read-only.
  - `[SerialNumber <String>]`: SerialNumber. This property is read-only.
  - `[SubscriberCarrier <String>]`: Subscriber Carrier. This property is read-only.
  - `[TotalStorageSpaceInBytes <Int64?>]`: Total Storage in Bytes. This property is read-only.
  - `[UserDisplayName <String>]`: User display name. This property is read-only.
  - `[UserId <String>]`: Unique Identifier for the user associated with the device. This property is read-only.
  - `[UserPrincipalName <String>]`: Device user principal name. This property is read-only.
  - `[WiFiMacAddress <String>]`: Wi-Fi MAC. This property is read-only.

MOBILETHREATDEFENSECONNECTORS <IMicrosoftGraphMobileThreatDefenseConnector1[]>: The list of Mobile threat Defense connectors configured by the tenant.
  - `[Id <String>]`: Read-only.
  - `[AndroidDeviceBlockedOnMissingPartnerData <Boolean?>]`: For Android, set whether Intune must receive data from the data sync partner prior to marking a device compliant
  - `[AndroidEnabled <Boolean?>]`: For Android, set whether data from the data sync partner should be used during compliance evaluations
  - `[IosDeviceBlockedOnMissingPartnerData <Boolean?>]`: For IOS, set whether Intune must receive data from the data sync partner prior to marking a device compliant
  - `[IosEnabled <Boolean?>]`: For IOS, get or set whether data from the data sync partner should be used during compliance evaluations
  - `[LastHeartbeatDateTime <DateTime?>]`: DateTime of last Heartbeat recieved from the Data Sync Partner
  - `[PartnerState <String>]`: mobileThreatPartnerTenantState
  - `[PartnerUnresponsivenessThresholdInDays <Int32?>]`: Get or Set days the per tenant tolerance to unresponsiveness for this partner integration
  - `[PartnerUnsupportedOSVersionBlocked <Boolean?>]`: Get or set whether to block devices on the enabled platforms that do not meet the minimum version requirements of the Data Sync Partner

NOTIFICATIONMESSAGETEMPLATES <IMicrosoftGraphNotificationMessageTemplate1[]>: The Notification Message Templates.
  - `[Id <String>]`: Read-only.
  - `[BrandingOptions <String>]`: 
  - `[DefaultLocale <String>]`: The default locale to fallback onto when the requested locale is not available.
  - `[DisplayName <String>]`: Display name for the Notification Message Template.
  - `[LastModifiedDateTime <DateTime?>]`: DateTime the object was last modified.
  - `[LocalizedNotificationMessages <IMicrosoftGraphLocalizedNotificationMessage[]>]`: The list of localized messages for this Notification Message Template.
    - `[Id <String>]`: Read-only.
    - `[IsDefault <Boolean?>]`: Flag to indicate whether or not this is the default locale for language fallback. This flag can only be set. To unset, set this property to true on another Localized Notification Message.
    - `[LastModifiedDateTime <DateTime?>]`: DateTime the object was last modified.
    - `[Locale <String>]`: The Locale for which this message is destined.
    - `[MessageTemplate <String>]`: The Message Template content.
    - `[Subject <String>]`: The Message Template Subject.

REMOTEASSISTANCEPARTNERS <IMicrosoftGraphRemoteAssistancePartner1[]>: The remote assist partners.
  - `[Id <String>]`: Read-only.
  - `[DisplayName <String>]`: Display name of the partner.
  - `[LastConnectionDateTime <DateTime?>]`: Timestamp of the last request sent to Intune by the TEM partner.
  - `[OnboardingStatus <String>]`: remoteAssistanceOnboardingStatus
  - `[OnboardingUrl <String>]`: URL of the partner's onboarding portal, where an administrator can configure their Remote Assistance service.

RESOURCEOPERATIONS <IMicrosoftGraphResourceOperation1[]>: The Resource Operations.
  - `[Id <String>]`: Read-only.
  - `[ActionName <String>]`: Type of action this operation is going to perform. The actionName should be concise and limited to as few words as possible.
  - `[Description <String>]`: Description of the resource operation. The description is used in mouse-over text for the operation when shown in the Azure Portal.
  - `[ResourceName <String>]`: Name of the Resource this operation is performed on.

ROLEASSIGNMENTS <IMicrosoftGraphDeviceAndAppManagementRoleAssignment1[]>: The Role Assignments.
  - `[Description <String>]`: Description of the Role Assignment.
  - `[DisplayName <String>]`: The display or friendly name of the role Assignment.
  - `[ResourceScopes <String[]>]`: List of ids of role scope member security groups.  These are IDs from Azure Active Directory.
  - `[RoleDefinition <IMicrosoftGraphRoleDefinition1>]`: The Role Definition resource. The role definition is the foundation of role based access in Intune. The role combines an Intune resource such as a Mobile App and associated role permissions such as Create or Read for the resource. There are two types of roles, built-in and custom. Built-in roles cannot be modified. Both built-in roles and custom roles must have assignments to be enforced. Create custom roles if you want to define a role that allows any of the available resources and role permissions to be combined into a single role.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[Description <String>]`: Description of the Role definition.
    - `[DisplayName <String>]`: Display Name of the Role definition.
    - `[IsBuiltIn <Boolean?>]`: Type of Role. Set to True if it is built-in, or set to False if it is a custom role definition.
    - `[RoleAssignments <IMicrosoftGraphRoleAssignment[]>]`: List of Role assignments for this role definition.
      - `[Id <String>]`: Read-only.
      - `[Description <String>]`: Description of the Role Assignment.
      - `[DisplayName <String>]`: The display or friendly name of the role Assignment.
      - `[ResourceScopes <String[]>]`: List of ids of role scope member security groups.  These are IDs from Azure Active Directory.
      - `[RoleDefinition <IMicrosoftGraphRoleDefinition1>]`: The Role Definition resource. The role definition is the foundation of role based access in Intune. The role combines an Intune resource such as a Mobile App and associated role permissions such as Create or Read for the resource. There are two types of roles, built-in and custom. Built-in roles cannot be modified. Both built-in roles and custom roles must have assignments to be enforced. Create custom roles if you want to define a role that allows any of the available resources and role permissions to be combined into a single role.
    - `[RolePermissions <IMicrosoftGraphRolePermission[]>]`: List of Role Permissions this role is allowed to perform. These must match the actionName that is defined as part of the rolePermission.
      - `[ResourceActions <IMicrosoftGraphResourceAction[]>]`: Resource Actions each containing a set of allowed and not allowed permissions.
        - `[AllowedResourceActions <String[]>]`: Allowed Actions
        - `[NotAllowedResourceActions <String[]>]`: Not Allowed Actions.
  - `[Id <String>]`: Read-only.
  - `[Members <String[]>]`: The list of ids of role member security groups. These are IDs from Azure Active Directory.

ROLEDEFINITIONS <IMicrosoftGraphRoleDefinition1[]>: The Role Definitions.
  - `[Id <String>]`: Read-only.
  - `[Description <String>]`: Description of the Role definition.
  - `[DisplayName <String>]`: Display Name of the Role definition.
  - `[IsBuiltIn <Boolean?>]`: Type of Role. Set to True if it is built-in, or set to False if it is a custom role definition.
  - `[RoleAssignments <IMicrosoftGraphRoleAssignment[]>]`: List of Role assignments for this role definition.
    - `[Id <String>]`: Read-only.
    - `[Description <String>]`: Description of the Role Assignment.
    - `[DisplayName <String>]`: The display or friendly name of the role Assignment.
    - `[ResourceScopes <String[]>]`: List of ids of role scope member security groups.  These are IDs from Azure Active Directory.
    - `[RoleDefinition <IMicrosoftGraphRoleDefinition1>]`: The Role Definition resource. The role definition is the foundation of role based access in Intune. The role combines an Intune resource such as a Mobile App and associated role permissions such as Create or Read for the resource. There are two types of roles, built-in and custom. Built-in roles cannot be modified. Both built-in roles and custom roles must have assignments to be enforced. Create custom roles if you want to define a role that allows any of the available resources and role permissions to be combined into a single role.
  - `[RolePermissions <IMicrosoftGraphRolePermission[]>]`: List of Role Permissions this role is allowed to perform. These must match the actionName that is defined as part of the rolePermission.
    - `[ResourceActions <IMicrosoftGraphResourceAction[]>]`: Resource Actions each containing a set of allowed and not allowed permissions.
      - `[AllowedResourceActions <String[]>]`: Allowed Actions
      - `[NotAllowedResourceActions <String[]>]`: Not Allowed Actions.

SETTINGS <IMicrosoftGraphDeviceManagementSettings1>: deviceManagementSettings
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[DeviceComplianceCheckinThresholdDays <Int32?>]`: The number of days a device is allowed to go without checking in to remain compliant.
  - `[IsScheduledActionEnabled <Boolean?>]`: Is feature enabled or not for scheduled action for rule.
  - `[SecureByDefault <Boolean?>]`: Device should be noncompliant when there is no compliance policy targeted when this is true

SOFTWAREUPDATESTATUSSUMMARY <IMicrosoftGraphSoftwareUpdateStatusSummary>: softwareUpdateStatusSummary
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[CompliantDeviceCount <Int32?>]`: Number of compliant devices.
  - `[CompliantUserCount <Int32?>]`: Number of compliant users.
  - `[ConflictDeviceCount <Int32?>]`: Number of conflict devices.
  - `[ConflictUserCount <Int32?>]`: Number of conflict users.
  - `[DisplayName <String>]`: The name of the policy.
  - `[ErrorDeviceCount <Int32?>]`: Number of devices had error.
  - `[ErrorUserCount <Int32?>]`: Number of users had error.
  - `[NonCompliantDeviceCount <Int32?>]`: Number of non compliant devices.
  - `[NonCompliantUserCount <Int32?>]`: Number of non compliant users.
  - `[NotApplicableDeviceCount <Int32?>]`: Number of not applicable devices.
  - `[NotApplicableUserCount <Int32?>]`: Number of not applicable users.
  - `[RemediatedDeviceCount <Int32?>]`: Number of remediated devices.
  - `[RemediatedUserCount <Int32?>]`: Number of remediated users.
  - `[UnknownDeviceCount <Int32?>]`: Number of unknown devices.
  - `[UnknownUserCount <Int32?>]`: Number of unknown users.

TELECOMEXPENSEMANAGEMENTPARTNERS <IMicrosoftGraphTelecomExpenseManagementPartner[]>: The telecom expense management partners.
  - `[Id <String>]`: Read-only.
  - `[AppAuthorized <Boolean?>]`: Whether the partner's AAD app has been authorized to access Intune.
  - `[DisplayName <String>]`: Display name of the TEM partner.
  - `[Enabled <Boolean?>]`: Whether Intune's connection to the TEM service is currently enabled or disabled.
  - `[LastConnectionDateTime <DateTime?>]`: Timestamp of the last request sent to Intune by the TEM partner.
  - `[Url <String>]`: URL of the TEM partner's administrative control panel, where an administrator can configure their TEM service.

TERMSANDCONDITIONS <IMicrosoftGraphTermsAndConditions1[]>: The terms and conditions associated with device management of the company.
  - `[Id <String>]`: Read-only.
  - `[AcceptanceStatement <String>]`: Administrator-supplied explanation of the terms and conditions, typically describing what it means to accept the terms and conditions set out in the T&C policy. This is shown to the user on prompts to accept the T&C policy.
  - `[AcceptanceStatuses <IMicrosoftGraphTermsAndConditionsAcceptanceStatus[]>]`: The list of acceptance statuses for this T&C policy.
    - `[Id <String>]`: Read-only.
    - `[AcceptedDateTime <DateTime?>]`: DateTime when the terms were last accepted by the user.
    - `[AcceptedVersion <Int32?>]`: Most recent version number of the T&C accepted by the user.
    - `[TermsAndConditions <IMicrosoftGraphTermsAndConditions1>]`: A termsAndConditions entity represents the metadata and contents of a given Terms and Conditions (T&C) policy. T&C policies' contents are presented to users upon their first attempt to enroll into Intune and subsequently upon edits where an administrator has required re-acceptance. They enable administrators to communicate the provisions to which a user must agree in order to have devices enrolled into Intune.
    - `[UserDisplayName <String>]`: Display name of the user whose acceptance the entity represents.
    - `[UserPrincipalName <String>]`: The userPrincipalName of the User that accepted the term.
  - `[Assignments <IMicrosoftGraphTermsAndConditionsAssignment[]>]`: The list of assignments for this T&C policy.
    - `[Id <String>]`: Read-only.
    - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[BodyText <String>]`: Administrator-supplied body text of the terms and conditions, typically the terms themselves. This is shown to the user on prompts to accept the T&C policy.
  - `[CreatedDateTime <DateTime?>]`: DateTime the object was created.
  - `[Description <String>]`: Administrator-supplied description of the T&C policy.
  - `[DisplayName <String>]`: Administrator-supplied name for the T&C policy.
  - `[LastModifiedDateTime <DateTime?>]`: DateTime the object was last modified.
  - `[Title <String>]`: Administrator-supplied title of the terms and conditions. This is shown to the user on prompts to accept the T&C policy.
  - `[Version <Int32?>]`: Integer indicating the current version of the terms. Incremented when an administrator makes a change to the terms and wishes to require users to re-accept the modified T&C policy.

TROUBLESHOOTINGEVENTS <IMicrosoftGraphDeviceManagementTroubleshootingEvent1[]>: The list of troubleshooting events for the tenant.
  - `[Id <String>]`: Read-only.
  - `[CorrelationId <String>]`: Id used for tracing the failure in the service.
  - `[EventDateTime <DateTime?>]`: Time when the event occurred .

WINDOWSINFORMATIONPROTECTIONAPPLEARNINGSUMMARIES <IMicrosoftGraphWindowsInformationProtectionAppLearningSummary[]>: The windows information protection app learning summaries.
  - `[Id <String>]`: Read-only.
  - `[ApplicationName <String>]`: Application Name
  - `[ApplicationType <String>]`: applicationType
  - `[DeviceCount <Int32?>]`: Device Count

WINDOWSINFORMATIONPROTECTIONNETWORKLEARNINGSUMMARIES <IMicrosoftGraphWindowsInformationProtectionNetworkLearningSummary[]>: The windows information protection network learning summaries.
  - `[Id <String>]`: Read-only.
  - `[DeviceCount <Int32?>]`: Device Count
  - `[Url <String>]`: Website url

## RELATED LINKS

## RELATED LINKS