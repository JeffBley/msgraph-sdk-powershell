---
external help file:
Module Name: Microsoft.Graph.Sites
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.sites/new-mgsitetermstoresetrelation
schema: 2.0.0
---

# New-MgSiteTermStoreSetRelation

## SYNOPSIS
Indicates which terms have been pinned or reused directly under the set.

## SYNTAX

### CreateExpanded (Default)
```
New-MgSiteTermStoreSetRelation -SetId <String> -SiteId <String> [-AdditionalProperties <Hashtable>]
 [-FromTerm <IMicrosoftGraphTermStoreTerm1>] [-Id <String>] [-Relationship <String>]
 [-Set <IMicrosoftGraphTermStoreSet1>] [-ToTerm <IMicrosoftGraphTermStoreTerm1>] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### Create
```
New-MgSiteTermStoreSetRelation -SetId <String> -SiteId <String>
 -BodyParameter <IMicrosoftGraphTermStoreRelation1> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create1
```
New-MgSiteTermStoreSetRelation -SetId <String> -SiteId <String> -StoreId <String>
 -BodyParameter <IMicrosoftGraphTermStoreRelation1> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateExpanded1
```
New-MgSiteTermStoreSetRelation -SetId <String> -SiteId <String> -StoreId <String>
 [-AdditionalProperties <Hashtable>] [-FromTerm <IMicrosoftGraphTermStoreTerm1>] [-Id <String>]
 [-Relationship <String>] [-Set <IMicrosoftGraphTermStoreSet1>] [-ToTerm <IMicrosoftGraphTermStoreTerm1>]
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentity
```
New-MgSiteTermStoreSetRelation -InputObject <ISitesIdentity>
 -BodyParameter <IMicrosoftGraphTermStoreRelation1> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentity1
```
New-MgSiteTermStoreSetRelation -InputObject <ISitesIdentity>
 -BodyParameter <IMicrosoftGraphTermStoreRelation1> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentityExpanded
```
New-MgSiteTermStoreSetRelation -InputObject <ISitesIdentity> [-AdditionalProperties <Hashtable>]
 [-FromTerm <IMicrosoftGraphTermStoreTerm1>] [-Id <String>] [-Relationship <String>]
 [-Set <IMicrosoftGraphTermStoreSet1>] [-ToTerm <IMicrosoftGraphTermStoreTerm1>] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### CreateViaIdentityExpanded1
```
New-MgSiteTermStoreSetRelation -InputObject <ISitesIdentity> [-AdditionalProperties <Hashtable>]
 [-FromTerm <IMicrosoftGraphTermStoreTerm1>] [-Id <String>] [-Relationship <String>]
 [-Set <IMicrosoftGraphTermStoreSet1>] [-ToTerm <IMicrosoftGraphTermStoreTerm1>] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

## DESCRIPTION
Indicates which terms have been pinned or reused directly under the set.

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: System.Collections.Hashtable
Parameter Sets: CreateExpanded, CreateExpanded1, CreateViaIdentityExpanded, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
relation
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphTermStoreRelation1
Parameter Sets: Create, Create1, CreateViaIdentity, CreateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -FromTerm
term
To construct, please use Get-Help -Online and see NOTES section for FROMTERM properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphTermStoreTerm1
Parameter Sets: CreateExpanded, CreateExpanded1, CreateViaIdentityExpanded, CreateViaIdentityExpanded1
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
Type: System.String
Parameter Sets: CreateExpanded, CreateExpanded1, CreateViaIdentityExpanded, CreateViaIdentityExpanded1
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
Type: Microsoft.Graph.PowerShell.Models.ISitesIdentity
Parameter Sets: CreateViaIdentity, CreateViaIdentity1, CreateViaIdentityExpanded, CreateViaIdentityExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Relationship
.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateExpanded1, CreateViaIdentityExpanded, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Set
set
To construct, please use Get-Help -Online and see NOTES section for SET properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphTermStoreSet1
Parameter Sets: CreateExpanded, CreateExpanded1, CreateViaIdentityExpanded, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SetId
key: id of set

```yaml
Type: System.String
Parameter Sets: Create, Create1, CreateExpanded, CreateExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SiteId
key: id of site

```yaml
Type: System.String
Parameter Sets: Create, Create1, CreateExpanded, CreateExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -StoreId
key: id of store

```yaml
Type: System.String
Parameter Sets: Create1, CreateExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ToTerm
term
To construct, please use Get-Help -Online and see NOTES section for TOTERM properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphTermStoreTerm1
Parameter Sets: CreateExpanded, CreateExpanded1, CreateViaIdentityExpanded, CreateViaIdentityExpanded1
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
Type: System.Management.Automation.SwitchParameter
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
Type: System.Management.Automation.SwitchParameter
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphTermStoreRelation1

### Microsoft.Graph.PowerShell.Models.ISitesIdentity

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphTermStoreRelation1

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphTermStoreRelation1>: relation
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[FromTerm <IMicrosoftGraphTermStoreTerm1>]`: term
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[Children <IMicrosoftGraphTermStoreTerm1[]>]`: Children of current term.
    - `[CreatedDateTime <DateTime?>]`: Date and time of term creation. Read-only.
    - `[Descriptions <IMicrosoftGraphTermStoreLocalizedDescription[]>]`: Description about term that is dependent on the languageTag.
      - `[Description <String>]`: The description in the localized language.
      - `[LanguageTag <String>]`: The language tag for the label.
    - `[Labels <IMicrosoftGraphTermStoreLocalizedLabel[]>]`: Label metadata for a term.
      - `[IsDefault <Boolean?>]`: Indicates whether the label is the default label.
      - `[LanguageTag <String>]`: The language tag for the label.
      - `[Name <String>]`: The name of the label.
    - `[LastModifiedDateTime <DateTime?>]`: Last date and time of term modification. Read-only.
    - `[Properties <IMicrosoftGraphKeyValue[]>]`: Collection of properties on the term.
      - `[Key <String>]`: Key.
      - `[Value <String>]`: Value.
    - `[Relations <IMicrosoftGraphTermStoreRelation1[]>]`: To indicate which terms are related to the current term as either pinned or reused.
    - `[Set <IMicrosoftGraphTermStoreSet1>]`: set
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[Children <IMicrosoftGraphTermStoreTerm1[]>]`: Children terms of set in term [store].
      - `[CreatedDateTime <DateTime?>]`: Date and time of set creation. Read-only.
      - `[Description <String>]`: Description giving details on the term usage.
      - `[LocalizedNames <IMicrosoftGraphTermStoreLocalizedName[]>]`: Name of the set for each languageTag.
        - `[LanguageTag <String>]`: The language tag for the label.
        - `[Name <String>]`: The name in the localized language.
      - `[ParentGroup <IMicrosoftGraphTermStoreGroup1>]`: group
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
        - `[CreatedDateTime <DateTime?>]`: Date and time of group creation. Read-only.
        - `[Description <String>]`: Description giving details on the term usage.
        - `[DisplayName <String>]`: Name of group.
        - `[ParentSiteId <String>]`: Id of the parent site of this group.
        - `[Scope <String>]`: 
        - `[Sets <IMicrosoftGraphTermStoreSet1[]>]`: All sets under the group in a term [store].
      - `[Properties <IMicrosoftGraphKeyValue[]>]`: Custom properties for the set.
      - `[Relations <IMicrosoftGraphTermStoreRelation1[]>]`: Indicates which terms have been pinned or reused directly under the set.
      - `[Terms <IMicrosoftGraphTermStoreTerm1[]>]`: All the terms under the set.
  - `[Relationship <String>]`: 
  - `[Set <IMicrosoftGraphTermStoreSet1>]`: set
  - `[ToTerm <IMicrosoftGraphTermStoreTerm1>]`: term

FROMTERM <IMicrosoftGraphTermStoreTerm1>: term
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[Children <IMicrosoftGraphTermStoreTerm1[]>]`: Children of current term.
  - `[CreatedDateTime <DateTime?>]`: Date and time of term creation. Read-only.
  - `[Descriptions <IMicrosoftGraphTermStoreLocalizedDescription[]>]`: Description about term that is dependent on the languageTag.
    - `[Description <String>]`: The description in the localized language.
    - `[LanguageTag <String>]`: The language tag for the label.
  - `[Labels <IMicrosoftGraphTermStoreLocalizedLabel[]>]`: Label metadata for a term.
    - `[IsDefault <Boolean?>]`: Indicates whether the label is the default label.
    - `[LanguageTag <String>]`: The language tag for the label.
    - `[Name <String>]`: The name of the label.
  - `[LastModifiedDateTime <DateTime?>]`: Last date and time of term modification. Read-only.
  - `[Properties <IMicrosoftGraphKeyValue[]>]`: Collection of properties on the term.
    - `[Key <String>]`: Key.
    - `[Value <String>]`: Value.
  - `[Relations <IMicrosoftGraphTermStoreRelation1[]>]`: To indicate which terms are related to the current term as either pinned or reused.
    - `[Id <String>]`: Read-only.
    - `[FromTerm <IMicrosoftGraphTermStoreTerm1>]`: term
    - `[Relationship <String>]`: 
    - `[Set <IMicrosoftGraphTermStoreSet1>]`: set
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[Children <IMicrosoftGraphTermStoreTerm1[]>]`: Children terms of set in term [store].
      - `[CreatedDateTime <DateTime?>]`: Date and time of set creation. Read-only.
      - `[Description <String>]`: Description giving details on the term usage.
      - `[LocalizedNames <IMicrosoftGraphTermStoreLocalizedName[]>]`: Name of the set for each languageTag.
        - `[LanguageTag <String>]`: The language tag for the label.
        - `[Name <String>]`: The name in the localized language.
      - `[ParentGroup <IMicrosoftGraphTermStoreGroup1>]`: group
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
        - `[CreatedDateTime <DateTime?>]`: Date and time of group creation. Read-only.
        - `[Description <String>]`: Description giving details on the term usage.
        - `[DisplayName <String>]`: Name of group.
        - `[ParentSiteId <String>]`: Id of the parent site of this group.
        - `[Scope <String>]`: 
        - `[Sets <IMicrosoftGraphTermStoreSet1[]>]`: All sets under the group in a term [store].
      - `[Properties <IMicrosoftGraphKeyValue[]>]`: Custom properties for the set.
      - `[Relations <IMicrosoftGraphTermStoreRelation1[]>]`: Indicates which terms have been pinned or reused directly under the set.
      - `[Terms <IMicrosoftGraphTermStoreTerm1[]>]`: All the terms under the set.
    - `[ToTerm <IMicrosoftGraphTermStoreTerm1>]`: term
  - `[Set <IMicrosoftGraphTermStoreSet1>]`: set

INPUTOBJECT <ISitesIdentity>: Identity Parameter
  - `[ColumnDefinitionId <String>]`: key: id of columnDefinition
  - `[ColumnLinkId <String>]`: key: id of columnLink
  - `[ContentTypeId <String>]`: key: id of contentType
  - `[DriveId <String>]`: key: id of drive
  - `[EndDateTime <String>]`: Usage: endDateTime={endDateTime}
  - `[GroupId <String>]`: key: id of group
  - `[IncludePersonalNotebooks <Boolean?>]`: Usage: includePersonalNotebooks={includePersonalNotebooks}
  - `[Interval <String>]`: Usage: interval={interval}
  - `[ListId <String>]`: key: id of list
  - `[ListId1 <String>]`: Usage: listId={listId}
  - `[ListItemId <String>]`: key: id of listItem
  - `[ListItemVersionId <String>]`: key: id of listItemVersion
  - `[NotebookId <String>]`: key: id of notebook
  - `[OnenotePageId <String>]`: key: id of onenotePage
  - `[OnenoteSectionId <String>]`: key: id of onenoteSection
  - `[Path <String>]`: Usage: path={path}
  - `[PermissionId <String>]`: key: id of permission
  - `[RelationId <String>]`: key: id of relation
  - `[RichLongRunningOperationId <String>]`: key: id of richLongRunningOperation
  - `[SetId <String>]`: key: id of set
  - `[SetId1 <String>]`: key: id of set
  - `[SiteId <String>]`: key: id of site
  - `[SiteId1 <String>]`: key: id of site
  - `[SitePageId <String>]`: key: id of sitePage
  - `[StartDateTime <String>]`: Usage: startDateTime={startDateTime}
  - `[StoreId <String>]`: key: id of store
  - `[SubscriptionId <String>]`: key: id of subscription
  - `[TermId <String>]`: key: id of term
  - `[TermId1 <String>]`: key: id of term
  - `[UserId <String>]`: key: id of user

SET <IMicrosoftGraphTermStoreSet1>: set
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[Children <IMicrosoftGraphTermStoreTerm1[]>]`: Children terms of set in term [store].
    - `[Id <String>]`: Read-only.
    - `[Children <IMicrosoftGraphTermStoreTerm1[]>]`: Children of current term.
    - `[CreatedDateTime <DateTime?>]`: Date and time of term creation. Read-only.
    - `[Descriptions <IMicrosoftGraphTermStoreLocalizedDescription[]>]`: Description about term that is dependent on the languageTag.
      - `[Description <String>]`: The description in the localized language.
      - `[LanguageTag <String>]`: The language tag for the label.
    - `[Labels <IMicrosoftGraphTermStoreLocalizedLabel[]>]`: Label metadata for a term.
      - `[IsDefault <Boolean?>]`: Indicates whether the label is the default label.
      - `[LanguageTag <String>]`: The language tag for the label.
      - `[Name <String>]`: The name of the label.
    - `[LastModifiedDateTime <DateTime?>]`: Last date and time of term modification. Read-only.
    - `[Properties <IMicrosoftGraphKeyValue[]>]`: Collection of properties on the term.
      - `[Key <String>]`: Key.
      - `[Value <String>]`: Value.
    - `[Relations <IMicrosoftGraphTermStoreRelation1[]>]`: To indicate which terms are related to the current term as either pinned or reused.
      - `[Id <String>]`: Read-only.
      - `[FromTerm <IMicrosoftGraphTermStoreTerm1>]`: term
      - `[Relationship <String>]`: 
      - `[Set <IMicrosoftGraphTermStoreSet1>]`: set
      - `[ToTerm <IMicrosoftGraphTermStoreTerm1>]`: term
    - `[Set <IMicrosoftGraphTermStoreSet1>]`: set
  - `[CreatedDateTime <DateTime?>]`: Date and time of set creation. Read-only.
  - `[Description <String>]`: Description giving details on the term usage.
  - `[LocalizedNames <IMicrosoftGraphTermStoreLocalizedName[]>]`: Name of the set for each languageTag.
    - `[LanguageTag <String>]`: The language tag for the label.
    - `[Name <String>]`: The name in the localized language.
  - `[ParentGroup <IMicrosoftGraphTermStoreGroup1>]`: group
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: Read-only.
    - `[CreatedDateTime <DateTime?>]`: Date and time of group creation. Read-only.
    - `[Description <String>]`: Description giving details on the term usage.
    - `[DisplayName <String>]`: Name of group.
    - `[ParentSiteId <String>]`: Id of the parent site of this group.
    - `[Scope <String>]`: 
    - `[Sets <IMicrosoftGraphTermStoreSet1[]>]`: All sets under the group in a term [store].
  - `[Properties <IMicrosoftGraphKeyValue[]>]`: Custom properties for the set.
  - `[Relations <IMicrosoftGraphTermStoreRelation1[]>]`: Indicates which terms have been pinned or reused directly under the set.
  - `[Terms <IMicrosoftGraphTermStoreTerm1[]>]`: All the terms under the set.

TOTERM <IMicrosoftGraphTermStoreTerm1>: term
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: Read-only.
  - `[Children <IMicrosoftGraphTermStoreTerm1[]>]`: Children of current term.
  - `[CreatedDateTime <DateTime?>]`: Date and time of term creation. Read-only.
  - `[Descriptions <IMicrosoftGraphTermStoreLocalizedDescription[]>]`: Description about term that is dependent on the languageTag.
    - `[Description <String>]`: The description in the localized language.
    - `[LanguageTag <String>]`: The language tag for the label.
  - `[Labels <IMicrosoftGraphTermStoreLocalizedLabel[]>]`: Label metadata for a term.
    - `[IsDefault <Boolean?>]`: Indicates whether the label is the default label.
    - `[LanguageTag <String>]`: The language tag for the label.
    - `[Name <String>]`: The name of the label.
  - `[LastModifiedDateTime <DateTime?>]`: Last date and time of term modification. Read-only.
  - `[Properties <IMicrosoftGraphKeyValue[]>]`: Collection of properties on the term.
    - `[Key <String>]`: Key.
    - `[Value <String>]`: Value.
  - `[Relations <IMicrosoftGraphTermStoreRelation1[]>]`: To indicate which terms are related to the current term as either pinned or reused.
    - `[Id <String>]`: Read-only.
    - `[FromTerm <IMicrosoftGraphTermStoreTerm1>]`: term
    - `[Relationship <String>]`: 
    - `[Set <IMicrosoftGraphTermStoreSet1>]`: set
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: Read-only.
      - `[Children <IMicrosoftGraphTermStoreTerm1[]>]`: Children terms of set in term [store].
      - `[CreatedDateTime <DateTime?>]`: Date and time of set creation. Read-only.
      - `[Description <String>]`: Description giving details on the term usage.
      - `[LocalizedNames <IMicrosoftGraphTermStoreLocalizedName[]>]`: Name of the set for each languageTag.
        - `[LanguageTag <String>]`: The language tag for the label.
        - `[Name <String>]`: The name in the localized language.
      - `[ParentGroup <IMicrosoftGraphTermStoreGroup1>]`: group
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: Read-only.
        - `[CreatedDateTime <DateTime?>]`: Date and time of group creation. Read-only.
        - `[Description <String>]`: Description giving details on the term usage.
        - `[DisplayName <String>]`: Name of group.
        - `[ParentSiteId <String>]`: Id of the parent site of this group.
        - `[Scope <String>]`: 
        - `[Sets <IMicrosoftGraphTermStoreSet1[]>]`: All sets under the group in a term [store].
      - `[Properties <IMicrosoftGraphKeyValue[]>]`: Custom properties for the set.
      - `[Relations <IMicrosoftGraphTermStoreRelation1[]>]`: Indicates which terms have been pinned or reused directly under the set.
      - `[Terms <IMicrosoftGraphTermStoreTerm1[]>]`: All the terms under the set.
    - `[ToTerm <IMicrosoftGraphTermStoreTerm1>]`: term
  - `[Set <IMicrosoftGraphTermStoreSet1>]`: set

## RELATED LINKS

