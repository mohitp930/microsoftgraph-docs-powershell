---
external help file: Microsoft.Graph.Identity.Governance-help.xml
Module Name: Microsoft.Graph.Identity.Governance
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/new-mgprivilegedaccess
schema: 2.0.0
---

# New-MgPrivilegedAccess

## SYNOPSIS
Add new entity to privilegedAccess

## SYNTAX

### CreateExpanded (Default)
```
New-MgPrivilegedAccess [-AdditionalProperties <Hashtable>] [-DisplayName <String>] [-Id <String>]
 [-Resources <IMicrosoftGraphGovernanceResource[]>]
 [-RoleAssignmentRequests <IMicrosoftGraphGovernanceRoleAssignmentRequest[]>]
 [-RoleAssignments <IMicrosoftGraphGovernanceRoleAssignment[]>]
 [-RoleDefinitions <IMicrosoftGraphGovernanceRoleDefinition[]>]
 [-RoleSettings <IMicrosoftGraphGovernanceRoleSetting[]>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgPrivilegedAccess -BodyParameter <IMicrosoftGraphPrivilegedAccess> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
Add new entity to privilegedAccess

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
privilegedAccess
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphPrivilegedAccess
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DisplayName
The display name of the provider managed by PIM.

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

### -Resources
A collection of resources for the provider.
To construct, see NOTES section for RESOURCES properties and create a hash table.

```yaml
Type: IMicrosoftGraphGovernanceResource[]
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RoleAssignmentRequests
A collection of role assignment requests for the provider.
To construct, see NOTES section for ROLEASSIGNMENTREQUESTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphGovernanceRoleAssignmentRequest[]
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RoleAssignments
A collection of role assignments for the provider.
To construct, see NOTES section for ROLEASSIGNMENTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphGovernanceRoleAssignment[]
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RoleDefinitions
A collection of role defintions for the provider.
To construct, see NOTES section for ROLEDEFINITIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphGovernanceRoleDefinition[]
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RoleSettings
A collection of role settings for the provider.
To construct, see NOTES section for ROLESETTINGS properties and create a hash table.

```yaml
Type: IMicrosoftGraphGovernanceRoleSetting[]
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphPrivilegedAccess

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphPrivilegedAccess

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphPrivilegedAccess>: privilegedAccess
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[DisplayName <String>]`: The display name of the provider managed by PIM.
  - `[Resources <IMicrosoftGraphGovernanceResource[]>]`: A collection of resources for the provider.
    - `[Id <String>]`: Read-only.
    - `[DisplayName <String>]`: The display name of the resource.
    - `[ExternalId <String>]`: The external id of the resource, representing its original id in the external system. For example, a subscription resource's external id can be '/subscriptions/c14ae696-5e0c-4e5d-88cc-bef6637737ac'.
    - `[Parent <IMicrosoftGraphGovernanceResource>]`: governanceResource
    - `[RegisteredDateTime <DateTime?>]`: Represents the date time when the resource is registered in PIM.
    - `[RegisteredRoot <String>]`: The externalId of the resource's root scope that is registered in PIM. The root scope can be the parent, grandparent, or higher ancestor resources.
    - `[RoleAssignmentRequests <IMicrosoftGraphGovernanceRoleAssignmentRequest[]>]`: The collection of role assignment requests for the resource.
      - `[Id <String>]`: Read-only.
      - `[AssignmentState <String>]`: Required. The state of the assignment. The possible values are: Eligible (for eligible assignment),  Active (if it is directly assigned), Active (by administrators, or activated on an eligible assignment by the users).
      - `[LinkedEligibleRoleAssignmentId <String>]`: If this is a request for role activation, it represents the id of the eligible assignment being referred; Otherwise, the value is null.
      - `[Reason <String>]`: A message provided by users and administrators when create the request about why it is needed.
      - `[RequestedDateTime <DateTime?>]`: Read-only. The request create time. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
      - `[ResourceId <String>]`: Required. The id of the resource which the role assignment request is associated with.
      - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
        - `[DisplayName <String>]`: The display name of the role definition.
        - `[ExternalId <String>]`: The external id of the role definition.
        - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
        - `[ResourceId <String>]`: Required. The id of the resource associated with the role definition.
        - `[RoleSetting <IMicrosoftGraphGovernanceRoleSetting>]`: governanceRoleSetting
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[Id <String>]`: Read-only.
          - `[AdminEligibleSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when an administrator tries to add an eligible role assignment.
            - `[RuleIdentifier <String>]`: The id of the rule. For example, ExpirationRule and MfaRule.
            - `[Setting <String>]`: The settings of the rule. The value is a JSON string with a list of pairs in the format of Parameter_Name:Parameter_Value. For example, {'permanentAssignment':false,'maximumGrantPeriodInMinutes':129600}
          - `[AdminMemberSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when an administrator tries to add a direct member role assignment.
          - `[IsDefault <Boolean?>]`: Read-only. Indicate if the roleSetting is a default roleSetting
          - `[LastUpdatedBy <String>]`: Read-only. The display name of the administrator who last updated the roleSetting.
          - `[LastUpdatedDateTime <DateTime?>]`: Read-only. The time when the role setting was last updated. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
          - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
          - `[ResourceId <String>]`: Required. The id of the resource that the role setting is associated with.
          - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
          - `[RoleDefinitionId <String>]`: Required. The id of the role definition that the role setting is associated with.
          - `[UserEligibleSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when a user tries to add an eligible role assignment. The setting is not supported for now.
          - `[UserMemberSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when a user tries to activate his role assignment.
        - `[TemplateId <String>]`: 
      - `[RoleDefinitionId <String>]`: Required. The id of the role definition which the role assignment request is associated with.
      - `[Schedule <IMicrosoftGraphGovernanceSchedule>]`: governanceSchedule
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Duration <TimeSpan?>]`: The duration of a role assignment. It is in format of a TimeSpan.
        - `[EndDateTime <DateTime?>]`: The end time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z. Note: if the value is null, it indicates a permanent assignment.
        - `[StartDateTime <DateTime?>]`: The start time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
        - `[Type <String>]`: The role assignment schedule type. Only Once is supported for now.
      - `[Status <IMicrosoftGraphGovernanceRoleAssignmentRequestStatus>]`: governanceRoleAssignmentRequestStatus
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Status <String>]`: 
        - `[StatusDetails <IMicrosoftGraphKeyValue[]>]`: 
          - `[Key <String>]`: Contains the name of the field that a value is associated with. When a sign in or domain hint is included in the sign-in request, corresponding fields are included as key-value pairs. Possible keys: Login hint present, Domain hint present.
          - `[Value <String>]`: Contains the corresponding value for the specified key. The value is true if a sign in hint was included in the sign-in request; otherwise false. The value is true if a domain hint was included in the sign-in request; otherwise false.
        - `[SubStatus <String>]`: 
      - `[Subject <IMicrosoftGraphGovernanceSubject>]`: governanceSubject
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
        - `[DisplayName <String>]`: The display name of the subject.
        - `[Email <String>]`: The email address of the user subject. If the subject is in other types, it is empty.
        - `[PrincipalName <String>]`: The principal name of the user subject. If the subject is in other types, it is empty.
        - `[Type <String>]`: The type of the subject. The value can be User, Group, and ServicePrincipal.
      - `[SubjectId <String>]`: Required. The id of the subject which the role assignment request is associated with.
      - `[Type <String>]`: Required. Representing the type of the operation on the role assignment. The possible values are: AdminAdd , UserAdd , AdminUpdate , AdminRemove , UserRemove , UserExtend , AdminExtend , UserRenew , AdminRenew.
    - `[RoleAssignments <IMicrosoftGraphGovernanceRoleAssignment[]>]`: The collection of role assignments for the resource.
      - `[Id <String>]`: Read-only.
      - `[AssignmentState <String>]`: The state of the assignment. The value can be Eligible for eligible assignment or Active if it is directly assigned Active by administrators, or activated on an eligible assignment by the users.
      - `[EndDateTime <DateTime?>]`: For a non-permanent role assignment, this is the time when the role assignment will be expired. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[ExternalId <String>]`: The external ID the resource that is used to identify the role assignment in the provider.
      - `[LinkedEligibleRoleAssignment <IMicrosoftGraphGovernanceRoleAssignment>]`: governanceRoleAssignment
      - `[LinkedEligibleRoleAssignmentId <String>]`: If this is an active assignment and created due to activation on an eligible assignment, it represents the ID of that eligible assignment; Otherwise, the value is null.
      - `[MemberType <String>]`: The type of member. The value can be: Inherited (if the role assignment is inherited from a parent resource scope), Group (if the role assignment is not inherited, but comes from the membership of a group assignment), or User (if the role assignment is neither inherited nor from a group assignment).
      - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
      - `[ResourceId <String>]`: Required. The ID of the resource which the role assignment is associated with.
      - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
      - `[RoleDefinitionId <String>]`: Required. The ID of the role definition which the role assignment is associated with.
      - `[StartDateTime <DateTime?>]`: The start time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[Status <String>]`: 
      - `[Subject <IMicrosoftGraphGovernanceSubject>]`: governanceSubject
      - `[SubjectId <String>]`: Required. The ID of the subject which the role assignment is associated with.
    - `[RoleDefinitions <IMicrosoftGraphGovernanceRoleDefinition[]>]`: The collection of role defintions for the resource.
    - `[RoleSettings <IMicrosoftGraphGovernanceRoleSetting[]>]`: The collection of role settings for the resource.
    - `[Status <String>]`: The status of a given resource. For example, it could represent whether the resource is locked or not (values: Active/Locked). Note: This property may be extended in the future to support more scenarios.
    - `[Type <String>]`: Required. Resource type. For example, for Azure resources, the type could be 'Subscription', 'ResourceGroup', 'Microsoft.Sql/server', etc.
  - `[RoleAssignmentRequests <IMicrosoftGraphGovernanceRoleAssignmentRequest[]>]`: A collection of role assignment requests for the provider.
  - `[RoleAssignments <IMicrosoftGraphGovernanceRoleAssignment[]>]`: A collection of role assignments for the provider.
  - `[RoleDefinitions <IMicrosoftGraphGovernanceRoleDefinition[]>]`: A collection of role defintions for the provider.
  - `[RoleSettings <IMicrosoftGraphGovernanceRoleSetting[]>]`: A collection of role settings for the provider.

RESOURCES <IMicrosoftGraphGovernanceResource[]>: A collection of resources for the provider.
  - `[Id <String>]`: Read-only.
  - `[DisplayName <String>]`: The display name of the resource.
  - `[ExternalId <String>]`: The external id of the resource, representing its original id in the external system. For example, a subscription resource's external id can be '/subscriptions/c14ae696-5e0c-4e5d-88cc-bef6637737ac'.
  - `[Parent <IMicrosoftGraphGovernanceResource>]`: governanceResource
  - `[RegisteredDateTime <DateTime?>]`: Represents the date time when the resource is registered in PIM.
  - `[RegisteredRoot <String>]`: The externalId of the resource's root scope that is registered in PIM. The root scope can be the parent, grandparent, or higher ancestor resources.
  - `[RoleAssignmentRequests <IMicrosoftGraphGovernanceRoleAssignmentRequest[]>]`: The collection of role assignment requests for the resource.
    - `[Id <String>]`: Read-only.
    - `[AssignmentState <String>]`: Required. The state of the assignment. The possible values are: Eligible (for eligible assignment),  Active (if it is directly assigned), Active (by administrators, or activated on an eligible assignment by the users).
    - `[LinkedEligibleRoleAssignmentId <String>]`: If this is a request for role activation, it represents the id of the eligible assignment being referred; Otherwise, the value is null.
    - `[Reason <String>]`: A message provided by users and administrators when create the request about why it is needed.
    - `[RequestedDateTime <DateTime?>]`: Read-only. The request create time. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
    - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
    - `[ResourceId <String>]`: Required. The id of the resource which the role assignment request is associated with.
    - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[DisplayName <String>]`: The display name of the role definition.
      - `[ExternalId <String>]`: The external id of the role definition.
      - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
      - `[ResourceId <String>]`: Required. The id of the resource associated with the role definition.
      - `[RoleSetting <IMicrosoftGraphGovernanceRoleSetting>]`: governanceRoleSetting
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
        - `[AdminEligibleSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when an administrator tries to add an eligible role assignment.
          - `[RuleIdentifier <String>]`: The id of the rule. For example, ExpirationRule and MfaRule.
          - `[Setting <String>]`: The settings of the rule. The value is a JSON string with a list of pairs in the format of Parameter_Name:Parameter_Value. For example, {'permanentAssignment':false,'maximumGrantPeriodInMinutes':129600}
        - `[AdminMemberSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when an administrator tries to add a direct member role assignment.
        - `[IsDefault <Boolean?>]`: Read-only. Indicate if the roleSetting is a default roleSetting
        - `[LastUpdatedBy <String>]`: Read-only. The display name of the administrator who last updated the roleSetting.
        - `[LastUpdatedDateTime <DateTime?>]`: Read-only. The time when the role setting was last updated. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
        - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
        - `[ResourceId <String>]`: Required. The id of the resource that the role setting is associated with.
        - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
        - `[RoleDefinitionId <String>]`: Required. The id of the role definition that the role setting is associated with.
        - `[UserEligibleSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when a user tries to add an eligible role assignment. The setting is not supported for now.
        - `[UserMemberSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when a user tries to activate his role assignment.
      - `[TemplateId <String>]`: 
    - `[RoleDefinitionId <String>]`: Required. The id of the role definition which the role assignment request is associated with.
    - `[Schedule <IMicrosoftGraphGovernanceSchedule>]`: governanceSchedule
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Duration <TimeSpan?>]`: The duration of a role assignment. It is in format of a TimeSpan.
      - `[EndDateTime <DateTime?>]`: The end time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z. Note: if the value is null, it indicates a permanent assignment.
      - `[StartDateTime <DateTime?>]`: The start time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[Type <String>]`: The role assignment schedule type. Only Once is supported for now.
    - `[Status <IMicrosoftGraphGovernanceRoleAssignmentRequestStatus>]`: governanceRoleAssignmentRequestStatus
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Status <String>]`: 
      - `[StatusDetails <IMicrosoftGraphKeyValue[]>]`: 
        - `[Key <String>]`: Contains the name of the field that a value is associated with. When a sign in or domain hint is included in the sign-in request, corresponding fields are included as key-value pairs. Possible keys: Login hint present, Domain hint present.
        - `[Value <String>]`: Contains the corresponding value for the specified key. The value is true if a sign in hint was included in the sign-in request; otherwise false. The value is true if a domain hint was included in the sign-in request; otherwise false.
      - `[SubStatus <String>]`: 
    - `[Subject <IMicrosoftGraphGovernanceSubject>]`: governanceSubject
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[DisplayName <String>]`: The display name of the subject.
      - `[Email <String>]`: The email address of the user subject. If the subject is in other types, it is empty.
      - `[PrincipalName <String>]`: The principal name of the user subject. If the subject is in other types, it is empty.
      - `[Type <String>]`: The type of the subject. The value can be User, Group, and ServicePrincipal.
    - `[SubjectId <String>]`: Required. The id of the subject which the role assignment request is associated with.
    - `[Type <String>]`: Required. Representing the type of the operation on the role assignment. The possible values are: AdminAdd , UserAdd , AdminUpdate , AdminRemove , UserRemove , UserExtend , AdminExtend , UserRenew , AdminRenew.
  - `[RoleAssignments <IMicrosoftGraphGovernanceRoleAssignment[]>]`: The collection of role assignments for the resource.
    - `[Id <String>]`: Read-only.
    - `[AssignmentState <String>]`: The state of the assignment. The value can be Eligible for eligible assignment or Active if it is directly assigned Active by administrators, or activated on an eligible assignment by the users.
    - `[EndDateTime <DateTime?>]`: For a non-permanent role assignment, this is the time when the role assignment will be expired. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
    - `[ExternalId <String>]`: The external ID the resource that is used to identify the role assignment in the provider.
    - `[LinkedEligibleRoleAssignment <IMicrosoftGraphGovernanceRoleAssignment>]`: governanceRoleAssignment
    - `[LinkedEligibleRoleAssignmentId <String>]`: If this is an active assignment and created due to activation on an eligible assignment, it represents the ID of that eligible assignment; Otherwise, the value is null.
    - `[MemberType <String>]`: The type of member. The value can be: Inherited (if the role assignment is inherited from a parent resource scope), Group (if the role assignment is not inherited, but comes from the membership of a group assignment), or User (if the role assignment is neither inherited nor from a group assignment).
    - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
    - `[ResourceId <String>]`: Required. The ID of the resource which the role assignment is associated with.
    - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
    - `[RoleDefinitionId <String>]`: Required. The ID of the role definition which the role assignment is associated with.
    - `[StartDateTime <DateTime?>]`: The start time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
    - `[Status <String>]`: 
    - `[Subject <IMicrosoftGraphGovernanceSubject>]`: governanceSubject
    - `[SubjectId <String>]`: Required. The ID of the subject which the role assignment is associated with.
  - `[RoleDefinitions <IMicrosoftGraphGovernanceRoleDefinition[]>]`: The collection of role defintions for the resource.
  - `[RoleSettings <IMicrosoftGraphGovernanceRoleSetting[]>]`: The collection of role settings for the resource.
  - `[Status <String>]`: The status of a given resource. For example, it could represent whether the resource is locked or not (values: Active/Locked). Note: This property may be extended in the future to support more scenarios.
  - `[Type <String>]`: Required. Resource type. For example, for Azure resources, the type could be 'Subscription', 'ResourceGroup', 'Microsoft.Sql/server', etc.

ROLEASSIGNMENTREQUESTS <IMicrosoftGraphGovernanceRoleAssignmentRequest[]>: A collection of role assignment requests for the provider.
  - `[Id <String>]`: Read-only.
  - `[AssignmentState <String>]`: Required. The state of the assignment. The possible values are: Eligible (for eligible assignment),  Active (if it is directly assigned), Active (by administrators, or activated on an eligible assignment by the users).
  - `[LinkedEligibleRoleAssignmentId <String>]`: If this is a request for role activation, it represents the id of the eligible assignment being referred; Otherwise, the value is null.
  - `[Reason <String>]`: A message provided by users and administrators when create the request about why it is needed.
  - `[RequestedDateTime <DateTime?>]`: Read-only. The request create time. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
  - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[DisplayName <String>]`: The display name of the resource.
    - `[ExternalId <String>]`: The external id of the resource, representing its original id in the external system. For example, a subscription resource's external id can be '/subscriptions/c14ae696-5e0c-4e5d-88cc-bef6637737ac'.
    - `[Parent <IMicrosoftGraphGovernanceResource>]`: governanceResource
    - `[RegisteredDateTime <DateTime?>]`: Represents the date time when the resource is registered in PIM.
    - `[RegisteredRoot <String>]`: The externalId of the resource's root scope that is registered in PIM. The root scope can be the parent, grandparent, or higher ancestor resources.
    - `[RoleAssignmentRequests <IMicrosoftGraphGovernanceRoleAssignmentRequest[]>]`: The collection of role assignment requests for the resource.
    - `[RoleAssignments <IMicrosoftGraphGovernanceRoleAssignment[]>]`: The collection of role assignments for the resource.
      - `[Id <String>]`: Read-only.
      - `[AssignmentState <String>]`: The state of the assignment. The value can be Eligible for eligible assignment or Active if it is directly assigned Active by administrators, or activated on an eligible assignment by the users.
      - `[EndDateTime <DateTime?>]`: For a non-permanent role assignment, this is the time when the role assignment will be expired. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[ExternalId <String>]`: The external ID the resource that is used to identify the role assignment in the provider.
      - `[LinkedEligibleRoleAssignment <IMicrosoftGraphGovernanceRoleAssignment>]`: governanceRoleAssignment
      - `[LinkedEligibleRoleAssignmentId <String>]`: If this is an active assignment and created due to activation on an eligible assignment, it represents the ID of that eligible assignment; Otherwise, the value is null.
      - `[MemberType <String>]`: The type of member. The value can be: Inherited (if the role assignment is inherited from a parent resource scope), Group (if the role assignment is not inherited, but comes from the membership of a group assignment), or User (if the role assignment is neither inherited nor from a group assignment).
      - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
      - `[ResourceId <String>]`: Required. The ID of the resource which the role assignment is associated with.
      - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
        - `[DisplayName <String>]`: The display name of the role definition.
        - `[ExternalId <String>]`: The external id of the role definition.
        - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
        - `[ResourceId <String>]`: Required. The id of the resource associated with the role definition.
        - `[RoleSetting <IMicrosoftGraphGovernanceRoleSetting>]`: governanceRoleSetting
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[Id <String>]`: Read-only.
          - `[AdminEligibleSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when an administrator tries to add an eligible role assignment.
            - `[RuleIdentifier <String>]`: The id of the rule. For example, ExpirationRule and MfaRule.
            - `[Setting <String>]`: The settings of the rule. The value is a JSON string with a list of pairs in the format of Parameter_Name:Parameter_Value. For example, {'permanentAssignment':false,'maximumGrantPeriodInMinutes':129600}
          - `[AdminMemberSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when an administrator tries to add a direct member role assignment.
          - `[IsDefault <Boolean?>]`: Read-only. Indicate if the roleSetting is a default roleSetting
          - `[LastUpdatedBy <String>]`: Read-only. The display name of the administrator who last updated the roleSetting.
          - `[LastUpdatedDateTime <DateTime?>]`: Read-only. The time when the role setting was last updated. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
          - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
          - `[ResourceId <String>]`: Required. The id of the resource that the role setting is associated with.
          - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
          - `[RoleDefinitionId <String>]`: Required. The id of the role definition that the role setting is associated with.
          - `[UserEligibleSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when a user tries to add an eligible role assignment. The setting is not supported for now.
          - `[UserMemberSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when a user tries to activate his role assignment.
        - `[TemplateId <String>]`: 
      - `[RoleDefinitionId <String>]`: Required. The ID of the role definition which the role assignment is associated with.
      - `[StartDateTime <DateTime?>]`: The start time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[Status <String>]`: 
      - `[Subject <IMicrosoftGraphGovernanceSubject>]`: governanceSubject
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
        - `[DisplayName <String>]`: The display name of the subject.
        - `[Email <String>]`: The email address of the user subject. If the subject is in other types, it is empty.
        - `[PrincipalName <String>]`: The principal name of the user subject. If the subject is in other types, it is empty.
        - `[Type <String>]`: The type of the subject. The value can be User, Group, and ServicePrincipal.
      - `[SubjectId <String>]`: Required. The ID of the subject which the role assignment is associated with.
    - `[RoleDefinitions <IMicrosoftGraphGovernanceRoleDefinition[]>]`: The collection of role defintions for the resource.
    - `[RoleSettings <IMicrosoftGraphGovernanceRoleSetting[]>]`: The collection of role settings for the resource.
    - `[Status <String>]`: The status of a given resource. For example, it could represent whether the resource is locked or not (values: Active/Locked). Note: This property may be extended in the future to support more scenarios.
    - `[Type <String>]`: Required. Resource type. For example, for Azure resources, the type could be 'Subscription', 'ResourceGroup', 'Microsoft.Sql/server', etc.
  - `[ResourceId <String>]`: Required. The id of the resource which the role assignment request is associated with.
  - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
  - `[RoleDefinitionId <String>]`: Required. The id of the role definition which the role assignment request is associated with.
  - `[Schedule <IMicrosoftGraphGovernanceSchedule>]`: governanceSchedule
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Duration <TimeSpan?>]`: The duration of a role assignment. It is in format of a TimeSpan.
    - `[EndDateTime <DateTime?>]`: The end time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z. Note: if the value is null, it indicates a permanent assignment.
    - `[StartDateTime <DateTime?>]`: The start time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
    - `[Type <String>]`: The role assignment schedule type. Only Once is supported for now.
  - `[Status <IMicrosoftGraphGovernanceRoleAssignmentRequestStatus>]`: governanceRoleAssignmentRequestStatus
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Status <String>]`: 
    - `[StatusDetails <IMicrosoftGraphKeyValue[]>]`: 
      - `[Key <String>]`: Contains the name of the field that a value is associated with. When a sign in or domain hint is included in the sign-in request, corresponding fields are included as key-value pairs. Possible keys: Login hint present, Domain hint present.
      - `[Value <String>]`: Contains the corresponding value for the specified key. The value is true if a sign in hint was included in the sign-in request; otherwise false. The value is true if a domain hint was included in the sign-in request; otherwise false.
    - `[SubStatus <String>]`: 
  - `[Subject <IMicrosoftGraphGovernanceSubject>]`: governanceSubject
  - `[SubjectId <String>]`: Required. The id of the subject which the role assignment request is associated with.
  - `[Type <String>]`: Required. Representing the type of the operation on the role assignment. The possible values are: AdminAdd , UserAdd , AdminUpdate , AdminRemove , UserRemove , UserExtend , AdminExtend , UserRenew , AdminRenew.

ROLEASSIGNMENTS <IMicrosoftGraphGovernanceRoleAssignment[]>: A collection of role assignments for the provider.
  - `[Id <String>]`: Read-only.
  - `[AssignmentState <String>]`: The state of the assignment. The value can be Eligible for eligible assignment or Active if it is directly assigned Active by administrators, or activated on an eligible assignment by the users.
  - `[EndDateTime <DateTime?>]`: For a non-permanent role assignment, this is the time when the role assignment will be expired. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
  - `[ExternalId <String>]`: The external ID the resource that is used to identify the role assignment in the provider.
  - `[LinkedEligibleRoleAssignment <IMicrosoftGraphGovernanceRoleAssignment>]`: governanceRoleAssignment
  - `[LinkedEligibleRoleAssignmentId <String>]`: If this is an active assignment and created due to activation on an eligible assignment, it represents the ID of that eligible assignment; Otherwise, the value is null.
  - `[MemberType <String>]`: The type of member. The value can be: Inherited (if the role assignment is inherited from a parent resource scope), Group (if the role assignment is not inherited, but comes from the membership of a group assignment), or User (if the role assignment is neither inherited nor from a group assignment).
  - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[DisplayName <String>]`: The display name of the resource.
    - `[ExternalId <String>]`: The external id of the resource, representing its original id in the external system. For example, a subscription resource's external id can be '/subscriptions/c14ae696-5e0c-4e5d-88cc-bef6637737ac'.
    - `[Parent <IMicrosoftGraphGovernanceResource>]`: governanceResource
    - `[RegisteredDateTime <DateTime?>]`: Represents the date time when the resource is registered in PIM.
    - `[RegisteredRoot <String>]`: The externalId of the resource's root scope that is registered in PIM. The root scope can be the parent, grandparent, or higher ancestor resources.
    - `[RoleAssignmentRequests <IMicrosoftGraphGovernanceRoleAssignmentRequest[]>]`: The collection of role assignment requests for the resource.
      - `[Id <String>]`: Read-only.
      - `[AssignmentState <String>]`: Required. The state of the assignment. The possible values are: Eligible (for eligible assignment),  Active (if it is directly assigned), Active (by administrators, or activated on an eligible assignment by the users).
      - `[LinkedEligibleRoleAssignmentId <String>]`: If this is a request for role activation, it represents the id of the eligible assignment being referred; Otherwise, the value is null.
      - `[Reason <String>]`: A message provided by users and administrators when create the request about why it is needed.
      - `[RequestedDateTime <DateTime?>]`: Read-only. The request create time. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
      - `[ResourceId <String>]`: Required. The id of the resource which the role assignment request is associated with.
      - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
        - `[DisplayName <String>]`: The display name of the role definition.
        - `[ExternalId <String>]`: The external id of the role definition.
        - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
        - `[ResourceId <String>]`: Required. The id of the resource associated with the role definition.
        - `[RoleSetting <IMicrosoftGraphGovernanceRoleSetting>]`: governanceRoleSetting
          - `[(Any) <Object>]`: This indicates any property can be added to this object.
          - `[Id <String>]`: Read-only.
          - `[AdminEligibleSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when an administrator tries to add an eligible role assignment.
            - `[RuleIdentifier <String>]`: The id of the rule. For example, ExpirationRule and MfaRule.
            - `[Setting <String>]`: The settings of the rule. The value is a JSON string with a list of pairs in the format of Parameter_Name:Parameter_Value. For example, {'permanentAssignment':false,'maximumGrantPeriodInMinutes':129600}
          - `[AdminMemberSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when an administrator tries to add a direct member role assignment.
          - `[IsDefault <Boolean?>]`: Read-only. Indicate if the roleSetting is a default roleSetting
          - `[LastUpdatedBy <String>]`: Read-only. The display name of the administrator who last updated the roleSetting.
          - `[LastUpdatedDateTime <DateTime?>]`: Read-only. The time when the role setting was last updated. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
          - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
          - `[ResourceId <String>]`: Required. The id of the resource that the role setting is associated with.
          - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
          - `[RoleDefinitionId <String>]`: Required. The id of the role definition that the role setting is associated with.
          - `[UserEligibleSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when a user tries to add an eligible role assignment. The setting is not supported for now.
          - `[UserMemberSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when a user tries to activate his role assignment.
        - `[TemplateId <String>]`: 
      - `[RoleDefinitionId <String>]`: Required. The id of the role definition which the role assignment request is associated with.
      - `[Schedule <IMicrosoftGraphGovernanceSchedule>]`: governanceSchedule
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Duration <TimeSpan?>]`: The duration of a role assignment. It is in format of a TimeSpan.
        - `[EndDateTime <DateTime?>]`: The end time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z. Note: if the value is null, it indicates a permanent assignment.
        - `[StartDateTime <DateTime?>]`: The start time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
        - `[Type <String>]`: The role assignment schedule type. Only Once is supported for now.
      - `[Status <IMicrosoftGraphGovernanceRoleAssignmentRequestStatus>]`: governanceRoleAssignmentRequestStatus
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Status <String>]`: 
        - `[StatusDetails <IMicrosoftGraphKeyValue[]>]`: 
          - `[Key <String>]`: Contains the name of the field that a value is associated with. When a sign in or domain hint is included in the sign-in request, corresponding fields are included as key-value pairs. Possible keys: Login hint present, Domain hint present.
          - `[Value <String>]`: Contains the corresponding value for the specified key. The value is true if a sign in hint was included in the sign-in request; otherwise false. The value is true if a domain hint was included in the sign-in request; otherwise false.
        - `[SubStatus <String>]`: 
      - `[Subject <IMicrosoftGraphGovernanceSubject>]`: governanceSubject
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
        - `[DisplayName <String>]`: The display name of the subject.
        - `[Email <String>]`: The email address of the user subject. If the subject is in other types, it is empty.
        - `[PrincipalName <String>]`: The principal name of the user subject. If the subject is in other types, it is empty.
        - `[Type <String>]`: The type of the subject. The value can be User, Group, and ServicePrincipal.
      - `[SubjectId <String>]`: Required. The id of the subject which the role assignment request is associated with.
      - `[Type <String>]`: Required. Representing the type of the operation on the role assignment. The possible values are: AdminAdd , UserAdd , AdminUpdate , AdminRemove , UserRemove , UserExtend , AdminExtend , UserRenew , AdminRenew.
    - `[RoleAssignments <IMicrosoftGraphGovernanceRoleAssignment[]>]`: The collection of role assignments for the resource.
    - `[RoleDefinitions <IMicrosoftGraphGovernanceRoleDefinition[]>]`: The collection of role defintions for the resource.
    - `[RoleSettings <IMicrosoftGraphGovernanceRoleSetting[]>]`: The collection of role settings for the resource.
    - `[Status <String>]`: The status of a given resource. For example, it could represent whether the resource is locked or not (values: Active/Locked). Note: This property may be extended in the future to support more scenarios.
    - `[Type <String>]`: Required. Resource type. For example, for Azure resources, the type could be 'Subscription', 'ResourceGroup', 'Microsoft.Sql/server', etc.
  - `[ResourceId <String>]`: Required. The ID of the resource which the role assignment is associated with.
  - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
  - `[RoleDefinitionId <String>]`: Required. The ID of the role definition which the role assignment is associated with.
  - `[StartDateTime <DateTime?>]`: The start time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
  - `[Status <String>]`: 
  - `[Subject <IMicrosoftGraphGovernanceSubject>]`: governanceSubject
  - `[SubjectId <String>]`: Required. The ID of the subject which the role assignment is associated with.

ROLEDEFINITIONS <IMicrosoftGraphGovernanceRoleDefinition[]>: A collection of role defintions for the provider.
  - `[Id <String>]`: Read-only.
  - `[DisplayName <String>]`: The display name of the role definition.
  - `[ExternalId <String>]`: The external id of the role definition.
  - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[DisplayName <String>]`: The display name of the resource.
    - `[ExternalId <String>]`: The external id of the resource, representing its original id in the external system. For example, a subscription resource's external id can be '/subscriptions/c14ae696-5e0c-4e5d-88cc-bef6637737ac'.
    - `[Parent <IMicrosoftGraphGovernanceResource>]`: governanceResource
    - `[RegisteredDateTime <DateTime?>]`: Represents the date time when the resource is registered in PIM.
    - `[RegisteredRoot <String>]`: The externalId of the resource's root scope that is registered in PIM. The root scope can be the parent, grandparent, or higher ancestor resources.
    - `[RoleAssignmentRequests <IMicrosoftGraphGovernanceRoleAssignmentRequest[]>]`: The collection of role assignment requests for the resource.
      - `[Id <String>]`: Read-only.
      - `[AssignmentState <String>]`: Required. The state of the assignment. The possible values are: Eligible (for eligible assignment),  Active (if it is directly assigned), Active (by administrators, or activated on an eligible assignment by the users).
      - `[LinkedEligibleRoleAssignmentId <String>]`: If this is a request for role activation, it represents the id of the eligible assignment being referred; Otherwise, the value is null.
      - `[Reason <String>]`: A message provided by users and administrators when create the request about why it is needed.
      - `[RequestedDateTime <DateTime?>]`: Read-only. The request create time. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
      - `[ResourceId <String>]`: Required. The id of the resource which the role assignment request is associated with.
      - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
      - `[RoleDefinitionId <String>]`: Required. The id of the role definition which the role assignment request is associated with.
      - `[Schedule <IMicrosoftGraphGovernanceSchedule>]`: governanceSchedule
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Duration <TimeSpan?>]`: The duration of a role assignment. It is in format of a TimeSpan.
        - `[EndDateTime <DateTime?>]`: The end time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z. Note: if the value is null, it indicates a permanent assignment.
        - `[StartDateTime <DateTime?>]`: The start time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
        - `[Type <String>]`: The role assignment schedule type. Only Once is supported for now.
      - `[Status <IMicrosoftGraphGovernanceRoleAssignmentRequestStatus>]`: governanceRoleAssignmentRequestStatus
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Status <String>]`: 
        - `[StatusDetails <IMicrosoftGraphKeyValue[]>]`: 
          - `[Key <String>]`: Contains the name of the field that a value is associated with. When a sign in or domain hint is included in the sign-in request, corresponding fields are included as key-value pairs. Possible keys: Login hint present, Domain hint present.
          - `[Value <String>]`: Contains the corresponding value for the specified key. The value is true if a sign in hint was included in the sign-in request; otherwise false. The value is true if a domain hint was included in the sign-in request; otherwise false.
        - `[SubStatus <String>]`: 
      - `[Subject <IMicrosoftGraphGovernanceSubject>]`: governanceSubject
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
        - `[DisplayName <String>]`: The display name of the subject.
        - `[Email <String>]`: The email address of the user subject. If the subject is in other types, it is empty.
        - `[PrincipalName <String>]`: The principal name of the user subject. If the subject is in other types, it is empty.
        - `[Type <String>]`: The type of the subject. The value can be User, Group, and ServicePrincipal.
      - `[SubjectId <String>]`: Required. The id of the subject which the role assignment request is associated with.
      - `[Type <String>]`: Required. Representing the type of the operation on the role assignment. The possible values are: AdminAdd , UserAdd , AdminUpdate , AdminRemove , UserRemove , UserExtend , AdminExtend , UserRenew , AdminRenew.
    - `[RoleAssignments <IMicrosoftGraphGovernanceRoleAssignment[]>]`: The collection of role assignments for the resource.
      - `[Id <String>]`: Read-only.
      - `[AssignmentState <String>]`: The state of the assignment. The value can be Eligible for eligible assignment or Active if it is directly assigned Active by administrators, or activated on an eligible assignment by the users.
      - `[EndDateTime <DateTime?>]`: For a non-permanent role assignment, this is the time when the role assignment will be expired. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[ExternalId <String>]`: The external ID the resource that is used to identify the role assignment in the provider.
      - `[LinkedEligibleRoleAssignment <IMicrosoftGraphGovernanceRoleAssignment>]`: governanceRoleAssignment
      - `[LinkedEligibleRoleAssignmentId <String>]`: If this is an active assignment and created due to activation on an eligible assignment, it represents the ID of that eligible assignment; Otherwise, the value is null.
      - `[MemberType <String>]`: The type of member. The value can be: Inherited (if the role assignment is inherited from a parent resource scope), Group (if the role assignment is not inherited, but comes from the membership of a group assignment), or User (if the role assignment is neither inherited nor from a group assignment).
      - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
      - `[ResourceId <String>]`: Required. The ID of the resource which the role assignment is associated with.
      - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
      - `[RoleDefinitionId <String>]`: Required. The ID of the role definition which the role assignment is associated with.
      - `[StartDateTime <DateTime?>]`: The start time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[Status <String>]`: 
      - `[Subject <IMicrosoftGraphGovernanceSubject>]`: governanceSubject
      - `[SubjectId <String>]`: Required. The ID of the subject which the role assignment is associated with.
    - `[RoleDefinitions <IMicrosoftGraphGovernanceRoleDefinition[]>]`: The collection of role defintions for the resource.
    - `[RoleSettings <IMicrosoftGraphGovernanceRoleSetting[]>]`: The collection of role settings for the resource.
      - `[Id <String>]`: Read-only.
      - `[AdminEligibleSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when an administrator tries to add an eligible role assignment.
        - `[RuleIdentifier <String>]`: The id of the rule. For example, ExpirationRule and MfaRule.
        - `[Setting <String>]`: The settings of the rule. The value is a JSON string with a list of pairs in the format of Parameter_Name:Parameter_Value. For example, {'permanentAssignment':false,'maximumGrantPeriodInMinutes':129600}
      - `[AdminMemberSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when an administrator tries to add a direct member role assignment.
      - `[IsDefault <Boolean?>]`: Read-only. Indicate if the roleSetting is a default roleSetting
      - `[LastUpdatedBy <String>]`: Read-only. The display name of the administrator who last updated the roleSetting.
      - `[LastUpdatedDateTime <DateTime?>]`: Read-only. The time when the role setting was last updated. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
      - `[ResourceId <String>]`: Required. The id of the resource that the role setting is associated with.
      - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
      - `[RoleDefinitionId <String>]`: Required. The id of the role definition that the role setting is associated with.
      - `[UserEligibleSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when a user tries to add an eligible role assignment. The setting is not supported for now.
      - `[UserMemberSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when a user tries to activate his role assignment.
    - `[Status <String>]`: The status of a given resource. For example, it could represent whether the resource is locked or not (values: Active/Locked). Note: This property may be extended in the future to support more scenarios.
    - `[Type <String>]`: Required. Resource type. For example, for Azure resources, the type could be 'Subscription', 'ResourceGroup', 'Microsoft.Sql/server', etc.
  - `[ResourceId <String>]`: Required. The id of the resource associated with the role definition.
  - `[RoleSetting <IMicrosoftGraphGovernanceRoleSetting>]`: governanceRoleSetting
  - `[TemplateId <String>]`: 

ROLESETTINGS <IMicrosoftGraphGovernanceRoleSetting[]>: A collection of role settings for the provider.
  - `[Id <String>]`: Read-only.
  - `[AdminEligibleSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when an administrator tries to add an eligible role assignment.
    - `[RuleIdentifier <String>]`: The id of the rule. For example, ExpirationRule and MfaRule.
    - `[Setting <String>]`: The settings of the rule. The value is a JSON string with a list of pairs in the format of Parameter_Name:Parameter_Value. For example, {'permanentAssignment':false,'maximumGrantPeriodInMinutes':129600}
  - `[AdminMemberSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when an administrator tries to add a direct member role assignment.
  - `[IsDefault <Boolean?>]`: Read-only. Indicate if the roleSetting is a default roleSetting
  - `[LastUpdatedBy <String>]`: Read-only. The display name of the administrator who last updated the roleSetting.
  - `[LastUpdatedDateTime <DateTime?>]`: Read-only. The time when the role setting was last updated. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
  - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[DisplayName <String>]`: The display name of the resource.
    - `[ExternalId <String>]`: The external id of the resource, representing its original id in the external system. For example, a subscription resource's external id can be '/subscriptions/c14ae696-5e0c-4e5d-88cc-bef6637737ac'.
    - `[Parent <IMicrosoftGraphGovernanceResource>]`: governanceResource
    - `[RegisteredDateTime <DateTime?>]`: Represents the date time when the resource is registered in PIM.
    - `[RegisteredRoot <String>]`: The externalId of the resource's root scope that is registered in PIM. The root scope can be the parent, grandparent, or higher ancestor resources.
    - `[RoleAssignmentRequests <IMicrosoftGraphGovernanceRoleAssignmentRequest[]>]`: The collection of role assignment requests for the resource.
      - `[Id <String>]`: Read-only.
      - `[AssignmentState <String>]`: Required. The state of the assignment. The possible values are: Eligible (for eligible assignment),  Active (if it is directly assigned), Active (by administrators, or activated on an eligible assignment by the users).
      - `[LinkedEligibleRoleAssignmentId <String>]`: If this is a request for role activation, it represents the id of the eligible assignment being referred; Otherwise, the value is null.
      - `[Reason <String>]`: A message provided by users and administrators when create the request about why it is needed.
      - `[RequestedDateTime <DateTime?>]`: Read-only. The request create time. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
      - `[ResourceId <String>]`: Required. The id of the resource which the role assignment request is associated with.
      - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
        - `[DisplayName <String>]`: The display name of the role definition.
        - `[ExternalId <String>]`: The external id of the role definition.
        - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
        - `[ResourceId <String>]`: Required. The id of the resource associated with the role definition.
        - `[RoleSetting <IMicrosoftGraphGovernanceRoleSetting>]`: governanceRoleSetting
        - `[TemplateId <String>]`: 
      - `[RoleDefinitionId <String>]`: Required. The id of the role definition which the role assignment request is associated with.
      - `[Schedule <IMicrosoftGraphGovernanceSchedule>]`: governanceSchedule
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Duration <TimeSpan?>]`: The duration of a role assignment. It is in format of a TimeSpan.
        - `[EndDateTime <DateTime?>]`: The end time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z. Note: if the value is null, it indicates a permanent assignment.
        - `[StartDateTime <DateTime?>]`: The start time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
        - `[Type <String>]`: The role assignment schedule type. Only Once is supported for now.
      - `[Status <IMicrosoftGraphGovernanceRoleAssignmentRequestStatus>]`: governanceRoleAssignmentRequestStatus
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Status <String>]`: 
        - `[StatusDetails <IMicrosoftGraphKeyValue[]>]`: 
          - `[Key <String>]`: Contains the name of the field that a value is associated with. When a sign in or domain hint is included in the sign-in request, corresponding fields are included as key-value pairs. Possible keys: Login hint present, Domain hint present.
          - `[Value <String>]`: Contains the corresponding value for the specified key. The value is true if a sign in hint was included in the sign-in request; otherwise false. The value is true if a domain hint was included in the sign-in request; otherwise false.
        - `[SubStatus <String>]`: 
      - `[Subject <IMicrosoftGraphGovernanceSubject>]`: governanceSubject
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
        - `[DisplayName <String>]`: The display name of the subject.
        - `[Email <String>]`: The email address of the user subject. If the subject is in other types, it is empty.
        - `[PrincipalName <String>]`: The principal name of the user subject. If the subject is in other types, it is empty.
        - `[Type <String>]`: The type of the subject. The value can be User, Group, and ServicePrincipal.
      - `[SubjectId <String>]`: Required. The id of the subject which the role assignment request is associated with.
      - `[Type <String>]`: Required. Representing the type of the operation on the role assignment. The possible values are: AdminAdd , UserAdd , AdminUpdate , AdminRemove , UserRemove , UserExtend , AdminExtend , UserRenew , AdminRenew.
    - `[RoleAssignments <IMicrosoftGraphGovernanceRoleAssignment[]>]`: The collection of role assignments for the resource.
      - `[Id <String>]`: Read-only.
      - `[AssignmentState <String>]`: The state of the assignment. The value can be Eligible for eligible assignment or Active if it is directly assigned Active by administrators, or activated on an eligible assignment by the users.
      - `[EndDateTime <DateTime?>]`: For a non-permanent role assignment, this is the time when the role assignment will be expired. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[ExternalId <String>]`: The external ID the resource that is used to identify the role assignment in the provider.
      - `[LinkedEligibleRoleAssignment <IMicrosoftGraphGovernanceRoleAssignment>]`: governanceRoleAssignment
      - `[LinkedEligibleRoleAssignmentId <String>]`: If this is an active assignment and created due to activation on an eligible assignment, it represents the ID of that eligible assignment; Otherwise, the value is null.
      - `[MemberType <String>]`: The type of member. The value can be: Inherited (if the role assignment is inherited from a parent resource scope), Group (if the role assignment is not inherited, but comes from the membership of a group assignment), or User (if the role assignment is neither inherited nor from a group assignment).
      - `[Resource <IMicrosoftGraphGovernanceResource>]`: governanceResource
      - `[ResourceId <String>]`: Required. The ID of the resource which the role assignment is associated with.
      - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
      - `[RoleDefinitionId <String>]`: Required. The ID of the role definition which the role assignment is associated with.
      - `[StartDateTime <DateTime?>]`: The start time of the role assignment. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z
      - `[Status <String>]`: 
      - `[Subject <IMicrosoftGraphGovernanceSubject>]`: governanceSubject
      - `[SubjectId <String>]`: Required. The ID of the subject which the role assignment is associated with.
    - `[RoleDefinitions <IMicrosoftGraphGovernanceRoleDefinition[]>]`: The collection of role defintions for the resource.
    - `[RoleSettings <IMicrosoftGraphGovernanceRoleSetting[]>]`: The collection of role settings for the resource.
    - `[Status <String>]`: The status of a given resource. For example, it could represent whether the resource is locked or not (values: Active/Locked). Note: This property may be extended in the future to support more scenarios.
    - `[Type <String>]`: Required. Resource type. For example, for Azure resources, the type could be 'Subscription', 'ResourceGroup', 'Microsoft.Sql/server', etc.
  - `[ResourceId <String>]`: Required. The id of the resource that the role setting is associated with.
  - `[RoleDefinition <IMicrosoftGraphGovernanceRoleDefinition>]`: governanceRoleDefinition
  - `[RoleDefinitionId <String>]`: Required. The id of the role definition that the role setting is associated with.
  - `[UserEligibleSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when a user tries to add an eligible role assignment. The setting is not supported for now.
  - `[UserMemberSettings <IMicrosoftGraphGovernanceRuleSetting[]>]`: The rule settings that are evaluated when a user tries to activate his role assignment.

## RELATED LINKS

## RELATED LINKS