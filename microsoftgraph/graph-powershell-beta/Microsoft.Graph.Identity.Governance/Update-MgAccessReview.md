---
external help file: Microsoft.Graph.Identity.Governance-help.xml
Module Name: Microsoft.Graph.Identity.Governance
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/update-mgaccessreview
schema: 2.0.0
---

# Update-MgAccessReview

## SYNOPSIS
Update entity in accessReviews

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgAccessReview -AccessReviewId <String> [-AdditionalProperties <Hashtable>]
 [-BusinessFlowTemplateId <String>] [-CreatedBy <IMicrosoftGraphUserIdentity>]
 [-Decisions <IMicrosoftGraphAccessReviewDecision[]>] [-Description <String>] [-DisplayName <String>]
 [-EndDateTime <DateTime>] [-Id <String>] [-Instances <IMicrosoftGraphAccessReview[]>]
 [-MyDecisions <IMicrosoftGraphAccessReviewDecision[]>] [-ReviewedEntity <IMicrosoftGraphIdentity>]
 [-ReviewerType <String>] [-Reviewers <IMicrosoftGraphAccessReviewReviewer[]>]
 [-Settings <IMicrosoftGraphAccessReviewSettings>] [-StartDateTime <DateTime>] [-Status <String>] [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Update
```
Update-MgAccessReview -AccessReviewId <String> -BodyParameter <IMicrosoftGraphAccessReview> [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgAccessReview -InputObject <IIdentityGovernanceIdentity> [-AdditionalProperties <Hashtable>]
 [-BusinessFlowTemplateId <String>] [-CreatedBy <IMicrosoftGraphUserIdentity>]
 [-Decisions <IMicrosoftGraphAccessReviewDecision[]>] [-Description <String>] [-DisplayName <String>]
 [-EndDateTime <DateTime>] [-Id <String>] [-Instances <IMicrosoftGraphAccessReview[]>]
 [-MyDecisions <IMicrosoftGraphAccessReviewDecision[]>] [-ReviewedEntity <IMicrosoftGraphIdentity>]
 [-ReviewerType <String>] [-Reviewers <IMicrosoftGraphAccessReviewReviewer[]>]
 [-Settings <IMicrosoftGraphAccessReviewSettings>] [-StartDateTime <DateTime>] [-Status <String>] [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgAccessReview -InputObject <IIdentityGovernanceIdentity> -BodyParameter <IMicrosoftGraphAccessReview>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Update entity in accessReviews

## EXAMPLES

## PARAMETERS

### -AccessReviewId
key: id of accessReview

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

### -BodyParameter
accessReview
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphAccessReview
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -BusinessFlowTemplateId
The business flow template identifier.
Required on create.
This value is case sensitive.

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

### -CreatedBy
userIdentity
To construct, see NOTES section for CREATEDBY properties and create a hash table.

```yaml
Type: IMicrosoftGraphUserIdentity
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Decisions
The collection of decisions for this access review.
To construct, see NOTES section for DECISIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphAccessReviewDecision[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
The description provided by the access review creator, to show to the reviewers.

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

### -DisplayName
The access review name.
Required on create.

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

### -EndDateTime
The DateTime when the review is scheduled to end.
This must be at least one day later than the start date.
Required on create.

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
Type: IIdentityGovernanceIdentity
Parameter Sets: UpdateViaIdentityExpanded, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Instances
The collection of access reviews instances past, present and future, if this object is a recurring access review.
To construct, see NOTES section for INSTANCES properties and create a hash table.

```yaml
Type: IMicrosoftGraphAccessReview[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MyDecisions
The collection of decisions for the caller, if the caller is a reviewer.
To construct, see NOTES section for MYDECISIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphAccessReviewDecision[]
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

### -ReviewedEntity
identity
To construct, see NOTES section for REVIEWEDENTITY properties and create a hash table.

```yaml
Type: IMicrosoftGraphIdentity
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Reviewers
The collection of reviewers for an access review, if access review reviewerType is of type delegated.
To construct, see NOTES section for REVIEWERS properties and create a hash table.

```yaml
Type: IMicrosoftGraphAccessReviewReviewer[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ReviewerType
The relationship type of reviewer to the target object, one of self, delegated or entityOwners.
Required on create.

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

### -Settings
accessReviewSettings
To construct, see NOTES section for SETTINGS properties and create a hash table.

```yaml
Type: IMicrosoftGraphAccessReviewSettings
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -StartDateTime
The DateTime when the review is scheduled to be start.
This could be a date in the future.
Required on create.

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

### -Status
This read-only field specifies the status of an accessReview.
The typical states include Initializing, NotStarted, Starting,InProgress, Completing, Completed, AutoReviewing, and AutoReviewed.

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

### Microsoft.Graph.PowerShell.Models.IIdentityGovernanceIdentity

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAccessReview

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphAccessReview>: accessReview
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[BusinessFlowTemplateId <String>]`: The business flow template identifier. Required on create.  This value is case sensitive.
  - `[CreatedBy <IMicrosoftGraphUserIdentity>]`: userIdentity
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
    - `[Id <String>]`: Unique identifier for the identity.
    - `[IPAddress <String>]`: Indicates the client IP address used by user performing the activity (audit log only).
    - `[UserPrincipalName <String>]`: The userPrincipalName attribute of the user.
  - `[Decisions <IMicrosoftGraphAccessReviewDecision[]>]`: The collection of decisions for this access review.
    - `[Id <String>]`: Read-only.
    - `[AccessRecommendation <String>]`: The feature- generated recommendation shown to the reviewer, one of Approve, Deny or NotAvailable.
    - `[AccessReviewId <String>]`: The feature-generated id of the access review.
    - `[AppliedBy <IMicrosoftGraphUserIdentity>]`: userIdentity
    - `[AppliedDateTime <DateTime?>]`: The date and time when the review decision was applied.
    - `[ApplyResult <String>]`: The outcome of applying the decision, one of NotApplied, Success, Failed, NotFound or NotSupported.
    - `[Justification <String>]`: The reviewer's business justification, if supplied.
    - `[ReviewResult <String>]`: The result of the review, one of NotReviewed, Deny, DontKnow or Approve.
    - `[ReviewedBy <IMicrosoftGraphUserIdentity>]`: userIdentity
    - `[ReviewedDateTime <DateTime?>]`: 
  - `[Description <String>]`: The description provided by the access review creator, to show to the reviewers.
  - `[DisplayName <String>]`: The access review name. Required on create.
  - `[EndDateTime <DateTime?>]`: The DateTime when the review is scheduled to end. This must be at least one day later than the start date.  Required on create.
  - `[Instances <IMicrosoftGraphAccessReview[]>]`: The collection of access reviews instances past, present and future, if this object is a recurring access review.
  - `[MyDecisions <IMicrosoftGraphAccessReviewDecision[]>]`: The collection of decisions for the caller, if the caller is a reviewer.
  - `[ReviewedEntity <IMicrosoftGraphIdentity>]`: identity
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
    - `[Id <String>]`: Unique identifier for the identity.
  - `[ReviewerType <String>]`: The relationship type of reviewer to the target object, one of self, delegated or entityOwners. Required on create.
  - `[Reviewers <IMicrosoftGraphAccessReviewReviewer[]>]`: The collection of reviewers for an access review, if access review reviewerType is of type delegated.
    - `[Id <String>]`: Read-only.
    - `[DisplayName <String>]`: 
    - `[UserPrincipalName <String>]`: 
  - `[Settings <IMicrosoftGraphAccessReviewSettings>]`: accessReviewSettings
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[AccessRecommendationsEnabled <Boolean?>]`: Indicates whether showing recommendations to reviewers is enabled.
    - `[ActivityDurationInDays <Int32?>]`: The number of days of user activities to show to reviewers.
    - `[AutoApplyReviewResultsEnabled <Boolean?>]`: Indicates whether the auto-apply capability, to automatically change the target object access resource, is enabled.  If not enabled, a user must, after the review completes, apply the access review.
    - `[AutoReviewEnabled <Boolean?>]`: Indicates whether a decision should be set if the reviewer did not supply one. For use when auto-apply is enabled. If you don't want to have a review decision recorded unless the reviewer makes an explicit choice, set it to false.
    - `[AutoReviewSettings <IMicrosoftGraphAutoReviewSettings>]`: autoReviewSettings
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[NotReviewedResult <String>]`: Possible values: Approve, Deny, or Recommendation.  If Recommendation, then accessRecommendationsEnabled in the accessReviewSettings resource should also be set to true. If you want to have the system provide a decision even if the reviewer does not make a choice, set the autoReviewEnabled property in the accessReviewSettings resource to true and include an autoReviewSettings object with the notReviewedResult property. Then, when a review completes, based on the notReviewedResult property, the decision is recorded as either Approve or Deny.
    - `[JustificationRequiredOnApproval <Boolean?>]`: Indicates whether reviewers are required to provide a justification when reviewing access.
    - `[MailNotificationsEnabled <Boolean?>]`: Indicates whether sending mails to reviewers and the review creator is enabled.
    - `[RecurrenceSettings <IMicrosoftGraphAccessReviewRecurrenceSettings>]`: accessReviewRecurrenceSettings
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[DurationInDays <Int32?>]`: The duration in days for recurrence.
      - `[RecurrenceCount <Int32?>]`: The count of recurrences, if the value of recurrenceEndType is occurrences, or 0 otherwise.
      - `[RecurrenceEndType <String>]`: How the recurrence ends. Possible values: never, endBy, occurrences, or recurrenceCount. If it is never, then there is no explicit end of the recurrence series. If it is endBy, then the recurrence ends at a certain date. If it is occurrences, then the series ends after recurrenceCount instances of the review have completed.
      - `[RecurrenceType <String>]`: The recurrence interval. Possible vaules: onetime, weekly, monthly, quarterly, halfyearly or annual.
    - `[RemindersEnabled <Boolean?>]`: Indicates whether sending reminder emails to reviewers is enabled.
  - `[StartDateTime <DateTime?>]`: The DateTime when the review is scheduled to be start.  This could be a date in the future.  Required on create.
  - `[Status <String>]`: This read-only field specifies the status of an accessReview. The typical states include Initializing, NotStarted, Starting,InProgress, Completing, Completed, AutoReviewing, and AutoReviewed.

CREATEDBY <IMicrosoftGraphUserIdentity>: userIdentity
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
  - `[Id <String>]`: Unique identifier for the identity.
  - `[IPAddress <String>]`: Indicates the client IP address used by user performing the activity (audit log only).
  - `[UserPrincipalName <String>]`: The userPrincipalName attribute of the user.

DECISIONS <IMicrosoftGraphAccessReviewDecision[]>: The collection of decisions for this access review.
  - `[Id <String>]`: Read-only.
  - `[AccessRecommendation <String>]`: The feature- generated recommendation shown to the reviewer, one of Approve, Deny or NotAvailable.
  - `[AccessReviewId <String>]`: The feature-generated id of the access review.
  - `[AppliedBy <IMicrosoftGraphUserIdentity>]`: userIdentity
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
    - `[Id <String>]`: Unique identifier for the identity.
    - `[IPAddress <String>]`: Indicates the client IP address used by user performing the activity (audit log only).
    - `[UserPrincipalName <String>]`: The userPrincipalName attribute of the user.
  - `[AppliedDateTime <DateTime?>]`: The date and time when the review decision was applied.
  - `[ApplyResult <String>]`: The outcome of applying the decision, one of NotApplied, Success, Failed, NotFound or NotSupported.
  - `[Justification <String>]`: The reviewer's business justification, if supplied.
  - `[ReviewResult <String>]`: The result of the review, one of NotReviewed, Deny, DontKnow or Approve.
  - `[ReviewedBy <IMicrosoftGraphUserIdentity>]`: userIdentity
  - `[ReviewedDateTime <DateTime?>]`: 

INPUTOBJECT <IIdentityGovernanceIdentity>: Identity Parameter
  - `[AccessPackageAssignmentId <String>]`: key: id of accessPackageAssignment
  - `[AccessPackageAssignmentPolicyId <String>]`: key: id of accessPackageAssignmentPolicy
  - `[AccessPackageAssignmentRequestId <String>]`: key: id of accessPackageAssignmentRequest
  - `[AccessPackageAssignmentResourceRoleId <String>]`: key: id of accessPackageAssignmentResourceRole
  - `[AccessPackageCatalogId <String>]`: key: id of accessPackageCatalog
  - `[AccessPackageId <String>]`: key: id of accessPackage
  - `[AccessPackageResourceEnvironmentId <String>]`: key: id of accessPackageResourceEnvironment
  - `[AccessPackageResourceId <String>]`: key: id of accessPackageResource
  - `[AccessPackageResourceRequestId <String>]`: key: id of accessPackageResourceRequest
  - `[AccessPackageResourceRoleId <String>]`: key: id of accessPackageResourceRole
  - `[AccessPackageResourceRoleScopeId <String>]`: key: id of accessPackageResourceRoleScope
  - `[AccessPackageResourceScopeId <String>]`: key: id of accessPackageResourceScope
  - `[AccessReviewDecisionId <String>]`: key: id of accessReviewDecision
  - `[AccessReviewId <String>]`: key: id of accessReview
  - `[AccessReviewId1 <String>]`: key: id of accessReview
  - `[AccessReviewInstanceId <String>]`: key: id of accessReviewInstance
  - `[AccessReviewReviewerId <String>]`: key: id of accessReviewReviewer
  - `[AccessReviewScheduleDefinitionId <String>]`: key: id of accessReviewScheduleDefinition
  - `[AgreementAcceptanceId <String>]`: key: id of agreementAcceptance
  - `[AgreementFileLocalizationId <String>]`: key: id of agreementFileLocalization
  - `[AgreementFileVersionId <String>]`: key: id of agreementFileVersion
  - `[AgreementId <String>]`: key: id of agreement
  - `[AppConsentRequestId <String>]`: key: id of appConsentRequest
  - `[ApprovalId <String>]`: key: id of approval
  - `[ApprovalStepId <String>]`: key: id of approvalStep
  - `[BusinessFlowTemplateId <String>]`: key: id of businessFlowTemplate
  - `[ConnectedOrganizationId <String>]`: key: id of connectedOrganization
  - `[DirectoryObjectId <String>]`: key: id of directoryObject
  - `[GovernanceResourceId <String>]`: key: id of governanceResource
  - `[GovernanceRoleAssignmentId <String>]`: key: id of governanceRoleAssignment
  - `[GovernanceRoleAssignmentRequestId <String>]`: key: id of governanceRoleAssignmentRequest
  - `[GovernanceRoleDefinitionId <String>]`: key: id of governanceRoleDefinition
  - `[GovernanceRoleSettingId <String>]`: key: id of governanceRoleSetting
  - `[On <String>]`: Usage: on={on}
  - `[PrivilegedAccessId <String>]`: key: id of privilegedAccess
  - `[PrivilegedApprovalId <String>]`: key: id of privilegedApproval
  - `[PrivilegedOperationEventId <String>]`: key: id of privilegedOperationEvent
  - `[PrivilegedRoleAssignmentId <String>]`: key: id of privilegedRoleAssignment
  - `[PrivilegedRoleAssignmentRequestId <String>]`: key: id of privilegedRoleAssignmentRequest
  - `[PrivilegedRoleId <String>]`: key: id of privilegedRole
  - `[ProgramControlId <String>]`: key: id of programControl
  - `[ProgramControlTypeId <String>]`: key: id of programControlType
  - `[ProgramId <String>]`: key: id of program
  - `[UserId <String>]`: key: id of user

INSTANCES <IMicrosoftGraphAccessReview[]>: The collection of access reviews instances past, present and future, if this object is a recurring access review.
  - `[Id <String>]`: Read-only.
  - `[BusinessFlowTemplateId <String>]`: The business flow template identifier. Required on create.  This value is case sensitive.
  - `[CreatedBy <IMicrosoftGraphUserIdentity>]`: userIdentity
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
    - `[Id <String>]`: Unique identifier for the identity.
    - `[IPAddress <String>]`: Indicates the client IP address used by user performing the activity (audit log only).
    - `[UserPrincipalName <String>]`: The userPrincipalName attribute of the user.
  - `[Decisions <IMicrosoftGraphAccessReviewDecision[]>]`: The collection of decisions for this access review.
    - `[Id <String>]`: Read-only.
    - `[AccessRecommendation <String>]`: The feature- generated recommendation shown to the reviewer, one of Approve, Deny or NotAvailable.
    - `[AccessReviewId <String>]`: The feature-generated id of the access review.
    - `[AppliedBy <IMicrosoftGraphUserIdentity>]`: userIdentity
    - `[AppliedDateTime <DateTime?>]`: The date and time when the review decision was applied.
    - `[ApplyResult <String>]`: The outcome of applying the decision, one of NotApplied, Success, Failed, NotFound or NotSupported.
    - `[Justification <String>]`: The reviewer's business justification, if supplied.
    - `[ReviewResult <String>]`: The result of the review, one of NotReviewed, Deny, DontKnow or Approve.
    - `[ReviewedBy <IMicrosoftGraphUserIdentity>]`: userIdentity
    - `[ReviewedDateTime <DateTime?>]`: 
  - `[Description <String>]`: The description provided by the access review creator, to show to the reviewers.
  - `[DisplayName <String>]`: The access review name. Required on create.
  - `[EndDateTime <DateTime?>]`: The DateTime when the review is scheduled to end. This must be at least one day later than the start date.  Required on create.
  - `[Instances <IMicrosoftGraphAccessReview[]>]`: The collection of access reviews instances past, present and future, if this object is a recurring access review.
  - `[MyDecisions <IMicrosoftGraphAccessReviewDecision[]>]`: The collection of decisions for the caller, if the caller is a reviewer.
  - `[ReviewedEntity <IMicrosoftGraphIdentity>]`: identity
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
    - `[Id <String>]`: Unique identifier for the identity.
  - `[ReviewerType <String>]`: The relationship type of reviewer to the target object, one of self, delegated or entityOwners. Required on create.
  - `[Reviewers <IMicrosoftGraphAccessReviewReviewer[]>]`: The collection of reviewers for an access review, if access review reviewerType is of type delegated.
    - `[Id <String>]`: Read-only.
    - `[DisplayName <String>]`: 
    - `[UserPrincipalName <String>]`: 
  - `[Settings <IMicrosoftGraphAccessReviewSettings>]`: accessReviewSettings
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[AccessRecommendationsEnabled <Boolean?>]`: Indicates whether showing recommendations to reviewers is enabled.
    - `[ActivityDurationInDays <Int32?>]`: The number of days of user activities to show to reviewers.
    - `[AutoApplyReviewResultsEnabled <Boolean?>]`: Indicates whether the auto-apply capability, to automatically change the target object access resource, is enabled.  If not enabled, a user must, after the review completes, apply the access review.
    - `[AutoReviewEnabled <Boolean?>]`: Indicates whether a decision should be set if the reviewer did not supply one. For use when auto-apply is enabled. If you don't want to have a review decision recorded unless the reviewer makes an explicit choice, set it to false.
    - `[AutoReviewSettings <IMicrosoftGraphAutoReviewSettings>]`: autoReviewSettings
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[NotReviewedResult <String>]`: Possible values: Approve, Deny, or Recommendation.  If Recommendation, then accessRecommendationsEnabled in the accessReviewSettings resource should also be set to true. If you want to have the system provide a decision even if the reviewer does not make a choice, set the autoReviewEnabled property in the accessReviewSettings resource to true and include an autoReviewSettings object with the notReviewedResult property. Then, when a review completes, based on the notReviewedResult property, the decision is recorded as either Approve or Deny.
    - `[JustificationRequiredOnApproval <Boolean?>]`: Indicates whether reviewers are required to provide a justification when reviewing access.
    - `[MailNotificationsEnabled <Boolean?>]`: Indicates whether sending mails to reviewers and the review creator is enabled.
    - `[RecurrenceSettings <IMicrosoftGraphAccessReviewRecurrenceSettings>]`: accessReviewRecurrenceSettings
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[DurationInDays <Int32?>]`: The duration in days for recurrence.
      - `[RecurrenceCount <Int32?>]`: The count of recurrences, if the value of recurrenceEndType is occurrences, or 0 otherwise.
      - `[RecurrenceEndType <String>]`: How the recurrence ends. Possible values: never, endBy, occurrences, or recurrenceCount. If it is never, then there is no explicit end of the recurrence series. If it is endBy, then the recurrence ends at a certain date. If it is occurrences, then the series ends after recurrenceCount instances of the review have completed.
      - `[RecurrenceType <String>]`: The recurrence interval. Possible vaules: onetime, weekly, monthly, quarterly, halfyearly or annual.
    - `[RemindersEnabled <Boolean?>]`: Indicates whether sending reminder emails to reviewers is enabled.
  - `[StartDateTime <DateTime?>]`: The DateTime when the review is scheduled to be start.  This could be a date in the future.  Required on create.
  - `[Status <String>]`: This read-only field specifies the status of an accessReview. The typical states include Initializing, NotStarted, Starting,InProgress, Completing, Completed, AutoReviewing, and AutoReviewed.

MYDECISIONS <IMicrosoftGraphAccessReviewDecision[]>: The collection of decisions for the caller, if the caller is a reviewer.
  - `[Id <String>]`: Read-only.
  - `[AccessRecommendation <String>]`: The feature- generated recommendation shown to the reviewer, one of Approve, Deny or NotAvailable.
  - `[AccessReviewId <String>]`: The feature-generated id of the access review.
  - `[AppliedBy <IMicrosoftGraphUserIdentity>]`: userIdentity
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
    - `[Id <String>]`: Unique identifier for the identity.
    - `[IPAddress <String>]`: Indicates the client IP address used by user performing the activity (audit log only).
    - `[UserPrincipalName <String>]`: The userPrincipalName attribute of the user.
  - `[AppliedDateTime <DateTime?>]`: The date and time when the review decision was applied.
  - `[ApplyResult <String>]`: The outcome of applying the decision, one of NotApplied, Success, Failed, NotFound or NotSupported.
  - `[Justification <String>]`: The reviewer's business justification, if supplied.
  - `[ReviewResult <String>]`: The result of the review, one of NotReviewed, Deny, DontKnow or Approve.
  - `[ReviewedBy <IMicrosoftGraphUserIdentity>]`: userIdentity
  - `[ReviewedDateTime <DateTime?>]`: 

REVIEWEDENTITY <IMicrosoftGraphIdentity>: identity
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[DisplayName <String>]`: The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
  - `[Id <String>]`: Unique identifier for the identity.

REVIEWERS <IMicrosoftGraphAccessReviewReviewer[]>: The collection of reviewers for an access review, if access review reviewerType is of type delegated.
  - `[Id <String>]`: Read-only.
  - `[DisplayName <String>]`: 
  - `[UserPrincipalName <String>]`: 

SETTINGS <IMicrosoftGraphAccessReviewSettings>: accessReviewSettings
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[AccessRecommendationsEnabled <Boolean?>]`: Indicates whether showing recommendations to reviewers is enabled.
  - `[ActivityDurationInDays <Int32?>]`: The number of days of user activities to show to reviewers.
  - `[AutoApplyReviewResultsEnabled <Boolean?>]`: Indicates whether the auto-apply capability, to automatically change the target object access resource, is enabled.  If not enabled, a user must, after the review completes, apply the access review.
  - `[AutoReviewEnabled <Boolean?>]`: Indicates whether a decision should be set if the reviewer did not supply one. For use when auto-apply is enabled. If you don't want to have a review decision recorded unless the reviewer makes an explicit choice, set it to false.
  - `[AutoReviewSettings <IMicrosoftGraphAutoReviewSettings>]`: autoReviewSettings
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[NotReviewedResult <String>]`: Possible values: Approve, Deny, or Recommendation.  If Recommendation, then accessRecommendationsEnabled in the accessReviewSettings resource should also be set to true. If you want to have the system provide a decision even if the reviewer does not make a choice, set the autoReviewEnabled property in the accessReviewSettings resource to true and include an autoReviewSettings object with the notReviewedResult property. Then, when a review completes, based on the notReviewedResult property, the decision is recorded as either Approve or Deny.
  - `[JustificationRequiredOnApproval <Boolean?>]`: Indicates whether reviewers are required to provide a justification when reviewing access.
  - `[MailNotificationsEnabled <Boolean?>]`: Indicates whether sending mails to reviewers and the review creator is enabled.
  - `[RecurrenceSettings <IMicrosoftGraphAccessReviewRecurrenceSettings>]`: accessReviewRecurrenceSettings
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DurationInDays <Int32?>]`: The duration in days for recurrence.
    - `[RecurrenceCount <Int32?>]`: The count of recurrences, if the value of recurrenceEndType is occurrences, or 0 otherwise.
    - `[RecurrenceEndType <String>]`: How the recurrence ends. Possible values: never, endBy, occurrences, or recurrenceCount. If it is never, then there is no explicit end of the recurrence series. If it is endBy, then the recurrence ends at a certain date. If it is occurrences, then the series ends after recurrenceCount instances of the review have completed.
    - `[RecurrenceType <String>]`: The recurrence interval. Possible vaules: onetime, weekly, monthly, quarterly, halfyearly or annual.
  - `[RemindersEnabled <Boolean?>]`: Indicates whether sending reminder emails to reviewers is enabled.

## RELATED LINKS

## RELATED LINKS