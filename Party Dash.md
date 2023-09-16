 **Current Party**
 **[[NPC Database|Edit NPCs]]**
> [!cards|dataview 5]
>```dataview
TABLE WITHOUT ID
>	link(file.path, name) AS "Name",
>	embed(Art) AS "Art",
>	
>	race AS "Race",
>	location AS "Location"
WHERE contains(NoteIcon, "Character") AND contains(WhichParty, "Party 1") AND !contains(Condition, "Dead")
>SORT file.name asc
>```

# **Session Notes**
> [!cards|dataview 3]
>```dataview
TABLE WITHOUT ID
>	link(file.path, name) AS "Name",
>	QuickNotes AS "QuickNotes"
WHERE contains(Note_Type, "Session Note")
>SORT file.name desc LIMIT 9
>```

# **Quests**
#### **[[Quest Database| New Quest]]**
> [!cards|dataview 3]
>```dataview
TABLE WITHOUT ID
>	link(file.path, name) AS "Name",
>	QuickNotes AS "QuickNotes"
WHERE contains(NoteIcon, "Quest") AND contains(WhichParty, "Party 1") AND contains(status, "Active")
>SORT file.name asc
>```