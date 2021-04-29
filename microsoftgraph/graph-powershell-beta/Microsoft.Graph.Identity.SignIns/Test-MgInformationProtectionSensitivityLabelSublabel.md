---
external help file: Microsoft.Graph.Identity.SignIns-help.xml
Module Name: Microsoft.Graph.Identity.SignIns
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/test-mginformationprotectionsensitivitylabelsublabel
schema: 2.0.0
---

# Test-MgInformationProtectionSensitivityLabelSublabel

## SYNOPSIS
Invoke action evaluate

## SYNTAX

### EvaluateExpanded (Default)
```
Test-MgInformationProtectionSensitivityLabelSublabel -SensitivityLabelId <String>
 [-AdditionalProperties <Hashtable>] [-CurrentLabel <IMicrosoftGraphCurrentLabel>]
 [-DiscoveredSensitiveTypes <IMicrosoftGraphDiscoveredSensitiveType[]>] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### Evaluate
```
Test-MgInformationProtectionSensitivityLabelSublabel -SensitivityLabelId <String>
 -BodyParameter <IPathsK62XddInformationprotectionSensitivitylabelsSensitivitylabelIdSublabelsMicrosoftGraphEvaluatePostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### EvaluateViaIdentityExpanded
```
Test-MgInformationProtectionSensitivityLabelSublabel -InputObject <IIdentitySignInsIdentity>
 [-AdditionalProperties <Hashtable>] [-CurrentLabel <IMicrosoftGraphCurrentLabel>]
 [-DiscoveredSensitiveTypes <IMicrosoftGraphDiscoveredSensitiveType[]>] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### EvaluateViaIdentity
```
Test-MgInformationProtectionSensitivityLabelSublabel -InputObject <IIdentitySignInsIdentity>
 -BodyParameter <IPathsK62XddInformationprotectionSensitivitylabelsSensitivitylabelIdSublabelsMicrosoftGraphEvaluatePostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action evaluate

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: EvaluateExpanded, EvaluateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IPathsK62XddInformationprotectionSensitivitylabelsSensitivitylabelIdSublabelsMicrosoftGraphEvaluatePostRequestbodyContentApplicationJsonSchema
Parameter Sets: Evaluate, EvaluateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CurrentLabel
currentLabel
To construct, see NOTES section for CURRENTLABEL properties and create a hash table.

```yaml
Type: IMicrosoftGraphCurrentLabel
Parameter Sets: EvaluateExpanded, EvaluateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DiscoveredSensitiveTypes
.
To construct, see NOTES section for DISCOVEREDSENSITIVETYPES properties and create a hash table.

```yaml
Type: IMicrosoftGraphDiscoveredSensitiveType[]
Parameter Sets: EvaluateExpanded, EvaluateViaIdentityExpanded
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
Type: IIdentitySignInsIdentity
Parameter Sets: EvaluateViaIdentityExpanded, EvaluateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -SensitivityLabelId
key: id of sensitivityLabel

```yaml
Type: String
Parameter Sets: EvaluateExpanded, Evaluate
Aliases:

Required: True
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

### Microsoft.Graph.PowerShell.Models.IIdentitySignInsIdentity

### Microsoft.Graph.PowerShell.Models.IPathsK62XddInformationprotectionSensitivitylabelsSensitivitylabelIdSublabelsMicrosoftGraphEvaluatePostRequestbodyContentApplicationJsonSchema

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphEvaluateLabelJobResponse

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IPathsK62XddInformationprotectionSensitivitylabelsSensitivitylabelIdSublabelsMicrosoftGraphEvaluatePostRequestbodyContentApplicationJsonSchema>: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[CurrentLabel <IMicrosoftGraphCurrentLabel>]`: currentLabel
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[ApplicationMode <String>]`: applicationMode
    - `[Id <String>]`: 
  - `[DiscoveredSensitiveTypes <IMicrosoftGraphDiscoveredSensitiveType[]>]`: 
    - `[ClassificationAttributes <IMicrosoftGraphClassificationAttribute[]>]`: 
      - `[Confidence <Int32?>]`: 
      - `[Count <Int32?>]`: 
    - `[Confidence <Int32?>]`: 
    - `[Count <Int32?>]`: 
    - `[Id <String>]`: 

CURRENTLABEL <IMicrosoftGraphCurrentLabel>: currentLabel
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[ApplicationMode <String>]`: applicationMode
  - `[Id <String>]`: 

DISCOVEREDSENSITIVETYPES <IMicrosoftGraphDiscoveredSensitiveType[]>: .
  - `[ClassificationAttributes <IMicrosoftGraphClassificationAttribute[]>]`: 
    - `[Confidence <Int32?>]`: 
    - `[Count <Int32?>]`: 
  - `[Confidence <Int32?>]`: 
  - `[Count <Int32?>]`: 
  - `[Id <String>]`: 

INPUTOBJECT <IIdentitySignInsIdentity>: Identity Parameter
  - `[ActivityBasedTimeoutPolicyId <String>]`: key: id of activityBasedTimeoutPolicy
  - `[AuthenticationContextClassReferenceId <String>]`: key: id of authenticationContextClassReference
  - `[AuthenticationMethodId <String>]`: key: id of authenticationMethod
  - `[AuthorizationPolicyId <String>]`: key: id of authorizationPolicy
  - `[ClaimsMappingPolicyId <String>]`: key: id of claimsMappingPolicy
  - `[ConditionalAccessPolicyId <String>]`: key: id of conditionalAccessPolicy
  - `[DataLossPreventionPolicyId <String>]`: key: id of dataLossPreventionPolicy
  - `[DataPolicyOperationId <String>]`: key: id of dataPolicyOperation
  - `[DirectoryObjectId <String>]`: key: id of directoryObject
  - `[EmailAuthenticationMethodId <String>]`: key: id of emailAuthenticationMethod
  - `[FeatureRolloutPolicyId <String>]`: key: id of featureRolloutPolicy
  - `[Fido2AuthenticationMethodId <String>]`: key: id of fido2AuthenticationMethod
  - `[HomeRealmDiscoveryPolicyId <String>]`: key: id of homeRealmDiscoveryPolicy
  - `[IdentityProviderId <String>]`: key: id of identityProvider
  - `[IdentityUserFlowId <String>]`: key: id of identityUserFlow
  - `[InformationProtectionLabelId <String>]`: key: id of informationProtectionLabel
  - `[LongRunningOperationId <String>]`: key: id of longRunningOperation
  - `[MicrosoftAuthenticatorAuthenticationMethodId <String>]`: key: id of microsoftAuthenticatorAuthenticationMethod
  - `[NamedLocationId <String>]`: key: id of namedLocation
  - `[OAuth2PermissionGrantId <String>]`: key: id of oAuth2PermissionGrant
  - `[OrganizationId <String>]`: key: id of organization
  - `[PasswordAuthenticationMethodId <String>]`: key: id of passwordAuthenticationMethod
  - `[PasswordlessMicrosoftAuthenticatorAuthenticationMethodId <String>]`: key: id of passwordlessMicrosoftAuthenticatorAuthenticationMethod
  - `[PermissionGrantConditionSetId <String>]`: key: id of permissionGrantConditionSet
  - `[PermissionGrantPolicyId <String>]`: key: id of permissionGrantPolicy
  - `[PhoneAuthenticationMethodId <String>]`: key: id of phoneAuthenticationMethod
  - `[PrivateEndpointConnectionId <String>]`: key: id of privateEndpointConnection
  - `[PrivateLinkResourcePolicyId <String>]`: key: id of privateLinkResourcePolicy
  - `[RiskDetectionId <String>]`: key: id of riskDetection
  - `[RiskyUserHistoryItemId <String>]`: key: id of riskyUserHistoryItem
  - `[RiskyUserId <String>]`: key: id of riskyUser
  - `[SensitivityLabelId <String>]`: key: id of sensitivityLabel
  - `[SensitivityLabelId1 <String>]`: key: id of sensitivityLabel
  - `[TemporaryAccessPassAuthenticationMethodId <String>]`: key: id of temporaryAccessPassAuthenticationMethod
  - `[ThreatAssessmentRequestId <String>]`: key: id of threatAssessmentRequest
  - `[ThreatAssessmentResultId <String>]`: key: id of threatAssessmentResult
  - `[TokenIssuancePolicyId <String>]`: key: id of tokenIssuancePolicy
  - `[TokenLifetimePolicyId <String>]`: key: id of tokenLifetimePolicy
  - `[TrustFrameworkKeySetId <String>]`: key: id of trustFrameworkKeySet
  - `[TrustFrameworkPolicyId <String>]`: key: id of trustFrameworkPolicy
  - `[UnifiedRoleManagementPolicyAssignmentId <String>]`: key: id of unifiedRoleManagementPolicyAssignment
  - `[UnifiedRoleManagementPolicyId <String>]`: key: id of unifiedRoleManagementPolicy
  - `[UnifiedRoleManagementPolicyRuleId <String>]`: key: id of unifiedRoleManagementPolicyRule
  - `[UserId <String>]`: key: id of user
  - `[WindowsHelloForBusinessAuthenticationMethodId <String>]`: key: id of windowsHelloForBusinessAuthenticationMethod

## RELATED LINKS