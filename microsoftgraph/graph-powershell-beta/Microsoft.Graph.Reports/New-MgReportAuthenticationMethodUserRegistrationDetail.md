---
external help file: Microsoft.Graph.Reports-help.xml
Module Name: Microsoft.Graph.Reports
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.reports/new-mgreportauthenticationmethoduserregistrationdetail
schema: 2.0.0
---

# New-MgReportAuthenticationMethodUserRegistrationDetail

## SYNOPSIS
Represents the state of a user's authentication methods, including which methods are registered and which features the user is registered and capable of (such as multi-factor authentication, self-service password reset, and passwordless authentication).

## SYNTAX

### CreateExpanded (Default)
```
New-MgReportAuthenticationMethodUserRegistrationDetail [-AdditionalProperties <Hashtable>] [-Id <String>]
 [-IsMfaCapable] [-IsMfaRegistered] [-IsPasswordlessCapable] [-IsSsprCapable] [-IsSsprEnabled]
 [-IsSsprRegistered] [-MethodsRegistered <String[]>] [-UserDisplayName <String>] [-UserPrincipalName <String>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgReportAuthenticationMethodUserRegistrationDetail -BodyParameter <IMicrosoftGraphUserRegistrationDetails>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Represents the state of a user's authentication methods, including which methods are registered and which features the user is registered and capable of (such as multi-factor authentication, self-service password reset, and passwordless authentication).

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
userRegistrationDetails
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphUserRegistrationDetails
Parameter Sets: Create
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
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsMfaCapable
Whether the user has registered a strong authentication method for multi-factor authentication.
The method must be allowed by the authentication methods policy.
Supports $filter (eq).

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsMfaRegistered
Whether the user has registered a strong authentication method for multi-factor authentication.
The method may not necessarily be allowed by the authentication methods policy.
Supports $filter (eq).

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsPasswordlessCapable
Whether the user has registered a passwordless strong authentication method (including FIDO2, Windows Hello for Business, and Microsoft Authenticator (Passwordless)) that is allowed by the authentication methods policy.
Supports $filter (eq).

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsSsprCapable
Whether the user has registered the required number of authentication methods for self-service password reset and the user is allowed to perform self-service password reset by policy.
Supports $filter (eq).

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsSsprEnabled
Whether the user is allowed to perform self-service password reset by policy.
The user may not necessarily have registered the required number of authentication methods for self-service password reset.
Supports $filter (eq).

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsSsprRegistered
Whether the user has registered the required number of authentication methods for self-service password reset.
The user may not necessarily be allowed to perform self-service password reset by policy.
Supports $filter (eq).

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MethodsRegistered
Collection of authentication methods registered, such as mobilePhone, email, fido2.
Supports $filter (any with eq).

```yaml
Type: String[]
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserDisplayName
The user display name, such as Adele Vance.
Supports $filter (eq, startsWith) and $orderBy.

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

### -UserPrincipalName
The user principal name, such as AdeleV@contoso.com.
Supports $filter (eq, startsWith) and $orderBy.

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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserRegistrationDetails
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserRegistrationDetails
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphUserRegistrationDetails>: userRegistrationDetails
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[IsMfaCapable <Boolean?>]`: Whether the user has registered a strong authentication method for multi-factor authentication. The method must be allowed by the authentication methods policy. Supports $filter (eq).
  - `[IsMfaRegistered <Boolean?>]`: Whether the user has registered a strong authentication method for multi-factor authentication. The method may not necessarily be allowed by the authentication methods policy.  Supports $filter (eq).
  - `[IsPasswordlessCapable <Boolean?>]`: Whether the user has registered a passwordless strong authentication method (including FIDO2, Windows Hello for Business, and Microsoft Authenticator (Passwordless)) that is allowed by the authentication methods policy. Supports $filter (eq).
  - `[IsSsprCapable <Boolean?>]`: Whether the user has registered the required number of authentication methods for self-service password reset and the user is allowed to perform self-service password reset by policy. Supports $filter (eq).
  - `[IsSsprEnabled <Boolean?>]`: Whether the user is allowed to perform self-service password reset by policy. The user may not necessarily have registered the required number of authentication methods for self-service password reset. Supports $filter (eq).
  - `[IsSsprRegistered <Boolean?>]`: Whether the user has registered the required number of authentication methods for self-service password reset. The user may not necessarily be allowed to perform self-service password reset by policy. Supports $filter (eq).
  - `[MethodsRegistered <String[]>]`: Collection of authentication methods registered, such as mobilePhone, email, fido2. Supports $filter (any with eq).
  - `[UserDisplayName <String>]`: The user display name, such as Adele Vance. Supports $filter (eq, startsWith) and $orderBy.
  - `[UserPrincipalName <String>]`: The user principal name, such as AdeleV@contoso.com. Supports $filter (eq, startsWith) and $orderBy.

## RELATED LINKS