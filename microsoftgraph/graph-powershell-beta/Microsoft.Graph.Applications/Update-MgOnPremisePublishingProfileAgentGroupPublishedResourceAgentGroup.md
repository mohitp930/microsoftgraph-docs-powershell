---
external help file: Microsoft.Graph.Applications-help.xml
Module Name: Microsoft.Graph.Applications
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.applications/update-mgonpremisepublishingprofileagentgrouppublishedresourceagentgroup
schema: 2.0.0
---

# Update-MgOnPremisePublishingProfileAgentGroupPublishedResourceAgentGroup

## SYNOPSIS
Update the navigation property agentGroups in onPremisesPublishingProfiles

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgOnPremisePublishingProfileAgentGroupPublishedResourceAgentGroup -OnPremisesAgentGroupId <String>
 -OnPremisesAgentGroupId1 <String> -OnPremisesPublishingProfileId <String> -PublishedResourceId <String>
 [-AdditionalProperties <Hashtable>] [-Agents <IMicrosoftGraphOnPremisesAgent[]>] [-DisplayName <String>]
 [-Id <String>] [-IsDefault] [-PublishedResources <IMicrosoftGraphPublishedResource[]>]
 [-PublishingType <String>] [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateExpanded1
```
Update-MgOnPremisePublishingProfileAgentGroupPublishedResourceAgentGroup -OnPremisesAgentGroupId <String>
 -OnPremisesAgentGroupId1 <String> -OnPremisesPublishingProfileId <String> -PublishedResourceId <String>
 -OnPremisesAgentId <String> [-AdditionalProperties <Hashtable>] [-Agents <IMicrosoftGraphOnPremisesAgent[]>]
 [-DisplayName <String>] [-Id <String>] [-IsDefault] [-PublishedResources <IMicrosoftGraphPublishedResource[]>]
 [-PublishingType <String>] [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Update1
```
Update-MgOnPremisePublishingProfileAgentGroupPublishedResourceAgentGroup -OnPremisesAgentGroupId <String>
 -OnPremisesAgentGroupId1 <String> -OnPremisesPublishingProfileId <String> -PublishedResourceId <String>
 -OnPremisesAgentId <String> -BodyParameter <IMicrosoftGraphOnPremisesAgentGroup> [-PassThru] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### Update
```
Update-MgOnPremisePublishingProfileAgentGroupPublishedResourceAgentGroup -OnPremisesAgentGroupId <String>
 -OnPremisesAgentGroupId1 <String> -OnPremisesPublishingProfileId <String> -PublishedResourceId <String>
 -BodyParameter <IMicrosoftGraphOnPremisesAgentGroup> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded1
```
Update-MgOnPremisePublishingProfileAgentGroupPublishedResourceAgentGroup -InputObject <IApplicationsIdentity>
 [-AdditionalProperties <Hashtable>] [-Agents <IMicrosoftGraphOnPremisesAgent[]>] [-DisplayName <String>]
 [-Id <String>] [-IsDefault] [-PublishedResources <IMicrosoftGraphPublishedResource[]>]
 [-PublishingType <String>] [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgOnPremisePublishingProfileAgentGroupPublishedResourceAgentGroup -InputObject <IApplicationsIdentity>
 [-AdditionalProperties <Hashtable>] [-Agents <IMicrosoftGraphOnPremisesAgent[]>] [-DisplayName <String>]
 [-Id <String>] [-IsDefault] [-PublishedResources <IMicrosoftGraphPublishedResource[]>]
 [-PublishingType <String>] [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity1
```
Update-MgOnPremisePublishingProfileAgentGroupPublishedResourceAgentGroup -InputObject <IApplicationsIdentity>
 -BodyParameter <IMicrosoftGraphOnPremisesAgentGroup> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgOnPremisePublishingProfileAgentGroupPublishedResourceAgentGroup -InputObject <IApplicationsIdentity>
 -BodyParameter <IMicrosoftGraphOnPremisesAgentGroup> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property agentGroups in onPremisesPublishingProfiles

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: UpdateExpanded, UpdateExpanded1, UpdateViaIdentityExpanded1, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Agents
List of onPremisesAgent that are assigned to an onPremisesAgentGroup.
Read-only.
Nullable.
To construct, see NOTES section for AGENTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphOnPremisesAgent[]
Parameter Sets: UpdateExpanded, UpdateExpanded1, UpdateViaIdentityExpanded1, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
onPremisesAgentGroup
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphOnPremisesAgentGroup
Parameter Sets: Update1, Update, UpdateViaIdentity1, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DisplayName
Display name of the onPremisesAgentGroup.

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateExpanded1, UpdateViaIdentityExpanded1, UpdateViaIdentityExpanded
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
Parameter Sets: UpdateExpanded, UpdateExpanded1, UpdateViaIdentityExpanded1, UpdateViaIdentityExpanded
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
Type: IApplicationsIdentity
Parameter Sets: UpdateViaIdentityExpanded1, UpdateViaIdentityExpanded, UpdateViaIdentity1, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -IsDefault
Indicates if the onPremisesAgentGroup is the default agent group.
Only a single agent group can be the default onPremisesAgentGroup and is set by the system.

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded, UpdateExpanded1, UpdateViaIdentityExpanded1, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OnPremisesAgentGroupId
key: id of onPremisesAgentGroup

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateExpanded1, Update1, Update
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OnPremisesAgentGroupId1
key: id of onPremisesAgentGroup

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateExpanded1, Update1, Update
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OnPremisesAgentId
key: id of onPremisesAgent

```yaml
Type: String
Parameter Sets: UpdateExpanded1, Update1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OnPremisesPublishingProfileId
key: id of onPremisesPublishingProfile

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateExpanded1, Update1, Update
Aliases:

Required: True
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

### -PublishedResourceId
key: id of publishedResource

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateExpanded1, Update1, Update
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PublishedResources
List of publishedResource that are assigned to an onPremisesAgentGroup.
Read-only.
Nullable.
To construct, see NOTES section for PUBLISHEDRESOURCES properties and create a hash table.

```yaml
Type: IMicrosoftGraphPublishedResource[]
Parameter Sets: UpdateExpanded, UpdateExpanded1, UpdateViaIdentityExpanded1, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PublishingType
onPremisesPublishingType

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateExpanded1, UpdateViaIdentityExpanded1, UpdateViaIdentityExpanded
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

### Microsoft.Graph.PowerShell.Models.IApplicationsIdentity

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphOnPremisesAgentGroup

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


AGENTS <IMicrosoftGraphOnPremisesAgent[]>: List of onPremisesAgent that are assigned to an onPremisesAgentGroup. Read-only. Nullable.
  - `[Id <String>]`: Read-only.
  - `[AgentGroups <IMicrosoftGraphOnPremisesAgentGroup[]>]`: List of onPremisesAgentGroups that an onPremisesAgent is assigned to. Read-only. Nullable.
    - `[Id <String>]`: Read-only.
    - `[Agents <IMicrosoftGraphOnPremisesAgent[]>]`: List of onPremisesAgent that are assigned to an onPremisesAgentGroup. Read-only. Nullable.
    - `[DisplayName <String>]`: Display name of the onPremisesAgentGroup.
    - `[IsDefault <Boolean?>]`: Indicates if the onPremisesAgentGroup is the default agent group. Only a single agent group can be the default onPremisesAgentGroup and is set by the system.
    - `[PublishedResources <IMicrosoftGraphPublishedResource[]>]`: List of publishedResource that are assigned to an onPremisesAgentGroup. Read-only. Nullable.
      - `[Id <String>]`: Read-only.
      - `[AgentGroups <IMicrosoftGraphOnPremisesAgentGroup[]>]`: List of onPremisesAgentGroups that a publishedResource is assigned to. Read-only. Nullable.
      - `[DisplayName <String>]`: Display Name of the publishedResource.
      - `[PublishingType <String>]`: onPremisesPublishingType
      - `[ResourceName <String>]`: Name of the publishedResource.
    - `[PublishingType <String>]`: onPremisesPublishingType
  - `[ExternalIP <String>]`: The external IP address as detected by the service for the agent machine. Read-only
  - `[MachineName <String>]`: The name of the machine that the aggent is running on. Read-only
  - `[Status <String>]`: agentStatus
  - `[SupportedPublishingTypes <String[]>]`: 

BODYPARAMETER <IMicrosoftGraphOnPremisesAgentGroup>: onPremisesAgentGroup
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[Agents <IMicrosoftGraphOnPremisesAgent[]>]`: List of onPremisesAgent that are assigned to an onPremisesAgentGroup. Read-only. Nullable.
    - `[Id <String>]`: Read-only.
    - `[AgentGroups <IMicrosoftGraphOnPremisesAgentGroup[]>]`: List of onPremisesAgentGroups that an onPremisesAgent is assigned to. Read-only. Nullable.
    - `[ExternalIP <String>]`: The external IP address as detected by the service for the agent machine. Read-only
    - `[MachineName <String>]`: The name of the machine that the aggent is running on. Read-only
    - `[Status <String>]`: agentStatus
    - `[SupportedPublishingTypes <String[]>]`: 
  - `[DisplayName <String>]`: Display name of the onPremisesAgentGroup.
  - `[IsDefault <Boolean?>]`: Indicates if the onPremisesAgentGroup is the default agent group. Only a single agent group can be the default onPremisesAgentGroup and is set by the system.
  - `[PublishedResources <IMicrosoftGraphPublishedResource[]>]`: List of publishedResource that are assigned to an onPremisesAgentGroup. Read-only. Nullable.
    - `[Id <String>]`: Read-only.
    - `[AgentGroups <IMicrosoftGraphOnPremisesAgentGroup[]>]`: List of onPremisesAgentGroups that a publishedResource is assigned to. Read-only. Nullable.
    - `[DisplayName <String>]`: Display Name of the publishedResource.
    - `[PublishingType <String>]`: onPremisesPublishingType
    - `[ResourceName <String>]`: Name of the publishedResource.
  - `[PublishingType <String>]`: onPremisesPublishingType

INPUTOBJECT <IApplicationsIdentity>: Identity Parameter
  - `[AppRoleAssignmentId <String>]`: key: id of appRoleAssignment
  - `[ApplicationId <String>]`: key: id of application
  - `[ApplicationTemplateId <String>]`: key: id of applicationTemplate
  - `[ConnectorGroupId <String>]`: key: id of connectorGroup
  - `[ConnectorId <String>]`: key: id of connector
  - `[DelegatedPermissionClassificationId <String>]`: key: id of delegatedPermissionClassification
  - `[DirectoryDefinitionId <String>]`: key: id of directoryDefinition
  - `[EndpointId <String>]`: key: id of endpoint
  - `[ExtensionPropertyId <String>]`: key: id of extensionProperty
  - `[GroupId <String>]`: key: id of group
  - `[LicenseDetailsId <String>]`: key: id of licenseDetails
  - `[OnPremisesAgentGroupId <String>]`: key: id of onPremisesAgentGroup
  - `[OnPremisesAgentGroupId1 <String>]`: key: id of onPremisesAgentGroup
  - `[OnPremisesAgentId <String>]`: key: id of onPremisesAgent
  - `[OnPremisesAgentId1 <String>]`: key: id of onPremisesAgent
  - `[OnPremisesPublishingProfileId <String>]`: key: id of onPremisesPublishingProfile
  - `[PublishedResourceId <String>]`: key: id of publishedResource
  - `[PublishedResourceId1 <String>]`: key: id of publishedResource
  - `[ServicePrincipalId <String>]`: key: id of servicePrincipal
  - `[SynchronizationJobId <String>]`: key: id of synchronizationJob
  - `[SynchronizationTemplateId <String>]`: key: id of synchronizationTemplate
  - `[UserId <String>]`: key: id of user

PUBLISHEDRESOURCES <IMicrosoftGraphPublishedResource[]>: List of publishedResource that are assigned to an onPremisesAgentGroup. Read-only. Nullable.
  - `[Id <String>]`: Read-only.
  - `[AgentGroups <IMicrosoftGraphOnPremisesAgentGroup[]>]`: List of onPremisesAgentGroups that a publishedResource is assigned to. Read-only. Nullable.
    - `[Id <String>]`: Read-only.
    - `[Agents <IMicrosoftGraphOnPremisesAgent[]>]`: List of onPremisesAgent that are assigned to an onPremisesAgentGroup. Read-only. Nullable.
      - `[Id <String>]`: Read-only.
      - `[AgentGroups <IMicrosoftGraphOnPremisesAgentGroup[]>]`: List of onPremisesAgentGroups that an onPremisesAgent is assigned to. Read-only. Nullable.
      - `[ExternalIP <String>]`: The external IP address as detected by the service for the agent machine. Read-only
      - `[MachineName <String>]`: The name of the machine that the aggent is running on. Read-only
      - `[Status <String>]`: agentStatus
      - `[SupportedPublishingTypes <String[]>]`: 
    - `[DisplayName <String>]`: Display name of the onPremisesAgentGroup.
    - `[IsDefault <Boolean?>]`: Indicates if the onPremisesAgentGroup is the default agent group. Only a single agent group can be the default onPremisesAgentGroup and is set by the system.
    - `[PublishedResources <IMicrosoftGraphPublishedResource[]>]`: List of publishedResource that are assigned to an onPremisesAgentGroup. Read-only. Nullable.
    - `[PublishingType <String>]`: onPremisesPublishingType
  - `[DisplayName <String>]`: Display Name of the publishedResource.
  - `[PublishingType <String>]`: onPremisesPublishingType
  - `[ResourceName <String>]`: Name of the publishedResource.

## RELATED LINKS