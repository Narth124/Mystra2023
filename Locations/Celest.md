---
NoteIcon: Settlement
Type: Large City
Defences: Formidable
Locale: "[[[Locations/The Emerald Forest.md|The Emerald Forest]]"
---

> [!infobox]
> # `=this.file.name`
> **Pronounced:**  "`=this.Pronounced`"
> ![[Pasted image 20230916093323.png|cover hm-sm]]
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
> ```dataview 
table join(Type, ", ") AS Type
WHERE econtains(Location, this.file.name) AND contains(NoteIcon, "Group")
SORT Type ASC



# **`=this.file.name`**

## Overview 

Celest is a city unlike any other, situated at the edge of the Origin, a vast whirlpool imbued with pure mana. The city'

s skilled mages harness the power of the mana-infused waters to create powerful magical artifacts and potions, which are highly sought after throughout Mystra. The city's trade thrives on the unique resources it possesses, making it a hub for those seeking to study and harness the power of mana.

The city itself is a sight to behold, with towering spires and grand plazas that gleam in the sunlight. Its streets are lined with beautiful gardens and ornate fountains, creating a serene and tranquil atmosphere that belies the bustling energy of its markets and trade centers.

Celest is ruled by a council of mages, with the High Mage serving as the head of government. The council works tirelessly to maintain order and ensure the safety of all citizens. Despite their efforts, crime remains an issue in certain parts of the city, and tensions can arise between different races and factions.

The population of Celest is estimated to be around 500,000, making it the largest city on Mystra. The city is home to many skilled artisans, traders, and mages who are drawn to its promise of wealth and opportunity. The districts are named after the Gods of the world, with the Radiant Enclave housing the Nobles and High Mages, Moradin's Heart being a district where the finest forges and smithies gather to sell and set up shop, The Melora Preserve being a large and beautiful park that is also home to many endangered animals and beasts, The Iounic Scriptorium's being where mages, scholars, and others live, study and sell, and The Avandrian Markets being the general markets and trade center of the city. The docks, dockyards, and sky yards are located in Sehanine's Port.


## Notable Locations

TBD


## Notable Characters

> ###### Notable Characters
> [[NPC Database|Add New NPC]]
> ```dataview
table Art, Pronouns, Party1Standing AS "Party 1 Standing", join(Occupation, ", ") AS "Occupation(s)", join(link(AssociatedGroup), ", ") AS "Associated Group(s)", join(link(AssociatedReligion), ", ") AS "Associated Religion(s)"
WHERE Location = this.file.name AND contains(NoteIcon, "Character") AND !contains(Condition, "Dead")
SORT file.name ASC

