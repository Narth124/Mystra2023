
> [!infobox]
> # `=this.file.name`
> ![[PlaceholderImage.png|cover hm-sm]]
> ###### Info
>  |
> ---|---|
> **Alias** | `=this.alias` |
> **Type** | `=this.type` |
> **Region** | `=link(this.Locale)` |
> ###### Politics
>  |
> ---|---|
> 
> **Leaders** | TBD |
> **Defenses** | `=this.defences` |
> 
> ###### Groups
> [[Group Database|Add New Group]]
> 

# **`=this.file.name`**

## Overview 

TBD


## Notable Locations

TBD


## Notable Characters

> ###### Notable Characters
> [[NPC Database|Add New NPC]]
> ```dataview
table Art, Pronouns, Party1Standing AS "Party 1 Standing", join(Occupation, ", ") AS "Occupation(s)", join(link(AssociatedGroup), ", ") AS "Associated Group(s)", join(link(AssociatedReligion), ", ") AS "Associated Religion(s)"
WHERE Location = this.file.name AND contains(NoteIcon, "Character") AND !contains(Condition, "Dead")
SORT file.name ASC

