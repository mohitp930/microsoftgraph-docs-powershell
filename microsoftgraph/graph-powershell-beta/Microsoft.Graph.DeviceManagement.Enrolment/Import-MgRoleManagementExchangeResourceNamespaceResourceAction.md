---
external help file: Microsoft.Graph.DeviceManagement.Enrolment-help.xml
Module Name: Microsoft.Graph.DeviceManagement.Enrolment
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/import-mgrolemanagementexchangeresourcenamespaceresourceaction
schema: 2.0.0
---

# Import-MgRoleManagementExchangeResourceNamespaceResourceAction

## SYNOPSIS
Invoke action importResourceActions

## SYNTAX

### ImportExpanded (Default)
```
Import-MgRoleManagementExchangeResourceNamespaceResourceAction -UnifiedRbacResourceNamespaceId <String>
 [-AdditionalProperties <Hashtable>] [-Format <String>] [-OverwriteResourceNamespace] [-Value <String>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Import
```
Import-MgRoleManagementExchangeResourceNamespaceResourceAction -UnifiedRbacResourceNamespaceId <String>
 -BodyParameter <IPaths15BodmaRolemanagementExchangeResourcenamespacesUnifiedrbacresourcenamespaceIdMicrosoftGraphImportresourceactionsPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ImportViaIdentityExpanded
```
Import-MgRoleManagementExchangeResourceNamespaceResourceAction
 -InputObject <IDeviceManagementEnrolmentIdentity> [-AdditionalProperties <Hashtable>] [-Format <String>]
 [-OverwriteResourceNamespace] [-Value <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ImportViaIdentity
```
Import-MgRoleManagementExchangeResourceNamespaceResourceAction
 -InputObject <IDeviceManagementEnrolmentIdentity>
 -BodyParameter <IPaths15BodmaRolemanagementExchangeResourcenamespacesUnifiedrbacresourcenamespaceIdMicrosoftGraphImportresourceactionsPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action importResourceActions

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: ImportExpanded, ImportViaIdentityExpanded
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
Type: IPaths15BodmaRolemanagementExchangeResourcenamespacesUnifiedrbacresourcenamespaceIdMicrosoftGraphImportresourceactionsPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Import, ImportViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Format
.

```yaml
Type: String
Parameter Sets: ImportExpanded, ImportViaIdentityExpanded
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
Type: IDeviceManagementEnrolmentIdentity
Parameter Sets: ImportViaIdentityExpanded, ImportViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -OverwriteResourceNamespace
.

```yaml
Type: SwitchParameter
Parameter Sets: ImportExpanded, ImportViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UnifiedRbacResourceNamespaceId
The unique identifier of unifiedRbacResourceNamespace

```yaml
Type: String
Parameter Sets: ImportExpanded, Import
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Value
.

```yaml
Type: String
Parameter Sets: ImportExpanded, ImportViaIdentityExpanded
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

### Microsoft.Graph.PowerShell.Models.IDeviceManagementEnrolmentIdentity
### Microsoft.Graph.PowerShell.Models.IPaths15BodmaRolemanagementExchangeResourcenamespacesUnifiedrbacresourcenamespaceIdMicrosoftGraphImportresourceactionsPostRequestbodyContentApplicationJsonSchema
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUnifiedRbacResourceNamespace1
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER `<IPaths15BodmaRolemanagementExchangeResourcenamespacesUnifiedrbacresourcenamespaceIdMicrosoftGraphImportresourceactionsPostRequestbodyContentApplicationJsonSchema>`: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Format <String>]`: 
  - `[OverwriteResourceNamespace <Boolean?>]`: 
  - `[Value <String>]`: 

INPUTOBJECT `<IDeviceManagementEnrolmentIdentity>`: Identity Parameter
  - `[AndroidDeviceOwnerEnrollmentProfileId <String>]`: The unique identifier of androidDeviceOwnerEnrollmentProfile
  - `[AndroidForWorkEnrollmentProfileId <String>]`: The unique identifier of androidForWorkEnrollmentProfile
  - `[AppScopeId <String>]`: The unique identifier of appScope
  - `[AppleEnrollmentProfileAssignmentId <String>]`: The unique identifier of appleEnrollmentProfileAssignment
  - `[AppleUserInitiatedEnrollmentProfileId <String>]`: The unique identifier of appleUserInitiatedEnrollmentProfile
  - `[ApprovalId <String>]`: The unique identifier of approval
  - `[ApprovalStepId <String>]`: The unique identifier of approvalStep
  - `[DepOnboardingSettingId <String>]`: The unique identifier of depOnboardingSetting
  - `[DeviceEnrollmentConfigurationId <String>]`: The unique identifier of deviceEnrollmentConfiguration
  - `[DeviceManagementAutopilotEventId <String>]`: The unique identifier of deviceManagementAutopilotEvent
  - `[DeviceManagementAutopilotPolicyStatusDetailId <String>]`: The unique identifier of deviceManagementAutopilotPolicyStatusDetail
  - `[DirectoryObjectId <String>]`: The unique identifier of directoryObject
  - `[EnrollmentConfigurationAssignmentId <String>]`: The unique identifier of enrollmentConfigurationAssignment
  - `[EnrollmentProfileId <String>]`: The unique identifier of enrollmentProfile
  - `[ImportedAppleDeviceIdentityId <String>]`: The unique identifier of importedAppleDeviceIdentity
  - `[ImportedDeviceIdentityId <String>]`: The unique identifier of importedDeviceIdentity
  - `[ImportedWindowsAutopilotDeviceIdentityId <String>]`: The unique identifier of importedWindowsAutopilotDeviceIdentity
  - `[On <String>]`: Usage: on='{on}'
  - `[UnifiedRbacResourceActionId <String>]`: The unique identifier of unifiedRbacResourceAction
  - `[UnifiedRbacResourceNamespaceId <String>]`: The unique identifier of unifiedRbacResourceNamespace
  - `[UnifiedRoleAssignmentId <String>]`: The unique identifier of unifiedRoleAssignment
  - `[UnifiedRoleAssignmentMultipleId <String>]`: The unique identifier of unifiedRoleAssignmentMultiple
  - `[UnifiedRoleAssignmentScheduleId <String>]`: The unique identifier of unifiedRoleAssignmentSchedule
  - `[UnifiedRoleAssignmentScheduleInstanceId <String>]`: The unique identifier of unifiedRoleAssignmentScheduleInstance
  - `[UnifiedRoleAssignmentScheduleRequestId <String>]`: The unique identifier of unifiedRoleAssignmentScheduleRequest
  - `[UnifiedRoleDefinitionId <String>]`: The unique identifier of unifiedRoleDefinition
  - `[UnifiedRoleDefinitionId1 <String>]`: The unique identifier of unifiedRoleDefinition
  - `[UnifiedRoleEligibilityScheduleId <String>]`: The unique identifier of unifiedRoleEligibilitySchedule
  - `[UnifiedRoleEligibilityScheduleInstanceId <String>]`: The unique identifier of unifiedRoleEligibilityScheduleInstance
  - `[UnifiedRoleEligibilityScheduleRequestId <String>]`: The unique identifier of unifiedRoleEligibilityScheduleRequest
  - `[WindowsAutopilotDeploymentProfileAssignmentId <String>]`: The unique identifier of windowsAutopilotDeploymentProfileAssignment
  - `[WindowsAutopilotDeploymentProfileId <String>]`: The unique identifier of windowsAutopilotDeploymentProfile
  - `[WindowsAutopilotDeviceIdentityId <String>]`: The unique identifier of windowsAutopilotDeviceIdentity
  - `[WindowsFeatureUpdateProfileAssignmentId <String>]`: The unique identifier of windowsFeatureUpdateProfileAssignment
  - `[WindowsFeatureUpdateProfileId <String>]`: The unique identifier of windowsFeatureUpdateProfile

## RELATED LINKS
