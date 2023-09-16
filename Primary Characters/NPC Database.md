---

database-plugin: basic

---

```yaml:dbfolder
name: new database
description: new description
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    accessor: __file__
    position: 1
    isSorted: true
    isSortedDesc: false
    width: 201
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
  __created__:
    key: __created__
    id: __created__
    input: calendar_time
    label: Created
    accessorKey: __created__
    isMetadata: true
    isDragDisabled: false
    skipPersist: false
    csvCandidate: true
    accessor: __created__
    position: 25
    width: 150
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
  __modified__:
    key: __modified__
    id: __modified__
    input: calendar_time
    label: Modified
    accessorKey: __modified__
    isMetadata: true
    isDragDisabled: false
    skipPersist: false
    csvCandidate: true
    accessor: __modified__
    position: 26
    width: 150
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
  Alignment:
    input: select
    accessor: Alignment
    key: Alignment
    label: Alignment
    position: 11
    skipPersist: false
    accessorKey: Alignment
    width: -53
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Neutral", value: "Neutral", color: "hsl(99, 95%, 90%)"}
      - { label: "TN", value: "TN", color: "hsl(240, 95%, 90%)"}
      - { label: "CN", value: "CN", color: "hsl(177, 95%, 90%)"}
      - { label: "NG", value: "NG", color: "hsl(152, 95%, 90%)"}
      - { label: "LG", value: "LG", color: "hsl(287, 95%, 90%)"}
      - { label: "CG", value: "CG", color: "hsl(174, 95%, 90%)"}
      - { label: "Unknown", value: "Unknown", color: "hsl(287, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
      option_source: manual
  Race:
    input: select
    accessor: Race
    key: Race
    label: Race
    position: 10
    skipPersist: false
    accessorKey: Race
    width: 128
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Human", value: "Human", color: "hsl(13, 95%, 90%)"}
      - { label: "Wood Elf", value: "Wood Elf", color: "hsl(16, 95%, 90%)"}
      - { label: "Vampire", value: "Vampire", color: "hsl(255, 95%, 90%)"}
      - { label: "Halfing", value: "Halfing", color: "hsl(232, 95%, 90%)"}
      - { label: "Tiefling", value: "Tiefling", color: "hsl(29, 95%, 90%)"}
      - { label: "Goliath", value: "Goliath", color: "hsl(143, 95%, 90%)"}
      - { label: "Dwarf", value: "Dwarf", color: "hsl(183, 95%, 90%)"}
      - { label: "Halfling", value: "Halfling", color: "hsl(269, 95%, 90%)"}
      - { label: "Tabaxi", value: "Tabaxi", color: "hsl(137, 95%, 90%)"}
      - { label: "Gnome", value: "Gnome", color: "hsl(341, 95%, 90%)"}
      - { label: "Half-Elf", value: "Half-Elf", color: "hsl(82, 95%, 90%)"}
      - { label: "Dragonborn", value: "Dragonborn", color: "hsl(112, 95%, 90%)"}
      - { label: "Aasimar", value: "Aasimar", color: "hsl(157, 95%, 90%)"}
      - { label: "Drow", value: "Drow", color: "hsl(131, 95%, 90%)"}
      - { label: "Half-Orc", value: "Half-Orc", color: "hsl(16, 95%, 90%)"}
      - { label: "Harengon", value: "Harengon", color: "hsl(304, 95%, 90%)"}
      - { label: "Tortle", value: "Tortle", color: "hsl(15, 95%, 90%)"}
      - { label: "Elf", value: "Elf", color: "hsl(110, 95%, 90%)"}
      - { label: "Leonin", value: "Leonin", color: "hsl(316, 95%, 90%)"}
      - { label: "[[Akuktuq|Akuktuq]]", value: "[[Akuktuq|Akuktuq]]", color: "hsl(176, 95%, 90%)"}
      - { label: "Frost Orc", value: "Frost Orc", color: "hsl(108, 95%, 90%)"}
      - { label: "Shark", value: "Shark", color: "hsl(249, 95%, 90%)"}
      - { label: "[[5e Wiki/Races/Gnome.md|Gnome]]", value: "[[5e Wiki/Races/Gnome.md|Gnome]]", color: "hsl(90, 95%, 90%)"}
      - { label: "[[5e Wiki/Races/Half-Orc.md|Half-Orc]]", value: "[[5e Wiki/Races/Half-Orc.md|Half-Orc]]", color: "hsl(46, 95%, 90%)"}
      - { label: "[[Frost Orc|Frost Orc]]", value: "[[Frost Orc|Frost Orc]]", color: "hsl(184, 95%, 90%)"}
      - { label: "[[5e Wiki/Races/Dwarf.md|Dwarf]]", value: "[[5e Wiki/Races/Dwarf.md|Dwarf]]", color: "hsl(246, 95%, 90%)"}
      - { label: "[[5e Wiki/Races/Human.md|Human]]", value: "[[5e Wiki/Races/Human.md|Human]]", color: "hsl(227, 95%, 90%)"}
      - { label: "Tiger-kin", value: "Tiger-kin", color: "hsl(106, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
  Age:
    input: select
    accessor: Age
    key: Age
    label: Age
    position: 12
    skipPersist: false
    accessorKey: Age
    width: 150
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Adult", value: "Adult", color: "hsl(4, 95%, 90%)"}
      - { label: "Ancient", value: "Ancient", color: "hsl(270, 95%, 90%)"}
      - { label: "Child", value: "Child", color: "hsl(271, 95%, 90%)"}
      - { label: "Elderly", value: "Elderly", color: "hsl(231, 95%, 90%)"}
      - { label: "Infant", value: "Infant", color: "hsl(94, 95%, 90%)"}
      - { label: "Mature Adult", value: "Mature Adult", color: "hsl(331, 95%, 90%)"}
      - { label: "Teen", value: "Teen", color: "hsl(328, 95%, 90%)"}
      - { label: "Young Adult", value: "Young Adult", color: "hsl(86, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
  NoteIcon:
    input: select
    accessor: NoteIcon
    key: NoteIcon
    label: NoteIcon
    position: 5
    skipPersist: false
    accessorKey: NoteIcon
    width: 150
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Character", value: "Character", color: "hsl(221, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
  Condition:
    input: select
    accessor: Condition
    key: Condition
    label: Condition
    position: 13
    skipPersist: false
    accessorKey: Condition
    width: 150
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Dead", value: "Dead", color: "hsl(280, 95%, 90%)"}
      - { label: "Dying", value: "Dying", color: "hsl(323, 95%, 90%)"}
      - { label: "Healthy", value: "Healthy", color: "hsl(342, 95%, 90%)"}
      - { label: "Hurt", value: "Hurt", color: "hsl(10, 95%, 90%)"}
      - { label: "Sick", value: "Sick", color: "hsl(80, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
  Location:
    input: select
    accessor: Location
    key: Location
    label: Location
    position: 14
    skipPersist: false
    accessorKey: Location
    width: 150
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Celest", value: "Celest", color: "hsl(154, 95%, 90%)"}
      - { label: "With Party", value: "With Party", color: "hsl(197, 95%, 90%)"}
      - { label: "[[Locations/Celeste.md|Celeste]]", value: "[[Locations/Celeste.md|Celeste]]", color: "hsl(233, 95%, 90%)"}
      - { label: "[[Celeste|Celeste]]", value: "[[Celeste|Celeste]]", color: "hsl(68, 95%, 90%)"}
      - { label: "[[Locations/Darken Post.md|Darken Post]]", value: "[[Locations/Darken Post.md|Darken Post]]", color: "hsl(205, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
  Alias:
    input: text
    accessor: Alias
    key: Alias
    label: Alias
    position: 4
    skipPersist: false
    accessorKey: Alias
    width: 176
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
  Occupation:
    input: tags
    accessor: Occupation
    key: Occupation
    label: Occupation
    position: 16
    skipPersist: false
    accessorKey: Occupation
    width: 132
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Adventurer", value: "Adventurer", color: "hsl(232, 95%, 90%)"}
      - { label: "Alchemist", value: "Alchemist", color: "hsl(204, 95%, 90%)"}
      - { label: "Archeologist", value: "Archeologist", color: "hsl(66, 95%, 90%)"}
      - { label: "Barkeeper", value: "Barkeeper", color: "hsl(68, 95%, 90%)"}
      - { label: "Blacksmith", value: "Blacksmith", color: "hsl(66, 95%, 90%)"}
      - { label: "Courier", value: "Courier", color: "hsl(164, 95%, 90%)"}
      - { label: "Enchanter", value: "Enchanter", color: "hsl(178, 95%, 90%)"}
      - { label: "Farmer", value: "Farmer", color: "hsl(70, 95%, 90%)"}
      - { label: "Guard", value: "Guard", color: "hsl(320, 95%, 90%)"}
      - { label: "Historian", value: "Historian", color: "hsl(24, 95%, 90%)"}
      - { label: "Libarian", value: "Libarian", color: "hsl(7, 95%, 90%)"}
      - { label: "Mage", value: "Mage", color: "hsl(194, 95%, 90%)"}
      - { label: "Merchant", value: "Merchant", color: "hsl(140, 95%, 90%)"}
      - { label: "Noble", value: "Noble", color: "hsl(28, 95%, 90%)"}
      - { label: "Priest", value: "Priest", color: "hsl(322, 95%, 90%)"}
      - { label: "Royal", value: "Royal", color: "hsl(126, 95%, 90%)"}
      - { label: "Servant", value: "Servant", color: "hsl(249, 95%, 90%)"}
      - { label: "Stablehand", value: "Stablehand", color: "hsl(25, 95%, 90%)"}
      - { label: "Steward", value: "Steward", color: "hsl(339, 95%, 90%)"}
      - { label: "Teacher", value: "Teacher", color: "hsl(36, 95%, 90%)"}
      - { label: "Hunter", value: "Hunter", color: "hsl(354, 95%, 90%)"}
      - { label: "Archwizard of Celeste", value: "Archwizard of Celeste", color: "hsl(16, 95%, 90%)"}
      - { label: "Council Member", value: "Council Member", color: "hsl(12, 95%, 90%)"}
      - { label: "Ship's Captain", value: "Ship's Captain", color: "hsl(355, 95%, 90%)"}
      - { label: "Mayor", value: "Mayor", color: "hsl(69, 95%, 90%)"}
      - { label: "Bishop of the Gods", value: "Bishop of the Gods", color: "hsl(268, 95%, 90%)"}
      - { label: "Mistress of the Seas", value: "Mistress of the Seas", color: "hsl(136, 95%, 90%)"}
      - { label: "Mistress of the Skies", value: "Mistress of the Skies", color: "hsl(134, 95%, 90%)"}
      - { label: "Guild Master", value: "Guild Master", color: "hsl(112, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
  AssociatedReligion:
    input: tags
    accessor: AssociatedReligion
    key: AssociatedReligion
    label: AssociatedReligion
    position: 18
    skipPersist: false
    accessorKey: AssociatedReligion
    width: 78
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Celest", value: "Celest", color: "hsl(155, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
  Pronounced:
    input: text
    accessor: Pronounced
    key: Pronounced
    label: Pronounced
    position: 3
    skipPersist: false
    accessorKey: Pronounced
    width: 190
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
      content_alignment: text-align-center
      content_vertical_alignment: align-middle
      wrap_content: true
  WhichParty:
    input: select
    accessor: WhichParty
    key: WhichParty
    label: WhichParty
    position: 15
    skipPersist: false
    accessorKey: WhichParty
    width: 138
    isHidden: false
    sortIndex: 2
    isSorted: true
    isSortedDesc: true
    options:
      - { label: "Party 1", value: "Party 1", color: "hsl(152, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
      option_source: manual
  Type:
    input: select
    accessor: Type
    key: Type
    label: Type
    position: 6
    skipPersist: false
    accessorKey: Type
    width: 174
    isHidden: false
    sortIndex: -1
    options:
      - { label: "[,VIP]", value: "[,VIP]", color: "hsl(250, 95%, 90%)"}
      - { label: "[,NPC]", value: "[,NPC]", color: "hsl(63, 95%, 90%)"}
      - { label: "NPC", value: "NPC", color: "hsl(146, 95%, 90%)"}
      - { label: "VIP", value: "VIP", color: "hsl(337, 95%, 90%)"}
      - { label: "[,,VIP]", value: "[,,VIP]", color: "hsl(257, 95%, 90%)"}
      - { label: "[,,NPC]", value: "[,,NPC]", color: "hsl(304, 95%, 90%)"}
      - { label: "Player", value: "Player", color: "hsl(301, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  SocialTrait:
    input: tags
    accessorKey: SocialTrait
    key: SocialTrait
    label: SocialTrait
    position: 20
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Bossy", value: "Bossy", color: "hsl(115, 95%, 90%)"}
      - { label: "Cruel", value: "Cruel", color: "hsl(116, 95%, 90%)"}
      - { label: "Deferential", value: "Deferential", color: "hsl(325, 95%, 90%)"}
      - { label: "Demanding", value: "Demanding", color: "hsl(111, 95%, 90%)"}
      - { label: "Dependable", value: "Dependable", color: "hsl(217, 95%, 90%)"}
      - { label: "Dishonest", value: "Dishonest", color: "hsl(100, 95%, 90%)"}
      - { label: "Forthcoming", value: "Forthcoming", color: "hsl(110, 95%, 90%)"}
      - { label: "Friendly", value: "Friendly", color: "hsl(234, 95%, 90%)"}
      - { label: "Generous", value: "Generous", color: "hsl(297, 95%, 90%)"}
      - { label: "Helpful", value: "Helpful", color: "hsl(303, 95%, 90%)"}
      - { label: "Honest", value: "Honest", color: "hsl(145, 95%, 90%)"}
      - { label: "Impartial", value: "Impartial", color: "hsl(70, 95%, 90%)"}
      - { label: "Intolerant", value: "Intolerant", color: "hsl(136, 95%, 90%)"}
      - { label: "Lenient", value: "Lenient", color: "hsl(343, 95%, 90%)"}
      - { label: "Loyal", value: "Loyal", color: "hsl(280, 95%, 90%)"}
      - { label: "Peaceful", value: "Peaceful", color: "hsl(105, 95%, 90%)"}
      - { label: "Quite", value: "Quite", color: "hsl(218, 95%, 90%)"}
      - { label: "Secretive", value: "Secretive", color: "hsl(310, 95%, 90%)"}
      - { label: "Selfish", value: "Selfish", color: "hsl(70, 95%, 90%)"}
      - { label: "Selfless", value: "Selfless", color: "hsl(79, 95%, 90%)"}
      - { label: "Stingy", value: "Stingy", color: "hsl(129, 95%, 90%)"}
      - { label: "Suspicious", value: "Suspicious", color: "hsl(80, 95%, 90%)"}
      - { label: "Talkative", value: "Talkative", color: "hsl(198, 95%, 90%)"}
      - { label: "Tolerant", value: "Tolerant", color: "hsl(154, 95%, 90%)"}
      - { label: "Trusting", value: "Trusting", color: "hsl(207, 95%, 90%)"}
      - { label: "Uncooperative", value: "Uncooperative", color: "hsl(66, 95%, 90%)"}
      - { label: "Unfair", value: "Unfair", color: "hsl(176, 95%, 90%)"}
      - { label: "Unfaithful", value: "Unfaithful", color: "hsl(329, 95%, 90%)"}
      - { label: "Unfriendly", value: "Unfriendly", color: "hsl(37, 95%, 90%)"}
      - { label: "Unreliable", value: "Unreliable", color: "hsl(318, 95%, 90%)"}
      - { label: "Violent", value: "Violent", color: "hsl(124, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  MentalTrait:
    input: tags
    accessorKey: MentalTrait
    key: MentalTrait
    label: MentalTrait
    position: 21
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Adaptive", value: "Adaptive", color: "hsl(346, 95%, 90%)"}
      - { label: "Ambitious", value: "Ambitious", color: "hsl(191, 95%, 90%)"}
      - { label: "Analytical", value: "Analytical", color: "hsl(124, 95%, 90%)"}
      - { label: "Cautious", value: "Cautious", color: "hsl(329, 95%, 90%)"}
      - { label: "Comformist", value: "Comformist", color: "hsl(73, 95%, 90%)"}
      - { label: "Complacent", value: "Complacent", color: "hsl(258, 95%, 90%)"}
      - { label: "Courageous", value: "Courageous", color: "hsl(53, 95%, 90%)"}
      - { label: "Cowardly", value: "Cowardly", color: "hsl(247, 95%, 90%)"}
      - { label: "Creative", value: "Creative", color: "hsl(96, 95%, 90%)"}
      - { label: "Decisive", value: "Decisive", color: "hsl(336, 95%, 90%)"}
      - { label: "Emotional", value: "Emotional", color: "hsl(212, 95%, 90%)"}
      - { label: "Impatient", value: "Impatient", color: "hsl(84, 95%, 90%)"}
      - { label: "Inattentive", value: "Inattentive", color: "hsl(281, 95%, 90%)"}
      - { label: "Incompetent", value: "Incompetent", color: "hsl(186, 95%, 90%)"}
      - { label: "Indecisive", value: "Indecisive", color: "hsl(270, 95%, 90%)"}
      - { label: "Independent", value: "Independent", color: "hsl(319, 95%, 90%)"}
      - { label: "Intelligent", value: "Intelligent", color: "hsl(66, 95%, 90%)"}
      - { label: "Patient", value: "Patient", color: "hsl(290, 95%, 90%)"}
      - { label: "Perceptive", value: "Perceptive", color: "hsl(21, 95%, 90%)"}
      - { label: "Reckless", value: "Reckless", color: "hsl(59, 95%, 90%)"}
      - { label: "Religious", value: "Religious", color: "hsl(279, 95%, 90%)"}
      - { label: "Secular", value: "Secular", color: "hsl(352, 95%, 90%)"}
      - { label: "Skeptical", value: "Skeptical", color: "hsl(11, 95%, 90%)"}
      - { label: "Skillful", value: "Skillful", color: "hsl(354, 95%, 90%)"}
      - { label: "Stupid", value: "Stupid", color: "hsl(315, 95%, 90%)"}
      - { label: "Superstitious", value: "Superstitious", color: "hsl(355, 95%, 90%)"}
      - { label: "Tenacious", value: "Tenacious", color: "hsl(195, 95%, 90%)"}
      - { label: "Uninventive", value: "Uninventive", color: "hsl(207, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  PersonalityTrait:
    input: tags
    accessorKey: PersonalityTrait
    key: PersonalityTrait
    label: PersonalityTrait
    position: 19
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Anxious", value: "Anxious", color: "hsl(21, 95%, 90%)"}
      - { label: "Apathetic", value: "Apathetic", color: "hsl(38, 95%, 90%)"}
      - { label: "Articulate", value: "Articulate", color: "hsl(131, 95%, 90%)"}
      - { label: "Awkward", value: "Awkward", color: "hsl(278, 95%, 90%)"}
      - { label: "Calm", value: "Calm", color: "hsl(136, 95%, 90%)"}
      - { label: "Caring", value: "Caring", color: "hsl(196, 95%, 90%)"}
      - { label: "Charming", value: "Charming", color: "hsl(12, 95%, 90%)"}
      - { label: "Cheerful", value: "Cheerful", color: "hsl(293, 95%, 90%)"}
      - { label: "Childish", value: "Childish", color: "hsl(339, 95%, 90%)"}
      - { label: "Cold", value: "Cold", color: "hsl(266, 95%, 90%)"}
      - { label: "Depressed", value: "Depressed", color: "hsl(130, 95%, 90%)"}
      - { label: "Dull", value: "Dull", color: "hsl(248, 95%, 90%)"}
      - { label: "Eccentric", value: "Eccentric", color: "hsl(244, 95%, 90%)"}
      - { label: "Energetic", value: "Energetic", color: "hsl(74, 95%, 90%)"}
      - { label: "Enthusiastic", value: "Enthusiastic", color: "hsl(333, 95%, 90%)"}
      - { label: "Funny", value: "Funny", color: "hsl(205, 95%, 90%)"}
      - { label: "Gentle", value: "Gentle", color: "hsl(233, 95%, 90%)"}
      - { label: "Humble", value: "Humble", color: "hsl(197, 95%, 90%)"}
      - { label: "Humorless", value: "Humorless", color: "hsl(128, 95%, 90%)"}
      - { label: "Impolite", value: "Impolite", color: "hsl(67, 95%, 90%)"}
      - { label: "Incoherent", value: "Incoherent", color: "hsl(49, 95%, 90%)"}
      - { label: "Listless", value: "Listless", color: "hsl(127, 95%, 90%)"}
      - { label: "Mature", value: "Mature", color: "hsl(138, 95%, 90%)"}
      - { label: "Naive", value: "Naive", color: "hsl(320, 95%, 90%)"}
      - { label: "Optimistic", value: "Optimistic", color: "hsl(136, 95%, 90%)"}
      - { label: "Overt", value: "Overt", color: "hsl(187, 95%, 90%)"}
      - { label: "Pessimistic", value: "Pessimistic", color: "hsl(345, 95%, 90%)"}
      - { label: "Polite", value: "Polite", color: "hsl(251, 95%, 90%)"}
      - { label: "Proud", value: "Proud", color: "hsl(353, 95%, 90%)"}
      - { label: "Repulsive", value: "Repulsive", color: "hsl(77, 95%, 90%)"}
      - { label: "Respectful", value: "Respectful", color: "hsl(61, 95%, 90%)"}
      - { label: "Savvy", value: "Savvy", color: "hsl(85, 95%, 90%)"}
      - { label: "Sensitive", value: "Sensitive", color: "hsl(186, 95%, 90%)"}
      - { label: "Smooth", value: "Smooth", color: "hsl(81, 95%, 90%)"}
      - { label: "Subtle", value: "Subtle", color: "hsl(266, 95%, 90%)"}
      - { label: "Thick-skinned", value: "Thick-skinned", color: "hsl(69, 95%, 90%)"}
      - { label: "Wrathful", value: "Wrathful", color: "hsl(186, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Likes:
    input: text
    accessorKey: Likes
    key: Likes
    label: Likes
    position: 22
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Dislikes:
    input: text
    accessorKey: Dislikes
    key: Dislikes
    label: Dislikes
    position: 24
    skipPersist: false
    isHidden: false
    width: 152
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Art:
    input: text
    accessorKey: Art
    key: Art
    id: Art
    label: Art
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Party1Standing:
    input: select
    accessorKey: Party1Standing
    key: Party1Standing
    id: PartyStanding
    label: Party1Standing
    position: 8
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Friend", value: "Friend", color: "hsl(243, 95%, 90%)"}
      - { label: "Family", value: "Family", color: "hsl(208, 95%, 90%)"}
      - { label: "Ally", value: "Ally", color: "hsl(91, 95%, 90%)"}
      - { label: "Enemy", value: "Enemy", color: "hsl(238, 95%, 90%)"}
      - { label: "Unmet", value: "Unmet", color: "hsl(108, 95%, 90%)"}
      - { label: "Acquaintance", value: "Acquaintance", color: "hsl(10, 95%, 90%)"}
      - { label: "Lover", value: "Lover", color: "hsl(337, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Class:
    input: select
    accessorKey: Class
    key: Class
    id: newColumn23
    label: Class
    position: 9
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "[[5e/Bard|Bard]]", value: "[[5e/Bard|Bard]]", color: "hsl(254, 95%, 90%)"}
      - { label: "Wizard", value: "Wizard", color: "hsl(356, 95%, 90%)"}
      - { label: "Fighter", value: "Fighter", color: "hsl(297, 95%, 90%)"}
      - { label: "Barbarian/Fighter", value: "Barbarian/Fighter", color: "hsl(152, 95%, 90%)"}
      - { label: "Rouge/Fighter", value: "Rouge/Fighter", color: "hsl(112, 95%, 90%)"}
      - { label: "[[5e/Bard.md|Bard]]", value: "[[5e/Bard.md|Bard]]", color: "hsl(318, 95%, 90%)"}
      - { label: "[,[[5e Wiki/Classes/Wizard.md|Wizard]]]", value: "[,[[5e Wiki/Classes/Wizard.md|Wizard]]]", color: "hsl(346, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Party:
    input: text
    accessorKey: Party
    key: Party
    id: newColumn24
    label: Party
    position: 23
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Sex:
    input: select
    accessorKey: Sex
    key: Sex
    id: newColumn25
    label: Sex
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Male", value: "Male", color: "hsl(289, 95%, 90%)"}
      - { label: "Female", value: "Female", color: "hsl(154, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Factions:
    input: tags
    accessor: AssociatedGroup
    key: Factions
    label: Factions
    position: 17
    skipPersist: false
    accessorKey: Factions
    width: 150
    isHidden: false
    sortIndex: -1
    options:
      - { label: "The Adopted", value: "The Adopted", color: "hsl(105, 95%, 90%)"}
      - { label: "[[Factions/High Council of Celeste.md|High Council of Celeste]]", value: "[[Factions/High Council of Celeste.md|High Council of Celeste]]", color: "hsl(214, 95%, 90%)"}
      - { label: "[[The Boneclaw Tribe|The Boneclaw Tribe]]", value: "[[The Boneclaw Tribe|The Boneclaw Tribe]]", color: "hsl(305, 95%, 90%)"}
      - { label: "[[Factions/The Adopted.md|The Adopted]]", value: "[[Factions/The Adopted.md|The Adopted]]", color: "hsl(165, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      source_data: current_folder
      option_source: manual
config:
  enable_show_state: false
  group_folder_column: 
  remove_field_when_delete_column: true
  cell_size: compact
  sticky_first_column: true
  show_metadata_created: true
  show_metadata_modified: true
  source_data: current_folder
  source_form_result: 
  show_metadata_tasks: false
  frontmatter_quote_wrap: false
  row_templates_folder: /
  current_row_template: Templates/Template - NPC.md
  pagination_size: 15
  source_destination_path: /
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: top
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  font_size: 16
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
  show_metadata_tags: false
filters:
  enabled: false
  conditions:
```