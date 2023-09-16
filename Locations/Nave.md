---
NoteIcon: Settlement
Type: Small Town
Defences: None
---
# **`=this.file.name`**

## Overview 

Nave is a quaint, weathered town located on the Rustic Isle, one of the eastern islands of Mystra. Once a prosperous and thriving community, Nave was renowned for its exquisite textiles and expert weavers, who crafted luxurious fabrics sought after across the realm. However, over time, as trade routes shifted and competition from other regions increased, Nave's fortunes waned, leaving the town a shadow of its former glory.

Now, Nave is primarily home to elderly villagers who have spent their entire lives in the town, as well as those too poor to leave or seek opportunities elsewhere. The streets are lined with aged, crumbling buildings, their facades hinting at the opulence that once adorned the town. Many of the once-thriving weaving workshops now stand empty, their looms and spinning wheels gathering dust as a somber reminder of the past.

Despite its decline, the residents of Nave hold tightly to their sense of community and pride. The town's modest market still offers a selection of locally produced goods, from hand-knitted garments to simple pottery and rustic wooden carvings. The people of Nave have learned to rely on one another, forming strong bonds that help them endure the hardships of their current circumstances.

Drifters, adventurers, and those seeking a fresh start occasionally find their way to Nave, drawn by the town's quiet, unassuming charm. While Nave may no longer be the bustling center of commerce it once was, its resilient spirit and the warmth of its inhabitants ensure that it remains a place where hope and camaraderie can still be found.


## Notable Locations

TBD


## Notable Characters

> ###### Notable Characters
> [[NPC Database|Add New NPC]]
> ```dataview
table Art, Pronouns, Party1Standing AS "Party 1 Standing", join(Occupation, ", ") AS "Occupation(s)", join(link(AssociatedGroup), ", ") AS "Associated Group(s)", join(link(AssociatedReligion), ", ") AS "Associated Religion(s)"
WHERE Location = this.file.name AND contains(NoteIcon, "Character") AND !contains(Condition, "Dead")
SORT file.name ASC





[Nave Map](https://www.legendkeeper.com/app/clgeu1oyz3s8l08985sqf2z46/clgesxudc009p033cbdu5btsj/)