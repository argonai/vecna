---
alias: Lyra
tags: Entity/Player-Character, Multiverse/D&D
cssclass: hcl, table, t-c, readable
hp: 86
ac:
modifier: INT
STR: 8
DEX: 16
CON: 14
INT: 20
WIS: 12
CHA: 8
LVL: 12
proficiency: 4
---
%%
Creator:: Argon
Universe:: Forgotten Realms
Campaign:: Vecna
Adventure_Diary:: 
%%
<i>**` dv= this.Creator`**
` dv= this.Universe`
` dv= this.Campaign`</i>

# Lyra
> (Description:: Lone Wanderer)

![[Artificer.jpg|locl+hs-med]] <i>[]()</i>

 ||
----|:---:|
**Class** | Artificer \| Armourer
**Level** | 12
**Race** | Astral Elf
**Alignment** | Neutral Good
**Background** | Astral Drifter

---
# Stats
HP | AC | Speed | Initiative |
:---:|:---:|:---:|:---:|
 `=this.hp` |14 + DEX max 2|35ft | `= floor((this.DEX - 10) / 2)`|

Hit Dice | Proficiency Bonus | Temp HP | 
:---:|:---:|:---:|
 d8|`="+" + this.proficiency`|0|

Senses | \# |
---|---|
**Passive Perception** |`= 10 + floor((this.WIS - 10) / 2)`|


|Advantage     |
| --- |
|  Stealth   |
|avoid/end charmed|


---
## Abilities
### Abilities
STR | DEX | CON | INT | WIS | CHA | |
:---:|:----:|:----:|:---:|:---:|:---:|---|
`= this.STR` | `= this.DEX` | `= this.CON` | `= this.INT` | `= this.WIS` | `= this.CHA` | **Stats** |
`= floor((this.STR - 10) / 2)` | `= floor((this.DEX - 10) / 2)` | `= floor((this.CON - 10) / 2)` | `= floor((this.INT - 10) / 2)` | `= floor((this.WIS - 10) / 2)` | `= floor((this.CHA - 10) / 2)` | **Modifier** |
`= floor((this.STR - 10) / 2)` | `= floor((this.DEX - 10) / 2)` | `= floor((this.CON - 10) / 2) +this.proficiency` | `= floor((this.INT - 10) / 2) + this.proficiency` | `= floor((this.WIS - 10) / 2)` | `= floor((this.CHA - 10) / 2)` | **Saving Throw** |


### Skills
\# | Skill | Ability | Proficient
:--:|-----|:------:|:-:|
`=floor((this.DEX -10) /2)`| Acrobatics | DEX |
`=floor((this.WIS -10) /2)`| Animal Handling | WIS |
`=floor((this.INT -10) /2) + this.proficiency`| Arcana | INT | X
`=floor((this.STR -10) /2)`| Athletics | STR |
`=floor((this.CHA -10) /2)`| Deception | CHA |
`=floor((this.INT -10) /2)`| History | INT |
`=floor((this.WIS -10) /2) + this.proficiency`| Insight | WIS | X
`=floor((this.CHA -10) /2)`| Intimidation | CHA |
`=floor((this.INT -10) /2) + this.proficiency`| Investigation | INT | X
`=floor((this.WIS -10) /2)`| Medicine | WIS |
`=floor((this.WIS -10) /2)`| Nature | WIS |
`=floor((this.WIS -10) /2) + this.proficiency`| Perception | WIS | X
`=floor((this.CHA -10) /2)`| Performance | CHA |
`=floor((this.CHA -10) /2)`| Persuasion | CHA |
`=floor((this.INT -10) /2)`| Religion | INT | X
`=floor((this.DEX -10) /2)`| Sleight of Hand | DEX |
`=floor((this.DEX -10) /2)`| Stealth | DEX |
`=floor((this.WIS -10) /2)`| Survival | WIS |

# Traits/Features

###### Background

- Proficiency in: `Insight`, `Religion`
- Gain 2 languages
- **Equipment:** A set of traveler's clothes, a diary, an ink pen, a bottle of ink, and a pouch containing 10gp
- Divine contact
	- Gain the magic initiate feat (cleric)
###### Magic initiate (cleric)
- Gain 2 cantrips and one 1st level spell (once per long rest), with wisdom modifier for cleric
###### Racial
- Gain 1 cantrip from `Dancing lights`, `light`,`sacred flame`
- Darkvision
- **Fey Ancestry**: You have advantage on saving throws you make to avoid or end the charmed condition on yourself
- **Keen senses**: Proficiency in `Perception` skill
- _**Starlight Step.**_ As a bonus action, you can magically teleport up to 30 feet to an unoccupied space you can see. You can use this trait a number of times equal to your proficiency bonus, and you regain all expended uses when you finish a long rest.
- **Astral Trance.**_ You don't need to sleep, and magic can't put you to sleep. You can finish a long rest in 4 hours if you spend those hours in a trancelike meditation, during which you remain conscious. Whenever you finish this trance, you gain proficiency in one skill of your choice and with one weapon or tool of your choice, selected from the _Player's Handbook_. You magically acquire these proficiencies by drawing them from shared elven memory and the experiences of entities on the Astral Plane, and you retain them until you finish your next long rest.
###### Armorer model
**Description of trait**

- [[Armor model]]
###### Extra attack
**Extra Attack**

- level 5 extra attack
###### Right tool for the job
**with thieves' tools or artisan's tools in hand, you can magically create one set of artisan's tools in an unoccupied space within 5 feet of you**

###### Tool Expertise
**at 6th level**
- proficiency bonus doubled for any ability check that uses proficiency with a tool
###### Flash of genius
- [[Flash of genius]]
###### Armor Modifications

- [[Armor Modifications]]
###### Spell-Storing Item

- [[Spell-Storing Item]]
###### Planar Wanderer

- [[Planar wanderer]]
`button-trait`

## Infusions
- Replicate magic item: Bag of holding
- Enhanced Arcane Focus (`+2` to attack rolls)
- Enhanced Defense (`+2` AC)
- Replicate magic item: Goggles of night -> maybe retrain at level 8 idk yet
- Spell-Refueling Ring
- Boots of the Winding Path
- Replicate magic item: Ring of Mind Shielding
- and another level 8 one idk yet
## Proficiencies
- Perception
- Insight
- Religion
- heavy armor
- Thieves tools
- Tinkers tools
- Smiths tools
- navigators tools
## Languages

- Common
- Elven
- Celestial
- Draconic maybe? idk not sure on the 4th
# Actions

###### Astral step

Type | To Hit | Hit | Reach | Targets |
---|:---:|:---:|---|:---:|
**==Bonus Action==** |||30ft|self|

`button-action`

## Spells
Max prepared: `=this.LVL + floor((this.INT - 10) / 2)`
- Spell save DC: `=8 + this.proficiency + floor((this.INT -10) /2)`
- Spell attack: `=this.proficiency + floor((this.INT -10) /2)`

|  Spell Slot Level   |1| 2 | 3 | 4     |   5   | 
| :---: | :---: | :---: | :---: | :---: | :---: |
|  Max  |   4   |   3   |   3   |   0   |   0   |
|current|   4   |   3   |   3   |   0   |   0   |


|      Name      | Level | Prepared | Conditional? | 
| :------------: | :---: |:-------: |:-----------: | 
| Dancing lights |   0   |          |              |     
|   Fire Bolt    |   0   |          |              |     
|    Mending     |   0   |          |              |     
|    Mage Hand     |   0   |          |              |   
|  Feather fall  |   1   |    X      |              |     
|  Detect Magic  |   1   |          | Y, long rest  |
| Absorb elements| 1     |     X     |              |
| False Life     | 1     |     x     |              |
| Magic Missile|1 |always | |
|thunderwave |1 |always | |
|mirror image |2 |always | |
|shatter |2 |always | |
| Heat metal| 2| x| |
| Invisibility |2 |x | |
| Lesser restoration |2 |x | |
|Faerie fire |1 | x| |
|Hypnotic pattern |3 |always | |
|lightning bolt |3 |always | |
| Dispel Magic|3 |x | |
|Protection from Energy |3 |x | |
 `button-spell`
 

# Equipment
CP | SP | EP | GP | PP |
:---:|:---:|:---:|:---:|:---:|
 |||||

- breastplate
- weapons idk

# Personality
###### Personality Traits

###### Ideals

###### Bonds

###### Flaws
# Appearance
Mechanical right arm
Tattoos all over body (voor armor magic te guiden)(denk phyre van vtmb2 see below)
![[tim-turner-bloodlines-2-phyre-01-1.jpg]]