# 1.60.1.70124 -> 1.60.1.70170

Compared `builds/1.60.1.70124` → `builds/1.60.1.70170`.

| Table | Added | Removed | Changed |
|---|---:|---:|---:|
| Achievement | 1 | 0 | 20 |
| Creature | 0 | 0 | 3 |
| GlobalStrings | 14 | 0 | 41 |
| Item | 3 | 0 | 36 |
| ItemEffect | 7 | 0 | 98 |
| ItemSparse | 3 | 3 | 122 |
| ItemXItemEffect | 7 | 0 | 0 |
| Map | 0 | 1 | 1 |
| Spell | 37 | 15 | 733 |
| SpellAuraOptions | 14 | 9 | 6 |
| SpellCooldowns | 6 | 6 | 0 |
| SpellEffect | 64 | 20 | 72 |
| SpellMisc | 37 | 15 | 143 |
| SpellName | 37 | 15 | 25 |
| SpellPower | 1 | 1 | 0 |
| SpellXSpellVisual | 26 | 12 | 29 |
| TraitDefinition | 2 | 0 | 1 |
| TraitNode | 1 | 0 | 4 |
| TraitNodeEntry | 2 | 0 | 1 |

## Achievement

1 added, 0 removed, 20 changed.

### $\color{#3FB950}\textbf{Added}$

- <Hidden> Completed New Player Experience (Account) (64208)

### $\color{#D29922}\textbf{Changed}$

- **Baron Rivendare kills (Stratholme) (1097)**
  - `Flags`: 524289 → 1572865
- **Conqueror of the Wilds (62034)**
  - `Title_lang`: Conquerer of the Wilds → Conqueror of the Wilds
- **Conqueror of the Deeps (62035)**
  - `Title_lang`: Conquerer of the Deeps → Conqueror of the Deeps
- **Rank 13 (62044)**
  - `Description_lang`: Reach the rank Field Marshal or Warlord in the Player vs. Player Honor System. → Reach the rank of Field Marshal or Warlord in the Player vs. Player Honor System.
- **Explore Eastern Kingdoms (62353)**
  - `Ui_order`: 11 → 20
- **Explore Kalimdor (62355)**
  - `Ui_order`: 12 → 21
- **Edwin VanCleef Kills (Deadmines) (63570)**
  - `Description_lang`: Edwin Vancleef Kills (Deadmines) → Edwin VanCleef Kills (Deadmines)
  - `Title_lang`: Edwin Vancleef Kills (Deadmines) → Edwin VanCleef Kills (Deadmines)
- **Cinder Kills (Shaper's Terrace) (63590)**
  - `Flags`: 524289 → 1572865
- **Bolt Kills (Shaper's Terrace) (63592)**
  - `Flags`: 524289 → 1572865
- **Snowtalon Kills (Shaper's Terrace) (63593)**
  - `Flags`: 524289 → 1572865
- **Conqueror of the Wilds (64019)**
  - `Title_lang`: Conquerer of the Wilds → Conqueror of the Wilds
- **Conqueror of the Deeps (64020)**
  - `Title_lang`: Conquerer of the Deeps → Conqueror of the Deeps
- **Rank 13 (64024)**
  - `Description_lang`: Reach the rank Field Marshal or Warlord in the Player vs. Player Honor System. → Reach the rank of Field Marshal or Warlord in the Player vs. Player Honor System.
- **Hidden: Rank 2 (64054)**
  - `Description_lang`: Reach the rank of Corportal or Grunt in the Player vs. Player Honor System. → Reach the rank of Corporal or Grunt in the Player vs. Player Honor System.
- **Hidden: Rank 13 (64062)**
  - `Description_lang`: Reach the rank Field Marshal or Warlord in the Player vs. Player Honor System. → Reach the rank of Field Marshal or Warlord in the Player vs. Player Honor System.
- **Darkspear Islands victories (64176)**
  - `Description_lang`: Darkspear Island victories → Darkspear Islands victories
  - `Title_lang`: Darkspear Island victories → Darkspear Islands victories
- **Darkspear Islands battles (64179)**
  - `Flags`: 0 → 1
- **Darkspear Islands Honorable Kills (64180)**
  - `Flags`: 0 → 1
- **Darkspear Islands Killing Blows (64181)**
  - `Description_lang`: Darkspear Island Killing Blows → Darkspear Islands Killing Blows
  - `Title_lang`: Darkspear Island Killing Blows → Darkspear Islands Killing Blows
  - `Flags`: 0 → 1
- **Deaths in Darkspear Islands (64182)**
  - `Flags`: 0 → 1

## Creature

0 added, 0 removed, 3 changed.

### $\color{#D29922}\textbf{Changed}$

- **Whiskers the Rat (16549)**
  - `DisplayID_0`: 2176 → 148791
- **Rat Familiar (266025)**
  - `DisplayID_0`: 1141 → 148790
- **Frog Familiar (268744)**
  - `DisplayID_0`: 6295 → 148792

## GlobalStrings

14 added, 0 removed, 41 changed.

### $\color{#3FB950}\textbf{Added}$

- (60383)
- (60405)
- (60421)
- (60424)
- (60428)
- (60429)
- (60430)
- (60433)
- (60434)
- (60435)
- (60436)
- (60438)
- (60439)
- (60440)

### $\color{#D29922}\textbf{Changed}$

- **(21011)**
  - `TagText_lang`: Increases the damage of your \|cFFFFFFFFSpells\|r by up to %d\n\nIncreased by \|cFFFFFFFFSpell Damage\|r and \|cFFFFFFF… → Increases the damage of your \|cFFFFFFFFSpells\|r by up to %d\n\nIncreased by \|cFFFFFFFFSpell Damage\|r and \|cFFFFFFF…
- **(21685)**
  - `TagText_lang`: Increases the healing of your \|cFFFFFFFFSpells\|r by up to %d\n\nIncreased by \|cFFFFFFFFSpell Healing\|r and \|cFFFFF… → Increases the healing of your \|cFFFFFFFFSpells\|r by up to %d\n\nIncreased by \|cFFFFFFFFSpell Healing\|r and \|cFFFFF…
- **(24150)**
  - `TagText_lang`: %s-%s → %s %s
- **(48704)**
  - `TagText_lang`: Invite to Instance Group → Invite to Group
- **(50406)**
  - `TagText_lang`: \|cffffffffDeath is permanent\|r\|n\|n\|cffffd200Hold, adventurer. The realm you are selecting is a HARDCORE realm. If … → \|cffffffffDeath is permanent\|r\|n\|n\|cffffd200Hold, adventurer. The realm you are selecting is a HARDCORE realm. If …
- **(50407)**
  - `TagText_lang`: Welcome to WoW Classic Hardcore Realms. Any character that dies on a Hardcore realm can never resurrect on that realm f… → Welcome to WoW Classic Hardcore Realms. Any character that dies on a Hardcore realm can never resurrect on that realm f…
- **(51483)**
  - `TagText_lang`: \|Hplayer:%s\|h[%s]\|h has been slain in a duel by %s in $s! They were level %d → \|Hplayer:%s\|h[%s]\|h has been slain in a duel by %s in %s! They were level %d
- **(51641)**
  - `TagText_lang`: A self-found character cannot do the following: - Trade with other players - Send mail to other players, or receive p… → A self-found character cannot do the following: - Trade with other players - Send mail to other players, or receive p…
- **(51876)**
  - `TagText_lang`: Only show raid-style warnings for guilds member deaths → Only show raid-style warnings for guild member deaths
- **(55263)**
  - `TagText_lang`: For thousands of years, a band of high elven exiles has remained safe and hidden upon their flying sanctuary of Zephras… → For thousands of years, a band of high elven exiles has remained safe and hidden upon their flying sanctuary of Zephras…
- **(55894)**
  - `TagText_lang`: This spell can be only be cast in raid instances. → This spell can only be cast in raid instances.
- **(56694)**
  - `TagText_lang`: Increase your pets loyalty and level to gain Training Points. → Increase your pet's loyalty and level to gain Training Points.
- **(57100)**
  - `TagText_lang`: Avoidable damage tracking is only active in current season instances → No avoidable damage has been dealt. Avoidable damage tracking may not be available in all content.
- **(57754)**
  - `TagText_lang`: Combat Audio Alerts are currently disabled. To enable them, type  /<spell>tts</spell>combat → Combat Audio Alerts are currently disabled. To enable them, type /<spell>tts</spell>combat
- **(57804)**
  - `TagText_lang`: Combat Audio Alert Say Targets Casts Voice set to %s → Combat Audio Alert Say Target's Casts Voice set to %s
- **(57925)**
  - `TagText_lang`: Says when a debuff is applied on you → Says when a debuff is applied to you
- **(57942)**
  - `TagText_lang`: Says when a debuff is applied on you → Says when a debuff is applied to you
- **(58199)**
  - `TagText_lang`: Purchase has failed, Insufficient funds. → Purchase has failed: insufficient funds.
- **(58307)**
  - `TagText_lang`: When this is true the gamepad UI will be enabled → When this is true, the gamepad UI will be enabled
- **(58413)**
  - `TagText_lang`: When two lights are overlapping the indicator will appear. → When two lights are overlapping, the indicator will appear.
- **(58434)**
  - `TagText_lang`: Wait, dont pull → Wait, don't pull
- **(58613)**
  - `TagText_lang`: Reticle Aiming: While the Targeting Modifier is active, move the HUD reticle in the center of the screen over a unit to… → Reticle Aiming: While the Targeting Modifier is active, move the HUD reticle in the center of the screen over a unit to…
- **(58632)**
  - `TagText_lang`: When the possess action bar is displayed, the selected action bar will be temporarily be replaced with it. → When the possess action bar is displayed, the selected action bar will be temporarily replaced with it.
- **(58634)**
  - `TagText_lang`: When the stance action bar is displayed, the selected action bar will be temporarily be replaced with it. → When the stance action bar is displayed, the selected action bar will be temporarily replaced with it.
- **(58672)**
  - `TagText_lang`: Secondary lighting effect are disabled. → Secondary lighting effects are disabled.
- **(58782)**
  - `TagText_lang`: Disables the Transmog System, you will not see other Players' Transmogs and they will not see yours. → Disables the Transmog System. You will not see other Players' Transmogs and they will not see yours.
- **(58940)**
  - `TagText_lang`: This wick is still souldbound to its finder. Try again in a moment. → This wick is still soulbound to its finder. Try again in a moment.
- **(59041)**
  - `TagText_lang`: Displays health, power, and class resources. The Personal Resource Display is currently disabled. Enable it in: Combat>… → Displays health, power, and class resources. The Personal Resource Display is currently disabled. Enable it in: Combat …
- **(59571)**
  - `TagText_lang`: Chose the style of voice used by the screen narrator → Choose the style of voice used by the screen narrator
- **(59629)**
  - `TagText_lang`: \|cnNORMAL_FONT_COLOR:You have received a Real ID friend request\|r\|n\|n\|cnHIGHLIGHT_FONT_COLOR:This should be a pers… → \|cnNORMAL_FONT_COLOR:You have received a Real ID friend request\|r\|n\|n\|cnHIGHLIGHT_FONT_COLOR:This should be a pers…
- **(59718)**
  - `TagText_lang`: Hide Interface enabled, Press Escape to exit mode → Hide Interface enabled. Press Escape to exit mode
- **(59827)**
  - `TagText_lang`: No valid channels to link.  Make sure you have Manage Channels permission on the server. → No valid channels to link. Make sure you have Manage Channels permission on the server.
- **(59992)**
  - `TagText_lang`: Very-High resolution reflections, Bicubic filtering, and flow calculations. → Very high resolution reflections, Bicubic filtering, and flow calculations.
- **(60023)**
  - `TagText_lang`: Please enter full character name. → Please enter a full character name.
- **(60078)**
  - `TagText_lang`: The world around you will refresh in %s %s. Make sure you are out of combat and in a safe area, or select refresh now. → The world around you will refresh in %s %s. Make sure you are out of combat and in a safe area, or click here to refres…
- **(60079)**
  - `TagText_lang`: The world around you will refresh in %s %s → World refresh in %s %s
- **(60110)**
  - `TagText_lang`: Camera follows centered behind the player. → Camera follows the player while remaining centered behind them.
- **(60130)**
  - `TagText_lang`: Stick angle past the set value will make the player face the stick movement otherwise the player strafes while facing t… → Stick angle past the set value will make the player face the stick movement; otherwise, the player strafes while facing…
- **(60131)**
  - `TagText_lang`: Stick angle past the set value will make the player face the stick movement otherwise the player strafes while facing t… → Stick angle past the set value will make the player face the stick movement; otherwise, the player strafes while facing…
- **(60189)**
  - `TagText_lang`: Your \|cFFFFFFFFAttacks\|r ignore %d of your enemies \|cFFFFFFFFArmor\|r when attacking. Reducing an enemies armor belo… → Your \|cFFFFFFFFAttacks\|r ignore %d of your enemies' \|cFFFFFFFFArmor\|r when attacking. Reducing an enemy's armor bel…
- **(60194)**
  - `TagText_lang`: PvP Rank's are currently unavailable. → PvP Ranks are currently unavailable.

## Item

3 added, 0 removed, 36 changed.

### $\color{#3FB950}\textbf{Added}$

- (287416)
- (287423)
- (287505)

### $\color{#D29922}\textbf{Changed}$

- **(3382)**
  - `SubclassID`: 1 → 2
- **(3388)**
  - `SubclassID`: 1 → 2
- **(3826)**
  - `SubclassID`: 1 → 2
- **(7997)**
  - `SubclassID`: 0 → 2
- **(20004)**
  - `SubclassID`: 1 → 2
- **(20007)**
  - `SubclassID`: 1 → 2
- **(213548)**
  - `IconFileDataID`: 134937 → 4549171
- **(213550)**
  - `IconFileDataID`: 134937 → 4549172
- **(217495)**
  - `Material`: 2 → 7
  - `IconFileDataID`: 254300 → 4549168
  - `ItemGroupSoundsID`: 12 → 20
- **(217496)**
  - `IconFileDataID`: 134937 → 4549173
- **(263412)**
  - `IconFileDataID`: 538570 → 134919
- **(272091)**
  - `IconFileDataID`: 133042 → 133053
- **(273636)**
  - `IconFileDataID`: 135638 → 135649
- **(277486)**
  - `IconFileDataID`: 4549170 → 4549172
- **(286977)**
  - `IconFileDataID`: 0 → 135312
- **(286981)**
  - `IconFileDataID`: 0 → 132605
- **(280839)**
  - `IconFileDataID`: 133643 → 132762
  - `ItemGroupSoundsID`: 15 → 13
- **(213564)**
  - `IconFileDataID`: 134937 → 4549171
- **(215257)**
  - `IconFileDataID`: 134937 → 4549171
- **(277492)**
  - `IconFileDataID`: 134937 → 4549171
- **(277484)**
  - `IconFileDataID`: 134937 → 4549172
- **(277491)**
  - `IconFileDataID`: 134937 → 4549172
- **(277499)**
  - `Material`: 2 → 7
  - `IconFileDataID`: 254300 → 4549168
  - `ItemGroupSoundsID`: 12 → 20
- **(277490)**
  - `IconFileDataID`: 134937 → 4549173
- **(277504)**
  - `IconFileDataID`: 134937 → 4549173
- **(268535)**
  - `ClassID`: 15 → 12
  - `SubclassID`: 4 → 0
- **(272092)**
  - `IconFileDataID`: 133042 → 133053
- **(272093)**
  - `IconFileDataID`: 133042 → 133053
- **(272094)**
  - `IconFileDataID`: 133042 → 133053
- **(277485)**
  - `IconFileDataID`: 4549170 → 4549168
- **(277496)**
  - `IconFileDataID`: 4549170 → 4549168
- **(277501)**
  - `IconFileDataID`: 4549170 → 4549168
- **(277494)**
  - `IconFileDataID`: 4549170 → 4549172
- **(277495)**
  - `IconFileDataID`: 4549170 → 4549172
- **(277498)**
  - `IconFileDataID`: 4549168 → 4549172
- **(277502)**
  - `IconFileDataID`: 4549170 → 4549172

## ItemEffect

7 added, 0 removed, 9 changed, 1 mass-changed column(s).

### $\color{#3FB950}\textbf{Added}$

- (238283)
- (238284)
- (238285)
- (238286)
- (238429)
- (238608)
- (238431)

### $\color{#D29922}\textbf{Changed}$

- **(97055)**
  - `CategoryCoolDownMSec`: 0 → 3000
- **(102918)**
  - `CategoryCoolDownMSec`: 0 → 3000
- **(103266)**
  - `CategoryCoolDownMSec`: 0 → 3000
- **(184327)**
  - `CategoryCoolDownMSec`: 30000 → 3000
- **(184879)**
  - `CategoryCoolDownMSec`: 30000 → 3000
- **(214441)**
  - `CategoryCoolDownMSec`: -1 → 3000
- **(214444)**
  - `CategoryCoolDownMSec`: -1 → 3000
- **(232891)**
  - `CategoryCoolDownMSec`: -1 → 3000
- **(213462)**
  - `SpellID`: 5006 → 435

### $\color{#A371F7}\textbf{Mass changes}$

- `SpellCategoryID` changed in 97 rows (e.g. 0 → 2593, 79 → 2593, 79 → 2593)

## ItemSparse

3 added, 3 removed, 122 changed.

### $\color{#3FB950}\textbf{Added}$

- Monster - Shield, Paladin (286140)
- Truskis' Cheesecake Slice (287416)
- Tender Strider Meat (287505)

### $\color{#F85149}\textbf{Removed}$

- Leafre's Ring of Great Resistance (274978)
- Leafre's Ring of Precise Spell Power (276765)
- Leafre's Ring of Armor Piercing (285326)

### $\color{#D29922}\textbf{Changed}$

- **Bronze Shortsword (2850)**
  - `Bonding`: 0 → 2
- **Rough Bronze Cuirass (2866)**
  - `Bonding`: 0 → 2
- **Rough Bronze Shoulders (3480)**
  - `Bonding`: 0 → 2
- **Green Leather Armor (4255)**
  - `Bonding`: 1 → 2
- **Solliden's Trousers (4261)**
  - `Bonding`: 0 → 2
- **Small Green Dagger (4302)**
  - `Flags_4`: 0 → 768
  - `Bonding`: 0 → 2
- **Raw Spotted Yellowtail (4603)**
  - `VendorStackCount`: 5 → 1
- **Golden Scale Bracers (6040)**
  - `Bonding`: 0 → 2
- **Raw Longjaw Mud Snapper (6289)**
  - `VendorStackCount`: 5 → 1
- **Raw Brilliant Smallfish (6291)**
  - `VendorStackCount`: 5 → 1
- **Raw Slitherskin Mackerel (6303)**
  - `VendorStackCount`: 5 → 1
- **Raw Bristle Whisker Catfish (6308)**
  - `VendorStackCount`: 5 → 1
- **Raw Loch Frenzy (6317)**
  - `VendorStackCount`: 5 → 1
- **Raw Rainbow Fin Albacore (6361)**
  - `VendorStackCount`: 5 → 1
- **Raw Rockscale Cod (6362)**
  - `VendorStackCount`: 5 → 1
- **Verigan's Fist (6953)**
  - `StatPercentEditor_0`: 4118 → 2941
  - `StatPercentEditor_1`: 7059 → 5882
- **Barbaric Iron Breastplate (7914)**
  - `Bonding`: 0 → 2
- **Steel Plate Helm (7922)**
  - `Bonding`: 0 → 2
- **Bronze Warhammer (7956)**
  - `Bonding`: 0 → 2
- **Bronze Greatsword (7957)**
  - `Bonding`: 0 → 2
- **Bronze Battle Axe (7958)**
  - `Bonding`: 0 → 2
- **Raw Mithril Head Trout (8365)**
  - `VendorStackCount`: 5 → 1
- **Raw Spinefin Halibut (8959)**
  - `VendorStackCount`: 5 → 1
- **Greater Magic Wand (11288)**
  - `SellPrice`: 1535 → 1
- **Lesser Magic Wand (11287)**
  - `SellPrice`: 508 → 1
- **Lesser Mystic Wand (11289)**
  - `SellPrice`: 3581 → 1
- **Alchemist's Stone (13503)**
  - `Display_lang`: Alchemists' Stone → Alchemist's Stone
- **Recipe: Alchemist's Stone (13517)**
  - `Display_lang`: Recipe: Alchemists' Stone → Recipe: Alchemist's Stone
- **Raw Glossy Mightfish (13754)**
  - `VendorStackCount`: 5 → 1
- **Raw Summer Bass (13756)**
  - `VendorStackCount`: 5 → 1
- **Raw Redgill (13758)**
  - `VendorStackCount`: 5 → 1
- **Raw Nightfin Snapper (13759)**
  - `VendorStackCount`: 5 → 1
- **Raw Sunscale Salmon (13760)**
  - `VendorStackCount`: 5 → 1
- **Darkclaw Lobster (13888)**
  - `VendorStackCount`: 5 → 1
- **Raw Whitescale Salmon (13889)**
  - `VendorStackCount`: 5 → 1
- **Dragonslayer's Signet (18403)**
  - `Flags_0`: 0 → 524288
- **Onyxia Blood Talisman (18406)**
  - `Flags_0`: 0 → 524288
- **Greater Mystic Wand (217287)**
  - `SellPrice`: 5263 → 1
- **Scroll of Cryoblast (217495)**
  - `Material`: 2 → 7
- **Forgotten Ashes (247684)**
  - `Description_lang`: All that remains of a terrible thing → All that remains of a terrible thing.
- **Twisted Nether Wand (249144)**
  - `SellPrice`: 5263 → 1
- **Lesser Eternal Wand (249232)**
  - `SellPrice`: 5263 → 1
- **Dreambough Wand (249234)**
  - `SellPrice`: 5263 → 1
- **Greater Eternal Wand (249237)**
  - `SellPrice`: 5263 → 1
- **Formula: Tenets of the Silver Hand (249477)**
  - `Description_lang`: Teaches you how to craft Tenants of the Silver Hand. → Teaches you how to craft Tenets of the Silver Hand.
- **Formula: Libram of Invocation (249494)**
  - `Description_lang`: Teaches you how to craft Libram of Invocation. → Teaches you how to craft a Libram of Invocation.
- **Formula: Totem of Ancestral Protection (249495)**
  - `Description_lang`: Teaches you how to craft an Totem of Ancestral Protection. → Teaches you how to craft a Totem of Ancestral Protection.
- **Formula: Enchant Bracer - Superior Deflection (249539)**
  - `Description_lang`: Teaches you how to permanently enchant bracers to give +9 Defense Skill. → Teaches you how to permanently enchant bracers to give +6 Defense Skill.
- **Crate of Exotic Parts (250725)**
  - `Description_lang`: A bill-of-lading is attached that clearly marks the shipment as hazardous and requiring gentle transport.  Notes on the… → A bill of lading is attached that clearly marks the shipment as hazardous and requiring gentle transport. Notes on the …
- **Firestarter Fir (250744)**
  - `Description_lang`: A twisted handful of viable kindling → A twisted handful of viable kindling.
- **Sachet of Spirit Powder (251320)**
  - `Display_lang`: Satchet of Spirit Powder → Sachet of Spirit Powder
- **The Hum Gun (253258)**
  - `Description_lang`: You can almost make out the sigil of the alliance, barely visible under heavy corrosion → You can almost make out the sigil of the alliance, barely visible under heavy corrosion.
- **Reverence (254696)**
  - `Display_lang`: Reverance → Reverence
- **Huge Feather (254780)**
  - `Description_lang`: Only the procurer could tell whether it was pulled from a harpy or a hippogryph → Only the procurer could tell whether it was pulled from a harpy or a hippogryph.
- **Vicious Hook Talon (254859)**
  - `Description_lang`: Retractable claw, like a razor, on the middle toe → Retractable claw, like a razor, on the middle toe.
- **Lucky Lure (258530)**
  - `Description_lang`: Covered in the guts of countless swamp fish → Covered in the guts of countless swamp fish.
- **Al'Alketh Cultist's Ear (258771)**
  - `Description_lang`: You can't help but wonder what the Nightclaw plan to do with all these ears? → You can't help but wonder what the Nightclaw plan to do with all these ears.
- **Scribbled Directions to Sulfur Vents (260236)**
  - `Description_lang`: A hastily-scrawled list of locations for prospecting. → A hastily scrawled list of locations for prospecting.
- **Durotar Supply and Logistics Tabard (262764)**
  - `Flags_1`: 24581 → 24577
- **Azeroth Commerce Authority Tabard (262765)**
  - `Flags_1`: 24582 → 24578
- **Idol of Shifting Tides (263411)**
  - `Display_lang`: Windcharged Leaf → Idol of Shifting Tides
  - `ItemLevel`: 6 → 16
  - `OverallQualityID`: 1 → 2
- **Totem of Charged Flames (263412)**
  - `Display_lang`: Windcarved Effigy → Totem of Charged Flames
  - `ItemLevel`: 6 → 10
  - `OverallQualityID`: 1 → 2
- **Schematic: EZ-Thro Tru-Trigger (264218)**
  - `Description_lang`: Teaches you how to make Ez-Thro Tru-Trigger. → Teaches you how to make EZ-Thro Tru-Trigger.
- **Bloody Heirloom (265141)**
  - `Description_lang`: Drenched in the blood of those who were once were promised a brighter future. → Drenched in the blood of those who were once promised a brighter future.
- **Bloodied Insignia (268535)**
  - `MaxCount`: 0 → 1
  - `RequiredLevel`: 0 → 16
- **Fel Ash Sample (268813)**
  - `Description_lang`: The acrid smell of brimestone wafts off the pile, causing a burning sensation in the nose and throat if accidently inha… → The acrid smell of brimstone wafts off the pile, causing a burning sensation in the nose and throat if accidentally inh…
- **Sludgy Bits (268814)**
  - `Description_lang`: Pieces of something that didn't quite liquify... → Pieces of something that didn't quite liquefy...
- **Bone Fragments (268815)**
  - `Description_lang`: To small to identify, yet sharp enough to leave a nasty cut. → Too small to identify, yet sharp enough to leave a nasty cut.
- **Corrupted Grovewalker Sap (269008)**
  - `Description_lang`: Thick and almost gellationous in consistancy, this sap seems to be as acrid as it is thick. → Thick and almost gelatinous in consistency, this sap seems to be as acrid as it is thick.
- **Ashen Infused Crystal (269233)**
  - `Description_lang`: As you hold this crystal, it almost feels as if somthing is writhing within it. → As you hold this crystal, it almost feels as if something is writhing within it.
- **Explorers' League Cartographer's Kit (271770)**
  - `Description_lang`: A standard issue kit with all the tools necessary for exploring and categorizing newly explored areas. → A standard-issue kit with all the tools necessary for exploring and categorizing newly explored areas.
- **Drained Crystal Fragment (271771)**
  - `Description_lang`: A gem that is cool to the touch and hums gently. Strangely no light seems to filter through it. → A gem that is cool to the touch and hums gently. Strangely, no light seems to filter through it.
- **Charged Crystal (271898)**
  - `Description_lang`: A gem that hums gently and seems to emit a static charge. On it's own it emits a tiny amount of light and small flashes… → A gem that hums gently and seems to emit a static charge. On its own it emits a tiny amount of light and small flashes …
- **Volunteer's Lucky Seal (271904)**
  - `ItemLevel`: 33 → 38
  - `RequiredLevel`: 28 → 33
- **Enriched Seal (271905)**
  - `ItemLevel`: 33 → 38
  - `RequiredLevel`: 28 → 33
- **Moist Crystal (271912)**
  - `Description_lang`: A gem that seems to collect condensation on the surface making it perpetually wet and hums gently.When turned in the li… → A gem that seems to collect condensation on the surface making it perpetually wet and hums gently. When turned in the l…
- **Dathrohan's Correspondence (272025)**
  - `Description_lang`: Saidan Dathrohan's correspondance before and during the third war → Saidan Dathrohan's correspondence before and during the third war
  - `Display_lang`: Dathrohan's Correspondance → Dathrohan's Correspondence
- **Darkspear Voodoo Seal (272059)**
  - `ItemLevel`: 33 → 38
  - `RequiredLevel`: 28 → 33
- **Relentless Raider's Seal (272062)**
  - `ItemLevel`: 33 → 38
  - `RequiredLevel`: 28 → 33
- **Slime Ward - Fel Ash Experimentation Notes (273002)**
  - `Description_lang`: Both runes and script dance across the surface of the page like spiders. Something about the this book feels sinister a… → Both runes and script dance across the surface of the page like spiders. Something about this book feels sinister and u…
- **Blueprint: Iron Oven (273115)**
  - `Description_lang`: Teaches you how to place a Baker's Oven at a campsite. → Teaches you how to place a Iron Oven at a campsite.
  - `Display_lang`: Blueprint: Baker's Oven → Blueprint: Iron Oven
- **Disease Ward - Fel Ash Experimentation Notes (273308)**
  - `Description_lang`: Both runes and script dance across the surface of the page like spiders. Something about the this book feels sinister a… → Both runes and script dance across the surface of the page like spiders. Something about this book feels sinister and u…
- **Vessel Ward - Fel Ash Experimentation Notes (273309)**
  - `Description_lang`: Both runes and script dance across the surface of the page like spiders. Something about the this book feels sinister a… → Both runes and script dance across the surface of the page like spiders. Something about this book feels sinister and u…
- **Alchemy Ward - Fel Ash Experimentation Notes (273310)**
  - `Description_lang`: Both runes and script dance across the surface of the page like spiders. Something about the this book feels sinister a… → Both runes and script dance across the surface of the page like spiders. Something about this book feels sinister and u…
  - `Display_lang`: Alchemey Ward - Fel Ash Experimentation Notes → Alchemy Ward - Fel Ash Experimentation Notes
- **Chef's Knife (273636)**
  - `SellPrice`: 16 → 60
  - `BuyPrice`: 82 → 300
  - `Flags_0`: 1024 → 1088
  - `Flags_1`: 24580 → 8196
- **Bloody Parchment (273659)**
  - `Description_lang`: The letter makes mention of  'The Pact' and a 'Wild King'... what could this mean? → The letter makes mention of 'The Pact' and a 'Wild King'... what could this mean?
- **Leather-bound Flask (274373)**
  - `Description_lang`: The pure hyjal springwater shimmers with pinecone resin. → The pure Hyjal springwater shimmers with pinecone resin.
- **Fel Ash Experimentation Notes (274396)**
  - `Description_lang`: Both runes and script dance across the surface of the page like spiders. Something about the this note feels sinister a… → Both runes and script dance across the surface of the page like spiders. Something about this note feels sinister and u…
- **Souvenir Sea Shell (274749)**
  - `Display_lang`: Souvenier Sea Shell → Souvenir Sea Shell
- **Crystallized Shard (276158)**
  - `Display_lang`: Crystalized Shard → Crystallized Shard
- **Corrupted Cat Figurine (276909)**
  - `Description_lang`: This once beautiful figurine has been stained by the felbood. It looks like it belonged to a set. → This once beautiful figurine has been stained by the felblood. It looks like it belonged to a set.
- **Bloodtalon Matriarch Eggs (277128)**
  - `Display_lang`: Bloodtalon Martriarch Eggs → Bloodtalon Matriarch Eggs
- **Artifact Seeker's Pendant (277202)**
  - `StatPercentEditor_0`: 5259 → 7368
  - `StatPercentEditor_1`: 5259 → 4736
  - `StatPercentEditor_2`: 5258 → 4210
- **Scholarly Pendant (277203)**
  - `StatPercentEditor_0`: 7601 → 6666
  - `StatPercentEditor_1`: 5066 → 5000
  - `ItemLevel`: 25 → 23
  - `OverallQualityID`: 3 → 2
- **Erudite's Amulet (277204)**
  - `StatPercentEditor_0`: 7601 → 6666
  - `StatPercentEditor_1`: 5066 → 5000
  - `ItemLevel`: 25 → 23
  - `OverallQualityID`: 3 → 2
- **Truthseeker's Bow (277254)**
  - `ItemLevel`: 48 → 45
- **Crest of Elucidation (277258)**
  - `StatPercentEditor_1`: 3553 → 7857
  - `StatPercentEditor_2`: 0 → 2857
  - `StatModifier_bonusStat_1`: 5 → 41
  - `StatModifier_bonusStat_2`: -1 → 42
  - `ItemLevel`: 50 → 45
- **Researcher's Night Light (277260)**
  - `StatPercentEditor_1`: 3553 → 5000
  - `StatModifier_bonusStat_1`: 5 → 85
  - `ItemLevel`: 50 → 45
- **Scroll of Greater Cryoblast (277499)**
  - `Material`: 2 → 7
- **Fel Tainted Journal (277533)**
  - `Display_lang`: Fel Tained Journal → Fel Tainted Journal
- **Plans: Rough Copper Chain Boots (277673)**
  - `Description_lang`: Teaches you how to make a Rough Copper Chain Boots. → Teaches you how to make Rough Copper Chain Boots.
- **Ironwood Blade (279259)**
  - `Flags_0`: 0 → 524288
- **Greenhammer (279261)**
  - `LimitCategory`: 712 → 0
  - `Flags_0`: 0 → 524288
- **Faction Banner (279972)**
  - `AllowableRace_0`: -1 → 1309324210
  - `AllowableRace_1`: -1 → -1440044374
- **Faction Banner (279973)**
  - `AllowableRace_0`: -1 → -1321907123
  - `AllowableRace_1`: -1 → 1427461461
- **Abominable Head (280438)**
  - `RequiredLevel`: 0 → 16
- **Rage of the Storm (280604)**
  - `StatModifier_bonusStat_0`: 4 → 5
- **Rabbit Crate (Arctic) (280797)**
  - `Display_lang`: Rabbit Crate (Artic) → Rabbit Crate (Arctic)
- **Blackrock Supplies (280839)**
  - `Display_lang`: Stolen Supplies → Blackrock Supplies
- **Spiked Collar (280911)**
  - `Stackable`: 10 → 5
  - `MaxCount`: 10 → 5
- **Torn Page (281347)**
  - `PageID`: 0 → 9258
- **Field Researcher's Loop (281634)**
  - `StatPercentEditor_0`: 5259 → 6363
  - `StatPercentEditor_1`: 5259 → 6363
  - `StatPercentEditor_2`: 5259 → 0
  - `StatModifier_bonusStat_2`: 4 → -1
  - `ItemLevel`: 40 → 35
  - `AllowableClass`: 8 → -1
- **Philanthropist's Ring (281635)**
  - `StatPercentEditor_1`: 8017 → 9090
  - `ItemLevel`: 40 → 35
- **Museum Keeper's Chain (281636)**
  - `StatPercentEditor_0`: 5259 → 5060
  - `StatPercentEditor_1`: 5259 → 5060
  - `StatPercentEditor_2`: 5258 → 5903
- **Antique Bulwark (281637)**
  - `StatPercentEditor_0`: 8425 → 6666
  - `StatPercentEditor_1`: 5330 → 4444
- **Alleria's Silver Coin (286265)**
  - `Description_lang`: May my sisters realize their full potential, the name Windrunner known as result of their deeds. → May my sisters realize their full potential, the name Windrunner known as a result of their deeds.
- **Arthas' Gold Coin (286281)**
  - `Description_lang`: Already, I've a kingdom in my prospects, a land to rule. What to ask for?  Perhaps a frozen scone... → Already, I've a kingdom in my prospects, a land to rule. What to ask for? Perhaps a frozen scone...
- **Zarla Ober's Gold Coin (286302)**
  - `Description_lang`: The amount of coins shining in the pool.. Maybe no one will notice if I take just one. → The amount of coins shining in the pool. Maybe no one will notice if I take just one.
- **Attumen's Copper Coin (286308)**
  - `Description_lang`: Can I have a more comfortable saddle?  My hindquarters ache. → Can I have a more comfortable saddle? My hindquarters ache.
- **Elling Trias' Copper Coin (286310)**
  - `Description_lang`: Being a rogue is hard work.  Someday I hope to pursue my life's one true passion... → Being a rogue is hard work. Someday I hope to pursue my life's one true passion...
- **Rhonin's Gold Coin (286327)**
  - `Description_lang`: Here you go Nozdormu. What was I supposed to do after this? → Here you go, Nozdormu. What was I supposed to do after this?
- **Elaadrin Evengale's Silver Coin (286328)**
  - `Description_lang`: How do I prove they copied us with this fountain. → How do I prove they copied us with this fountain?

## ItemXItemEffect

7 added, 0 removed, 0 changed.

### $\color{#3FB950}\textbf{Added}$

- (170384)
- (170385)
- (170386)
- (170387)
- (170498)
- (170500)
- (170677)

## Map

0 added, 1 removed, 1 changed.

### $\color{#F85149}\textbf{Removed}$

- (3002)

### $\color{#D29922}\textbf{Changed}$

- **(2997)**
  - `MapDescription0_lang`: Off the coast of Kalimdor is the ceremonial islands of the Darkspear tribe. → Off the coast of Kalimdor are the ceremonial islands of the Darkspear tribe.
  - `MapDescription1_lang`: Off the coast of Kalimdor is the ceremonial islands of the Darkspear tribe. → Off the coast of Kalimdor are the ceremonial islands of the Darkspear tribe.
  - `PvpLongDescription_lang`: - Capture and hold objectives - Capture the Darkspear relic - Earn 1500 resources → - Capture and hold objectives - Capture the Darkspear Islands Flag - Earn 2000 resources

## Spell

37 added, 15 removed, 0 changed, 2 mass-changed column(s).

### $\color{#3FB950}\textbf{Added}$

- Holy Forgefire (1322218)
- Corpse Chopper (1322303)
- Crystal Breaker (1322304)
- Corpse Chopper (1322305)
- Recently Siphoned the Grave (1322311)
- Cookie's Stirring Rod (1322312)
- Twilight Empowerment (1322318)
- Yay (1322587)
- Shifting Power (1322605)
- Improved Shifting Power (1322670)
- Lunch for Kyle (1323075)
- Shark Attack (1323184)
- War Stomp (1323209)
- Summon Skeletal Servant (1322054)
- [DNT]Avatar of Hakkar Player Checker (1322065)
- [DNT]Avatar of Hakkar Player Checker Ping (1322067)
- Shadow Channeling (1322287)
- Firebolt (1322295)
- Ritual Circle (1322296)
- (DNT) Mod Armor No Mods (1322297)
- (DNT) Mod Resistance by Bonus Defense (1322299)
- Rule of Rage (DND) (1322574)
- Capturing (1322629)
- Dummy (1322901)
- Dummy (1322935)
- Rain of Arrows (1323240)
- Rain of Arrows (1323243)
- Shoot (1323246)
- Enrage (1323289)
- Revelation (1323377)
- Tapped (1323390)
- Revelation (1323392)
- Revelation (1323400)
- Revelation (1323410)
- Revelation (1323418)
- Revelation (1323419)
- Totemic Recall (1323420)

### $\color{#F85149}\textbf{Removed}$

- Create Test Ring Test (405667)
- Roast Beast (1249805)
- Disease Cloud (1321936)
- Disease Cloud (1321937)
- Knockdown (1321938)
- Immolation (1321998)
- Immolation (1321999)
- Flame Buffet (1322000)
- Flame Buffet (1322001)
- Prepare Fish (1292245)
- Prepare Fish (1292246)
- Gargoyle Strike (1321952)
- Move to Highest Threat Target Primer (1321960)
- Infernal (1322004)
- Infernal (1322005)

### $\color{#A371F7}\textbf{Mass changes}$

- `Description_lang` changed in 661 rows (e.g. Shapeshift into cat form, inc… → Shapeshift into Cat Form, inc…, Transforms the druid into a t… → Shapeshift into Travel Form, …, Shapeshift into aquatic form,… → Shapeshift into Aquatic Form,…)
- `AuraDescription_lang` changed in 185 rows (e.g. Immunity to Polymorph effects… → Immunity to Polymorph effects…, Chance to be hit by melee and… → Chance to be hit by melee and…, Immune to Polymorph effects. … → Immune to Polymorph effects. …)

## SpellAuraOptions

14 added, 9 removed, 6 changed.

### $\color{#3FB950}\textbf{Added}$

- (247340)
- (248440)
- (248462)
- (248463)
- (248464)
- (248465)
- (248466)
- (248467)
- (248540)
- (248543)
- (248545)
- (248546)
- (248548)
- (248549)

### $\color{#F85149}\textbf{Removed}$

- (115921)
- (119851)
- (122966)
- (123473)
- (125526)
- (128798)
- (247868)
- (248422)
- (248423)

### $\color{#D29922}\textbf{Changed}$

- **(124240)**
  - `ProcCharges`: 4 → 3
- **(124699)**
  - `ProcChance`: 60 → 100
- **(247172)**
  - `ProcChance`: 101 → 10
- **(247243)**
  - `ProcCategoryRecovery`: 0 → 3000
- **(248392)**
  - `ProcTypeMask_0`: -2146784600 → 0
  - `ProcTypeMask_1`: 0 → 4
- **(248393)**
  - `ProcCategoryRecovery`: 0 → 2000
  - `ProcChance`: 10 → 100
  - `ProcTypeMask_0`: 17408 → 2114560

## SpellCooldowns

6 added, 6 removed, 0 changed.

### $\color{#3FB950}\textbf{Added}$

- (101888)
- (101889)
- (101892)
- (101893)
- (101953)
- (102004)

### $\color{#F85149}\textbf{Removed}$

- (53522)
- (53523)
- (53540)
- (55712)
- (55801)
- (101872)

## SpellEffect

64 added, 20 removed, 72 changed.

### $\color{#3FB950}\textbf{Added}$

- (1357678)
- (1357699)
- (1357715)
- (1357717)
- (1357910)
- (1357911)
- (1357984)
- (1357988)
- (1357989)
- (1357990)
- (1357991)
- (1357998)
- (1357999)
- (1358000)
- (1358004)
- (1358011)
- (1358012)
- (1358013)
- (1358014)
- (1358015)
- (1358016)
- (1358028)
- (1358029)
- (1358037)
- (1358385)
- (1358414)
- (1358438)
- (1358439)
- (1358440)
- (1358457)
- (1358458)
- (1358499)
- (1358554)
- (1358923)
- (1358978)
- (1359152)
- (1359171)
- (1359172)
- (1359378)
- (1359430)
- (1359486)
- (1359489)
- (1359492)
- (1359527)
- (1359528)
- (1359529)
- (1359531)
- (1359532)
- (1359533)
- (1359534)
- (1359568)
- (1359569)
- (1359673)
- (1359709)
- (1359729)
- (1359732)
- (1359742)
- (1359753)
- (1359777)
- (1359778)
- (1359779)
- (1359780)
- (1359782)
- (1359783)

### $\color{#F85149}\textbf{Removed}$

- (1054072)
- (1253572)
- (1312135)
- (1312136)
- (1341130)
- (1345676)
- (1357509)
- (1357510)
- (1357515)
- (1357535)
- (1357549)
- (1357622)
- (1357623)
- (1357624)
- (1357625)
- (1357628)
- (1357629)
- (1357630)
- (1357632)
- (1357633)

### $\color{#D29922}\textbf{Changed}$

- **(679272)**
  - `EffectBasePointsF`: -140 → -280
- **(679605)**
  - `EffectRadiusIndex_0`: 10 → 9
  - `ImplicitTarget_0`: 15 → 16
- **(687318)**
  - `EffectMiscValue_0`: 111148 → 109515
- **(688427)**
  - `EffectBasePointsF`: 1 → 0
- **(690887)**
  - `EffectBasePointsF`: -280 → -560
- **(691187)**
  - `EffectBasePointsF`: -405 → -810
- **(691709)**
  - `EffectMiscValue_0`: 0 → 2
- **(692327)**
  - `EffectSpellClassMask_0`: -1877999613 → -1743781885
  - `EffectSpellClassMask_1`: 266240 → 4096
  - `EffectSpellClassMask_3`: 1073741824 → 0
- **(692357)**
  - `EffectSpellClassMask_0`: -615203184 → -638304624
- **(692439)**
  - `EffectAura`: 42 → 4
- **(697659)**
  - `EffectBasePointsF`: 20 → 30
- **(698885)**
  - `EffectBasePointsF`: 20 → 30
- **(699486)**
  - `EffectBasePointsF`: 20 → 30
- **(699721)**
  - `EffectRealPointsPerLevel`: 0.91000002623 → 0.5
  - `EffectBasePointsF`: 100 → 60
- **(701690)**
  - `EffectRealPointsPerLevel`: 0.02999999933 → 0.01999999955
  - `EffectBasePointsF`: 56 → 34
- **(702216)**
  - `EffectRealPointsPerLevel`: 0.69999998808 → 0.40000000596
  - `EffectBasePointsF`: 136 → 82
- **(702274)**
  - `EffectRealPointsPerLevel`: 1 → 0.60000002384
  - `EffectBasePointsF`: 9 → 5
- **(705014)**
  - `EffectSpellClassMask_1`: 64 → 0
- **(705694)**
  - `EffectBasePointsF`: 1 → 0
- **(705722)**
  - `EffectBasePointsF`: 1 → 0
- **(1098623)**
  - `EffectAura`: 80 → 137
  - `EffectMiscValue_0`: -1 → 0
- **(1133944)**
  - `EffectRealPointsPerLevel`: 0 → 8
  - `EffectBasePointsF`: 215 → 50
- **(1242609)**
  - `EffectAura`: 379 → 110
  - `EffectMiscValue_0`: 4 → 0
- **(1251880)**
  - `EffectAura`: 80 → 137
  - `EffectMiscValue_0`: 4 → 0
- **(1251972)**
  - `EffectTriggerSpell`: 1248808 → 0
  - `Variance`: 0.5 → 0
  - `EffectBasePointsF`: 100 → 0
- **(1251976)**
  - `EffectAura`: 290 → 107
  - `EffectMiscValue_0`: 0 → 7
  - `EffectSpellClassMask_0`: 0 → 547494642
  - `EffectSpellClassMask_3`: 0 → 8
- **(1269066)**
  - `EffectSpellClassMask_0`: 68290334 → 100794910
  - `EffectSpellClassMask_1`: 2099464 → 2097408
- **(1269067)**
  - `EffectSpellClassMask_0`: 68290334 → 100794910
  - `EffectSpellClassMask_1`: 2318 → 2097408
- **(1269068)**
  - `EffectSpellClassMask_0`: 710934758 → 1784679630
  - `EffectSpellClassMask_1`: 4 → 5
  - `EffectSpellClassMask_2`: 0 → 1
- **(1269069)**
  - `EffectSpellClassMask_0`: 710934758 → 1784679630
  - `EffectSpellClassMask_1`: 4 → 5
  - `EffectSpellClassMask_2`: 0 → 1
- **(1269070)**
  - `EffectAura`: 108 → 4
  - `EffectMiscValue_0`: 22 → 0
  - `EffectSpellClassMask_0`: 32 → 0
- **(1269071)**
  - `EffectAura`: 108 → 4
  - `EffectMiscValue_0`: 22 → 0
  - `EffectSpellClassMask_0`: 1048832 → 0
- **(1269077)**
  - `EffectSpellClassMask_0`: 545397431 → 549591799
- **(1269078)**
  - `EffectSpellClassMask_0`: 545397431 → 551688947
  - `EffectSpellClassMask_3`: 0 → 8
- **(1269079)**
  - `EffectSpellClassMask_0`: 1 → 0
  - `EffectSpellClassMask_1`: 4096 → 0
- **(1269085)**
  - `EffectSpellClassMask_0`: 542127 → 541165
  - `EffectSpellClassMask_1`: 8388994 → 8650880
- **(1269086)**
  - `EffectSpellClassMask_0`: 542127 → 524773
  - `EffectSpellClassMask_1`: 8388994 → 8388736
- **(1269087)**
  - `EffectSpellClassMask_0`: 17422 → 16392
  - `EffectSpellClassMask_1`: 258 → 262144
- **(1269092)**
  - `EffectSpellClassMask_0`: 183811792 → 150224528
  - `EffectSpellClassMask_1`: 8486916 → 8388614
  - `EffectSpellClassMask_2`: 64 → 0
- **(1269093)**
  - `EffectSpellClassMask_0`: 183811792 → 150224528
  - `EffectSpellClassMask_1`: 8486916 → 8486918
  - `EffectSpellClassMask_2`: 64 → 0
- **(1269094)**
  - `EffectSpellClassMask_0`: 43024448 → 10485760
  - `EffectSpellClassMask_1`: 8454144 → 98304
  - `EffectSpellClassMask_2`: 64 → 0
- **(1282528)**
  - `EffectSpellClassMask_0`: 1 → 268435457
- **(1287660)**
  - `Effect`: 90 → 3
  - `EffectMiscValue_0`: 257964 → 0
  - `EffectRadiusIndex_0`: 12 → 0
  - `ImplicitTarget_0`: 34 → 25
- **(1303714)**
  - `EffectAura`: 4 → 42
  - `EffectRealPointsPerLevel`: 1 → 0
  - `EffectTriggerSpell`: 0 → 1322318
- **(1303935)**
  - `EffectAura`: 89 → 0
  - `Effect`: 6 → 165
  - `EffectAuraPeriod`: 2000 → 0
- **(1307812)**
  - `EffectBonusCoefficient`: 0.20000000298 → 0
  - `EffectBasePointsF`: 30 → 35
- **(1308696)**
  - `EffectBasePointsF`: -15 → -25
- **(1310233)**
  - `EffectBasePointsF`: -3000 → -1000
  - `EffectSpellClassMask_1`: 0 → -2147483648
  - `EffectSpellClassMask_2`: 2048 → 0
- **(1311016)**
  - `Variance`: 0.66666668653 → 0
  - `EffectBasePointsF`: 3 → 0
- **(1311019)**
  - `Variance`: 0.66666668653 → 0
  - `EffectBasePointsF`: 3 → 7
- **(1312312)**
  - `Effect`: 206 → 359
  - `EffectMiscValue_0`: 0 → 209
- **(1315028)**
  - `EffectAura`: 4 → 54
  - `EffectBasePointsF`: 5 → 10
- **(1324199)**
  - `EffectAura`: 80 → 137
  - `EffectMiscValue_0`: 4 → 0
- **(1324968)**
  - `EffectBasePointsF`: 18 → 35
- **(1326284)**
  - `EffectBasePointsF`: -3000 → -1000
  - `EffectSpellClassMask_1`: 0 → -2147483648
  - `EffectSpellClassMask_2`: 2048 → 0
- **(1327864)**
  - `EffectRealPointsPerLevel`: 0 → 12
  - `EffectBasePointsF`: 755 → 400
- **(1334034)**
  - `EffectBasePointsF`: -10 → -2
- **(1334040)**
  - `EffectAura`: 55 → 4
  - `EffectBasePointsF`: 3 → 5
- **(1334043)**
  - `EffectBasePointsF`: -15 → -3
- **(1334049)**
  - `EffectBasePointsF`: 5 → 1
- **(1338267)**
  - `EffectBasePointsF`: 4 → 2
- **(1338833)**
  - `EffectBasePointsF`: 40 → 20
- **(1339126)**
  - `EffectSpellClassMask_0`: 33554432 → 0
- **(1348592)**
  - `EffectBasePointsF`: 2 → -2
- **(1348595)**
  - `EffectBasePointsF`: 4 → -4
- **(1350103)**
  - `EffectBasePointsF`: 20 → 22
- **(1350104)**
  - `EffectTriggerSpell`: 1309323 → 1317040
- **(1350514)**
  - `EffectBasePointsF`: 3 → -3
- **(1350515)**
  - `EffectBasePointsF`: 7 → -7
- **(1356873)**
  - `EffectBasePointsF`: 40 → 20
- **(1356918)**
  - `ImplicitTarget_0`: 6 → 21
- **(1356919)**
  - `EffectBasePointsF`: 0 → 100

## SpellMisc

37 added, 15 removed, 92 changed, 1 mass-changed column(s).

### $\color{#3FB950}\textbf{Added}$

- (867729)
- (867740)
- (867742)
- (867874)
- (867942)
- (867950)
- (867951)
- (867952)
- (867954)
- (867957)
- (867958)
- (867959)
- (867965)
- (867966)
- (867972)
- (868230)
- (868243)
- (868264)
- (868287)
- (868327)
- (868562)
- (868596)
- (868740)
- (868851)
- (868876)
- (868907)
- (868910)
- (868913)
- (868950)
- (869038)
- (869051)
- (869053)
- (869061)
- (869071)
- (869082)
- (869083)
- (869084)

### $\color{#F85149}\textbf{Removed}$

- (664530)
- (804038)
- (839683)
- (839684)
- (867618)
- (867619)
- (867620)
- (867634)
- (867642)
- (867680)
- (867681)
- (867682)
- (867683)
- (867686)
- (867687)

### $\color{#D29922}\textbf{Changed}$

- **(28061)**
  - `Attributes_13`: 0 → 32
- **(28062)**
  - `Attributes_13`: 0 → 32
- **(28065)**
  - `Attributes_13`: 0 → 32
- **(314411)**
  - `Attributes_6`: 0 → 8388608
- **(315106)**
  - `Attributes_6`: 0 → 8388608
- **(315545)**
  - `Attributes_8`: 0 → 512
- **(315680)**
  - `Attributes_16`: 0 → 16
- **(316193)**
  - `Attributes_1`: 134480160 → 134481184
- **(318256)**
  - `DurationIndex`: 21 → 0
- **(318815)**
  - `Attributes_6`: 0 → 8388608
- **(319015)**
  - `Attributes_16`: 0 → 16
- **(319117)**
  - `Attributes_6`: 0 → 8388608
- **(319142)**
  - `Attributes_1`: 134480160 → 134481184
- **(319191)**
  - `Attributes_6`: 0 → 8388608
- **(319890)**
  - `Attributes_2`: 541065216 → 4194304
  - `Attributes_8`: 0 → 512
- **(320157)**
  - `Attributes_16`: 0 → 16
- **(320564)**
  - `Attributes_16`: 0 → 16
- **(320766)**
  - `Attributes_6`: 0 → 8388608
- **(320813)**
  - `Attributes_1`: 138412544 → 134218240
  - `Attributes_4`: 8 → 1048584
- **(321010)**
  - `Attributes_6`: 0 → 8388608
- **(321057)**
  - `DurationIndex`: 4 → 5
- **(321312)**
  - `Attributes_1`: 138412544 → 134218240
  - `Attributes_4`: 8 → 1048584
- **(321534)**
  - `Attributes_1`: 138412544 → 134218240
  - `Attributes_4`: 8 → 1048584
- **(321562)**
  - `Attributes_16`: 0 → 16
- **(321744)**
  - `Attributes_16`: 0 → 16
- **(321754)**
  - `Attributes_16`: 0 → 16
- **(321878)**
  - `RangeIndex`: 12 → 6
- **(321963)**
  - `Attributes_16`: 0 → 16
- **(322119)**
  - `Attributes_3`: 128 → 262272
- **(322200)**
  - `Attributes_16`: 0 → 16
- **(322490)**
  - `Attributes_6`: 0 → 8388608
- **(322540)**
  - `Attributes_1`: 138412544 → 134218240
  - `Attributes_4`: 8 → 1048584
- **(322606)**
  - `Attributes_6`: 0 → 8388608
- **(323324)**
  - `Attributes_6`: 0 → 8388608
- **(323325)**
  - `Attributes_6`: 0 → 8388608
- **(323414)**
  - `Attributes_6`: 0 → 8388608
- **(323543)**
  - `Attributes_1`: 138412544 → 134218240
  - `Attributes_4`: 8 → 1048584
- **(324065)**
  - `Attributes_1`: 134480160 → 134481184
- **(324196)**
  - `Attributes_2`: 541065216 → 4194304
  - `Attributes_8`: 0 → 512
- **(324640)**
  - `Attributes_16`: 0 → 16
- **(325049)**
  - `Attributes_3`: 0 → 131072
- **(325910)**
  - `Attributes_3`: 128 → 262272
- **(326149)**
  - `Attributes_2`: 541065216 → 4194304
  - `Attributes_8`: 0 → 512
- **(326478)**
  - `Attributes_1`: 0 → 1024
  - `Attributes_5`: 0 → 33554432
- **(327203)**
  - `Attributes_0`: 327936 → 328064
  - `Attributes_3`: 0 → 1048576
  - `DurationIndex`: 0 → 21
- **(327609)**
  - `Attributes_8`: 0 → 512
- **(328555)**
  - `Attributes_8`: 0 → 512
- **(328556)**
  - `Attributes_8`: 0 → 512
- **(328762)**
  - `Attributes_8`: 0 → 512
- **(328770)**
  - `Attributes_8`: 0 → 512
- **(331343)**
  - `Attributes_3`: 1073741952 → 1074004096
- **(732519)**
  - `Attributes_11`: 0 → 4
- **(803309)**
  - `CastingTimeIndex`: 1 → 14
- **(803314)**
  - `CastingTimeIndex`: 1 → 14
- **(803316)**
  - `CastingTimeIndex`: 1 → 14
- **(824914)**
  - `CastingTimeIndex`: 1 → 19
- **(827902)**
  - `Attributes_13`: 1 → 33554433
- **(828250)**
  - `Attributes_2`: 1073741824 → 1073741828
  - `Attributes_5`: 1024 → 67109888
- **(828251)**
  - `Attributes_2`: 1073741824 → 1073741828
  - `Attributes_5`: 1024 → 67109888
- **(828252)**
  - `Attributes_2`: 1073741824 → 1073741828
  - `Attributes_5`: 1024 → 67109888
- **(828253)**
  - `Attributes_2`: 1073741824 → 1073741828
  - `Attributes_5`: 1024 → 67109888
- **(828254)**
  - `Attributes_2`: 1073741824 → 1073741828
  - `Attributes_5`: 1024 → 67109888
- **(828258)**
  - `Attributes_2`: 1073741824 → 1073741828
  - `Attributes_5`: 1024 → 67109888
- **(834390)**
  - `Attributes_0`: 256 → 0
  - `Attributes_15`: 8192 → 0
  - `SchoolMask`: 1 → 32
- **(834525)**
  - `Attributes_0`: 218103808 → 220200960
  - `Attributes_3`: 65536 → 327680
  - `Attributes_7`: 0 → 25165824
  - `DurationIndex`: 21 → 0
- **(835673)**
  - `Attributes_2`: 0 → 4
- **(835674)**
  - `Attributes_2`: 0 → 4
- **(837197)**
  - `DurationIndex`: 31 → 9
- **(837709)**
  - `Attributes_2`: 268435456 → 268435460
- **(839768)**
  - `CastingTimeIndex`: 1 → 14
- **(841511)**
  - `Attributes_2`: 0 → 4
- **(841529)**
  - `Attributes_2`: 0 → 4
- **(841530)**
  - `Attributes_2`: 0 → 4
- **(841539)**
  - `Attributes_2`: 0 → 4
- **(841540)**
  - `Attributes_2`: 131072 → 131076
- **(841542)**
  - `Attributes_2`: 131072 → 131076
- **(841606)**
  - `Attributes_2`: 0 → 4
- **(841625)**
  - `Attributes_2`: 0 → 4
- **(841629)**
  - `Attributes_2`: 0 → 4
- **(841630)**
  - `Attributes_2`: 0 → 4
- **(841709)**
  - `Attributes_15`: 0 → 8192
- **(847344)**
  - `Attributes_1`: 0 → 136
- **(855655)**
  - `Attributes_3`: 0 → 65536
  - `Attributes_4`: 0 → 8388608
- **(855985)**
  - `RangeIndex`: 2 → 13
- **(856075)**
  - `Attributes_0`: 536871296 → 536871168
- **(857275)**
  - `DurationIndex`: 0 → 1
  - `RangeIndex`: 114 → 582
- **(857374)**
  - `DurationIndex`: 0 → 1
  - `RangeIndex`: 114 → 582
- **(857375)**
  - `DurationIndex`: 0 → 1
  - `RangeIndex`: 114 → 582
- **(866852)**
  - `Attributes_0`: 536870912 → -1610612736
  - `Attributes_1`: 0 → 2048
- **(867239)**
  - `Attributes_8`: 0 → 4096
  - `DurationIndex`: 8 → 1
- **(867268)**
  - `RangeIndex`: 37 → 6
- **(867269)**
  - `Attributes_0`: 448 → 65984

### $\color{#A371F7}\textbf{Mass changes}$

- `SpellIconFileDataID` changed in 51 rows (e.g. 136235 → 136243, 136235 → 136243, 136235 → 136243)

## SpellName

37 added, 15 removed, 25 changed.

### $\color{#3FB950}\textbf{Added}$

- [DNT]Avatar of Hakkar Player Checker (1322065)
- [DNT]Avatar of Hakkar Player Checker Ping (1322067)
- Holy Forgefire (1322218)
- (DNT) Mod Armor No Mods (1322297)
- (DNT) Mod Resistance by Bonus Defense (1322299)
- Corpse Chopper (1322303)
- Crystal Breaker (1322304)
- Recently Siphoned the Grave (1322311)
- Cookie's Stirring Rod (1322312)
- Yay (1322587)
- Shifting Power (1322605)
- Capturing (1322629)
- Improved Shifting Power (1322670)
- Lunch for Kyle (1323075)
- War Stomp (1323209)
- Firebolt (1322295)
- Enrage (1323289)
- Shoot (1323246)
- Shadow Channeling (1322287)
- Summon Skeletal Servant (1322054)
- Totemic Recall (1323420)
- Revelation (1323377)
- Revelation (1323392)
- Revelation (1323400)
- Revelation (1323410)
- Revelation (1323418)
- Revelation (1323419)
- Rain of Arrows (1323240)
- Rain of Arrows (1323243)
- Twilight Empowerment (1322318)
- Shark Attack (1323184)
- Tapped (1323390)
- Ritual Circle (1322296)
- Dummy (1322901)
- Dummy (1322935)
- Rule of Rage (DND) (1322574)
- Corpse Chopper (1322305)

### $\color{#F85149}\textbf{Removed}$

- Create Test Ring Test (405667)
- Roast Beast (1249805)
- Prepare Fish (1292245)
- Move to Highest Threat Target Primer (1321960)
- Infernal (1322004)
- Immolation (1321998)
- Immolation (1321999)
- Knockdown (1321938)
- Flame Buffet (1322000)
- Flame Buffet (1322001)
- Disease Cloud (1321936)
- Disease Cloud (1321937)
- Gargoyle Strike (1321952)
- Prepare Fish (1292246)
- Infernal (1322005)

### $\color{#D29922}\textbf{Changed}$

- **Palomino Stallion (471)**
  - `Name_lang`: Palamino Stallion → Palomino Stallion
- **Troll's Blood Elixir (3223)**
  - `Name_lang`: Regeneration → Troll's Blood Elixir
- **Major Troll's Blood Elixir (24361)**
  - `Name_lang`: Regeneration → Major Troll's Blood Elixir
- **Heating Up (400624)**
  - `Name_lang`: Hot Streak → Heating Up
- **Soul Harvest (437032)**
  - `Name_lang`: Soul Harvesting → Soul Harvest
- **Dormant Heart of the Mountain (1249114)**
  - `Name_lang`: Dormant  Heart of the Mountain → Dormant Heart of the Mountain
- **Sit A While... (1255950)**
  - `Name_lang`: Sit A While.. → Sit A While...
- **Flame Charged (1270478)**
  - `Name_lang`: Charged Lightning → Flame Charged
- **Mithril Lode (1272216)**
  - `Name_lang`: Mithil Lode → Mithril Lode
- **Twilight Empowerment (1286699)**
  - `Name_lang`: Twilight Ritual → Twilight Empowerment
- **Shifting Power Cooldown Reduction (1291059)**
  - `Name_lang`: Tiger's Fury Cooldown Reduction → Shifting Power Cooldown Reduction
- **Recently Embraced (1291816)**
  - `Name_lang`: Recently Siphoned the Grave → Recently Embraced
- **Spiritcaller Treads (1292972)**
  - `Name_lang`: Spiritcaller Boots → Spiritcaller Treads
- **Spiritcaller Boots (1299917)**
  - `Name_lang`: Spiritcaller Treads → Spiritcaller Boots
- **Heal Health 1.0 Coefficient Over Time (1300952)**
  - `Name_lang`: Heal Health 1.0 Coeffecient Over Time → Heal Health 1.0 Coefficient Over Time
- **1.60.0 - Item - Tier 1 - Druid - Feral 5P Bonus - Shifting … (1301247)**
  - `Name_lang`: 1.60.0 - Item - Tier 1 - Druid - Feral 5P Bonus - Tiger's Fury → 1.60.0 - Item - Tier 1 - Druid - Feral 5P Bonus - Shifting Power
- **Mischievous Zephyr (1301947)**
  - `Name_lang`: Mischevious Zephyr → Mischievous Zephyr
- **[DNT] Play Sound - Spawn Virulent Blood (1309588)**
  - `Name_lang`: [DNT] Play Sound - Spawn Virtulent Blood → [DNT] Play Sound - Spawn Virulent Blood
- **Rule of Rage (DND) (1313291)**
  - `Name_lang`: Dual Wield Specialization → Rule of Rage (DND)
- **Increase Strength 22 (1317038)**
  - `Name_lang`: Increase Strength 20 → Increase Strength 22
- **Lesser Troll's Blood Elixir (3222)**
  - `Name_lang`: Regeneration → Lesser Troll's Blood Elixir
- **Heating Up (400625)**
  - `Name_lang`: Hot Streak → Heating Up
- **First Aid Kit (1255255)**
  - `Name_lang`:  First Aid Kit → First Aid Kit
- **Sit A While... (1255951)**
  - `Name_lang`: Sit A While.. → Sit A While...
- **Sit A While... (1256875)**
  - `Name_lang`: Sit A While.. → Sit A While...

## SpellPower

1 added, 1 removed, 0 changed.

### $\color{#3FB950}\textbf{Added}$

- (314986)

### $\color{#F85149}\textbf{Removed}$

- (312962)

## SpellXSpellVisual

26 added, 12 removed, 29 changed.

### $\color{#3FB950}\textbf{Added}$

- (536167)
- (536246)
- (536252)
- (536255)
- (536259)
- (536260)
- (536261)
- (536263)
- (536267)
- (536268)
- (536270)
- (536440)
- (536449)
- (536498)
- (536736)
- (536835)
- (536858)
- (536862)
- (536892)
- (536958)
- (536964)
- (536966)
- (536970)
- (536976)
- (536977)
- (536978)

### $\color{#F85149}\textbf{Removed}$

- (383537)
- (492176)
- (516861)
- (516863)
- (536094)
- (536095)
- (536096)
- (536104)
- (536144)
- (536145)
- (536148)
- (536149)

### $\color{#D29922}\textbf{Changed}$

- **(419557)**
  - `SpellVisualID`: 41 → 263
- **(420050)**
  - `SpellVisualID`: 161 → 193557
- **(492066)**
  - `SpellVisualID`: 92 → 390
- **(506415)**
  - `SpellVisualID`: 215 → 174698
- **(519250)**
  - `SpellVisualID`: 4279 → 193585
- **(519579)**
  - `SpellVisualID`: 353 → 193581
- **(519600)**
  - `SpellVisualID`: 4279 → 193582
- **(523707)**
  - `SpellVisualID`: 4279 → 193557
- **(523709)**
  - `SpellVisualID`: 4279 → 193585
- **(523716)**
  - `SpellVisualID`: 4279 → 193585
- **(523747)**
  - `SpellVisualID`: 4279 → 193582
- **(523748)**
  - `SpellVisualID`: 4279 → 193582
- **(523749)**
  - `SpellVisualID`: 353 → 193581
- **(523750)**
  - `SpellVisualID`: 76 → 193557
- **(523755)**
  - `SpellVisualID`: 76 → 193557
- **(523756)**
  - `SpellVisualID`: 76 → 193557
- **(523759)**
  - `SpellVisualID`: 161 → 193565
- **(523761)**
  - `SpellVisualID`: 0 → 193587
- **(523763)**
  - `SpellVisualID`: 353 → 193581
- **(523764)**
  - `SpellVisualID`: 4279 → 193585
- **(523765)**
  - `SpellVisualID`: 4279 → 193582
- **(523766)**
  - `SpellVisualID`: 4279 → 193557
- **(523767)**
  - `SpellVisualID`: 4279 → 193557
- **(523768)**
  - `SpellVisualID`: 4279 → 193557
- **(523769)**
  - `SpellVisualID`: 140456 → 193578
- **(523770)**
  - `SpellVisualID`: 4279 → 193557
- **(523771)**
  - `SpellVisualID`: 4279 → 193585
- **(523772)**
  - `SpellVisualID`: 4279 → 193582
- **(528643)**
  - `SpellVisualID`: 0 → 193587

## TraitDefinition

2 added, 0 removed, 1 changed.

### $\color{#3FB950}\textbf{Added}$

- (145858)
- (145859)

### $\color{#D29922}\textbf{Changed}$

- **(134412)**
  - `SpellID`: 417046 → 1322605

## TraitNode

1 added, 0 removed, 4 changed.

### $\color{#3FB950}\textbf{Added}$

- (113563)

### $\color{#D29922}\textbf{Changed}$

- **(104945)**
  - `PosY`: 3930 → 3330
- **(104950)**
  - `PosX`: 5020 → 6820
- **(104951)**
  - `PosX`: 6820 → 5020
  - `PosY`: 4530 → 3930
- **(110298)**
  - `Flags`: 8 → 10

## TraitNodeEntry

2 added, 0 removed, 1 changed.

### $\color{#3FB950}\textbf{Added}$

- (141187)
- (141188)

### $\color{#D29922}\textbf{Changed}$

- **(129611)**
  - `MaxRanks`: 3 → 1
